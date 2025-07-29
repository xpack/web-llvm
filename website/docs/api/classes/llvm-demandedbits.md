---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/demandedbits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DemandedBits` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DemandedBits { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">llvm/Analysis/DemandedBits.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c02558c64850cc22b32db512b994066">DemandedBits</a> (Function &amp;F, AssumptionCache &amp;AC, DominatorTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35c645afbcec5f66b70f92c4cd8e8be4">getDemandedBits</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the bits demanded from instruction I. <a href="#a35c645afbcec5f66b70f92c4cd8e8be4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34469f29a61b3bcb61f8e2a9af25be65">getDemandedBits</a> (Use *U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the bits demanded from use U. <a href="#a34469f29a61b3bcb61f8e2a9af25be65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c32d3fae56332d1061a12cf1a3f3d7">isInstructionDead</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if, during analysis, I could not be reached. <a href="#ab4c32d3fae56332d1061a12cf1a3f3d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdfa4615d4c528925ba6490398cc54af">isUseDead</a> (Use *U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether this use is dead by means of not having any demanded bits. <a href="#abdfa4615d4c528925ba6490398cc54af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d9c0e9003a093505555e8051a6c7c91">print</a> (raw_ostream &amp;OS)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aac114e9867cfa136207d3f6de225ec">performAnalysis</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4f6a38ef244dd0ce8b7c192b6bc8716">determineLiveOperandBits</a> (const Instruction *UserI, const Value *Val, unsigned OperandNo, const APInt &amp;AOut, APInt &amp;AB, KnownBits &amp;Known, KnownBits &amp;Known2, bool &amp;KnownBitsComputed)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab42d28870569bb48318ee1e37a908e8c">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b8a3bcd0f1a07cae6634ddbfb4fad9">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a040ec2fdd1da12ed25b73e116f05d76c">DT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac765530164b55965a6e5b8857b0b3736">Analyzed</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af03edbc565188cf2cfc7e8dc42e6e76e">Visited</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a3cee048486397e62c5d6ae772835c">AliveBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2101b708831c488be1feac94dff010e">DeadUses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe7a48a211004f16170900dba49e625">determineLiveOperandBitsAdd</a> (unsigned OperandNo, const APInt &amp;AOut, const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute alive bits of one addition operand from alive output and known operand bits. <a href="#a4fe7a48a211004f16170900dba49e625">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5a4fedee642c9e9d2323ea22d7ae1cd">determineLiveOperandBitsSub</a> (unsigned OperandNo, const APInt &amp;AOut, const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute alive bits of one subtraction operand from alive output and known operand bits. <a href="#ab5a4fedee642c9e9d2323ea22d7ae1cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DemandedBits() {#a9c02558c64850cc22b32db512b994066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DemandedBits::DemandedBits (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDemandedBits() {#a35c645afbcec5f66b70f92c4cd8e8be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt DemandedBits::getDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the bits demanded from instruction I.</p>


<p>For vector instructions individual vector elements are not distinguished: A bit is demanded if it is demanded for any of the vector elements. The size of the return value corresponds to the type size in bits of the scalar type.</p>


<p>Instructions that do not have integer or vector of integer type are accepted, but will always produce a mask with all bits set.</p>


<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a34469f29a61b3bcb61f8e2a9af25be65">getDemandedBits</a> and <a href="#a0d9c0e9003a093505555e8051a6c7c91">print</a>.</p>

</div>
</div>

### getDemandedBits() {#a34469f29a61b3bcb61f8e2a9af25be65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt DemandedBits::getDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the bits demanded from use U.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="#a35c645afbcec5f66b70f92c4cd8e8be4">getDemandedBits</a>, <a href="#abdfa4615d4c528925ba6490398cc54af">isUseDead</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### isInstructionDead() {#ab4c32d3fae56332d1061a12cf1a3f3d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DemandedBits::isInstructionDead (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if, during analysis, I could not be reached.</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp/#a58c352ad903fb7fbe5fcbada4bce6551">isAlwaysLive</a>.</p>

</div>
</div>

### isUseDead() {#abdfa4615d4c528925ba6490398cc54af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DemandedBits::isUseDead (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether this use is dead by means of not having any demanded bits.</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp/#a58c352ad903fb7fbe5fcbada4bce6551">isAlwaysLive</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>.</p>


<p>Referenced by <a href="#a34469f29a61b3bcb61f8e2a9af25be65">getDemandedBits</a>.</p>

</div>
</div>

### print() {#a0d9c0e9003a093505555e8051a6c7c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DemandedBits::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a35c645afbcec5f66b70f92c4cd8e8be4">getDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### determineLiveOperandBits() {#ad4f6a38ef244dd0ce8b7c192b6bc8716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DemandedBits::determineLiveOperandBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UserI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, unsigned OperandNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; AOut, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; AB, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known2, bool &amp; KnownBitsComputed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a>.</p>

</div>
</div>

### performAnalysis() {#a5aac114e9867cfa136207d3f6de225ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DemandedBits::performAnalysis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#a19b8a3bcd0f1a07cae6634ddbfb4fad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; llvm::DemandedBits::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>.</p>

</div>
</div>

### AliveBits {#ac7a3cee048486397e62c5d6ae772835c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Instruction *, APInt&gt; llvm::DemandedBits::AliveBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>.</p>

</div>
</div>

### Analyzed {#ac765530164b55965a6e5b8857b0b3736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DemandedBits::Analyzed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>.</p>

</div>
</div>

### DeadUses {#af2101b708831c488be1feac94dff010e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Use *, 16&gt; llvm::DemandedBits::DeadUses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>.</p>

</div>
</div>

### DT {#a040ec2fdd1da12ed25b73e116f05d76c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; llvm::DemandedBits::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>.</p>

</div>
</div>

### F {#ab42d28870569bb48318ee1e37a908e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; llvm::DemandedBits::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>.</p>

</div>
</div>

### Visited {#af03edbc565188cf2cfc7e8dc42e6e76e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction*, 32&gt; llvm::DemandedBits::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### determineLiveOperandBitsAdd() {#a4fe7a48a211004f16170900dba49e625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt DemandedBits::determineLiveOperandBitsAdd (unsigned OperandNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; AOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute alive bits of one addition operand from alive output and known operand bits.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp/#ab0b0d4186175ae749e0fa20fca628699">determineLiveOperandBitsAddCarry</a>.</p>

</div>
</div>

### determineLiveOperandBitsSub() {#ab5a4fedee642c9e9d2323ea22d7ae1cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt DemandedBits::determineLiveOperandBitsSub (unsigned OperandNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; AOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute alive bits of one subtraction operand from alive output and known operand bits.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a>, definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp/#ab0b0d4186175ae749e0fa20fca628699">determineLiveOperandBitsAddCarry</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">DemandedBits.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp">DemandedBits.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
