---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/bottomupvec
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BottomUpVec` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::BottomUpVec { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">llvm/Transforms/Vectorize/SandboxVectorizer/Passes/BottomUpVec.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpass">FunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pass that runs on a sandbox::Function. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a121d3320d95d3836b765bf8e8cbb4de8">BottomUpVec</a> (StringRef Pipeline)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99e15876a8fdb279707835eb24b037b">runOnFunction</a> (Function &amp;F, const Analyses &amp;A) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if it modifies <span class="doxyComputerOutput">F</span>. <a href="#af99e15876a8fdb279707835eb24b037b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47aa4241833389268fb4194c2ed936f5">printPipeline</a> (raw_ostream &amp;OS) const final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#ae4725099d02b2c60f33fca89e8672194">print()</a> but adds a newline. Used for testing. <a href="#a47aa4241833389268fb4194c2ed936f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78f745978a01f6f983897de815aaeb3c">createVectorInstr</a> (ArrayRef&lt; Value * &gt; Bndl, ArrayRef&lt; Value * &gt; Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates and returns a vector instruction that replaces the instructions in <span class="doxyComputerOutput">Bndl</span>. <a href="#a78f745978a01f6f983897de815aaeb3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add88155b9971925fb8c376e33a64af0a">tryEraseDeadInstrs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erases all dead instructions from the dead instruction candidates collected during vectorization. <a href="#add88155b9971925fb8c376e33a64af0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab03077fa914979d08c0d2684ed51a7b8">createShuffle</a> (Value *VecOp, const ShuffleMask &amp;Mask, BasicBlock *UserBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a shuffle instruction that shuffles <span class="doxyComputerOutput">VecOp</span> according to <span class="doxyComputerOutput">Mask</span>. <a href="#ab03077fa914979d08c0d2684ed51a7b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8f38d76aa2d3e923b1a72248a8a07e">createPack</a> (ArrayRef&lt; Value * &gt; ToPack, BasicBlock *UserBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Packs all elements of <span class="doxyComputerOutput">ToPack</span> into a vector and returns that vector. <a href="#aae8f38d76aa2d3e923b1a72248a8a07e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad7b5f4a7820715d589e79d06cc653c">collectPotentiallyDeadInstrs</a> (ArrayRef&lt; Value * &gt; Bndl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After we create vectors for groups of instructions, the original instructions are potentially dead and may need to be removed. <a href="#a5ad7b5f4a7820715d589e79d06cc653c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1500c0378bbec9f606ab408bc781f5">vectorizeRec</a> (ArrayRef&lt; Value * &gt; Bndl, ArrayRef&lt; Value * &gt; UserBndl, unsigned Depth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively try to vectorize <span class="doxyComputerOutput">Bndl</span> and its operands. <a href="#a2f1500c0378bbec9f606ab408bc781f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5597f69a1272ebf88ba70920c448d452">tryVectorize</a> (ArrayRef&lt; Value * &gt; Seeds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Entry point for vectorization starting from <span class="doxyComputerOutput">Seeds</span>. <a href="#a5597f69a1272ebf88ba70920c448d452">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dfd1da2f0ff3326944c923ab7d3b2b4">Change</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityanalysis">LegalityAnalysis</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f184aadfb0d48357960d51b3490de59">Legality</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8862e1c5d84a550101c93c76551f4790">DeadInstrCandidates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The original instructions that are potentially dead after vectorization. <a href="#a8862e1c5d84a550101c93c76551f4790">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instrmaps">InstrMaps</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7960076a164cc6cebdc824873e0e116">IMaps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps scalars to vectors. <a href="#ad7960076a164cc6cebdc824873e0e116">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionpassmanager">RegionPassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f18710c8016c42aa3dd429496513cf">RPM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The PM containing the pipeline of region passes. <a href="#ab5f18710c8016c42aa3dd429496513cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BottomUpVec() {#a121d3320d95d3836b765bf8e8cbb4de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::BottomUpVec::BottomUpVec (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pipeline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpass/#a0e0cb4a456ac5281b4f3baf5e55b4044">llvm::sandboxir::FunctionPass::FunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printPipeline() {#a47aa4241833389268fb4194c2ed936f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::BottomUpVec::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Similar to <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#ae4725099d02b2c60f33fca89e8672194">print()</a> but adds a newline. Used for testing.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#afd425fe36e3defee0e95b3b52cac0ae6">llvm::sandboxir::Pass::getName</a>.</p>

</div>
</div>

### runOnFunction() {#af99e15876a8fdb279707835eb24b037b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::BottomUpVec::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/analyses">Analyses</a> &amp; A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns true if it modifies <span class="doxyComputerOutput">F</span>.</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecce776bde376ee1d65c3d99abf3d175">llvm::AllowNonPow2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vecutils/#ab3b71740aabd9ed0695bae2780f0247d">llvm::sandboxir::VecUtils::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a94ed4ff75262c5c7bf6107a1cb09d583">llvm::sandboxir::Utils::getExpectedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vecutils/#afa56faa35b026a814f2fd65fd3016a4d">llvm::sandboxir::VecUtils::getFloorPowerOf2</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a880037a6ce1e268642581425f4f44c5f">llvm::sandboxir::Utils::getNumBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2101fdd9c93e15c51bc3dea630137be">llvm::OverrideVecRegBits</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af">llvm::TargetTransformInfo::RGK_FixedWidthVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectPotentiallyDeadInstrs() {#a5ad7b5f4a7820715d589e79d06cc653c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::BottomUpVec::collectPotentiallyDeadInstrs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * &gt; Bndl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After we create vectors for groups of instructions, the original instructions are potentially dead and may need to be removed.</p>


<p>This function helps collect these instructions (along with the pointer operands for loads/stores) so that they can be cleaned up later.</p>


<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a>.</p>

</div>
</div>

### createPack() {#aae8f38d76aa2d3e923b1a72248a8a07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::BottomUpVec::createPack (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * &gt; ToPack, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/basicblock">BasicBlock</a> * UserBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Packs all elements of <span class="doxyComputerOutput">ToPack</span> into a vector and returns that vector.</p>


<p><span class="doxyComputerOutput">UserBB</span> is the block of the user bundle.</p>


<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a>.</p>

</div>
</div>

### createShuffle() {#ab03077fa914979d08c0d2684ed51a7b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::BottomUpVec::createShuffle (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * VecOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflemask">ShuffleMask</a> &amp; Mask, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/basicblock">BasicBlock</a> * UserBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a shuffle instruction that shuffles <span class="doxyComputerOutput">VecOp</span> according to <span class="doxyComputerOutput">Mask</span>.</p>


<p><span class="doxyComputerOutput">UserBB</span> is the block of the user bundle.</p>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a>.</p>

</div>
</div>

### createVectorInstr() {#a78f745978a01f6f983897de815aaeb3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::BottomUpVec::createVectorInstr (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * &gt; Bndl, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * &gt; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates and returns a vector instruction that replaces the instructions in <span class="doxyComputerOutput">Bndl</span>.</p>


<p><span class="doxyComputerOutput">Operands</span> are the already vectorized operands.</p>


<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a>.</p>

</div>
</div>

### tryEraseDeadInstrs() {#add88155b9971925fb8c376e33a64af0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::BottomUpVec::tryEraseDeadInstrs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erases all dead instructions from the dead instruction candidates collected during vectorization.</p>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a>.</p>

</div>
</div>

### tryVectorize() {#a5597f69a1272ebf88ba70920c448d452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::BottomUpVec::tryVectorize (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * &gt; Seeds)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Entry point for vectorization starting from <span class="doxyComputerOutput">Seeds</span>.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a>.</p>

</div>
</div>

### vectorizeRec() {#a2f1500c0378bbec9f606ab408bc781f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::BottomUpVec::vectorizeRec (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * &gt; Bndl, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * &gt; UserBndl, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively try to vectorize <span class="doxyComputerOutput">Bndl</span> and its operands.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Change {#a6dfd1da2f0ff3326944c923ab7d3b2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::BottomUpVec::Change = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>.</p>

</div>
</div>

### DeadInstrCandidates {#a8862e1c5d84a550101c93c76551f4790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Instruction *&gt; llvm::sandboxir::BottomUpVec::DeadInstrCandidates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The original instructions that are potentially dead after vectorization.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>.</p>

</div>
</div>

### IMaps {#ad7960076a164cc6cebdc824873e0e116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InstrMaps&gt; llvm::sandboxir::BottomUpVec::IMaps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps scalars to vectors.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>.</p>

</div>
</div>

### Legality {#a9f184aadfb0d48357960d51b3490de59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LegalityAnalysis&gt; llvm::sandboxir::BottomUpVec::Legality</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>.</p>

</div>
</div>

### RPM {#ab5f18710c8016c42aa3dd429496513cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionPassManager llvm::sandboxir::BottomUpVec::RPM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The PM containing the pipeline of region passes.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/include/llvm/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-h">BottomUpVec.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/lib/transforms/vectorize/sandboxvectorizer/passes/bottomupvec-cpp">BottomUpVec.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
