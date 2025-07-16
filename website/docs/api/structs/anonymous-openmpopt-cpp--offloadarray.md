---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-openmpopt-cpp-/offloadarray
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OffloadArray` Struct Reference

<p>Used to map the values physically (in the IR) stored in an offload array, to a vector in memory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{OpenMPOpt.cpp}::OffloadArray { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6543f9970e6871f17563fa524e1cf429">OffloadArray</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad44a6bd915587c4aeb48e71abf9c3b">initialize</a> (AllocaInst &amp;Array, Instruction &amp;Before)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes the <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/offloadarray">OffloadArray</a> with the values stored in <span class="doxyComputerOutput">Array</span> before instruction <span class="doxyComputerOutput">Before</span> is reached. <a href="#aaad44a6bd915587c4aeb48e71abf9c3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd90ebabb4f13fc7c699ed9be36854e">getValues</a> (AllocaInst &amp;Array, Instruction &amp;Before)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traverses the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> where <span class="doxyComputerOutput">Array</span> is, collecting the stores made to <span class="doxyComputerOutput">Array</span>, leaving StoredValues with the values stored before the instruction <span class="doxyComputerOutput">Before</span> is reached. <a href="#abcd90ebabb4f13fc7c699ed9be36854e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa664ac237b971e3539f82620abff8c69">isFilled</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if all values in StoredValues and LastAccesses are not nullptrs. <a href="#aa664ac237b971e3539f82620abff8c69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e338d161ac468cb651181f7b1d9de5">Array</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Physical array (in the IR). <a href="#a83e338d161ac468cb651181f7b1d9de5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba8427b95e7b7131f9f29496b57f62d">StoredValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapped values. <a href="#a5ba8427b95e7b7131f9f29496b57f62d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74602f109e29a69df2a3b3e0703af0ab">LastAccesses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Last stores made in the offload array. <a href="#a74602f109e29a69df2a3b3e0703af0ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d3a8ab468d984c21c102488a3e665e">DeviceIDArgNum</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07a5e257da9528b91e11fa2a165c3f1">BasePtrsArgNum</a> = 3</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2a0d7c49b57df3c38db2ab6909ccfd">PtrsArgNum</a> = 4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58a7b27f98146692b1ee1e481d359910">SizesArgNum</a> = 5</td>
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

<p>Used to map the values physically (in the IR) stored in an offload array, to a vector in memory.</p>

<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OffloadArray() {#a6543f9970e6871f17563fa524e1cf429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{OpenMPOpt.cpp}::OffloadArray::OffloadArray ()</td>
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



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### initialize() {#aaad44a6bd915587c4aeb48e71abf9c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::OffloadArray::initialize (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; Array, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Before)</td>
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

<p>Initializes the <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/offloadarray">OffloadArray</a> with the values stored in <span class="doxyComputerOutput">Array</span> before instruction <span class="doxyComputerOutput">Before</span> is reached.</p>


<p>Returns false if the initialization fails. This MUST be used immediately after the construction of the object.</p>


<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="#a83e338d161ac468cb651181f7b1d9de5">Array</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getValues() {#abcd90ebabb4f13fc7c699ed9be36854e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::OffloadArray::getValues (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; Array, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Before)</td>
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

<p>Traverses the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> where <span class="doxyComputerOutput">Array</span> is, collecting the stores made to <span class="doxyComputerOutput">Array</span>, leaving StoredValues with the values stored before the instruction <span class="doxyComputerOutput">Before</span> is reached.</p>

<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### isFilled() {#aa664ac237b971e3539f82620abff8c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::OffloadArray::isFilled ()</td>
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

<p>Returns true if all values in StoredValues and LastAccesses are not nullptrs.</p>

<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Array {#a83e338d161ac468cb651181f7b1d9de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{OpenMPOpt.cpp}::OffloadArray::Array = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Physical array (in the IR).</p>

<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#aaad44a6bd915587c4aeb48e71abf9c3b">initialize</a>.</p>

</div>
</div>

### LastAccesses {#a74602f109e29a69df2a3b3e0703af0ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StoreInst *, 8&gt; anonymous{OpenMPOpt.cpp}::OffloadArray::LastAccesses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Last stores made in the offload array.</p>

<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### StoredValues {#a5ba8427b95e7b7131f9f29496b57f62d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Value *, 8&gt; anonymous{OpenMPOpt.cpp}::OffloadArray::StoredValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapped values.</p>

<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### BasePtrsArgNum {#ad07a5e257da9528b91e11fa2a165c3f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{OpenMPOpt.cpp}::OffloadArray::BasePtrsArgNum = 3</td>
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



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### DeviceIDArgNum {#a82d3a8ab468d984c21c102488a3e665e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{OpenMPOpt.cpp}::OffloadArray::DeviceIDArgNum = 1</td>
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



<p>Definition at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### PtrsArgNum {#a8a2a0d7c49b57df3c38db2ab6909ccfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{OpenMPOpt.cpp}::OffloadArray::PtrsArgNum = 4</td>
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



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### SizesArgNum {#a58a7b27f98146692b1ee1e481d359910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{OpenMPOpt.cpp}::OffloadArray::SizesArgNum = 5</td>
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



<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
