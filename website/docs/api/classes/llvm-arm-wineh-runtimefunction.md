---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/arm/wineh/runtimefunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RuntimeFunction` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction">RuntimeFunction</a> - An entry in the table of procedure data (.pdata) <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ARM::WinEH::RuntimeFunction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">llvm/Support/ARMWinEH.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b259790094ea1a231c9615e7ce6808">RuntimeFunction</a> (const support::ulittle32_t *Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65c56a6dfdcea7b50ac11334f93ead1a">RuntimeFunction</a> (const support::ulittle32_t BeginAddress, const support::ulittle32_t UnwindData)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476">RuntimeFunctionFlag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde08212016aba3c342f4ff364c76651">ExceptionInformationRVA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640953dc6606d0e5659ff41c5aecdd0d">PackedUnwindData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db64c8c0387faec9126020239d7c0f6">FunctionLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#aeb1849a948db3f783d1598b797186c4a">ReturnType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9efc762fd3ae7a8e8add95799386d8f">Ret</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af806966e3f89b479ce3e4225cbcdb44f">H</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1475ab1a5cfef4363310b4b168ac3f5a">Reg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a266444653b4abae6042b825b69472f43">R</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df4a184a2540941ab26d6fc674fb89a">L</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de418235442473079cb6f6aa4f43026">C</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3395b83c55bd385b4ff4e2cd25f8bee">StackAdjust</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f972e68049aa411ee7474e67670cc7b">BeginAddress</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a></td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction">RuntimeFunction</a> - An entry in the table of procedure data (.pdata)</p>


<p>This is <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> specific, but the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Start RVA, Flag and ExceptionInformationRVA fields work identically for ARM64.</p>


<p>3 3 2 2 2 2 2 2 2 2 2 2 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 +------------------------------------------------------------—+ | <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Start RVA | +----------------—+-+-+-+--—+-+—+------------------—+—+ | Stack Adjust |C|L|R| Reg |H|Ret| <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Length |Flg| +----------------—+-+-+-+--—+-+—+------------------—+—+</p>


<p>Flag : 2-bit field with the following meanings:</p>


<ul class="doxyList ">
<li>00 = packed unwind data not used; reamining bits point to .xdata record</li>
<li>01 = packed unwind data</li>
<li>10 = packed unwind data, function assumed to have no prologue; useful for function fragments that are discontiguous with the start of the function</li>
<li>11 = reserved <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Length : 11-bit field providing the length of the entire function in bytes, divided by 2; if the function is greater than 4KB, a full .xdata record must be used instead Ret : 2-bit field indicating how the function returns</li>
<li>00 = return via pop {pc} (the L bit must be set)</li>
<li>01 = return via 16-bit branch</li>
<li>10 = return via 32-bit branch</li>
<li>11 = no epilogue; useful for function fragments that may only contain a prologue but the epilogue is elsewhere H : 1-bit flag indicating whether the function "homes" the integer parameter registers (r0-r3), allocating 16-bytes on the stack Reg : 3-bit field indicating the index of the last saved non-volatile register. If the R bit is set to 0, then only integer registers are saved (r4-rN, where N is 4 + Reg). If the R bit is set to 1, then only floating-point registers are being saved (d8-dN, where N is 8 + Reg). The special case of the R bit being set to 1 and Reg equal to 7 indicates that no registers are saved. R : 1-bit flag indicating whether the non-volatile registers are integer or floating-point. 0 indicates integer, 1 indicates floating-point. The special case of the R-flag being set and Reg being set to 7 indicates that no non-volatile registers are saved. L : 1-bit flag indicating whether the function saves/restores the link register (LR) C : 1-bit flag indicating whether the function includes extra instructions to setup a frame chain for fast walking. If this flag is set, r11 is implicitly added to the list of saved non-volatile integer registers. Stack Adjust : 10-bit field indicating the number of bytes of stack that are allocated for this function. Only values between 0x000 and 0x3f3 can be directly encoded. If the value is 0x3f4 or greater, then the low 4 bits have special meaning as follows:

<ul class="doxyList ">
<li>Bit 0-1 indicate the number of words' of adjustment (1-4), minus 1</li>
<li>Bit 2 indicates if the prologue combined adjustment into push</li>
<li>Bit 3 indicates if the epilogue combined adjustment into pop</li>
</ul></li>
</ul>

<p>RESTRICTIONS:</p>


<ul class="doxyList ">
<li>IF C is SET:

<ul class="doxyList ">
<li>L flag must be set since frame chaining requires r11 and lr</li>
<li>r11 must NOT be included in the set of registers described by Reg</li>
</ul></li>
<li>IF Ret is 0:

<ul class="doxyList ">
<li>L flag must be set</li>
</ul></li>
</ul>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RuntimeFunction() {#ab3b259790094ea1a231c9615e7ce6808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARM::WinEH::RuntimeFunction::RuntimeFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> * Data)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="#a6f972e68049aa411ee7474e67670cc7b">BeginAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>

</div>
</div>

### RuntimeFunction() {#a65c56a6dfdcea7b50ac11334f93ead1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARM::WinEH::RuntimeFunction::RuntimeFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> BeginAddress, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> UnwindData)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="#a6f972e68049aa411ee7474e67670cc7b">BeginAddress</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### C() {#a7de418235442473079cb6f6aa4f43026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::RuntimeFunction::C ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="#a2df4a184a2540941ab26d6fc674fb89a">L</a>, <a href="#a266444653b4abae6042b825b69472f43">R</a>, <a href="#a1475ab1a5cfef4363310b4b168ac3f5a">Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a6249bf4eca2396a8bfde962a65a661bb">llvm::ARM::WinEH::SavedRegisterMask</a>.</p>

</div>
</div>

### ExceptionInformationRVA() {#afde08212016aba3c342f4ff364c76651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::RuntimeFunction::ExceptionInformationRVA ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476af5a03e381d3bd0eabef74975876a2670">llvm::ARM::WinEH::RFF_Unpacked</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>

</div>
</div>

### Flag() {#a4b92d8543b07a07fc5e7f911dde42f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunctionFlag llvm::ARM::WinEH::RuntimeFunction::Flag ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>


<p>Referenced by <a href="#a7de418235442473079cb6f6aa4f43026">C</a>, <a href="#afde08212016aba3c342f4ff364c76651">ExceptionInformationRVA</a>, <a href="#a7db64c8c0387faec9126020239d7c0f6">FunctionLength</a>, <a href="#af806966e3f89b479ce3e4225cbcdb44f">H</a>, <a href="#a2df4a184a2540941ab26d6fc674fb89a">L</a>, <a href="#a640953dc6606d0e5659ff41c5aecdd0d">PackedUnwindData</a>, <a href="#a266444653b4abae6042b825b69472f43">R</a>, <a href="#a1475ab1a5cfef4363310b4b168ac3f5a">Reg</a>, <a href="#ab9efc762fd3ae7a8e8add95799386d8f">Ret</a> and <a href="#ae3395b83c55bd385b4ff4e2cd25f8bee">StackAdjust</a>.</p>

</div>
</div>

### FunctionLength() {#a7db64c8c0387faec9126020239d7c0f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::RuntimeFunction::FunctionLength ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>

</div>
</div>

### H() {#af806966e3f89b479ce3e4225cbcdb44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::RuntimeFunction::H ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a6249bf4eca2396a8bfde962a65a661bb">llvm::ARM::WinEH::SavedRegisterMask</a>.</p>

</div>
</div>

### L() {#a2df4a184a2540941ab26d6fc674fb89a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::RuntimeFunction::L ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>


<p>Referenced by <a href="#a7de418235442473079cb6f6aa4f43026">C</a>, <a href="#ab9efc762fd3ae7a8e8add95799386d8f">Ret</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a6249bf4eca2396a8bfde962a65a661bb">llvm::ARM::WinEH::SavedRegisterMask</a>.</p>

</div>
</div>

### PackedUnwindData() {#a640953dc6606d0e5659ff41c5aecdd0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::RuntimeFunction::PackedUnwindData ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>

</div>
</div>

### R() {#a266444653b4abae6042b825b69472f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::RuntimeFunction::R ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>


<p>Referenced by <a href="#a7de418235442473079cb6f6aa4f43026">C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a6249bf4eca2396a8bfde962a65a661bb">llvm::ARM::WinEH::SavedRegisterMask</a>.</p>

</div>
</div>

### Reg() {#a1475ab1a5cfef4363310b4b168ac3f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::RuntimeFunction::Reg ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>


<p>Referenced by <a href="#a7de418235442473079cb6f6aa4f43026">C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a6249bf4eca2396a8bfde962a65a661bb">llvm::ARM::WinEH::SavedRegisterMask</a>.</p>

</div>
</div>

### Ret() {#ab9efc762fd3ae7a8e8add95799386d8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReturnType llvm::ARM::WinEH::RuntimeFunction::Ret ()</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="#a2df4a184a2540941ab26d6fc674fb89a">L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a6249bf4eca2396a8bfde962a65a661bb">llvm::ARM::WinEH::SavedRegisterMask</a>.</p>

</div>
</div>

### StackAdjust() {#ae3395b83c55bd385b4ff4e2cd25f8bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::ARM::WinEH::RuntimeFunction::StackAdjust ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#a35c647fe34a495a3e78c65008a97df37">UnwindData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a431bf441802854857ff3a71232b0e08a">llvm::ARM::WinEH::EpilogueFolding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a6965acfec7c5ad1fc08d817422bf3419">llvm::ARM::WinEH::PrologueFolding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a6249bf4eca2396a8bfde962a65a661bb">llvm::ARM::WinEH::SavedRegisterMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#abbeb84a95402989ddf5e26b616f8d9b4">llvm::ARM::WinEH::StackAdjustment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BeginAddress {#a6f972e68049aa411ee7474e67670cc7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const support::ulittle32_t llvm::ARM::WinEH::RuntimeFunction::BeginAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Referenced by <a href="#ab3b259790094ea1a231c9615e7ce6808">RuntimeFunction</a> and <a href="#a65c56a6dfdcea7b50ac11334f93ead1a">RuntimeFunction</a>.</p>

</div>
</div>

### UnwindData {#a35c647fe34a495a3e78c65008a97df37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const support::ulittle32_t llvm::ARM::WinEH::RuntimeFunction::UnwindData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Referenced by <a href="#a7de418235442473079cb6f6aa4f43026">C</a>, <a href="#afde08212016aba3c342f4ff364c76651">ExceptionInformationRVA</a>, <a href="#a4b92d8543b07a07fc5e7f911dde42f1f">Flag</a>, <a href="#a7db64c8c0387faec9126020239d7c0f6">FunctionLength</a>, <a href="#af806966e3f89b479ce3e4225cbcdb44f">H</a>, <a href="#a2df4a184a2540941ab26d6fc674fb89a">L</a>, <a href="#a640953dc6606d0e5659ff41c5aecdd0d">PackedUnwindData</a>, <a href="#a266444653b4abae6042b825b69472f43">R</a>, <a href="#a1475ab1a5cfef4363310b4b168ac3f5a">Reg</a>, <a href="#ab9efc762fd3ae7a8e8add95799386d8f">Ret</a>, <a href="#ab3b259790094ea1a231c9615e7ce6808">RuntimeFunction</a>, <a href="#a65c56a6dfdcea7b50ac11334f93ead1a">RuntimeFunction</a> and <a href="#ae3395b83c55bd385b4ff4e2cd25f8bee">StackAdjust</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
