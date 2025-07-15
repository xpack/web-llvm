---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-riscvinsertvsetvli-cpp-/demandedfields
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DemandedFields` Struct Reference

<p>Which subfields of VL or VTYPE have values we need to preserve? <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint8_t { <a href="#a481cc16a7c81ea3d327a8f5d756e6205">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint8_t { <a href="#aae081abcd45e8904d475f26707cca435">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41487a7a460359f81eaee78768528571">usedVTYPE</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9053528e68e79dd1cb4c924188af2b86">usedVL</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ff20644f9195bf26795f92c9b8ff8d">demandVTYPE</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbedca58a2d373cf3f1babbd0f3bcbcf">demandVL</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ccff12698a97b99ead60ee24a00584">doUnion</a> (const DemandedFields &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423c378f7cfc3637d0a97b19ef757fac">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support for debugging, callable in GDB: V-&gt;<a href="#a423c378f7cfc3637d0a97b19ef757fac">dump()</a> <a href="#a423c378f7cfc3637d0a97b19ef757fac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73d2591b970928ee9f9219efeaedb28">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement operator&lt;&lt;. <a href="#ad73d2591b970928ee9f9219efeaedb28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8abb14768456a716a6358554abf677f">VLAny</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9336071446cc03509eda50674d3708">VLZeroness</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{RISCVInsertVSETVLI.cpp}::DemandedFields</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a3e360a57185517c8faad15dc37458">SEW</a> = <a href="#a481cc16a7c81ea3d327a8f5d756e6205a34af2b7a76e6bc1c4f18c02ee9ab920c">SEWNone</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{RISCVInsertVSETVLI.cpp}::DemandedFields</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab81fbf459aa1e84bbc578894ff676028">LMUL</a> = <a href="#aae081abcd45e8904d475f26707cca435a8fc232344f928f06a1c460534ea0d091">LMULNone</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6a7b78f07c41b474dc380ad02d91e95">SEWLMULRatio</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c35482a24edb537ee6d4ecf44f68aac">TailPolicy</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2da60d85d2479e3140e20160117b5e">MaskPolicy</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df4b4c2e1f84821ae17c53bb04ec89f">VILL</a> = false</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-riscvinsertvsetvli-cpp-/demandedfields">DemandedFields</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b25eee520411a343380b9f847efea96">all</a> ()</td>
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

<p>Which subfields of VL or VTYPE have values we need to preserve?</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a481cc16a7c81ea3d327a8f5d756e6205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint8_t</td>
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
<td class="doxyEnumItemName">SEWEqual<a id="a481cc16a7c81ea3d327a8f5d756e6205a0a83530f3f8d65aa0584eec9540af97c"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEWGreaterThanOrEqualAndLessThan64<a id="a481cc16a7c81ea3d327a8f5d756e6205ab95be7cc49d3cde7f1bef471e5741007"></a></td>
<td class="doxyEnumItemDescription">
 (=
        2)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEWGreaterThanOrEqual<a id="a481cc16a7c81ea3d327a8f5d756e6205ad1f534f6337bd8e12f6415b012093745"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEWNone<a id="a481cc16a7c81ea3d327a8f5d756e6205a34af2b7a76e6bc1c4f18c02ee9ab920c"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### anonymous enum  {#aae081abcd45e8904d475f26707cca435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint8_t</td>
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
<td class="doxyEnumItemName">LMULEqual<a id="aae081abcd45e8904d475f26707cca435af822705c15f9a4e811d83f0d444b3989"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LMULLessThanOrEqualToM1<a id="aae081abcd45e8904d475f26707cca435a7fb6fdc4d1547b1360a1e11607b3620d"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LMULNone<a id="aae081abcd45e8904d475f26707cca435a8fc232344f928f06a1c460534ea0d091"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### demandVL() {#afbedca58a2d373cf3f1babbd0f3bcbcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::demandVL ()</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="#ae8abb14768456a716a6358554abf677f">VLAny</a> and <a href="#adf9336071446cc03509eda50674d3708">VLZeroness</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>.</p>

</div>
</div>

### demandVTYPE() {#a70ff20644f9195bf26795f92c9b8ff8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::demandVTYPE ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="#ab81fbf459aa1e84bbc578894ff676028">LMUL</a>, <a href="#aae081abcd45e8904d475f26707cca435af822705c15f9a4e811d83f0d444b3989">LMULEqual</a>, <a href="#aac2da60d85d2479e3140e20160117b5e">MaskPolicy</a>, <a href="#a04a3e360a57185517c8faad15dc37458">SEW</a>, <a href="#a481cc16a7c81ea3d327a8f5d756e6205a0a83530f3f8d65aa0584eec9540af97c">SEWEqual</a>, <a href="#ab6a7b78f07c41b474dc380ad02d91e95">SEWLMULRatio</a>, <a href="#a9c35482a24edb537ee6d4ecf44f68aac">TailPolicy</a> and <a href="#a0df4b4c2e1f84821ae17c53bb04ec89f">VILL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>.</p>

</div>
</div>

### doUnion() {#a78ccff12698a97b99ead60ee24a00584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::doUnion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvinsertvsetvli-cpp-/demandedfields">DemandedFields</a> &amp; B)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ab81fbf459aa1e84bbc578894ff676028">LMUL</a>, <a href="#aac2da60d85d2479e3140e20160117b5e">MaskPolicy</a>, <a href="#a04a3e360a57185517c8faad15dc37458">SEW</a>, <a href="#ab6a7b78f07c41b474dc380ad02d91e95">SEWLMULRatio</a>, <a href="#a9c35482a24edb537ee6d4ecf44f68aac">TailPolicy</a>, <a href="#a0df4b4c2e1f84821ae17c53bb04ec89f">VILL</a>, <a href="#ae8abb14768456a716a6358554abf677f">VLAny</a> and <a href="#adf9336071446cc03509eda50674d3708">VLZeroness</a>.</p>

</div>
</div>

### dump() {#a423c378f7cfc3637d0a97b19ef757fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::dump ()</td>
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

<p>Support for debugging, callable in GDB: V-&gt;<a href="#a423c378f7cfc3637d0a97b19ef757fac">dump()</a></p>

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### print() {#ad73d2591b970928ee9f9219efeaedb28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Implement operator&lt;&lt;.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="#ab81fbf459aa1e84bbc578894ff676028">LMUL</a>, <a href="#aae081abcd45e8904d475f26707cca435af822705c15f9a4e811d83f0d444b3989">LMULEqual</a>, <a href="#aae081abcd45e8904d475f26707cca435a7fb6fdc4d1547b1360a1e11607b3620d">LMULLessThanOrEqualToM1</a>, <a href="#aae081abcd45e8904d475f26707cca435a8fc232344f928f06a1c460534ea0d091">LMULNone</a>, <a href="#aac2da60d85d2479e3140e20160117b5e">MaskPolicy</a>, <a href="#a04a3e360a57185517c8faad15dc37458">SEW</a>, <a href="#a481cc16a7c81ea3d327a8f5d756e6205a0a83530f3f8d65aa0584eec9540af97c">SEWEqual</a>, <a href="#a481cc16a7c81ea3d327a8f5d756e6205ad1f534f6337bd8e12f6415b012093745">SEWGreaterThanOrEqual</a>, <a href="#a481cc16a7c81ea3d327a8f5d756e6205ab95be7cc49d3cde7f1bef471e5741007">SEWGreaterThanOrEqualAndLessThan64</a>, <a href="#ab6a7b78f07c41b474dc380ad02d91e95">SEWLMULRatio</a>, <a href="#a481cc16a7c81ea3d327a8f5d756e6205a34af2b7a76e6bc1c4f18c02ee9ab920c">SEWNone</a>, <a href="#a9c35482a24edb537ee6d4ecf44f68aac">TailPolicy</a>, <a href="#a0df4b4c2e1f84821ae17c53bb04ec89f">VILL</a>, <a href="#ae8abb14768456a716a6358554abf677f">VLAny</a> and <a href="#adf9336071446cc03509eda50674d3708">VLZeroness</a>.</p>

</div>
</div>

### usedVL() {#a9053528e68e79dd1cb4c924188af2b86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::usedVL ()</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="#ae8abb14768456a716a6358554abf677f">VLAny</a> and <a href="#adf9336071446cc03509eda50674d3708">VLZeroness</a>.</p>

</div>
</div>

### usedVTYPE() {#a41487a7a460359f81eaee78768528571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::usedVTYPE ()</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="#ab81fbf459aa1e84bbc578894ff676028">LMUL</a>, <a href="#aac2da60d85d2479e3140e20160117b5e">MaskPolicy</a>, <a href="#a04a3e360a57185517c8faad15dc37458">SEW</a>, <a href="#ab6a7b78f07c41b474dc380ad02d91e95">SEWLMULRatio</a>, <a href="#a9c35482a24edb537ee6d4ecf44f68aac">TailPolicy</a> and <a href="#a0df4b4c2e1f84821ae17c53bb04ec89f">VILL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LMUL {#ab81fbf459aa1e84bbc578894ff676028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::LMUL = <a href="#aae081abcd45e8904d475f26707cca435a8fc232344f928f06a1c460534ea0d091">LMULNone</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a70ff20644f9195bf26795f92c9b8ff8d">demandVTYPE</a>, <a href="#a78ccff12698a97b99ead60ee24a00584">doUnion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>, <a href="#ad73d2591b970928ee9f9219efeaedb28">print</a> and <a href="#a41487a7a460359f81eaee78768528571">usedVTYPE</a>.</p>

</div>
</div>

### MaskPolicy {#aac2da60d85d2479e3140e20160117b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::MaskPolicy = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a70ff20644f9195bf26795f92c9b8ff8d">demandVTYPE</a>, <a href="#a78ccff12698a97b99ead60ee24a00584">doUnion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>, <a href="#ad73d2591b970928ee9f9219efeaedb28">print</a> and <a href="#a41487a7a460359f81eaee78768528571">usedVTYPE</a>.</p>

</div>
</div>

### SEW {#a04a3e360a57185517c8faad15dc37458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::SEW = <a href="#a481cc16a7c81ea3d327a8f5d756e6205a34af2b7a76e6bc1c4f18c02ee9ab920c">SEWNone</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a70ff20644f9195bf26795f92c9b8ff8d">demandVTYPE</a>, <a href="#a78ccff12698a97b99ead60ee24a00584">doUnion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>, <a href="#ad73d2591b970928ee9f9219efeaedb28">print</a> and <a href="#a41487a7a460359f81eaee78768528571">usedVTYPE</a>.</p>

</div>
</div>

### SEWLMULRatio {#ab6a7b78f07c41b474dc380ad02d91e95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::SEWLMULRatio = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a70ff20644f9195bf26795f92c9b8ff8d">demandVTYPE</a>, <a href="#a78ccff12698a97b99ead60ee24a00584">doUnion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>, <a href="#ad73d2591b970928ee9f9219efeaedb28">print</a> and <a href="#a41487a7a460359f81eaee78768528571">usedVTYPE</a>.</p>

</div>
</div>

### TailPolicy {#a9c35482a24edb537ee6d4ecf44f68aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::TailPolicy = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a70ff20644f9195bf26795f92c9b8ff8d">demandVTYPE</a>, <a href="#a78ccff12698a97b99ead60ee24a00584">doUnion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>, <a href="#ad73d2591b970928ee9f9219efeaedb28">print</a> and <a href="#a41487a7a460359f81eaee78768528571">usedVTYPE</a>.</p>

</div>
</div>

### VILL {#a0df4b4c2e1f84821ae17c53bb04ec89f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::VILL = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a70ff20644f9195bf26795f92c9b8ff8d">demandVTYPE</a>, <a href="#a78ccff12698a97b99ead60ee24a00584">doUnion</a>, <a href="#ad73d2591b970928ee9f9219efeaedb28">print</a> and <a href="#a41487a7a460359f81eaee78768528571">usedVTYPE</a>.</p>

</div>
</div>

### VLAny {#ae8abb14768456a716a6358554abf677f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::VLAny = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#afbedca58a2d373cf3f1babbd0f3bcbcf">demandVL</a>, <a href="#a78ccff12698a97b99ead60ee24a00584">doUnion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>, <a href="#ad73d2591b970928ee9f9219efeaedb28">print</a> and <a href="#a9053528e68e79dd1cb4c924188af2b86">usedVL</a>.</p>

</div>
</div>

### VLZeroness {#adf9336071446cc03509eda50674d3708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::VLZeroness = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#afbedca58a2d373cf3f1babbd0f3bcbcf">demandVL</a>, <a href="#a78ccff12698a97b99ead60ee24a00584">doUnion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>, <a href="#ad73d2591b970928ee9f9219efeaedb28">print</a> and <a href="#a9053528e68e79dd1cb4c924188af2b86">usedVL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### all() {#a5b25eee520411a343380b9f847efea96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DemandedFields anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::all ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
