---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `X86ISelAddressMode` Struct

<p>This corresponds to <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a>, but uses <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>'s instead of register numbers for the leaves of the matched tree. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a9292ef61b1daa6ff3b196b5143a9ff80">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682e2202c34ddb0bc4fba7020fa6159e">X86ISelAddressMode</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17e379933969571ba706b16c5feec0d">hasSymbolicDisplacement</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40f14d899a3552f6abd1794fed78868">hasBaseOrIndexReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7101e0e6830728006d41004e1edb4f59">isRIPRelative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this addressing mode is already RIP-relative. <a href="#a7101e0e6830728006d41004e1edb4f59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eee6f28a14ce4f99314d6e9958aa1e9">setBaseReg</a> (SDValue Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a> (SelectionDAG *DAG=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{X86ISelDAGToDAG.cpp}<a href="#a682e2202c34ddb0bc4fba7020fa6159e">::X86ISelAddressMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a82fb8b3432eb59d67b11f9bea61ad">BaseType</a> = <a href="#a9292ef61b1daa6ff3b196b5143a9ff80ab6333a3a249c370c332154836ec04a6e">RegBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412ec06a6062bcccc3f49a69fca1ee7d">Base_Reg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadd2e67514d819f779f558e60c4a440a">Base_FrameIndex</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac213320b61ed1826759de0453f269cc7">Scale</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20dfd7fb84e4c732a82cf8774648b720">IndexReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b72b26445d23261158043ddd2ff966">Disp</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16fa998e52eb46bfba78acf77f90da48">Segment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7e2c286868b05fbf17f8be35f5cd28d">GV</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c91750028b5180bb238de7b5659547">CP</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb5de85b55dd43c0a24eabc9df6e4a7">BlockAddr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1e6d6a0ed656333585f64c7b473881a">ES</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468ccef5321c450c6472b7a2a2a82247">MCSym</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04bf07ebe938014e01a8ee4b24c915d">JT</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a325021d3f5fdf1fb880944777dc4691a">Alignment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af84ea306565f5ab5283f2d814b0e522b">SymbolFlags</a> = X86II::MO_NO_FLAG</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76bbdddd04a63ac3282bb44213057a8f">NegateIndex</a> = false</td>
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

<p>This corresponds to <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a>, but uses <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>'s instead of register numbers for the leaves of the matched tree.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a9292ef61b1daa6ff3b196b5143a9ff80}

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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegBase<a id="a9292ef61b1daa6ff3b196b5143a9ff80ab6333a3a249c370c332154836ec04a6e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrameIndexBase<a id="a9292ef61b1daa6ff3b196b5143a9ff80adb05d288b96bb22158889b47f2240bc3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### X86ISelAddressMode() {#a682e2202c34ddb0bc4fba7020fa6159e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::X86ISelAddressMode ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#aae0b9feff51bc4ede09ff1d3859ab367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::dump (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * DAG=nullptr)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a325021d3f5fdf1fb880944777dc4691a">Alignment</a>, <a href="#aadd2e67514d819f779f558e60c4a440a">Base_FrameIndex</a>, <a href="#a412ec06a6062bcccc3f49a69fca1ee7d">Base_Reg</a>, <a href="#ad7a82fb8b3432eb59d67b11f9bea61ad">BaseType</a>, <a href="#ab3c91750028b5180bb238de7b5659547">CP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a38b72b26445d23261158043ddd2ff966">Disp</a>, <a href="#ae1e6d6a0ed656333585f64c7b473881a">ES</a>, <a href="#a9292ef61b1daa6ff3b196b5143a9ff80adb05d288b96bb22158889b47f2240bc3">FrameIndexBase</a>, <a href="#ab7e2c286868b05fbf17f8be35f5cd28d">GV</a>, <a href="#a20dfd7fb84e4c732a82cf8774648b720">IndexReg</a>, <a href="#af04bf07ebe938014e01a8ee4b24c915d">JT</a>, <a href="#a468ccef5321c450c6472b7a2a2a82247">MCSym</a>, <a href="#a76bbdddd04a63ac3282bb44213057a8f">NegateIndex</a> and <a href="#ac213320b61ed1826759de0453f269cc7">Scale</a>.</p>

</div>
</div>

### hasBaseOrIndexReg() {#ad40f14d899a3552f6abd1794fed78868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::hasBaseOrIndexReg ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a412ec06a6062bcccc3f49a69fca1ee7d">Base_Reg</a>, <a href="#ad7a82fb8b3432eb59d67b11f9bea61ad">BaseType</a>, <a href="#a9292ef61b1daa6ff3b196b5143a9ff80adb05d288b96bb22158889b47f2240bc3">FrameIndexBase</a> and <a href="#a20dfd7fb84e4c732a82cf8774648b720">IndexReg</a>.</p>

</div>
</div>

