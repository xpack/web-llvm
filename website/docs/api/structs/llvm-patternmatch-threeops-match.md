---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/threeops-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ThreeOps_match` Struct Template Reference

<p>Matches instructions with Opcode and three operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T0, typename T1, typename T2, unsigned Opcode, bool CommutableOp2Op3 = false&gt;
struct llvm::PatternMatch::ThreeOps_match&lt;T0, T1, T2, Opcode, CommutableOp2Op3&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a56e3f01ae368a90d0b72c75d8fc4ef2c">ThreeOps_match</a> (const T0 &amp;Op1, const T1 &amp;Op2, const T2 &amp;Op3)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OpTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acdcd29c63521748d4cacc25f5f682716">match</a> (OpTy *V)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T0</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0d2fff03a83bd2ffd943050d89fc71fe">Op1</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#affffcccd86a39bd78f548d9cea4f9025">Op2</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T2</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af9a2d991269cef2b9da482a604459ad3">Op3</a></td>
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

<p>Matches instructions with Opcode and three operands.</p>

<p>Definition at line 1744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ThreeOps\_match() {#a56e3f01ae368a90d0b72c75d8fc4ef2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0, typename T1, typename T2, unsigned Opcode, bool CommutableOp2Op3 = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::ThreeOps_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T0 &amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &amp; Op2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T2 &amp; Op3)</td>
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



<p>Definition at line 1749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="#a0d2fff03a83bd2ffd943050d89fc71fe">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::Op1</a>, <a href="#affffcccd86a39bd78f548d9cea4f9025">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::Op2</a>, <a href="#af9a2d991269cef2b9da482a604459ad3">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::Op3</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#acdcd29c63521748d4cacc25f5f682716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::match (OpTy * V)</td>
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



<p>Definition at line 1752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0d2fff03a83bd2ffd943050d89fc71fe">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::Op1</a>, <a href="#affffcccd86a39bd78f548d9cea4f9025">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::Op2</a> and <a href="#af9a2d991269cef2b9da482a604459ad3">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::Op3</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Op1 {#a0d2fff03a83bd2ffd943050d89fc71fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0, typename T1, typename T2, unsigned Opcode, bool CommutableOp2Op3 = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T0 llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::Op1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#acdcd29c63521748d4cacc25f5f682716">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::match</a> and <a href="#a56e3f01ae368a90d0b72c75d8fc4ef2c">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::ThreeOps_match</a>.</p>

</div>
</div>

### Op2 {#affffcccd86a39bd78f548d9cea4f9025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0, typename T1, typename T2, unsigned Opcode, bool CommutableOp2Op3 = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T1 llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::Op2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1746 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#acdcd29c63521748d4cacc25f5f682716">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::match</a> and <a href="#a56e3f01ae368a90d0b72c75d8fc4ef2c">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::ThreeOps_match</a>.</p>

</div>
</div>

### Op3 {#af9a2d991269cef2b9da482a604459ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0, typename T1, typename T2, unsigned Opcode, bool CommutableOp2Op3 = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T2 llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::Op3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#acdcd29c63521748d4cacc25f5f682716">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::match</a> and <a href="#a56e3f01ae368a90d0b72c75d8fc4ef2c">llvm::PatternMatch::ThreeOps_match&lt; T0, T1, T2, Opcode, CommutableOp2Op3 &gt;::ThreeOps_match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
