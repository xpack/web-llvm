---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/irsimilarity/irsimilaritycandidate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IRSimilarityCandidate` Class

<p>This is a class that wraps a range of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> from one point to another in the vector of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>, which is a region of the program. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::IRSimilarity::IRSimilarityCandidate { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">llvm/Analysis/IRSimilarityIdentifier.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa35442169d90583b71e568b9a27690b0">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/simple-ilist/#aaa26237d7a40d3f5207b306d693babbd">IRInstructionDataList::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a> (unsigned StartIdx, unsigned Len, IRInstructionData *FirstInstIt, IRInstructionData *LastInstIt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8239e67766cc20df91095f93133318">operator&lt;</a> (const IRSimilarityCandidate &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a84e5cc221f28b26321adf56f0bb05">createCanonicalRelationFrom</a> (IRSimilarityCandidate &amp;SourceCand, DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;ToSourceMapping, DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;FromSourceMapping)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a mapping for the value numbering of the calling <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>, to a different separate set of numbers, based on the canonical ordering in <span class="doxyComputerOutput">SourceCand</span>. <a href="#a21a84e5cc221f28b26321adf56f0bb05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1383f060f0db621671d555250dd7f3">createCanonicalRelationFrom</a> (IRSimilarityCandidate &amp;SourceCand, DenseMap&lt; unsigned, unsigned &gt; &amp;OneToOne, DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;ToSourceMapping, DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;FromSourceMapping)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a mapping for the value numbering of the calling <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>, to a different separate set of numbers, based on the canonical ordering in <span class="doxyComputerOutput">SourceCand</span>. <a href="#aee1383f060f0db621671d555250dd7f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a519b49635e958003f142b5bc5277cadf">createCanonicalRelationFrom</a> (IRSimilarityCandidate &amp;SourceCand, IRSimilarityCandidate &amp;SourceCandLarge, IRSimilarityCandidate &amp;TargetCandLarge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a mapping for the value numbering of the calling <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>, to a different separate set of numbers, based on the canonical ordering in <span class="doxyComputerOutput">SourceCand</span>. <a href="#a519b49635e958003f142b5bc5277cadf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93f165686cbc3ed0554ec8431f9c9b21">getBasicBlocks</a> (DenseSet&lt; BasicBlock * &gt; &amp;BBSet) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54182dd4333475d439513da05d634aad">getBasicBlocks</a> (DenseSet&lt; BasicBlock * &gt; &amp;BBSet, SmallVector&lt; BasicBlock * &gt; &amp;BBList) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee0f83ee06a7cddc9644e23c6f34d1d">getLength</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada960ccf6a96ca62ce5db3af1b7bf7f5">getStartIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd2e1a8a3658307e8c0d87a153d8c24">getEndIdx</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79c3d65a39c004b7517e811db43522c">front</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc4eeab876adfaa7a403fd1a15e9d94">back</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa77784ba0d88967a5cf2d657accb01c5">frontInstruction</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1655b1e16471852e14153554570a0f75">backInstruction</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae22d915fa9ab51e40345773c663ebdeb">getStartBB</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa741eaf03ea033a9a1a3b669d0321983">getEndBB</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc4581d38f96e5833319a3d1ad24c1c">getFunction</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ffe65f27fa3355ffd96fbcd0bb1cbb9">getGVN</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the positive number associated with <span class="doxyComputerOutput">V</span> if it has been mapped. <a href="#a3ffe65f27fa3355ffd96fbcd0bb1cbb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbaf4d24ed4249c75741662ebfa1f43">fromGVN</a> (unsigned Num)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> associate with <span class="doxyComputerOutput">Num</span> if it exists. <a href="#a9fbaf4d24ed4249c75741662ebfa1f43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b404a6e77e0349378afa8ae7ce0e4a">getCanonicalNum</a> (unsigned N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the canonical number from the global value number <span class="doxyComputerOutput">N</span> stored in the candidate. <a href="#ae6b404a6e77e0349378afa8ae7ce0e4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c1194a6f6117d8fb7c77e42b70f048">fromCanonicalNum</a> (unsigned N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the global value number from the canonical number <span class="doxyComputerOutput">N</span> stored in the candidate. <a href="#ae9c1194a6f6117d8fb7c77e42b70f048">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa35442169d90583b71e568b9a27690b0">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ba54e3f1226fa08acedeff0ea6ce87">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa35442169d90583b71e568b9a27690b0">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324b374cfba3764268b25644adb7b24d">end</a> () const</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab09a5afbb6f8a65f3e1ef77e81bb834a">ValueToNumber</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Numbering structures

Stores the mapping of the value to the number assigned to it in the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>. <a href="#ab09a5afbb6f8a65f3e1ef77e81bb834a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5805815e8db83987684fd0a32e6aef57">NumberToValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the mapping of the number to the value assigned this number. <a href="#a5805815e8db83987684fd0a32e6aef57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ba60f8014d23e7fe9d4bd7952587c29">NumberToCanonNum</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the mapping of a value's number to canonical numbering in the candidate's respective similarity group. <a href="#a0ba60f8014d23e7fe9d4bd7952587c29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67405688af48e183d685ded7c7259de7">CanonNumToNumber</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the mapping of canonical number in the candidate's respective similarity group to a value number. <a href="#a67405688af48e183d685ded7c7259de7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2251823ac08db0d52089ce66740b94bd">StartIdx</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The start index of this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> in the instruction list. <a href="#a2251823ac08db0d52089ce66740b94bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9849d2ac15c41fd593c14d0c0b633259">Len</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of instructions in this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>. <a href="#a9849d2ac15c41fd593c14d0c0b633259">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae77abf4493bd521c4a79177e51bde21">FirstInst</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The first instruction in this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>. <a href="#aae77abf4493bd521c4a79177e51bde21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a943be76ed9835a47e7dfb5c998775ab3">LastInst</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The last instruction in this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>. <a href="#a943be76ed9835a47e7dfb5c998775ab3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23d2b4941adb672f1a2ce945399065e3">isSimilar</a> (const IRSimilarityCandidate &amp;A, const IRSimilarityCandidate &amp;B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7090e2692a1125bbf970b981dbe21ce">compareStructure</a> (const IRSimilarityCandidate &amp;A, const IRSimilarityCandidate &amp;B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d2b8c755a8e7b54f4680d27cd40d244">compareStructure</a> (const IRSimilarityCandidate &amp;A, const IRSimilarityCandidate &amp;B, DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;ValueNumberMappingA, DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;ValueNumberMappingB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaccf8f3711195931b9eaaa317eb637c">compareNonCommutativeOperandMapping</a> (OperandMapping A, OperandMapping B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare the operands in <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> and check that the current mapping of global value numbers from <span class="doxyComputerOutput">A</span> to <span class="doxyComputerOutput">B</span> and <span class="doxyComputerOutput">B</span> to \A is consistent. <a href="#afaccf8f3711195931b9eaaa317eb637c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6bd5545903e7ba1de9af2e7d0d2a4a">compareCommutativeOperandMapping</a> (OperandMapping A, OperandMapping B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare the operands in <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> and check that the current mapping of global value numbers from <span class="doxyComputerOutput">A</span> to <span class="doxyComputerOutput">B</span> and <span class="doxyComputerOutput">B</span> to \A is consistent given that the operands are commutative. <a href="#afe6bd5545903e7ba1de9af2e7d0d2a4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad01245fba0cda069bb7ce68a9296a4">compareAssignmentMapping</a> (const unsigned InstValA, const unsigned &amp;InstValB, DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;ValueNumberMappingA, DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;ValueNumberMappingB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare the GVN of the assignment value in corresponding instructions in IRSimilarityCandidates <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> and check that there exists a mapping between the values and replaces the mapping with a one-to-one value if needed. <a href="#a7ad01245fba0cda069bb7ce68a9296a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a8f00e0169503c48f26bffcf4d6646">checkRelativeLocations</a> (RelativeLocMapping A, RelativeLocMapping B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare the relative locations in <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> and check that the distances match if both locations are contained in the region, and that the branches both point outside the region if they do not. <a href="#aa8a8f00e0169503c48f26bffcf4d6646">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab887db0898db0bfae23199acc51e4f48">createCanonicalMappingFor</a> (IRSimilarityCandidate &amp;CurrCand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a mapping from the value numbering to a different separate set of numbers. <a href="#ab887db0898db0bfae23199acc51e4f48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad02bc9bd1feca133eb84b3618e93fb37">overlap</a> (const IRSimilarityCandidate &amp;A, const IRSimilarityCandidate &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare the start and end indices of the two IRSimilarityCandidates for whether they overlap. <a href="#ad02bc9bd1feca133eb84b3618e93fb37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is a class that wraps a range of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> from one point to another in the vector of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>, which is a region of the program.</p>


<p>It is also responsible for defining the structure within this region of instructions.</p>


<p>The structure of a region is defined through a value numbering system assigned to each unique value in a region at the creation of the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p>


<p>For example, for each <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> we add a mapping for each new value seen in that <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. IR: Mapping Added: add1 = add i32 a, c1 add1 -&gt; 3, a -&gt; 1, c1 -&gt; 2 add2 = add i32 a, %1 add2 -&gt; 4 add3 = add i32 c2, c1 add3 -&gt; 6, c2 -&gt; 5</p>


<p>We can compare IRSimilarityCandidates against one another. The <a href="#a23d2b4941adb672f1a2ce945399065e3">isSimilar</a> function compares each <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> against one another and if we have the same sequences of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> that would create the same hash, we have similar IRSimilarityCandidates.</p>


<p>We can also compare the structure of IRSimilarityCandidates. If we can create a mapping of registers in the region contained by one <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to the region contained by different <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>, they can be considered structurally similar.</p>


<p>IRSimilarityCandidate1: IRSimilarityCandidate2: add1 = add i32 a, b add1 = add i32 d, e add2 = add i32 a, c add2 = add i32 d, f add3 = add i32 c1, c2 add3 = add i32 c3, c4</p>


<p>Can have the following mapping from candidate to candidate of: a -&gt; d, b -&gt; e, c -&gt; f, c1 -&gt; c3, c2 -&gt; c4 and can be considered similar.</p>


<p>IRSimilarityCandidate1: IRSimilarityCandidate2: add1 = add i32 a, b add1 = add i32 d, c4 add2 = add i32 a, c add2 = add i32 d, f add3 = add i32 c1, c2 add3 = add i32 c3, c4</p>


<p>We cannot create the same mapping since the use of c4 is not used in the same way as b or c2.</p>


<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#aa35442169d90583b71e568b9a27690b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IRSimilarity::IRSimilarityCandidate::iterator =  IRInstructionDataList::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IRSimilarityCandidate() {#ae35aff2dc6fcdec60f53cdcfabea59f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRSimilarityCandidate::IRSimilarityCandidate (unsigned StartIdx, unsigned Len, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> * FirstInstIt, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> * LastInstIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">StartIdx</td>
<td class="doxyParamItemDescription"><p>- The starting location of the region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>- The length of the region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FirstInstIt</td>
<td class="doxyParamItemDescription"><p>- The starting <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> of the region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LastInstIt</td>
<td class="doxyParamItemDescription"><p>- The ending <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> of the region.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a93f165686cbc3ed0554ec8431f9c9b21">getBasicBlocks</a>.</p>


<p>Referenced by <a href="#ab7090e2692a1125bbf970b981dbe21ce">compareStructure</a>, <a href="#a2d2b8c755a8e7b54f4680d27cd40d244">compareStructure</a>, <a href="#ab887db0898db0bfae23199acc51e4f48">createCanonicalMappingFor</a>, <a href="#a21a84e5cc221f28b26321adf56f0bb05">createCanonicalRelationFrom</a>, <a href="#aee1383f060f0db621671d555250dd7f3">createCanonicalRelationFrom</a>, <a href="#a519b49635e958003f142b5bc5277cadf">createCanonicalRelationFrom</a>, <a href="#a23d2b4941adb672f1a2ce945399065e3">isSimilar</a>, <a href="#a9c8239e67766cc20df91095f93133318">operator&lt;</a> and <a href="#ad02bc9bd1feca133eb84b3618e93fb37">overlap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a9c8239e67766cc20df91095f93133318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRSimilarityCandidate::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; RHS)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">RHS</td>
<td class="doxyParamItemDescription"><p>-The <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to compare against</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> is occurs after the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> in the program.</p></dd>
</dl>


<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>References <a href="#ada960ccf6a96ca62ce5db3af1b7bf7f5">getStartIdx</a>, <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#a8cc4eeab876adfaa7a403fd1a15e9d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData * llvm::IRSimilarity::IRSimilarityCandidate::back ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The last <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</p></dd>
</dl>


<p>Definition at line 938 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#a324b374cfba3764268b25644adb7b24d">end</a>.</p>

</div>
</div>

### backInstruction() {#a1655b1e16471852e14153554570a0f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::IRSimilarity::IRSimilarityCandidate::backInstruction ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The last <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></p></dd>
</dl>


<p>Definition at line 943 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### begin() {#ac8ba54e3f1226fa08acedeff0ea6ce87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::IRSimilarity::IRSimilarityCandidate::begin ()</td>
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



<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="#af79c3d65a39c004b7517e811db43522c">front</a>.</p>

</div>
</div>

### createCanonicalRelationFrom() {#a21a84e5cc221f28b26321adf56f0bb05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRSimilarityCandidate::createCanonicalRelationFrom (<a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; SourceCand, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; ToSourceMapping, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; FromSourceMapping)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a mapping for the value numbering of the calling <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>, to a different separate set of numbers, based on the canonical ordering in <span class="doxyComputerOutput">SourceCand</span>.</p>


<p>These are defined based on the found mappings in <span class="doxyComputerOutput">ToSourceMapping</span> and <span class="doxyComputerOutput">FromSourceMapping</span>. Both of these relationships should have the same information, just in opposite directions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] SourceCand</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to create a canonical numbering from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ToSourceMapping</td>
<td class="doxyParamItemDescription"><p>- The mapping of value numbers from this candidate to <span class="doxyComputerOutput">SourceCand</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FromSourceMapping</td>
<td class="doxyParamItemDescription"><p>- The mapping of value numbers from <span class="doxyComputerOutput">SoureCand</span> to this candidate.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 848 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 1005 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a836d9cba6deced0bb1fa7333ce5afd3a">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="#ae9c1194a6f6117d8fb7c77e42b70f048">fromCanonicalNum</a>, <a href="#a9fbaf4d24ed4249c75741662ebfa1f43">fromGVN</a>, <a href="#aa77784ba0d88967a5cf2d657accb01c5">frontInstruction</a>, <a href="#a93f165686cbc3ed0554ec8431f9c9b21">getBasicBlocks</a>, <a href="#ae6b404a6e77e0349378afa8ae7ce0e4a">getCanonicalNum</a>, <a href="#a3ffe65f27fa3355ffd96fbcd0bb1cbb9">getGVN</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="#ae22d915fa9ab51e40345773c663ebdeb">getStartBB</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>.</p>

</div>
</div>

### createCanonicalRelationFrom() {#aee1383f060f0db621671d555250dd7f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IRSimilarity::IRSimilarityCandidate::createCanonicalRelationFrom (<a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; SourceCand, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt; &amp; OneToOne, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; ToSourceMapping, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; FromSourceMapping)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a mapping for the value numbering of the calling <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>, to a different separate set of numbers, based on the canonical ordering in <span class="doxyComputerOutput">SourceCand</span>.</p>


<p>These are defined based on the found mappings in <span class="doxyComputerOutput">ToSourceMapping</span> and <span class="doxyComputerOutput">FromSourceMapping</span>. Both of these relationships should have the same information, just in opposite directions. Uses the <span class="doxyComputerOutput">OneToOne</span> mapping from target candidate to <span class="doxyComputerOutput">SourceCand</span> GVNs to determine the mapping first for values with multiple mappings. This mapping is created by the ordering of operands in the instruction they are first seen in the candidates.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] SourceCand</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to create a canonical numbering from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OneToOne</td>
<td class="doxyParamItemDescription"><p>- A mapping of value numbers from candidate <span class="doxyComputerOutput">A</span> to candidate \B using the structure of the original instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ToSourceMapping</td>
<td class="doxyParamItemDescription"><p>- The mapping of value numbers from this candidate to <span class="doxyComputerOutput">SourceCand</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FromSourceMapping</td>
<td class="doxyParamItemDescription"><p>- The mapping of value numbers from <span class="doxyComputerOutput">SoureCand</span> to this candidate.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a>.</p>

</div>
</div>

### createCanonicalRelationFrom() {#a519b49635e958003f142b5bc5277cadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRSimilarityCandidate::createCanonicalRelationFrom (<a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; SourceCand, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; SourceCandLarge, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; TargetCandLarge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a mapping for the value numbering of the calling <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>, to a different separate set of numbers, based on the canonical ordering in <span class="doxyComputerOutput">SourceCand</span>.</p>


<p>These are defined based on the canonical mapping defined between <span class="doxyComputerOutput">SoureCandLarge</span> and <span class="doxyComputerOutput">TargetCandLarge</span>. These IRSimilarityCandidates are already structurally similar, and fully encapsulate the IRSimilarityCandidates in question. These are used as a "bridge" from the <span class="doxyComputerOutput">SourceCand</span> to the target.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] SourceCand</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to create a canonical numbering from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SoureCandLarge</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> fully containing <span class="doxyComputerOutput">SourceCand</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetCandLarge</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> fully containing this Candidate.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="#ae9c1194a6f6117d8fb7c77e42b70f048">fromCanonicalNum</a>, <a href="#a9fbaf4d24ed4249c75741662ebfa1f43">fromGVN</a>, <a href="#ae6b404a6e77e0349378afa8ae7ce0e4a">getCanonicalNum</a>, <a href="#a3ffe65f27fa3355ffd96fbcd0bb1cbb9">getGVN</a> and <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a>.</p>

</div>
</div>

### end() {#a324b374cfba3764268b25644adb7b24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::IRSimilarity::IRSimilarityCandidate::end ()</td>
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



<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="#a8cc4eeab876adfaa7a403fd1a15e9d94">back</a>.</p>

</div>
</div>

### fromCanonicalNum() {#ae9c1194a6f6117d8fb7c77e42b70f048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::IRSimilarity::IRSimilarityCandidate::fromCanonicalNum (unsigned N)</td>
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

<p>Find the global value number from the canonical number <span class="doxyComputerOutput">N</span> stored in the candidate.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p>- The canonical number to find the global vlaue number for.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An optional containing the value, and std::nullopt if it could not be found.</p></dd>
</dl>


<p>Definition at line 996 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a21a84e5cc221f28b26321adf56f0bb05">createCanonicalRelationFrom</a> and <a href="#a519b49635e958003f142b5bc5277cadf">createCanonicalRelationFrom</a>.</p>

</div>
</div>

### fromGVN() {#a9fbaf4d24ed4249c75741662ebfa1f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; llvm::IRSimilarity::IRSimilarityCandidate::fromGVN (unsigned Num)</td>
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

<p>Finds the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> associate with <span class="doxyComputerOutput">Num</span> if it exists.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Num</td>
<td class="doxyParamItemDescription"><p>- the number to find.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> associated with the number.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if not present.</p></dd>
</dl>


<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a21a84e5cc221f28b26321adf56f0bb05">createCanonicalRelationFrom</a> and <a href="#a519b49635e958003f142b5bc5277cadf">createCanonicalRelationFrom</a>.</p>

</div>
</div>

### front() {#af79c3d65a39c004b7517e811db43522c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData * llvm::IRSimilarity::IRSimilarityCandidate::front ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The first <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</p></dd>
</dl>


<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#ac8ba54e3f1226fa08acedeff0ea6ce87">begin</a>.</p>

</div>
</div>

### frontInstruction() {#aa77784ba0d88967a5cf2d657accb01c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::IRSimilarity::IRSimilarityCandidate::frontInstruction ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The first <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p></dd>
</dl>


<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#a21a84e5cc221f28b26321adf56f0bb05">createCanonicalRelationFrom</a>.</p>

</div>
</div>

### getBasicBlocks() {#a93f165686cbc3ed0554ec8431f9c9b21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IRSimilarity::IRSimilarityCandidate::getBasicBlocks (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BBSet)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] BBSet</td>
<td class="doxyParamItemDescription"><p>- The set to track the basic blocks.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#a21a84e5cc221f28b26321adf56f0bb05">createCanonicalRelationFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8b12ae89227758cb5684cc7cf25a7f43">findCostForOutputBlocks</a> and <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a>.</p>

</div>
</div>

### getBasicBlocks() {#a54182dd4333475d439513da05d634aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IRSimilarity::IRSimilarityCandidate::getBasicBlocks (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BBSet, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BBList)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] BBSet</td>
<td class="doxyParamItemDescription"><p>- The set to track the basic blocks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] BBList</td>
<td class="doxyParamItemDescription"><p>- A list in order of use to track the basic blocks.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getCanonicalNum() {#ae6b404a6e77e0349378afa8ae7ce0e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::IRSimilarity::IRSimilarityCandidate::getCanonicalNum (unsigned N)</td>
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

<p>Find the canonical number from the global value number <span class="doxyComputerOutput">N</span> stored in the candidate.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p>- The global value number to find the canonical number for.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An optional containing the value, and std::nullopt if it could not be found.</p></dd>
</dl>


<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a21a84e5cc221f28b26321adf56f0bb05">createCanonicalRelationFrom</a>, <a href="#a519b49635e958003f142b5bc5277cadf">createCanonicalRelationFrom</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a>.</p>

</div>
</div>

### getEndBB() {#aa741eaf03ea033a9a1a3b669d0321983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::IRSimilarity::IRSimilarityCandidate::getEndBB ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> ends in.</p></dd>
</dl>


<p>Definition at line 948 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>.</p>

</div>
</div>

### getEndIdx() {#a5fd2e1a8a3658307e8c0d87a153d8c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IRSimilarity::IRSimilarityCandidate::getEndIdx ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the end index of this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p></dd>
</dl>


<p>Definition at line 933 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp/#afe58a1278a6b1a8f254a740575a6a102">CheckLargerCands</a>.</p>

</div>
</div>

### getFunction() {#abfc4581d38f96e5833319a3d1ad24c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::IRSimilarity::IRSimilarityCandidate::getFunction ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> that the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> is located in.</p></dd>
</dl>


<p>Definition at line 951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a> and <a href="#ae22d915fa9ab51e40345773c663ebdeb">getStartBB</a>.</p>

</div>
</div>

### getGVN() {#a3ffe65f27fa3355ffd96fbcd0bb1cbb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::IRSimilarity::IRSimilarityCandidate::getGVN (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Finds the positive number associated with <span class="doxyComputerOutput">V</span> if it has been mapped.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] V</td>
<td class="doxyParamItemDescription"><p>- the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to find.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The positive number corresponding to the value.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if not present.</p></dd>
</dl>


<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a21a84e5cc221f28b26321adf56f0bb05">createCanonicalRelationFrom</a>, <a href="#a519b49635e958003f142b5bc5277cadf">createCanonicalRelationFrom</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a>.</p>

</div>
</div>

### getLength() {#a4ee0f83ee06a7cddc9644e23c6f34d1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IRSimilarity::IRSimilarityCandidate::getLength ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the number of instructions in this Candidate.</p></dd>
</dl>


<p>Definition at line 927 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### getStartBB() {#ae22d915fa9ab51e40345773c663ebdeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::IRSimilarity::IRSimilarityCandidate::getStartBB ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> starts in.</p></dd>
</dl>


<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>.</p>


<p>Referenced by <a href="#a21a84e5cc221f28b26321adf56f0bb05">createCanonicalRelationFrom</a>, <a href="#abfc4581d38f96e5833319a3d1ad24c1c">getFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a>.</p>

</div>
</div>

### getStartIdx() {#ada960ccf6a96ca62ce5db3af1b7bf7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IRSimilarity::IRSimilarityCandidate::getStartIdx ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the start index of this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p></dd>
</dl>


<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp/#afe58a1278a6b1a8f254a740575a6a102">CheckLargerCands</a> and <a href="#a9c8239e67766cc20df91095f93133318">operator&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CanonNumToNumber {#a67405688af48e183d685ded7c7259de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; llvm::IRSimilarity::IRSimilarityCandidate::CanonNumToNumber</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores the mapping of canonical number in the candidate's respective similarity group to a value number.</p>

<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### NumberToCanonNum {#a0ba60f8014d23e7fe9d4bd7952587c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; llvm::IRSimilarity::IRSimilarityCandidate::NumberToCanonNum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores the mapping of a value's number to canonical numbering in the candidate's respective similarity group.</p>

<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### NumberToValue {#a5805815e8db83987684fd0a32e6aef57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, Value *&gt; llvm::IRSimilarity::IRSimilarityCandidate::NumberToValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores the mapping of the number to the value assigned this number.</p>

<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### ValueToNumber {#ab09a5afbb6f8a65f3e1ef77e81bb834a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, unsigned&gt; llvm::IRSimilarity::IRSimilarityCandidate::ValueToNumber</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Numbering structures

Stores the mapping of the value to the number assigned to it in the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p>

<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FirstInst {#aae77abf4493bd521c4a79177e51bde21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData* llvm::IRSimilarity::IRSimilarityCandidate::FirstInst = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The first instruction in this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p>

<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### LastInst {#a943be76ed9835a47e7dfb5c998775ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData* llvm::IRSimilarity::IRSimilarityCandidate::LastInst = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The last instruction in this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p>

<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### Len {#a9849d2ac15c41fd593c14d0c0b633259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IRSimilarity::IRSimilarityCandidate::Len = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of instructions in this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p>

<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### StartIdx {#a2251823ac08db0d52089ce66740b94bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IRSimilarity::IRSimilarityCandidate::StartIdx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The start index of this <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> in the instruction list.</p>

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### checkRelativeLocations() {#aa8a8f00e0169503c48f26bffcf4d6646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRSimilarityCandidate::checkRelativeLocations (<a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irsimilaritycandidate/relativelocmapping">RelativeLocMapping</a> A, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irsimilaritycandidate/relativelocmapping">RelativeLocMapping</a> B)</td>
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

<p>Compare the relative locations in <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> and check that the distances match if both locations are contained in the region, and that the branches both point outside the region if they do not.</p>


<p>Example <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">entry:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %0, label %block_1, label %block_3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_0:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %0, label %block_1, label %block_2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %0, label %block_2, label %block_3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_2:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %1, label %block_1, label %block_4</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_3:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %2, label %block_2, label %block_5</span></span></div>

</div>


<p>If we compare the branches in block_0 and block_1 the relative values are 1 and 2 for both, so we consider this a match.</p>


<p>If we compare the branches in entry and block_0 the relative values are 2 and 3, and 1 and 2 respectively. Since these are not the same we do not consider them a match.</p>


<p>If we compare the branches in block_1 and block_2 the relative values are 1 and 2, and -1 and None respectively. As a result we do not consider these to be the same</p>


<p>If we compare the branches in block_2 and block_3 the relative values are -1 and None for both. We do consider these to be a match.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>- The first IRInstructionCandidate, relative location value, and incoming block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">B</td>
<td class="doxyParamItemDescription"><p>- The second IRInstructionCandidate, relative location value, and incoming block.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the relative locations match.</p></dd>
</dl>


<p>Declaration at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>.</p>


<p>Referenced by <a href="#a2d2b8c755a8e7b54f4680d27cd40d244">compareStructure</a>.</p>

</div>
</div>

### compareAssignmentMapping() {#a7ad01245fba0cda069bb7ce68a9296a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRSimilarityCandidate::compareAssignmentMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned InstValA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned &amp; InstValB, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; ValueNumberMappingA, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; ValueNumberMappingB)</td>
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

<p>Compare the GVN of the assignment value in corresponding instructions in IRSimilarityCandidates <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> and check that there exists a mapping between the values and replaces the mapping with a one-to-one value if needed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InstValA</td>
<td class="doxyParamItemDescription"><p>- The assignment GVN from the first <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InstValB</td>
<td class="doxyParamItemDescription"><p>- The assignment GVN from the second <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] ValueNumberMappingA</td>
<td class="doxyParamItemDescription"><p>- A mapping of value numbers from candidate <span class="doxyComputerOutput">A</span> to candidate \B.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] ValueNumberMappingB</td>
<td class="doxyParamItemDescription"><p>- A mapping of value numbers from candidate <span class="doxyComputerOutput">B</span> to candidate \A.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the IRSimilarityCandidates assignments are compatible.</p></dd>
</dl>


<p>Declaration at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a836d9cba6deced0bb1fa7333ce5afd3a">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::contains</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>.</p>


<p>Referenced by <a href="#a2d2b8c755a8e7b54f4680d27cd40d244">compareStructure</a>.</p>

</div>
</div>

### compareCommutativeOperandMapping() {#afe6bd5545903e7ba1de9af2e7d0d2a4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRSimilarityCandidate::compareCommutativeOperandMapping (<a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irsimilaritycandidate/operandmapping">OperandMapping</a> A, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irsimilaritycandidate/operandmapping">OperandMapping</a> B)</td>
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

<p>Compare the operands in <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> and check that the current mapping of global value numbers from <span class="doxyComputerOutput">A</span> to <span class="doxyComputerOutput">B</span> and <span class="doxyComputerOutput">B</span> to \A is consistent given that the operands are commutative.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>- The first IRInstructionCandidate, operand values, and current operand mappings to compare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">B</td>
<td class="doxyParamItemDescription"><p>- The second IRInstructionCandidate, operand values, and current operand mappings to compare.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the IRSimilarityCandidates operands are compatible.</p></dd>
</dl>


<p>Declaration at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp/#afbf484050e75f5876a5f490e2047e233">checkNumberingAndReplaceCommutative</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>.</p>


<p>Referenced by <a href="#a2d2b8c755a8e7b54f4680d27cd40d244">compareStructure</a>.</p>

</div>
</div>

### compareNonCommutativeOperandMapping() {#afaccf8f3711195931b9eaaa317eb637c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRSimilarityCandidate::compareNonCommutativeOperandMapping (<a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irsimilaritycandidate/operandmapping">OperandMapping</a> A, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irsimilaritycandidate/operandmapping">OperandMapping</a> B)</td>
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

<p>Compare the operands in <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> and check that the current mapping of global value numbers from <span class="doxyComputerOutput">A</span> to <span class="doxyComputerOutput">B</span> and <span class="doxyComputerOutput">B</span> to \A is consistent.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>- The first IRInstructionCandidate, operand values, and current operand mappings to compare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">B</td>
<td class="doxyParamItemDescription"><p>- The second IRInstructionCandidate, operand values, and current operand mappings to compare.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the IRSimilarityCandidates operands are compatible.</p></dd>
</dl>


<p>Declaration at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp/#a01e8f5742b534af36f06b7378e647d78">checkNumberingAndReplace</a>.</p>


<p>Referenced by <a href="#a2d2b8c755a8e7b54f4680d27cd40d244">compareStructure</a>.</p>

</div>
</div>

### compareStructure() {#ab7090e2692a1125bbf970b981dbe21ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRSimilarityCandidate::compareStructure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; B)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] A</td>
<td class="doxyParamItemDescription"><p>- The first IRInstructionCandidate to compare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] B</td>
<td class="doxyParamItemDescription"><p>- The second IRInstructionCandidate to compare.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True when every <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> in <span class="doxyComputerOutput">A</span> is structurally similar to <span class="doxyComputerOutput">B</span>.</p></dd>
</dl>


<p>Declaration at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ab7090e2692a1125bbf970b981dbe21ce">compareStructure</a> and <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a>.</p>


<p>Referenced by <a href="#ab7090e2692a1125bbf970b981dbe21ce">compareStructure</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp/#ad34b0969cb7181bf8847c796b0e52825">findCandidateStructures</a>.</p>

</div>
</div>

### compareStructure() {#a2d2b8c755a8e7b54f4680d27cd40d244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRSimilarityCandidate::compareStructure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; ValueNumberMappingA, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; ValueNumberMappingB)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] A</td>
<td class="doxyParamItemDescription"><p>- The first IRInstructionCandidate to compare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] B</td>
<td class="doxyParamItemDescription"><p>- The second IRInstructionCandidate to compare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] ValueNumberMappingA</td>
<td class="doxyParamItemDescription"><p>- A mapping of value numbers from candidate <span class="doxyComputerOutput">A</span> to candidate \B.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] ValueNumberMappingB</td>
<td class="doxyParamItemDescription"><p>- A mapping of value numbers from candidate <span class="doxyComputerOutput">B</span> to candidate \A.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True when every <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> in <span class="doxyComputerOutput">A</span> is structurally similar to <span class="doxyComputerOutput">B</span>.</p></dd>
</dl>


<p>Declaration at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aa8a8f00e0169503c48f26bffcf4d6646">checkRelativeLocations</a>, <a href="#a7ad01245fba0cda069bb7ce68a9296a4">compareAssignmentMapping</a>, <a href="#afe6bd5545903e7ba1de9af2e7d0d2a4a">compareCommutativeOperandMapping</a>, <a href="#afaccf8f3711195931b9eaaa317eb637c">compareNonCommutativeOperandMapping</a>, <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#ad7518d710d81c7c4c04cc6a61e7d65bc">llvm::IRSimilarity::isClose</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>

</div>
</div>

### createCanonicalMappingFor() {#ab887db0898db0bfae23199acc51e4f48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRSimilarityCandidate::createCanonicalMappingFor (<a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; CurrCand)</td>
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

<p>Create a mapping from the value numbering to a different separate set of numbers.</p>


<p>This will serve as a guide for relating one candidate to another. The canonical number gives use the ability identify which global value number in one candidate relates to the global value number in the other.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] CurrCand</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to create a canonical numbering for.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp/#ad34b0969cb7181bf8847c796b0e52825">findCandidateStructures</a>.</p>

</div>
</div>

### isSimilar() {#a23d2b4941adb672f1a2ce945399065e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRSimilarityCandidate::isSimilar (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; B)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>- The first IRInstructionCandidate to compare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">B</td>
<td class="doxyParamItemDescription"><p>- The second IRInstructionCandidate to compare.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True when every <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> in <span class="doxyComputerOutput">A</span> is similar to every <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> in <span class="doxyComputerOutput">B</span>.</p></dd>
</dl>


<p>Declaration at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#ad7518d710d81c7c4c04cc6a61e7d65bc">llvm::IRSimilarity::isClose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>

</div>
</div>

### overlap() {#ad02bc9bd1feca133eb84b3618e93fb37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRSimilarityCandidate::overlap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; B)</td>
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

<p>Compare the start and end indices of the two IRSimilarityCandidates for whether they overlap.</p>


<p>If the start instruction of one <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> is less than the end instruction of the other, and the start instruction of one is greater than the start instruction of the other, they overlap.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the IRSimilarityCandidates do not have overlapping instructions.</p></dd>
</dl>


<p>Declaration at line 923 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ae35aff2dc6fcdec60f53cdcfabea59f7">IRSimilarityCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
