---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/callbase/bundleopinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BundleOpInfo` Struct Reference

<p>Used to keep track of an operand bundle. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::CallBase::BundleOpInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a7e6ab6866fa489b430fcb315b0ed8e">operator==</a> (const BundleOpInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; uint32_t &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa7df1351e95051b1565a3df18dacb0">Tag</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The operand bundle tag, interned by <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6ca6e14339dfb653b003a458b80a4802">LLVMContextImpl::getOrInsertBundleTag</a>. <a href="#a6aa7df1351e95051b1565a3df18dacb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af823d55c0067f516522508d1a38b2992">Begin</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index in the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>&amp; vector where operands for this operand bundle starts. <a href="#af823d55c0067f516522508d1a38b2992">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada395c3a073fdc65e96bf018d9d0cf4f">End</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index in the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>&amp; vector where operands for this operand bundle ends. <a href="#ada395c3a073fdc65e96bf018d9d0cf4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Used to keep track of an operand bundle.</p>


<p>See the main comment on OperandBundleUser above.</p>


<p>Definition at line 2138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#a3a7e6ab6866fa489b430fcb315b0ed8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::BundleOpInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> &amp; Other)</td>
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



<p>Definition at line 2151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#af823d55c0067f516522508d1a38b2992">Begin</a>, <a href="#ada395c3a073fdc65e96bf018d9d0cf4f">End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a6aa7df1351e95051b1565a3df18dacb0">Tag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Begin {#af823d55c0067f516522508d1a38b2992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::CallBase::BundleOpInfo::Begin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index in the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>&amp; vector where operands for this operand bundle starts.</p>

<p>Definition at line 2145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumebundlequeries-cpp/#ae6be7fe28837ecffcc216aea370259bb">bundleHasArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a7a21e7face454c8ea6c4b9e12b506e40">llvm::CallBase::getBundleOperandsStartIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a05315814f0e1ff39f8e753d7ac430a02">llvm::CallBase::getBundleOpInfoForOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5b33634e0aa97435f13845ce7e10411e">llvm::getKnowledgeFromBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumebundlequeries-cpp/#a4ba9c3f6eaec5417b7ba57bc108203f7">getValueFromBundleOpInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a1b6cd42ee6d8d51324f79e5e5e5d5f74">llvm::CallBase::operandBundleFromBundleOpInfo</a>, <a href="#a3a7e6ab6866fa489b430fcb315b0ed8e">operator==</a> and <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aba1e9ea5dd5dfc2b1559cb6cef8b4854">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::tryToPreserveWithoutAddingAssume</a>.</p>

</div>
</div>

### End {#ada395c3a073fdc65e96bf018d9d0cf4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::CallBase::BundleOpInfo::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index in the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>&amp; vector where operands for this operand bundle ends.</p>

<p>Definition at line 2149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumebundlequeries-cpp/#ae6be7fe28837ecffcc216aea370259bb">bundleHasArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0951bc018bd4725e28d9d05e36a1360a">llvm::CallBase::getBundleOperandsEndIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a05315814f0e1ff39f8e753d7ac430a02">llvm::CallBase::getBundleOpInfoForOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5b33634e0aa97435f13845ce7e10411e">llvm::getKnowledgeFromBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a1b6cd42ee6d8d51324f79e5e5e5d5f74">llvm::CallBase::operandBundleFromBundleOpInfo</a> and <a href="#a3a7e6ab6866fa489b430fcb315b0ed8e">operator==</a>.</p>

</div>
</div>

### Tag {#a6aa7df1351e95051b1565a3df18dacb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntry&lt;uint32_t&gt;* llvm::CallBase::BundleOpInfo::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The operand bundle tag, interned by <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6ca6e14339dfb653b003a458b80a4802">LLVMContextImpl::getOrInsertBundleTag</a>.</p>

<p>Definition at line 2141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5b33634e0aa97435f13845ce7e10411e">llvm::getKnowledgeFromBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a1b6cd42ee6d8d51324f79e5e5e5d5f74">llvm::CallBase::operandBundleFromBundleOpInfo</a> and <a href="#a3a7e6ab6866fa489b430fcb315b0ed8e">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
