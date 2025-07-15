---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-bpfaspacecastsimplifypass-cpp-/castgepcast
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CastGEPCast` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{BPFASpaceCastSimplifyPass.cpp}::CastGEPCast { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab558890ee34084040e962c122ddd83f4">rewrite</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst">AddrSpaceCastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297d31288fe3e97d53e1b673638c0fe1">OuterCast</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-bpfaspacecastsimplifypass-cpp-/castgepcast">CastGEPCast</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac868ac3d1fb9f763763f1f5f7bf35569">match</a> (Value *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d873e7b88defd621fe04dc43e8b337">changeAddressSpace</a> (PointerType *Ty, unsigned AS)</td>
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


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfaspacecastsimplifypass-cpp">BPFASpaceCastSimplifyPass.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### rewrite() {#ab558890ee34084040e962c122ddd83f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetElementPtrInst * anonymous{BPFASpaceCastSimplifyPass.cpp}::CastGEPCast::rewrite ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfaspacecastsimplifypass-cpp">BPFASpaceCastSimplifyPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac9d873e7b88defd621fe04dc43e8b337">changeAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a> and <a href="#a297d31288fe3e97d53e1b673638c0fe1">OuterCast</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### OuterCast {#a297d31288fe3e97d53e1b673638c0fe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrSpaceCastInst* anonymous{BPFASpaceCastSimplifyPass.cpp}::CastGEPCast::OuterCast</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfaspacecastsimplifypass-cpp">BPFASpaceCastSimplifyPass.cpp</a>.</p>


<p>Referenced by <a href="#ac868ac3d1fb9f763763f1f5f7bf35569">match</a> and <a href="#ab558890ee34084040e962c122ddd83f4">rewrite</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### changeAddressSpace() {#ac9d873e7b88defd621fe04dc43e8b337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * anonymous{BPFASpaceCastSimplifyPass.cpp}::CastGEPCast::changeAddressSpace (<a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> * Ty, unsigned AS)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfaspacecastsimplifypass-cpp">BPFASpaceCastSimplifyPass.cpp</a>.</p>


<p>Referenced by <a href="#ab558890ee34084040e962c122ddd83f4">rewrite</a>.</p>

</div>
</div>

### match() {#ac868ac3d1fb9f763763f1f5f7bf35569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CastGEPCast &gt; anonymous{BPFASpaceCastSimplifyPass.cpp}::CastGEPCast::match (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfaspacecastsimplifypass-cpp">BPFASpaceCastSimplifyPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a297d31288fe3e97d53e1b673638c0fe1">OuterCast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bpfaspacecastsimplifypass/#a76364c57022d89ac618f1b1e22bef6e2">llvm::BPFASpaceCastSimplifyPass::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfaspacecastsimplifypass-cpp">BPFASpaceCastSimplifyPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
