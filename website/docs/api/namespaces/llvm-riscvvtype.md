---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvvtype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `RISCVVType` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVVType { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa18a6c74ee58139536f65e458f1c4586">isValidSEW</a> (unsigned SEW)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657b16aac49c151c563e6f5785811803">isValidLMUL</a> (unsigned LMUL, bool Fractional)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3636219b4d0045029530c6a16c160dc">encodeVTYPE</a> (RISCVII::VLMUL VLMUL, unsigned SEW, bool TailAgnostic, bool MaskAgnostic)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12465125c9315bf864c53298cccde08a">getVLMUL</a> (unsigned VType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5144889af710ec49f5eeff7be79e671d">decodeVLMUL</a> (RISCVII::VLMUL VLMUL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b192af1b1d40bfec9bec062af85ed5b">encodeLMUL</a> (unsigned LMUL, bool Fractional)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a291f15cffaa5063b9056d0160413bc82">decodeVSEW</a> (unsigned VSEW)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9335bf4c28fd800cc0225a1aad37ba6b">encodeSEW</a> (unsigned SEW)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5af8d664535a4bfbb71f0243ed9ae3a">getSEW</a> (unsigned VType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08cfea4b8c9e0a6118dc031cafeb0773">isTailAgnostic</a> (unsigned VType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc0d6840d44bc9348088a786932fc68">isMaskAgnostic</a> (unsigned VType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acab957b7266a5cb7bb0a69c3d1277397">printVType</a> (unsigned VType, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c33217fc9f7cae7a19701e421dc70f">getSEWLMULRatio</a> (unsigned SEW, RISCVII::VLMUL VLMul)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8d57c058770de811ad0fafc3a8b1ce4">getSameRatioLMUL</a> (unsigned SEW, RISCVII::VLMUL VLMUL, unsigned EEW)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; unsigned, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f772560fe4772399488fdc4ec6e973">getEMULEqualsEEWDivSEWTimesLMUL</a> (unsigned Log2EEW, const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return EMUL = (EEW / SEW) * LMUL where EEW comes from Log2EEW and LMUL and SEW are from the TSFlags of MI. <a href="#a19f772560fe4772399488fdc4ec6e973">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### decodeVLMUL() {#a5144889af710ec49f5eeff7be79e671d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, bool &gt; llvm::RISCVVType::decodeVLMUL (<a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a> VLMUL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvtargetparser-cpp">RISCVTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1ca1fc4732c22ad534f1cec77512aa4c451">llvm::RISCVII::LMUL_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1cafc3cf026a9a458e993d77f9d723cffe7">llvm::RISCVII::LMUL_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1ca81b84a0b11f1c29695dbf7765f8ceaa7">llvm::RISCVII::LMUL_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1cae7fe853f54d8e8aaf63568ed61da11e0">llvm::RISCVII::LMUL_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1caf5395daef0a34ae8d78919a587eee448">llvm::RISCVII::LMUL_F2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1caea5ed9248acd465f986c64e15db529e5">llvm::RISCVII::LMUL_F4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1ca61d90764106d2ac6346f4bc1ae1bd3fd">llvm::RISCVII::LMUL_F8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a436965f98f9e4301e33096c32ed6dbd2">llvm::RISCVInstrInfo::copyPhysRegVector</a>, <a href="#a19f772560fe4772399488fdc4ec6e973">getEMULEqualsEEWDivSEWTimesLMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a601135659272829d63f02580f4559995">llvm::RISCVTargetLowering::getLMULCost</a>, <a href="#a51c33217fc9f7cae7a19701e421dc70f">getSEWLMULRatio</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#acdb094fc50fe7940c520020f9008aa2f">llvm::RISCVTargetLowering::isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#afe7727717d0a490a4f48ad5b8e1779b7">anonymous{RISCVInsertVSETVLI.cpp}::isLMUL1OrSmaller</a>, <a href="#acab957b7266a5cb7bb0a69c3d1277397">printVType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#af390be4480c0588fa6c3fc6cd05e4166">llvm::RISCVDAGToDAGISel::selectVLXSEG</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a35a4f3715a02bc5b5d9ced3b5324f439">llvm::RISCVDAGToDAGISel::selectVSXSEG</a>.</p>

</div>
</div>

### decodeVSEW() {#a291f15cffaa5063b9056d0160413bc82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVVType::decodeVSEW (unsigned VSEW)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="#af5af8d664535a4bfbb71f0243ed9ae3a">getSEW</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a97a91b8b1f7d203b918218d0db9cec5d">llvm::RISCVDAGToDAGISel::selectVSETVLI</a>.</p>

</div>
</div>

### encodeLMUL() {#a7b192af1b1d40bfec9bec062af85ed5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVII::VLMUL llvm::RISCVVType::encodeLMUL (unsigned LMUL, bool Fractional)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a657b16aac49c151c563e6f5785811803">isValidLMUL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>.</p>


<p>Referenced by <a href="#af8d57c058770de811ad0fafc3a8b1ce4">getSameRatioLMUL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a897f4bf6b373f935cca5183ce7d4fd78">lowerGetVectorLength</a>.</p>

</div>
</div>

### encodeSEW() {#a9335bf4c28fd800cc0225a1aad37ba6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVVType::encodeSEW (unsigned SEW)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa18a6c74ee58139536f65e458f1c4586">isValidSEW</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>.</p>


<p>Referenced by <a href="#ad3636219b4d0045029530c6a16c160dc">encodeVTYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a897f4bf6b373f935cca5183ce7d4fd78">lowerGetVectorLength</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a95bb2318cffbd613f244603838b30094">lowerVectorIntrinsicScalars</a>.</p>

</div>
</div>

### encodeVTYPE() {#ad3636219b4d0045029530c6a16c160dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVVType::encodeVTYPE (<a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a> VLMUL, unsigned SEW, bool TailAgnostic, bool MaskAgnostic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvtargetparser-cpp">RISCVTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9335bf4c28fd800cc0225a1aad37ba6b">encodeSEW</a> and <a href="#aa18a6c74ee58139536f65e458f1c4586">isValidSEW</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#a3af1ce05932756a9695dbe24512cb40e">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::encodeVTYPE</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a97a91b8b1f7d203b918218d0db9cec5d">llvm::RISCVDAGToDAGISel::selectVSETVLI</a>.</p>

</div>
</div>

### getEMULEqualsEEWDivSEWTimesLMUL() {#a19f772560fe4772399488fdc4ec6e973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, bool &gt; llvm::RISCVVType::getEMULEqualsEEWDivSEWTimesLMUL (unsigned Log2EEW, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return EMUL = (EEW / SEW) * LMUL where EEW comes from Log2EEW and LMUL and SEW are from the TSFlags of MI.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp">RISCVVLOptimizer.cpp</a>.</p>


<p>References <a href="#a5144889af710ec49f5eeff7be79e671d">decodeVLMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a7dd086d89a22b8e83abd3e687cd13a35">llvm::RISCVII::getLMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#af9dfac3d961f5f889f2c6d38ce89685f">llvm::RISCVII::getSEWOpNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#af957d09b67e374fee8d9cffe19567c3d">getOperandInfo</a>.</p>

</div>
</div>

### getSameRatioLMUL() {#af8d57c058770de811ad0fafc3a8b1ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; RISCVII::VLMUL &gt; llvm::RISCVVType::getSameRatioLMUL (unsigned SEW, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a> VLMUL, unsigned EEW)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvtargetparser-cpp">RISCVTargetParser.cpp</a>.</p>


<p>References <a href="#a7b192af1b1d40bfec9bec062af85ed5b">encodeLMUL</a>, <a href="#a51c33217fc9f7cae7a19701e421dc70f">getSEWLMULRatio</a> and <a href="#a657b16aac49c151c563e6f5785811803">isValidLMUL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp/#a29c512a9a215945f15f473648f57537c">adjustIncoming</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ad0d97c2779bb2264df1ceeac09052e5a">llvm::mca::getEEWAndEMUL</a>.</p>

</div>
</div>

### getSEW() {#af5af8d664535a4bfbb71f0243ed9ae3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVVType::getSEW (unsigned VType)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a>.</p>


<p>Reference <a href="#a291f15cffaa5063b9056d0160413bc82">decodeVSEW</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#aa4bfcbb7dbb18b0413a59da72b0d4a89">anonymous{RISCVInsertVSETVLI.cpp}::areCompatibleVTYPEs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvinstrumentmanager/#ae0185b56daf5bfb7ebff494d4ade9787">llvm::mca::RISCVInstrumentManager::createInstruments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#acec254d4fbb18621ee4d54f867af85f9">isConvertibleToVMV_V_V</a>, <a href="#acab957b7266a5cb7bb0a69c3d1277397">printVType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ab41df3f24906d7ac103c09ccc17a58ec">llvm::RISCVInstPrinter::printVTypeI</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#aa4ed778e7cf004e26e2bd53b5b5de8a1">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setVTYPE</a>.</p>

</div>
</div>

### getSEWLMULRatio() {#a51c33217fc9f7cae7a19701e421dc70f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVVType::getSEWLMULRatio (unsigned SEW, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a> VLMul)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvtargetparser-cpp">RISCVTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5144889af710ec49f5eeff7be79e671d">decodeVLMUL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#aa4bfcbb7dbb18b0413a59da72b0d4a89">anonymous{RISCVInsertVSETVLI.cpp}::areCompatibleVTYPEs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="#af8d57c058770de811ad0fafc3a8b1ce4">getSameRatioLMUL</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#ad78b447d6a130e6102f95a35c58bef9e">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getSEWLMULRatio</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a97a91b8b1f7d203b918218d0db9cec5d">llvm::RISCVDAGToDAGISel::selectVSETVLI</a>.</p>

</div>
</div>

### getVLMUL() {#a12465125c9315bf864c53298cccde08a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVII::VLMUL llvm::RISCVVType::getVLMUL (unsigned VType)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#aa4bfcbb7dbb18b0413a59da72b0d4a89">anonymous{RISCVInsertVSETVLI.cpp}::areCompatibleVTYPEs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvinstrumentmanager/#ae0185b56daf5bfb7ebff494d4ade9787">llvm::mca::RISCVInstrumentManager::createInstruments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#acec254d4fbb18621ee4d54f867af85f9">isConvertibleToVMV_V_V</a>, <a href="#acab957b7266a5cb7bb0a69c3d1277397">printVType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ab41df3f24906d7ac103c09ccc17a58ec">llvm::RISCVInstPrinter::printVTypeI</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#aa4ed778e7cf004e26e2bd53b5b5de8a1">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setVTYPE</a>.</p>

</div>
</div>

### isMaskAgnostic() {#a7dc0d6840d44bc9348088a786932fc68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVVType::isMaskAgnostic (unsigned VType)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#aa4bfcbb7dbb18b0413a59da72b0d4a89">anonymous{RISCVInsertVSETVLI.cpp}::areCompatibleVTYPEs</a>, <a href="#acab957b7266a5cb7bb0a69c3d1277397">printVType</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#aa4ed778e7cf004e26e2bd53b5b5de8a1">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setVTYPE</a>.</p>

</div>
</div>

### isTailAgnostic() {#a08cfea4b8c9e0a6118dc031cafeb0773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVVType::isTailAgnostic (unsigned VType)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#aa4bfcbb7dbb18b0413a59da72b0d4a89">anonymous{RISCVInsertVSETVLI.cpp}::areCompatibleVTYPEs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#acec254d4fbb18621ee4d54f867af85f9">isConvertibleToVMV_V_V</a>, <a href="#acab957b7266a5cb7bb0a69c3d1277397">printVType</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#aa4ed778e7cf004e26e2bd53b5b5de8a1">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setVTYPE</a>.</p>

</div>
</div>

### isValidLMUL() {#a657b16aac49c151c563e6f5785811803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVVType::isValidLMUL (unsigned LMUL, bool Fractional)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>.</p>


<p>Referenced by <a href="#a7b192af1b1d40bfec9bec062af85ed5b">encodeLMUL</a> and <a href="#af8d57c058770de811ad0fafc3a8b1ce4">getSameRatioLMUL</a>.</p>

</div>
</div>

### isValidSEW() {#aa18a6c74ee58139536f65e458f1c4586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVVType::isValidSEW (unsigned SEW)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#abe6772bd0f8b4b1bc3186473a7205dfe">llvm::RISCVInstrInfo::createMIROperandComment</a>, <a href="#a9335bf4c28fd800cc0225a1aad37ba6b">encodeSEW</a>, <a href="#ad3636219b4d0045029530c6a16c160dc">encodeVTYPE</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a6643db423ad018f2a7375b8f46e439af">llvm::RISCVInstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### printVType() {#acab957b7266a5cb7bb0a69c3d1277397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RISCVVType::printVType (unsigned VType, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvtargetparser-cpp">RISCVTargetParser.cpp</a>.</p>


<p>References <a href="#a5144889af710ec49f5eeff7be79e671d">decodeVLMUL</a>, <a href="#af5af8d664535a4bfbb71f0243ed9ae3a">getSEW</a>, <a href="#a12465125c9315bf864c53298cccde08a">getVLMUL</a>, <a href="#a7dc0d6840d44bc9348088a786932fc68">isMaskAgnostic</a> and <a href="#a08cfea4b8c9e0a6118dc031cafeb0773">isTailAgnostic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#abe6772bd0f8b4b1bc3186473a7205dfe">llvm::RISCVInstrInfo::createMIROperandComment</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a5c67f50a9eeeeebe54d2cb8393b3d956">anonymous{RISCVAsmParser.cpp}::RISCVOperand::print</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ab41df3f24906d7ac103c09ccc17a58ec">llvm::RISCVInstPrinter::printVTypeI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvtargetparser-h">RISCVTargetParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp">RISCVVLOptimizer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvtargetparser-cpp">RISCVTargetParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
