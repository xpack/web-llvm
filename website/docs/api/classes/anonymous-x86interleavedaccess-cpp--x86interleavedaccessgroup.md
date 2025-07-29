---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86interleavedaccess-cpp-/x86interleavedaccessgroup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `X86InterleavedAccessGroup` Class

<p>This class holds necessary information to represent an interleaved access group and supports utilities to lower the group into X86-specific instructions/intrinsics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9baadcb34d80f6467fcd01c3f513b60">X86InterleavedAccessGroup</a> (Instruction *I, ArrayRef&lt; ShuffleVectorInst * &gt; Shuffs, ArrayRef&lt; unsigned &gt; Ind, const unsigned F, const X86Subtarget &amp;STarget, IRBuilder&lt;&gt; &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In order to form an interleaved access group <a href="/web-llvm/docs/api/classes/anonymous-x86interleavedaccess-cpp-/x86interleavedaccessgroup">X86InterleavedAccessGroup</a> requires a wide-load instruction <span class="doxyComputerOutput">'I'</span>, a group of interleaved-vectors <span class="doxyComputerOutput">Shuffs</span>, reference to the first indices of each interleaved-vector <span class="doxyComputerOutput">'Ind'</span> and the interleaving stride factor <span class="doxyComputerOutput">F</span>. <a href="#ae9baadcb34d80f6467fcd01c3f513b60">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae769158e04d7d2df19b436d90e02bb85">isSupported</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this interleaved access group can be lowered into x86-specific instructions/intrinsics, false otherwise. <a href="#ae769158e04d7d2df19b436d90e02bb85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d756a0a03371c31155a702e0ba4d85">lowerIntoOptimizedSequence</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lowers this interleaved access group into X86-specific instructions/intrinsics. <a href="#a57d756a0a03371c31155a702e0ba4d85">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f53f3f8492b54fcd27314807c3d4cb">decompose</a> (Instruction *Inst, unsigned NumSubVectors, FixedVectorType *T, SmallVectorImpl&lt; Instruction * &gt; &amp;DecomposedVectors)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Breaks down a vector <span class="doxyComputerOutput">'Inst'</span> of N elements into <span class="doxyComputerOutput">NumSubVectors</span> sub vectors of type <span class="doxyComputerOutput">T</span>. <a href="#a24f53f3f8492b54fcd27314807c3d4cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae212ec75f34f93b61b9b844d91d88cbf">transpose_4x4</a> (ArrayRef&lt; Instruction * &gt; InputVectors, SmallVectorImpl&lt; Value * &gt; &amp;TransposedMatrix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Performs matrix transposition on a 4x4 matrix <span class="doxyComputerOutput">InputVectors</span> and returns the transposed-vectors in <span class="doxyComputerOutput">TransposedVectors</span>. <a href="#ae212ec75f34f93b61b9b844d91d88cbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b63009d179b0b2bf2bac09c2cd4a85">interleave8bitStride4</a> (ArrayRef&lt; Instruction * &gt; InputVectors, SmallVectorImpl&lt; Value * &gt; &amp;TransposedMatrix, unsigned NumSubVecElems)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc416e3d7dcca17f66d807d51076e577">interleave8bitStride4VF8</a> (ArrayRef&lt; Instruction * &gt; InputVectors, SmallVectorImpl&lt; Value * &gt; &amp;TransposedMatrix)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aaa9231b8068bafc53d55ff41859ab8">interleave8bitStride3</a> (ArrayRef&lt; Instruction * &gt; InputVectors, SmallVectorImpl&lt; Value * &gt; &amp;TransposedMatrix, unsigned NumSubVecElems)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a381ab069da925c1d1849c1d112557d22">deinterleave8bitStride3</a> (ArrayRef&lt; Instruction * &gt; InputVectors, SmallVectorImpl&lt; Value * &gt; &amp;TransposedMatrix, unsigned NumSubVecElems)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280961a2a503560a593bd10e40d2980a">Inst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the wide-load instruction of an interleaved access group. <a href="#a280961a2a503560a593bd10e40d2980a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76df646a3ada0c8cf15362aca59f7ad7">Shuffles</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the shuffle(s), consumer(s) of the (load) 'Inst'. <a href="#a76df646a3ada0c8cf15362aca59f7ad7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29aa9edc5697764a3cdef5794607eef">Indices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the starting index of each user-shuffle. <a href="#ad29aa9edc5697764a3cdef5794607eef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d580413fd88c5c822575d9029fd6d01">Factor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the interleaving stride in terms of elements. <a href="#a7d580413fd88c5c822575d9029fd6d01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2097662b67c129d2ef5fae70aedd59">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the underlying target. <a href="#a9a2097662b67c129d2ef5fae70aedd59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1be9345b202bf8470401cd3e01c5c51f">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a016d6625682bad1dc47e0a47459986">Builder</a></td>
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

<p>This class holds necessary information to represent an interleaved access group and supports utilities to lower the group into X86-specific instructions/intrinsics.</p>