### hasSymbolicDisplacement() {#ad17e379933969571ba706b16c5feec0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::hasSymbolicDisplacement ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a4fb5de85b55dd43c0a24eabc9df6e4a7">BlockAddr</a>, <a href="#ab3c91750028b5180bb238de7b5659547">CP</a>, <a href="#ae1e6d6a0ed656333585f64c7b473881a">ES</a>, <a href="#ab7e2c286868b05fbf17f8be35f5cd28d">GV</a>, <a href="#af04bf07ebe938014e01a8ee4b24c915d">JT</a> and <a href="#a468ccef5321c450c6472b7a2a2a82247">MCSym</a>.</p>

</div>
</div>

### isRIPRelative() {#a7101e0e6830728006d41004e1edb4f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::isRIPRelative ()</td>
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

<p>Return true if this addressing mode is already RIP-relative.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a412ec06a6062bcccc3f49a69fca1ee7d">Base_Reg</a>, <a href="#ad7a82fb8b3432eb59d67b11f9bea61ad">BaseType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a9292ef61b1daa6ff3b196b5143a9ff80ab6333a3a249c370c332154836ec04a6e">RegBase</a>.</p>

</div>
</div>

### setBaseReg() {#a1eee6f28a14ce4f99314d6e9958aa1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::setBaseReg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Reg)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a412ec06a6062bcccc3f49a69fca1ee7d">Base_Reg</a>, <a href="#ad7a82fb8b3432eb59d67b11f9bea61ad">BaseType</a> and <a href="#a9292ef61b1daa6ff3b196b5143a9ff80ab6333a3a249c370c332154836ec04a6e">RegBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Alignment {#a325021d3f5fdf1fb880944777dc4691a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::Alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a>.</p>

</div>
</div>

### Base\_FrameIndex {#aadd2e67514d819f779f558e60c4a440a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::Base_FrameIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a>.</p>

</div>
</div>

### Base\_Reg {#a412ec06a6062bcccc3f49a69fca1ee7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::Base_Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a>, <a href="#ad40f14d899a3552f6abd1794fed78868">hasBaseOrIndexReg</a>, <a href="#a7101e0e6830728006d41004e1edb4f59">isRIPRelative</a> and <a href="#a1eee6f28a14ce4f99314d6e9958aa1e9">setBaseReg</a>.</p>

</div>
</div>

### BaseType {#ad7a82fb8b3432eb59d67b11f9bea61ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::BaseType = <a href="#a9292ef61b1daa6ff3b196b5143a9ff80ab6333a3a249c370c332154836ec04a6e">RegBase</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a>, <a href="#ad40f14d899a3552f6abd1794fed78868">hasBaseOrIndexReg</a>, <a href="#a7101e0e6830728006d41004e1edb4f59">isRIPRelative</a> and <a href="#a1eee6f28a14ce4f99314d6e9958aa1e9">setBaseReg</a>.</p>

</div>
</div>

### BlockAddr {#a4fb5de85b55dd43c0a24eabc9df6e4a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockAddress* anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::BlockAddr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ad17e379933969571ba706b16c5feec0d">hasSymbolicDisplacement</a>.</p>

</div>
</div>

### CP {#ab3c91750028b5180bb238de7b5659547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Constant* anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::CP = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a> and <a href="#ad17e379933969571ba706b16c5feec0d">hasSymbolicDisplacement</a>.</p>

</div>
</div>

### Disp {#a38b72b26445d23261158043ddd2ff966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::Disp = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a>.</p>

</div>
</div>

### ES {#ae1e6d6a0ed656333585f64c7b473881a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::ES = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a> and <a href="#ad17e379933969571ba706b16c5feec0d">hasSymbolicDisplacement</a>.</p>

</div>
</div>

### GV {#ab7e2c286868b05fbf17f8be35f5cd28d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue* anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::GV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a> and <a href="#ad17e379933969571ba706b16c5feec0d">hasSymbolicDisplacement</a>.</p>

</div>
</div>

### IndexReg {#a20dfd7fb84e4c732a82cf8774648b720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::IndexReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a> and <a href="#ad40f14d899a3552f6abd1794fed78868">hasBaseOrIndexReg</a>.</p>

</div>
</div>

### JT {#af04bf07ebe938014e01a8ee4b24c915d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::JT = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a> and <a href="#ad17e379933969571ba706b16c5feec0d">hasSymbolicDisplacement</a>.</p>

</div>
</div>

### MCSym {#a468ccef5321c450c6472b7a2a2a82247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::MCSym = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a> and <a href="#ad17e379933969571ba706b16c5feec0d">hasSymbolicDisplacement</a>.</p>

</div>
</div>

### NegateIndex {#a76bbdddd04a63ac3282bb44213057a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::NegateIndex = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a>.</p>

</div>
</div>

### Scale {#ac213320b61ed1826759de0453f269cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::Scale = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#aae0b9feff51bc4ede09ff1d3859ab367">dump</a>.</p>

</div>
</div>

### Segment {#a16fa998e52eb46bfba78acf77f90da48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::Segment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SymbolFlags {#af84ea306565f5ab5283f2d814b0e522b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char anonymous{X86ISelDAGToDAG.cpp}::X86ISelAddressMode::SymbolFlags = X86II::MO_NO_FLAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
