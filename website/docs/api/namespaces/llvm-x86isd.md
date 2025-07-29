---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/x86isd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `X86ISD` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::X86ISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#a9441a4f94d36d0f7c0c34aca42e3f76a">...</a> }</td>
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

### NodeType {#a9441a4f94d36d0f7c0c34aca42e3f76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86ISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa21644bb1fecd89fe8aef108bd866cb59"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSF<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae5919ad05b126b2a4c57f822c6521d77"></a></td>
<td class="doxyEnumItemDescription">Bit scan forward</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3eb8cf555013535c83a18858c5c4d5e3"></a></td>
<td class="doxyEnumItemDescription">Bit scan reverse</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSHL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aafc7ffcf1a4cad7c33343cede072fb0e5"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> funnel/double shift i16 instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSHR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa92ed95813cdeed918027c599d9f3a7fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FAND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaed927d0ca1203766de671e7437d658b2"></a></td>
<td class="doxyEnumItemDescription">Bitwise logical AND of floating point values</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FOR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaabe3cfcecab0e3b2e2ab496a566c8d1c"></a></td>
<td class="doxyEnumItemDescription">Bitwise logical OR of floating point values</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FXOR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa72b53026518573189b8a49ae5f5c2c2d"></a></td>
<td class="doxyEnumItemDescription">Bitwise logical XOR of floating point values</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FANDN<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa97670c93c4c4e70151c63e534993e04a"></a></td>
<td class="doxyEnumItemDescription">Bitwise logical ANDNOT of floating point values</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8e74b6dccfb024d3f1f6dc71554e5513"></a></td>
<td class="doxyEnumItemDescription">These operations represent an abstract <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> call instruction, which includes a bunch of information</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NT_CALL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacfb44d4457297705eda018ce456f2a08"></a></td>
<td class="doxyEnumItemDescription">Same as call except it adds the NoTrack prefix</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_RVMARKER<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0e7673d6e0ca7db6dfaebb83d789bad4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa23260aedef0a54d543d227e57955c652"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> compare and logical compare instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6ef50922ad9f8f5c658d0b2206f612f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COMI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6ecbcb7b3e43614532f37958e9f2d478"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UCOMI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa59887cd94d252432c1d81f048a6615b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COMX<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5f297a5e0783ef4fae52ff79e78db0ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UCOMX<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3c956bed0faf947f360a2e54073e9108"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa081ba89905b8c040bee9e6944233a6e1"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> bit-test instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa45f2ab1ba8d655b3fde883df17385b54"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> SetCC</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SELECTS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa662b452dbcf89005c6cfa88be806ee9b"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> Select</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC_CARRY<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadd6a532536216924183465a65e0585b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSETCC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7b0a95242bc129e654632fbc83ecc472"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> FP SETCC, implemented with CMP{cc}SS/CMP{cc}SD</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSETCCM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa665753f9d5107a9344271ae055935ddb"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> FP SETCC, similar to above, but with output as an i1 mask and and a version with SAE</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSETCCM_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae9def2a528ac0c4dcfe0d53e973ee73b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMOV<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf413bba9e77d68afdc1afba084851728"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> conditional moves</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRCOND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa788e2bf6afec57a73a4118be1cc7af3e"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> conditional branches</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NT_BRIND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5913fb8adc3c04ec97f2069e6df3ffa1"></a></td>
<td class="doxyEnumItemDescription">BRIND node with NoTrack prefix</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2bd3e24213c1785fdc448d206207d9f0"></a></td>
<td class="doxyEnumItemDescription">Return with a glue operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRET<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3fe478f754d5761df437300f6a8bbf2a"></a></td>
<td class="doxyEnumItemDescription">Return from interrupt. Operand 0 is the number of bytes to pop</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REP_STOS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7fc250aeeb22d10e6a7752671df796ab"></a></td>
<td class="doxyEnumItemDescription">Repeat fill, corresponds to X86::REP_STOSx</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REP_MOVS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa04dbe44e07f24ce17ff84e1dcf424c11"></a></td>
<td class="doxyEnumItemDescription">Repeat move, corresponds to X86::REP_MOVSx</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GlobalBaseReg<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9f2e4e1e83010173fe9361ecfa60faef"></a></td>
<td class="doxyEnumItemDescription">On Darwin, this node represents the result of the popl at function entry, used for PIC code</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Wrapper<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac52ade4e38c09090c08d423e886cb4b2"></a></td>
<td class="doxyEnumItemDescription">A wrapper node for TargetConstantPool, TargetJumpTable, TargetExternalSymbol, TargetGlobalAddress, TargetGlobalTLSAddress, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> and TargetBlockAddress</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WrapperRIP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf9b840077b4580ddbfd3bf992fe359eb"></a></td>
<td class="doxyEnumItemDescription">Special wrapper used under X86-64 PIC mode for RIP relative displacements</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVQ2DQ<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa126e28f14818b0b293da6aef89e11cbe"></a></td>
<td class="doxyEnumItemDescription">Copies a 64-bit value from an MMX vector to the low word of an XMM vector, with the high word zero filled</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVDQ2Q<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadd5701bb43afc4c3b3c13bf989a03cd1"></a></td>
<td class="doxyEnumItemDescription">Copies a 64-bit value from the low word of an XMM vector to an MMX vector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MMX_MOVD2W<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad3385085c4af3524215765245e0422d7"></a></td>
<td class="doxyEnumItemDescription">Copies a 32-bit value from the low word of a MMX vector to a GPR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MMX_MOVW2D<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac35c5dfd3dcced61622fbacc9fa1ab93"></a></td>
<td class="doxyEnumItemDescription">Copies a GPR into the low 32-bit word of a MMX vector and zero out the high word</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PEXTRB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa71fe63f40efcc073f1a5dd6df6efc550"></a></td>
<td class="doxyEnumItemDescription">Extract an 8-bit value from a vector and zero extend it to i32, corresponds to X86::PEXTRB</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PEXTRW<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8c57aafe37f470b4b146ea8307983228"></a></td>
<td class="doxyEnumItemDescription">Extract a 16-bit value from a vector and zero extend it to i32, corresponds to X86::PEXTRW</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INSERTPS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa87f757077dbefa56b1172c1d7c05da53"></a></td>
<td class="doxyEnumItemDescription">Insert any element of a 4 x float vector into any element of a destination 4 x floatvector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PINSRB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7d9a2bb887ffdd3c85b7eb7215b891db"></a></td>
<td class="doxyEnumItemDescription">Insert the lower 8-bits of a 32-bit value to a vector, corresponds to X86::PINSRB</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PINSRW<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac851454bb8c0c576e53b3d993d9c2acf"></a></td>
<td class="doxyEnumItemDescription">Insert the lower 16-bits of a 32-bit value to a vector, corresponds to X86::PINSRW</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PSHUFB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8a421b1832302b5097a94b81ed579170"></a></td>
<td class="doxyEnumItemDescription">Shuffle 16 8-bit values within a vector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PSADBW<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaaa69270d771a472e5b86c11370dc0330"></a></td>
<td class="doxyEnumItemDescription">Compute Sum of Absolute Differences</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DBPSADBW<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac0b1faf88e3c4a4ebfc407bd17f645c8"></a></td>
<td class="doxyEnumItemDescription">Compute Double Block Packed Sum-Absolute-Differences</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANDNP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852"></a></td>
<td class="doxyEnumItemDescription">Bitwise Logical AND NOT of Packed FP values</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BLENDI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa134343dc9302925cf314b9b891880380"></a></td>
<td class="doxyEnumItemDescription">Blend where the selector is an immediate</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BLENDV<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa249e11d47119ca5c2666008857b3b534"></a></td>
<td class="doxyEnumItemDescription">Dynamic (non-constant condition) vector blend where only the sign bits of the condition elements are used</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDSUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa278b7d83da7d0e71506a7544c6b23c4d"></a></td>
<td class="doxyEnumItemDescription">Combined add and sub on an FP vector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FADD_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad039095a3b18fb119e3929dcf949ae6c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FADDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1fb173ccbbe141aa5c819ba36cf87849"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FADDS_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa067363685eda80921daed7993066bbc7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSUB_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf9d613b4288ba64169c6f2ff90babdd4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSUBS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa4a172e5849a0b1f80e5e6d3cf949f3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSUBS_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaffef8d647f109c19bfd14555e0e87877"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMUL_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa081ad31e11c96722823903ac255ae32b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMULS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacc8282228b74b56cc6a53361a5271489"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMULS_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa79ed16d103bea9f4676a49664dc90a26"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FDIV_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa28d3778b305e9cd8452a3b036ba0578e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FDIVS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa16ba91b20629c6e48a27c7965368fc57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FDIVS_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6f9186dba0b89b0c8bf2c2f531fc2f41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAX_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad2bdc2914d21b659d4f2bf2ac6cfd1fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3dc546cd25a305869670d4174f0fb10a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMIN_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa95c31a8450db82864c351f9c36df54f3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa180049595cef360c0596f95548bc03d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSQRT_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa41f21265309401dee0d414fb2e2ee255"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSQRTS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5ed8031749f99840b23a9eebd7f2d903"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSQRTS_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa216afc93c7bde60ee5793bdf213aa546"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FGETEXP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2e2bdd7a118eba1b817d42388b6896e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FGETEXP_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa562ba3f47b99cd3bb249504ea3d02d51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FGETEXPS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7dde8ec5661ebe9358d997cb23fb8fb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FGETEXPS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa74e3b6bdc0045d389b98b5b31692721"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VGETMANT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5072511395458f5fe7d4cc27572abc1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VGETMANT_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aade887b13dfe529aefd13567e249de176"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VGETMANTS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa297e24c8feac1bac6ed692acf3e4f485"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VGETMANTS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6fd46692289cc6584c6fb6d3ca692082"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALEF<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6beb8e11551cc9f18bbb68c31f840f45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALEF_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae9517faa6d410438f4fe1933e903c82d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALEFS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2ce7ee11eeeaa6641bd7d78c1505e907"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALEFS_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aada1ec746d8e7647f1c2cc9a53aa3734f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0f4ce46b34ac79f389d475fa6745463e"></a></td>
<td class="doxyEnumItemDescription">Integer horizontal add/sub</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HSUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf02f5b8c1cc25ab0a8e6cd8e5364332f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FHADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3a702f9706acfd0711a2ef618e764eb9"></a></td>
<td class="doxyEnumItemDescription">Floating point horizontal add/sub</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FHSUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaab2f2aa57f37dc2b9c616ce720e6b8ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONFLICT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7952a7e629684de1c61fe7245bfaaa6e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAX<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa080313447e98432d4b62801bf2ad761f"></a></td>
<td class="doxyEnumItemDescription">Floating point max and min</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMIN<a id="a9441a4f94d36d0f7c0c34aca42e3f76aabad10e5691f05a78824d6bad0300e529"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa24b80a5be93b9ddfa62446ced71b68e"></a></td>
<td class="doxyEnumItemDescription">Commutative FMIN and FMAX</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aafb454d19747fe081325da96a69373f82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3a7ade0eaf12aa0843f485208618255b"></a></td>
<td class="doxyEnumItemDescription">Scalar intrinsic floating point max and min</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae5f201c0525e49f4d2c7a057ec30bfe6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRSQRT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaff7f55bae98701a821d0529a64932088"></a></td>
<td class="doxyEnumItemDescription">Floating point reciprocal-sqrt and reciprocal approximation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRCP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacd28a0d5248d37cbf2d4449434a70a98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RSQRT14<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa21b59cc5ca5ded1817c314f5b97d3aeb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RSQRT14S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf9facf214845bf370af9f19b94044b58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RCP14<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa922028714f0d0d6899869165be3b00b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RCP14S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2610620b0e8119a44f46ca42f3cd1b94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSADDR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf7f49707613da7903f31628aa4937a6f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSBASEADDR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6c656a3bd0b9b4c50b7df6d8a5d74c95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSCALL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab3bdd022c4bbd31d548975d4ddee3209"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSDESC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa52477985fec64d0dfdd5f65d364df8ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_RETURN<a id="a9441a4f94d36d0f7c0c34aca42e3f76aace8521ad98fb024aee02f065b73590bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_SETJMP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1e9c72799b70329f6a0935d8747c59d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_LONGJMP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9dc7fa6ef54f761457981b9852d361f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_SETUP_DISPATCH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacad0dbbf36bfadb4214f411ba415d854"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TC_RETURN<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaaa37a4cc02090ea86d2448dc9d967d75"></a></td>
<td class="doxyEnumItemDescription">Tail call return</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VZEXT_MOVL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1356801ab44d90ec9c7643ac8ff0770c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTRUNC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aabb0879a5b12d023b74697191612bddaa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTRUNCUS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3b2fdb13adfdfd71f723a38073cb43f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTRUNCS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa192681cddd79867e5a6924bbcf453965"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMTRUNC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac22543849609d3caeb0512a0e5c5262a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMTRUNCUS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa02585b0d1a0db91ca9ccd66eb04746a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMTRUNCS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa77dfd27220e9b2f57ddf703bc778a582"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPEXT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa31b0c916aeabfacd2542a2a447470ced"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPEXT_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2dbffd930f9f8858e33d32e511c8b651"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPEXTS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa44a11b6f6f7a9acbf638b7b1a3263c3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPEXTS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6db142daa44ca48a2b60e62c0e16d3ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPROUND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa931754702331756731a26916aebb794c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPROUND2<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad4112769c56366408892df7d864f6392"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPROUND2_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7133302ea2001b1d581c74c94ae5cdf0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPROUND_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0adb8ee8a556d467a329a64c10233b6a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPROUNDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad56756310253b2495db1bae128a851b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPROUNDS_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad5528253199b00f693c4786aa1a7a40c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMFPROUND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4d1e3a8e02ddc590b8c60205884b32d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHLDQ<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7e968cfe56e1cef0e04fc1537d5a5219"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRLDQ<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa671bbc2a9353cf20bbfb8af47aa237ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4c0d35627a076e5424b6de3804613ec6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0f740b2d7ea674677c7e8073453f8814"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRA<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa751ccb36d27604bba1151ef84cd98510"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHLV<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8a2fc33ce2fe41ef2d20854eda49a4f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRLV<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1e837f978c72eafaf138c1b0a7b6cddf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRAV<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7b2c246cb3a5d3513041dab6a32b2901"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHLI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf5db7ecddd15a88ac103ef566d0b2180"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRLI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa88145107ca3ab31b2e96b5e99bf5b517"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRAI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa53a1bf88056b37006ab9ba3b83f1f6ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KSHIFTL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa00eeeadc9b5bc4170585af2c864b0080"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KSHIFTR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa990193ae17623553503589ce732d6d9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VROTLI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aafdc80e4b94d055e1a1e9ec2c445fba9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VROTRI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7523f4161dc4fb59fdb57c1660970b17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0f4605a7e5bb3cda3e1e3f6b05c08c46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCMPEQ<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8e6b692f93aee762231d7221e5730598"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCMPGT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf1366c70ee0fa95a076fe683d900e9f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PHMINPOS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa38ba196e1b29c1704ec66c3b4859b670"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULTISHIFT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa301b53c316c4e29eae3ce69e0b8a67bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa05d9c829463eaf8b091ad6a9c87c88d6"></a></td>
<td class="doxyEnumItemDescription">Vector comparison generating mask bits for fp and integer signed and unsigned data types</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPMM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aabce03abccd69ac47244d25f564ff70cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPMM_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa09b3f463b81f42e923f8df942244822f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacf42ecbf82f3dcbf52c109ee0e3f5838"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4affb47abdfdd54079d5a2f8c1d3e628"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa72deaddfd41882e7ddf09409d9528bc8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5d99076d052295315dc1e2dd067d2ad7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMUL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7ae4b4652e07c1ad3ff57c36e3f04f89"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMUL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac459a26428cf593d442a86904673b560"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf362e78ded62dc71fd125ff7f8099475"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa483bad339c6126c64687d14c10979979"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8957fd90a0c765af6746fb0849ee1a8a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BEXTR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7ead8df5cf10d5f87e8c19b6f7d34ad6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BEXTRI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0e30dfae5bfdf5db17847036581a181f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BZHI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf20c535f7b902c26c1b25bd507b473e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PDEP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa492e5211769c80814cb779b4ba995f23"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PEXT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5e4a0e6bc60434430bf6a9da9071e894"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUL_IMM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab42a00cd9b29370e08759eeed0673c0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVMSK<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5b943cbe99c34600de83e0c7c0046e18"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PTEST<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadae3cae50736994b3df8afc2e3cb0e63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TESTP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa71996007c100b1c370ffc2444bc680a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KORTEST<a id="a9441a4f94d36d0f7c0c34aca42e3f76aabb8899e3583836cf58a89eeefc1efda0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KTEST<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa24c4d2d0c589d3b38776e776335f51df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa34a17ff22deb585364ba42c95a8849ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACKSS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0e447f5393ad6797e4af00c9401ca6d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACKUS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae3abaac16c2c7818508b6e93d170c6b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PALIGNR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadbc8832d51cd514c75c2be6b65f0ac82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALIGN<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadc975c428af9c770fddc2a81ddbce015"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PSHUFD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa182b063ab7dd0842ce968cef5f981e92"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PSHUFHW<a id="a9441a4f94d36d0f7c0c34aca42e3f76aafce56cb4ce3db03407437c4ae07d4103"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PSHUFLW<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6c444c7b1be0ea32c7e2c92fbc40388a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHUFP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa24d6477bb4120ec6b6517ca5e272da9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHLD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa82bb8ac1e1f2a963db85670fbaee715b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHRD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3de35096170c042afd35bee9db4e8b7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHLDV<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa25ea339c7f2bfdf4cd8eb5ab7c217abb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHRDV<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa199fa92ce65208d6f17d763eb7e3f54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHUF128<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa79877458fe9ec4fc94c68f40e2b54fe0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVDDUP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6ce5ecc4640f78a2ecbe9acb4e3908de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVSHDUP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaccebcd9a853dde6b119f0ce7ba968c50"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVSLDUP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aabedb442ee692bfea01853044734e5ae1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVLHPS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1c741c364406fb0b9958fdbba2c7be66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVHLPS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa607fe97a2d1c7d13eec1b620df6ab05a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVSD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac1ce5c2b00e728bf0dd6b84f67f418ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVSS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf6eab04fa10f5f7e89800dacfbe2dd2c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVSH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa341f5831cc328c89d5082a91b9c6b1e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNPCKL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa000697f31e57d54cd3ae43a2568c36ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNPCKH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa03a9611e6b354e10a8c3809f49b61eac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPERMILPV<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac98989ae74d479c77e8ac37cf95f3f22"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPERMILPI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadbf48e1eda461f1db91b138d32c7e8d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPERMI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8bc7868b5b5c49adff7e1b701e2f6daf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPERM2X128<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad57ffc99b9cbbf690e9ac199fc06573d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPERMV<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab250ea084b009cb311b1617f5f527c35"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPERMV3<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab63fa0a5c1888e275635edaaf3ffa3ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPTERNLOG<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2a83b0801da091b55c27832f5ad62959"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFIXUPIMM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa516f7bb97176eac5c7a3f38e3597ee9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFIXUPIMM_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4cf2967fcccf1cbd62151463b26d8e51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFIXUPIMMS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab240bafad0a1cf9d7838d667c95fac6f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFIXUPIMMS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6b0b67403e508af6f31b4ee5fce9aae4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRANGE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacf101718a8e7287ad3696b436dc943fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRANGE_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4afdc36a30470fb3f832738efac285e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRANGES<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa63db9eb5097f5cfd28f0ac7e2157d481"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRANGES_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf3d48c079fad95deebcd93f52004de0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREDUCE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aabffa032eefb42c52ff22ba390b07c8d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREDUCE_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa644490f76951b1e6c9ce41db673fbbeb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREDUCES<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaebb47def1a8ecfc0aecb45275d23dd4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREDUCES_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6337c2357d0b910456eca0807645e534"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRNDSCALE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaaa13b769dd360fbb653f40a94a006bc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRNDSCALE_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf19e3446029942e26d64a6b1d60725f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRNDSCALES<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab246d9e41099c9d3a8e449d3cf3f9e59"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRNDSCALES_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa32432bf8053f0712c3b8ef4ebc36e6ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPCLASS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4d77910a4bbb88e5fbdcdd8dd8a44592"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPCLASSS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6c22ee97f4017a0ba64f984609726513"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VBROADCAST<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac3bc043916fd84786c2ac451e0a3cd24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VBROADCASTM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa869088ddb6de16553217214a72041351"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTRQI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa39d334524059c9dfadbdc28394139b2"></a></td>
<td class="doxyEnumItemDescription">SSE4A Extraction and Insertion</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INSERTQI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aace7867675de7ee0798a8fec222fe3a7b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPSHA<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaece0f87e173b1f5b36990e9ac4aa5ae5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPSHL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaab0d78bdd53f75f09beb712341df5660"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPCOM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadcca882e85abfd81e17c1dba55d05e1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPCOMU<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3be4201d9ac120bd22b241cb6062f558"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPPERM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa223d75974bc37f644ce46f5a8684ab9e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPERMIL2<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa359935c9a800c36fd9429fa8691c98f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMULUDQ<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7f0c379fa7f4b37235504936c56ae486"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMULDQ<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac42bb75fe0307f14264032e6db521de2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHRS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4e5191d0825333d06789828dbf59f4e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPMADDUBSW<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab02310456415907ec1be4ceae53d48a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPMADDWD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa90d5ada6e2cf83b82e077c35702f2fc3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPMADD52L<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad670fb5b06e9318973006f77bd5d483e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPMADD52H<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0a886b39a599413aab2fe1e4c03278f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPBUSD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6b5d567a96d6f2fb18520983409598c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPBUSDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae331d34ee769883576fdda6f841eb646"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPWSSD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa946b1be843e180fc4e11e56960986cd5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPWSSDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8cadaea018465e8e4de867b43111e34a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNMADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa367039352ad0788f23a2ce9bcd493f2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMSUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9d8ad87414cdc8a0416b4c94957c1775"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNMSUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5366e83be28759f315637517f6d3f369"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMADDSUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa58f003a627b6506ad2893c67204325e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMSUBADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aabeccad22b28fc7542e683776e90454d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMADD_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae5c55557d6753435f3b5b6d9678dfacc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNMADD_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa60f697da41de26a8822eeea8b508404c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMSUB_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa865d34b939542df305710438eb9a8d2f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNMSUB_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6adc5233cdab66da1ea6f13370a00570"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMADDSUB_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2877f0d6e51388d3a93a7b407289ae70"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMSUBADD_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa255d13dedbd0510f453bd5927ed80c31"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMADDC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa68a04a27d499f804cd5d667ced552e43"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMADDC_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadd8bbe7b440f3040ac125b08a688a668"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMADDC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa507577f8af9912aa2336e0f05196d536"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMADDC_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0588e11908989553cfd28a2077cb3df3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMULC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5f29e5c0f677a84a777ab70e00bcb637"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMULC_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9cf8bcd4a1f6c1d6b710ac38098a8cf1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMULC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa0b3bd02ac22b665f1abc59f4966d465"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMULC_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa47b02bca89898c97abdebf2f35c564aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMADDCSH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa24c3eb4e85b19ea59ab331bbf8436eab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMADDCSH_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa84f6160970111fabf12254b001730002"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMADDCSH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4b90d4862d20b8215cb5fc10c9a59579"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMADDCSH_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa207b1c29bc248c99b8520e1b81498c68"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMULCSH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac55abce289a45c173d09c4715cb8e524"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMULCSH_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9a042006693dd82dc4171f8bc47b0652"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMULCSH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab07cbd44f29994e55842e61cf8d6d376"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMULCSH_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa20924153d8178ee60aa7c91e6f030ab8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPBSUD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9e6a01310ea9f8d99513efc450a5d6d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPBSUDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5c2d5b0e33a1b0c141520f67f59ca957"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPBUUD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa078890f5f92b98d46137ca3258e7b1cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPBUUDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf9c43005ad46f3b790001d6643758210"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPBSSD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa67f80b3c93f172aa617efbec9d9a8fdc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPBSSDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa173fe6a5c99e98e0ee8be4f6fc2fd297"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPWSUD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aafd447ff7c4f9e0ba48ae4a26915ce7fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPWSUDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf90213f07a1d68a69c3acf60cd8977bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPWUSD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae5b9e8a636fdbfb156e458fbf68d59dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPWUSDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf5318cda25fa519a3e216886084d2cf1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPWUUD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9b604ecf63dba334a19d482b67c3541b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPDPWUUDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7f1dfde126fd8796d887e9282c9b59c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMINMAX<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8a46b34ae14e7f018ca3a7f52dbc3441"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMINMAX_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa437adea36c081a086ccc2c31702c9592"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMINMAXS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacd7291bb51d817eb1bff2bd36192b2c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMINMAXS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa25d85f0d2045bef9fdbdf76b4fc099a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTP2IBS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2e5dc826247429b94f8d2a6cca73f034"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTP2IUBS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacc7ba465c6511ce84d7ef1d5377b7353"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTP2IBS_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa136db57ba5d363b012b47f7f3418f72e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTP2IUBS_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaaf4508357fc0f57c5d864976bde03fd3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2IBS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5a186072e91ce4cae03ca43fcad37aa0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2IUBS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf21450fa03b9dc78ccbe07a69b34c44d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2IBS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf6d2b8a4255c10af87761cc5fe94f37a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2IUBS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadf438d6dd7b20fe5ec87f3ad45f929a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MPSADBW<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0004f0cfb0895225b723eb113ad9eb85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVT2PH2BF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa478cb7912f9e542f1759e5b11d9f2a78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVT2PH2BF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacf90cb110b438b48ee855a752a3178a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVT2PH2HF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa08970a08b6389ed2a73a689b079cd63b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVT2PH2HF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaea17d788e5cf6cc4df7239d8e9d5f1ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTBIASPH2BF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa603fcbaa07ba4fecebc6540ee3e4fe4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTBIASPH2BF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa02937f73aab4431c06f435badaac38de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTBIASPH2HF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa104ca3bd322f9431f253ab1e57dbfd83"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTBIASPH2HF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4185683a06e849040e67f43e885f6da3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTPH2BF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac29937c09acc98c409c1cee01b9bb5a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTPH2BF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5408fe61ff8689c88585c81a41e3c86c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTPH2HF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa686fef8453e5cf5155ff15ed2975c12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTPH2HF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab9da993e0f23e1b1bf584c875c2ef8df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMCVTBIASPH2BF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad21f1dfbe136bba8f74062332585d620"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMCVTBIASPH2BF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1f163b4e0bacb6713f41e090eab62229"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMCVTBIASPH2HF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaffff33c58c4c30be142eac20366d33bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMCVTBIASPH2HF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa31475b7935891e98bd0b6f485bfacdc5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMCVTPH2BF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2a1a3f153cae74c774fae10419fb5a6e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMCVTPH2BF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadd6981ad0b29de0f73aa7fce6bb701eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMCVTPH2HF8<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1f25695cce8faff9ea2d26bb4ad9646a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMCVTPH2HF8S<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5a1df3428132e6e956dcf0ff1fb3cd10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTHF82PH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa70c1224e527be2a699078aee6b971219"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COMPRESS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae15cf1828833984eef9d968c615e6138"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXPAND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac60182f40cd78eacf11f5fdd693d5e7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPSHUFBITQMB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaae0ff7afe174b3d7204996bc4c43552e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SINT_TO_FP_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa547e3a838c6b30d76d00fc496c29ee3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UINT_TO_FP_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa319b27184731b63dc4b39ff6accc9691"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALAR_SINT_TO_FP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa407337747b5113a53385b50c0a597a48"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALAR_UINT_TO_FP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa340f7e03b1e3c8ee7be2477ca74ebfe3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALAR_SINT_TO_FP_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9d8392877cff1235b95d6cb7cb1455d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALAR_UINT_TO_FP_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6d8aeee598a8004dcefbfaa51933c1e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTP2SI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3d9c4511648f4aeb6cdc39851c6b4759"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTP2UI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5af26ba107d346037ecbd751de03de5d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTP2SI_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa18d00f87be06fee47378f202c35468c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTP2UI_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa698f316756f4e7c1baf0a06a4599a083"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTS2SI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa545539a5bbdd377269a6d299a4be73fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTS2UI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaced1fc5ce4b98f7ef9204075ce905021"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTS2SI_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0ac7d42bb27453d6dc820fac679ba014"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTS2UI_RND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6b22addc6d55b1bf7ff3470c44fd1711"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2SI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa873eda45cff31b9f5fe7af33ed2ec407"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2UI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac6c8013c7f060d7023eb23cb32fc14c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2SI_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa51c6f5c47733cecb1988af29d95be353"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2UI_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa94956dcc08eac4c0e590704a1221d45d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2SIS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa72680a4bbc04e3f8f1c79c753947bdad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2UIS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7310a80781fd78e4d6c5613612da555b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2SIS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa81b90ad1e39cd0d4dbc4747e608ff0f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTP2UIS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad9089b4010048e0c497cffcaed73dd55"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTTP2SIS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4608ef6812af0d3a623cf57df47178a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTTP2UIS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa14cef8c252c1acfa276c0da5f1740743"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTS2SI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaefa3cb39beba178ca2b864fadb5bb83e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTS2UI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaca3af1442dc41a3731d484050a697a22"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTS2SI_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae85f531aa16b24a15dc5e8a4cc16d69e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTS2UI_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6526af58299b0a822638d6c86ac68716"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTSI2P<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf64444ca786d0cddde2bc8628f324e3e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTUI2P<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7821643340a91702a2540ac9a3e6ab53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTS2SIS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa279e4ef4c996545a1e4b7d63daf99481"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTS2UIS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae69e5934149e848875fa1a0a4c84fcfe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTS2SIS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6d2c761e19f450e193a3d77088a218d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTTS2UIS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa14a8aa5bd38e5b61661bff1254785969"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTP2SI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9fc9cf61fd9db57b6e139ba9faa632ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTP2UI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa73d8b03b224b357896577a0b4df66be4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTTP2SI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4e58653f8830ab73ca1b46538568aafc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTTP2UI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5cffc707d7313cf293e1101acd35a609"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTSI2P<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae2925d7ff6b5400012986018a81ecaa2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTUI2P<a id="a9441a4f94d36d0f7c0c34aca42e3f76aafe9aa5f2f459e64cb14518d17481ad3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTNEPS2BF16<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8106cde91dc7605229698a79d0b0437a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTNEPS2BF16<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf77396da05a782a1761d0da51bcfde0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPBF16PS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab7a2dc90351bdda2d00ca3cc02f3fb76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPFP16PS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa394052ffe3e0d6f01f64714597c56478"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DYN_ALLOCA<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa694c09be9924a5ebc16d55f9c8d4bfa9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_ALLOCA<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5403a695e5b22104bb387fd57a8d63ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PROBED_ALLOCA<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9000b99495c93d338d9a273e1b295629"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MFENCE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8907928c0b30b37c444d6a932a239c8f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RDRAND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad6c69380bc79b951347c7ee83004605e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RDSEED<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae1b4dab672befc47006283fa37d529fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RDPKRU<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9147f32d52c21215196994ef54041183"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WRPKRU<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac7fcc7e016484307f4a0f1a578d0835a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCMPISTR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa31e2fe326f1bbdf7ad6711d5f05a12e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCMPESTR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9ad9e95fc1723ed3c9e58743d106e28d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XTEST<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa66c4a04f53c729b0b2d750bb41a9141e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTPS2PH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1fec5162852502da5a2832321f9c1012"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTPS2PH_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae9b4c6ab2c63cb94042b8fc8b6e85992"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTPH2PS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa94c00be07b5a7475ca1ae4b1e1676fff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVTPH2PS_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3dc220961118a7c2f036a42985f288c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTPS2PH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1bdf811a50ebc4ef297a426ff53509c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCVTPS2PH_SAE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa15072c0b21bdf25d9d5bfbde511ee443"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GF2P8AFFINEINVQB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6236fd616da35e18597c6610b1931c12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GF2P8AFFINEQB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa09a2f82b73ba8c6396e7a03211b72a2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GF2P8MULB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa07fdebcf8f923d22b160d09ae5959a43"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LWPINS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4bf29741f01b0d622546776b4f80beae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMWAIT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8d26c89d55b54b179e9fe918f4046fe9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TPAUSE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9c058e34b3f26561a4943a108a47f02f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENQCMD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa3ca6e1f278f4463bf12a0ed620eedbff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENQCMDS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0b751e2781acc00275a1a4599e571c5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VP2INTERSECT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9b885ded18161ab3fbcc821ddf87877c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TESTUI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad86aa3ff6cdfd3b7be47bdc260a7394e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP80_ADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadea760a47453a56bf9cbcf4a1055f861"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CCMP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad78a253f3de9dfc5f4e85503dc5e21e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTEST<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa132a0fae25bb3cc37363f9ec73b61a11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_STRICTFP_OPCODE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aafb1d40d2d5be36b2802e39c46f42bcec"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> strict FP compare instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCMP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2fd2f346e29cc62fa712e56beba83b38"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_STRICTFP_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCMPS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae070a3a7c9ae6080d68cddd5746d65c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_CMPP<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0c37c93f4be0b73fca737169759f1b47"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_CMPM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa34f5dcfb89d057728020ae6a1751c3ee"></a></td>
<td class="doxyEnumItemDescription">Vector comparison generating mask bits for fp and integer signed and unsigned data types</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_CVTTP2SI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa64a6fc099c65248a3deba44a57f1d99f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_CVTTP2UI<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa40f22ea742439c6dddbfe08b02d48331"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFPEXT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa99c9fe64240a4efa15100581791f7f36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFPROUND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab12f350653f681354125c5f9a97c6bab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VRNDSCALE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa53be739a3b69a5d27e1a521ebcad8029"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_CVTSI2P<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa73a98d37d002eedda0f99b15e04462a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_CVTUI2P<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6b06c0682b59b924440540643e5c3262"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FNMADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8d273a921f347c6711b85b0da9bbae43"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMSUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa74732dc3358e5cf49d56f725cc9b1946"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FNMSUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf58da512c0b7a4f83134b838525d4340"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_CVTPS2PH<a id="a9441a4f94d36d0f7c0c34aca42e3f76aafa37e128cf1dbc7b4b4825400f999e83"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_CVTPH2PS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa711d4a7af7fc515982a14698747aa12f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP80_ADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf23db64fbd4fbbd52b562bbb31924c8e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMAX<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2f49fc0a41551736df3850240384a0ab"></a></td>
<td class="doxyEnumItemDescription">Floating point max and min</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMIN<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7cdfcd3101cf1f5168d138368cf6f636"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_STRICTFP_OPCODE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aade2bbda69cf12cb28e43fa4e4d056241"></a></td>
<td class="doxyEnumItemDescription"> (= STRICT_FMIN)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_MEMORY_OPCODE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa88eab0f3f37b1ae95ccc40f69075f975"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LCMPXCHG_DAG<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa6f9a4c263c8adc3a587ba2ec396b2e56"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_MEMORY_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LCMPXCHG8_DAG<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa4d2a298fcfba10ab50983efa354ebcb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LCMPXCHG16_DAG<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaeb1887e4cd15e006f28a5f75a691a620"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LCMPXCHG16_SAVE_RBX_DAG<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab4e25ab99584790282db2a9592159ce5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab8c48043da28b0059034ddfe36e1e2c1"></a></td>
<td class="doxyEnumItemDescription">LOCK-prefixed arithmetic read-modify-write instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSUB<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacb817f4013cbb43f97d5a23c3868c390"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa12eff13d69c745a9d52ef4a184585f27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LXOR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa735b26fdeac5e6ddba04dfcb39c18980"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa35eb2233e71afe64505425d29d360e03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LBTS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaab2b92203536550d0cd9b1bfdda5b8de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LBTC<a id="a9441a4f94d36d0f7c0c34aca42e3f76aad86ab6a5c6817ef12f4d98b3efd9d748"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LBTR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaccc3a8ee74010b9d94abd5970985d377"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LBTS_RM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aafba77fe59c23c7445e2529d8462d3adc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LBTC_RM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa2bf5e9177616f57af5fed8b59ee48bcf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LBTR_RM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9a90980a18e57ac4c628653200184046"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9158e93d3c4e93b340095aac79715583"></a></td>
<td class="doxyEnumItemDescription">RAO arithmetic instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AOR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9439e0bd5b70780559323950b62213c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AXOR<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa1d5477039b32f39431063a37317cd88e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AAND<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa29c8cde3a962314115f5b9408dcc6fc5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VZEXT_LOAD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa41663b0542b9ae893f5c9122a7b1ce4c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEXTRACT_STORE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaeb84460d683f07195940fd88ff366cf2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VBROADCAST_LOAD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa78f74c46439b34ecc3b826e4bb5f1fc2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBV_BROADCAST_LOAD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa17d58dbb94911cf1630e9c523cfe1911"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNSTCW16m<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa250bc85789f2fe4cbb3262f24b9eac0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLDCW16m<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac5eb385c9c674672b8de9664ee92c1c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNSTENVm<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa7cd00281c7d3688a68b196c7c90892e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLDENVm<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa5be7146cbdbc04e2ae021bbf7605b86f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_SINT_SAT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa254fe3775f6769e9b0a07402db7e153"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_UINT_SAT<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa037ef8dd52f75e9f1f9a9706ba4d8f42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_INT_IN_MEM<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab820cab376b5f1282419c6cfc7e812b4"></a></td>
<td class="doxyEnumItemDescription">This instruction implements FP_TO_SINT with the integer destination in memory and a FP reg source</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FILD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aadc5e8eb45f3fff639c5f0edefe64f641"></a></td>
<td class="doxyEnumItemDescription">This instruction implements SINT_TO_FP with the integer source in memory and FP reg result</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIST<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab76ad9f323bc617cfce12a9df044441f"></a></td>
<td class="doxyEnumItemDescription">This instruction implements a fp-&gt;int store from FP stack slots</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa84fca900d9cdc9761f9e0f00d386b1e"></a></td>
<td class="doxyEnumItemDescription">This instruction implements an extending load to FP stack slots</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FST<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa01d97a3473a8e41bf1dcc6ba3ea8c7eb"></a></td>
<td class="doxyEnumItemDescription">This instruction implements a truncating store from FP stack slots</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VAARG_64<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaed54019ccab3d2b3d28b3eae73a57d98"></a></td>
<td class="doxyEnumItemDescription">These instructions grab the address of the next argument from a va_list</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VAARG_X32<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa05fff877311a353768a3795e99a28bfe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTRUNCSTOREUS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8adef190fdf91a221cd7c481c1589980"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTRUNCSTORES<a id="a9441a4f94d36d0f7c0c34aca42e3f76aacfe7beb33a948c4ed025f2487c0bf2f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMTRUNCSTOREUS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa873ea178137a32bd3665fadd64a54547"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMTRUNCSTORES<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaf7316afbc9db0eb538a42eedad77dd37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MGATHER<a id="a9441a4f94d36d0f7c0c34aca42e3f76aab87f23ed71e4bfc2234328ede40dccd2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSCATTER<a id="a9441a4f94d36d0f7c0c34aca42e3f76aac94a1f22824051f250590a7fa31e442c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AESENC128KL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa33fcd967dbc97acf0f12c49847942536"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AESDEC128KL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaa27c1071edae41c208c483ae11588246"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AESENC256KL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa644ab8ad04ed5b3f23c3fad56501c716"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AESDEC256KL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa99dc9b1f7c6dac11c969df3a293e3a2f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AESENCWIDE128KL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aae309ef23b118357ddb2ebde54fd2d5bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AESDECWIDE128KL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa0063c59cc2e72b7624e64b2c1be3994e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AESENCWIDE256KL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa82b827caf756179657650adf332b677b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AESDECWIDE256KL<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa9374d451b8bdb7a3b81b36d232025dfd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPCCXADD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aaca2c3acd9376753cf352cc5c8c64f199"></a></td>
<td class="doxyEnumItemDescription">Compare and Add if Condition is Met</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VASTART_SAVE_XMM_REGS<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa85e3eaca3021f7b1c78eb4105d281445"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLOAD<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8a8c8f74a281b988a0641dd7f909e20a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSTORE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa99e2bb0ac23ed780f3929d5024cbc088"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_MEMORY_OPCODE<a id="a9441a4f94d36d0f7c0c34aca42e3f76aa8ae930c725ba632011e1ae7e1eecda5a"></a></td>
<td class="doxyEnumItemDescription"> (= CSTORE)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
