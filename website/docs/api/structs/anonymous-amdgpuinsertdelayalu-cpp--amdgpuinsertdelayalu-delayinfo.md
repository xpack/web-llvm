---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DelayInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cf6091a2788656eb4530ee4846a5b1">DelayInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b83b17146d0ef5d6d35faf1a202723">DelayInfo</a> (DelayType Type, unsigned Cycles)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b51fd4bd2aedd09beb93b3f5ab0d257">operator==</a> (const DelayInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3344e090d03f3a1e0d179a244f93855e">operator!=</a> (const DelayInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f970d3531548ca857ac0f9de4f251e">merge</a> (const DelayInfo &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b4674daaa8ceac1612984bbdebb50f">advance</a> (DelayType Type, unsigned Cycles)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d7299007a147890b7210adaec22a27c">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c75e701c9edc69fb919b5ba944f5cc">VALUCycles</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2720f790c61cec3b607f094725e22a9">VALUNum</a> = <a href="#a32bbbf7da4ad61a76cce07a336f8b9f7">VALU_MAX</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a83984d6fe52683f6ead034a535eb5e">TRANSCycles</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a476491112db2775de6b2003ae62341c1">TRANSNum</a> = <a href="#a990d7b1dba90a47ef530024145a016b4">TRANS_MAX</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a327a68baee6f61f592a78c93e9cdfbb6">TRANSNumVALU</a> = <a href="#a32bbbf7da4ad61a76cce07a336f8b9f7">VALU_MAX</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a870fc34a3ab61ee4003b6aa1d7536c4f">SALUCycles</a> = 0</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32bbbf7da4ad61a76cce07a336f8b9f7">VALU_MAX</a> = 5</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a990d7b1dba90a47ef530024145a016b4">TRANS_MAX</a> = 4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9f5d59a24be46cbac8a6d800992d50">SALU_CYCLES_MAX</a> = 4</td>
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


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DelayInfo() {#a07cf6091a2788656eb4530ee4846a5b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::DelayInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#ab2f970d3531548ca857ac0f9de4f251e">merge</a>, <a href="#a3344e090d03f3a1e0d179a244f93855e">operator!=</a> and <a href="#a7b51fd4bd2aedd09beb93b3f5ab0d257">operator==</a>.</p>

</div>
</div>

### DelayInfo() {#a44b83b17146d0ef5d6d35faf1a202723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::DelayInfo (<a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a61a5ea8046e1a487e39c75b2af78bef9">DelayType</a> Type, unsigned Cycles)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a61a5ea8046e1a487e39c75b2af78bef9a2bc00b11763adfa20e728ff6c62b9486">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::SALU</a>, <a href="#acf9f5d59a24be46cbac8a6d800992d50">SALU_CYCLES_MAX</a>, <a href="#a870fc34a3ab61ee4003b6aa1d7536c4f">SALUCycles</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a61a5ea8046e1a487e39c75b2af78bef9ab27dc6b647ff6c0da4e42e6b08301929">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::TRANS</a>, <a href="#a5a83984d6fe52683f6ead034a535eb5e">TRANSCycles</a>, <a href="#a476491112db2775de6b2003ae62341c1">TRANSNum</a>, <a href="#a327a68baee6f61f592a78c93e9cdfbb6">TRANSNumVALU</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a61a5ea8046e1a487e39c75b2af78bef9a2d1d8dfa7b8a93b7b3339cb9bd860a4d">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::VALU</a>, <a href="#af8c75e701c9edc69fb919b5ba944f5cc">VALUCycles</a> and <a href="#ad2720f790c61cec3b607f094725e22a9">VALUNum</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a3344e090d03f3a1e0d179a244f93855e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo">DelayInfo</a> &amp; RHS)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Reference <a href="#a07cf6091a2788656eb4530ee4846a5b1">DelayInfo</a>.</p>

</div>
</div>

### operator==() {#a7b51fd4bd2aedd09beb93b3f5ab0d257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo">DelayInfo</a> &amp; RHS)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="#a07cf6091a2788656eb4530ee4846a5b1">DelayInfo</a>, <a href="#a870fc34a3ab61ee4003b6aa1d7536c4f">SALUCycles</a>, <a href="#a5a83984d6fe52683f6ead034a535eb5e">TRANSCycles</a>, <a href="#a476491112db2775de6b2003ae62341c1">TRANSNum</a>, <a href="#a327a68baee6f61f592a78c93e9cdfbb6">TRANSNumVALU</a>, <a href="#af8c75e701c9edc69fb919b5ba944f5cc">VALUCycles</a> and <a href="#ad2720f790c61cec3b607f094725e22a9">VALUNum</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advance() {#a87b4674daaa8ceac1612984bbdebb50f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::advance (<a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a61a5ea8046e1a487e39c75b2af78bef9">DelayType</a> Type, unsigned Cycles)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="#a870fc34a3ab61ee4003b6aa1d7536c4f">SALUCycles</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a61a5ea8046e1a487e39c75b2af78bef9ab27dc6b647ff6c0da4e42e6b08301929">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::TRANS</a>, <a href="#a990d7b1dba90a47ef530024145a016b4">TRANS_MAX</a>, <a href="#a5a83984d6fe52683f6ead034a535eb5e">TRANSCycles</a>, <a href="#a476491112db2775de6b2003ae62341c1">TRANSNum</a>, <a href="#a327a68baee6f61f592a78c93e9cdfbb6">TRANSNumVALU</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a61a5ea8046e1a487e39c75b2af78bef9a2d1d8dfa7b8a93b7b3339cb9bd860a4d">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::VALU</a>, <a href="#a32bbbf7da4ad61a76cce07a336f8b9f7">VALU_MAX</a>, <a href="#af8c75e701c9edc69fb919b5ba944f5cc">VALUCycles</a> and <a href="#ad2720f790c61cec3b607f094725e22a9">VALUNum</a>.</p>

</div>
</div>

### dump() {#a5d7299007a147890b7210adaec22a27c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::dump ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a870fc34a3ab61ee4003b6aa1d7536c4f">SALUCycles</a>, <a href="#a990d7b1dba90a47ef530024145a016b4">TRANS_MAX</a>, <a href="#a5a83984d6fe52683f6ead034a535eb5e">TRANSCycles</a>, <a href="#a476491112db2775de6b2003ae62341c1">TRANSNum</a>, <a href="#a327a68baee6f61f592a78c93e9cdfbb6">TRANSNumVALU</a>, <a href="#a32bbbf7da4ad61a76cce07a336f8b9f7">VALU_MAX</a>, <a href="#af8c75e701c9edc69fb919b5ba944f5cc">VALUCycles</a> and <a href="#ad2720f790c61cec3b607f094725e22a9">VALUNum</a>.</p>

</div>
</div>

### merge() {#ab2f970d3531548ca857ac0f9de4f251e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo">DelayInfo</a> &amp; RHS)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="#a07cf6091a2788656eb4530ee4846a5b1">DelayInfo</a>, <a href="#a870fc34a3ab61ee4003b6aa1d7536c4f">SALUCycles</a>, <a href="#a5a83984d6fe52683f6ead034a535eb5e">TRANSCycles</a>, <a href="#a476491112db2775de6b2003ae62341c1">TRANSNum</a>, <a href="#a327a68baee6f61f592a78c93e9cdfbb6">TRANSNumVALU</a>, <a href="#af8c75e701c9edc69fb919b5ba944f5cc">VALUCycles</a> and <a href="#ad2720f790c61cec3b607f094725e22a9">VALUNum</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a4e91d805ee46e758435fafffa3126255">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::runOnMachineBasicBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### SALUCycles {#a870fc34a3ab61ee4003b6aa1d7536c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::SALUCycles = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a87b4674daaa8ceac1612984bbdebb50f">advance</a>, <a href="#a44b83b17146d0ef5d6d35faf1a202723">DelayInfo</a>, <a href="#a5d7299007a147890b7210adaec22a27c">dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a7cdd14f8272a87151d5bd4f1aeeeb4de">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu</a>, <a href="#ab2f970d3531548ca857ac0f9de4f251e">merge</a> and <a href="#a7b51fd4bd2aedd09beb93b3f5ab0d257">operator==</a>.</p>

</div>
</div>

### TRANSCycles {#a5a83984d6fe52683f6ead034a535eb5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::TRANSCycles = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a87b4674daaa8ceac1612984bbdebb50f">advance</a>, <a href="#a44b83b17146d0ef5d6d35faf1a202723">DelayInfo</a>, <a href="#a5d7299007a147890b7210adaec22a27c">dump</a>, <a href="#ab2f970d3531548ca857ac0f9de4f251e">merge</a> and <a href="#a7b51fd4bd2aedd09beb93b3f5ab0d257">operator==</a>.</p>

</div>
</div>

### TRANSNum {#a476491112db2775de6b2003ae62341c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::TRANSNum = <a href="#a990d7b1dba90a47ef530024145a016b4">TRANS_MAX</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a87b4674daaa8ceac1612984bbdebb50f">advance</a>, <a href="#a44b83b17146d0ef5d6d35faf1a202723">DelayInfo</a>, <a href="#a5d7299007a147890b7210adaec22a27c">dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a7cdd14f8272a87151d5bd4f1aeeeb4de">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu</a>, <a href="#ab2f970d3531548ca857ac0f9de4f251e">merge</a> and <a href="#a7b51fd4bd2aedd09beb93b3f5ab0d257">operator==</a>.</p>

</div>
</div>

### TRANSNumVALU {#a327a68baee6f61f592a78c93e9cdfbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::TRANSNumVALU = <a href="#a32bbbf7da4ad61a76cce07a336f8b9f7">VALU_MAX</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a87b4674daaa8ceac1612984bbdebb50f">advance</a>, <a href="#a44b83b17146d0ef5d6d35faf1a202723">DelayInfo</a>, <a href="#a5d7299007a147890b7210adaec22a27c">dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a7cdd14f8272a87151d5bd4f1aeeeb4de">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu</a>, <a href="#ab2f970d3531548ca857ac0f9de4f251e">merge</a> and <a href="#a7b51fd4bd2aedd09beb93b3f5ab0d257">operator==</a>.</p>

</div>
</div>

### VALUCycles {#af8c75e701c9edc69fb919b5ba944f5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::VALUCycles = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a87b4674daaa8ceac1612984bbdebb50f">advance</a>, <a href="#a44b83b17146d0ef5d6d35faf1a202723">DelayInfo</a>, <a href="#a5d7299007a147890b7210adaec22a27c">dump</a>, <a href="#ab2f970d3531548ca857ac0f9de4f251e">merge</a> and <a href="#a7b51fd4bd2aedd09beb93b3f5ab0d257">operator==</a>.</p>

</div>
</div>

### VALUNum {#ad2720f790c61cec3b607f094725e22a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::VALUNum = <a href="#a32bbbf7da4ad61a76cce07a336f8b9f7">VALU_MAX</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a87b4674daaa8ceac1612984bbdebb50f">advance</a>, <a href="#a44b83b17146d0ef5d6d35faf1a202723">DelayInfo</a>, <a href="#a5d7299007a147890b7210adaec22a27c">dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a7cdd14f8272a87151d5bd4f1aeeeb4de">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu</a>, <a href="#ab2f970d3531548ca857ac0f9de4f251e">merge</a> and <a href="#a7b51fd4bd2aedd09beb93b3f5ab0d257">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### SALU\_CYCLES\_MAX {#acf9f5d59a24be46cbac8a6d800992d50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::SALU_CYCLES_MAX = 4</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a44b83b17146d0ef5d6d35faf1a202723">DelayInfo</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a7cdd14f8272a87151d5bd4f1aeeeb4de">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu</a>.</p>

</div>
</div>

### TRANS\_MAX {#a990d7b1dba90a47ef530024145a016b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::TRANS_MAX = 4</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a87b4674daaa8ceac1612984bbdebb50f">advance</a>, <a href="#a5d7299007a147890b7210adaec22a27c">dump</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a7cdd14f8272a87151d5bd4f1aeeeb4de">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu</a>.</p>

</div>
</div>

### VALU\_MAX {#a32bbbf7da4ad61a76cce07a336f8b9f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::VALU_MAX = 5</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a87b4674daaa8ceac1612984bbdebb50f">advance</a>, <a href="#a5d7299007a147890b7210adaec22a27c">dump</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a7cdd14f8272a87151d5bd4f1aeeeb4de">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
