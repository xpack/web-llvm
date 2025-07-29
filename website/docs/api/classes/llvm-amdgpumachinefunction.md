---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpumachinefunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPUMachineFunction` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUMachineFunction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">Target/AMDGPU/AMDGPUMachineFunction.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> - This class can be derived from and used by targets to hold private target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/r600machinefunctioninfo">R600MachineFunctionInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo">SIMachineFunctionInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class keeps track of the SPI_SP_INPUT_ADDR config register, which tells the hardware which interpolation parameters to load. <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a> (const Function &amp;F, const AMDGPUSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ced58aedd5a6e72293baf4894eff497">getExplicitKernArgSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d8554bed127850d39571581b7ded81">getMaxKernArgAlign</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2bde424bd7365a73971777ed20a7a8">getLDSSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cf3d96902ddf401b7d128644c0d19ce">getGDSSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab37f1839fd82f8b84b7a2ca87b289c46">isEntryFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1af3affe7a4cee4c8f08afbd7e20282">isModuleEntryFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc6e445f31f547c90d8d35d0b2259df">isChainFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a54a8e4e1d0b402f3cfd22a32bb3452">isBottomOfStack</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3d7e85a788c31301c51ac32d2788c51">hasNoSignedZerosFPMath</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407ff8c3197738bf736ec51719151e48">isMemoryBound</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61125d565ef25fe00c5ca2a62c3c0e63">needsWaveLimiter</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa98e28f571427a5c66c2f74420e85c4c">hasInitWholeWave</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10b5e43cf76cb088fdcd63d47146b703">setInitWholeWave</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb5cd8f55deecfdc2acb25c44491a36">allocateLDSGlobal</a> (const DataLayout &amp;DL, const GlobalVariable &amp;GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37239bfcbdcba6fbb3c2ca3226e2d90b">allocateLDSGlobal</a> (const DataLayout &amp;DL, const GlobalVariable &amp;GV, Align Trailing)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b38e2d55792f4c7e547a0ef20a76af">getDynLDSAlign</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a525be06bfa09ba3686ce7a9406a3f6cf">setDynLDSAlign</a> (const Function &amp;F, const GlobalVariable &amp;GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347908ae309a3e56923ff52177e50f89">setUsesDynamicLDS</a> (bool DynLDS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e4d90e6195c166c1d7115f6815a3fa">isDynamicLDSUsed</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9318690cba377542ffecdb6a8a2ac39f">ExplicitKernArgSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5bc726d50b57e9e82bfd02eecb7e91">MaxKernArgAlign</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea1052b644ee8178f59af2fc849ad74">LDSSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of bytes in the LDS that are being used. <a href="#a4ea1052b644ee8178f59af2fc849ad74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e4dd0cb7a44f4d03ce17571e9b63c06">GDSSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f51075bee6e9e5c9d7dfb47ea79a85">StaticLDSSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of bytes in the LDS allocated statically. <a href="#ad8f51075bee6e9e5c9d7dfb47ea79a85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f8ddd08e6b72408232138955af8b84">StaticGDSSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26dfb8d7a283c9d86569786a61f4ced8">DynLDSAlign</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/align">Align</a> for dynamic shared memory if any. <a href="#a26dfb8d7a283c9d86569786a61f4ced8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd14168911d00008d017d4d2f79d88d7">UsesDynamicLDS</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59a9d94554865b7bab5bea11f8b973d">IsEntryFunction</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6d8c6efdd13fdf8c3831ca049d1377">IsModuleEntryFunction</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a037d12d5a0b5626bca86803be4ff3dcc">IsChainFunction</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb0af18f1972cd5ac546dd5c00fd8a3c">NoSignedZerosFPMath</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2639538d0b4aad2be25d5c27085c7d">MemoryBound</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42989a7812f1018b0aa737f7fed9f3f2">WaveLimiter</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7087f849071c453aff24149484195ad">HasInitWholeWave</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, unsigned, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a261a7da3fba146fc550b218428e993bf">LocalMemoryObjects</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map to keep track of local memory objects and their offsets within the local memory space. <a href="#a261a7da3fba146fc550b218428e993bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13726c00b6a447734d47ecaae49ebbd0">getLDSKernelIdMetadata</a> (const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6367c396ac6375707af64e0f9a8ad08f">getLDSAbsoluteAddress</a> (const GlobalValue &amp;GV)</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUMachineFunction() {#a068641b222182c6ca0412660993bf1fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUMachineFunction::AMDGPUMachineFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget">AMDGPUSubtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp">AMDGPUMachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca27a385675142c462571165c839e41aa0">llvm::CallingConv::AMDGPU_KERNEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a9318690cba377542ffecdb6a8a2ac39f">ExplicitKernArgSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a6e4dd0cb7a44f4d03ce17571e9b63c06">GDSSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af017d22179b9ba0f528f0e415fe480e0">llvm::AMDGPU::getIntegerPairAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp/#a837598db9a2a36fcd2506709d42134bc">getKernelDynLDSGlobalFromFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a70f42ed02a8993b84bdf97da5d54d097">llvm::Attribute::getValueAsBool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp/#a25f072ebcf5504971ea9d182365ec466">hasLDSKernelArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="#a037d12d5a0b5626bca86803be4ff3dcc">IsChainFunction</a>, <a href="#aa59a9d94554865b7bab5bea11f8b973d">IsEntryFunction</a>, <a href="#ace6d8c6efdd13fdf8c3831ca049d1377">IsModuleEntryFunction</a>, <a href="#a4ea1052b644ee8178f59af2fc849ad74">LDSSize</a>, <a href="#a5b5bc726d50b57e9e82bfd02eecb7e91">MaxKernArgAlign</a>, <a href="#a6f2639538d0b4aad2be25d5c27085c7d">MemoryBound</a>, <a href="#adb0af18f1972cd5ac546dd5c00fd8a3c">NoSignedZerosFPMath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9b5e79699935bf721647d44339701860">llvm::CallingConv::SPIR_KERNEL</a>, <a href="#a42f8ddd08e6b72408232138955af8b84">StaticGDSSize</a>, <a href="#ad8f51075bee6e9e5c9d7dfb47ea79a85">StaticLDSSize</a>, <a href="#abd14168911d00008d017d4d2f79d88d7">UsesDynamicLDS</a> and <a href="#a42989a7812f1018b0aa737f7fed9f3f2">WaveLimiter</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600machinefunctioninfo/#ac625294cecdec3d1d7bec80b56d5688f">llvm::R600MachineFunctionInfo::R600MachineFunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af63d1fba23bc323d27c9dc50313698eb">llvm::SIMachineFunctionInfo::SIMachineFunctionInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocateLDSGlobal() {#aafb5cd8f55deecfdc2acb25c44491a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPUMachineFunction::allocateLDSGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; GV)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>References <a href="#aafb5cd8f55deecfdc2acb25c44491a36">allocateLDSGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="#a26dfb8d7a283c9d86569786a61f4ced8">DynLDSAlign</a>.</p>


<p>Referenced by <a href="#aafb5cd8f55deecfdc2acb25c44491a36">allocateLDSGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6a5658766cf2558d59b0344bb48f0754">llvm::AMDGPUTargetLowering::LowerGlobalAddress</a>.</p>

</div>
</div>

### allocateLDSGlobal() {#a37239bfcbdcba6fbb3c2ca3226e2d90b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUMachineFunction::allocateLDSGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; GV, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Trailing)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp">AMDGPUMachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a6e4dd0cb7a44f4d03ce17571e9b63c06">GDSSize</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a702d4986803a1782ba305b1c7a0f1c21">llvm::GlobalValue::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a115ac0121663aa8365e095d095d0c633">llvm::GlobalObject::getAlign</a>, <a href="#a6367c396ac6375707af64e0f9a8ad08f">getLDSAbsoluteAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="#ac1af3affe7a4cee4c8f08afbd7e20282">isModuleEntryFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a98625eaa7fa561edb6921fc5c7fcefcd">llvm::AMDGPU::isNamedBarrier</a>, <a href="#a4ea1052b644ee8178f59af2fc849ad74">LDSSize</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a5b71ba6fa435ec288aba849e113721a7">llvm::AMDGPUAS::REGION_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#a42f8ddd08e6b72408232138955af8b84">StaticGDSSize</a> and <a href="#ad8f51075bee6e9e5c9d7dfb47ea79a85">StaticLDSSize</a>.</p>

</div>
</div>

### getDynLDSAlign() {#af2b38e2d55792f4c7e547a0ef20a76af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AMDGPUMachineFunction::getDynLDSAlign ()</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#a26dfb8d7a283c9d86569786a61f4ced8">DynLDSAlign</a>.</p>

</div>
</div>

### getExplicitKernArgSize() {#a1ced58aedd5a6e72293baf4894eff497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPUMachineFunction::getExplicitKernArgSize ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#a9318690cba377542ffecdb6a8a2ac39f">ExplicitKernArgSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a5a663b4deab0378b73e460588d96871a">llvm::AMDGPUTargetLowering::getImplicitParameterOffset</a>.</p>

</div>
</div>

### getGDSSize() {#a5cf3d96902ddf401b7d128644c0d19ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPUMachineFunction::getGDSSize ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#a6e4dd0cb7a44f4d03ce17571e9b63c06">GDSSize</a>.</p>

</div>
</div>

### getLDSSize() {#a1e2bde424bd7365a73971777ed20a7a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPUMachineFunction::getLDSSize ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#a4ea1052b644ee8178f59af2fc849ad74">LDSSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af63d1fba23bc323d27c9dc50313698eb">llvm::SIMachineFunctionInfo::SIMachineFunctionInfo</a>.</p>

</div>
</div>

### getMaxKernArgAlign() {#a13d8554bed127850d39571581b7ded81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AMDGPUMachineFunction::getMaxKernArgAlign ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#a5b5bc726d50b57e9e82bfd02eecb7e91">MaxKernArgAlign</a>.</p>

</div>
</div>

### hasInitWholeWave() {#aa98e28f571427a5c66c2f74420e85c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::hasInitWholeWave ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#af7087f849071c453aff24149484195ad">HasInitWholeWave</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1e0aa89e6577318443a666796f159a30">llvm::SIMachineFunctionInfo::allocateWWMSpill</a>.</p>

</div>
</div>

### hasNoSignedZerosFPMath() {#ad3d7e85a788c31301c51ac32d2788c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::hasNoSignedZerosFPMath ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#adb0af18f1972cd5ac546dd5c00fd8a3c">NoSignedZerosFPMath</a>.</p>

</div>
</div>

### isBottomOfStack() {#a4a54a8e4e1d0b402f3cfd22a32bb3452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::isBottomOfStack ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>References <a href="#a8bc6e445f31f547c90d8d35d0b2259df">isChainFunction</a> and <a href="#ab37f1839fd82f8b84b7a2ca87b289c46">isEntryFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>.</p>

</div>
</div>

### isChainFunction() {#a8bc6e445f31f547c90d8d35d0b2259df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::isChainFunction ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#a037d12d5a0b5626bca86803be4ff3dcc">IsChainFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1e0aa89e6577318443a666796f159a30">llvm::SIMachineFunctionInfo::allocateWWMSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a7865e2cad3030c3c48b64c9cf1243d46">llvm::SIFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a9011fd4dec97b74c665033f7a42d485a">llvm::SIFrameLowering::hasFPImpl</a>, <a href="#a4a54a8e4e1d0b402f3cfd22a32bb3452">isBottomOfStack</a> and <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a572f7d3a80aeaedcf8eec0b7872e6c89">llvm::SIFrameLowering::requiresStackPointerReference</a>.</p>

</div>
</div>

### isDynamicLDSUsed() {#a32e4d90e6195c166c1d7115f6815a3fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMachineFunction::isDynamicLDSUsed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp">AMDGPUMachineFunction.cpp</a>.</p>


<p>Reference <a href="#abd14168911d00008d017d4d2f79d88d7">UsesDynamicLDS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#a00df0d04b86c6d3d0d027c912afb7282">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitHiddenKernelArgs</a>.</p>

</div>
</div>

### isEntryFunction() {#ab37f1839fd82f8b84b7a2ca87b289c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::isEntryFunction ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#aa59a9d94554865b7bab5bea11f8b973d">IsEntryFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1e0aa89e6577318443a666796f159a30">llvm::SIMachineFunctionInfo::allocateWWMSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a7865e2cad3030c3c48b64c9cf1243d46">llvm::SIFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ac5bebf636fd9c3f6c9b7484f3244fb67">llvm::SIFrameLowering::determineCalleeSavesSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa07427c984394cc2c4b4cf8b7158def4">llvm::AMDGPUAsmPrinter::emitFunctionBodyEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#ae3bd05a52450589489fbb3602ad95530">llvm::AMDGPUAsmPrinter::emitFunctionBodyStart</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a14f377c5693a34d02d4554382492ee1b">llvm::AMDGPUAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a9011fd4dec97b74c665033f7a42d485a">llvm::SIFrameLowering::hasFPImpl</a>, <a href="#a4a54a8e4e1d0b402f3cfd22a32bb3452">isBottomOfStack</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a8bc1455f0ec29a33f76adecf8e668af8">llvm::AMDGPULegalizerInfo::legalizeImplicitArgPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ab40f765949a66d4973d528dcf38615fc">llvm::AMDGPULegalizerInfo::legalizeLDSKernelId</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a572f7d3a80aeaedcf8eec0b7872e6c89">llvm::SIFrameLowering::requiresStackPointerReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af63d1fba23bc323d27c9dc50313698eb">llvm::SIMachineFunctionInfo::SIMachineFunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#abc385634c5cb053216d49b31696b2e6a">llvm::SITargetLowering::supportSplitCSR</a>.</p>

</div>
</div>

### isMemoryBound() {#a407ff8c3197738bf736ec51719151e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::isMemoryBound ()</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#a6f2639538d0b4aad2be25d5c27085c7d">MemoryBound</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ab51348abdbbc76d0e8db5c01a5ee5280">llvm::SIMachineFunctionInfo::getMinAllowedOccupancy</a>.</p>

</div>
</div>

### isModuleEntryFunction() {#ac1af3affe7a4cee4c8f08afbd7e20282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::isModuleEntryFunction ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#ace6d8c6efdd13fdf8c3831ca049d1377">IsModuleEntryFunction</a>.</p>


<p>Referenced by <a href="#a37239bfcbdcba6fbb3c2ca3226e2d90b">allocateLDSGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6a5658766cf2558d59b0344bb48f0754">llvm::AMDGPUTargetLowering::LowerGlobalAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### needsWaveLimiter() {#a61125d565ef25fe00c5ca2a62c3c0e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::needsWaveLimiter ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#a42989a7812f1018b0aa737f7fed9f3f2">WaveLimiter</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ab51348abdbbc76d0e8db5c01a5ee5280">llvm::SIMachineFunctionInfo::getMinAllowedOccupancy</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### setDynLDSAlign() {#a525be06bfa09ba3686ce7a9406a3f6cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMachineFunction::setDynLDSAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp">AMDGPUMachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a26dfb8d7a283c9d86569786a61f4ced8">DynLDSAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a115ac0121663aa8365e095d095d0c633">llvm::GlobalObject::getAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp/#a837598db9a2a36fcd2506709d42134bc">getKernelDynLDSGlobalFromFunction</a>, <a href="#a6367c396ac6375707af64e0f9a8ad08f">getLDSAbsoluteAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="#a4ea1052b644ee8178f59af2fc849ad74">LDSSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="#ad8f51075bee6e9e5c9d7dfb47ea79a85">StaticLDSSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>.</p>

</div>
</div>

### setInitWholeWave() {#a10b5e43cf76cb088fdcd63d47146b703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPUMachineFunction::setInitWholeWave ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Reference <a href="#af7087f849071c453aff24149484195ad">HasInitWholeWave</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### setUsesDynamicLDS() {#a347908ae309a3e56923ff52177e50f89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMachineFunction::setUsesDynamicLDS (bool DynLDS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp">AMDGPUMachineFunction.cpp</a>.</p>


<p>Reference <a href="#abd14168911d00008d017d4d2f79d88d7">UsesDynamicLDS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DynLDSAlign {#a26dfb8d7a283c9d86569786a61f4ced8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AMDGPUMachineFunction::DynLDSAlign</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/align">Align</a> for dynamic shared memory if any.</p>


<p>Dynamic shared memory is allocated directly after the static one, i.e., LDSSize. Need to pad LDSSize to ensure that dynamic one is aligned accordingly. The maximal alignment is updated during IR translation or lowering stages.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#aafb5cd8f55deecfdc2acb25c44491a36">allocateLDSGlobal</a>, <a href="#af2b38e2d55792f4c7e547a0ef20a76af">getDynLDSAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a> and <a href="#a525be06bfa09ba3686ce7a9406a3f6cf">setDynLDSAlign</a>.</p>

</div>
</div>

### ExplicitKernArgSize {#a9318690cba377542ffecdb6a8a2ac39f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPUMachineFunction::ExplicitKernArgSize = 0</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>, <a href="#a1ced58aedd5a6e72293baf4894eff497">getExplicitKernArgSize</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>.</p>

</div>
</div>

### GDSSize {#a6e4dd0cb7a44f4d03ce17571e9b63c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPUMachineFunction::GDSSize = 0</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a37239bfcbdcba6fbb3c2ca3226e2d90b">allocateLDSGlobal</a>, <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>, <a href="#a5cf3d96902ddf401b7d128644c0d19ce">getGDSSize</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>.</p>

</div>
</div>

### HasInitWholeWave {#af7087f849071c453aff24149484195ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::HasInitWholeWave = false</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#aa98e28f571427a5c66c2f74420e85c4c">hasInitWholeWave</a> and <a href="#a10b5e43cf76cb088fdcd63d47146b703">setInitWholeWave</a>.</p>

</div>
</div>

### IsChainFunction {#a037d12d5a0b5626bca86803be4ff3dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::IsChainFunction = false</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a> and <a href="#a8bc6e445f31f547c90d8d35d0b2259df">isChainFunction</a>.</p>

</div>
</div>

### IsEntryFunction {#aa59a9d94554865b7bab5bea11f8b973d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::IsEntryFunction = false</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a> and <a href="#ab37f1839fd82f8b84b7a2ca87b289c46">isEntryFunction</a>.</p>

</div>
</div>

### IsModuleEntryFunction {#ace6d8c6efdd13fdf8c3831ca049d1377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::IsModuleEntryFunction = false</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a> and <a href="#ac1af3affe7a4cee4c8f08afbd7e20282">isModuleEntryFunction</a>.</p>

</div>
</div>

### LDSSize {#a4ea1052b644ee8178f59af2fc849ad74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPUMachineFunction::LDSSize = 0</td>
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

<p>Number of bytes in the LDS that are being used.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a37239bfcbdcba6fbb3c2ca3226e2d90b">allocateLDSGlobal</a>, <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>, <a href="#a1e2bde424bd7365a73971777ed20a7a8">getLDSSize</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a> and <a href="#a525be06bfa09ba3686ce7a9406a3f6cf">setDynLDSAlign</a>.</p>

</div>
</div>

### MaxKernArgAlign {#a5b5bc726d50b57e9e82bfd02eecb7e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AMDGPUMachineFunction::MaxKernArgAlign</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>, <a href="#a13d8554bed127850d39571581b7ded81">getMaxKernArgAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af63d1fba23bc323d27c9dc50313698eb">llvm::SIMachineFunctionInfo::SIMachineFunctionInfo</a>.</p>

</div>
</div>

### MemoryBound {#a6f2639538d0b4aad2be25d5c27085c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::MemoryBound = false</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a> and <a href="#a407ff8c3197738bf736ec51719151e48">isMemoryBound</a>.</p>

</div>
</div>

### NoSignedZerosFPMath {#adb0af18f1972cd5ac546dd5c00fd8a3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::NoSignedZerosFPMath = false</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>, <a href="#ad3d7e85a788c31301c51ac32d2788c51">hasNoSignedZerosFPMath</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>.</p>

</div>
</div>

### StaticGDSSize {#a42f8ddd08e6b72408232138955af8b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPUMachineFunction::StaticGDSSize = 0</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a37239bfcbdcba6fbb3c2ca3226e2d90b">allocateLDSGlobal</a> and <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>.</p>

</div>
</div>

### StaticLDSSize {#ad8f51075bee6e9e5c9d7dfb47ea79a85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPUMachineFunction::StaticLDSSize = 0</td>
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

<p>Number of bytes in the LDS allocated statically.</p>


<p>This field is only used in the instruction selector and not part of the machine function info.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a37239bfcbdcba6fbb3c2ca3226e2d90b">allocateLDSGlobal</a>, <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a> and <a href="#a525be06bfa09ba3686ce7a9406a3f6cf">setDynLDSAlign</a>.</p>

</div>
</div>

### UsesDynamicLDS {#abd14168911d00008d017d4d2f79d88d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::UsesDynamicLDS = false</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>, <a href="#a32e4d90e6195c166c1d7115f6815a3fa">isDynamicLDSUsed</a> and <a href="#a347908ae309a3e56923ff52177e50f89">setUsesDynamicLDS</a>.</p>

</div>
</div>

### WaveLimiter {#a42989a7812f1018b0aa737f7fed9f3f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUMachineFunction::WaveLimiter = false</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>


<p>Referenced by <a href="#a068641b222182c6ca0412660993bf1fe">AMDGPUMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a> and <a href="#a61125d565ef25fe00c5ca2a62c3c0e63">needsWaveLimiter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LocalMemoryObjects {#a261a7da3fba146fc550b218428e993bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;const GlobalValue *, unsigned, 4&gt; llvm::AMDGPUMachineFunction::LocalMemoryObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map to keep track of local memory objects and their offsets within the local memory space.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getLDSAbsoluteAddress() {#a6367c396ac6375707af64e0f9a8ad08f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; AMDGPUMachineFunction::getLDSAbsoluteAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp">AMDGPUMachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a7918bda9a2e43bf56739cfe8c3d92803">llvm::GlobalValue::getAbsoluteSymbolRange</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a702d4986803a1782ba305b1c7a0f1c21">llvm::GlobalValue::getAddressSpace</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>.</p>


<p>Referenced by <a href="#a37239bfcbdcba6fbb3c2ca3226e2d90b">allocateLDSGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#adfa24b29ddb799607095546fa388954a">llvm::AMDGPUAsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6a5658766cf2558d59b0344bb48f0754">llvm::AMDGPUTargetLowering::LowerGlobalAddress</a> and <a href="#a525be06bfa09ba3686ce7a9406a3f6cf">setDynLDSAlign</a>.</p>

</div>
</div>

### getLDSKernelIdMetadata() {#a13726c00b6a447734d47ecaae49ebbd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; AMDGPUMachineFunction::getLDSKernelIdMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp">AMDGPUMachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3bf20d7d5d2943a38d01c00d1aa82104">llvm::AMDGPULegalizerInfo::getLDSKernelId</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-cpp">AMDGPUMachineFunction.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
