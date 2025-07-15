---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/callingconv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `CallingConv` Namespace Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/callingconv">CallingConv</a> Namespace - This namespace contains an enum with a value for the well-known calling conventions. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::CallingConv { ... }
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf8cf606905c10634e831390981b0ed">ID</a> = unsigned</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM IR allows to use arbitrary numbers as calling convention identifiers. <a href="#abdf8cf606905c10634e831390981b0ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#ac6aa1387c4375260e2468eb5a77fdb4c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of enums which specify the assigned numeric values for known llvm calling conventions. <a href="#ac6aa1387c4375260e2468eb5a77fdb4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/callingconv">CallingConv</a> Namespace - This namespace contains an enum with a value for the well-known calling conventions.</p>

<div class="doxySectionDef">

## Typedefs

### ID {#abdf8cf606905c10634e831390981b0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CallingConv::ID =  unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM IR allows to use arbitrary numbers as calling convention identifiers.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">CallingConv.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#ac6aa1387c4375260e2468eb5a77fdb4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set of enums which specify the assigned numeric values for known llvm calling conventions.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C<a id="ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb"></a></td>
<td class="doxyEnumItemDescription">The default llvm calling convention, compatible with C (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Fast<a id="ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba"></a></td>
<td class="doxyEnumItemDescription">Attempts to make calls as fast as possible (e.g (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cold<a id="ac6aa1387c4375260e2468eb5a77fdb4ca94ec9273479164e4aec1d5d91b71dc85"></a></td>
<td class="doxyEnumItemDescription">Attempts to make code in the caller as efficient as possible under the assumption that the call is not commonly executed (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GHC<a id="ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e"></a></td>
<td class="doxyEnumItemDescription">Used by the Glasgow Haskell Compiler (GHC) (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HiPE<a id="ac6aa1387c4375260e2468eb5a77fdb4ca20ddc463f96d806f369d56205ea205f5"></a></td>
<td class="doxyEnumItemDescription">Used by the High-Performance Erlang Compiler (HiPE) (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AnyReg<a id="ac6aa1387c4375260e2468eb5a77fdb4ca4f42667edde6e9cb80cfae6361e5e76a"></a></td>
<td class="doxyEnumItemDescription">OBSOLETED - Used for stack based JavaScript calls (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PreserveMost<a id="ac6aa1387c4375260e2468eb5a77fdb4ca4eeb29fe27dc20afa4f443765f45f9a5"></a></td>
<td class="doxyEnumItemDescription">Used for runtime calls that preserves most registers (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PreserveAll<a id="ac6aa1387c4375260e2468eb5a77fdb4ca9f6ac05d37c2fbf197de42295c23fd6e"></a></td>
<td class="doxyEnumItemDescription">Used for runtime calls that preserves (almost) all registers (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Swift<a id="ac6aa1387c4375260e2468eb5a77fdb4ca2740493172a4ce246941c8cff95e0f83"></a></td>
<td class="doxyEnumItemDescription">Calling convention for Swift (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CXX_FAST_TLS<a id="ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf"></a></td>
<td class="doxyEnumItemDescription">Used for access functions (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Tail<a id="ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e"></a></td>
<td class="doxyEnumItemDescription">Attemps to make calls as fast as possible while guaranteeing that tail call optimization can always be performed (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CFGuard_Check<a id="ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b"></a></td>
<td class="doxyEnumItemDescription">Special calling convention on Windows for calling the Control Guard <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> ICall funtion (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SwiftTail<a id="ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa"></a></td>
<td class="doxyEnumItemDescription">This follows the Swift calling convention in how arguments are passed but guarantees tail calls will be made by making the callee clean up their stack (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PreserveNone<a id="ac6aa1387c4375260e2468eb5a77fdb4cad5385f408f537fc279d485c77d2463ce"></a></td>
<td class="doxyEnumItemDescription">Used for runtime calls that preserves none general registers (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstTargetCC<a id="ac6aa1387c4375260e2468eb5a77fdb4caa901d0f0329620dac86bcfc42f5bfa7e"></a></td>
<td class="doxyEnumItemDescription">This is the start of the target-specific calling conventions, e.g (= 64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86_StdCall<a id="ac6aa1387c4375260e2468eb5a77fdb4caa88ccf4313b5bc700dec76fd9bc5d40e"></a></td>
<td class="doxyEnumItemDescription">stdcall is mostly used by the Win32 API (= 64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86_FastCall<a id="ac6aa1387c4375260e2468eb5a77fdb4cafde87569738f9e23963e8735f71c33eb"></a></td>
<td class="doxyEnumItemDescription">'fast' analog of X86_StdCall (= 65)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM_APCS<a id="ac6aa1387c4375260e2468eb5a77fdb4ca39e4f9a6d108588930a09d779d4e812f"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Procedure Calling Standard (obsolete, but still used on some targets) (= 66)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM_AAPCS<a id="ac6aa1387c4375260e2468eb5a77fdb4ca6460922e7050fc0dcff22631e4bc7fdb"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Architecture Procedure Calling Standard calling convention (aka <a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91">EABI</a>) (= 67)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM_AAPCS_VFP<a id="ac6aa1387c4375260e2468eb5a77fdb4caf5725080d76d25fff371be12a0bf29f4"></a></td>
<td class="doxyEnumItemDescription">Same as ARM_AAPCS, but uses hard floating point ABI (= 68)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSP430_INTR<a id="ac6aa1387c4375260e2468eb5a77fdb4cac6355efbcea63774ceca1dfa7b237d42"></a></td>
<td class="doxyEnumItemDescription">Used for <a href="/web-llvm/docs/api/namespaces/llvm/msp430">MSP430</a> interrupt routines (= 69)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86_ThisCall<a id="ac6aa1387c4375260e2468eb5a77fdb4ca97109ccd68cac64fb38dbd24fc4589c6"></a></td>
<td class="doxyEnumItemDescription">Similar to X86_StdCall (= 70)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PTX_Kernel<a id="ac6aa1387c4375260e2468eb5a77fdb4cae60325da71f0576e18cc0e5dd7e8afb6"></a></td>
<td class="doxyEnumItemDescription">Call to a PTX kernel. Passes all arguments in parameter space (= 71)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PTX_Device<a id="ac6aa1387c4375260e2468eb5a77fdb4ca9b03ea185599539f24eb1f467627c111"></a></td>
<td class="doxyEnumItemDescription">Call to a PTX device function (= 72)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIR_FUNC<a id="ac6aa1387c4375260e2468eb5a77fdb4caacadec9c4ef27d184bcbbea409afebb2"></a></td>
<td class="doxyEnumItemDescription">Used for SPIR non-kernel device functions (= 75)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIR_KERNEL<a id="ac6aa1387c4375260e2468eb5a77fdb4ca9b5e79699935bf721647d44339701860"></a></td>
<td class="doxyEnumItemDescription">Used for SPIR kernel functions (= 76)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Intel_OCL_BI<a id="ac6aa1387c4375260e2468eb5a77fdb4cad47327c131a0990283111588b89587cb"></a></td>
<td class="doxyEnumItemDescription">Used for Intel OpenCL built-ins (= 77)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86_64_SysV<a id="ac6aa1387c4375260e2468eb5a77fdb4ca10f11fb587acddab17f3ad85eb698fbe"></a></td>
<td class="doxyEnumItemDescription">The C convention as specified in the x86-64 supplement to the System V ABI, used on most non-Windows systems (= 78)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Win64<a id="ac6aa1387c4375260e2468eb5a77fdb4cae41511c1ad4197da36cef403f34bac72"></a></td>
<td class="doxyEnumItemDescription">The C convention as implemented on Windows/x86-64 and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> (= 79)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86_VectorCall<a id="ac6aa1387c4375260e2468eb5a77fdb4cacfa4cc9bcdaefd5e969c258c994052b9"></a></td>
<td class="doxyEnumItemDescription">MSVC calling convention that passes vectors and vector aggregates in SSE registers (= 80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUMMY_HHVM<a id="ac6aa1387c4375260e2468eb5a77fdb4ca51dcc0bcdca1d5609b0ec4b43c0d9971"></a></td>
<td class="doxyEnumItemDescription">Placeholders for HHVM calling conventions (deprecated, removed) (= 81)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUMMY_HHVM_C<a id="ac6aa1387c4375260e2468eb5a77fdb4cad710a26c741142a91059eff051990185"></a></td>
<td class="doxyEnumItemDescription"> (= 82)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86_INTR<a id="ac6aa1387c4375260e2468eb5a77fdb4ca765508a953368531a7d69d1279e6cfb1"></a></td>
<td class="doxyEnumItemDescription">x86 hardware interrupt context (= 83)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVR_INTR<a id="ac6aa1387c4375260e2468eb5a77fdb4ca44deee0b3babbda0be6f27856afaacf9"></a></td>
<td class="doxyEnumItemDescription">Used for <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> interrupt routines (= 84)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVR_SIGNAL<a id="ac6aa1387c4375260e2468eb5a77fdb4ca1e000300c2d50f08aa18761448d5860e"></a></td>
<td class="doxyEnumItemDescription">Used for <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> signal routines (= 85)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVR_BUILTIN<a id="ac6aa1387c4375260e2468eb5a77fdb4ca8ddc8eecc1584438b45d1d45fc8b87ae"></a></td>
<td class="doxyEnumItemDescription">Used for special <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> rtlib functions which have an "optimized" convention to preserve registers (= 86)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_VS<a id="ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223"></a></td>
<td class="doxyEnumItemDescription">Used for Mesa vertex shaders, or AMDPAL last shader stage before rasterization (vertex shader if tessellation and geometry are not in use, or otherwise copy shader if one is needed) (= 87)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_GS<a id="ac6aa1387c4375260e2468eb5a77fdb4ca6f08d1631b96043fe0201973d84e5539"></a></td>
<td class="doxyEnumItemDescription">Used for Mesa/AMDPAL geometry shaders (= 88)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_PS<a id="ac6aa1387c4375260e2468eb5a77fdb4ca91283117ce67ebdae50cc7730694d8f8"></a></td>
<td class="doxyEnumItemDescription">Used for Mesa/AMDPAL pixel shaders (= 89)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_CS<a id="ac6aa1387c4375260e2468eb5a77fdb4ca16c3e679fa61136bfeb3c5c9b7542d9f"></a></td>
<td class="doxyEnumItemDescription">Used for Mesa/AMDPAL compute shaders (= 90)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_KERNEL<a id="ac6aa1387c4375260e2468eb5a77fdb4ca27a385675142c462571165c839e41aa0"></a></td>
<td class="doxyEnumItemDescription">Used for <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> code object kernels (= 91)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86_RegCall<a id="ac6aa1387c4375260e2468eb5a77fdb4cafab01b07b85e043c71ad4e2715d22073"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> calling convention used for parameters transfer optimization (= 92)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_HS<a id="ac6aa1387c4375260e2468eb5a77fdb4ca5c0f66e45afd7c51f4ee51552d8fb606"></a></td>
<td class="doxyEnumItemDescription">Used for Mesa/AMDPAL hull shaders (= tessellation control shaders) (= 93)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSP430_BUILTIN<a id="ac6aa1387c4375260e2468eb5a77fdb4ca1be5f33158d1f92c70edc260fdd7fc3c"></a></td>
<td class="doxyEnumItemDescription">Used for special <a href="/web-llvm/docs/api/namespaces/llvm/msp430">MSP430</a> rtlib functions which have an "optimized" convention using additional registers (= 94)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_LS<a id="ac6aa1387c4375260e2468eb5a77fdb4caf2c5be679d7769a9f3e5e308f73a9ff8"></a></td>
<td class="doxyEnumItemDescription">Used for AMDPAL vertex shader if tessellation is in use (= 95)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_ES<a id="ac6aa1387c4375260e2468eb5a77fdb4cad61318e853e529ac703f52a853efa1d1"></a></td>
<td class="doxyEnumItemDescription">Used for AMDPAL shader stage before geometry shader if geometry is in use (= 96)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AArch64_VectorCall<a id="ac6aa1387c4375260e2468eb5a77fdb4ca0e62ecb2c693281fafd77f39b2ddd284"></a></td>
<td class="doxyEnumItemDescription">Used between <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> Advanced SIMD functions (= 97)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AArch64_SVE_VectorCall<a id="ac6aa1387c4375260e2468eb5a77fdb4ca300efd85d130657d0d06f0469980bd0f"></a></td>
<td class="doxyEnumItemDescription">Used between <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> SVE functions (= 98)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_EmscriptenInvoke<a id="ac6aa1387c4375260e2468eb5a77fdb4ca7f1f535012fdeda3c9f35f2079b919a7"></a></td>
<td class="doxyEnumItemDescription">For emscripten __invoke_* functions (= 99)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_Gfx<a id="ac6aa1387c4375260e2468eb5a77fdb4ca4f9824c54cfd32b3e38c01d5331f318b"></a></td>
<td class="doxyEnumItemDescription">Used for AMD graphics targets (= 100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">M68k_INTR<a id="ac6aa1387c4375260e2468eb5a77fdb4ca19e10cbfb07e93e0a7e40cca2faff4c0"></a></td>
<td class="doxyEnumItemDescription">Used for <a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> interrupt routines (= 101)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AArch64_SME_ABI_Support_Routines_PreserveMost_From_X0<a id="ac6aa1387c4375260e2468eb5a77fdb4ca7c23dce1e95fc36e9d2c168f9e036cc7"></a></td>
<td class="doxyEnumItemDescription">Preserve X0-X13, X19-X29, SP, Z0-Z31, P0-P15 (= 102)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AArch64_SME_ABI_Support_Routines_PreserveMost_From_X2<a id="ac6aa1387c4375260e2468eb5a77fdb4ca72069ecfe852db0ea1f10c1549989424"></a></td>
<td class="doxyEnumItemDescription">Preserve X2-X15, X19-X29, SP, Z0-Z31, P0-P15 (= 103)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_CS_Chain<a id="ac6aa1387c4375260e2468eb5a77fdb4ca8d298f27ddf40e08cd5aacea9837784f"></a></td>
<td class="doxyEnumItemDescription">Used on AMDGPUs to give the middle-end more control over argument placement (= 104)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDGPU_CS_ChainPreserve<a id="ac6aa1387c4375260e2468eb5a77fdb4ca521c5b7a44a8222c814379b57481aec9"></a></td>
<td class="doxyEnumItemDescription">Used on AMDGPUs to give the middle-end more control over argument placement (= 105)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">M68k_RTD<a id="ac6aa1387c4375260e2468eb5a77fdb4cafb7645aeee7db3640bbfdad799b4cfe9"></a></td>
<td class="doxyEnumItemDescription">Used for <a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> rtd-based CC (similar to <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a>'s stdcall) (= 106)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GRAAL<a id="ac6aa1387c4375260e2468eb5a77fdb4cae9c6786f93f1d156d2b40ecc6be438bb"></a></td>
<td class="doxyEnumItemDescription">Used by GraalVM. Two additional registers are reserved (= 107)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM64EC_Thunk_X64<a id="ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e"></a></td>
<td class="doxyEnumItemDescription">Calling convention used in the ARM64EC ABI to implement calls between x64 code and thunks (= 108)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM64EC_Thunk_Native<a id="ac6aa1387c4375260e2468eb5a77fdb4ca047fefb5017b2873eb2e88f1a27fb14a"></a></td>
<td class="doxyEnumItemDescription">Calling convention used in the ARM64EC ABI to implement calls between ARM64 code and thunks (= 109)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RISCV_VectorCall<a id="ac6aa1387c4375260e2468eb5a77fdb4ca12164937f88e72c8b59ca563c70187e0"></a></td>
<td class="doxyEnumItemDescription">Calling convention used for RISC-V V-extension (= 110)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AArch64_SME_ABI_Support_Routines_PreserveMost_From_X1<a id="ac6aa1387c4375260e2468eb5a77fdb4ca963e14ac38d6e3b63f8e37085702951c"></a></td>
<td class="doxyEnumItemDescription">Preserve X1-X15, X19-X29, SP, Z0-Z31, P0-P15 (= 111)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MaxID<a id="ac6aa1387c4375260e2468eb5a77fdb4ca2f101663d054cffa9c9956f30e7ecf7d"></a></td>
<td class="doxyEnumItemDescription">The highest possible <a href="#abdf8cf606905c10634e831390981b0ed">ID</a>. Must be some 2^k - 1 (= 1023)</td>
</tr>

</table>
</dd>
</dl>


<p>LLVM Calling Convention Representation</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">CallingConv.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">CallingConv.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
