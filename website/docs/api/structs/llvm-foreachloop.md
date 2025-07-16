---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/foreachloop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ForeachLoop` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> - <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the iteration state associated with a for loop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ForeachLoop { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TableGen/TGParser.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018a8f365bef5f39ff2d28b6a32c366f">ForeachLoop</a> (SMLoc Loc, const VarInit *IVar, const Init *LValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69aac7774c444f12ffae0a9608aa38e1">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6973c5db49102794d0194783375ea87a">Loc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/varinit">VarInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c1e4b0b504ac19402a177d159a89d2">IterVar</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a638b43088a009852994f727d83bf45">ListValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0835f537cf71b2242968974330b76b63">Entries</a></td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> - <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the iteration state associated with a for loop.</p>


<p>This is used to instantiate items in the loop body.</p>


<p>IterVar is allowed to be null, in which case no iteration variable is defined in the loop at all. (This happens when a <a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> is constructed by desugaring an if statement.)</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ForeachLoop() {#a018a8f365bef5f39ff2d28b6a32c366f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ForeachLoop::ForeachLoop (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/varinit">VarInit</a> * IVar, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * LValue)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="#a91c1e4b0b504ac19402a177d159a89d2">IterVar</a>, <a href="#a5a638b43088a009852994f727d83bf45">ListValue</a>, <a href="#a6973c5db49102794d0194783375ea87a">Loc</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ab67ef02b75c3226cfe0b2791e2b48b06a74accfde3d3f8e8a27c326eba229d16c">LValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a69aac7774c444f12ffae0a9608aa38e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ForeachLoop::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4470 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>


<p>References <a href="#a0835f537cf71b2242968974330b76b63">Entries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a91c1e4b0b504ac19402a177d159a89d2">IterVar</a>, <a href="#a5a638b43088a009852994f727d83bf45">ListValue</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Entries {#a0835f537cf71b2242968974330b76b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;RecordsEntry&gt; llvm::ForeachLoop::Entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="#a69aac7774c444f12ffae0a9608aa38e1">dump</a>.</p>

</div>
</div>

### IterVar {#a91c1e4b0b504ac19402a177d159a89d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VarInit* llvm::ForeachLoop::IterVar</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="#a69aac7774c444f12ffae0a9608aa38e1">dump</a> and <a href="#a018a8f365bef5f39ff2d28b6a32c366f">ForeachLoop</a>.</p>

</div>
</div>

### ListValue {#a5a638b43088a009852994f727d83bf45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init* llvm::ForeachLoop::ListValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="#a69aac7774c444f12ffae0a9608aa38e1">dump</a> and <a href="#a018a8f365bef5f39ff2d28b6a32c366f">ForeachLoop</a>.</p>

</div>
</div>

### Loc {#a6973c5db49102794d0194783375ea87a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::ForeachLoop::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="#a018a8f365bef5f39ff2d28b6a32c366f">ForeachLoop</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
