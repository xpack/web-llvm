---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-irmover-cpp-/typemapty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TypeMapTy` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{IRMover.cpp}::TypeMapTy { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemaptyperemapper">ValueMapTypeRemapper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a class that can be implemented by clients to remap types when cloning constants and instructions. <a href="/web-llvm/docs/api/classes/llvm/valuemaptyperemapper/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa275b2c48b86647c8013b29c85b4f958">TypeMapTy</a> (IRMover::IdentifiedStructTypeSet &amp;DstStructTypesSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ffc031e0ab9260c4521b5e5a8c16c3">addTypeMapping</a> (Type *DstTy, Type *SrcTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that the specified type in the destination module is conceptually equivalent to the specified type in the source module. <a href="#a38ffc031e0ab9260c4521b5e5a8c16c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9458e9521315cb278dee23c71634b48e">linkDefinedTypeBodies</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce a body for an opaque type in the dest module from a type definition in the source module. <a href="#a9458e9521315cb278dee23c71634b48e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30460dd0f1cb911d96c45a476cb2b4e9">get</a> (Type *SrcTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the mapped type to use for the specified input type from the source module. <a href="#a30460dd0f1cb911d96c45a476cb2b4e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4560aabfb53fdcd353203fdca21a0eab">get</a> (Type *SrcTy, SmallPtrSet&lt; StructType *, 8 &gt; &amp;Visited)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbedc4a67ef945addc0b70024a4e43be">get</a> (FunctionType *T)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c19f1ac40445a784187b0c5cf76fd0">remapType</a> (Type *SrcTy) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The client should implement this method if they want to remap types while mapping values. <a href="#ab9c19f1ac40445a784187b0c5cf76fd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad62885810aa160ae4da044597fc9f4e8">areTypesIsomorphic</a> (Type *DstTy, Type *SrcTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively walk this pair of types, returning true if they are isomorphic, false if they are not. <a href="#ad62885810aa160ae4da044597fc9f4e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irmover/identifiedstructtypeset">IRMover::IdentifiedStructTypeSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf4983735e6e2e6c9184c210d03c3c1">DstStructTypesSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcdf79ff0235e6bcf3ce508be4cb83ba">MappedTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a mapping from a source type to a destination type to use. <a href="#adcdf79ff0235e6bcf3ce508be4cb83ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df03bb7372ac66454c3773e2e29a614">SpeculativeTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When checking to see if two subgraphs are isomorphic, we speculatively add types to MappedTypes, but keep track of them here in case we need to roll back. <a href="#a9df03bb7372ac66454c3773e2e29a614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca58d93a1070a0b8e95d610a53d4a15">SpeculativeDstOpaqueTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18de62c7b2f578643da867fd0f172c1b">SrcDefinitionsToResolve</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a list of non-opaque structs in the source module that are mapped to an opaque struct in the destination module. <a href="#a18de62c7b2f578643da867fd0f172c1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae32d71e6a568554d78072f5634267c90">DstResolvedOpaqueTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the set of opaque types in the destination modules who are getting a body from the source module. <a href="#ae32d71e6a568554d78072f5634267c90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TypeMapTy() {#aa275b2c48b86647c8013b29c85b4f958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{IRMover.cpp}::TypeMapTy::TypeMapTy (<a href="/web-llvm/docs/api/classes/llvm/irmover/identifiedstructtypeset">IRMover::IdentifiedStructTypeSet</a> &amp; DstStructTypesSet)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<p>Reference <a href="#addf4983735e6e2e6c9184c210d03c3c1">DstStructTypesSet</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addTypeMapping() {#a38ffc031e0ab9260c4521b5e5a8c16c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeMapTy::addTypeMapping (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that the specified type in the destination module is conceptually equivalent to the specified type in the source module.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### get() {#a30460dd0f1cb911d96c45a476cb2b4e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{IRMover.cpp}::TypeMapTy::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the mapped type to use for the specified input type from the source module.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>

</div>
</div>

### get() {#a4560aabfb53fdcd353203fdca21a0eab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{IRMover.cpp}::TypeMapTy::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *, 8 &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>

</div>
</div>

### get() {#acbedc4a67ef945addc0b70024a4e43be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * anonymous{IRMover.cpp}::TypeMapTy::get (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * T)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

### linkDefinedTypeBodies() {#a9458e9521315cb278dee23c71634b48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeMapTy::linkDefinedTypeBodies ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produce a body for an opaque type in the dest module from a type definition in the source module.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#addf4983735e6e2e6c9184c210d03c3c1">DstStructTypesSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aec7c3cecd0559788b36c46df1b2181c1">llvm::StructType::isOpaque</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#abd30ef90eb46b6ec20daf57888433380">llvm::StructType::setBodyOrError</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### areTypesIsomorphic() {#ad62885810aa160ae4da044597fc9f4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TypeMapTy::areTypesIsomorphic (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively walk this pair of types, returning true if they are isomorphic, false if they are not.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>

</div>
</div>

### remapType() {#ab9c19f1ac40445a784187b0c5cf76fd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{IRMover.cpp}::TypeMapTy::remapType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The client should implement this method if they want to remap types while mapping values.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DstStructTypesSet {#addf4983735e6e2e6c9184c210d03c3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRMover::IdentifiedStructTypeSet&amp; anonymous{IRMover.cpp}::TypeMapTy::DstStructTypesSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<p>Referenced by <a href="#a9458e9521315cb278dee23c71634b48e">linkDefinedTypeBodies</a> and <a href="#aa275b2c48b86647c8013b29c85b4f958">TypeMapTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DstResolvedOpaqueTypes {#ae32d71e6a568554d78072f5634267c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;StructType *, 16&gt; anonymous{IRMover.cpp}::TypeMapTy::DstResolvedOpaqueTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the set of opaque types in the destination modules who are getting a body from the source module.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>

</div>
</div>

### MappedTypes {#adcdf79ff0235e6bcf3ce508be4cb83ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Type *, Type *&gt; anonymous{IRMover.cpp}::TypeMapTy::MappedTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a mapping from a source type to a destination type to use.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>

</div>
</div>

### SpeculativeDstOpaqueTypes {#a4ca58d93a1070a0b8e95d610a53d4a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StructType *, 16&gt; anonymous{IRMover.cpp}::TypeMapTy::SpeculativeDstOpaqueTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>

</div>
</div>

### SpeculativeTypes {#a9df03bb7372ac66454c3773e2e29a614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Type *, 16&gt; anonymous{IRMover.cpp}::TypeMapTy::SpeculativeTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When checking to see if two subgraphs are isomorphic, we speculatively add types to MappedTypes, but keep track of them here in case we need to roll back.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>

</div>
</div>

### SrcDefinitionsToResolve {#a18de62c7b2f578643da867fd0f172c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StructType *, 16&gt; anonymous{IRMover.cpp}::TypeMapTy::SrcDefinitionsToResolve</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a list of non-opaque structs in the source module that are mapped to an opaque struct in the destination module.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
