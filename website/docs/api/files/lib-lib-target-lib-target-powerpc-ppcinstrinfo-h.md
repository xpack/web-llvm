---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `PPCInstrInfo.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">MCTargetDesc/PPCMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppc-h">PPC.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcregisterinfo-h">PPCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">llvm/CodeGen/LiveVariables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "PPCGenInstrInfo.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/imminstrinfo">ImmInstrInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loadimmediateinfo">LoadImmediateInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo">PPCInstrInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12de263eb2ee622714701bc1946fad6">GET_INSTRINFO_HEADER</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>&nbsp;&nbsp;&nbsp;PPC::INSTRUCTION_LIST_END</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3af7dd392d3f1ac0334a0bd9bcee7b7">Pwr8LoadOpcodes</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8467b8c357083adfbd9b946f88d27f2">Pwr9LoadOpcodes</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f385e94cf27ae7f3d7b553ff9d1b23">Pwr10LoadOpcodes</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4bd0708e970617d62c73a6dcdb8fa6">FutureLoadOpcodes</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeede7fb719ccff62a01eac19a67f1011">Pwr8StoreOpcodes</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3fe4088c4201675b2271e4a0b9fb352">Pwr9StoreOpcodes</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87737f1fa6b89788b36aed50ca83104c">Pwr10StoreOpcodes</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5e3fd5c7a6766a5ecffb1a6004032f">FutureStoreOpcodes</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a749eafd6d931bbd6e3ab69a33b6520f8">StoreOpcodesForSpill</a>&nbsp;&nbsp;&nbsp;  { <a href="#aeede7fb719ccff62a01eac19a67f1011">Pwr8StoreOpcodes</a>, <a href="#ae3fe4088c4201675b2271e4a0b9fb352">Pwr9StoreOpcodes</a>, <a href="#a87737f1fa6b89788b36aed50ca83104c">Pwr10StoreOpcodes</a>, <a href="#adf5e3fd5c7a6766a5ecffb1a6004032f">FutureStoreOpcodes</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b4746eb68842a31e5a8673ed46434a">LoadOpcodesForSpill</a>&nbsp;&nbsp;&nbsp;  { <a href="#ad3af7dd392d3f1ac0334a0bd9bcee7b7">Pwr8LoadOpcodes</a>, <a href="#ae8467b8c357083adfbd9b946f88d27f2">Pwr9LoadOpcodes</a>, <a href="#a33f385e94cf27ae7f3d7b553ff9d1b23">Pwr10LoadOpcodes</a>, <a href="#a6f4bd0708e970617d62c73a6dcdb8fa6">FutureLoadOpcodes</a> }</td>
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

## Macro Definitions

### FutureLoadOpcodes {#a6f4bd0708e970617d62c73a6dcdb8fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FutureLoadOpcodes&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                                                                            \
    PPC::LWZ, PPC::LD, PPC::LFD, PPC::LFS, PPC::RESTORE_CR,                    \
        PPC::RESTORE_CRBIT, PPC::LVX, PPC::LXV, PPC::DFLOADf64,                \
        PPC::DFLOADf32, PPC::SPILLTOVSR_LD, PPC::LXVP, PPC::RESTORE_ACC,       \
        PPC::RESTORE_UACC, PPC::RESTORE_WACC, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, PPC::RESTORE_QUADWORD   \
  }
</div>
</dd>
</dl>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### FutureStoreOpcodes {#adf5e3fd5c7a6766a5ecffb1a6004032f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FutureStoreOpcodes&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                                                                            \
    PPC::STW, PPC::STD, PPC::STFD, PPC::STFS, PPC::SPILL_CR, PPC::SPILL_CRBIT, \
        PPC::STVX, PPC::STXV, PPC::DFSTOREf64, PPC::DFSTOREf32,                \
        PPC::SPILLTOVSR_ST, PPC::STXVP, PPC::SPILL_ACC, PPC::SPILL_UACC,       \
        PPC::SPILL_WACC, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, PPC::SPILL_QUADWORD                          \
  }
</div>
</dd>
</dl>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_HEADER {#ab12de263eb2ee622714701bc1946fad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_HEADER</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### LoadOpcodesForSpill {#a32b4746eb68842a31e5a8673ed46434a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LoadOpcodesForSpill&nbsp;&nbsp;&nbsp;  { <a href="#ad3af7dd392d3f1ac0334a0bd9bcee7b7">Pwr8LoadOpcodes</a>, <a href="#ae8467b8c357083adfbd9b946f88d27f2">Pwr9LoadOpcodes</a>, <a href="#a33f385e94cf27ae7f3d7b553ff9d1b23">Pwr10LoadOpcodes</a>, <a href="#a6f4bd0708e970617d62c73a6dcdb8fa6">FutureLoadOpcodes</a> }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### NoInstr {#ad0752610c1da72547dce07755ea5d883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NoInstr&nbsp;&nbsp;&nbsp;PPC::INSTRUCTION_LIST_END</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### Pwr10LoadOpcodes {#a33f385e94cf27ae7f3d7b553ff9d1b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Pwr10LoadOpcodes&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                                                                            \
    PPC::LWZ, PPC::LD, PPC::LFD, PPC::LFS, PPC::RESTORE_CR,                    \
        PPC::RESTORE_CRBIT, PPC::LVX, PPC::LXV, PPC::DFLOADf64,                \
        PPC::DFLOADf32, PPC::SPILLTOVSR_LD, PPC::LXVP, PPC::RESTORE_ACC,       \
        PPC::RESTORE_UACC, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, PPC::RESTORE_QUADWORD             \
  }
</div>
</dd>
</dl>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### Pwr10StoreOpcodes {#a87737f1fa6b89788b36aed50ca83104c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Pwr10StoreOpcodes&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                                                                            \
    PPC::STW, PPC::STD, PPC::STFD, PPC::STFS, PPC::SPILL_CR, PPC::SPILL_CRBIT, \
        PPC::STVX, PPC::STXV, PPC::DFSTOREf64, PPC::DFSTOREf32,                \
        PPC::SPILLTOVSR_ST, PPC::STXVP, PPC::SPILL_ACC, PPC::SPILL_UACC,       \
        <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, PPC::SPILL_QUADWORD                                  \
  }
</div>
</dd>
</dl>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### Pwr8LoadOpcodes {#ad3af7dd392d3f1ac0334a0bd9bcee7b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Pwr8LoadOpcodes&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                                                                            \
    PPC::LWZ, PPC::LD, PPC::LFD, PPC::LFS, PPC::RESTORE_CR,                    \
        PPC::RESTORE_CRBIT, PPC::LVX, PPC::LXVD2X, PPC::LXSDX, PPC::LXSSPX,    \
        PPC::SPILLTOVSR_LD, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, PPC::EVLDD,    \
        PPC::RESTORE_QUADWORD                                                  \
  }
</div>
</dd>
</dl>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### Pwr8StoreOpcodes {#aeede7fb719ccff62a01eac19a67f1011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Pwr8StoreOpcodes&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                                                                            \
    PPC::STW, PPC::STD, PPC::STFD, PPC::STFS, PPC::SPILL_CR, PPC::SPILL_CRBIT, \
        PPC::STVX, PPC::STXVD2X, PPC::STXSDX, PPC::STXSSPX,                    \
        PPC::SPILLTOVSR_ST, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, PPC::EVSTDD,   \
        PPC::SPILL_QUADWORD                                                    \
  }
</div>
</dd>
</dl>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### Pwr9LoadOpcodes {#ae8467b8c357083adfbd9b946f88d27f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Pwr9LoadOpcodes&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                                                                            \
    PPC::LWZ, PPC::LD, PPC::LFD, PPC::LFS, PPC::RESTORE_CR,                    \
        PPC::RESTORE_CRBIT, PPC::LVX, PPC::LXV, PPC::DFLOADf64,                \
        PPC::DFLOADf32, PPC::SPILLTOVSR_LD, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>,         \
        <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, PPC::RESTORE_QUADWORD                                \
  }
</div>
</dd>
</dl>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### Pwr9StoreOpcodes {#ae3fe4088c4201675b2271e4a0b9fb352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Pwr9StoreOpcodes&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  {                                                                            \
    PPC::STW, PPC::STD, PPC::STFD, PPC::STFS, PPC::SPILL_CR, PPC::SPILL_CRBIT, \
        PPC::STVX, PPC::STXV, PPC::DFSTOREf64, PPC::DFSTOREf32,                \
        PPC::SPILLTOVSR_ST, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>, <a href="#ad0752610c1da72547dce07755ea5d883">NoInstr</a>,       \
        PPC::SPILL_QUADWORD                                                    \
  }
</div>
</dd>
</dl>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

### StoreOpcodesForSpill {#a749eafd6d931bbd6e3ab69a33b6520f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define StoreOpcodesForSpill&nbsp;&nbsp;&nbsp;  { <a href="#aeede7fb719ccff62a01eac19a67f1011">Pwr8StoreOpcodes</a>, <a href="#ae3fe4088c4201675b2271e4a0b9fb352">Pwr9StoreOpcodes</a>, <a href="#a87737f1fa6b89788b36aed50ca83104c">Pwr10StoreOpcodes</a>, <a href="#adf5e3fd5c7a6766a5ecffb1a6004032f">FutureStoreOpcodes</a> }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
