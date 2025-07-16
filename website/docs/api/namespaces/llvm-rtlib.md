---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/rtlib
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `RTLIB` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::RTLIB { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rtlib/runtimelibcallsinfo">RuntimeLibcallsInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A simple container for information about the supported runtime calls. <a href="/web-llvm/docs/api/structs/llvm/rtlib/runtimelibcallsinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Libcall { <a href="#a50a0bab21f1d14a86a1483ec283e4447">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> enum - This enum defines all of the runtime library calls the backend can emit. <a href="#a50a0bab21f1d14a86a1483ec283e4447">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea94ed67dbfe2a4e0aa7121da40b0e94">getFPLibCall</a> (EVT VT, Libcall Call_F32, Libcall Call_F64, Libcall Call_F80, Libcall Call_F128, Libcall Call_PPCF128)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetFPLibCall - Helper to return the right libcall for the given floating point type, or UNKNOWN_LIBCALL if there is none. <a href="#aea94ed67dbfe2a4e0aa7121da40b0e94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82ac391f77e4b35af455c9c1f9d7fba">getFPEXT</a> (EVT OpVT, EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFPEXT - Return the FPEXT_*_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#ab82ac391f77e4b35af455c9c1f9d7fba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba26b1883eac90bc8f0c2b51a5377545">getFPROUND</a> (EVT OpVT, EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFPROUND - Return the FPROUND_*_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#aba26b1883eac90bc8f0c2b51a5377545">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70a6cd6c880ca47e604870efe33eba4">getFPTOSINT</a> (EVT OpVT, EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFPTOSINT - Return the FPTOSINT_*_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#aa70a6cd6c880ca47e604870efe33eba4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e747e8b302cf5ad8e1d5ecade1937c">getFPTOUINT</a> (EVT OpVT, EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFPTOUINT - Return the FPTOUINT_*_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#a80e747e8b302cf5ad8e1d5ecade1937c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11ba84d43a1ba5d6c1e1c645d34a0dd9">getSINTTOFP</a> (EVT OpVT, EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSINTTOFP - Return the SINTTOFP_*_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#a11ba84d43a1ba5d6c1e1c645d34a0dd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c139798e0933ade84b12ac860b593de">getUINTTOFP</a> (EVT OpVT, EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getUINTTOFP - Return the UINTTOFP_*_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#a3c139798e0933ade84b12ac860b593de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0616dff37f5666b8c8ab44b6a0e6c5b8">getPOWI</a> (EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPOWI - Return the POWI_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#a0616dff37f5666b8c8ab44b6a0e6c5b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac6012b94c35d58e5c9c03ffad6659a">getLDEXP</a> (EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLDEXP - Return the LDEXP_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#a3ac6012b94c35d58e5c9c03ffad6659a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4108acc1008674be6cf74b8980361e8f">getFREXP</a> (EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFREXP - Return the FREXP_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#a4108acc1008674be6cf74b8980361e8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b7f41eef07b5130e87122453bc7a01">getFSINCOS</a> (EVT RetVT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFSINCOS - Return the FSINCOS_* value for the given types, or UNKNOWN_LIBCALL if there is none. <a href="#a03b7f41eef07b5130e87122453bc7a01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a9c838f40a37e66a425b537704a9acd">getSYNC</a> (unsigned Opc, MVT VT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the SYNC_FETCH_AND_* value for the given opcode and type, or UNKNOWN_LIBCALL if there is none. <a href="#a3a9c838f40a37e66a425b537704a9acd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b0ade6b04479c67edcd6309b2dbff5">getOutlineAtomicHelper</a> (const Libcall(&amp;LC)[5][4], AtomicOrdering Order, uint64_t MemSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the outline atomics value for the given atomic ordering, access size and set of libcalls for a given atomic, or UNKNOWN_LIBCALL if there is none. <a href="#ae2b0ade6b04479c67edcd6309b2dbff5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d3dcfdec97d221021bfc9430beaba1">getOUTLINE_ATOMIC</a> (unsigned Opc, AtomicOrdering Order, MVT VT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the outline atomics value for the given opcode, atomic ordering and type, or UNKNOWN_LIBCALL if there is none. <a href="#ab0d3dcfdec97d221021bfc9430beaba1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6106aafebda4df95af50c030d688e118">getMEMCPY_ELEMENT_UNORDERED_ATOMIC</a> (uint64_t ElementSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMEMCPY_ELEMENT_UNORDERED_ATOMIC - Return MEMCPY_ELEMENT_UNORDERED_ATOMIC_* value for the given element size or UNKNOW_LIBCALL if there is none. <a href="#a6106aafebda4df95af50c030d688e118">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45528a36ebf2a1c82f3082d5ee656c3">getMEMMOVE_ELEMENT_UNORDERED_ATOMIC</a> (uint64_t ElementSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMEMMOVE_ELEMENT_UNORDERED_ATOMIC - Return MEMMOVE_ELEMENT_UNORDERED_ATOMIC_* value for the given element size or UNKNOW_LIBCALL if there is none. <a href="#af45528a36ebf2a1c82f3082d5ee656c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77a10f68d49a01ccc93b8b84af42f67">getMEMSET_ELEMENT_UNORDERED_ATOMIC</a> (uint64_t ElementSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMEMSET_ELEMENT_UNORDERED_ATOMIC - Return MEMSET_ELEMENT_UNORDERED_ATOMIC_* value for the given element size or UNKNOW_LIBCALL if there is none. <a href="#ac77a10f68d49a01ccc93b8b84af42f67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3184a09f23b382b5fd6f231f1d285883">initCmpLibcallCCs</a> (ISD::CondCode *CmpLibcallCCs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the default condition code on the libcalls. <a href="#a3184a09f23b382b5fd6f231f1d285883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### Libcall {#a50a0bab21f1d14a86a1483ec283e4447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RTLIB::Libcall </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> enum - This enum defines all of the runtime library calls the backend can emit.</p>


<p>The various long double types cannot be merged, because 80-bit library functions use "xf" and 128-bit use "tf".</p>


<p>When adding PPCF128 functions here, note that their names generally need to be overridden for Darwin with the xxx$LDBL128 form. See <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/runtimelibcalls-h">RuntimeLibcalls.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getFPEXT() {#ab82ac391f77e4b35af455c9c1f9d7fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getFPEXT (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OpVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFPEXT - Return the FPEXT_*_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab6fa4a61feadaf493e383ab28709d486">getConvRTLibDesc</a>.</p>

</div>
</div>

### getFPLibCall() {#aea94ed67dbfe2a4e0aa7121da40b0e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getFPLibCall (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a> Call_F32, <a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a> Call_F64, <a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a> Call_F80, <a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a> Call_F128, <a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a> Call_PPCF128)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetFPLibCall - Helper to return the right libcall for the given floating point type, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="#a4108acc1008674be6cf74b8980361e8f">getFREXP</a>, <a href="#a03b7f41eef07b5130e87122453bc7a01">getFSINCOS</a>, <a href="#a3ac6012b94c35d58e5c9c03ffad6659a">getLDEXP</a> and <a href="#a0616dff37f5666b8c8ab44b6a0e6c5b8">getPOWI</a>.</p>

</div>
</div>

### getFPROUND() {#aba26b1883eac90bc8f0c2b51a5377545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getFPROUND (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OpVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFPROUND - Return the FPROUND_*_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab6fa4a61feadaf493e383ab28709d486">getConvRTLibDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>.</p>

</div>
</div>

### getFPTOSINT() {#aa70a6cd6c880ca47e604870efe33eba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getFPTOSINT (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OpVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFPTOSINT - Return the FPTOSINT_*_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizefloattypes-cpp/#a219666604b8d066914b87cdf21db4e21">findFPToIntLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab6fa4a61feadaf493e383ab28709d486">getConvRTLibDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">llvm::LoongArchTargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

### getFPTOUINT() {#a80e747e8b302cf5ad8e1d5ecade1937c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getFPTOUINT (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OpVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFPTOUINT - Return the FPTOUINT_*_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizefloattypes-cpp/#a219666604b8d066914b87cdf21db4e21">findFPToIntLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab6fa4a61feadaf493e383ab28709d486">getConvRTLibDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

### getFREXP() {#a4108acc1008674be6cf74b8980361e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getFREXP (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFREXP - Return the FREXP_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Reference <a href="#aea94ed67dbfe2a4e0aa7121da40b0e94">getFPLibCall</a>.</p>

</div>
</div>

### getFSINCOS() {#a03b7f41eef07b5130e87122453bc7a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getFSINCOS (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFSINCOS - Return the FSINCOS_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Reference <a href="#aea94ed67dbfe2a4e0aa7121da40b0e94">getFPLibCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizedag-cpp/#a36c2b44ba7777f90513e20d73362e519">isSinCosLibcallAvailable</a>.</p>

</div>
</div>

### getLDEXP() {#a3ac6012b94c35d58e5c9c03ffad6659a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getLDEXP (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLDEXP - Return the LDEXP_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Reference <a href="#aea94ed67dbfe2a4e0aa7121da40b0e94">getFPLibCall</a>.</p>

</div>
</div>

### getMEMCPY\_ELEMENT\_UNORDERED\_ATOMIC() {#a6106aafebda4df95af50c030d688e118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getMEMCPY_ELEMENT_UNORDERED_ATOMIC (uint64_t ElementSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMEMCPY_ELEMENT_UNORDERED_ATOMIC - Return MEMCPY_ELEMENT_UNORDERED_ATOMIC_* value for the given element size or UNKNOW_LIBCALL if there is none.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c9c5b337e855fb0ce25e53c0bd3f992">llvm::SelectionDAG::getAtomicMemcpy</a>.</p>

</div>
</div>

### getMEMMOVE\_ELEMENT\_UNORDERED\_ATOMIC() {#af45528a36ebf2a1c82f3082d5ee656c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getMEMMOVE_ELEMENT_UNORDERED_ATOMIC (uint64_t ElementSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMEMMOVE_ELEMENT_UNORDERED_ATOMIC - Return MEMMOVE_ELEMENT_UNORDERED_ATOMIC_* value for the given element size or UNKNOW_LIBCALL if there is none.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abe645b6f7de2918e594b110f3c819b07">llvm::SelectionDAG::getAtomicMemmove</a>.</p>

</div>
</div>

### getMEMSET\_ELEMENT\_UNORDERED\_ATOMIC() {#ac77a10f68d49a01ccc93b8b84af42f67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getMEMSET_ELEMENT_UNORDERED_ATOMIC (uint64_t ElementSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMEMSET_ELEMENT_UNORDERED_ATOMIC - Return MEMSET_ELEMENT_UNORDERED_ATOMIC_* value for the given element size or UNKNOW_LIBCALL if there is none.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c60b6ae234b668266d9f21b0e1b8f89">llvm::SelectionDAG::getAtomicMemset</a>.</p>

</div>
</div>

### getOUTLINE\_ATOMIC() {#ab0d3dcfdec97d221021bfc9430beaba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getOUTLINE_ATOMIC (unsigned Opc, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Order, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the outline atomics value for the given opcode, atomic ordering and type, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74">llvm::ISD::ATOMIC_LOAD_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8ceaa81a8088781e5efec0886ffe86be">llvm::ISD::ATOMIC_LOAD_CLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c">llvm::ISD::ATOMIC_LOAD_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0">llvm::ISD::ATOMIC_LOAD_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">llvm::ISD::ATOMIC_SWAP</a>, <a href="#ae2b0ade6b04479c67edcd6309b2dbff5">getOutlineAtomicHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abdeb0e345d1884804b99c02dafb2eb08">llvm::MVT::isScalarInteger</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#a7caf1b72b68025eb17420cc4663ad64d">LCALL5</a>.</p>

</div>
</div>

### getOutlineAtomicHelper() {#ae2b0ade6b04479c67edcd6309b2dbff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getOutlineAtomicHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a50a0bab21f1d14a86a1483ec283e4447">Libcall</a>(&amp;) LC=[5][4], <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Order, uint64_t MemSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the outline atomics value for the given atomic ordering, access size and set of libcalls for a given atomic, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a>.</p>


<p>Referenced by <a href="#ab0d3dcfdec97d221021bfc9430beaba1">getOUTLINE_ATOMIC</a>.</p>

</div>
</div>

### getPOWI() {#a0616dff37f5666b8c8ab44b6a0e6c5b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getPOWI (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPOWI - Return the POWI_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Reference <a href="#aea94ed67dbfe2a4e0aa7121da40b0e94">getFPLibCall</a>.</p>

</div>
</div>

### getSINTTOFP() {#a11ba84d43a1ba5d6c1e1c645d34a0dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getSINTTOFP (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OpVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSINTTOFP - Return the SINTTOFP_*_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab6fa4a61feadaf493e383ab28709d486">getConvRTLibDesc</a>.</p>

</div>
</div>

### getSYNC() {#a3a9c838f40a37e66a425b537704a9acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getSYNC (unsigned Opc, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the SYNC_FETCH_AND_* value for the given opcode and type, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74">llvm::ISD::ATOMIC_LOAD_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30">llvm::ISD::ATOMIC_LOAD_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1cf8547d612d954d34aab1d4f78e7fa1">llvm::ISD::ATOMIC_LOAD_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7049708cb0e0703a467b95a506293aec">llvm::ISD::ATOMIC_LOAD_MIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a13a3e6402abf972278c6a7d5ee509f9d">llvm::ISD::ATOMIC_LOAD_NAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c">llvm::ISD::ATOMIC_LOAD_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3d12dbff6e50803982d0e92768a1479">llvm::ISD::ATOMIC_LOAD_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ca44a643714809ef384e7494604db14">llvm::ISD::ATOMIC_LOAD_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ff6f20a9255f7a333f4c9d25393674c">llvm::ISD::ATOMIC_LOAD_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0">llvm::ISD::ATOMIC_LOAD_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">llvm::ISD::ATOMIC_SWAP</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#a245c76edc10bd7711d8afdd278d4ae68">OP_TO_LIBCALL</a>.</p>

</div>
</div>

### getUINTTOFP() {#a3c139798e0933ade84b12ac860b593de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall llvm::RTLIB::getUINTTOFP (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OpVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getUINTTOFP - Return the UINTTOFP_*_* value for the given types, or UNKNOWN_LIBCALL if there is none.</p>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab6fa4a61feadaf493e383ab28709d486">getConvRTLibDesc</a>.</p>

</div>
</div>

### initCmpLibcallCCs() {#a3184a09f23b382b5fd6f231f1d285883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RTLIB::initCmpLibcallCCs (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> * CmpLibcallCCs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the default condition code on the libcalls.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a>, definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07aeded54fe1be320194e9ff0f5825df0e5">llvm::ISD::SETCC_INVALID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4">llvm::ISD::SETGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">llvm::ISD::SETGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac5c03f3e796f76a1a81cdf3f41e24493">llvm::TargetLoweringBase::TargetLoweringBase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">RuntimeLibcallUtil.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/runtimelibcalls-h">RuntimeLibcalls.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
