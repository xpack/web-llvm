---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/ppcisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `PPCISD` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::PPCISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#ad1c32e5bb1cb213fb836bc3d221e4f19">...</a> }</td>
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

### NodeType {#ad1c32e5bb1cb213fb836bc3d221e4f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPCISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="ad1c32e5bb1cb213fb836bc3d221e4f19abc3b4bb39053cdc6356a2b4cdd9fca36"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSEL<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aed93fe593cbca270b48f14bc00c5d73a"></a></td>
<td class="doxyEnumItemDescription">FSEL - Traditional three-operand fsel node</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSMAXC<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a9ff59d0440e169de36176333f9905ec7"></a></td>
<td class="doxyEnumItemDescription">XSMAXC[DQ]P, XSMINC[DQ]P - C-type min/max instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSMINC<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aa92d1e6695bd2774d420cfbf25f381b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCFID<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a7d46bc38a9f3de58adde307de9c5e892"></a></td>
<td class="doxyEnumItemDescription">FCFID - The FCFID instruction, taking an f64 operand and producing and f64 value containing the FP representation of the integer that was temporarily in the f64 operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCFIDU<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aea46f7cc94ac666cf413d686484ce45d"></a></td>
<td class="doxyEnumItemDescription">Newer FCFID[US] integer-to-floating-point conversion instructions for unsigned integers and single-precision outputs</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCFIDS<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a7e06dc9bf94c1b690b4379bec9d64962"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCFIDUS<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aa52f8d0b1001830d27a193285d4a7090"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCTIDZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a2a79156c141fbb0faadd358c767b906b"></a></td>
<td class="doxyEnumItemDescription">FCTI[D,W]Z - The FCTIDZ and FCTIWZ instructions, taking an f32 or f64 operand, producing an f64 value containing the integer representation of that FP value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCTIWZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a2a6e33357fd46c15294432ab65adecec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCTIDUZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a043df81d8fc961c94e42fc8fa2c71331"></a></td>
<td class="doxyEnumItemDescription">Newer FCTI[D,W]UZ floating-point-to-integer conversion instructions for unsigned integers with round toward zero</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCTIWUZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a88c7793fdfe5003a35e5cac9a3527eb9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEXTS<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ab1825d0c725f95300cef6d29474457c3"></a></td>
<td class="doxyEnumItemDescription">VEXTS, ByteWidth - takes an input in VSFRC and produces an output in VSFRC that is sign-extended from ByteWidth to a 64-byte integer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a3475aac39d7d3909ef94c56fbdfbe7a9"></a></td>
<td class="doxyEnumItemDescription">Reciprocal estimate instructions (unary FP ops)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRSQRTE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19abe7e3f85845897ad4b6270b32f8c7030"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FTSQRT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ac92e8ccc748c33e78a958b4a590abf42"></a></td>
<td class="doxyEnumItemDescription">Test instruction for software square root</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSQRT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a0742f4312740e5a3d92ed2dfbadc3572"></a></td>
<td class="doxyEnumItemDescription">Square root instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPERM<a id="ad1c32e5bb1cb213fb836bc3d221e4f19abd37e9e242507f9bcda602075a67c9dd"></a></td>
<td class="doxyEnumItemDescription">VPERM - The <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> VPERM <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XXSPLT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a58495c4d013cd9851f4ab527c3548b22"></a></td>
<td class="doxyEnumItemDescription">XXSPLT - The <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> VSX splat instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XXSPLTI_SP_TO_DP<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ac0436a181d9ba4cb7067186d26e52f56"></a></td>
<td class="doxyEnumItemDescription">XXSPLTI_SP_TO_DP - The <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> VSX splat instructions for immediates for converting immediate single precision numbers to double precision vector or scalar</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XXSPLTI32DX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a31d181189194ec87162affcc5e92b150"></a></td>
<td class="doxyEnumItemDescription">XXSPLTI32DX - The <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> XXSPLTI32DX instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECINSERT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a1ee1a9a5178726a6542ef8ab6d50fc03"></a></td>
<td class="doxyEnumItemDescription">VECINSERT - The <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> vector insert instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECSHL<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ad193a3cd768e4fb4bb4239e8bbaf6c7f"></a></td>
<td class="doxyEnumItemDescription">VECSHL - The <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> vector shift left instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XXPERMDI<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a5c9fa769fde0b5d1e1068e564fa14c93"></a></td>
<td class="doxyEnumItemDescription">XXPERMDI - The <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> XXPERMDI instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XXPERM<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ab8bc34e0a04f9698bc188b3d75488d38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPB<a id="ad1c32e5bb1cb213fb836bc3d221e4f19acbf3c8dc964f8156f3bc2749ba63869d"></a></td>
<td class="doxyEnumItemDescription">The CMPB instruction (takes two operands of i32 or i64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Hi<a id="ad1c32e5bb1cb213fb836bc3d221e4f19afaa3b6d013f5589d52186fb31c1507de"></a></td>
<td class="doxyEnumItemDescription">Hi/Lo - These represent the high and low 16-bit parts of a global address respectively</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lo<a id="ad1c32e5bb1cb213fb836bc3d221e4f19abcb9c462158b362a5edc6a1d754c9edb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DYNALLOC<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a098fa0d2b0ca58b9d504edb6a164ee54"></a></td>
<td class="doxyEnumItemDescription">The following two target-specific nodes are used for calls through function pointers in the 64-bit SVR4 ABI</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DYNAREAOFFSET<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ac4a20bcfe32da6eeed7334e31f358682"></a></td>
<td class="doxyEnumItemDescription">This instruction is lowered in <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">PPCRegisterInfo::eliminateFrameIndex</a> to compute an offset from native SP to the address of the most recent dynamic alloca</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PROBED_ALLOCA<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a93beacf6ed2253988c2898d81ff02a48"></a></td>
<td class="doxyEnumItemDescription">To avoid stack clash, allocation is performed by block and each block is probed</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GlobalBaseReg<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a9e4500d93af7f70fdff992d9d748559d"></a></td>
<td class="doxyEnumItemDescription">The result of the mflr at function entry, used for PIC code</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRL<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a1b0abca17bd696928f9399acfd3d1522"></a></td>
<td class="doxyEnumItemDescription">These nodes represent <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> shifts</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRA<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aad0d80bf5cf5a07b271e4357ed436f62"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHL<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a56a6aa00c6f25ef2c1f51277099a78a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNMSUB<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a24c65ae2b770c0b178a4c2458586b058"></a></td>
<td class="doxyEnumItemDescription">FNMSUB - Negated multiply-subtract instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTSWSLI<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ad7cc7f9bc57ea2f3d5deb4e305c50cc3"></a></td>
<td class="doxyEnumItemDescription">EXTSWSLI = The <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> extswsli instruction, which does an extend-sign word and shift left immediate</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRA_ADDZE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ad78bb5b4a8218f88e112b72fab5d508c"></a></td>
<td class="doxyEnumItemDescription">The combination of sra[wd]i and addze used to implemented signed integer division by a power of 2</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aa09dfd0e28e0ffea73ccfc88fb2fd95c"></a></td>
<td class="doxyEnumItemDescription">CALL - A direct function call</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_NOP<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ada865a374b524adeca1892f0eed6eb0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_NOTOC<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ab9d1ecf80764a45e6761396dfb71efdb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MTCTR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aa48a0d892596a0da3cf4a82c6ff5a91f"></a></td>
<td class="doxyEnumItemDescription">CHAIN,FLAG = <a href="#ad1c32e5bb1cb213fb836bc3d221e4f19aa48a0d892596a0da3cf4a82c6ff5a91f">MTCTR(VAL, CHAIN[, INFLAG])</a> - Directly corresponds to a MTCTR instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BCTRL<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a453b3ee2482b8a61bbcf5ce1cd6e395e"></a></td>
<td class="doxyEnumItemDescription">CHAIN,FLAG = <a href="#ad1c32e5bb1cb213fb836bc3d221e4f19a453b3ee2482b8a61bbcf5ce1cd6e395e">BCTRL(CHAIN, INFLAG)</a> - Directly corresponds to a BCTRL instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BCTRL_LOAD_TOC<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a7382bd1ceab96ffedb276ad49b4308ca"></a></td>
<td class="doxyEnumItemDescription">CHAIN,FLAG = <a href="#ad1c32e5bb1cb213fb836bc3d221e4f19a453b3ee2482b8a61bbcf5ce1cd6e395e">BCTRL(CHAIN, ADDR, INFLAG)</a> - The combination of a bctrl instruction and the TOC reload required on 64-bit <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a>, 32-bit AIX and 64-bit AIX</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_RM<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a0ca86fac87a16ac9aa26f6ab3625a5aa"></a></td>
<td class="doxyEnumItemDescription">The variants that implicitly define rounding mode for calls with strictfp semantics</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_NOP_RM<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a0a587e32cccf298ed32dfcefa59d08d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_NOTOC_RM<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a01495b70fc5bd028897c0b297fa2438f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BCTRL_RM<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aa82b0f1a7296f1ae77fe7a79dcd8631c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BCTRL_LOAD_TOC_RM<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a8733bcf440af126f3cd4df36ec026da6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a48f471d5b31fefcebe7a7be442b7e27e"></a></td>
<td class="doxyEnumItemDescription">Return with a glue operand, matched by 'blr'</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MFOCRF<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a58202903ffe35789bd984f290d83e11f"></a></td>
<td class="doxyEnumItemDescription">R32 = <a href="#ad1c32e5bb1cb213fb836bc3d221e4f19a58202903ffe35789bd984f290d83e11f">MFOCRF(CRREG, INFLAG)</a> - Represents the MFOCRF instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MFVSR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19af5896749994dc6b774ce5c9c4a64966a"></a></td>
<td class="doxyEnumItemDescription">Direct move from a VSX register to a GPR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MTVSRA<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a63a76994e79df471be43c2773b1d9003"></a></td>
<td class="doxyEnumItemDescription">Direct move from a GPR to a VSX register (algebraic)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MTVSRZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a19c6996c521458ff9fa40429470e5a45"></a></td>
<td class="doxyEnumItemDescription">Direct move from a GPR to a VSX register (zero)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUILD_FP128<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ab0e0c5eda3a0cf78f4c93f32e37b9439"></a></td>
<td class="doxyEnumItemDescription">Direct move of 2 consecutive GPR to a VSX register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUILD_SPE64<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a4726c939556eac0d044c4ba355e51e16"></a></td>
<td class="doxyEnumItemDescription">BUILD_SPE64 and EXTRACT_SPE are analogous to BUILD_PAIR and EXTRACT_ELEMENT but take f64 arguments instead of i64, as i64 is unsupported for this target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTRACT_SPE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a3f9ba00aac004b0e0ab81e7bb6e6a82f"></a></td>
<td class="doxyEnumItemDescription">Extract SPE register component, second argument is high or low</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SINT_VEC_TO_FP<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a3cafc18814a975a06f6e8a39926700b4"></a></td>
<td class="doxyEnumItemDescription">Extract a subvector from signed integer vector and convert to FP</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UINT_VEC_TO_FP<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ae29580d04452d6ce523cc25ba9f833a2"></a></td>
<td class="doxyEnumItemDescription">Extract a subvector from unsigned integer vector and convert to FP</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALAR_TO_VECTOR_PERMUTED<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a4b53fee9c411b207317f688e141e9128"></a></td>
<td class="doxyEnumItemDescription">PowerPC instructions that have SCALAR_TO_VECTOR semantics tend to place the value into the least significant element of the most significant doubleword in the vector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANDI_rec_1_EQ_BIT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a320d58aba8e7aee5461dbb44378a83ba"></a></td>
<td class="doxyEnumItemDescription">i1 = ANDI_rec_1_[EQ|GT]_BIT(i32 or i64 x) - Represents the result of the eq or gt bit of CR0 after executing andi</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANDI_rec_1_GT_BIT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a2f5e9e30846196a91f11a3e45e802eb7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READ_TIME_BASE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a4fed17be029140e1e4721aedfa68fa4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_SETJMP<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a819ce93b1bf9e907128d4a48ce356a21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_LONGJMP<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ae1846075ba0055d16c23e95fb9069efd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCMP<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a43a3ad5a512466965973ac46c8239c60"></a></td>
<td class="doxyEnumItemDescription">RESVEC = <a href="#ad1c32e5bb1cb213fb836bc3d221e4f19a43a3ad5a512466965973ac46c8239c60">VCMP(LHS, RHS, OPC)</a> - Represents one of the altivec VCMP* instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCMP_rec<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aaa7a0554c16e55d6c686d04418d15108"></a></td>
<td class="doxyEnumItemDescription">RESVEC, OUTFLAG = <a href="#ad1c32e5bb1cb213fb836bc3d221e4f19aaa7a0554c16e55d6c686d04418d15108">VCMP_rec(LHS, RHS, OPC)</a> - Represents one of the altivec VCMP*_rec instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_BRANCH<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a0992940624286ed6bc85cd7163501613"></a></td>
<td class="doxyEnumItemDescription">CHAIN = COND_BRANCH CHAIN, CRRC, OPC, DESTBB [, INFLAG] - This corresponds to the COND_BRANCH pseudo instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BDNZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a160ec67350dc5e964fc0a12a9cde1df8"></a></td>
<td class="doxyEnumItemDescription">CHAIN = BDNZ CHAIN, DESTBB - These are used to create counter-based loops</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BDZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19addb9d78754c1f2e6d765a0da913f0800"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FADDRTZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ad2b0da006c4560646ac3eb561a8b73b2"></a></td>
<td class="doxyEnumItemDescription">F8RC = FADDRTZ F8RC, F8RC - This is an FADD done with rounding towards zero</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MFFS<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aab6a046c536c71121190fefd548d6b25"></a></td>
<td class="doxyEnumItemDescription">F8RC = MFFS - This moves the FPSCR (not modeled) into the register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TC_RETURN<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aa4dc9f480c199614ca9475c7969ead06"></a></td>
<td class="doxyEnumItemDescription">TC_RETURN - A tail call return</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CR6SET<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a7fa84f3807a868c9e48e0928e3ac7f81"></a></td>
<td class="doxyEnumItemDescription">ch, gl = CR6[UN]SET ch, inglue - Toggle CR bit 6 for SVR4 vararg calls</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CR6UNSET<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a0a616f27a6f2de704ab3ed849b50b181"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC32_GOT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a6e3a9527c997e95ea74a9c377ba14add"></a></td>
<td class="doxyEnumItemDescription">GPRC = address of <em>GLOBAL_OFFSET_TABLE</em></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC32_PICGOT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a75da00c638a1f554457f78c4e2ef7a5c"></a></td>
<td class="doxyEnumItemDescription">GPRC = address of <em>GLOBAL_OFFSET_TABLE</em></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDIS_GOT_TPREL_HA<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a390f7ff6ebc81e2540d946d8d1061f29"></a></td>
<td class="doxyEnumItemDescription">G8RC = ADDIS_GOT_TPREL_HA x2, Symbol - Used by the initial-exec TLS model, produces an ADDIS8 instruction that adds the GOT base to sym@got@tprel@ha</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD_GOT_TPREL_L<a id="ad1c32e5bb1cb213fb836bc3d221e4f19af54af574e0a93231dd275e38ed4cf026"></a></td>
<td class="doxyEnumItemDescription">G8RC = LD_GOT_TPREL_L Symbol, G8RReg - Used by the initial-exec TLS model, produces a LD instruction with base register G8RReg and offset sym@got@tprel@l</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADD_TLS<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a606fcb46940146f9bb7ee312d6a4835f"></a></td>
<td class="doxyEnumItemDescription">G8RC = ADD_TLS G8RReg, Symbol - Can be used by the initial-exec and local-exec TLS models, produces an ADD instruction that adds the contents of G8RReg to the thread pointer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDIS_TLSGD_HA<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a968bba2363b57ced282bda51b19c8162"></a></td>
<td class="doxyEnumItemDescription">G8RC = ADDIS_TLSGD_HA x2, Symbol - For the general-dynamic TLS model, produces an ADDIS8 instruction that adds the GOT base register to sym@got@tlsgd@ha</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDI_TLSGD_L<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ac3043814fcbe457dc6a768c714864692"></a></td>
<td class="doxyEnumItemDescription">x3 = ADDI_TLSGD_L G8RReg, Symbol - For the general-dynamic TLS model, produces an ADDI8 instruction that adds G8RReg to sym@got@tlsgd@l and stores the result in X3</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_TLS_ADDR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a2c181ed9e9ec3fb57f7e8542df22f422"></a></td>
<td class="doxyEnumItemDescription">x3 = GET_TLS_ADDR x3, Symbol - For the general-dynamic TLS model, produces a call to __tls_get_addr(sym@tlsgd)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_TPOINTER<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ae427b9b3788c953b56cebb1dfc0e61fc"></a></td>
<td class="doxyEnumItemDescription">x3 = GET_TPOINTER - Used for the local- and initial-exec TLS model on 32-bit AIX, produces a call to .__get_tpointer to retrieve the thread pointer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDI_TLSGD_L_ADDR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a046e97f3becfbef4e0b3e1760a809dca"></a></td>
<td class="doxyEnumItemDescription">G8RC = ADDI_TLSGD_L_ADDR G8RReg, Symbol, Symbol - <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> that combines ADDI_TLSGD_L and GET_TLS_ADDR until expansion following register assignment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSGD_AIX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19addcc7a7066b3355e80163ae36bdac00e"></a></td>
<td class="doxyEnumItemDescription">GPRC = TLSGD_AIX, TOC_ENTRY, TOC_ENTRY G8RC = TLSGD_AIX, TOC_ENTRY, TOC_ENTRY <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> that combines two register copies of TOC entries (region handle into R3 and variable offset into R4) followed by a GET_TLS_ADDR node which will be expanded to a call to .__tls_get_addr</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_TLS_MOD_AIX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a8862af7d0d03a2e2689a8ea634913d96"></a></td>
<td class="doxyEnumItemDescription">x3 = GET_TLS_MOD_AIX _$TLSML - For the AIX local-dynamic TLS model, produces a call to .__tls_get_mod(_$TLSML@ml)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSLD_AIX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a09ab315581c1b578f529f618351ee400"></a></td>
<td class="doxyEnumItemDescription">[GP|G8]RC = TLSLD_AIX, <a href="#ad1c32e5bb1cb213fb836bc3d221e4f19a5ac8e8dafc2dd10379a59ceff7b237d6">TOC_ENTRY(module handle)</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> that requires a single input of the module handle TOC entry in R3, and generates a GET_TLS_MOD_AIX node which will be expanded into a call to .__tls_get_mod</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDIS_TLSLD_HA<a id="ad1c32e5bb1cb213fb836bc3d221e4f19abdad0d05f0b11932ef877b95832e31ea"></a></td>
<td class="doxyEnumItemDescription">G8RC = ADDIS_TLSLD_HA x2, Symbol - For the local-dynamic TLS model, produces an ADDIS8 instruction that adds the GOT base register to sym@got@tlsld@ha</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDI_TLSLD_L<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ad1e4cb7a1fc0c9ea50baef6974f21431"></a></td>
<td class="doxyEnumItemDescription">x3 = ADDI_TLSLD_L G8RReg, Symbol - For the local-dynamic TLS model, produces an ADDI8 instruction that adds G8RReg to sym@got@tlsld@l and stores the result in X3</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_TLSLD_ADDR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ac0753db07d6a64f1ee53f3d31dbac379"></a></td>
<td class="doxyEnumItemDescription">x3 = GET_TLSLD_ADDR x3, Symbol - For the local-dynamic TLS model, produces a call to __tls_get_addr(sym@tlsld)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDI_TLSLD_L_ADDR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a41664c9403b22dedab5a78fc8ef07b42"></a></td>
<td class="doxyEnumItemDescription">G8RC = ADDI_TLSLD_L_ADDR G8RReg, Symbol, Symbol - <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> that combines ADDI_TLSLD_L and GET_TLSLD_ADDR until expansion following register assignment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDIS_DTPREL_HA<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a5fdb4eb697cc8fb8a8aa8fa53effac34"></a></td>
<td class="doxyEnumItemDescription">G8RC = ADDIS_DTPREL_HA x3, Symbol - For the local-dynamic TLS model, produces an ADDIS8 instruction that adds X3 to sym@dtprel@ha</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDI_DTPREL_L<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a6f48c93bc2c3495090cdad2d375290dc"></a></td>
<td class="doxyEnumItemDescription">G8RC = ADDI_DTPREL_L G8RReg, Symbol - For the local-dynamic TLS model, produces an ADDI8 instruction that adds G8RReg to sym@got@dtprel@l</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PADDI_DTPREL<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ab0724ba8c987cd526c269d09bb5b2bf7"></a></td>
<td class="doxyEnumItemDescription">G8RC = PADDI_DTPREL x3, Symbol - For the pc-rel based local-dynamic TLS model, produces a PADDI8 instruction that adds X3 to sym@dtprel</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADD_SPLAT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a63d10572d28760b1a149732cc760628a"></a></td>
<td class="doxyEnumItemDescription">VRRC = VADD_SPLAT Elt, EltSize - Temporary node to be expanded during instruction selection to optimize a BUILD_VECTOR into operations on splats</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SC<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a2ae057e4de45c51c89b7e5dc5053df62"></a></td>
<td class="doxyEnumItemDescription">CHAIN = SC CHAIN, Imm128 - System call</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLRBHRB<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a39b31c544933df302c4b6b049a0185e0"></a></td>
<td class="doxyEnumItemDescription">CHAIN = CLRBHRB CHAIN - Clear branch history rolling buffer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MFBHRBE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aea2dbb65ca28f544afc80f4665a6f82c"></a></td>
<td class="doxyEnumItemDescription">GPRC, CHAIN = MFBHRBE CHAIN, Entry, Dummy - Move from branch history rolling buffer entry</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RFEBB<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a25c6863bf54d5a65a55506cce743e333"></a></td>
<td class="doxyEnumItemDescription">CHAIN = RFEBB CHAIN, State - Return from event-based branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XXSWAPD<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a4156aa36da735bf4f407406f04aa9a49"></a></td>
<td class="doxyEnumItemDescription">VSRC, CHAIN = XXSWAPD CHAIN, VSRC - Occurs only for little endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SWAP_NO_CHAIN<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aeec65142befe62f016e921ebf1ab2976"></a></td>
<td class="doxyEnumItemDescription">An <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> for swaps that are not associated with any loads/stores and thereby have no chain</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_EXTEND_HALF<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ac9eb1f199dbf096dc303ec84b69537f0"></a></td>
<td class="doxyEnumItemDescription"><a href="#ad1c32e5bb1cb213fb836bc3d221e4f19ac9eb1f199dbf096dc303ec84b69537f0">FP_EXTEND_HALF(VECTOR, IDX)</a> - Custom extend upper (IDX=0) half or lower (IDX=1) half of v4f32 to v2f64</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAT_PCREL_ADDR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a57dec08b9c245de78b203b5ce73a85a3"></a></td>
<td class="doxyEnumItemDescription">MAT_PCREL_ADDR = Materialize a PC Relative address</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLS_DYNAMIC_MAT_PCREL_ADDR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19af5d482f504e4591346e162e5cf33faaa"></a></td>
<td class="doxyEnumItemDescription">TLS_DYNAMIC_MAT_PCREL_ADDR = Materialize a PC Relative address for TLS global address when using dynamic access models</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLS_LOCAL_EXEC_MAT_ADDR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ab46d5355de307e34ab21c677c7c7c7db"></a></td>
<td class="doxyEnumItemDescription">TLS_LOCAL_EXEC_MAT_ADDR = Materialize an address for TLS global address when using local exec access models, and when prefixed instructions are available</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ACC_BUILD<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a9d22d6055af16a92989e3413db5c61e4"></a></td>
<td class="doxyEnumItemDescription">ACC_BUILD = Build an accumulator register from 4 VSX registers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PAIR_BUILD<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ac677b8b728cb9be271ba1e5c69c4a323"></a></td>
<td class="doxyEnumItemDescription">PAIR_BUILD = Build a vector pair register from 2 VSX registers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTRACT_VSX_REG<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a4d78018aab544301aaa95d949c194cb3"></a></td>
<td class="doxyEnumItemDescription">EXTRACT_VSX_REG = Extract one of the underlying vsx registers of an accumulator or pair register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XXMFACC<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a93f8e78c9b32393c5190960b84dc3a57"></a></td>
<td class="doxyEnumItemDescription">XXMFACC = This corresponds to the xxmfacc instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_STRICTFP_OPCODE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a173a769349d6fff3afc4ad6b38e24664"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCTIDZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ad00a593b7d71618f307d171781f5558d"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_STRICTFP_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCTIWZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a8a852db39a510adbbbadbbdede7aa648"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCTIDUZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a8a5acab2f34e1b806efaa3ee64c5a3aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCTIWUZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a553b2f3eaf318b2455673f16cb396baf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCFID<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a07c87149008709f85754a38b4f22adaf"></a></td>
<td class="doxyEnumItemDescription">Constrained integer-to-floating-point conversion instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCFIDU<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a72a662f3bbd13bf94bf0262ac1d4e868"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCFIDS<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a746850a5fa94a4ce3e8071b6219121f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCFIDUS<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ab58ea28e66ebad19b7718055fc998f08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FADDRTZ<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ac81afec4bdfa40303000449f212d7ac3"></a></td>
<td class="doxyEnumItemDescription">Constrained floating point add in round-to-zero mode</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_STRICTFP_OPCODE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aeaba78fa9a092ab99b5e2dd09d12d6d0"></a></td>
<td class="doxyEnumItemDescription"> (= STRICT_FADDRTZ)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETBC<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a8979933cc5b3ebf6a3f6a322dfe1330c"></a></td>
<td class="doxyEnumItemDescription">SETBC - The ISA 3.1 (P10) SETBC instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETBCR<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a9855b472ab773e21bafb60ffca9d4cec"></a></td>
<td class="doxyEnumItemDescription">SETBCR - The ISA 3.1 (P10) SETBCR instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_MEMORY_OPCODE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a48ab1a753603bbb6ce3eac231a498184"></a></td>
<td class="doxyEnumItemDescription">CHAIN = STBRX CHAIN, GPRC, Ptr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> - This is a byte-swapping store instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STBRX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19af2142b68a3cab0d2f680eecbb31c76e0"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_MEMORY_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LBRX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a8032251e5c6dfb52579250ef6373d599"></a></td>
<td class="doxyEnumItemDescription">GPRC, CHAIN = LBRX CHAIN, Ptr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> - This is a byte-swapping load instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STFIWX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aa71de12afd261e0b3f2e040ce1c10315"></a></td>
<td class="doxyEnumItemDescription">STFIWX - The STFIWX instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LFIWAX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19af19177e57893484cb79f34527b5cd7f8"></a></td>
<td class="doxyEnumItemDescription">GPRC, CHAIN = LFIWAX CHAIN, Ptr - This is a floating-point load which sign-extends from a 32-bit integer value into the destination 64-bit register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LFIWZX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a480a6977d64df14b9af6821de3f520b9"></a></td>
<td class="doxyEnumItemDescription">GPRC, CHAIN = LFIWZX CHAIN, Ptr - This is a floating-point load which zero-extends from a 32-bit integer value into the destination 64-bit register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LXSIZX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a21e2465b6dea8fe886e3261185e13c8d"></a></td>
<td class="doxyEnumItemDescription">GPRC, CHAIN = LXSIZX, CHAIN, Ptr, ByteWidth - This is a load of an integer smaller than 64 bits into a VSR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STXSIX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a5043cfa31ad158389477a46bd7c366b4"></a></td>
<td class="doxyEnumItemDescription">STXSIX - The STXSI[bh]X instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LXVD2X<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a9f74f2eb04440389d18aabcff035a19f"></a></td>
<td class="doxyEnumItemDescription">VSRC, CHAIN = LXVD2X_LE CHAIN, Ptr - Occurs only for little endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LXVRZX<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ae507654c72e23edbb1c74349cb5cfe33"></a></td>
<td class="doxyEnumItemDescription">LXVRZX - Load VSX Vector Rightmost and Zero Extend This node represents v1i128 BUILD_VECTOR of a zero extending load instruction from &lt;byte, halfword, word, or doubleword&gt; to i128</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOAD_VEC_BE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aeff91ba7f74fec449108bf0c7bcac818"></a></td>
<td class="doxyEnumItemDescription">VSRC, CHAIN = LOAD_VEC_BE CHAIN, Ptr - Occurs only for little endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD_VSX_LH<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a901207ea8da185757fdf6b2f36a1a395"></a></td>
<td class="doxyEnumItemDescription">VSRC, CHAIN = LD_VSX_LH CHAIN, Ptr - This is a floating-point load of a v2f32 value into the lower half of a VSR register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD_SPLAT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19aa95297a81ed350b1df6d0e322be12e23"></a></td>
<td class="doxyEnumItemDescription">VSRC, CHAIN = LD_SPLAT, CHAIN, Ptr - a splatting load memory instructions such as LXVDSX, LXVWSX</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZEXT_LD_SPLAT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ad423fc6dce425d3b017dea23db96a20b"></a></td>
<td class="doxyEnumItemDescription">VSRC, CHAIN = ZEXT_LD_SPLAT, CHAIN, Ptr - a splatting load memory that zero-extends</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEXT_LD_SPLAT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a01e7f48b2ccc0aed9c6f66314b23af32"></a></td>
<td class="doxyEnumItemDescription">VSRC, CHAIN = SEXT_LD_SPLAT, CHAIN, Ptr - a splatting load memory that sign-extends</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STXVD2X<a id="ad1c32e5bb1cb213fb836bc3d221e4f19ad7ff3b99ede678baebc8e3cd79b1090a"></a></td>
<td class="doxyEnumItemDescription">CHAIN = STXVD2X CHAIN, VSRC, Ptr - Occurs only for little endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STORE_VEC_BE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a1587d1d239eb39b23bdc1d173ccef453"></a></td>
<td class="doxyEnumItemDescription">CHAIN = STORE_VEC_BE CHAIN, VSRC, Ptr - Occurs only for little endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST_VSR_SCAL_INT<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a42f12c79832e19ec572ddd606b803756"></a></td>
<td class="doxyEnumItemDescription">Store scalar integers from VSR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_CMP_SWAP_8<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a427c8d80e0d4ec009de59a94847ce3c2"></a></td>
<td class="doxyEnumItemDescription">ATOMIC_CMP_SWAP - the exact same as the target-independent nodes except they ensure that the compare input is zero-extended for sub-word versions because the atomic loads zero-extend</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_CMP_SWAP_16<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a05c872ee0bd45120100d36acd763c832"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STORE_COND<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a3b16216732bca028b1c75cf3d662966a"></a></td>
<td class="doxyEnumItemDescription">CHAIN,Glue = STORE_COND CHAIN, GPR, Ptr The store conditional instruction ST[BHWD]ARX that produces a glue result to attach it to a conditional branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOC_ENTRY<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a5ac8e8dafc2dd10379a59ceff7b237d6"></a></td>
<td class="doxyEnumItemDescription">GPRC = TOC_ENTRY GA, TOC Loads the entry for GA from the TOC, where the TOC base is given by the last operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_MEMORY_OPCODE<a id="ad1c32e5bb1cb213fb836bc3d221e4f19a187ef05806bf70a33b6cefb03ecfc139"></a></td>
<td class="doxyEnumItemDescription"> (= TOC_ENTRY)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
