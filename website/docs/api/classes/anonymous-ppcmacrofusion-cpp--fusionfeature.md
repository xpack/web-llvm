---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppcmacrofusion-cpp-/fusionfeature
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FusionFeature` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCMacroFusion.cpp}::FusionFeature { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; unsigned &gt; <a href="#afce7c3d42d830243e56b0191e205f35a">FusionOpSet</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">FusionKind { <a href="#a9180da3be917e7829faaffae67e7ac05">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae68e7f1fb7eb8186bd289bcb5dba22ac">FusionFeature</a> (FusionKind Kind, bool HasFeature, int Index, const FusionOpSet &amp;First, const FusionOpSet &amp;Second)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c6ab7c1c9b82843905ae1a520cfed8">hasOp1</a> (unsigned Opc) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f9a13a1a2606a297fbfb685250afbe">hasOp2</a> (unsigned Opc) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28da93339389153c3f7447403cfb254b">isSupported</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7386ff218bee9b67c13c5bda1ba91be6">depOpIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9180da3be917e7829faaffae67e7ac05">FusionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997c012fe47b359d899400919c8f962e">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9180da3be917e7829faaffae67e7ac05">FusionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9baf5a73d6790d0325d105d8b3d95bb8">Kd</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f0f76cffeb9b1f9ebd65fe34a7950e">Supported</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e511285ad83e13f8aa0c0e816e8768e">DepOpIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afce7c3d42d830243e56b0191e205f35a">FusionOpSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb0699493ab1f70c81fc6a3ad64e5ab">OpSet1</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afce7c3d42d830243e56b0191e205f35a">FusionOpSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0754158fec533e9c74c3c48963813b0">OpSet2</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FusionOpSet {#afce7c3d42d830243e56b0191e205f35a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallDenseSet&lt;unsigned&gt; anonymous{PPCMacroFusion.cpp}::FusionFeature::FusionOpSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### FusionKind {#a9180da3be917e7829faaffae67e7ac05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{PPCMacroFusion.cpp}::FusionFeature::FusionKind </td>
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
<td class="doxyEnumItemName">FUSION_FEATURE<a id="a9180da3be917e7829faaffae67e7ac05a9003d2408851efdef7ade3283f23b823"></a></td>
<td class="doxyEnumItemDescription">
 (=(AddiLoad, hasAddiLoadFusion, 2, 
               FUSION_OP_SET(ADDI, ADDI8, ADDItocL, ADDItocL8), 
               FUSION_OP_SET(LXVD2X, LXVW4X, LXVDSX, LVEBX, LVEHX, LVEWX, 
                             LVX, LXSDX))


FUSION_FEATURE(AddisLoad, hasAddisLoadFusion, 2, 
               FUSION_OP_SET(ADDIS, ADDIS8, ADDIStocHA8), 
               FUSION_OP_SET(LD, LBZ, LBZ8, LHZ, LHZ8, LWZ, LWZ8))



FUSION_FEATURE(ArithAdd, hasArithAddFusion, -1,
               FUSION_OP_SET(ADD4, ADD8, MULLD), FUSION_OP_SET(ADD4, ADD8))


FUSION_FEATURE(ArithLogical, hasAddLogicalFusion, -1,
               FUSION_OP_SET(ADD4, ADD8, SUBF, SUBF8),
               FUSION_OP_SET(AND, AND8, OR, OR8, NAND, NAND8, NOR, NOR8))


FUSION_FEATURE(LogicalArith, hasLogicalAddFusion, -1,
               FUSION_OP_SET(AND, ANDC, EQV, NAND, NOR, OR, ORC, XOR, AND8,
                             ANDC8, EQV8, NAND8, NOR8, OR8, ORC8, XOR8),
               FUSION_OP_SET(ADD4, ADD8, SUBF, SUBF8))


FUSION_FEATURE(Logical, hasLogicalFusion, -1,
               FUSION_OP_SET(AND, ANDC, EQV, NAND, NOR, OR, ORC, XOR, AND8,
                             ANDC8, EQV8, NAND8, NOR8, OR8, ORC8, XOR8),
               FUSION_OP_SET(AND, ANDC, EQV, NAND, NOR, OR, ORC, XOR, AND8,
                             ANDC8, EQV8, NAND8, NOR8, OR8, ORC8, XOR8))


FUSION_FEATURE(VecAdd, hasArithAddFusion, -1, FUSION_OP_SET(VADDUDM),
               FUSION_OP_SET(VADDUDM))


FUSION_FEATURE(VecLogical, hasLogicalFusion, -1,
               FUSION_OP_SET(VAND, VANDC, VEQV, VNAND, VNOR, VOR, VORC, VXOR),
               FUSION_OP_SET(VAND, VANDC, VEQV, VNAND, VNOR, VOR, VORC, VXOR))



FUSION_FEATURE(SldiAdd, hasArithAddFusion, -1, FUSION_OP_SET(RLDICR, RLDICR_32),
               FUSION_OP_SET(ADD4, ADD8, SUBF, SUBF8))


FUSION_FEATURE(RotateLeftXor, hasSha3Fusion, 1,
               FUSION_OP_SET(RLDICL, RLDICL_32, RLDICL_32_64),
               FUSION_OP_SET(XOR, XOR8))


FUSION_FEATURE(RotateRightXor, hasSha3Fusion, 1,
               FUSION_OP_SET(RLDICR, RLDICR_32), FUSION_OP_SET(XOR, XOR8))







FUSION_FEATURE(LoadCmp1, hasCompareFusion, 1,
               FUSION_OP_SET(LBZ, LBZ8, LBZX, LBZX8, LBZXTLS, LBZXTLS_,
                             LBZXTLS_32, LHZ, LHZ8, LHZX, LHZX8, LHZXTLS,
                             LHZXTLS_, LHZXTLS_32, LWZ, LWZ8, LWZX, LWZX8,
                             LWZXTLS, LWZXTLS_, LWZXTLS_32),
               FUSION_OP_SET(CMPDI, CMPLDI, CMPLWI))



FUSION_FEATURE(LoadCmp2, hasCompareFusion, 1,
               FUSION_OP_SET(LD, LDX, LDXTLS, LDXTLS_),
               FUSION_OP_SET(CMPDI, CMPLDI))


FUSION_FEATURE(LoadCmp3, hasCompareFusion, 1,
               FUSION_OP_SET(LHA, LHA8, LHAX, LHAX8, LWA, LWA_32, LWAX,
                             LWAX_32),
               FUSION_OP_SET(CMPLDI, CMPLWI))


FUSION_FEATURE(OriOris, hasWideImmFusion, 1, FUSION_OP_SET(ORI, ORI8),
               FUSION_OP_SET(ORIS, ORIS8))


FUSION_FEATURE(LisOri, hasWideImmFusion, 1, FUSION_OP_SET(LIS, LIS8),
               FUSION_OP_SET(ORI, ORI8))


FUSION_FEATURE(OrisOri, hasWideImmFusion, 1, FUSION_OP_SET(ORIS, ORIS8),
               FUSION_OP_SET(ORI, ORI8))


FUSION_FEATURE(XoriXoris, hasWideImmFusion, 1, FUSION_OP_SET(XORI, XORI8),
               FUSION_OP_SET(XORIS, XORIS8))


FUSION_FEATURE(XorisXori, hasWideImmFusion, 1, FUSION_OP_SET(XORIS, XORIS8),
               FUSION_OP_SET(XORI, XORI8))


FUSION_FEATURE(AddisAddi, hasWideImmFusion, 1,
               FUSION_OP_SET(ADDIS, ADDIS8, ADDIStocHA8, ADDIStocHA),
               FUSION_OP_SET(ADDI, ADDI8, ADDItocL8, ADDItocL))


FUSION_FEATURE(AddiAddis, hasWideImmFusion, 1,
               FUSION_OP_SET(ADDI, ADDI8, ADDItocL8, ADDItocL),
               FUSION_OP_SET(ADDIS, ADDIS8, ADDIStocHA8, ADDIStocHA))


FUSION_FEATURE(ZeroMoveCTR, hasZeroMoveFusion, -1,
               FUSION_OP_SET(MTCTR, MTCTRloop, MTSPR8, MTSPR),
               FUSION_OP_SET(BCCTR, BCCTRn, BCCTR8, BCCTR8n, BCCTRL, BCCTRLn,
                             BCCTRL8, BCCTRL8n, gBCCTR, gBCCTRL))


FUSION_FEATURE(ZeroMoveLR, hasZeroMoveFusion, -1,
               FUSION_OP_SET(MTLR8, MTLR, MTSPR8, MTSPR),
               FUSION_OP_SET(BCLR, BCLRn, gBCLR, BCLRL, BCLRLn, gBCLRL))

# 1 "/Users/ilg/MyProjects/xpack.github/docusaurus/web-llvm.git/llvm-project/llvm/lib/Target/PowerPC/PPCBack2BackFusion.def" 1




FUSION_FEATURE(GeneralBack2Back, hasBack2BackFusion, -1,
  FUSION_OP_SET(ADD4,
    ADD4O,
    ADD4TLS,
    ADD4_rec,
    ADD8,
    ADD8O,
    ADD8TLS,
    ADD8TLS_,
    ADD8_rec,
    ADDE,
    ADDE8,
    ADDE8O,
    ADDEO,
    ADDEX,
    ADDEX8,
    ADDI,
    ADDI8,
    ADDIC,
    ADDIC8,
    ADDIS,
    ADDIS8,
    ADDISdtprelHA32,
    ADDIStocHA,
    ADDIStocHA8,
    ADDIdtprelL32,
    ADDItlsldLADDR32,
    ADDItocL8,
    ADDME,
    ADDME8,
    ADDME8O,
    ADDMEO,
    ADDZE,
    ADDZE8,
    ADDZE8O,
    ADDZEO,
    AND,
    AND8,
    AND8_rec,
    ANDC,
    ANDC8,
    ANDC8_rec,
    ANDC_rec,
    ANDI8_rec,
    ANDIS8_rec,
    ANDIS_rec,
    ANDI_rec,
    AND_rec,
    CBCDTD,
    CBCDTD8,
    CDTBCD,
    CDTBCD8,
    CMPB,
    CMPB8,
    CNTLZD,
    CNTLZD_rec,
    CNTLZW,
    CNTLZW8,
    CNTLZW8_rec,
    CNTLZW_rec,
    CNTTZD,
    CNTTZD_rec,
    CNTTZW,
    CNTTZW8,
    CNTTZW8_rec,
    CNTTZW_rec,
    EQV,
    EQV8,
    EQV8_rec,
    EQV_rec,
    EXTSB,
    EXTSB8,
    EXTSB8_32_64,
    EXTSB8_rec,
    EXTSB_rec,
    EXTSH,
    EXTSH8,
    EXTSH8_32_64,
    EXTSH8_rec,
    EXTSH_rec,
    EXTSW,
    EXTSWSLI,
    EXTSWSLI_32_64,
    EXTSWSLI_32_64_rec,
    EXTSWSLI_rec,
    EXTSW_32,
    EXTSW_32_64,
    EXTSW_32_64_rec,
    EXTSW_rec,
    FABSD,
    FABSS,
    FCPSGND,
    FCPSGNS,
    FMR,
    FNABSD,
    FNABSS,
    FNEGD,
    FNEGS,
    ISEL,
    ISEL8,
    LI,
    LI8,
    LIS,
    LIS8,
    MFCTR,
    MFCTR8,
    MFLR,
    MFLR8,
    MFOCRF,
    MFOCRF8,
    MFVRD,
    MFVRWZ,
    MFVSRD,
    MFVSRWZ,
    MTVRD,
    MTVRWA,
    MTVRWZ,
    MTVSRBM,
    MTVSRBMI,
    MTVSRD,
    MTVSRDM,
    MTVSRHM,
    MTVSRQM,
    MTVSRWA,
    MTVSRWM,
    MTVSRWZ,
    NAND,
    NAND8,
    NAND8_rec,
    NAND_rec,
    NEG,
    NEG8,
    NEG8O,
    NEG8_rec,
    NEGO,
    NEG_rec,
    NOP,
    NOP_GT_PWR6,
    NOP_GT_PWR7,
    NOR,
    NOR8,
    NOR8_rec,
    NOR_rec,
    OR,
    OR8,
    OR8_rec,
    ORC,
    ORC8,
    ORC8_rec,
    ORC_rec,
    ORI,
    ORI8,
    ORIS,
    ORIS8,
    OR_rec,
    POPCNTB,
    POPCNTB8,
    POPCNTD,
    POPCNTW,
    RLDCL,
    RLDCL_rec,
    RLDCR,
    RLDCR_rec,
    RLDIC,
    RLDICL,
    RLDICL_32,
    RLDICL_32_64,
    RLDICL_32_rec,
    RLDICL_rec,
    RLDICR,
    RLDICR_32,
    RLDICR_rec,
    RLDIC_rec,
    RLDIMI,
    RLDIMI_rec,
    RLWIMI,
    RLWIMI8,
    RLWIMI8_rec,
    RLWIMI_rec,
    RLWINM,
    RLWINM8,
    RLWINM8_rec,
    RLWINM_rec,
    RLWNM,
    RLWNM8,
    RLWNM8_rec,
    RLWNM_rec,
    SETB,
    SETB8,
    SETBC,
    SETBC8,
    SETBCR,
    SETBCR8,
    SETNBC,
    SETNBC8,
    SETNBCR,
    SETNBCR8,
    SLD,
    SLD_rec,
    SLW,
    SLW8,
    SLW8_rec,
    SLW_rec,
    SRAD,
    SRADI,
    SRADI_32,
    SRAW,
    SRAWI,
    SRD,
    SRD_rec,
    SRW,
    SRW8,
    SRW8_rec,
    SRW_rec,
    SUBF,
    SUBF8,
    SUBF8O,
    SUBF8_rec,
    SUBFE,
    SUBFE8,
    SUBFE8O,
    SUBFEO,
    SUBFIC,
    SUBFIC8,
    SUBFME,
    SUBFME8,
    SUBFME8O,
    SUBFMEO,
    SUBFO,
    SUBFZE,
    SUBFZE8,
    SUBFZE8O,
    SUBFZEO,
    SUBF_rec,
    VABSDUB,
    VABSDUH,
    VABSDUW,
    VADDCUW,
    VADDSBS,
    VADDSHS,
    VADDSWS,
    VADDUBM,
    VADDUBS,
    VADDUDM,
    VADDUHM,
    VADDUHS,
    VADDUWM,
    VADDUWS,
    VAND,
    VANDC,
    VAVGSB,
    VAVGSH,
    VAVGSW,
    VAVGUB,
    VAVGUH,
    VAVGUW,
    VCLZB,
    VCLZD,
    VCLZH,
    VCLZW,
    VCMPBFP,
    VCMPBFP_rec,
    VCMPEQFP,
    VCMPEQFP_rec,
    VCMPEQUB,
    VCMPEQUB_rec,
    VCMPEQUD,
    VCMPEQUD_rec,
    VCMPEQUH,
    VCMPEQUH_rec,
    VCMPEQUQ,
    VCMPEQUQ_rec,
    VCMPEQUW,
    VCMPEQUW_rec,
    VCMPGEFP,
    VCMPGEFP_rec,
    VCMPGTFP,
    VCMPGTFP_rec,
    VCMPGTSB,
    VCMPGTSB_rec,
    VCMPGTSD,
    VCMPGTSD_rec,
    VCMPGTSH,
    VCMPGTSH_rec,
    VCMPGTSQ,
    VCMPGTSQ_rec,
    VCMPGTSW,
    VCMPGTSW_rec,
    VCMPGTUB,
    VCMPGTUB_rec,
    VCMPGTUD,
    VCMPGTUD_rec,
    VCMPGTUH,
    VCMPGTUH_rec,
    VCMPGTUQ,
    VCMPGTUQ_rec,
    VCMPGTUW,
    VCMPGTUW_rec,
    VCMPNEB,
    VCMPNEB_rec,
    VCMPNEH,
    VCMPNEH_rec,
    VCMPNEW,
    VCMPNEW_rec,
    VCMPNEZB,
    VCMPNEZB_rec,
    VCMPNEZH,
    VCMPNEZH_rec,
    VCMPNEZW,
    VCMPNEZW_rec,
    VCNTMBB,
    VCNTMBD,
    VCNTMBH,
    VCNTMBW,
    VCTZB,
    VCTZD,
    VCTZH,
    VCTZW,
    VEQV,
    VEXPANDBM,
    VEXPANDDM,
    VEXPANDHM,
    VEXPANDQM,
    VEXPANDWM,
    VEXTRACTBM,
    VEXTRACTDM,
    VEXTRACTHM,
    VEXTRACTQM,
    VEXTRACTWM,
    VEXTSB2D,
    VEXTSB2Ds,
    VEXTSB2W,
    VEXTSB2Ws,
    VEXTSD2Q,
    VEXTSH2D,
    VEXTSH2Ds,
    VEXTSH2W,
    VEXTSH2Ws,
    VEXTSW2D,
    VEXTSW2Ds,
    VMAXFP,
    VMAXSB,
    VMAXSD,
    VMAXSH,
    VMAXSW,
    VMAXUB,
    VMAXUD,
    VMAXUH,
    VMAXUW,
    VMINFP,
    VMINSB,
    VMINSD,
    VMINSH,
    VMINSW,
    VMINUB,
    VMINUD,
    VMINUH,
    VMINUW,
    VMRGEW,
    VMRGOW,
    VNAND,
    VNEGD,
    VNEGW,
    VNOR,
    VOR,
    VORC,
    VPOPCNTB,
    VPOPCNTD,
    VPOPCNTH,
    VPOPCNTW,
    VPRTYBD,
    VPRTYBW,
    VRLB,
    VRLD,
    VRLDMI,
    VRLDNM,
    VRLH,
    VRLW,
    VRLWMI,
    VRLWNM,
    VSEL,
    VSHASIGMAD,
    VSHASIGMAW,
    VSLB,
    VSLD,
    VSLH,
    VSLW,
    VSRAB,
    VSRAD,
    VSRAH,
    VSRAW,
    VSRB,
    VSRD,
    VSRH,
    VSRW,
    VSUBCUW,
    VSUBSBS,
    VSUBSHS,
    VSUBSWS,
    VSUBUBM,
    VSUBUBS,
    VSUBUDM,
    VSUBUHM,
    VSUBUHS,
    VSUBUWM,
    VSUBUWS,
    VXOR,
    V_SET0,
    V_SET0B,
    V_SET0H,
    XOR,
    XOR8,
    XOR8_rec,
    XORI,
    XORI8,
    XORIS,
    XORIS8,
    XOR_rec,
    XSABSDP,
    XSABSQP,
    XSCMPEQDP,
    XSCMPGEDP,
    XSCMPGTDP,
    XSCPSGNDP,
    XSCPSGNQP,
    XSCVHPDP,
    XSCVSPDPN,
    XSIEXPDP,
    XSIEXPQP,
    XSMAXCDP,
    XSMAXDP,
    XSMAXJDP,
    XSMINCDP,
    XSMINDP,
    XSMINJDP,
    XSNABSDP,
    XSNABSDPs,
    XSNABSQP,
    XSNEGDP,
    XSNEGQP,
    XSXEXPDP,
    XSXEXPQP,
    XSXSIGDP,
    XVABSDP,
    XVABSSP,
    XVCMPEQDP,
    XVCMPEQDP_rec,
    XVCMPEQSP,
    XVCMPEQSP_rec,
    XVCMPGEDP,
    XVCMPGEDP_rec,
    XVCMPGESP,
    XVCMPGESP_rec,
    XVCMPGTDP,
    XVCMPGTDP_rec,
    XVCMPGTSP,
    XVCMPGTSP_rec,
    XVCPSGNDP,
    XVCPSGNSP,
    XVCVHPSP,
    XVIEXPDP,
    XVIEXPSP,
    XVMAXDP,
    XVMAXSP,
    XVMINDP,
    XVMINSP,
    XVNABSDP,
    XVNABSSP,
    XVNEGDP,
    XVNEGSP,
    XVTSTDCDP,
    XVTSTDCSP,
    XVXEXPDP,
    XVXEXPSP,
    XVXSIGDP,
    XVXSIGSP,
    XXLAND,
    XXLANDC,
    XXLEQV,
    XXLEQVOnes,
    XXLNAND,
    XXLNOR,
    XXLOR,
    XXLORC,
    XXLORf,
    XXLXOR,
    XXLXORdpz,
    XXLXORspz,
    XXLXORz,
    XXSEL),
  FUSION_OP_SET(ADD4,
    ADD4O,
    ADD4TLS,
    ADD4_rec,
    ADD8,
    ADD8O,
    ADD8TLS,
    ADD8TLS_,
    ADD8_rec,
    ADDE,
    ADDE8,
    ADDE8O,
    ADDEO,
    ADDEX,
    ADDEX8,
    ADDI,
    ADDI8,
    ADDIC,
    ADDIC8,
    ADDIS,
    ADDIS8,
    ADDISdtprelHA32,
    ADDIStocHA,
    ADDIStocHA8,
    ADDIdtprelL32,
    ADDItlsldLADDR32,
    ADDItocL8,
    ADDME,
    ADDME8,
    ADDME8O,
    ADDMEO,
    ADDZE,
    ADDZE8,
    ADDZE8O,
    ADDZEO,
    AND,
    AND8,
    AND8_rec,
    ANDC,
    ANDC8,
    ANDC8_rec,
    ANDC_rec,
    ANDI8_rec,
    ANDIS8_rec,
    ANDIS_rec,
    ANDI_rec,
    AND_rec,
    CBCDTD,
    CBCDTD8,
    CDTBCD,
    CDTBCD8,
    CMPB,
    CMPB8,
    CMPD,
    CMPDI,
    CMPEQB,
    CMPLD,
    CMPLDI,
    CMPLW,
    CMPLWI,
    CMPRB,
    CMPRB8,
    CMPW,
    CMPWI,
    CNTLZD,
    CNTLZD_rec,
    CNTLZW,
    CNTLZW8,
    CNTLZW8_rec,
    CNTLZW_rec,
    CNTTZD,
    CNTTZD_rec,
    CNTTZW,
    CNTTZW8,
    CNTTZW8_rec,
    CNTTZW_rec,
    CR6SET,
    CR6UNSET,
    CRAND,
    CRANDC,
    CREQV,
    CRNAND,
    CRNOR,
    CROR,
    CRORC,
    CRSET,
    CRUNSET,
    CRXOR,
    DSS,
    DSSALL,
    DST,
    DST64,
    DSTST,
    DSTST64,
    DSTSTT,
    DSTSTT64,
    DSTT,
    DSTT64,
    EQV,
    EQV8,
    EQV8_rec,
    EQV_rec,
    EXTSB,
    EXTSB8,
    EXTSB8_32_64,
    EXTSB8_rec,
    EXTSB_rec,
    EXTSH,
    EXTSH8,
    EXTSH8_32_64,
    EXTSH8_rec,
    EXTSH_rec,
    EXTSW,
    EXTSWSLI,
    EXTSWSLI_32_64,
    EXTSWSLI_32_64_rec,
    EXTSWSLI_rec,
    EXTSW_32,
    EXTSW_32_64,
    EXTSW_32_64_rec,
    EXTSW_rec,
    FABSD,
    FABSS,
    FCMPOD,
    FCMPOS,
    FCMPUD,
    FCMPUS,
    FCPSGND,
    FCPSGNS,
    FMR,
    FNABSD,
    FNABSS,
    FNEGD,
    FNEGS,
    FTDIV,
    FTSQRT,
    ISEL,
    ISEL8,
    LI,
    LI8,
    LIS,
    LIS8,
    MCRF,
    MCRXRX,
    MFCTR,
    MFCTR8,
    MFLR,
    MFLR8,
    MFOCRF,
    MFOCRF8,
    MFVRD,
    MFVRWZ,
    MFVSRD,
    MFVSRWZ,
    MTCTR,
    MTCTR8,
    MTCTR8loop,
    MTCTRloop,
    MTLR,
    MTLR8,
    MTOCRF,
    MTOCRF8,
    MTVRD,
    MTVRWA,
    MTVRWZ,
    MTVSRBM,
    MTVSRBMI,
    MTVSRD,
    MTVSRDM,
    MTVSRHM,
    MTVSRQM,
    MTVSRWA,
    MTVSRWM,
    MTVSRWZ,
    NAND,
    NAND8,
    NAND8_rec,
    NAND_rec,
    NEG,
    NEG8,
    NEG8O,
    NEG8_rec,
    NEGO,
    NEG_rec,
    NOP,
    NOP_GT_PWR6,
    NOP_GT_PWR7,
    NOR,
    NOR8,
    NOR8_rec,
    NOR_rec,
    OR,
    OR8,
    OR8_rec,
    ORC,
    ORC8,
    ORC8_rec,
    ORC_rec,
    ORI,
    ORI8,
    ORIS,
    ORIS8,
    OR_rec,
    POPCNTB,
    POPCNTB8,
    POPCNTD,
    POPCNTW,
    RLDCL,
    RLDCL_rec,
    RLDCR,
    RLDCR_rec,
    RLDIC,
    RLDICL,
    RLDICL_32,
    RLDICL_32_64,
    RLDICL_32_rec,
    RLDICL_rec,
    RLDICR,
    RLDICR_32,
    RLDICR_rec,
    RLDIC_rec,
    RLDIMI,
    RLDIMI_rec,
    RLWIMI,
    RLWIMI8,
    RLWIMI8_rec,
    RLWIMI_rec,
    RLWINM,
    RLWINM8,
    RLWINM8_rec,
    RLWINM_rec,
    RLWNM,
    RLWNM8,
    RLWNM8_rec,
    RLWNM_rec,
    SETB,
    SETB8,
    SETBC,
    SETBC8,
    SETBCR,
    SETBCR8,
    SETNBC,
    SETNBC8,
    SETNBCR,
    SETNBCR8,
    SLD,
    SLD_rec,
    SLW,
    SLW8,
    SLW8_rec,
    SLW_rec,
    SRAD,
    SRADI,
    SRADI_32,
    SRAW,
    SRAWI,
    SRD,
    SRD_rec,
    SRW,
    SRW8,
    SRW8_rec,
    SRW_rec,
    SUBF,
    SUBF8,
    SUBF8O,
    SUBF8_rec,
    SUBFE,
    SUBFE8,
    SUBFE8O,
    SUBFEO,
    SUBFIC,
    SUBFIC8,
    SUBFME,
    SUBFME8,
    SUBFME8O,
    SUBFMEO,
    SUBFO,
    SUBFZE,
    SUBFZE8,
    SUBFZE8O,
    SUBFZEO,
    SUBF_rec,
    TD,
    TDI,
    TRAP,
    TW,
    TWI,
    VABSDUB,
    VABSDUH,
    VABSDUW,
    VADDCUW,
    VADDSBS,
    VADDSHS,
    VADDSWS,
    VADDUBM,
    VADDUBS,
    VADDUDM,
    VADDUHM,
    VADDUHS,
    VADDUWM,
    VADDUWS,
    VAND,
    VANDC,
    VAVGSB,
    VAVGSH,
    VAVGSW,
    VAVGUB,
    VAVGUH,
    VAVGUW,
    VCLZB,
    VCLZD,
    VCLZH,
    VCLZW,
    VCMPBFP,
    VCMPBFP_rec,
    VCMPEQFP,
    VCMPEQFP_rec,
    VCMPEQUB,
    VCMPEQUB_rec,
    VCMPEQUD,
    VCMPEQUD_rec,
    VCMPEQUH,
    VCMPEQUH_rec,
    VCMPEQUQ,
    VCMPEQUQ_rec,
    VCMPEQUW,
    VCMPEQUW_rec,
    VCMPGEFP,
    VCMPGEFP_rec,
    VCMPGTFP,
    VCMPGTFP_rec,
    VCMPGTSB,
    VCMPGTSB_rec,
    VCMPGTSD,
    VCMPGTSD_rec,
    VCMPGTSH,
    VCMPGTSH_rec,
    VCMPGTSQ,
    VCMPGTSQ_rec,
    VCMPGTSW,
    VCMPGTSW_rec,
    VCMPGTUB,
    VCMPGTUB_rec,
    VCMPGTUD,
    VCMPGTUD_rec,
    VCMPGTUH,
    VCMPGTUH_rec,
    VCMPGTUQ,
    VCMPGTUQ_rec,
    VCMPGTUW,
    VCMPGTUW_rec,
    VCMPNEB,
    VCMPNEB_rec,
    VCMPNEH,
    VCMPNEH_rec,
    VCMPNEW,
    VCMPNEW_rec,
    VCMPNEZB,
    VCMPNEZB_rec,
    VCMPNEZH,
    VCMPNEZH_rec,
    VCMPNEZW,
    VCMPNEZW_rec,
    VCMPSQ,
    VCMPUQ,
    VCNTMBB,
    VCNTMBD,
    VCNTMBH,
    VCNTMBW,
    VCTZB,
    VCTZD,
    VCTZH,
    VCTZW,
    VEQV,
    VEXPANDBM,
    VEXPANDDM,
    VEXPANDHM,
    VEXPANDQM,
    VEXPANDWM,
    VEXTRACTBM,
    VEXTRACTDM,
    VEXTRACTHM,
    VEXTRACTQM,
    VEXTRACTWM,
    VEXTSB2D,
    VEXTSB2Ds,
    VEXTSB2W,
    VEXTSB2Ws,
    VEXTSD2Q,
    VEXTSH2D,
    VEXTSH2Ds,
    VEXTSH2W,
    VEXTSH2Ws,
    VEXTSW2D,
    VEXTSW2Ds,
    VMAXFP,
    VMAXSB,
    VMAXSD,
    VMAXSH,
    VMAXSW,
    VMAXUB,
    VMAXUD,
    VMAXUH,
    VMAXUW,
    VMINFP,
    VMINSB,
    VMINSD,
    VMINSH,
    VMINSW,
    VMINUB,
    VMINUD,
    VMINUH,
    VMINUW,
    VMRGEW,
    VMRGOW,
    VNAND,
    VNEGD,
    VNEGW,
    VNOR,
    VOR,
    VORC,
    VPOPCNTB,
    VPOPCNTD,
    VPOPCNTH,
    VPOPCNTW,
    VPRTYBD,
    VPRTYBW,
    VRLB,
    VRLD,
    VRLDMI,
    VRLDNM,
    VRLH,
    VRLW,
    VRLWMI,
    VRLWNM,
    VSEL,
    VSHASIGMAD,
    VSHASIGMAW,
    VSLB,
    VSLD,
    VSLH,
    VSLW,
    VSRAB,
    VSRAD,
    VSRAH,
    VSRAW,
    VSRB,
    VSRD,
    VSRH,
    VSRW,
    VSUBCUW,
    VSUBSBS,
    VSUBSHS,
    VSUBSWS,
    VSUBUBM,
    VSUBUBS,
    VSUBUDM,
    VSUBUHM,
    VSUBUHS,
    VSUBUWM,
    VSUBUWS,
    VXOR,
    V_SET0,
    V_SET0B,
    V_SET0H,
    WAIT,
    WAITP10,
    XOR,
    XOR8,
    XOR8_rec,
    XORI,
    XORI8,
    XORIS,
    XORIS8,
    XOR_rec,
    XSABSDP,
    XSABSQP,
    XSCMPEQDP,
    XSCMPEXPDP,
    XSCMPGEDP,
    XSCMPGTDP,
    XSCMPODP,
    XSCMPUDP,
    XSCPSGNDP,
    XSCPSGNQP,
    XSCVHPDP,
    XSCVSPDPN,
    XSIEXPDP,
    XSIEXPQP,
    XSMAXCDP,
    XSMAXDP,
    XSMAXJDP,
    XSMINCDP,
    XSMINDP,
    XSMINJDP,
    XSNABSDP,
    XSNABSDPs,
    XSNABSQP,
    XSNEGDP,
    XSNEGQP,
    XSTDIVDP,
    XSTSQRTDP,
    XSTSTDCDP,
    XSTSTDCSP,
    XSXEXPDP,
    XSXEXPQP,
    XSXSIGDP,
    XVABSDP,
    XVABSSP,
    XVCMPEQDP,
    XVCMPEQDP_rec,
    XVCMPEQSP,
    XVCMPEQSP_rec,
    XVCMPGEDP,
    XVCMPGEDP_rec,
    XVCMPGESP,
    XVCMPGESP_rec,
    XVCMPGTDP,
    XVCMPGTDP_rec,
    XVCMPGTSP,
    XVCMPGTSP_rec,
    XVCPSGNDP,
    XVCPSGNSP,
    XVCVHPSP,
    XVIEXPDP,
    XVIEXPSP,
    XVMAXDP,
    XVMAXSP,
    XVMINDP,
    XVMINSP,
    XVNABSDP,
    XVNABSSP,
    XVNEGDP,
    XVNEGSP,
    XVTDIVDP,
    XVTDIVSP,
    XVTLSBB,
    XVTSQRTDP,
    XVTSQRTSP,
    XVTSTDCDP,
    XVTSTDCSP,
    XVXEXPDP,
    XVXEXPSP,
    XVXSIGDP,
    XVXSIGSP,
    XXLAND,
    XXLANDC,
    XXLEQV,
    XXLEQVOnes,
    XXLNAND,
    XXLNOR,
    XXLOR,
    XXLORC,
    XXLORf,
    XXLXOR,
    XXLXORdpz,
    XXLXORspz,
    XXLXORz,
    XXSEL))
# 156 "/Users/ilg/MyProjects/xpack.github/docusaurus/web-llvm.git/llvm-project/llvm/lib/Target/PowerPC/PPCMacroFusion.def" 2



# 32 "/Users/ilg/MyProjects/xpack.github/docusaurus/web-llvm.git/llvm-project/llvm/lib/Target/PowerPC/PPCMacroFusion.cpp" 2)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUSION_FEATURE<a id="a9180da3be917e7829faaffae67e7ac05a9003d2408851efdef7ade3283f23b823"></a></td>
<td class="doxyEnumItemDescription">
 (=(AddiLoad, hasAddiLoadFusion, 2, 
               FUSION_OP_SET(ADDI, ADDI8, ADDItocL, ADDItocL8), 
               FUSION_OP_SET(LXVD2X, LXVW4X, LXVDSX, LVEBX, LVEHX, LVEWX, 
                             LVX, LXSDX))


FUSION_FEATURE(AddisLoad, hasAddisLoadFusion, 2, 
               FUSION_OP_SET(ADDIS, ADDIS8, ADDIStocHA8), 
               FUSION_OP_SET(LD, LBZ, LBZ8, LHZ, LHZ8, LWZ, LWZ8))



FUSION_FEATURE(ArithAdd, hasArithAddFusion, -1,
               FUSION_OP_SET(ADD4, ADD8, MULLD), FUSION_OP_SET(ADD4, ADD8))


FUSION_FEATURE(ArithLogical, hasAddLogicalFusion, -1,
               FUSION_OP_SET(ADD4, ADD8, SUBF, SUBF8),
               FUSION_OP_SET(AND, AND8, OR, OR8, NAND, NAND8, NOR, NOR8))


FUSION_FEATURE(LogicalArith, hasLogicalAddFusion, -1,
               FUSION_OP_SET(AND, ANDC, EQV, NAND, NOR, OR, ORC, XOR, AND8,
                             ANDC8, EQV8, NAND8, NOR8, OR8, ORC8, XOR8),
               FUSION_OP_SET(ADD4, ADD8, SUBF, SUBF8))


FUSION_FEATURE(Logical, hasLogicalFusion, -1,
               FUSION_OP_SET(AND, ANDC, EQV, NAND, NOR, OR, ORC, XOR, AND8,
                             ANDC8, EQV8, NAND8, NOR8, OR8, ORC8, XOR8),
               FUSION_OP_SET(AND, ANDC, EQV, NAND, NOR, OR, ORC, XOR, AND8,
                             ANDC8, EQV8, NAND8, NOR8, OR8, ORC8, XOR8))


FUSION_FEATURE(VecAdd, hasArithAddFusion, -1, FUSION_OP_SET(VADDUDM),
               FUSION_OP_SET(VADDUDM))


FUSION_FEATURE(VecLogical, hasLogicalFusion, -1,
               FUSION_OP_SET(VAND, VANDC, VEQV, VNAND, VNOR, VOR, VORC, VXOR),
               FUSION_OP_SET(VAND, VANDC, VEQV, VNAND, VNOR, VOR, VORC, VXOR))



FUSION_FEATURE(SldiAdd, hasArithAddFusion, -1, FUSION_OP_SET(RLDICR, RLDICR_32),
               FUSION_OP_SET(ADD4, ADD8, SUBF, SUBF8))


FUSION_FEATURE(RotateLeftXor, hasSha3Fusion, 1,
               FUSION_OP_SET(RLDICL, RLDICL_32, RLDICL_32_64),
               FUSION_OP_SET(XOR, XOR8))


FUSION_FEATURE(RotateRightXor, hasSha3Fusion, 1,
               FUSION_OP_SET(RLDICR, RLDICR_32), FUSION_OP_SET(XOR, XOR8))







FUSION_FEATURE(LoadCmp1, hasCompareFusion, 1,
               FUSION_OP_SET(LBZ, LBZ8, LBZX, LBZX8, LBZXTLS, LBZXTLS_,
                             LBZXTLS_32, LHZ, LHZ8, LHZX, LHZX8, LHZXTLS,
                             LHZXTLS_, LHZXTLS_32, LWZ, LWZ8, LWZX, LWZX8,
                             LWZXTLS, LWZXTLS_, LWZXTLS_32),
               FUSION_OP_SET(CMPDI, CMPLDI, CMPLWI))



FUSION_FEATURE(LoadCmp2, hasCompareFusion, 1,
               FUSION_OP_SET(LD, LDX, LDXTLS, LDXTLS_),
               FUSION_OP_SET(CMPDI, CMPLDI))


FUSION_FEATURE(LoadCmp3, hasCompareFusion, 1,
               FUSION_OP_SET(LHA, LHA8, LHAX, LHAX8, LWA, LWA_32, LWAX,
                             LWAX_32),
               FUSION_OP_SET(CMPLDI, CMPLWI))


FUSION_FEATURE(OriOris, hasWideImmFusion, 1, FUSION_OP_SET(ORI, ORI8),
               FUSION_OP_SET(ORIS, ORIS8))


FUSION_FEATURE(LisOri, hasWideImmFusion, 1, FUSION_OP_SET(LIS, LIS8),
               FUSION_OP_SET(ORI, ORI8))


FUSION_FEATURE(OrisOri, hasWideImmFusion, 1, FUSION_OP_SET(ORIS, ORIS8),
               FUSION_OP_SET(ORI, ORI8))


FUSION_FEATURE(XoriXoris, hasWideImmFusion, 1, FUSION_OP_SET(XORI, XORI8),
               FUSION_OP_SET(XORIS, XORIS8))


FUSION_FEATURE(XorisXori, hasWideImmFusion, 1, FUSION_OP_SET(XORIS, XORIS8),
               FUSION_OP_SET(XORI, XORI8))


FUSION_FEATURE(AddisAddi, hasWideImmFusion, 1,
               FUSION_OP_SET(ADDIS, ADDIS8, ADDIStocHA8, ADDIStocHA),
               FUSION_OP_SET(ADDI, ADDI8, ADDItocL8, ADDItocL))


FUSION_FEATURE(AddiAddis, hasWideImmFusion, 1,
               FUSION_OP_SET(ADDI, ADDI8, ADDItocL8, ADDItocL),
               FUSION_OP_SET(ADDIS, ADDIS8, ADDIStocHA8, ADDIStocHA))


FUSION_FEATURE(ZeroMoveCTR, hasZeroMoveFusion, -1,
               FUSION_OP_SET(MTCTR, MTCTRloop, MTSPR8, MTSPR),
               FUSION_OP_SET(BCCTR, BCCTRn, BCCTR8, BCCTR8n, BCCTRL, BCCTRLn,
                             BCCTRL8, BCCTRL8n, gBCCTR, gBCCTRL))


FUSION_FEATURE(ZeroMoveLR, hasZeroMoveFusion, -1,
               FUSION_OP_SET(MTLR8, MTLR, MTSPR8, MTSPR),
               FUSION_OP_SET(BCLR, BCLRn, gBCLR, BCLRL, BCLRLn, gBCLRL))

# 1 "/Users/ilg/MyProjects/xpack.github/docusaurus/web-llvm.git/llvm-project/llvm/lib/Target/PowerPC/PPCBack2BackFusion.def" 1




FUSION_FEATURE(GeneralBack2Back, hasBack2BackFusion, -1,
  FUSION_OP_SET(ADD4,
    ADD4O,
    ADD4TLS,
    ADD4_rec,
    ADD8,
    ADD8O,
    ADD8TLS,
    ADD8TLS_,
    ADD8_rec,
    ADDE,
    ADDE8,
    ADDE8O,
    ADDEO,
    ADDEX,
    ADDEX8,
    ADDI,
    ADDI8,
    ADDIC,
    ADDIC8,
    ADDIS,
    ADDIS8,
    ADDISdtprelHA32,
    ADDIStocHA,
    ADDIStocHA8,
    ADDIdtprelL32,
    ADDItlsldLADDR32,
    ADDItocL8,
    ADDME,
    ADDME8,
    ADDME8O,
    ADDMEO,
    ADDZE,
    ADDZE8,
    ADDZE8O,
    ADDZEO,
    AND,
    AND8,
    AND8_rec,
    ANDC,
    ANDC8,
    ANDC8_rec,
    ANDC_rec,
    ANDI8_rec,
    ANDIS8_rec,
    ANDIS_rec,
    ANDI_rec,
    AND_rec,
    CBCDTD,
    CBCDTD8,
    CDTBCD,
    CDTBCD8,
    CMPB,
    CMPB8,
    CNTLZD,
    CNTLZD_rec,
    CNTLZW,
    CNTLZW8,
    CNTLZW8_rec,
    CNTLZW_rec,
    CNTTZD,
    CNTTZD_rec,
    CNTTZW,
    CNTTZW8,
    CNTTZW8_rec,
    CNTTZW_rec,
    EQV,
    EQV8,
    EQV8_rec,
    EQV_rec,
    EXTSB,
    EXTSB8,
    EXTSB8_32_64,
    EXTSB8_rec,
    EXTSB_rec,
    EXTSH,
    EXTSH8,
    EXTSH8_32_64,
    EXTSH8_rec,
    EXTSH_rec,
    EXTSW,
    EXTSWSLI,
    EXTSWSLI_32_64,
    EXTSWSLI_32_64_rec,
    EXTSWSLI_rec,
    EXTSW_32,
    EXTSW_32_64,
    EXTSW_32_64_rec,
    EXTSW_rec,
    FABSD,
    FABSS,
    FCPSGND,
    FCPSGNS,
    FMR,
    FNABSD,
    FNABSS,
    FNEGD,
    FNEGS,
    ISEL,
    ISEL8,
    LI,
    LI8,
    LIS,
    LIS8,
    MFCTR,
    MFCTR8,
    MFLR,
    MFLR8,
    MFOCRF,
    MFOCRF8,
    MFVRD,
    MFVRWZ,
    MFVSRD,
    MFVSRWZ,
    MTVRD,
    MTVRWA,
    MTVRWZ,
    MTVSRBM,
    MTVSRBMI,
    MTVSRD,
    MTVSRDM,
    MTVSRHM,
    MTVSRQM,
    MTVSRWA,
    MTVSRWM,
    MTVSRWZ,
    NAND,
    NAND8,
    NAND8_rec,
    NAND_rec,
    NEG,
    NEG8,
    NEG8O,
    NEG8_rec,
    NEGO,
    NEG_rec,
    NOP,
    NOP_GT_PWR6,
    NOP_GT_PWR7,
    NOR,
    NOR8,
    NOR8_rec,
    NOR_rec,
    OR,
    OR8,
    OR8_rec,
    ORC,
    ORC8,
    ORC8_rec,
    ORC_rec,
    ORI,
    ORI8,
    ORIS,
    ORIS8,
    OR_rec,
    POPCNTB,
    POPCNTB8,
    POPCNTD,
    POPCNTW,
    RLDCL,
    RLDCL_rec,
    RLDCR,
    RLDCR_rec,
    RLDIC,
    RLDICL,
    RLDICL_32,
    RLDICL_32_64,
    RLDICL_32_rec,
    RLDICL_rec,
    RLDICR,
    RLDICR_32,
    RLDICR_rec,
    RLDIC_rec,
    RLDIMI,
    RLDIMI_rec,
    RLWIMI,
    RLWIMI8,
    RLWIMI8_rec,
    RLWIMI_rec,
    RLWINM,
    RLWINM8,
    RLWINM8_rec,
    RLWINM_rec,
    RLWNM,
    RLWNM8,
    RLWNM8_rec,
    RLWNM_rec,
    SETB,
    SETB8,
    SETBC,
    SETBC8,
    SETBCR,
    SETBCR8,
    SETNBC,
    SETNBC8,
    SETNBCR,
    SETNBCR8,
    SLD,
    SLD_rec,
    SLW,
    SLW8,
    SLW8_rec,
    SLW_rec,
    SRAD,
    SRADI,
    SRADI_32,
    SRAW,
    SRAWI,
    SRD,
    SRD_rec,
    SRW,
    SRW8,
    SRW8_rec,
    SRW_rec,
    SUBF,
    SUBF8,
    SUBF8O,
    SUBF8_rec,
    SUBFE,
    SUBFE8,
    SUBFE8O,
    SUBFEO,
    SUBFIC,
    SUBFIC8,
    SUBFME,
    SUBFME8,
    SUBFME8O,
    SUBFMEO,
    SUBFO,
    SUBFZE,
    SUBFZE8,
    SUBFZE8O,
    SUBFZEO,
    SUBF_rec,
    VABSDUB,
    VABSDUH,
    VABSDUW,
    VADDCUW,
    VADDSBS,
    VADDSHS,
    VADDSWS,
    VADDUBM,
    VADDUBS,
    VADDUDM,
    VADDUHM,
    VADDUHS,
    VADDUWM,
    VADDUWS,
    VAND,
    VANDC,
    VAVGSB,
    VAVGSH,
    VAVGSW,
    VAVGUB,
    VAVGUH,
    VAVGUW,
    VCLZB,
    VCLZD,
    VCLZH,
    VCLZW,
    VCMPBFP,
    VCMPBFP_rec,
    VCMPEQFP,
    VCMPEQFP_rec,
    VCMPEQUB,
    VCMPEQUB_rec,
    VCMPEQUD,
    VCMPEQUD_rec,
    VCMPEQUH,
    VCMPEQUH_rec,
    VCMPEQUQ,
    VCMPEQUQ_rec,
    VCMPEQUW,
    VCMPEQUW_rec,
    VCMPGEFP,
    VCMPGEFP_rec,
    VCMPGTFP,
    VCMPGTFP_rec,
    VCMPGTSB,
    VCMPGTSB_rec,
    VCMPGTSD,
    VCMPGTSD_rec,
    VCMPGTSH,
    VCMPGTSH_rec,
    VCMPGTSQ,
    VCMPGTSQ_rec,
    VCMPGTSW,
    VCMPGTSW_rec,
    VCMPGTUB,
    VCMPGTUB_rec,
    VCMPGTUD,
    VCMPGTUD_rec,
    VCMPGTUH,
    VCMPGTUH_rec,
    VCMPGTUQ,
    VCMPGTUQ_rec,
    VCMPGTUW,
    VCMPGTUW_rec,
    VCMPNEB,
    VCMPNEB_rec,
    VCMPNEH,
    VCMPNEH_rec,
    VCMPNEW,
    VCMPNEW_rec,
    VCMPNEZB,
    VCMPNEZB_rec,
    VCMPNEZH,
    VCMPNEZH_rec,
    VCMPNEZW,
    VCMPNEZW_rec,
    VCNTMBB,
    VCNTMBD,
    VCNTMBH,
    VCNTMBW,
    VCTZB,
    VCTZD,
    VCTZH,
    VCTZW,
    VEQV,
    VEXPANDBM,
    VEXPANDDM,
    VEXPANDHM,
    VEXPANDQM,
    VEXPANDWM,
    VEXTRACTBM,
    VEXTRACTDM,
    VEXTRACTHM,
    VEXTRACTQM,
    VEXTRACTWM,
    VEXTSB2D,
    VEXTSB2Ds,
    VEXTSB2W,
    VEXTSB2Ws,
    VEXTSD2Q,
    VEXTSH2D,
    VEXTSH2Ds,
    VEXTSH2W,
    VEXTSH2Ws,
    VEXTSW2D,
    VEXTSW2Ds,
    VMAXFP,
    VMAXSB,
    VMAXSD,
    VMAXSH,
    VMAXSW,
    VMAXUB,
    VMAXUD,
    VMAXUH,
    VMAXUW,
    VMINFP,
    VMINSB,
    VMINSD,
    VMINSH,
    VMINSW,
    VMINUB,
    VMINUD,
    VMINUH,
    VMINUW,
    VMRGEW,
    VMRGOW,
    VNAND,
    VNEGD,
    VNEGW,
    VNOR,
    VOR,
    VORC,
    VPOPCNTB,
    VPOPCNTD,
    VPOPCNTH,
    VPOPCNTW,
    VPRTYBD,
    VPRTYBW,
    VRLB,
    VRLD,
    VRLDMI,
    VRLDNM,
    VRLH,
    VRLW,
    VRLWMI,
    VRLWNM,
    VSEL,
    VSHASIGMAD,
    VSHASIGMAW,
    VSLB,
    VSLD,
    VSLH,
    VSLW,
    VSRAB,
    VSRAD,
    VSRAH,
    VSRAW,
    VSRB,
    VSRD,
    VSRH,
    VSRW,
    VSUBCUW,
    VSUBSBS,
    VSUBSHS,
    VSUBSWS,
    VSUBUBM,
    VSUBUBS,
    VSUBUDM,
    VSUBUHM,
    VSUBUHS,
    VSUBUWM,
    VSUBUWS,
    VXOR,
    V_SET0,
    V_SET0B,
    V_SET0H,
    XOR,
    XOR8,
    XOR8_rec,
    XORI,
    XORI8,
    XORIS,
    XORIS8,
    XOR_rec,
    XSABSDP,
    XSABSQP,
    XSCMPEQDP,
    XSCMPGEDP,
    XSCMPGTDP,
    XSCPSGNDP,
    XSCPSGNQP,
    XSCVHPDP,
    XSCVSPDPN,
    XSIEXPDP,
    XSIEXPQP,
    XSMAXCDP,
    XSMAXDP,
    XSMAXJDP,
    XSMINCDP,
    XSMINDP,
    XSMINJDP,
    XSNABSDP,
    XSNABSDPs,
    XSNABSQP,
    XSNEGDP,
    XSNEGQP,
    XSXEXPDP,
    XSXEXPQP,
    XSXSIGDP,
    XVABSDP,
    XVABSSP,
    XVCMPEQDP,
    XVCMPEQDP_rec,
    XVCMPEQSP,
    XVCMPEQSP_rec,
    XVCMPGEDP,
    XVCMPGEDP_rec,
    XVCMPGESP,
    XVCMPGESP_rec,
    XVCMPGTDP,
    XVCMPGTDP_rec,
    XVCMPGTSP,
    XVCMPGTSP_rec,
    XVCPSGNDP,
    XVCPSGNSP,
    XVCVHPSP,
    XVIEXPDP,
    XVIEXPSP,
    XVMAXDP,
    XVMAXSP,
    XVMINDP,
    XVMINSP,
    XVNABSDP,
    XVNABSSP,
    XVNEGDP,
    XVNEGSP,
    XVTSTDCDP,
    XVTSTDCSP,
    XVXEXPDP,
    XVXEXPSP,
    XVXSIGDP,
    XVXSIGSP,
    XXLAND,
    XXLANDC,
    XXLEQV,
    XXLEQVOnes,
    XXLNAND,
    XXLNOR,
    XXLOR,
    XXLORC,
    XXLORf,
    XXLXOR,
    XXLXORdpz,
    XXLXORspz,
    XXLXORz,
    XXSEL),
  FUSION_OP_SET(ADD4,
    ADD4O,
    ADD4TLS,
    ADD4_rec,
    ADD8,
    ADD8O,
    ADD8TLS,
    ADD8TLS_,
    ADD8_rec,
    ADDE,
    ADDE8,
    ADDE8O,
    ADDEO,
    ADDEX,
    ADDEX8,
    ADDI,
    ADDI8,
    ADDIC,
    ADDIC8,
    ADDIS,
    ADDIS8,
    ADDISdtprelHA32,
    ADDIStocHA,
    ADDIStocHA8,
    ADDIdtprelL32,
    ADDItlsldLADDR32,
    ADDItocL8,
    ADDME,
    ADDME8,
    ADDME8O,
    ADDMEO,
    ADDZE,
    ADDZE8,
    ADDZE8O,
    ADDZEO,
    AND,
    AND8,
    AND8_rec,
    ANDC,
    ANDC8,
    ANDC8_rec,
    ANDC_rec,
    ANDI8_rec,
    ANDIS8_rec,
    ANDIS_rec,
    ANDI_rec,
    AND_rec,
    CBCDTD,
    CBCDTD8,
    CDTBCD,
    CDTBCD8,
    CMPB,
    CMPB8,
    CMPD,
    CMPDI,
    CMPEQB,
    CMPLD,
    CMPLDI,
    CMPLW,
    CMPLWI,
    CMPRB,
    CMPRB8,
    CMPW,
    CMPWI,
    CNTLZD,
    CNTLZD_rec,
    CNTLZW,
    CNTLZW8,
    CNTLZW8_rec,
    CNTLZW_rec,
    CNTTZD,
    CNTTZD_rec,
    CNTTZW,
    CNTTZW8,
    CNTTZW8_rec,
    CNTTZW_rec,
    CR6SET,
    CR6UNSET,
    CRAND,
    CRANDC,
    CREQV,
    CRNAND,
    CRNOR,
    CROR,
    CRORC,
    CRSET,
    CRUNSET,
    CRXOR,
    DSS,
    DSSALL,
    DST,
    DST64,
    DSTST,
    DSTST64,
    DSTSTT,
    DSTSTT64,
    DSTT,
    DSTT64,
    EQV,
    EQV8,
    EQV8_rec,
    EQV_rec,
    EXTSB,
    EXTSB8,
    EXTSB8_32_64,
    EXTSB8_rec,
    EXTSB_rec,
    EXTSH,
    EXTSH8,
    EXTSH8_32_64,
    EXTSH8_rec,
    EXTSH_rec,
    EXTSW,
    EXTSWSLI,
    EXTSWSLI_32_64,
    EXTSWSLI_32_64_rec,
    EXTSWSLI_rec,
    EXTSW_32,
    EXTSW_32_64,
    EXTSW_32_64_rec,
    EXTSW_rec,
    FABSD,
    FABSS,
    FCMPOD,
    FCMPOS,
    FCMPUD,
    FCMPUS,
    FCPSGND,
    FCPSGNS,
    FMR,
    FNABSD,
    FNABSS,
    FNEGD,
    FNEGS,
    FTDIV,
    FTSQRT,
    ISEL,
    ISEL8,
    LI,
    LI8,
    LIS,
    LIS8,
    MCRF,
    MCRXRX,
    MFCTR,
    MFCTR8,
    MFLR,
    MFLR8,
    MFOCRF,
    MFOCRF8,
    MFVRD,
    MFVRWZ,
    MFVSRD,
    MFVSRWZ,
    MTCTR,
    MTCTR8,
    MTCTR8loop,
    MTCTRloop,
    MTLR,
    MTLR8,
    MTOCRF,
    MTOCRF8,
    MTVRD,
    MTVRWA,
    MTVRWZ,
    MTVSRBM,
    MTVSRBMI,
    MTVSRD,
    MTVSRDM,
    MTVSRHM,
    MTVSRQM,
    MTVSRWA,
    MTVSRWM,
    MTVSRWZ,
    NAND,
    NAND8,
    NAND8_rec,
    NAND_rec,
    NEG,
    NEG8,
    NEG8O,
    NEG8_rec,
    NEGO,
    NEG_rec,
    NOP,
    NOP_GT_PWR6,
    NOP_GT_PWR7,
    NOR,
    NOR8,
    NOR8_rec,
    NOR_rec,
    OR,
    OR8,
    OR8_rec,
    ORC,
    ORC8,
    ORC8_rec,
    ORC_rec,
    ORI,
    ORI8,
    ORIS,
    ORIS8,
    OR_rec,
    POPCNTB,
    POPCNTB8,
    POPCNTD,
    POPCNTW,
    RLDCL,
    RLDCL_rec,
    RLDCR,
    RLDCR_rec,
    RLDIC,
    RLDICL,
    RLDICL_32,
    RLDICL_32_64,
    RLDICL_32_rec,
    RLDICL_rec,
    RLDICR,
    RLDICR_32,
    RLDICR_rec,
    RLDIC_rec,
    RLDIMI,
    RLDIMI_rec,
    RLWIMI,
    RLWIMI8,
    RLWIMI8_rec,
    RLWIMI_rec,
    RLWINM,
    RLWINM8,
    RLWINM8_rec,
    RLWINM_rec,
    RLWNM,
    RLWNM8,
    RLWNM8_rec,
    RLWNM_rec,
    SETB,
    SETB8,
    SETBC,
    SETBC8,
    SETBCR,
    SETBCR8,
    SETNBC,
    SETNBC8,
    SETNBCR,
    SETNBCR8,
    SLD,
    SLD_rec,
    SLW,
    SLW8,
    SLW8_rec,
    SLW_rec,
    SRAD,
    SRADI,
    SRADI_32,
    SRAW,
    SRAWI,
    SRD,
    SRD_rec,
    SRW,
    SRW8,
    SRW8_rec,
    SRW_rec,
    SUBF,
    SUBF8,
    SUBF8O,
    SUBF8_rec,
    SUBFE,
    SUBFE8,
    SUBFE8O,
    SUBFEO,
    SUBFIC,
    SUBFIC8,
    SUBFME,
    SUBFME8,
    SUBFME8O,
    SUBFMEO,
    SUBFO,
    SUBFZE,
    SUBFZE8,
    SUBFZE8O,
    SUBFZEO,
    SUBF_rec,
    TD,
    TDI,
    TRAP,
    TW,
    TWI,
    VABSDUB,
    VABSDUH,
    VABSDUW,
    VADDCUW,
    VADDSBS,
    VADDSHS,
    VADDSWS,
    VADDUBM,
    VADDUBS,
    VADDUDM,
    VADDUHM,
    VADDUHS,
    VADDUWM,
    VADDUWS,
    VAND,
    VANDC,
    VAVGSB,
    VAVGSH,
    VAVGSW,
    VAVGUB,
    VAVGUH,
    VAVGUW,
    VCLZB,
    VCLZD,
    VCLZH,
    VCLZW,
    VCMPBFP,
    VCMPBFP_rec,
    VCMPEQFP,
    VCMPEQFP_rec,
    VCMPEQUB,
    VCMPEQUB_rec,
    VCMPEQUD,
    VCMPEQUD_rec,
    VCMPEQUH,
    VCMPEQUH_rec,
    VCMPEQUQ,
    VCMPEQUQ_rec,
    VCMPEQUW,
    VCMPEQUW_rec,
    VCMPGEFP,
    VCMPGEFP_rec,
    VCMPGTFP,
    VCMPGTFP_rec,
    VCMPGTSB,
    VCMPGTSB_rec,
    VCMPGTSD,
    VCMPGTSD_rec,
    VCMPGTSH,
    VCMPGTSH_rec,
    VCMPGTSQ,
    VCMPGTSQ_rec,
    VCMPGTSW,
    VCMPGTSW_rec,
    VCMPGTUB,
    VCMPGTUB_rec,
    VCMPGTUD,
    VCMPGTUD_rec,
    VCMPGTUH,
    VCMPGTUH_rec,
    VCMPGTUQ,
    VCMPGTUQ_rec,
    VCMPGTUW,
    VCMPGTUW_rec,
    VCMPNEB,
    VCMPNEB_rec,
    VCMPNEH,
    VCMPNEH_rec,
    VCMPNEW,
    VCMPNEW_rec,
    VCMPNEZB,
    VCMPNEZB_rec,
    VCMPNEZH,
    VCMPNEZH_rec,
    VCMPNEZW,
    VCMPNEZW_rec,
    VCMPSQ,
    VCMPUQ,
    VCNTMBB,
    VCNTMBD,
    VCNTMBH,
    VCNTMBW,
    VCTZB,
    VCTZD,
    VCTZH,
    VCTZW,
    VEQV,
    VEXPANDBM,
    VEXPANDDM,
    VEXPANDHM,
    VEXPANDQM,
    VEXPANDWM,
    VEXTRACTBM,
    VEXTRACTDM,
    VEXTRACTHM,
    VEXTRACTQM,
    VEXTRACTWM,
    VEXTSB2D,
    VEXTSB2Ds,
    VEXTSB2W,
    VEXTSB2Ws,
    VEXTSD2Q,
    VEXTSH2D,
    VEXTSH2Ds,
    VEXTSH2W,
    VEXTSH2Ws,
    VEXTSW2D,
    VEXTSW2Ds,
    VMAXFP,
    VMAXSB,
    VMAXSD,
    VMAXSH,
    VMAXSW,
    VMAXUB,
    VMAXUD,
    VMAXUH,
    VMAXUW,
    VMINFP,
    VMINSB,
    VMINSD,
    VMINSH,
    VMINSW,
    VMINUB,
    VMINUD,
    VMINUH,
    VMINUW,
    VMRGEW,
    VMRGOW,
    VNAND,
    VNEGD,
    VNEGW,
    VNOR,
    VOR,
    VORC,
    VPOPCNTB,
    VPOPCNTD,
    VPOPCNTH,
    VPOPCNTW,
    VPRTYBD,
    VPRTYBW,
    VRLB,
    VRLD,
    VRLDMI,
    VRLDNM,
    VRLH,
    VRLW,
    VRLWMI,
    VRLWNM,
    VSEL,
    VSHASIGMAD,
    VSHASIGMAW,
    VSLB,
    VSLD,
    VSLH,
    VSLW,
    VSRAB,
    VSRAD,
    VSRAH,
    VSRAW,
    VSRB,
    VSRD,
    VSRH,
    VSRW,
    VSUBCUW,
    VSUBSBS,
    VSUBSHS,
    VSUBSWS,
    VSUBUBM,
    VSUBUBS,
    VSUBUDM,
    VSUBUHM,
    VSUBUHS,
    VSUBUWM,
    VSUBUWS,
    VXOR,
    V_SET0,
    V_SET0B,
    V_SET0H,
    WAIT,
    WAITP10,
    XOR,
    XOR8,
    XOR8_rec,
    XORI,
    XORI8,
    XORIS,
    XORIS8,
    XOR_rec,
    XSABSDP,
    XSABSQP,
    XSCMPEQDP,
    XSCMPEXPDP,
    XSCMPGEDP,
    XSCMPGTDP,
    XSCMPODP,
    XSCMPUDP,
    XSCPSGNDP,
    XSCPSGNQP,
    XSCVHPDP,
    XSCVSPDPN,
    XSIEXPDP,
    XSIEXPQP,
    XSMAXCDP,
    XSMAXDP,
    XSMAXJDP,
    XSMINCDP,
    XSMINDP,
    XSMINJDP,
    XSNABSDP,
    XSNABSDPs,
    XSNABSQP,
    XSNEGDP,
    XSNEGQP,
    XSTDIVDP,
    XSTSQRTDP,
    XSTSTDCDP,
    XSTSTDCSP,
    XSXEXPDP,
    XSXEXPQP,
    XSXSIGDP,
    XVABSDP,
    XVABSSP,
    XVCMPEQDP,
    XVCMPEQDP_rec,
    XVCMPEQSP,
    XVCMPEQSP_rec,
    XVCMPGEDP,
    XVCMPGEDP_rec,
    XVCMPGESP,
    XVCMPGESP_rec,
    XVCMPGTDP,
    XVCMPGTDP_rec,
    XVCMPGTSP,
    XVCMPGTSP_rec,
    XVCPSGNDP,
    XVCPSGNSP,
    XVCVHPSP,
    XVIEXPDP,
    XVIEXPSP,
    XVMAXDP,
    XVMAXSP,
    XVMINDP,
    XVMINSP,
    XVNABSDP,
    XVNABSSP,
    XVNEGDP,
    XVNEGSP,
    XVTDIVDP,
    XVTDIVSP,
    XVTLSBB,
    XVTSQRTDP,
    XVTSQRTSP,
    XVTSTDCDP,
    XVTSTDCSP,
    XVXEXPDP,
    XVXEXPSP,
    XVXSIGDP,
    XVXSIGSP,
    XXLAND,
    XXLANDC,
    XXLEQV,
    XXLEQVOnes,
    XXLNAND,
    XXLNOR,
    XXLOR,
    XXLORC,
    XXLORf,
    XXLXOR,
    XXLXORdpz,
    XXLXORspz,
    XXLXORz,
    XXSEL))
# 156 "/Users/ilg/MyProjects/xpack.github/docusaurus/web-llvm.git/llvm-project/llvm/lib/Target/PowerPC/PPCMacroFusion.def" 2



# 32 "/Users/ilg/MyProjects/xpack.github/docusaurus/web-llvm.git/llvm-project/llvm/lib/Target/PowerPC/PPCMacroFusion.cpp" 2)
</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FusionFeature() {#ae68e7f1fb7eb8186bd289bcb5dba22ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCMacroFusion.cpp}::FusionFeature::FusionFeature (<a href="#a9180da3be917e7829faaffae67e7ac05">FusionKind</a> Kind, bool HasFeature, int Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afce7c3d42d830243e56b0191e205f35a">FusionOpSet</a> &amp; First, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afce7c3d42d830243e56b0191e205f35a">FusionOpSet</a> &amp; Second)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### depOpIdx() {#a7386ff218bee9b67c13c5bda1ba91be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; anonymous{PPCMacroFusion.cpp}::FusionFeature::depOpIdx ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

### getKind() {#a997c012fe47b359d899400919c8f962e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FusionKind anonymous{PPCMacroFusion.cpp}::FusionFeature::getKind ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

### hasOp1() {#ab9c6ab7c1c9b82843905ae1a520cfed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCMacroFusion.cpp}::FusionFeature::hasOp1 (unsigned Opc)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

### hasOp2() {#a81f9a13a1a2606a297fbfb685250afbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCMacroFusion.cpp}::FusionFeature::hasOp2 (unsigned Opc)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

### isSupported() {#a28da93339389153c3f7447403cfb254b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCMacroFusion.cpp}::FusionFeature::isSupported ()</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DepOpIdx {#a6e511285ad83e13f8aa0c0e816e8768e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{PPCMacroFusion.cpp}::FusionFeature::DepOpIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

### Kd {#a9baf5a73d6790d0325d105d8b3d95bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FusionKind anonymous{PPCMacroFusion.cpp}::FusionFeature::Kd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

### OpSet1 {#a9eb0699493ab1f70c81fc6a3ad64e5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FusionOpSet anonymous{PPCMacroFusion.cpp}::FusionFeature::OpSet1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

### OpSet2 {#ab0754158fec533e9c74c3c48963813b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FusionOpSet anonymous{PPCMacroFusion.cpp}::FusionFeature::OpSet2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

### Supported {#ab6f0f76cffeb9b1f9ebd65fe34a7950e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCMacroFusion.cpp}::FusionFeature::Supported</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmacrofusion-cpp">PPCMacroFusion.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
