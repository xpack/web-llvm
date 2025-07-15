---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/use
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Use` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> represents the edge between a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> definition and its users. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Use { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c437d9dcaefebe4efaf0edf00c45de">User</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5794eddf111636a89357ec2c4dfc600d">Use</a> (const Use &amp;U)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa95ce897f391faa1f8570faca4b700ef">Use</a> (User *Parent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor. <a href="#aa95ce897f391faa1f8570faca4b700ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb18a92dc5900d1bcde573be804c47bc">~Use</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destructor - Only for <a href="#a017fb8dfaf7591379bf7596ce0f196eb">zap()</a> <a href="#aeb18a92dc5900d1bcde573be804c47bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a008e3d16a9e6648481a0d2b1a61bffa4">operator Value *</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada20e2dc9c9b0301ce74b2fc3f40b7ee">operator=</a> (Value *RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45233a330c2da331f9724991e6f46174">operator=</a> (const Use &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92763d56156cb84df0086a0e39f5e487">operator-&gt;</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a1080f6345aafd5d4b863508deaab20">operator-&gt;</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a571caa9e25e6854e940f5bd78b7d8c9b">swap</a> (Use &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a fast substitute to <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap&lt;Use&gt;</a> that also works with less standard-compliant compilers. <a href="#a571caa9e25e6854e940f5bd78b7d8c9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad77c21b5dd2c8765f87e3fb054d68def">get</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user">User</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53a48d67682705c5f7f06ffc850fd622">getUser</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> that contains this <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>. <a href="#a53a48d67682705c5f7f06ffc850fd622">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40360b4fa7b8e6920a68e5a8a0814f1f">set</a> (Value *Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32360b17f849df25d61b70bc82cc753">getNext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a541187eb976df2189b40b3f62ed2cee0">getOperandNo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand # of this use in its <a href="/web-llvm/docs/api/classes/llvm/user">User</a>. <a href="#a541187eb976df2189b40b3f62ed2cee0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa091fe5596a8e214d862051fa8041b7">addToList</a> (Use **List)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c0d277d2c92d591ece8c4f01f8d10ac">removeFromList</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0efbf6b34580370cf6bf4833169a5a70">Val</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda51dbaf8cd54d598a2180e57de1fd3">Next</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c30f52e067f2df94d5322962478553e">Prev</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user">User</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafa3de6cb373610feeb60ee87f9684e5">Parent</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a017fb8dfaf7591379bf7596ce0f196eb">zap</a> (Use *Start, const Use *Stop, bool del=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroys <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> operands when the number of operands of a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> changes. <a href="#a017fb8dfaf7591379bf7596ce0f196eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> represents the edge between a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> definition and its users.</p>


<p>This is notionally a two-dimensional linked list. It supports traversing all of the uses for a particular value definition. It also supports jumping directly to the used value when we arrive from the <a href="/web-llvm/docs/api/classes/llvm/user">User</a>'s operands, and jumping directly to the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> when we arrive from the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>'s uses.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<div class="doxySectionDef">

## Friends

### User {#a38c437d9dcaefebe4efaf0edf00c45de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/user">User</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<p>Reference <a href="#a38c437d9dcaefebe4efaf0edf00c45de">User</a>.</p>


<p>Referenced by <a href="#a53a48d67682705c5f7f06ffc850fd622">getUser</a> and <a href="#a38c437d9dcaefebe4efaf0edf00c45de">User</a>.</p>

</div>
</div>

### Value {#aeceedf6e1a7d48a588516ce2b1983d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="#ad77c21b5dd2c8765f87e3fb054d68def">get</a>, <a href="#a541187eb976df2189b40b3f62ed2cee0">getOperandNo</a>, <a href="#a008e3d16a9e6648481a0d2b1a61bffa4">operator Value *</a>, <a href="#a92763d56156cb84df0086a0e39f5e487">operator-&gt;</a>, <a href="#a3a1080f6345aafd5d4b863508deaab20">operator-&gt;</a>, <a href="#ada20e2dc9c9b0301ce74b2fc3f40b7ee">operator=</a>, <a href="#a40360b4fa7b8e6920a68e5a8a0814f1f">set</a> and <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Use() {#a5794eddf111636a89357ec2c4dfc600d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Use::Use (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a5794eddf111636a89357ec2c4dfc600d">Use</a>.</p>


<p>Referenced by <a href="#ad32360b17f849df25d61b70bc82cc753">getNext</a>, <a href="#a45233a330c2da331f9724991e6f46174">operator=</a> and <a href="#a5794eddf111636a89357ec2c4dfc600d">Use</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Use() {#aa95ce897f391faa1f8570faca4b700ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Use::Use (<a href="/web-llvm/docs/api/classes/llvm/user">User</a> * Parent)</td>
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

<p>Constructor.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~Use() {#aeb18a92dc5900d1bcde573be804c47bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Use::~Use ()</td>
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

<p>Destructor - Only for <a href="#a017fb8dfaf7591379bf7596ce0f196eb">zap()</a></p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator Value \*() {#a008e3d16a9e6648481a0d2b1a61bffa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Use::operator Value * ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

### operator-&gt;() {#a92763d56156cb84df0086a0e39f5e487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Use::operator-&gt; ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

### operator-&gt;() {#a3a1080f6345aafd5d4b863508deaab20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::Use::operator-&gt; ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

### operator=() {#ada20e2dc9c9b0301ce74b2fc3f40b7ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Use::operator= (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>, definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a40360b4fa7b8e6920a68e5a8a0814f1f">set</a> and <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

### operator=() {#a45233a330c2da331f9724991e6f46174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use &amp; llvm::Use::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; RHS)</td>
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



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>, definition at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a40360b4fa7b8e6920a68e5a8a0814f1f">set</a> and <a href="#a5794eddf111636a89357ec2c4dfc600d">Use</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#ad77c21b5dd2c8765f87e3fb054d68def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Use::get ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a755df7966331f81ed038b727d99b8ddc">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::addDeadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a0d4a83cd78f12aa1ab452c4d94b9cb7b">llvm::User::getDescriptor</a>, <a href="/web-llvm/docs/api/structs/llvm/simplify-type-281e69781494059eea45e68051c37fd3/#a37607e885539a5a68651cece02813964">llvm::simplify_type&lt; const Use &gt;::getSimplifiedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/simplify-type-27218edf7fb98a791934726f4ff31474/#a96566c79e16938431d587d7e4347b231">llvm::simplify_type&lt; Use &gt;::getSimplifiedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a9ace593776041510de450a2eccc56eeb">operandWithNewAddressSpaceOrCreatePoison</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>.</p>

</div>
</div>

### getNext() {#ad32360b17f849df25d61b70bc82cc753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use * llvm::Use::getNext ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<p>Reference <a href="#a5794eddf111636a89357ec2c4dfc600d">Use</a>.</p>

</div>
</div>

### getOperandNo() {#a541187eb976df2189b40b3f62ed2cee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Use::getOperandNo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the operand # of this use in its <a href="/web-llvm/docs/api/classes/llvm/user">User</a>.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/use-cpp">Use.cpp</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5843fbc0765c997fa4bf9b6d876891b6">allUsesTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxtype/#a35fe5ece89bdf61c25ccfea4b6c0f43d">anonymous{X86LowerAMXType.cpp}::X86LowerAMXType::combineLoadBitcast</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a064517d4fd6ce0d70f560e1ae3cdb4a6">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::combineLoadCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcoptaddrmode-cpp/#a488daa300aea64109710b4e2fe0cbc44">dominatesAllUsesOf</a>, <a href="/web-llvm/docs/api/classes/shapecalculator/#a860edc537080dfa1a9a28aed98922a2d">ShapeCalculator::getShape</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a0c47c47ebffcc56ccf426575cc7688f1">llvm::RISCVDAGToDAGISel::hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8f7c0e181f6da8ad09295aaaa2445880">llvm::SITargetLowering::hasMemSDNodeUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a37275b44ee2af4598d1782f93d9204f3">hasNonFlagsUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37275b44ee2af4598d1782f93d9204f3">hasNonFlagsUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#a04a8af897aa17e64fedac0215ae4e705">isCompatibleReplacement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa7b7afb33f3a3f2da4bb2420499b398e">llvm::propagatesPoison</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/compatiblesets/#a4ef2eab86cf6fefd01ef4607cc834432">anonymous{SimplifyCFG.cpp}::CompatibleSets::shouldBelongToSameSet</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5ca29e57ad15a06f70b6676ec2665f34">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::transformAMXCast</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxtype/#aa0f5d1726cd1b45bdde53cc4a40e61f9">anonymous{X86LowerAMXType.cpp}::X86LowerAMXType::transformBitcast</a>.</p>

</div>
</div>

### getUser() {#a53a48d67682705c5f7f06ffc850fd622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User * llvm::Use::getUser ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> that contains this <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>.</p>


<p>For an instruction operand, for example, this will return the instruction.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>


<p>Reference <a href="#a38c437d9dcaefebe4efaf0edf00c45de">User</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5843fbc0765c997fa4bf9b6d876891b6">allUsesTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a4e92272bbf0049770569394d4956918b">llvm::MemorySSA::dominates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a55af5cce8eb7833907578e6fc3f0ab5e">eliminateSwiftErrorAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a021f42abfec39ba02f6b719a449b21db">ExtendUsesToFormExtLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31070c67db84f4caef376dcb7906c4fb">getCaseResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a7839b6e2958308f5941b95e49c69b1e8">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::getEdge</a>, <a href="/web-llvm/docs/api/classes/shapecalculator/#a860edc537080dfa1a9a28aed98922a2d">ShapeCalculator::getShape</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a0c47c47ebffcc56ccf426575cc7688f1">llvm::RISCVDAGToDAGISel::hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#abafc68a948c0a4deac7648103a979a70">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::hasLiveIncomingEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8f7c0e181f6da8ad09295aaaa2445880">llvm::SITargetLowering::hasMemSDNodeUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a37275b44ee2af4598d1782f93d9204f3">hasNonFlagsUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37275b44ee2af4598d1782f93d9204f3">hasNonFlagsUse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a29da820d4c19ac64f750762012fd13ca">anonymous{IndirectCallPromotion.cpp}::isDestBBSuitableForSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3bd0d872bcf9d623a8c432e3369cb0ec">isF128MovedToParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a26c84133695829e63f3a69adaddbe6b4">isI128MovedToParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a9ace593776041510de450a2eccc56eeb">operandWithNewAddressSpaceOrCreatePoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5991e29bae68e989e978dc600f93b48e">performMemPairCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa7b7afb33f3a3f2da4bb2420499b398e">llvm::propagatesPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2869d5459dca008c1c7a1e824e7faf5e">llvm::SelectionDAG::ReplaceAllUsesOfValuesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloopidiomrecognition-cpp/#a59208fe3d14291b83cd531d9d3166bcf">replaceAllUsesOfWithIn</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a4240fc0963676b19a8cbf8448a599700">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/compatiblesets/#a4ef2eab86cf6fefd01ef4607cc834432">anonymous{SimplifyCFG.cpp}::CompatibleSets::shouldBelongToSameSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6ad23b58059ffd91df6a2dddf30c5d71">llvm::X86TargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfoimpl/#a42d1b636e669eab226d5c36c5569c4d6">anonymous{AttributorAttributes.cpp}::AAInstanceInfoImpl::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9b97177f4c89df3fd0a2f05deec3378f">usePartialVectorLoads</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>

</div>
</div>

### set() {#a40360b4fa7b8e6920a68e5a8a0814f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Use::set (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>, definition at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sdnode/#aeffcf6f6a22d7591beed2f7a9d9fee20">llvm::SDNode::DropOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a55af5cce8eb7833907578e6fc3f0ab5e">eliminateSwiftErrorAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5877bd47049087f890aed4f0f501ec3f">llvm::SelectionDAG::MorphNodeTo</a>, <a href="#a45233a330c2da331f9724991e6f46174">operator=</a>, <a href="#ada20e2dc9c9b0301ce74b2fc3f40b7ee">operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#aff8bc09200ccc3617a5cb37e0d2f23ff">llvm::SwitchInst::removeCase</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa91c37999052160d434c5bf803257c9">llvm::SelectionDAG::RemoveDeadNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#ac0cc9b34e16910d245245642350d4456">llvm::IndirectBrInst::removeDestination</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2869d5459dca008c1c7a1e824e7faf5e">llvm::SelectionDAG::ReplaceAllUsesOfValuesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac630ccda26fea2f45afa3fb89bc1a8f4">llvm::SelectionDAG::ReplaceAllUsesOfValueWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5da44486df08f753ea147fe04e86026f">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8518c120f782df9e974c8b1b589feb40">llvm::SelectionDAG::ReplaceAllUsesWith</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>.</p>

</div>
</div>

### swap() {#a571caa9e25e6854e940f5bd78b7d8c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Use::swap (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide a fast substitute to <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap&lt;Use&gt;</a> that also works with less standard-compliant compilers.</p>

<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/use-cpp">Use.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addToList() {#aaa091fe5596a8e214d862051fa8041b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Use::addToList (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> ** List)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>

</div>
</div>

### removeFromList() {#a7c0d277d2c92d591ece8c4f01f8d10ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Use::removeFromList ()</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Next {#afda51dbaf8cd54d598a2180e57de1fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use* llvm::Use::Next = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>

</div>
</div>

### Parent {#aafa3de6cb373610feeb60ee87f9684e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User* llvm::Use::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>

</div>
</div>

### Prev {#a5c30f52e067f2df94d5322962478553e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use** llvm::Use::Prev = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>

</div>
</div>

### Val {#a0efbf6b34580370cf6bf4833169a5a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::Use::Val = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### zap() {#a017fb8dfaf7591379bf7596ce0f196eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Use::zap (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * Stop, bool del=false)</td>
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

<p>Destroys <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> operands when the number of operands of a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> changes.</p>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/use-cpp">Use.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">Use.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/use-cpp">Use.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