<p>E.g. A group of interleaving access loads (Factor = 2; accessing every other element) wide.vec = load &lt;8 x i32&gt;, &lt;8 x i32&gt;* ptr v0 = shuffle &lt;8 x i32&gt; wide.vec, &lt;8 x i32&gt; poison, &lt;0, 2, 4, 6&gt; v1 = shuffle &lt;8 x i32&gt; wide.vec, &lt;8 x i32&gt; poison, &lt;1, 3, 5, 7&gt;</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86InterleavedAccessGroup() {#ae9baadcb34d80f6467fcd01c3f513b60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::X86InterleavedAccessGroup (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * &gt; Shuffs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Ind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; STarget, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In order to form an interleaved access group <a href="/web-llvm/docs/api/classes/anonymous-x86interleavedaccess-cpp-/x86interleavedaccessgroup">X86InterleavedAccessGroup</a> requires a wide-load instruction <span class="doxyComputerOutput">'I'</span>, a group of interleaved-vectors <span class="doxyComputerOutput">Shuffs</span>, reference to the first indices of each interleaved-vector <span class="doxyComputerOutput">'Ind'</span> and the interleaving stride factor <span class="doxyComputerOutput">F</span>.</p>


<p>In order to generate X86-specific instructions/intrinsics it also requires the underlying target information <span class="doxyComputerOutput">STarget</span>.</p>


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isSupported() {#ae769158e04d7d2df19b436d90e02bb85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InterleavedAccessGroup::isSupported ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this interleaved access group can be lowered into x86-specific instructions/intrinsics, false otherwise.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21b1f2d0effa0506f01cb146823de6a2">llvm::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### lowerIntoOptimizedSequence() {#a57d756a0a03371c31155a702e0ba4d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86InterleavedAccessGroup::lowerIntoOptimizedSequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lowers this interleaved access group into X86-specific instructions/intrinsics.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4288169d91ab0f0f01405115fd2931a7">llvm::concatenateVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### decompose() {#a24f53f3f8492b54fcd27314807c3d4cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InterleavedAccessGroup::decompose (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, unsigned NumSubVectors, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * T, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; DecomposedVectors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Breaks down a vector <span class="doxyComputerOutput">'Inst'</span> of N elements into <span class="doxyComputerOutput">NumSubVectors</span> sub vectors of type <span class="doxyComputerOutput">T</span>.</p>


<p>Returns the sub-vectors in <span class="doxyComputerOutput">DecomposedVectors</span>.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### deinterleave8bitStride3() {#a381ab069da925c1d1849c1d112557d22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InterleavedAccessGroup::deinterleave8bitStride3 (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; InputVectors, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; TransposedMatrix, unsigned NumSubVecElems)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### interleave8bitStride3() {#a6aaa9231b8068bafc53d55ff41859ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InterleavedAccessGroup::interleave8bitStride3 (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; InputVectors, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; TransposedMatrix, unsigned NumSubVecElems)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### interleave8bitStride4() {#a41b63009d179b0b2bf2bac09c2cd4a85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InterleavedAccessGroup::interleave8bitStride4 (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; InputVectors, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; TransposedMatrix, unsigned NumSubVecElems)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### interleave8bitStride4VF8() {#acc416e3d7dcca17f66d807d51076e577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InterleavedAccessGroup::interleave8bitStride4VF8 (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; InputVectors, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; TransposedMatrix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### transpose\_4x4() {#ae212ec75f34f93b61b9b844d91d88cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InterleavedAccessGroup::transpose_4x4 (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; InputVectors, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; TransposedMatrix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Performs matrix transposition on a 4x4 matrix <span class="doxyComputerOutput">InputVectors</span> and returns the transposed-vectors in <span class="doxyComputerOutput">TransposedVectors</span>.</p>


<p>E.g. InputVectors: In-V0 = p1, p2, p3, p4 In-V1 = q1, q2, q3, q4 In-V2 = r1, r2, r3, r4 In-V3 = s1, s2, s3, s4 OutputVectors: Out-V0 = p1, q1, r1, s1 Out-V1 = p2, q2, r2, s2 Out-V2 = p3, q3, r3, s3 Out-V3 = P4, q4, r4, s4</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Builder {#a7a016d6625682bad1dc47e0a47459986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder&amp; anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### DL {#a1be9345b202bf8470401cd3e01c5c51f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### Factor {#a7d580413fd88c5c822575d9029fd6d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::Factor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to the interleaving stride in terms of elements.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### Indices {#ad29aa9edc5697764a3cdef5794607eef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;unsigned&gt; anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::Indices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to the starting index of each user-shuffle.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### Inst {#a280961a2a503560a593bd10e40d2980a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* const anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::Inst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to the wide-load instruction of an interleaved access group.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### Shuffles {#a76df646a3ada0c8cf15362aca59f7ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;ShuffleVectorInst *&gt; anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::Shuffles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to the shuffle(s), consumer(s) of the (load) 'Inst'.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

### Subtarget {#a9a2097662b67c129d2ef5fae70aedd59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget&amp; anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to the underlying target.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
