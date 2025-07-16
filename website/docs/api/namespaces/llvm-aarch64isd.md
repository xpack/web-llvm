---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/aarch64isd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `AArch64ISD` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::AArch64ISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#a35ad1b8db0dfad0b69c9185c5fe24e19">...</a> }</td>
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

### NodeType {#a35ad1b8db0dfad0b69c9185c5fe24e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64ISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4e6bee589f2340d206010f5ac573708b"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WrapperLarge<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2bac403076acbbf971d9213895e49c4f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1506f6dab9103c66c2463fdded31a599"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_RVMARKER<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a95e48c51e4bf205ee490105e96350bbc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_BTI<a id="a35ad1b8db0dfad0b69c9185c5fe24e19adc79ed255f1706e125f05ac99a7341c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUTH_CALL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a3d25de941ed197fd00717b8024be207c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUTH_TC_RETURN<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a412d284f54ae9192c798a55786c47a7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUTH_CALL_RVMARKER<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a5517cf2a434cad2e6738d97d7bb2ecf1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COALESCER_BARRIER<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a047ba44fc28cdb42e45b171b4c871513"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VG_SAVE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a62f802d67d2c02b27555a6a737b955e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VG_RESTORE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9437be4c74c2ffdb174275e894a7c634"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMSTART<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a195e0238576389dfb91a8610b0e881d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMSTOP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19afa0e42f3d1f5a26bbf63a2e6ad1125ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RESTORE_ZA<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9fe0a6fd20f3c4e41ce8cecbde8d06e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RESTORE_ZT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a20a4c4ed442a366739eb8383950fa95e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SAVE_ZT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1748c672ccffe764a0bcc1fdfe16c9f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_ARM64EC_TO_X64<a id="a35ad1b8db0dfad0b69c9185c5fe24e19abf20adf1123111c49f741eb7c622210a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSDESC_CALLSEQ<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7053d31b0e2ad10afa17f7cf4332b40b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSDESC_AUTH_CALLSEQ<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af7afca2e2aa18122be22935ca2986ad5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADRP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa2e9d9d7c30818fd5ba551f8d3f0af34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADR<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a8ee06ddad96ab8a83a8513e4b5b49717"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDlow<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a64a83c4bc05c2caeca43015fda341f45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOADgot<a id="a35ad1b8db0dfad0b69c9185c5fe24e19adfb5f0cc680a060e5ca88e6e923d7183"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a42e72f1d9f66fe07d466b88a92920c22"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRCOND<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1dd8fc0bc13596b74da85b07a1ee5dd2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSEL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aeaea22b21177ff390559a1314dbf6947"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSINV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a87407f364bf7154debfe6a3008760e8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSNEG<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7749b66ee4fb30ffb40a30f5ef67b46f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSINC<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4a963d58bfd84cd339df4a7c57f8764e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">THREAD_POINTER<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad25be6e24e6b7104abbf0660c96589e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADC<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a570a73eb4f12ab7c7db1e81f280b363c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBC<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a3e0f0bc95b04d7de664c53bb98ec888b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PROBED_ALLOCA<a id="a35ad1b8db0dfad0b69c9185c5fe24e19adebd178a2fa65f2846ffe7985061b29c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABDS_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a41558bfb98ed3b2341959aa622dc2495"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABDU_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a45354be2b9fb574b34b8e38f6fbdf15a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FADD_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a79b964a205e8af1c7d40c1c7ea27cbeb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FDIV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a236b6f5a3fa768b9338169585b94d31e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMA_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a26eebef9ecd023d56a0d1f5659c6d56f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAX_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ae188e1a972d14cacb4b25aaa08c03fe7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXNM_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a06e995899e91ad228e89b42a733a9fc8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMIN_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1280ffb064fa61a167776c1714f8c115"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINNM_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a13039ac177cb3a515571da75980a41bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMUL_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a92132db91b6ec7e16a2d779bcc78385e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSUB_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a05dd7344f5aef716731bf261a43f218c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HADDS_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6ee732dc403611ea57c638c36abde989"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HADDU_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a0a20600fa3b8b7576ef1e7a16f0c8351"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUL_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ace3d70db16ae903ef91f4848cf3c7485"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHS_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4b0056cc9bd2dd8caad14edf30f960a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHU_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ab1654eebeb0da72fb694cad7ccc65836"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RHADDS_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a06dadc5c6f83ab133efe7d629fa0ce54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RHADDU_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a472127f5c49ffe5d374d554b6fb69252"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDIV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a69fe576c392c2f7ac25f62a38d5b5fc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHL_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a981ab95d67a836e9429e0e630293a927"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMAX_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6294f6cf79e63b6c350709ec5548e4e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMIN_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a14342e3e6a442d9ecebef1bae5f148a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRA_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1b64a920259075393097452bf7a007bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRL_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ab191c27a034857539bdaa17d122c8523"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UDIV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a71288440df1a68bef426732d7bfe6606"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMAX_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19afa3fac889eef5ac98a58aa3e11f21425"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMIN_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2fc0cbcf497c726edd333d5c9b0059a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BIC<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa13d0bd502aeac8ee6bfdb48903a47db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRAD_MERGE_OP1<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af4a48a9cc4383907e6a5d4bc64decb49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FABS_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a95126578449c59d8c182dcaec35c447c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCEIL_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6683923954c2104dc5500772c896891f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFLOOR_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6e4af32448924c58cb4a748a07864bea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNEARBYINT_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a685ce754a67e5cb56d1ef4093e6bf4fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNEG_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac13d816d2cb81731c25f88a756f78b75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRECPX_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ae20731453b229dcb3d378c282b68fe8e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRINT_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a43d0d40d03e4d03b0512a74db902be45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FROUND_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7c0da9722d4fb6b68c096e15b50bdbac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FROUNDEVEN_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4ce802350a14f6dd022c1d2dd87ec7b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSQRT_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac51e55480048612eede3cb1b18513b22"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FTRUNC_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9fb341bd2a710ddf055b0545efc68fc0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_ROUND_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2f6610e806b817c326a00ba86c3c39ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_EXTEND_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2af744ee43acb71c6a7b2792a4bc7e0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UINT_TO_FP_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a45614e13bc7af6996cacd17ad8a0e829"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SINT_TO_FP_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad72f64d0c5da384ad511761d2c9d43f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCVTX_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a80c54a646e51ad20866f14d0315cb0bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCVTZU_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ae42c77576ffd4957708a186a3d262a49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCVTZS_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a736e40ee8bf80d195036bf07fee64f8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIGN_EXTEND_INREG_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa560a9bc62116f8349176c8303745d0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZERO_EXTEND_INREG_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a74402c4f59142fad82137878d3d7b41e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABS_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a23379b95ff6faf89e6fad047bfb0ac1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NEG_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4e506b3ba0ddd0fc4041cdd4656dee37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac148c71eaed20be4b9ea132008532d8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a61ede97ea8fc84f9f11d6478d5d214a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19acdc788ad7d0ba7ecc3806c90b39b46ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADCS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ab98a7740ca34fec72ed6e3b38760b2b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBCS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a3ce7d4f224730b380e96d3e674ef269c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANDS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af36f36b0406330ead921ee1fb07de2cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CCMP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a82c3a82c9284fc5edff2a96dec362f57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CCMN<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a8deb26c97d84f931bdfb22aee53cebbc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCCMP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af6319439dbf716e743039fae1f75a4fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19adee98654dac93ffd21f1b9a129ec40e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9e0955df410f281dcdb5272e0ab9ce3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUPLANE8<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9e5cc09bf44571679cb7abc733bca21b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUPLANE16<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a63256211d7e9fcab596baa05d672db8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUPLANE32<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a5d3f342d733ac020d495e08094c201bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUPLANE64<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a626e899c69c3bfdbdbb094dd1c43bcc5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUPLANE128<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a5dea2cc356e551e1a38be00f441d0aed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVI<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a91a9a99c6c9977fcb422a33cedb64baa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVIshift<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7eec025fe97bc08e06bd04b45390cbbc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVIedit<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a56f30b92d605204b6d1e8f6736f5b45c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVImsl<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4298c4f3218b85d0754a31c3bc49dd38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMOV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a02e94d994c40b37bc4cf95827982393d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MVNIshift<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa4493521473b54b2568fb53290007104"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MVNImsl<a id="a35ad1b8db0dfad0b69c9185c5fe24e19afb280860060c7afbb8c931e5ab7fade9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BICi<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad6ab97e04848339b891365ffbcc1a0fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORRi<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6390897d4e079aa4d38ce5a5fd206b2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a21d1b00201e7e4cb249066ba0da2dd0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZIP1<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a574234144ef4f4e0115d0ef71a4efd80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZIP2<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a58511b67177595581d8f94facb3565fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UZP1<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4db23bc2ed0cc6a04a5c5d11bb45235f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UZP2<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a8aec775bf28196c442cf229cd43db2e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRN1<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a0ad2c68321ce87aa1ddfecd5db5620a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRN2<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a568bdb1eb9c9d07c9baa011b76a97b06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REV16<a id="a35ad1b8db0dfad0b69c9185c5fe24e19afae32e400e4bc01cc4673f48e856472d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REV32<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a44e0c654278b7245da534b69f2a290a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REV64<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a227cc47204e0e6af51133e52dbda3cad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a489b5bf6d9df2ae4dac6fce059b91bda"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPLICE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a210b1c8a403932ae546ed0b54128cdda"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19afb30ccc51f3686858a621b86f7171087"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLSHR<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4318caf60a3c8fb3a95e336e55457763"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VASHR<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a794f9f6bbb4013df844fce71137cb255"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SQSHL_I<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a73276e2beba77ee68e34de9f315b1dbb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UQSHL_I<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1deab4f18a0ec0ad579affbd7e5014dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SQSHLU_I<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a60ba9419992364c7fa566dbe626f91b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRSHR_I<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a22c1b5a92aba9ebf969a2f0235b9094c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">URSHR_I<a id="a35ad1b8db0dfad0b69c9185c5fe24e19abcf28dc2b8c571927124b7d94e5d0003"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">URSHR_I_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad8c685c545945926c56f84910d693898"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RSHRNB_I<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ae932a885fc5b27453c0530e88c4363b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSLI<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6d52931686af9b030c3cacbaf6708331"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRI<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a77430d9bb48aa864b70bdf019101c653"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMEQ<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4dfc32c20ebb97a98e406c25891d43c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMGE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac14d53a0ab8efc58263ff49cdc148af4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMGT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a28bb858be63e74941b0dcd6754d4c1f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMHI<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a28b81ba2a9cf5507fa21cf8341e1464f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMHS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a3a4c664b8c91eb49caa763b8b1076171"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMEQ<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ae57993c65e826491faff8e9f23ae2b94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMGE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a49584572cc555ded4c292404822bff1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMGT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a967eebc9c3cd77d0eddf5a53bda3e9ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMEQz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a253c60efdc75571e3bc8a58dd59becaf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMGEz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19adbfcc48de5a86d26dad681e5ab4ae73b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMGTz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ae0425e98d56c0083b583f1c5c714efd9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMLEz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af534c8b3b04bafe5c651e83dd0e83ef6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMLTz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a655dffaac8a992d3a612963917df3a63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMEQz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6ffcbbcb6e2951b44a89f04a89507a0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMGEz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7c644e021148062cb8186d06335d6c5b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMGTz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac7807ff6ae2440eb553822033f355ceb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMLEz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ae8eea7e42467af1888111d30aa1ffc9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMLTz<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac4260922a57a444b076d7680cdfaed32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCVTXN<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af6764ee93df826e9e67f63452a71cf13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a3390d467679dbd70e70dab4d9b89fdd7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a433c4e85025f39985b0e259cbf6f95ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDLV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aefb2386076002c124b7f4ecc8949ab91"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDLV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad112f423ccad26e1e2802c343f2c4d90"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDWT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af8d0dfb8e455b848875a7c0c87cbf851"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDWB<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a63c6337ab1a4098be3b02a65477f4c5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDWT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a83dc1c5f075d4e60118e4f1ca1bc2211"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDWB<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa0008165bc327e2a955dc5c33ebabe07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac2b2c785ce82d3782f292a3f9c2803e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDLP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19afda36640e88b2cdaef1df445d425b4a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDLP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a910ab243c66c6b15ec6db4768b7ea871"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UDOT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad96eeee7eab7d3e204af2c4cc2f3f28a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDOT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a602b2e270a81071e70ed8e06d9a715b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USDOT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa065b2acf229c3ebfd2af7b406a1abba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMINV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4e18ab55d69c25d612218c79b2085610"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMINV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a232dbb219a38c392daad50613ed1958e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMAXV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19acf7722d737cd958a55d56d66b37b1d0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMAXV<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1267fa1fba459cdc29d3291f477f2050"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1b407df6fb5622c341022152b51143e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a8368d7899d9217339a7e13fa3b7dc29e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMAXV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a226820ffad10c7875d1595c4863135fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMAXV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af368614239dc9c9128bd40dd311092b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMINV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7cab9fec71264bcc17aa00de077beb8f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMINV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad4727f1a13490b87d6c32c6bae2f0a3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac239596aafdd24f4101f56f205fe8e7f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EORV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19accc2b0352ba19606af1040c262293f09"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANDV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a233bc9367b23f2632c606088f60495a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CBZ<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac723fb32863b8b811d1f5e20a9d29b83"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CBNZ<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1ace695a3a0de6c36056b46791fdbd53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBZ<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa7d178f513996b738fea26d693c54e9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBNZ<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a31e3eddf628ce0ce1ab1624e731ee92b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TC_RETURN<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a0c096147ce35f351a1d0876af1c61501"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PREFETCH<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a710b6a09ffa3675a809f5560d18eb69b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SITOF<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6a32a9de2d68106613af27a4b5287b08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UITOF<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a107e9a4d70948139aa83c61738c101c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NVCAST<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a79512f79cb3d87ff14fd966207218ca5"></a></td>
<td class="doxyEnumItemDescription">Natural vector cast</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a0767ec4421b5ce84bb44f55969d6bea8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMULL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a088ad415e58a6fbb41ded8063e26bca6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMULL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ae9765ad45095f8a38ed3c365c8b8039a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMULL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a52bd6aa1392a591e5727dfd0d0e880ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRECPE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1e640c0d1dfbd984946b94c00bb08e42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRECPS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a584f88016830e5aed58404ed12f9b3e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRSQRTE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a3ad8163d9a9b7beace806694b5818168"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRSQRTS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2b59dada319a790ce5397dc4f8f02a8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUNPKHI<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad97a96707d208382bc33f77bbe9f9edd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUNPKLO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aca0f8df53ae7a68829ef5100ee8e133a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UUNPKHI<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a001f62f9f1eca066cc571960f52dc564"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UUNPKLO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa5f5eaa830a51e606a1a5749dea7f297"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLASTA_N<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aae0756f28d186b8713f960df55dc15b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLASTB_N<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af47f2fa02f0c000b2bb2713f4044ca55"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LASTA<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a71296993893d456da697d6a6e1c5c81b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LASTB<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aceba80367c90c9597740f44793a920a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4cd6678c26ce1ff7c0b0fab8b53707c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FADDA_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a672ec7ad6023bc5e6288c32f9d0b65a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FADDV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6efdb0e8c7f9876a8c7d5018948e0acd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a852f902347015cf35be53ca82a2d36eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXNMV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ade8465168b90801e75f1d747b3a869db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac69039ab54d0e64408e26e1e82dbf857"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINNMV_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a19b22d25633ae42d72b6b5e81baccca5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INSR<a id="a35ad1b8db0dfad0b69c9185c5fe24e19afe73a33ffb540dcae45e6c1fcf2ae167"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PTEST<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa32899962a2e5c6828f51d4183e4a3a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PTEST_ANY<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a55a346ec47012d131cd5068a91bfd35e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PTRUE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a83d0adb1d7f20d5a28003d08814e828a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTTZ_ELTS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19adc867f8bbfd796edbf20fd98de8e275b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITREVERSE_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a921a34e318b619f9c1973aa431fa2a7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSWAP_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2ca380dca8a9dd681808096bfdd62695"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REVH_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2b59bac19683a082e19a41340bfd7be0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REVW_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2b9e9a63926146d3d7d738850ac2e402"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTLZ_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7423f39e91075c53373cbc86362ddfb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTPOP_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6dc4d1d9ec66f752416aaa390a8dfdcb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUP_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aeeea721755ccf2b778a95b42ff8eb55c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INDEX_VECTOR<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a22122a4f0234fbe3b44057ba8d742148"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REINTERPRET_CAST<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6ee026906ebb33819f0452450d5bc4ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LS64_BUILD<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2af2841f081fa05b7343e785ac360633"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LS64_EXTRACT<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac22f87518ea997c68c74ba353797e025"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD1_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4e624e8cd76c2c489fc4a426687a5004"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD1S_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa98c8308b08e86e1e953f273207b0528"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDNF1_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac2a18bdf7917f763d050a81ab0762d91"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDNF1S_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6824f40cd97f2889787f803af41de828"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDFF1_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a866e96767e66fab323aa11daa967334d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDFF1S_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a8e7f7012e9567f0e2a466ff0fa38753b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD1RQ_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa3aa3cc3b66896fabee5c23c3f3c3f10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD1RO_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9fb6eadbeea30022b1d1e4eb86494c38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SVE_LD2_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a80d287373eef2e8f8a71d40c853afb75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SVE_LD3_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a740628cb5637cb8afc89ee4fe2cbaf7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SVE_LD4_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ab170dcf429997433e64e079c98657d75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a17e64b48fdac9928b6a0a092c5af7dc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac8f6f034b1c865aa8e77ccaebda32218"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1_UXTW_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19afa65635052abba7d2eb891eb24706af9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1_SXTW_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a74b91234a131f53b9a68a9ca4cd26c87"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1_UXTW_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad79b28d6740520761635d67c6c3c5dc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1_SXTW_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1e9d1eebf5bf9d4ff49ef45d7880e4ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1_IMM_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7923f428f833cc997e1f5ecf0993f90e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1Q_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a0bfe9e8819e5c1bfb6ab5515936a69ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1Q_INDEX_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a3521337d037a29d43555c7ea1b96f75d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1S_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9be68046aad6ca20ef30d451f3ab9eb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1S_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac1b72bf6c7bc204136030e0ae144f3de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1S_UXTW_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19acc129ce1cfc16e162528c86841b10e32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1S_SXTW_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a558ddabda114cddf991cf8052babf0da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1S_UXTW_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a5ca98fbce7ddde8900dfd68b03a5b76f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1S_SXTW_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af263284586304c99345ed0c663ea2e3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLD1S_IMM_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac11bd3bd817019b249d11d7f12aedd31"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aec4b3e29e4c750748f6eec345d2ecfe7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a0d5ecaf42b919f021d7f90a1b17d3d4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1_UXTW_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa63ddb8204981576c188ecd594ec388a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1_SXTW_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a637b9743c971911cbd50d1f7205db274"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1_UXTW_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a68588f7134c66b9586fa7ad3d9720258"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1_SXTW_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a33060aa53377821ae236cdcdc6234f21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1_IMM_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a94f47573b2939ef71e656156bc5cd991"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1S_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa631fe3aedf8ad98d00b72a60a83331b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1S_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6860799327fcd8cec080e54dc44657ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1S_UXTW_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa02c6d9794c8cb1e8ef9cbedd506e8a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1S_SXTW_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a0a33fd3f562a7cd1aa496e8c99023e53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1S_UXTW_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6cd3f502d5d40edc8c908a6dcea9502f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1S_SXTW_SCALED_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa9468a8cff4e6e8565df6264690cd325"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDFF1S_IMM_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6702dc1bf5b9209ddf6d77196b38181e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDNT1_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a148014182bdd341f262ef4d64969bb72"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDNT1_INDEX_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a658fff45ec5b54f450348d849379d5e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLDNT1S_MERGE_ZERO<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9bbaca23753c5b631bf9a62f3a730fe6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST1_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a8c086cd580aa6cfe36c410ac0eaecffe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SST1_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a228badaf4ea8fc1855e346884210a40f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SST1_SCALED_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4c18de870cd5cdb48d13c2554dbe975e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SST1_UXTW_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19adb25d74321dce9c4a69412fd849e6709"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SST1_SXTW_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a63629e520272560bfaa91072ced436db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SST1_UXTW_SCALED_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a31c76b6e0b307a491e2064bdaa55e16d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SST1_SXTW_SCALED_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aee81f3a7f92882048ae759626cce52fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SST1_IMM_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a85ed05e5b6525f68f560aeec26360a9f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SST1Q_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a58d30483f428219ebfd40e279db19942"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SST1Q_INDEX_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad1c18847191322766d77b00a67708c9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSTNT1_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac790946c00d53a027bcd49843379fb21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSTNT1_INDEX_PRED<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ac59023c7b0b3c6f3fa7ff35406ebe37e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RDSVL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1f75be7ca0afb86d4ed6696a290d4b39"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REVD_MERGE_PASSTHRU<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a111ab9bf74b48fddceb457cbe3d9b2b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALLOCATE_ZA_BUFFER<a id="a35ad1b8db0dfad0b69c9185c5fe24e19abed4fc5cfb6475d3141b7a9d51c8d0d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INIT_TPIDR2OBJ<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9e45b2b2b8505169eda1ba9272a908e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_SME_SAVE_SIZE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7d73c0d4c5c8077d7c6e89e4c970714b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALLOC_SME_SAVE_BUFFER<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a708cfb0f0b290388103fab23b2df11b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASSERT_ZEXT_BOOL<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9e2fdd4065ecdc6146b74253f5591ed5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRRS<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad0d9536662de9b7080a988a986f7ab1e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSRR<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a2486a390b5849a760c293a7aa8a569f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_STRICTFP_OPCODE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a0aebc864d51a274a2f4b31dc087c754c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCMP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ae2e012d1717a5485a8723c1372f0a0ce"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_STRICTFP_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCMPE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ab7831d4deb75f0578e943637e29477ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_STRICTFP_OPCODE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a792fec4d540221e473e22415ccdf1ce2"></a></td>
<td class="doxyEnumItemDescription"> (= STRICT_FCMPE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_MEMORY_OPCODE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a359df87ab7d0de701b8bad4407292658"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD2post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a611efefd07581a309272ce3604a444f1"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_MEMORY_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD3post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a10515cb929353e22ba15cf55d9d8b67a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD4post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa6617bab04266e3a038086c0e27fe5a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST2post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ab094a6a98cc4e55bec227f809503a184"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST3post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a95de67e2367d3060cb2336a6805e48cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST4post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1a8fa2bbc5e58ecdb4d5405c52165959"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD1x2post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a4a633f62fc41f2022fe2170031a65d0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD1x3post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a28800ddf447359f84e24d7314ccb98de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD1x4post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a1e3fbe83f867fe16454d9928afa4b29f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST1x2post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a5d2518cc25a5983068164109fdd92691"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST1x3post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a5b1de6bb4e7f7e0cf389ba2f258066e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST1x4post<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6d588334989b7663c1d0cdbbbf209f15"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD1DUPpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a0b3f053c7801048ee58d05f6877995d0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD2DUPpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a68a32966ba07f4efbe2397915501622f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD3DUPpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a74c7f6579312bce1adcf3adf0f3ca33a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD4DUPpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9d12cf233445b196a30a2cb5e339b6dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD1LANEpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19af9aa22215f868a0dcc94cf13bc459460"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD2LANEpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19acffc300e996f001cf3bbbf1e25c7b974"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD3LANEpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aec77dff21e4270304e2569473d701994"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD4LANEpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a5323cab8ff6fd076ef57c895a0965f62"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST2LANEpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a08ec19f37da502bfd936951a14f678c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST3LANEpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a677e79b3b0d2d9969f84dfc567683f2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST4LANEpost<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a8f9b927f69d51deab20e1da9cf296300"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STG<a id="a35ad1b8db0dfad0b69c9185c5fe24e19aa931d46bc7be6ffc74d0673d26fd4b86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STZG<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ad4cde0015d3454bacad2b4d1669608f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST2G<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a293600b79057550d0e087a9aa8be097d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STZ2G<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a84ae19f2bf01a162207d82a39b1ba230"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a6c9a44d7fa618f0161949ff4d455db12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDIAPP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a45e4c2a81a1d0bc6e191eb1a11e41020"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDNP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a3cabad4255ec575c6df049ad5c3c8568"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a05487d4f8bc52d52005b9f3ccfe9556d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STILP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9b6a5a5ff693c2554a05274a8107506c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STNP<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a7ebbef8c7398740fa451f47dd77fbd58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_MEMORY_OPCODE<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a45bff57bd866d49de6c5f917d21d4b2b"></a></td>
<td class="doxyEnumItemDescription"> (= STNP)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SME_ZA_LDR<a id="a35ad1b8db0dfad0b69c9185c5fe24e19ab691f36326443f587301f2e094d9d941"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SME_ZA_STR<a id="a35ad1b8db0dfad0b69c9185c5fe24e19a9d2511e25a56a5cae1526e6cc7917221"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
