---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VectorInfo` Struct Reference

<p><a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> stores abstract the following information for each vector element: <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bbec17d6b2661cf505e9b0b710f5d67">VectorInfo</a> (FixedVectorType *VTy)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb2b35e8ead18dc515e982896010b98">VectorInfo</a> (const VectorInfo &amp;c)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d2c8622f92d8a21bd572d39398581d3">~VectorInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b78279f22a019d8c9bc223b6e37cd9">operator=</a> (const VectorInfo &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ea3a7eb7c5244097ef8835b62b7a5c">getDimension</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204b8dfd1121295f9a57bb5aa0723016">isInterleaved</a> (unsigned Factor, const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> can be part of an interleaved load with the specified factor. <a href="#a204b8dfd1121295f9a57bb5aa0723016">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac17c1d0602cd8a80dbcfa26073b1c3">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ef94cfe93d7be9ddc4049c74be0ed66">BB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Basic-block the load instructions are within. <a href="#a5ef94cfe93d7be9ddc4049c74be0ed66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da1e105224e606057c1e65a92de50e7">PV</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer value of all participation load instructions. <a href="#a5da1e105224e606057c1e65a92de50e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08461f1158e4b7409b6373c7c33ef56d">LIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Participating load instructions. <a href="#a08461f1158e4b7409b6373c7c33ef56d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167f2d9af02ead3486c652746f93a329">Is</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Participating instructions. <a href="#a167f2d9af02ead3486c652746f93a329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094276da323ffdce4edaa2897e65462a">SVI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Final shuffle-vector instruction. <a href="#a094276da323ffdce4edaa2897e65462a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/elementinfo">ElementInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b54b274a1d7b72dce47d87a4c81528">EI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information of the offset for each vector element. <a href="#a98b54b274a1d7b72dce47d87a4c81528">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0a8b76b6050362a865f2eb45feb6e4">VTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#a6f0a8b76b6050362a865f2eb45feb6e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae703f01e30a1aef1bcd4b1c234b5ef32">compute</a> (Value *V, VectorInfo &amp;Result, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively computes the vector information stored in V. <a href="#ae703f01e30a1aef1bcd4b1c234b5ef32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30656b818497e335ff16282be4fe6300">computeFromBCI</a> (BitCastInst *BCI, VectorInfo &amp;Result, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a> specialization to compute the vector information. <a href="#a30656b818497e335ff16282be4fe6300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512a96bc40ecd933dab9e74af6be51b0">computeFromSVI</a> (ShuffleVectorInst *SVI, VectorInfo &amp;Result, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> specialization to compute vector information. <a href="#a512a96bc40ecd933dab9e74af6be51b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb38e302133457f235fdcc6723abeac">computeFromLI</a> (LoadInst *LI, VectorInfo &amp;Result, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> specialization to compute vector information. <a href="#a0cb38e302133457f235fdcc6723abeac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2088d6a1f9882689fbea2dff8f09494c">computePolynomialBinOp</a> (BinaryOperator &amp;BO, Polynomial &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively compute polynomial of a value. <a href="#a2088d6a1f9882689fbea2dff8f09494c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab719192e40abe9e51c199e82c8019e1c">computePolynomial</a> (Value &amp;V, Polynomial &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively compute polynomial of a value. <a href="#ab719192e40abe9e51c199e82c8019e1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a01001593bf75700ee024b15bdf413">computePolynomialFromPointer</a> (Value &amp;Ptr, Polynomial &amp;Result, Value *&amp;BasePtr, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> representation of a Pointer type. <a href="#a38a01001593bf75700ee024b15bdf413">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> stores abstract the following information for each vector element:</p>


<p>1) The memory address loaded into the element as <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> 2) a set of load instruction necessary to construct the vector, 3) a set of all other instructions that are necessary to create the vector and 4) a pointer value that can be used as relative base for all elements.</p>


<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VectorInfo() {#a2bbec17d6b2661cf505e9b0b710f5d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::VectorInfo (<a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VTy)</td>
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



<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#a98b54b274a1d7b72dce47d87a4c81528">EI</a> and <a href="#a6f0a8b76b6050362a865f2eb45feb6e4">VTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### VectorInfo() {#a9bb2b35e8ead18dc515e982896010b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::VectorInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &amp; c)</td>
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



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VectorInfo() {#a6d2c8622f92d8a21bd572d39398581d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::~VectorInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Reference <a href="#a98b54b274a1d7b72dce47d87a4c81528">EI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#af3b78279f22a019d8c9bc223b6e37cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorInfo &amp; anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDimension() {#a80ea3a7eb7c5244097ef8835b62b7a5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::getDimension ()</td>
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



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Reference <a href="#a6f0a8b76b6050362a865f2eb45feb6e4">VTy</a>.</p>


<p>Referenced by <a href="#a204b8dfd1121295f9a57bb5aa0723016">isInterleaved</a> and <a href="#a2ac17c1d0602cd8a80dbcfa26073b1c3">print</a>.</p>

</div>
</div>

### isInterleaved() {#a204b8dfd1121295f9a57bb5aa0723016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::isInterleaved (unsigned Factor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Test if the <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> can be part of an interleaved load with the specified factor.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Factor</td>
<td class="doxyParamItemDescription"><p>of the interleave</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Targets Datalayout</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this is possible and false if not</p></dd>
</dl>


<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a98b54b274a1d7b72dce47d87a4c81528">EI</a>, <a href="#a80ea3a7eb7c5244097ef8835b62b7a5c">getDimension</a>, <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial/#aab36480a7c88876050105835be050f98">anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::isProvenEqualTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a6f0a8b76b6050362a865f2eb45feb6e4">VTy</a>.</p>

</div>
</div>

### print() {#a2ac17c1d0602cd8a80dbcfa26073b1c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#a98b54b274a1d7b72dce47d87a4c81528">EI</a>, <a href="#a80ea3a7eb7c5244097ef8835b62b7a5c">getDimension</a> and <a href="#a5da1e105224e606057c1e65a92de50e7">PV</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BB {#a5ef94cfe93d7be9ddc4049c74be0ed66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::BB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Basic-block the load instructions are within.</p>

<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#a30656b818497e335ff16282be4fe6300">computeFromBCI</a>.</p>

</div>
</div>

### EI {#a98b54b274a1d7b72dce47d87a4c81528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementInfo* anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::EI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Information of the offset for each vector element.</p>

<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#a30656b818497e335ff16282be4fe6300">computeFromBCI</a>, <a href="#a204b8dfd1121295f9a57bb5aa0723016">isInterleaved</a>, <a href="#a2ac17c1d0602cd8a80dbcfa26073b1c3">print</a>, <a href="#a2bbec17d6b2661cf505e9b0b710f5d67">VectorInfo</a> and <a href="#a6d2c8622f92d8a21bd572d39398581d3">~VectorInfo</a>.</p>

</div>
</div>

### Is {#a167f2d9af02ead3486c652746f93a329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;Instruction *&gt; anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::Is</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Participating instructions.</p>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#a30656b818497e335ff16282be4fe6300">computeFromBCI</a>.</p>

</div>
</div>

### LIs {#a08461f1158e4b7409b6373c7c33ef56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;LoadInst *&gt; anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::LIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Participating load instructions.</p>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#a30656b818497e335ff16282be4fe6300">computeFromBCI</a>.</p>

</div>
</div>

### PV {#a5da1e105224e606057c1e65a92de50e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::PV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer value of all participation load instructions.</p>

<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#a30656b818497e335ff16282be4fe6300">computeFromBCI</a> and <a href="#a2ac17c1d0602cd8a80dbcfa26073b1c3">print</a>.</p>

</div>
</div>

### SVI {#a094276da323ffdce4edaa2897e65462a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShuffleVectorInst* anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::SVI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Final shuffle-vector instruction.</p>

<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#ae703f01e30a1aef1bcd4b1c234b5ef32">compute</a> and <a href="#a512a96bc40ecd933dab9e74af6be51b0">computeFromSVI</a>.</p>

</div>
</div>

### VTy {#a6f0a8b76b6050362a865f2eb45feb6e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType* const anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::VTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>

<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#a30656b818497e335ff16282be4fe6300">computeFromBCI</a>, <a href="#a80ea3a7eb7c5244097ef8835b62b7a5c">getDimension</a>, <a href="#a204b8dfd1121295f9a57bb5aa0723016">isInterleaved</a> and <a href="#a2bbec17d6b2661cf505e9b0b710f5d67">VectorInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### compute() {#ae703f01e30a1aef1bcd4b1c234b5ef32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::compute (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Recursively computes the vector information stored in V.</p>


<p>This function delegates the work to specialized implementations</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to operate on</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>Result of the computation</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if no sensible information can be gathered.</p></dd>
</dl>


<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#a30656b818497e335ff16282be4fe6300">computeFromBCI</a>, <a href="#a0cb38e302133457f235fdcc6723abeac">computeFromLI</a>, <a href="#a512a96bc40ecd933dab9e74af6be51b0">computeFromSVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a094276da323ffdce4edaa2897e65462a">SVI</a>.</p>


<p>Referenced by <a href="#a30656b818497e335ff16282be4fe6300">computeFromBCI</a> and <a href="#a512a96bc40ecd933dab9e74af6be51b0">computeFromSVI</a>.</p>

</div>
</div>

### computeFromBCI() {#a30656b818497e335ff16282be4fe6300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromBCI (<a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a> * BCI, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a> specialization to compute the vector information.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BCI</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a> to operate on</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>Result of the computation</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if no sensible information can be gathered.</p></dd>
</dl>


<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#a5ef94cfe93d7be9ddc4049c74be0ed66">BB</a>, <a href="#ae703f01e30a1aef1bcd4b1c234b5ef32">compute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a98b54b274a1d7b72dce47d87a4c81528">EI</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a167f2d9af02ead3486c652746f93a329">Is</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/elementinfo/#a58257478afd480ed1b208a77109e3af0">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::ElementInfo::LI</a>, <a href="#a08461f1158e4b7409b6373c7c33ef56d">LIs</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/elementinfo/#a39efe97c9d8eb5beb817f438feba50ca">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::ElementInfo::Ofs</a>, <a href="#a5da1e105224e606057c1e65a92de50e7">PV</a> and <a href="#a6f0a8b76b6050362a865f2eb45feb6e4">VTy</a>.</p>


<p>Referenced by <a href="#ae703f01e30a1aef1bcd4b1c234b5ef32">compute</a>.</p>

</div>
</div>

### computeFromLI() {#a0cb38e302133457f235fdcc6723abeac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromLI (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> specialization to compute vector information.</p>


<p>This function also acts as abort condition to the recursion.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LI</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> to operate on</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>Result of the computation</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if no sensible information can be gathered.</p></dd>
</dl>


<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#a38a01001593bf75700ee024b15bdf413">computePolynomialFromPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a57efb022f2ee2e19e4cdf582f4d27f2d">llvm::Instruction::isAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2eccc19f9061eeb7ad1e30e21f76034d">llvm::LoadInst::isVolatile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#ae703f01e30a1aef1bcd4b1c234b5ef32">compute</a>.</p>

</div>
</div>

### computeFromSVI() {#a512a96bc40ecd933dab9e74af6be51b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromSVI (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * SVI, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> specialization to compute vector information.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SVI</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> to operate on</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>Result of the computation</p></td>
</tr>
</table>
</dd>
</dl>

<p>Compute the left and the right side vector information and merge them by applying the shuffle operation. This function also ensures that the left and right side have compatible loads. This means that all loads are with in the same basic block and are based on the same pointer.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if no sensible information can be gathered.</p></dd>
</dl>


<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ae703f01e30a1aef1bcd4b1c234b5ef32">compute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a094276da323ffdce4edaa2897e65462a">SVI</a>.</p>


<p>Referenced by <a href="#ae703f01e30a1aef1bcd4b1c234b5ef32">compute</a> and <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/interleavedloadcombineimpl/#a67598b6a57000bd24f98853c3c692ce8">anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombineImpl::run</a>.</p>

</div>
</div>

### computePolynomial() {#ab719192e40abe9e51c199e82c8019e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomial (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp; Result)</td>
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

<p>Recursively compute polynomial of a value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p>input value</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>result polynomial</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#a2088d6a1f9882689fbea2dff8f09494c">computePolynomialBinOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a2088d6a1f9882689fbea2dff8f09494c">computePolynomialBinOp</a> and <a href="#a38a01001593bf75700ee024b15bdf413">computePolynomialFromPointer</a>.</p>

</div>
</div>

### computePolynomialBinOp() {#a2088d6a1f9882689fbea2dff8f09494c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialBinOp (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; BO, <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp; Result)</td>
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

<p>Recursively compute polynomial of a value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BO</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> binary operation</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>Result polynomial</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ab719192e40abe9e51c199e82c8019e1c">computePolynomial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#ab719192e40abe9e51c199e82c8019e1c">computePolynomial</a>.</p>

</div>
</div>

### computePolynomialFromPointer() {#a38a01001593bf75700ee024b15bdf413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialFromPointer (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; Ptr, <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; BasePtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Compute the <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> representation of a Pointer type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ptr</td>
<td class="doxyParamItemDescription"><p>input pointer value</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>result polynomial</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BasePtr</td>
<td class="doxyParamItemDescription"><p>pointer the polynomial is based on</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Datalayout of the target machine</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab719192e40abe9e51c199e82c8019e1c">computePolynomial</a>, <a href="#a38a01001593bf75700ee024b15bdf413">computePolynomialFromPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a3685b2128d8e6917000e4adc3b266ff6">llvm::CastInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a0cb38e302133457f235fdcc6723abeac">computeFromLI</a> and <a href="#a38a01001593bf75700ee024b15bdf413">computePolynomialFromPointer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
