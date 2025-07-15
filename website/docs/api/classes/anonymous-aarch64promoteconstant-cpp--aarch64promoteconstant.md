---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64PromoteConstant` Class Reference

<p>Promotes interesting constant into global variables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> class - This class is used to implement unstructured interprocedural optimizations and analyses. <a href="/web-llvm/docs/api/classes/llvm/modulepass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e357c8b7364d5898a8085b69bf2191c">PromotionCacheTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *, <a href="/web-llvm/docs/api/structs/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/promotedconstant">PromotedConstant</a>, 16 &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be10e967738b01a826d0619658feb6e">Uses</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, unsigned &gt;, 4 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> to store a list of Uses. <a href="#a6be10e967738b01a826d0619658feb6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433ad60ba4e1bc3b77fbd7adccf6213c">InsertionPoints</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">Uses</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map an insertion point to all the uses it dominates. <a href="#a433ad60ba4e1bc3b77fbd7adccf6213c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332e5f6f2291c407f086104317716727">AArch64PromoteConstant</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2805049a8572b7ccbb50e28bf92b25">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a3f2805049a8572b7ccbb50e28bf92b25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef722b33868983f0b2e4f6d3657a8ae">runOnModule</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterate over the functions and promote the interesting constants into global variables with module scope. <a href="#a1ef722b33868983f0b2e4f6d3657a8ae">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf9032af059c3a53925dca879193eea">runOnFunction</a> (Function &amp;F, PromotionCacheTy &amp;PromotionCache)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for interesting constants used within the given function. <a href="#aeaf9032af059c3a53925dca879193eea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e44b24170d835e47f0d83ec0c5dc717">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a6e44b24170d835e47f0d83ec0c5dc717">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a319f00db9e55ea29e751829283c477bb">findInsertionPoint</a> (Instruction &amp;User, unsigned OpNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the closest point that dominates the given <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>. <a href="#a319f00db9e55ea29e751829283c477bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0755590d0f64e0ca540ab35b2e8674e9">isDominated</a> (Instruction *NewPt, Instruction *User, unsigned OpNo, InsertionPoints &amp;InsertPts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the given insertion point is dominated by an existing insertion point. <a href="#a0755590d0f64e0ca540ab35b2e8674e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f98a42cd28775ed8e06364323fd555d">tryAndMerge</a> (Instruction *NewPt, Instruction *User, unsigned OpNo, InsertionPoints &amp;InsertPts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the given insertion point can be merged with an existing insertion point in a common dominator. <a href="#a2f98a42cd28775ed8e06364323fd555d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56925206b190383ea8d5a2c9ed7b13b6">computeInsertionPoint</a> (Instruction *User, unsigned OpNo, InsertionPoints &amp;InsertPts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the minimal insertion points to dominates all the interesting uses of value. <a href="#a56925206b190383ea8d5a2c9ed7b13b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a06c2dcc42265ded0f1c3ff3b8b23a2">insertDefinitions</a> (Function &amp;F, GlobalVariable &amp;GV, InsertionPoints &amp;InsertPts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a definition of a new global variable at each point contained in InsPtsPerFunc and update the related uses (also contained in InsPtsPerFunc). <a href="#a1a06c2dcc42265ded0f1c3ff3b8b23a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625ee8ef5b69bb96a15ef3a7064ef0e7">promoteConstants</a> (Function &amp;F, SmallVectorImpl&lt; UpdateRecord &gt; &amp;Updates, PromotionCacheTy &amp;PromotionCache)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do the constant promotion indicated by the Updates records, keeping track of globals in PromotionCache. <a href="#a625ee8ef5b69bb96a15ef3a7064ef0e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce58b7a04ffbe385500a85e63957f7e">appendAndTransferDominatedUses</a> (Instruction *NewPt, Instruction *User, unsigned OpNo, InsertionPoints::iterator &amp;IPI, InsertionPoints &amp;InsertPts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer the list of dominated uses of IPI to NewPt in InsertPts. <a href="#a8ce58b7a04ffbe385500a85e63957f7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f2383fad0fb27c1a24f243ebc825da">ID</a> = 0</td>
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

<p>Promotes interesting constant into global variables.</p>


<p>The motivating example is: static const uint16_t TableA[32] = { 41944, 40330, 38837, 37450, 36158, 34953, 33826, 32768, 31776, 30841, 29960, 29128, 28340, 27595, 26887, 26215, 25576, 24967, 24386, 23832, 23302, 22796, 22311, 21846, 21400, 20972, 20561, 20165, 19785, 19419, 19066, 18725, };</p>


<p>uint8x16x4_t LoadStatic(void) { uint8x16x4_t ret; ret.val[0] = vld1q_u16(TableA + 0); ret.val[1] = vld1q_u16(TableA + 8); ret.val[2] = vld1q_u16(TableA + 16); ret.val[3] = vld1q_u16(TableA + 24); return ret; }</p>


<p>The constants in this example are folded into the uses. Thus, 4 different constants are created.</p>


<p>As their type is vector the cheapest way to create them is to load them for the memory.</p>


<p>Therefore the final assembly final has 4 different loads. With this pass enabled, only one load is issued for the constants.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PromotionCacheTy {#a4e357c8b7364d5898a8085b69bf2191c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::PromotionCacheTy =  SmallDenseMap&lt;Constant *, PromotedConstant, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### InsertionPoints {#a433ad60ba4e1bc3b77fbd7adccf6213c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::InsertionPoints =  DenseMap&lt;Instruction *, Uses&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map an insertion point to all the uses it dominates.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### Uses {#a6be10e967738b01a826d0619658feb6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::Uses =  SmallVector&lt;std::pair&lt;Instruction *, unsigned&gt;, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> to store a list of Uses.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AArch64PromoteConstant() {#a332e5f6f2291c407f086104317716727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::AArch64PromoteConstant ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a71f2383fad0fb27c1a24f243ebc825da">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31f7820c2baf31ef6792320e105af10d">llvm::initializeAArch64PromoteConstantPass</a> and <a href="/web-llvm/docs/api/classes/llvm/modulepass/#a723659a08d210f4f566887bda3f9f976">llvm::ModulePass::ModulePass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae1dee0e28b161d52ffd8a6921ad83e2b">llvm::createAArch64PromoteConstantPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPassName() {#a3f2805049a8572b7ccbb50e28bf92b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>Referenced by <a href="#a1ef722b33868983f0b2e4f6d3657a8ae">runOnModule</a>.</p>

</div>
</div>

### runOnModule() {#a1ef722b33868983f0b2e4f6d3657a8ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::runOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Iterate over the functions and promote the interesting constants into global variables with module scope.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3f2805049a8572b7ccbb50e28bf92b25">getPassName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#a3985f1f39349428d17f0d2b81ebc6349">runOnFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/modulepass/#ab0f92e1d06aa28c44dc236c73460ba7a">llvm::ModulePass::skipModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeInsertionPoint() {#a56925206b190383ea8d5a2c9ed7b13b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PromoteConstant::computeInsertionPoint (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/densemap">InsertionPoints</a> &amp; InsertPts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the minimal insertion points to dominates all the interesting uses of value.</p>


<p>Insertion points are group per function and each insertion point contains a list of all the uses it dominates within the related function</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/user"&gt;User&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>the user of the constant</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OpNo</td>
<td class="doxyParamItemDescription"><p>the operand number of the constant</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] InsertPts</td>
<td class="doxyParamItemDescription"><p>output storage of the analysis</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### findInsertionPoint() {#a319f00db9e55ea29e751829283c477bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * AArch64PromoteConstant::findInsertionPoint (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; User, unsigned OpNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the closest point that dominates the given <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a6e44b24170d835e47f0d83ec0c5dc717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### insertDefinitions() {#a1a06c2dcc42265ded0f1c3ff3b8b23a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PromoteConstant::insertDefinitions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; GV, <a href="/web-llvm/docs/api/classes/llvm/densemap">InsertionPoints</a> &amp; InsertPts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a definition of a new global variable at each point contained in InsPtsPerFunc and update the related uses (also contained in InsPtsPerFunc).</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### isDominated() {#a0755590d0f64e0ca540ab35b2e8674e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PromoteConstant::isDominated (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * NewPt, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/densemap">InsertionPoints</a> &amp; InsertPts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the given insertion point is dominated by an existing insertion point.</p>


<p>If true, the given use is added to the list of dominated uses for the related existing point.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewPt</td>
<td class="doxyParamItemDescription"><p>the insertion point to be checked</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/user"&gt;User&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>the user of the constant</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OpNo</td>
<td class="doxyParamItemDescription"><p>the operand number of the use</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InsertPts</td>
<td class="doxyParamItemDescription"><p>existing insertion points</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>NewPt and all instruction in InsertPts belong to the same function</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if one of the insertion point in InsertPts dominates NewPt, false otherwise</p></dd>
</dl>


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### promoteConstants() {#a625ee8ef5b69bb96a15ef3a7064ef0e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PromoteConstant::promoteConstants (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/updaterecord">UpdateRecord</a> &gt; &amp; Updates, <a href="#a4e357c8b7364d5898a8085b69bf2191c">PromotionCacheTy</a> &amp; PromotionCache)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do the constant promotion indicated by the Updates records, keeping track of globals in PromotionCache.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### runOnFunction() {#aeaf9032af059c3a53925dca879193eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PromoteConstant::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="#a4e357c8b7364d5898a8085b69bf2191c">PromotionCacheTy</a> &amp; PromotionCache)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for interesting constants used within the given function.</p>


<p>Promote them into global variables, load these global variables within the related function, so that the number of inserted load is minimal.</p>


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### tryAndMerge() {#a2f98a42cd28775ed8e06364323fd555d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PromoteConstant::tryAndMerge (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * NewPt, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/densemap">InsertionPoints</a> &amp; InsertPts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the given insertion point can be merged with an existing insertion point in a common dominator.</p>


<p>If true, the given use is added to the list of the created insertion point.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewPt</td>
<td class="doxyParamItemDescription"><p>the insertion point to be checked</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/user"&gt;User&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>the user of the constant</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OpNo</td>
<td class="doxyParamItemDescription"><p>the operand number of the use</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InsertPts</td>
<td class="doxyParamItemDescription"><p>existing insertion points</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>NewPt and all instruction in InsertPts belong to the same function</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>isDominated returns false for the exact same parameters.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it exists an insertion point in InsertPts that could have been merged with NewPt in a common dominator, false otherwise</p></dd>
</dl>


<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### appendAndTransferDominatedUses() {#a8ce58b7a04ffbe385500a85e63957f7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::appendAndTransferDominatedUses (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * NewPt, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a214e872d61db2ea8cb023f127cafd0b9">InsertionPoints::iterator</a> &amp; IPI, <a href="/web-llvm/docs/api/classes/llvm/densemap">InsertionPoints</a> &amp; InsertPts)</td>
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

<p>Transfer the list of dominated uses of IPI to NewPt in InsertPts.</p>


<p>Append <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> to this list and delete the entry of IPI in InsertPts.</p>


<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a71f2383fad0fb27c1a24f243ebc825da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char AArch64PromoteConstant::ID = 0</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>Referenced by <a href="#a332e5f6f2291c407f086104317716727">AArch64PromoteConstant</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
