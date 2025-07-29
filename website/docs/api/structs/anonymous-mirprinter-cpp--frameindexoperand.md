---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-mirprinter-cpp-/frameindexoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FrameIndexOperand` Struct

<p>This structure describes how to print out stack object references. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MIRPrinter.cpp}::FrameIndexOperand { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a36201e859854a2dbd2b26dc463934a">FrameIndexOperand</a> (StringRef Name, unsigned ID, bool IsFixed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affcb28fbbbcb9a5e4cc645bd4941edca">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef391a001ea7b7f7c27a013273e575f1">ID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e5cd69199bc9cbeb5bc387bb11a53b8">IsFixed</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-mirprinter-cpp-/frameindexoperand">FrameIndexOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1245948287d60a5384eb715fbcae6e8">create</a> (StringRef Name, unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an ordinary stack object reference. <a href="#ad1245948287d60a5384eb715fbcae6e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-mirprinter-cpp-/frameindexoperand">FrameIndexOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d7e359161b639dcfa5307afd85dfe96">createFixed</a> (unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a fixed stack object reference. <a href="#a0d7e359161b639dcfa5307afd85dfe96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This structure describes how to print out stack object references.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FrameIndexOperand() {#a2a36201e859854a2dbd2b26dc463934a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MIRPrinter.cpp}::FrameIndexOperand::FrameIndexOperand (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, unsigned ID, bool IsFixed)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="#aef391a001ea7b7f7c27a013273e575f1">ID</a>, <a href="#a3e5cd69199bc9cbeb5bc387bb11a53b8">IsFixed</a> and <a href="#affcb28fbbbcb9a5e4cc645bd4941edca">Name</a>.</p>


<p>Referenced by <a href="#ad1245948287d60a5384eb715fbcae6e8">create</a> and <a href="#a0d7e359161b639dcfa5307afd85dfe96">createFixed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ID {#aef391a001ea7b7f7c27a013273e575f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MIRPrinter.cpp}::FrameIndexOperand::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>Referenced by <a href="#ad1245948287d60a5384eb715fbcae6e8">create</a>, <a href="#a0d7e359161b639dcfa5307afd85dfe96">createFixed</a> and <a href="#a2a36201e859854a2dbd2b26dc463934a">FrameIndexOperand</a>.</p>

</div>
</div>

### IsFixed {#a3e5cd69199bc9cbeb5bc387bb11a53b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MIRPrinter.cpp}::FrameIndexOperand::IsFixed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>Referenced by <a href="#a2a36201e859854a2dbd2b26dc463934a">FrameIndexOperand</a>.</p>

</div>
</div>

### Name {#affcb28fbbbcb9a5e4cc645bd4941edca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{MIRPrinter.cpp}::FrameIndexOperand::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>Referenced by <a href="#ad1245948287d60a5384eb715fbcae6e8">create</a> and <a href="#a2a36201e859854a2dbd2b26dc463934a">FrameIndexOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#ad1245948287d60a5384eb715fbcae6e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FrameIndexOperand anonymous{MIRPrinter.cpp}::FrameIndexOperand::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, unsigned ID)</td>
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

<p>Return an ordinary stack object reference.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="#a2a36201e859854a2dbd2b26dc463934a">FrameIndexOperand</a>, <a href="#aef391a001ea7b7f7c27a013273e575f1">ID</a> and <a href="#affcb28fbbbcb9a5e4cc645bd4941edca">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>.</p>

</div>
</div>

### createFixed() {#a0d7e359161b639dcfa5307afd85dfe96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FrameIndexOperand anonymous{MIRPrinter.cpp}::FrameIndexOperand::createFixed (unsigned ID)</td>
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

<p>Return a fixed stack object reference.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="#a2a36201e859854a2dbd2b26dc463934a">FrameIndexOperand</a> and <a href="#aef391a001ea7b7f7c27a013273e575f1">ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
