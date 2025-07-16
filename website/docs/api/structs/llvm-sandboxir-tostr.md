---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sandboxir/tostr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ToStr` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::sandboxir::ToStr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">llvm/Transforms/Vectorize/SandboxVectorizer/Legality.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4110cbc5123ca0efdcc039dddb8d571">getLegalityResultID</a> (LegalityResultID ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3853e76dfef9b687eb1ae3e0dc7c476d">getVecReason</a> (ResultReason Reason)</td>
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


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getLegalityResultID() {#ac4110cbc5123ca0efdcc039dddb8d571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::sandboxir::ToStr::getLegalityResultID (<a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a26b0c28c43366c455232e14a5ebee1b6">LegalityResultID</a> ID)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a26b0c28c43366c455232e14a5ebee1b6a2949967e8957e37973cb1dc0e007821b">llvm::sandboxir::DiamondReuse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a26b0c28c43366c455232e14a5ebee1b6af2b1f6977f0a1f37de21d2bf22f6aec9">llvm::sandboxir::DiamondReuseMultiInput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a26b0c28c43366c455232e14a5ebee1b6a35720a713d11d72df3b14b4e1d427fda">llvm::sandboxir::DiamondReuseWithShuffle</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a26b0c28c43366c455232e14a5ebee1b6a4492081ca02b059f9e8af4ddaf0f7292">llvm::sandboxir::Pack</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a26b0c28c43366c455232e14a5ebee1b6ac43930a350749df9be8979b9c16f921e">llvm::sandboxir::Widen</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityresult/#ac45ada55c2eb4f56eac51088fed5d4e2">llvm::sandboxir::LegalityResult::print</a>.</p>

</div>
</div>

### getVecReason() {#a3853e76dfef9b687eb1ae3e0dc7c476d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::sandboxir::ToStr::getVecReason (<a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066">ResultReason</a> Reason)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066a3dfffbccd89c4df7a51723feea9e2708">llvm::sandboxir::CantSchedule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066afbd7d0e706dad851a17c7ad5fecd6e82">llvm::sandboxir::DiffBBs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066a2be1525d03c0dc09e257d24f60519d4e">llvm::sandboxir::DiffMathFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066a9a36ae1e72ed46b245257b37f625a2b7">llvm::sandboxir::DiffOpcodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066a7ff1bdee29302360cc1247644dd60440">llvm::sandboxir::DiffTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066a20c2a7ecd77046dec3d25c1ec579aa14">llvm::sandboxir::DiffWrapFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066a54def92f4c562f166a6abbcbceadeb46">llvm::sandboxir::Infeasible</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066a3c5e56cace7f26f06603d05bbb39705a">llvm::sandboxir::NotConsecutive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066a9133d09287731f5a84acaa902b1bf3ce">llvm::sandboxir::NotInstructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ab75a4a911dcbc5a402e38b472f4f0066aa6122fbac59d9c4f3fd78b12cfe6c5ee">llvm::sandboxir::Unimplemented</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityresultwithreason/#a8c3753b5d60c36291573bbead47fa840">llvm::sandboxir::LegalityResultWithReason::print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
