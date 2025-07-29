---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ms-demangle/pointertypenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PointerTypeNode` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::ms_demangle::PointerTypeNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">llvm/Demangle/MicrosoftDemangleNodes.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode">TypeNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94a5e3578a9b634d931e7109daba8b69">PointerTypeNode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd7b41bd8a19c92e657a2782d37bc2f2">outputPre</a> (OutputBuffer &amp;OB, OutputFlags Flags) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec0267be54d05127c01e8104884eda2">outputPost</a> (OutputBuffer &amp;OB, OutputFlags Flags) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26">PointerAffinity</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409ee45c3f349d08c44bca115a558758">Affinity</a> = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26a6adf97f83acf6453d4a6a4b1070f3754">PointerAffinity::None</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/qualifiednamenode">QualifiedNameNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4672172c95d250f8e2d7ef2d1f18c913">ClassParent</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode">TypeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1db34de23e39b5e0d905150df1f22e10">Pointee</a> = nullptr</td>
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


<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PointerTypeNode() {#a94a5e3578a9b634d931e7109daba8b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ms_demangle::PointerTypeNode::PointerTypeNode ()</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46ae385c38bb67ea909198e13ee23c21028">llvm::ms_demangle::PointerType</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode/#a4c498ca8535b565f0cd03672c7f4a55a">llvm::ms_demangle::TypeNode::TypeNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### outputPost() {#a4ec0267be54d05127c01e8104884eda2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PointerTypeNode::outputPost (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93">OutputFlags</a> Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46acb17ff5177bb277ed8dd79480aad9c27">llvm::ms_demangle::ArrayType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46aa238297af6fa869d4317808ad411b476">llvm::ms_demangle::FunctionSignature</a> and <a href="#a1db34de23e39b5e0d905150df1f22e10">Pointee</a>.</p>

</div>
</div>

### outputPre() {#acd7b41bd8a19c92e657a2782d37bc2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PointerTypeNode::outputPre (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93">OutputFlags</a> Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>References <a href="#a409ee45c3f349d08c44bca115a558758">Affinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46acb17ff5177bb277ed8dd79480aad9c27">llvm::ms_demangle::ArrayType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/functionsignaturenode/#af345ae8cf3d9d55bd40b73141bad8bad">llvm::ms_demangle::FunctionSignatureNode::CallConvention</a>, <a href="#a4672172c95d250f8e2d7ef2d1f18c913">ClassParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46aa238297af6fa869d4317808ad411b476">llvm::ms_demangle::FunctionSignature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93a5d9fdd8676f8e6f6ceb39ee2032d5ff5">llvm::ms_demangle::OF_NoCallingConvention</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp/#a141bc818a0114d9c6f5a81666e56dede">outputCallingConvention</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/functionsignaturenode/#a07ccd063ae170622a6af1ff591868c24">llvm::ms_demangle::FunctionSignatureNode::outputPre</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp/#a9e879fc145b1a29b5e6e304b32bc4848">outputQualifiers</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp/#adf65acd60cfe638347e29d174d4b5c77">outputSpaceIfNecessary</a>, <a href="#a1db34de23e39b5e0d905150df1f22e10">Pointee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26a61cf8510205077b6f5491d38cd44c0f7">llvm::ms_demangle::Pointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca198cb1c3c5c899ac467fd758a9c2630d">llvm::ms_demangle::Q_Unaligned</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode/#a52b0ebeb73b31f45a974e773d1d872ec">llvm::ms_demangle::TypeNode::Quals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26a63d5049791d9d79d86e9a108b0a999ca">llvm::ms_demangle::Reference</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26aa68a3262ced5b445f2a5a1953c279116">llvm::ms_demangle::RValueReference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Affinity {#a409ee45c3f349d08c44bca115a558758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerAffinity llvm::ms_demangle::PointerTypeNode::Affinity = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26a6adf97f83acf6453d4a6a4b1070f3754">PointerAffinity::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#acd7b41bd8a19c92e657a2782d37bc2f2">outputPre</a>.</p>

</div>
</div>

### ClassParent {#a4672172c95d250f8e2d7ef2d1f18c913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QualifiedNameNode* llvm::ms_demangle::PointerTypeNode::ClassParent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#acd7b41bd8a19c92e657a2782d37bc2f2">outputPre</a>.</p>

</div>
</div>

### Pointee {#a1db34de23e39b5e0d905150df1f22e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeNode* llvm::ms_demangle::PointerTypeNode::Pointee = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#a4ec0267be54d05127c01e8104884eda2">outputPost</a> and <a href="#acd7b41bd8a19c92e657a2782d37bc2f2">outputPre</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
