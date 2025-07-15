---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpulibfuncbase/param
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Param` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPULibFuncBase::Param { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">Target/AMDGPU/AMDGPULibFunc.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb34f43d41245b5146fe08697283cea">reset</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Stream&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e34e7fcb819c6a0f617854ed5a35544">mangleItanium</a> (Stream &amp;os)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6aba5ea4aaeb77192a50982874a003">ArgType</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469fe9010014da053431ef7376268c47">VectorSize</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909a7690a970a0c70d7c3ff1a2df63b0">PtrKind</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac211f121492daa03e72b8257d8dfe08a">Reserved</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/amdgpulibfuncbase/param">Param</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2fe1bf027f37c94352497fc299ae668">getIntN</a> (unsigned char NumElts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/amdgpulibfuncbase/param">Param</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd940cbe9661c05ef27f751e09cac77">getFromTy</a> (Type *Ty, bool Signed)</td>
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


<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### mangleItanium() {#a0e34e7fcb819c6a0f617854ed5a35544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Stream&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPULibFuncBase::Param::mangleItanium (Stream &amp; os)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### reset() {#a0cb34f43d41245b5146fe08697283cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPULibFuncBase::Param::reset ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>References <a href="#afe6aba5ea4aaeb77192a50982874a003">ArgType</a>, <a href="#a909a7690a970a0c70d7c3ff1a2df63b0">PtrKind</a> and <a href="#a469fe9010014da053431ef7376268c47">VectorSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ArgType {#afe6aba5ea4aaeb77192a50982874a003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::AMDGPULibFuncBase::Param::ArgType = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#a0b53d60342909a86b16824b265a29a4b">getArgType</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a> and <a href="#a0cb34f43d41245b5146fe08697283cea">reset</a>.</p>

</div>
</div>

### PtrKind {#a909a7690a970a0c70d7c3ff1a2df63b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::AMDGPULibFuncBase::Param::PtrKind = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#a82fc29e6e65a437cc296e3dbfebd2b20">anonymous{AMDGPULibFunc.cpp}::getRetType</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a> and <a href="#a0cb34f43d41245b5146fe08697283cea">reset</a>.</p>

</div>
</div>

### Reserved {#ac211f121492daa03e72b8257d8dfe08a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::AMDGPULibFuncBase::Param::Reserved = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### VectorSize {#a469fe9010014da053431ef7376268c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::AMDGPULibFuncBase::Param::VectorSize = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#a66b370f607062909219c834ffca364dd">getVecSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a> and <a href="#a0cb34f43d41245b5146fe08697283cea">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFromTy() {#aedd940cbe9661c05ef27f751e09cac77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPULibFuncBase::Param AMDGPULibFuncBase::Param::getFromTy (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool Signed)</td>
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



<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>, definition at line 888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8af91b4c3fb5deff779fa5884c0d521278">llvm::AMDGPULibFuncBase::F16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8af5e427970dc9c29ec50cb3f39fbcf774">llvm::AMDGPULibFuncBase::F32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a06c2414f8276b0025f4057efce9bc562">llvm::AMDGPULibFuncBase::F64</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">llvm::Type::HalfTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3a5514459881fc9d2444d6ac8a18a8c2">llvm::AMDGPULibFuncBase::I16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8039c0339aea621d2589419bc0c7ffdf">llvm::AMDGPULibFuncBase::I32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aaeb097d554a6e77e61dd1dc797ea062f">llvm::AMDGPULibFuncBase::I64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ad0af55ef4d18b5452d50afa947f2f150">llvm::AMDGPULibFuncBase::I8</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a76424308db519548eaeda3655a288bc4">llvm::AMDGPULibFuncBase::U16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3e402cd027c568fa43f4b554c0b348b6">llvm::AMDGPULibFuncBase::U32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8c6c6342eca81ee6609a590cdc4fcad6">llvm::AMDGPULibFuncBase::U64</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ae8baa7f9c7af35b4306f6d225214404e">llvm::AMDGPULibFuncBase::U8</a>.</p>

</div>
</div>

### getIntN() {#ab2fe1bf027f37c94352497fc299ae668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Param llvm::AMDGPULibFuncBase::Param::getIntN (unsigned char NumElts)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8039c0339aea621d2589419bc0c7ffdf">llvm::AMDGPULibFuncBase::I32</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
