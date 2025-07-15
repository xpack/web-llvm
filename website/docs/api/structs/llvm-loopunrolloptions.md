---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/loopunrolloptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoopUnrollOptions` Struct Reference

<p>A set of parameters used to control various transforms performed by the LoopUnroll pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LoopUnrollOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">llvm/Transforms/Scalar/LoopUnrollPass.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a> (int OptLevel=2, bool OnlyWhenForced=false, bool ForgetSCEV=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopunrolloptions">LoopUnrollOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705ee9545a1e744dc12412ed3f603854">setPartial</a> (bool Partial)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables partial unrolling. <a href="#a705ee9545a1e744dc12412ed3f603854">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopunrolloptions">LoopUnrollOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3531f53e646c9dc4db4b143396eaaa9">setRuntime</a> (bool Runtime)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables unrolling of loops with runtime trip count. <a href="#ad3531f53e646c9dc4db4b143396eaaa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopunrolloptions">LoopUnrollOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a141c98b22bfdde079b9838d9c926dcb8">setPeeling</a> (bool Peeling)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables loop peeling. <a href="#a141c98b22bfdde079b9838d9c926dcb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopunrolloptions">LoopUnrollOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83eb8e86169f58ee4e49081c812e9ae">setUpperBound</a> (bool UpperBound)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables the use of trip count upper bound in loop unrolling. <a href="#ac83eb8e86169f58ee4e49081c812e9ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopunrolloptions">LoopUnrollOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23b58007b48c92fc47e2297b358fcab6">setOptLevel</a> (int O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopunrolloptions">LoopUnrollOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a3cf2a9623a5ce834c918e84b03167">setProfileBasedPeeling</a> (int O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopunrolloptions">LoopUnrollOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa262f9050d63cff88c42d9e8e148cab2">setFullUnrollMaxCount</a> (unsigned O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3533763e5a069304cac300d58aa3c335">AllowPartial</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f3cc58de97975474aec06d7c46b2fa">AllowPeeling</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e0d8e894c9a946cab90061f99a514d4">AllowRuntime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd31f207713b86ad24694c320b1db3f0">AllowUpperBound</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85e15580034714afcf2519f689174b10">AllowProfileBasedPeeling</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a307cbe3aacadc70d64a8570be1394229">FullUnrollMaxCount</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffbb1b91937d258b118eccfd4fb5d74">OptLevel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7f4d26f7d8ccc72d9006b729e6a637">OnlyWhenForced</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If false, use a cost model to determine whether unrolling of a loop is profitable. <a href="#a1d7f4d26f7d8ccc72d9006b729e6a637">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27976a17a9771b0dbbf007157226c33d">ForgetSCEV</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, forget all loops when unrolling. <a href="#a27976a17a9771b0dbbf007157226c33d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A set of parameters used to control various transforms performed by the LoopUnroll pass.</p>


<p>Each of the boolean parameters can be set to: true - enabling the transformation. false - disabling the transformation. None - relying on a global default.</p>


<p>There is also OptLevel parameter, which is used for additional loop unroll tuning.</p>


<p>Intended use is to create a default object, modify parameters with additional setters and then pass it to <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a>.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopUnrollOptions() {#a6214d3222968e378abe9eadcd6599df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopUnrollOptions::LoopUnrollOptions (int OptLevel=2, bool OnlyWhenForced=false, bool ForgetSCEV=false)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>References <a href="#a27976a17a9771b0dbbf007157226c33d">ForgetSCEV</a>, <a href="#a1d7f4d26f7d8ccc72d9006b729e6a637">OnlyWhenForced</a> and <a href="#a0ffbb1b91937d258b118eccfd4fb5d74">OptLevel</a>.</p>


<p>Referenced by <a href="#aa262f9050d63cff88c42d9e8e148cab2">setFullUnrollMaxCount</a>, <a href="#a23b58007b48c92fc47e2297b358fcab6">setOptLevel</a>, <a href="#a705ee9545a1e744dc12412ed3f603854">setPartial</a>, <a href="#a141c98b22bfdde079b9838d9c926dcb8">setPeeling</a>, <a href="#ae1a3cf2a9623a5ce834c918e84b03167">setProfileBasedPeeling</a>, <a href="#ad3531f53e646c9dc4db4b143396eaaa9">setRuntime</a> and <a href="#ac83eb8e86169f58ee4e49081c812e9ae">setUpperBound</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setFullUnrollMaxCount() {#aa262f9050d63cff88c42d9e8e148cab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollOptions &amp; llvm::LoopUnrollOptions::setFullUnrollMaxCount (unsigned O)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>References <a href="#a307cbe3aacadc70d64a8570be1394229">FullUnrollMaxCount</a> and <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>.</p>

</div>
</div>

### setOptLevel() {#a23b58007b48c92fc47e2297b358fcab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollOptions &amp; llvm::LoopUnrollOptions::setOptLevel (int O)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>References <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a> and <a href="#a0ffbb1b91937d258b118eccfd4fb5d74">OptLevel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>.</p>

</div>
</div>

### setPartial() {#a705ee9545a1e744dc12412ed3f603854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollOptions &amp; llvm::LoopUnrollOptions::setPartial (bool Partial)</td>
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

<p>Enables or disables partial unrolling.</p>


<p>When disabled only full unrolling is allowed.</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>References <a href="#a3533763e5a069304cac300d58aa3c335">AllowPartial</a> and <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>.</p>

</div>
</div>

### setPeeling() {#a141c98b22bfdde079b9838d9c926dcb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollOptions &amp; llvm::LoopUnrollOptions::setPeeling (bool Peeling)</td>
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

<p>Enables or disables loop peeling.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>References <a href="#a89f3cc58de97975474aec06d7c46b2fa">AllowPeeling</a> and <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>.</p>

</div>
</div>

### setProfileBasedPeeling() {#ae1a3cf2a9623a5ce834c918e84b03167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollOptions &amp; llvm::LoopUnrollOptions::setProfileBasedPeeling (int O)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>References <a href="#a85e15580034714afcf2519f689174b10">AllowProfileBasedPeeling</a> and <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>.</p>

</div>
</div>

### setRuntime() {#ad3531f53e646c9dc4db4b143396eaaa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollOptions &amp; llvm::LoopUnrollOptions::setRuntime (bool Runtime)</td>
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

<p>Enables or disables unrolling of loops with runtime trip count.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>References <a href="#a4e0d8e894c9a946cab90061f99a514d4">AllowRuntime</a>, <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabdabc366f2d0ba3d681e7a3899917c5d3de">llvm::Runtime</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>.</p>

</div>
</div>

### setUpperBound() {#ac83eb8e86169f58ee4e49081c812e9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollOptions &amp; llvm::LoopUnrollOptions::setUpperBound (bool UpperBound)</td>
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

<p>Enables or disables the use of trip count upper bound in loop unrolling.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>References <a href="#acd31f207713b86ad24694c320b1db3f0">AllowUpperBound</a> and <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllowPartial {#a3533763e5a069304cac300d58aa3c335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::LoopUnrollOptions::AllowPartial</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>Referenced by <a href="#a705ee9545a1e744dc12412ed3f603854">setPartial</a>.</p>

</div>
</div>

### AllowPeeling {#a89f3cc58de97975474aec06d7c46b2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::LoopUnrollOptions::AllowPeeling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>Referenced by <a href="#a141c98b22bfdde079b9838d9c926dcb8">setPeeling</a>.</p>

</div>
</div>

### AllowProfileBasedPeeling {#a85e15580034714afcf2519f689174b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::LoopUnrollOptions::AllowProfileBasedPeeling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>Referenced by <a href="#ae1a3cf2a9623a5ce834c918e84b03167">setProfileBasedPeeling</a>.</p>

</div>
</div>

### AllowRuntime {#a4e0d8e894c9a946cab90061f99a514d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::LoopUnrollOptions::AllowRuntime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>Referenced by <a href="#ad3531f53e646c9dc4db4b143396eaaa9">setRuntime</a>.</p>

</div>
</div>

### AllowUpperBound {#acd31f207713b86ad24694c320b1db3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::LoopUnrollOptions::AllowUpperBound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>Referenced by <a href="#ac83eb8e86169f58ee4e49081c812e9ae">setUpperBound</a>.</p>

</div>
</div>

### ForgetSCEV {#a27976a17a9771b0dbbf007157226c33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::LoopUnrollOptions::ForgetSCEV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, forget all loops when unrolling.</p>


<p>If false, forget top-most loop of the currently processed loops, which removes one entry at a time from the internal <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> records. For large loops, the former is faster.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>Referenced by <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a>.</p>

</div>
</div>

### FullUnrollMaxCount {#a307cbe3aacadc70d64a8570be1394229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::LoopUnrollOptions::FullUnrollMaxCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>Referenced by <a href="#aa262f9050d63cff88c42d9e8e148cab2">setFullUnrollMaxCount</a>.</p>

</div>
</div>

### OnlyWhenForced {#a1d7f4d26f7d8ccc72d9006b729e6a637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopUnrollOptions::OnlyWhenForced</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If false, use a cost model to determine whether unrolling of a loop is profitable.</p>


<p>If true, only loops that explicitly request unrolling via metadata are considered. All other loops are skipped.</p>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>Referenced by <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a>.</p>

</div>
</div>

### OptLevel {#a0ffbb1b91937d258b118eccfd4fb5d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::LoopUnrollOptions::OptLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<p>Referenced by <a href="#a6214d3222968e378abe9eadcd6599df1">LoopUnrollOptions</a> and <a href="#a23b58007b48c92fc47e2297b358fcab6">setOptLevel</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
