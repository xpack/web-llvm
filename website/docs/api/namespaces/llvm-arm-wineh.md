---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/arm/wineh
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `WinEH` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::ARM::WinEH { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction">RuntimeFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction">RuntimeFunction</a> - An entry in the table of procedure data (.pdata) <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunctionarm64">RuntimeFunctionARM64</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunctionarm64">RuntimeFunctionARM64</a> - An entry in the table of procedure data (.pdata) <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunctionarm64/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/arm/wineh/epiloguescope">EpilogueScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord">ExceptionDataRecord</a> - An entry in the table of exception data (.xdata) <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/epiloguescope/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord">ExceptionDataRecord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RuntimeFunctionFlag { <a href="#a42eec988a426045927f9b40043dad476">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ReturnType { <a href="#aeb1849a948db3f783d1598b797186c4a">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6965acfec7c5ad1fc08d817422bf3419">PrologueFolding</a> (const RuntimeFunction &amp;RF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PrologueFolding - pseudo-flag derived from Stack Adjust indicating that the prologue has stack adjustment combined into the push. <a href="#a6965acfec7c5ad1fc08d817422bf3419">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a431bf441802854857ff3a71232b0e08a">EpilogueFolding</a> (const RuntimeFunction &amp;RF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Epilogue - pseudo-flag derived from Stack Adjust indicating that the epilogue has stack adjustment combined into the pop. <a href="#a431bf441802854857ff3a71232b0e08a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbeb84a95402989ddf5e26b616f8d9b4">StackAdjustment</a> (const RuntimeFunction &amp;RF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>StackAdjustment - calculated stack adjustment in words. <a href="#abbeb84a95402989ddf5e26b616f8d9b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint16_t, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6249bf4eca2396a8bfde962a65a661bb">SavedRegisterMask</a> (const RuntimeFunction &amp;RF, bool Prologue=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SavedRegisterMask - Utility function to calculate the set of saved general purpose (r0-r15) and VFP (d0-d31) registers. <a href="#a6249bf4eca2396a8bfde962a65a661bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca4bf94569d7af05df6be821c0d19f00">HeaderWords</a> (const ExceptionDataRecord &amp;XR)</td>
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

### ReturnType {#aeb1849a948db3f783d1598b797186c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ARM::WinEH::ReturnType </td>
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
<td class="doxyEnumItemName">RT_POP<a id="aeb1849a948db3f783d1598b797186c4aa9e47e908ef3b502b5758ff7280e6a068"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT_B<a id="aeb1849a948db3f783d1598b797186c4aa2450ae9cbb990b46a005d0c7ccb69176"></a></td>
<td class="doxyEnumItemDescription">return via pop {pc} (L flag must be set)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT_BW<a id="aeb1849a948db3f783d1598b797186c4aab48ee82e3e87467c42a587cb4bba5c57"></a></td>
<td class="doxyEnumItemDescription">16-bit branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RT_NoEpilogue<a id="aeb1849a948db3f783d1598b797186c4aad5aab004418d7a265f86cefb9d4e05f1"></a></td>
<td class="doxyEnumItemDescription">32-bit branch</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>

</div>
</div>

### RuntimeFunctionFlag {#a42eec988a426045927f9b40043dad476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ARM::WinEH::RuntimeFunctionFlag </td>
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
<td class="doxyEnumItemName">RFF_Unpacked<a id="a42eec988a426045927f9b40043dad476af5a03e381d3bd0eabef74975876a2670"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RFF_Packed<a id="a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee"></a></td>
<td class="doxyEnumItemDescription">unpacked entry</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RFF_PackedFragment<a id="a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b"></a></td>
<td class="doxyEnumItemDescription">packed entry</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RFF_Reserved<a id="a42eec988a426045927f9b40043dad476abc3df5646df18b78bad2f5c11b3383da"></a></td>
<td class="doxyEnumItemDescription">packed entry representing a fragment</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### EpilogueFolding() {#a431bf441802854857ff3a71232b0e08a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::EpilogueFolding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction">RuntimeFunction</a> &amp; RF)</td>
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

<p>Epilogue - pseudo-flag derived from Stack Adjust indicating that the epilogue has stack adjustment combined into the pop.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#ae3395b83c55bd385b4ff4e2cd25f8bee">llvm::ARM::WinEH::RuntimeFunction::StackAdjust</a>.</p>


<p>Referenced by <a href="#a6249bf4eca2396a8bfde962a65a661bb">SavedRegisterMask</a>.</p>

</div>
</div>

### HeaderWords() {#aca4bf94569d7af05df6be821c0d19f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ARM::WinEH::HeaderWords (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord">ExceptionDataRecord</a> &amp; XR)</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord/#a4666cdfaaae2aabc3c84cf83a3a6838d">llvm::ARM::WinEH::ExceptionDataRecord::Data</a> and <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord/#a233df223bb2d0c05a94506b1cd866e0a">llvm::ARM::WinEH::ExceptionDataRecord::isAArch64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord/#add11c2ad7367043eecc4aa89befa7903">llvm::ARM::WinEH::ExceptionDataRecord::CodeWords</a>, <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord/#ae37170ac9b2a64d82b601622e6817737">llvm::ARM::WinEH::ExceptionDataRecord::EpilogueCount</a>, <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord/#a9e8a8cac27eee7b6b082dd6af3c42846">llvm::ARM::WinEH::ExceptionDataRecord::EpilogueScopes</a>, <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord/#ab54645df04406348e514f5cd61f236da">llvm::ARM::WinEH::ExceptionDataRecord::ExceptionHandlerParameter</a>, <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord/#a2fe82d94f803c204e29f093949dd7bbf">llvm::ARM::WinEH::ExceptionDataRecord::ExceptionHandlerRVA</a> and <a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord/#a024a668705032c00996b65aeaa0f6183">llvm::ARM::WinEH::ExceptionDataRecord::UnwindByteCode</a>.</p>

</div>
</div>

### PrologueFolding() {#a6965acfec7c5ad1fc08d817422bf3419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::PrologueFolding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction">RuntimeFunction</a> &amp; RF)</td>
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

<p>PrologueFolding - pseudo-flag derived from Stack Adjust indicating that the prologue has stack adjustment combined into the push.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#ae3395b83c55bd385b4ff4e2cd25f8bee">llvm::ARM::WinEH::RuntimeFunction::StackAdjust</a>.</p>


<p>Referenced by <a href="#a6249bf4eca2396a8bfde962a65a661bb">SavedRegisterMask</a>.</p>

</div>
</div>

### SavedRegisterMask() {#a6249bf4eca2396a8bfde962a65a661bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint16_t, uint32_t &gt; llvm::ARM::WinEH::SavedRegisterMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction">RuntimeFunction</a> &amp; RF, bool Prologue=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SavedRegisterMask - Utility function to calculate the set of saved general purpose (r0-r15) and VFP (d0-d31) registers.</p>

<p>Definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armwineh-cpp">ARMWinEH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#a7de418235442473079cb6f6aa4f43026">llvm::ARM::WinEH::RuntimeFunction::C</a>, <a href="#a431bf441802854857ff3a71232b0e08a">EpilogueFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#af806966e3f89b479ce3e4225cbcdb44f">llvm::ARM::WinEH::RuntimeFunction::H</a>, <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#a2df4a184a2540941ab26d6fc674fb89a">llvm::ARM::WinEH::RuntimeFunction::L</a>, <a href="#a6965acfec7c5ad1fc08d817422bf3419">PrologueFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#a266444653b4abae6042b825b69472f43">llvm::ARM::WinEH::RuntimeFunction::R</a>, <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#a1475ab1a5cfef4363310b4b168ac3f5a">llvm::ARM::WinEH::RuntimeFunction::Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#ab9efc762fd3ae7a8e8add95799386d8f">llvm::ARM::WinEH::RuntimeFunction::Ret</a>, <a href="#aeb1849a948db3f783d1598b797186c4aa9e47e908ef3b502b5758ff7280e6a068">RT_POP</a> and <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#ae3395b83c55bd385b4ff4e2cd25f8bee">llvm::ARM::WinEH::RuntimeFunction::StackAdjust</a>.</p>

</div>
</div>

### StackAdjustment() {#abbeb84a95402989ddf5e26b616f8d9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::ARM::WinEH::StackAdjustment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction">RuntimeFunction</a> &amp; RF)</td>
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

<p>StackAdjustment - calculated stack adjustment in words.</p>


<p>The stack adjustment should be determined via this function to account for the special handling the special encoding when the value is &gt;= 0x3f4.</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunction/#ae3395b83c55bd385b4ff4e2cd25f8bee">llvm::ARM::WinEH::RuntimeFunction::StackAdjust</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/armwineh-cpp">ARMWinEH.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
