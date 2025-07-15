---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopnest
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopNest` Class Reference

<p>This class represents a loop nest and can be used to query its properties. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopNest { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">llvm/Analysis/LoopNestAnalysis.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3d2f48690d2cdc62adb54486ea1ef7c">InstrVectorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LoopNestEnum { <a href="#a69ead1aa41112d86315adbec764d66ac">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80b31035ddca93f1c59789d3c8af1d4">LoopNest</a> (Loop &amp;Root, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a loop nest rooted by loop <span class="doxyComputerOutput">Root</span>. <a href="#aa80b31035ddca93f1c59789d3c8af1d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a432b4455d6653676c5cd49ffb464b7dd">LoopNest</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb26e0f4ad96cecfa73f0abbed21b61f">getOutermostLoop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the outermost loop in the loop nest. <a href="#aeb26e0f4ad96cecfa73f0abbed21b61f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee0bc590a090ac389d8f1f3957e669b6">getInnermostLoop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the innermost loop in the loop nest if the nest has only one innermost loop, and a nullptr otherwise. <a href="#aee0bc590a090ac389d8f1f3957e669b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad3f25fdf2e9c0c04e72750a569afffd">getLoop</a> (unsigned Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the loop at the given <span class="doxyComputerOutput">Index</span>. <a href="#aad3f25fdf2e9c0c04e72750a569afffd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ae5f7cbdbb9f3e4ff06623bc815c24">getLoopIndex</a> (const Loop &amp;L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the loop index of the given loop <span class="doxyComputerOutput">L</span>. <a href="#ad6ae5f7cbdbb9f3e4ff06623bc815c24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec57833927c1ee7b4ce3c49d3867ee23">getNumLoops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of loops in the nest. <a href="#aec57833927c1ee7b4ce3c49d3867ee23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b8c1f7e00ee579ae55bad5bb1b44b31">getLoops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the loops in the nest. <a href="#a2b8c1f7e00ee579ae55bad5bb1b44b31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a74fccdd55e3793730ca5fd831595b16d">LoopVectorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a55eae28402873c1a08fcb29323a16b">getLoopsAtDepth</a> (unsigned Depth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the loops in the nest at the given <span class="doxyComputerOutput">Depth</span>. <a href="#a9a55eae28402873c1a08fcb29323a16b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a74fccdd55e3793730ca5fd831595b16d">LoopVectorTy</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57dd4a8d48a825207a80611dfef6d45e">getPerfectLoops</a> (ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve a vector of perfect loop nests contained in the current loop nest. <a href="#a57dd4a8d48a825207a80611dfef6d45e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e412f8b916b22399f515ff64bfb6705">getNestDepth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the loop nest depth (i.e. <a href="#a2e412f8b916b22399f515ff64bfb6705">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe3cef3fd28531e0c1e5ae0980e916f">getMaxPerfectDepth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum perfect nesting depth. <a href="#acbe3cef3fd28531e0c1e5ae0980e916f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb914cbf1769e0ced099aafb56e63adf">areAllLoopsSimplifyForm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all loops in the loop nest are in simplify form. <a href="#aeb914cbf1769e0ced099aafb56e63adf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe544749686c1cec7d210cd31cc092c">areAllLoopsRotatedForm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all loops in the loop nest are in rotated form. <a href="#aafe544749686c1cec7d210cd31cc092c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc0fffa89a787bcc12e5db7a603006c">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the function to which the loop-nest belongs. <a href="#accc0fffa89a787bcc12e5db7a603006c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a054dd1de2de1b190b7a47b0c67a75730">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f02315a5f8b586f46e88acdd9d555b4">MaxPerfectDepth</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a74fccdd55e3793730ca5fd831595b16d">LoopVectorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3085b412e1547510b6891a60494b1d14">Loops</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f905da3130336a4fddcd7a7d3360bfd">getLoopNest</a> (Loop &amp;Root, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> object. <a href="#a9f905da3130336a4fddcd7a7d3360bfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c21f16b8b65879632a1d332e79d253">arePerfectlyNested</a> (const Loop &amp;OuterLoop, const Loop &amp;InnerLoop, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given loops <span class="doxyComputerOutput">OuterLoop</span> and <span class="doxyComputerOutput">InnerLoop</span> are perfectly nested with respect to each other, and false otherwise. <a href="#a67c21f16b8b65879632a1d332e79d253">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#aa3d2f48690d2cdc62adb54486ea1ef7c">InstrVectorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797a9f600b2119356e4ea74cdc6ba25a">getInterveningInstructions</a> (const Loop &amp;OuterLoop, const Loop &amp;InnerLoop, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vector of instructions that prevent the <a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> given by loops <span class="doxyComputerOutput">OuterLoop</span> and <span class="doxyComputerOutput">InnerLoop</span> from being perfect. <a href="#a797a9f600b2119356e4ea74cdc6ba25a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c7f512c7735232319f74e85a4263e2">getMaxPerfectDepth</a> (const Loop &amp;Root, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum nesting depth of the loop nest rooted by loop <span class="doxyComputerOutput">Root</span>. <a href="#ad2c7f512c7735232319f74e85a4263e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3d91a5a6e71c114dea21819cc71382">skipEmptyBlockUntil</a> (const BasicBlock *From, const BasicBlock *End, bool CheckUniquePred=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursivelly traverse all empty 'single successor' basic blocks of <span class="doxyComputerOutput">From</span> (if there are any). <a href="#a0c3d91a5a6e71c114dea21819cc71382">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static LoopNestEnum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1603d50c5be9254d107d88f9d5b0cd3a">analyzeLoopNestForPerfectNest</a> (const Loop &amp;OuterLoop, const Loop &amp;InnerLoop, ScalarEvolution &amp;SE)</td>
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

<p>This class represents a loop nest and can be used to query its properties.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### InstrVectorTy {#aa3d2f48690d2cdc62adb54486ea1ef7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoopNest::InstrVectorTy =  SmallVector&lt;const Instruction *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LoopNestEnum {#a69ead1aa41112d86315adbec764d66ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoopNest::LoopNestEnum </td>
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
<td class="doxyEnumItemName">PerfectLoopNest<a id="a69ead1aa41112d86315adbec764d66aca4583d47bb51f160c5c120a329aa0bc12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImperfectLoopNest<a id="a69ead1aa41112d86315adbec764d66acad85973afeb09b3b812e285674aa2b40e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InvalidLoopStructure<a id="a69ead1aa41112d86315adbec764d66aca8e8e513e9fe34d154bf9aa0482a2b923"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OuterLoopLowerBoundUnknown<a id="a69ead1aa41112d86315adbec764d66aca65e0c77d568ff0603e82cd8546acc6f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoopNest() {#aa80b31035ddca93f1c59789d3c8af1d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopNest::LoopNest (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a loop nest rooted by loop <span class="doxyComputerOutput">Root</span>.</p>

<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp">LoopNestAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c754cdf7230d80a20aded3ead0c6d37">llvm::breadth_first</a>, <a href="#ad2c7f512c7735232319f74e85a4263e2">getMaxPerfectDepth</a>, <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a> and <a href="#a8f02315a5f8b586f46e88acdd9d555b4">MaxPerfectDepth</a>.</p>

</div>
</div>

### LoopNest() {#a432b4455d6653676c5cd49ffb464b7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopNest::LoopNest ()</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>References <a href="#a67c21f16b8b65879632a1d332e79d253">arePerfectlyNested</a>, <a href="#a797a9f600b2119356e4ea74cdc6ba25a">getInterveningInstructions</a>, <a href="#a9f905da3130336a4fddcd7a7d3360bfd">getLoopNest</a>, <a href="#ad2c7f512c7735232319f74e85a4263e2">getMaxPerfectDepth</a> and <a href="#a0c3d91a5a6e71c114dea21819cc71382">skipEmptyBlockUntil</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### areAllLoopsRotatedForm() {#aafe544749686c1cec7d210cd31cc092c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopNest::areAllLoopsRotatedForm ()</td>
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

<p>Return true if all loops in the loop nest are in rotated form.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a> and <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>

</div>
</div>

### areAllLoopsSimplifyForm() {#aeb914cbf1769e0ced099aafb56e63adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopNest::areAllLoopsSimplifyForm ()</td>
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

<p>Return true if all loops in the loop nest are in simplify form.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a> and <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>

</div>
</div>

### getInnermostLoop() {#aee0bc590a090ac389d8f1f3957e669b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * llvm::LoopNest::getInnermostLoop ()</td>
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

<p>Return the innermost loop in the loop nest if the nest has only one innermost loop, and a nullptr otherwise.</p>


<p>Note: the innermost loop returned is not necessarily perfectly nested.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a57994482c17097d9f936acff3a6598ac">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopDepth</a> and <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>

</div>
</div>

### getLoop() {#aad3f25fdf2e9c0c04e72750a569afffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * llvm::LoopNest::getLoop (unsigned Index)</td>
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

<p>Return the loop at the given <span class="doxyComputerOutput">Index</span>.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>


<p>Referenced by <a href="#ad6ae5f7cbdbb9f3e4ff06623bc815c24">getLoopIndex</a> and <a href="#a9a55eae28402873c1a08fcb29323a16b">getLoopsAtDepth</a>.</p>

</div>
</div>

### getLoopIndex() {#ad6ae5f7cbdbb9f3e4ff06623bc815c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopNest::getLoopIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
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

<p>Get the loop index of the given loop <span class="doxyComputerOutput">L</span>.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>References <a href="#aad3f25fdf2e9c0c04e72750a569afffd">getLoop</a>, <a href="#aec57833927c1ee7b4ce3c49d3867ee23">getNumLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getLoops() {#a2b8c1f7e00ee579ae55bad5bb1b44b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Loop * &gt; llvm::LoopNest::getLoops ()</td>
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

<p>Get the loops in the nest.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>Reference <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6a1c647f91f86b7bfea85c0cee90de91">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopinterchange-cpp-/loopinterchange/#a377904340b53c8545eb81eb92022c4f4">anonymous{LoopInterchange.cpp}::LoopInterchange::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopinterchangepass/#a99a46045e2cc7182d6a786d400604d76">llvm::LoopInterchangePass::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a0da6529029f6f71768e36765c25d54d5">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### getLoopsAtDepth() {#a9a55eae28402873c1a08fcb29323a16b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorTy llvm::LoopNest::getLoopsAtDepth (unsigned Depth)</td>
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

<p>Get the loops in the nest at the given <span class="doxyComputerOutput">Depth</span>.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#aad3f25fdf2e9c0c04e72750a569afffd">getLoop</a>, <a href="#aec57833927c1ee7b4ce3c49d3867ee23">getNumLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>

</div>
</div>

### getMaxPerfectDepth() {#acbe3cef3fd28531e0c1e5ae0980e916f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopNest::getMaxPerfectDepth ()</td>
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

<p>Return the maximum perfect nesting depth.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>Reference <a href="#a8f02315a5f8b586f46e88acdd9d555b4">MaxPerfectDepth</a>.</p>

</div>
</div>

### getName() {#a054dd1de2de1b190b7a47b0c67a75730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::LoopNest::getName ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>Reference <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>

</div>
</div>

### getNestDepth() {#a2e412f8b916b22399f515ff64bfb6705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopNest::getNestDepth ()</td>
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

<p>Return the loop nest depth (i.e.</p>


<p>the loop depth of the 'deepest' loop) For example given the loop nest:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(i)      </span><span class="doxyHighlightComment">// loop at level 1 and Root of the nest</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(j1)   </span><span class="doxyHighlightComment">// loop at level 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(k)  </span><span class="doxyHighlightComment">// loop at level 3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(j2)   </span><span class="doxyHighlightComment">// loop at level 2</span></span></div>

</div>


<p><a href="#a2e412f8b916b22399f515ff64bfb6705">getNestDepth()</a> would return 3.</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6a1c647f91f86b7bfea85c0cee90de91">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getNumLoops() {#aec57833927c1ee7b4ce3c49d3867ee23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::LoopNest::getNumLoops ()</td>
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

<p>Return the number of loops in the nest.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>Reference <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>


<p>Referenced by <a href="#ad6ae5f7cbdbb9f3e4ff06623bc815c24">getLoopIndex</a> and <a href="#a9a55eae28402873c1a08fcb29323a16b">getLoopsAtDepth</a>.</p>

</div>
</div>

### getOutermostLoop() {#aeb26e0f4ad96cecfa73f0abbed21b61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop &amp; llvm::LoopNest::getOutermostLoop ()</td>
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

<p>Return the outermost loop in the loop nest.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>Reference <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6a1c647f91f86b7bfea85c0cee90de91">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopinterchangepass/#a99a46045e2cc7182d6a786d400604d76">llvm::LoopInterchangePass::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a0da6529029f6f71768e36765c25d54d5">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### getParent() {#accc0fffa89a787bcc12e5db7a603006c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::LoopNest::getParent ()</td>
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

<p>Return the function to which the loop-nest belongs.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>Reference <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopinterchangepass/#a99a46045e2cc7182d6a786d400604d76">llvm::LoopInterchangePass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/loopunrollandjampass/#aceae0aba9cc69bf89d3241d61190b9ec">llvm::LoopUnrollAndJamPass::run</a>.</p>

</div>
</div>

### getPerfectLoops() {#a57dd4a8d48a825207a80611dfef6d45e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; LoopVectorTy, 4 &gt; LoopNest::getPerfectLoops (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve a vector of perfect loop nests contained in the current loop nest.</p>


<p>For example, given the following nest containing 4 loops, this member function would return {{L1,L2},{L3,L4}}.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(i) </span><span class="doxyHighlightComment">// L1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(j) </span><span class="doxyHighlightComment">// L2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;code&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(k) </span><span class="doxyHighlightComment">// L3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(l) </span><span class="doxyHighlightComment">// L4</span></span></div>

</div>


<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp">LoopNestAnalysis.cpp</a>.</p>


<p>References <a href="#a67c21f16b8b65879632a1d332e79d253">arePerfectlyNested</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a3085b412e1547510b6891a60494b1d14">Loops</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Loops {#a3085b412e1547510b6891a60494b1d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorTy llvm::LoopNest::Loops</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>Referenced by <a href="#aafe544749686c1cec7d210cd31cc092c">areAllLoopsRotatedForm</a>, <a href="#aeb914cbf1769e0ced099aafb56e63adf">areAllLoopsSimplifyForm</a>, <a href="#aee0bc590a090ac389d8f1f3957e669b6">getInnermostLoop</a>, <a href="#aad3f25fdf2e9c0c04e72750a569afffd">getLoop</a>, <a href="#a2b8c1f7e00ee579ae55bad5bb1b44b31">getLoops</a>, <a href="#a9a55eae28402873c1a08fcb29323a16b">getLoopsAtDepth</a>, <a href="#a054dd1de2de1b190b7a47b0c67a75730">getName</a>, <a href="#a2e412f8b916b22399f515ff64bfb6705">getNestDepth</a>, <a href="#aec57833927c1ee7b4ce3c49d3867ee23">getNumLoops</a>, <a href="#aeb26e0f4ad96cecfa73f0abbed21b61f">getOutermostLoop</a>, <a href="#accc0fffa89a787bcc12e5db7a603006c">getParent</a>, <a href="#a57dd4a8d48a825207a80611dfef6d45e">getPerfectLoops</a> and <a href="#aa80b31035ddca93f1c59789d3c8af1d4">LoopNest</a>.</p>

</div>
</div>

### MaxPerfectDepth {#a8f02315a5f8b586f46e88acdd9d555b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::LoopNest::MaxPerfectDepth</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>.</p>


<p>Referenced by <a href="#acbe3cef3fd28531e0c1e5ae0980e916f">getMaxPerfectDepth</a> and <a href="#aa80b31035ddca93f1c59789d3c8af1d4">LoopNest</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### arePerfectlyNested() {#a67c21f16b8b65879632a1d332e79d253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopNest::arePerfectlyNested (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; OuterLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; InnerLoop, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Return true if the given loops <span class="doxyComputerOutput">OuterLoop</span> and <span class="doxyComputerOutput">InnerLoop</span> are perfectly nested with respect to each other, and false otherwise.</p>


<p>Example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(j)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(k)</span></span></div>

</div>


<p>arePerfectlyNested(loop_i, loop_j, SE) would return true. arePerfectlyNested(loop_j, loop_k, SE) would return true. arePerfectlyNested(loop_i, loop_k, SE) would return false.</p>


<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp">LoopNestAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ad2c7f512c7735232319f74e85a4263e2">getMaxPerfectDepth</a>, <a href="#a57dd4a8d48a825207a80611dfef6d45e">getPerfectLoops</a> and <a href="#a432b4455d6653676c5cd49ffb464b7dd">LoopNest</a>.</p>

</div>
</div>

### getInterveningInstructions() {#a797a9f600b2119356e4ea74cdc6ba25a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopNest::InstrVectorTy LoopNest::getInterveningInstructions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; OuterLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; InnerLoop, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Return a vector of instructions that prevent the <a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> given by loops <span class="doxyComputerOutput">OuterLoop</span> and <span class="doxyComputerOutput">InnerLoop</span> from being perfect.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp">LoopNestAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#a6a54f3aff376f5f286501361749fea29">checkSafeInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a096b15bbaad7c5f24d29b0592339b9e8">llvm::Loop::getBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ab48af53a5000ecede46c76dabb4578d2">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#a410517ee51b91e86b7908a3895138054">getInnerLoopGuardCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#a1324f8c4f6c399fbb6c4fae0404a47ca">getOuterLoopLatchCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#ab3595005ef7c117f30d4c18201190bbb">VerboseDebug</a>.</p>


<p>Referenced by <a href="#a432b4455d6653676c5cd49ffb464b7dd">LoopNest</a>.</p>

</div>
</div>

### getLoopNest() {#a9f905da3130336a4fddcd7a7d3360bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LoopNest &gt; LoopNest::getLoopNest (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> object.</p>

<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp">LoopNestAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a432b4455d6653676c5cd49ffb464b7dd">LoopNest</a> and <a href="/web-llvm/docs/api/classes/llvm/loopnestprinterpass/#aaf9544eaca7fe1e7b473639f38a3b094">llvm::LoopNestPrinterPass::run</a>.</p>

</div>
</div>

### getMaxPerfectDepth() {#ad2c7f512c7735232319f74e85a4263e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LoopNest::getMaxPerfectDepth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Return the maximum nesting depth of the loop nest rooted by loop <span class="doxyComputerOutput">Root</span>.</p>


<p>For example given the loop nest:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(i)     </span><span class="doxyHighlightComment">// loop at level 1 and Root of the nest</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(j)   </span><span class="doxyHighlightComment">// loop at level 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;code&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(k) </span><span class="doxyHighlightComment">// loop at level 3</span></span></div>

</div>


<p>getMaxPerfectDepth(Loop_i) would return 2.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp">LoopNestAnalysis.cpp</a>.</p>


<p>References <a href="#a67c21f16b8b65879632a1d332e79d253">arePerfectlyNested</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a917a64b00c1745fd0c78c2b2320cd4ad">llvm::Loop::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a56aaf5c25d50d52888f79b444f2d6c">llvm::LoopBase&lt; BlockT, LoopT &gt;::getSubLoops</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a432b4455d6653676c5cd49ffb464b7dd">LoopNest</a>, <a href="#aa80b31035ddca93f1c59789d3c8af1d4">LoopNest</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6a1c647f91f86b7bfea85c0cee90de91">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### skipEmptyBlockUntil() {#a0c3d91a5a6e71c114dea21819cc71382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock &amp; LoopNest::skipEmptyBlockUntil (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * End, bool CheckUniquePred=false)</td>
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

<p>Recursivelly traverse all empty 'single successor' basic blocks of <span class="doxyComputerOutput">From</span> (if there are any).</p>


<p>When <span class="doxyComputerOutput">CheckUniquePred</span> is set to true, check if each of the empty single successors has a unique predecessor. Return the last basic block found or <span class="doxyComputerOutput">End</span> if it was reached during the search.</p>


<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp">LoopNestAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a74aa9daea070e2ad3394a3ec58b7316a">llvm::BasicBlock::getUniquePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a57f1945911ca1e95d0f51d7c3516b529">llvm::BasicBlock::getUniqueSuccessor</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loop/#a580a6361a2bad87e6071ecc795bdae96">llvm::Loop::getLoopGuardBranch</a> and <a href="#a432b4455d6653676c5cd49ffb464b7dd">LoopNest</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### analyzeLoopNestForPerfectNest() {#a1603d50c5be9254d107d88f9d5b0cd3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopNest::LoopNestEnum LoopNest::analyzeLoopNestForPerfectNest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; OuterLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; InnerLoop, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp">LoopNestAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">LoopNestAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp">LoopNestAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
