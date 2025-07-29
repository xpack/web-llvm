---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/genericssacontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GenericSSAContext` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename _FunctionT&gt;
class llvm::GenericSSAContext&lt;_FunctionT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">llvm/ADT/GenericSSAContext.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae61a8004a357c9ecb198807986c136af">ValueRefT</a> = typename SSATraits::ValueRefT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a679e3edc0e69cd3904b77334ec5a9763">ConstValueRefT</a> = typename SSATraits::ConstValueRefT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06a515c7957bf4613d82ce20e8718a9c">InstructionT</a> = typename SSATraits::InstructionT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd7b9405a070052a7d161fadb3e5cb05">UseT</a> = typename SSATraits::UseT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c0d30d44944317e45adf1c9d0d0522f">BlockT</a> = typename SSATraits::BlockT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e95e12a93bcb75e4f836cd5b3c2c2df">FunctionT</a> = typename SSATraits::FunctionT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adade4ed236ba6edfd68417b663767bc9">DominatorTreeT</a> = <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; <a href="#a9c0d30d44944317e45adf1c9d0d0522f">BlockT</a>, false &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab591ad0c7d087e2352b2001f7b1a3d73">SSATraits</a> = <a href="/web-llvm/docs/api/structs/llvm/genericssatraits">GenericSSATraits</a>&lt; _FunctionT &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5c463c7051122ac89c9c80b4ed8bd2a1">GenericSSAContext</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aff16c3135f40666327cbe863043cc3e4">GenericSSAContext</a> (const FunctionT *F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2e95e12a93bcb75e4f836cd5b3c2c2df">FunctionT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30a51889c6eedfd8e8af2716ba146c12">getFunction</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9c0d30d44944317e45adf1c9d0d0522f">BlockT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa11ffe4178be0cb118d76dbc8d3f3b13">getDefBlock</a> (ConstValueRefT value) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/printable">Printable</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a662a00e83eaad4940874eaa0840ac142">print</a> (const BlockT *block) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/printable">Printable</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae963d2b8ccb6c1cf648185920f8aaccf">printAsOperand</a> (const BlockT *BB) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/printable">Printable</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade67d94e3f67a42b8ce0c7ef1adb9956">print</a> (const InstructionT *inst) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/printable">Printable</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a798232c13fea327c66a0fb62d07e0a">print</a> (ConstValueRefT value) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SSATraits::FunctionT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac616371ea30c0c275bd60115307d13cb">F</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a603a1b95327596a772990dcf264192bb">getIntrinsicID</a> (const InstructionT &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11d0bd29c71e5e0f4f886d9a5d038f6d">appendBlockDefs</a> (SmallVectorImpl&lt; ValueRefT &gt; &amp;defs, BlockT &amp;block)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b38e4e9aa6fc7cbfaca50399fae5778">appendBlockDefs</a> (SmallVectorImpl&lt; ConstValueRefT &gt; &amp;defs, const BlockT &amp;block)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4848ac5fdb1eb954bb63b84200386e0b">appendBlockTerms</a> (SmallVectorImpl&lt; InstructionT * &gt; &amp;terms, BlockT &amp;block)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0af40690ef913f659af917ec7e5d42b3">appendBlockTerms</a> (SmallVectorImpl&lt; const InstructionT * &gt; &amp;terms, const BlockT &amp;block)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a45adcf8fed75ea4249d40bf8d43a7736">isConstantOrUndefValuePhi</a> (const InstructionT &amp;Instr)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="#ae61a8004a357c9ecb198807986c136af">ValueRefT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a563c7270994befe0515d101fb9040c02">ValueRefNull</a> = {}</td>
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


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlockT {#a9c0d30d44944317e45adf1c9d0d0522f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericSSAContext&lt; _FunctionT &gt;::BlockT =  typename SSATraits::BlockT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### ConstValueRefT {#a679e3edc0e69cd3904b77334ec5a9763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericSSAContext&lt; _FunctionT &gt;::ConstValueRefT =  typename SSATraits::ConstValueRefT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### DominatorTreeT {#adade4ed236ba6edfd68417b663767bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericSSAContext&lt; _FunctionT &gt;::DominatorTreeT =  DominatorTreeBase&lt;BlockT, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### FunctionT {#a2e95e12a93bcb75e4f836cd5b3c2c2df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericSSAContext&lt; _FunctionT &gt;::FunctionT =  typename SSATraits::FunctionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### InstructionT {#a06a515c7957bf4613d82ce20e8718a9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericSSAContext&lt; _FunctionT &gt;::InstructionT =  typename SSATraits::InstructionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### UseT {#acd7b9405a070052a7d161fadb3e5cb05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericSSAContext&lt; _FunctionT &gt;::UseT =  typename SSATraits::UseT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### ValueRefT {#ae61a8004a357c9ecb198807986c136af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericSSAContext&lt; _FunctionT &gt;::ValueRefT =  typename SSATraits::ValueRefT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### SSATraits {#ab591ad0c7d087e2352b2001f7b1a3d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericSSAContext&lt; _FunctionT &gt;::SSATraits =  GenericSSATraits&lt;_FunctionT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GenericSSAContext() {#a5c463c7051122ac89c9c80b4ed8bd2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericSSAContext&lt; _FunctionT &gt;::GenericSSAContext ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### GenericSSAContext() {#aff16c3135f40666327cbe863043cc3e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericSSAContext&lt; _FunctionT &gt;::GenericSSAContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2e95e12a93bcb75e4f836cd5b3c2c2df">FunctionT</a> * F)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDefBlock() {#aa11ffe4178be0cb118d76dbc8d3f3b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockT * llvm::GenericSSAContext&lt; _FunctionT &gt;::getDefBlock (<a href="#a679e3edc0e69cd3904b77334ec5a9763">ConstValueRefT</a> value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### getFunction() {#a30a51889c6eedfd8e8af2716ba146c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionT * llvm::GenericSSAContext&lt; _FunctionT &gt;::getFunction ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### print() {#a662a00e83eaad4940874eaa0840ac142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Printable llvm::GenericSSAContext&lt; _FunctionT &gt;::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9c0d30d44944317e45adf1c9d0d0522f">BlockT</a> * block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### print() {#ade67d94e3f67a42b8ce0c7ef1adb9956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Printable llvm::GenericSSAContext&lt; _FunctionT &gt;::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a06a515c7957bf4613d82ce20e8718a9c">InstructionT</a> * inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### print() {#a8a798232c13fea327c66a0fb62d07e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Printable llvm::GenericSSAContext&lt; _FunctionT &gt;::print (<a href="#a679e3edc0e69cd3904b77334ec5a9763">ConstValueRefT</a> value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### printAsOperand() {#ae963d2b8ccb6c1cf648185920f8aaccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Printable llvm::GenericSSAContext&lt; _FunctionT &gt;::printAsOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9c0d30d44944317e45adf1c9d0d0522f">BlockT</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### F {#ac616371ea30c0c275bd60115307d13cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SSATraits::FunctionT* llvm::GenericSSAContext&lt; _FunctionT &gt;::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### appendBlockDefs() {#a11d0bd29c71e5e0f4f886d9a5d038f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericSSAContext&lt; _FunctionT &gt;::appendBlockDefs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#ae61a8004a357c9ecb198807986c136af">ValueRefT</a> &gt; &amp; defs, <a href="#a9c0d30d44944317e45adf1c9d0d0522f">BlockT</a> &amp; block)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### appendBlockDefs() {#a7b38e4e9aa6fc7cbfaca50399fae5778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericSSAContext&lt; _FunctionT &gt;::appendBlockDefs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a679e3edc0e69cd3904b77334ec5a9763">ConstValueRefT</a> &gt; &amp; defs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9c0d30d44944317e45adf1c9d0d0522f">BlockT</a> &amp; block)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### appendBlockTerms() {#a4848ac5fdb1eb954bb63b84200386e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericSSAContext&lt; _FunctionT &gt;::appendBlockTerms (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a06a515c7957bf4613d82ce20e8718a9c">InstructionT</a> * &gt; &amp; terms, <a href="#a9c0d30d44944317e45adf1c9d0d0522f">BlockT</a> &amp; block)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### appendBlockTerms() {#a0af40690ef913f659af917ec7e5d42b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericSSAContext&lt; _FunctionT &gt;::appendBlockTerms (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a06a515c7957bf4613d82ce20e8718a9c">InstructionT</a> * &gt; &amp; terms, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9c0d30d44944317e45adf1c9d0d0522f">BlockT</a> &amp; block)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### getIntrinsicID() {#a603a1b95327596a772990dcf264192bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID llvm::GenericSSAContext&lt; _FunctionT &gt;::getIntrinsicID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a06a515c7957bf4613d82ce20e8718a9c">InstructionT</a> &amp; I)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

### isConstantOrUndefValuePhi() {#a45adcf8fed75ea4249d40bf8d43a7736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericSSAContext&lt; _FunctionT &gt;::isConstantOrUndefValuePhi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a06a515c7957bf4613d82ce20e8718a9c">InstructionT</a> &amp; Instr)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ValueRefNull {#a563c7270994befe0515d101fb9040c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueRefT* llvm::GenericSSAContext&lt; _FunctionT &gt;::ValueRefNull = {}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
