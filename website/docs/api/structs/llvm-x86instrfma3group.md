---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/x86instrfma3group
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `X86InstrFMA3Group` Struct

<p>This class is used to group {132, 213, 231} forms of FMA opcodes together. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::X86InstrFMA3Group { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">Target/X86/X86InstrFMA3Info.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a82b5ddb2e7d2e3c20d06a31708d966e7">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint16_t { <a href="#acf05964d78e0210534dfca8c7a4c22c8">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f74efb8033052bc72118b7aa31b0600">operator&lt;</a> (const X86InstrFMA3Group &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd37916537bfff84deebc6d98e8a08a8">get132Opcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the 132 form of FMA opcode. <a href="#acd37916537bfff84deebc6d98e8a08a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f439451927228a606e1f9cfaf2a4848">get213Opcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the 213 form of FMA opcode. <a href="#a3f439451927228a606e1f9cfaf2a4848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c2273d606fea74678359bf9162361c5">get231Opcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the 231 form of FMA opcode. <a href="#a6c2273d606fea74678359bf9162361c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9543312524e5fcda12a036c26b9f4dfc">isIntrinsic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the group of FMA opcodes holds intrinsic opcodes. <a href="#a9543312524e5fcda12a036c26b9f4dfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34eef045b5b21cc69d06aa7ed29c9a9">isKMergeMasked</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the group of FMA opcodes holds k-merge-masked opcodes. <a href="#aa34eef045b5b21cc69d06aa7ed29c9a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4360b138d750c21278b697f0b8ccaf3">isKZeroMasked</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the group of FMA opcodes holds k-zero-masked opcodes. <a href="#af4360b138d750c21278b697f0b8ccaf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481d3dba9acb9d69c8098a27b41ca60d">isKMasked</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the group of FMA opcodes holds any of k-masked opcodes. <a href="#a481d3dba9acb9d69c8098a27b41ca60d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba9a218514a869a928b1c4e301b93ad5">Opcodes</a>[3]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An array holding 3 forms of FMA opcodes. <a href="#aba9a218514a869a928b1c4e301b93ad5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f1755989daddfcf4eb4b6d47fca9fe">Attributes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This bitfield specifies the attributes associated with the created FMA groups of opcodes. <a href="#a08f1755989daddfcf4eb4b6d47fca9fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class is used to group {132, 213, 231} forms of FMA opcodes together.</p>


<p>Each of the groups has either 3 opcodes, Also, each group has an attributes field describing it.</p>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a82b5ddb2e7d2e3c20d06a31708d966e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">Form132<a id="a82b5ddb2e7d2e3c20d06a31708d966e7ac11caf195b365be2cf98ad1d2ae07db3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Form213<a id="a82b5ddb2e7d2e3c20d06a31708d966e7a25c5ed52f6a872c7c38ab2bacf20df45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Form231<a id="a82b5ddb2e7d2e3c20d06a31708d966e7a5796a7f5a0506c1de1700a9b07019860"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>

</div>
</div>

### anonymous enum  {#acf05964d78e0210534dfca8c7a4c22c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint16_t</td>
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
<td class="doxyEnumItemName">Intrinsic<a id="acf05964d78e0210534dfca8c7a4c22c8a09d7f7041cbcc86db224cfe0cd28ff2e"></a></td>
<td class="doxyEnumItemDescription">This bit must be set in the 'Attributes' field of FMA group if such group of FMA opcodes consists of FMA intrinsic opcodes (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KMergeMasked<a id="acf05964d78e0210534dfca8c7a4c22c8af79bf3edf15af90400b4e77e3d8fd13a"></a></td>
<td class="doxyEnumItemDescription">This bit must be set in the 'Attributes' field of FMA group if such group of FMA opcodes consists of AVX512 opcodes accepting a k-mask and passing the elements from the 1st operand to the result of the operation when the correpondings bits in the k-mask are unset (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KZeroMasked<a id="acf05964d78e0210534dfca8c7a4c22c8ad632ba2d763e0e4dba650160e18866d9"></a></td>
<td class="doxyEnumItemDescription">This bit must be set in the 'Attributes' field of FMA group if such group of FMA opcodes consists of AVX512 opcodes accepting a k-zeromask (= 0x4)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a5f74efb8033052bc72118b7aa31b0600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86InstrFMA3Group::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86instrfma3group">X86InstrFMA3Group</a> &amp; RHS)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>References <a href="#aba9a218514a869a928b1c4e301b93ad5">Opcodes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get132Opcode() {#acd37916537bfff84deebc6d98e8a08a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86InstrFMA3Group::get132Opcode ()</td>
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

<p>Returns the 132 form of FMA opcode.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>References <a href="#a82b5ddb2e7d2e3c20d06a31708d966e7ac11caf195b365be2cf98ad1d2ae07db3">Form132</a> and <a href="#aba9a218514a869a928b1c4e301b93ad5">Opcodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#af39f85bc7795ab54bd45481cb6fbd7ef">llvm::X86InstrInfo::getFMA3OpcodeToCommuteOperands</a>.</p>

</div>
</div>

### get213Opcode() {#a3f439451927228a606e1f9cfaf2a4848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86InstrFMA3Group::get213Opcode ()</td>
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

<p>Returns the 213 form of FMA opcode.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>References <a href="#a82b5ddb2e7d2e3c20d06a31708d966e7a25c5ed52f6a872c7c38ab2bacf20df45">Form213</a> and <a href="#aba9a218514a869a928b1c4e301b93ad5">Opcodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#af39f85bc7795ab54bd45481cb6fbd7ef">llvm::X86InstrInfo::getFMA3OpcodeToCommuteOperands</a>.</p>

</div>
</div>

### get231Opcode() {#a6c2273d606fea74678359bf9162361c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86InstrFMA3Group::get231Opcode ()</td>
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

<p>Returns the 231 form of FMA opcode.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>References <a href="#a82b5ddb2e7d2e3c20d06a31708d966e7a5796a7f5a0506c1de1700a9b07019860">Form231</a> and <a href="#aba9a218514a869a928b1c4e301b93ad5">Opcodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#af39f85bc7795ab54bd45481cb6fbd7ef">llvm::X86InstrInfo::getFMA3OpcodeToCommuteOperands</a>.</p>

</div>
</div>

### isIntrinsic() {#a9543312524e5fcda12a036c26b9f4dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86InstrFMA3Group::isIntrinsic ()</td>
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

<p>Returns true iff the group of FMA opcodes holds intrinsic opcodes.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>References <a href="#a08f1755989daddfcf4eb4b6d47fca9fe">Attributes</a> and <a href="#acf05964d78e0210534dfca8c7a4c22c8a09d7f7041cbcc86db224cfe0cd28ff2e">Intrinsic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a2c3415ef8f310c64d20ff8772825e0b5">llvm::X86InstrInfo::findCommutedOpIndices</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#af39f85bc7795ab54bd45481cb6fbd7ef">llvm::X86InstrInfo::getFMA3OpcodeToCommuteOperands</a>.</p>

</div>
</div>

### isKMasked() {#a481d3dba9acb9d69c8098a27b41ca60d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86InstrFMA3Group::isKMasked ()</td>
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

<p>Returns true iff the group of FMA opcodes holds any of k-masked opcodes.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>References <a href="#a08f1755989daddfcf4eb4b6d47fca9fe">Attributes</a>, <a href="#acf05964d78e0210534dfca8c7a4c22c8af79bf3edf15af90400b4e77e3d8fd13a">KMergeMasked</a> and <a href="#acf05964d78e0210534dfca8c7a4c22c8ad632ba2d763e0e4dba650160e18866d9">KZeroMasked</a>.</p>

</div>
</div>

### isKMergeMasked() {#aa34eef045b5b21cc69d06aa7ed29c9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86InstrFMA3Group::isKMergeMasked ()</td>
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

<p>Returns true iff the group of FMA opcodes holds k-merge-masked opcodes.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>References <a href="#a08f1755989daddfcf4eb4b6d47fca9fe">Attributes</a> and <a href="#acf05964d78e0210534dfca8c7a4c22c8af79bf3edf15af90400b4e77e3d8fd13a">KMergeMasked</a>.</p>

</div>
</div>

### isKZeroMasked() {#af4360b138d750c21278b697f0b8ccaf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86InstrFMA3Group::isKZeroMasked ()</td>
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

<p>Returns true iff the group of FMA opcodes holds k-zero-masked opcodes.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>References <a href="#a08f1755989daddfcf4eb4b6d47fca9fe">Attributes</a> and <a href="#acf05964d78e0210534dfca8c7a4c22c8ad632ba2d763e0e4dba650160e18866d9">KZeroMasked</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Attributes {#a08f1755989daddfcf4eb4b6d47fca9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::X86InstrFMA3Group::Attributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This bitfield specifies the attributes associated with the created FMA groups of opcodes.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>Referenced by <a href="#a9543312524e5fcda12a036c26b9f4dfc">isIntrinsic</a>, <a href="#a481d3dba9acb9d69c8098a27b41ca60d">isKMasked</a>, <a href="#aa34eef045b5b21cc69d06aa7ed29c9a9">isKMergeMasked</a> and <a href="#af4360b138d750c21278b697f0b8ccaf3">isKZeroMasked</a>.</p>

</div>
</div>

### Opcodes {#aba9a218514a869a928b1c4e301b93ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::X86InstrFMA3Group::Opcodes[3]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An array holding 3 forms of FMA opcodes.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>.</p>


<p>Referenced by <a href="#acd37916537bfff84deebc6d98e8a08a8">get132Opcode</a>, <a href="#a3f439451927228a606e1f9cfaf2a4848">get213Opcode</a>, <a href="#a6c2273d606fea74678359bf9162361c5">get231Opcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ac81c73fb91e0b2c0c30ae63c671d23">llvm::getFMA3Group</a> and <a href="#a5f74efb8033052bc72118b7aa31b0600">operator&lt;</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
