---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/intrinsic/iitdescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IITDescriptor` Struct Reference

<p>This is a type descriptor which explains the type requirements of an intrinsic. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::Intrinsic::IITDescriptor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IITDescriptorKind { <a href="#a4bdf4f1a432b628d6c78a4942244c0fc">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ArgKind { <a href="#aa48e413b8ff95ee0224759e09bc05e9e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05dbd072c1bae120cfbe9a0b888bbefd">getArgumentNumber</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa48e413b8ff95ee0224759e09bc05e9e">ArgKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa6dc7ef06077494d709103a44248763">getArgumentKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef12d1a6bd65bd3aafa847df7953a43b">getOverloadArgNumber</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a836067268e2bcd54527e4a40cab75">getRefArgNumber</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#a4bdf4f1a432b628d6c78a4942244c0fc">llvm::Intrinsic::IITDescriptor::IITDescriptorKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03351835850db3fc6d4f4430fc35b481">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f30eafee97a66ad8878d9b0be0836ab">Integer_Width</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4631eb9d44bf213748a81473f85c15c">Float_Width</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762c43ce973df8e33994402fa2022c3c">Pointer_AddressSpace</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a0db71663d6d23636584eba86e8b4b">Struct_NumElements</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73182a468e6800cd351abb6a6c5257ba">Argument_Info</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a182c1d2eaaf77ea3d939c42e4e0462c9">Vector_Width</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">llvm::Intrinsic::IITDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3cc5504cf875355ffb44c4be7cde3d3"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">IITDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047b830ad41f2b7ebf9d1102f3f10821">get</a> (IITDescriptorKind K, unsigned Field)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">IITDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68248e57f5e48be90aad3c9ee0a1d5e1">get</a> (IITDescriptorKind K, unsigned short Hi, unsigned short Lo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">IITDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2939c2224325c678cad4d045e7f8d791">getVector</a> (unsigned Width, bool IsScalable)</td>
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

<p>This is a type descriptor which explains the type requirements of an intrinsic.</p>


<p>This is returned by getIntrinsicInfoTableEntries.</p>


<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ArgKind {#aa48e413b8ff95ee0224759e09bc05e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Intrinsic::IITDescriptor::ArgKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### IITDescriptorKind {#a4bdf4f1a432b628d6c78a4942244c0fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Intrinsic::IITDescriptor::IITDescriptorKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Void<a id="a4bdf4f1a432b628d6c78a4942244c0fca857d9d3e14e60b7d00a2607096ce0c60"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VarArg<a id="a4bdf4f1a432b628d6c78a4942244c0fca484f6ab5099f6776d80396a092c84ac5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MMX<a id="a4bdf4f1a432b628d6c78a4942244c0fcad078e0ac4447cbf137c6204424c8b73a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Token<a id="a4bdf4f1a432b628d6c78a4942244c0fca712d5c1287f92a8fbea35d83d0ccc75f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Metadata<a id="a4bdf4f1a432b628d6c78a4942244c0fca5157f3e7b95fecffafb2ba8d42429bc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Half<a id="a4bdf4f1a432b628d6c78a4942244c0fcabd342ca365e9c9fad8bb56e2ce305e1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BFloat<a id="a4bdf4f1a432b628d6c78a4942244c0fcaf235f6717c68a94a85e65f62cbbc1cf2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Float<a id="a4bdf4f1a432b628d6c78a4942244c0fca6dc7395b51cab89eca51926f6fc1cf3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Double<a id="a4bdf4f1a432b628d6c78a4942244c0fca3603faa1969eba79c799b51c01aa2b64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Quad<a id="a4bdf4f1a432b628d6c78a4942244c0fcad4d9186a77d3bc1a6e8c5dfb52889bc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Integer<a id="a4bdf4f1a432b628d6c78a4942244c0fcad8956869e778d2dfe5532559e7c1ecf9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Vector<a id="a4bdf4f1a432b628d6c78a4942244c0fca04581b997ef295baa87e1221f1054236"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer<a id="a4bdf4f1a432b628d6c78a4942244c0fca7bbcb21238bfb73b2c5b666ac7f19438"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Struct<a id="a4bdf4f1a432b628d6c78a4942244c0fcab4f1ac6b37c7049da733e72ef90eabcd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Argument<a id="a4bdf4f1a432b628d6c78a4942244c0fca486b75e3989ba93a6cdc34431291c3b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtendArgument<a id="a4bdf4f1a432b628d6c78a4942244c0fca96fdd05970b9e4e9c723ed8a9dad202d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TruncArgument<a id="a4bdf4f1a432b628d6c78a4942244c0fca8e8e4da223ec106852da84f310e70a7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HalfVecArgument<a id="a4bdf4f1a432b628d6c78a4942244c0fca8395d709fee30ad194e89ae8ffabe77c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SameVecWidthArgument<a id="a4bdf4f1a432b628d6c78a4942244c0fca0f4d1d546be9b2dcd98447aa2025c865"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VecOfAnyPtrsToElt<a id="a4bdf4f1a432b628d6c78a4942244c0fca1009ba462e1f603b84e09353affb33e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VecElementArgument<a id="a4bdf4f1a432b628d6c78a4942244c0fcaaf8734a000f80e2a1f7b045b78039150"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Subdivide2Argument<a id="a4bdf4f1a432b628d6c78a4942244c0fca936ed04793701ae718cf6633323b775e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Subdivide4Argument<a id="a4bdf4f1a432b628d6c78a4942244c0fcac1ffa06e40a405d13acde21e4b553479"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VecOfBitcastsToInt<a id="a4bdf4f1a432b628d6c78a4942244c0fca8de511b20956ddac6bc3a9359177a99c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMX<a id="a4bdf4f1a432b628d6c78a4942244c0fcaea820cc7f317726dd2835ae0a2b65645"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPCQuad<a id="a4bdf4f1a432b628d6c78a4942244c0fca5d9d3e96b39da7e7151e1b939feeea9e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AArch64Svcount<a id="a4bdf4f1a432b628d6c78a4942244c0fcae165c41b5afec76ce66a83747dc0edd3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getArgumentKind() {#aaa6dc7ef06077494d709103a44248763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgKind llvm::Intrinsic::IITDescriptor::getArgumentKind ()</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>References <a href="#a4bdf4f1a432b628d6c78a4942244c0fca486b75e3989ba93a6cdc34431291c3b3">Argument</a>, <a href="#a73182a468e6800cd351abb6a6c5257ba">Argument_Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca96fdd05970b9e4e9c723ed8a9dad202d">ExtendArgument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca8395d709fee30ad194e89ae8ffabe77c">HalfVecArgument</a>, <a href="#a03351835850db3fc6d4f4430fc35b481">Kind</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca0f4d1d546be9b2dcd98447aa2025c865">SameVecWidthArgument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca936ed04793701ae718cf6633323b775e">Subdivide2Argument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fcac1ffa06e40a405d13acde21e4b553479">Subdivide4Argument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca8e8e4da223ec106852da84f310e70a7d">TruncArgument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fcaaf8734a000f80e2a1f7b045b78039150">VecElementArgument</a> and <a href="#a4bdf4f1a432b628d6c78a4942244c0fca8de511b20956ddac6bc3a9359177a99c">VecOfBitcastsToInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>.</p>

</div>
</div>

### getArgumentNumber() {#a05dbd072c1bae120cfbe9a0b888bbefd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Intrinsic::IITDescriptor::getArgumentNumber ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>References <a href="#a4bdf4f1a432b628d6c78a4942244c0fca486b75e3989ba93a6cdc34431291c3b3">Argument</a>, <a href="#a73182a468e6800cd351abb6a6c5257ba">Argument_Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca96fdd05970b9e4e9c723ed8a9dad202d">ExtendArgument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca8395d709fee30ad194e89ae8ffabe77c">HalfVecArgument</a>, <a href="#a03351835850db3fc6d4f4430fc35b481">Kind</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca0f4d1d546be9b2dcd98447aa2025c865">SameVecWidthArgument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca936ed04793701ae718cf6633323b775e">Subdivide2Argument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fcac1ffa06e40a405d13acde21e4b553479">Subdivide4Argument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fca8e8e4da223ec106852da84f310e70a7d">TruncArgument</a>, <a href="#a4bdf4f1a432b628d6c78a4942244c0fcaaf8734a000f80e2a1f7b045b78039150">VecElementArgument</a> and <a href="#a4bdf4f1a432b628d6c78a4942244c0fca8de511b20956ddac6bc3a9359177a99c">VecOfBitcastsToInt</a>.</p>

</div>
</div>

### getOverloadArgNumber() {#aef12d1a6bd65bd3aafa847df7953a43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Intrinsic::IITDescriptor::getOverloadArgNumber ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>References <a href="#a73182a468e6800cd351abb6a6c5257ba">Argument_Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a03351835850db3fc6d4f4430fc35b481">Kind</a> and <a href="#a4bdf4f1a432b628d6c78a4942244c0fca1009ba462e1f603b84e09353affb33e6">VecOfAnyPtrsToElt</a>.</p>

</div>
</div>

### getRefArgNumber() {#ac4a836067268e2bcd54527e4a40cab75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Intrinsic::IITDescriptor::getRefArgNumber ()</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>References <a href="#a73182a468e6800cd351abb6a6c5257ba">Argument_Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a03351835850db3fc6d4f4430fc35b481">Kind</a> and <a href="#a4bdf4f1a432b628d6c78a4942244c0fca1009ba462e1f603b84e09353affb33e6">VecOfAnyPtrsToElt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#ab3cc5504cf875355ffb44c4be7cde3d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::Intrinsic::IITDescriptor llvm::Intrinsic::IITDescriptor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### Argument\_Info {#a73182a468e6800cd351abb6a6c5257ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Intrinsic::IITDescriptor::Argument_Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>Referenced by <a href="#aaa6dc7ef06077494d709103a44248763">getArgumentKind</a>, <a href="#a05dbd072c1bae120cfbe9a0b888bbefd">getArgumentNumber</a>, <a href="#aef12d1a6bd65bd3aafa847df7953a43b">getOverloadArgNumber</a> and <a href="#ac4a836067268e2bcd54527e4a40cab75">getRefArgNumber</a>.</p>

</div>
</div>

### Float\_Width {#ad4631eb9d44bf213748a81473f85c15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Intrinsic::IITDescriptor::Float_Width</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### Integer\_Width {#a5f30eafee97a66ad8878d9b0be0836ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Intrinsic::IITDescriptor::Integer_Width</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### Kind {#a03351835850db3fc6d4f4430fc35b481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Intrinsic::IITDescriptor::IITDescriptorKind llvm::Intrinsic::IITDescriptor::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="#aaa6dc7ef06077494d709103a44248763">getArgumentKind</a>, <a href="#a05dbd072c1bae120cfbe9a0b888bbefd">getArgumentNumber</a>, <a href="#aef12d1a6bd65bd3aafa847df7953a43b">getOverloadArgNumber</a> and <a href="#ac4a836067268e2bcd54527e4a40cab75">getRefArgNumber</a>.</p>

</div>
</div>

### Pointer\_AddressSpace {#a762c43ce973df8e33994402fa2022c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Intrinsic::IITDescriptor::Pointer_AddressSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### Struct\_NumElements {#a34a0db71663d6d23636584eba86e8b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Intrinsic::IITDescriptor::Struct_NumElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### Vector\_Width {#a182c1d2eaaf77ea3d939c42e4e0462c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount llvm::Intrinsic::IITDescriptor::Vector_Width</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a047b830ad41f2b7ebf9d1102f3f10821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IITDescriptor llvm::Intrinsic::IITDescriptor::get (<a href="#a4bdf4f1a432b628d6c78a4942244c0fc">IITDescriptorKind</a> K, unsigned Field)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### get() {#a68248e57f5e48be90aad3c9ee0a1d5e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IITDescriptor llvm::Intrinsic::IITDescriptor::get (<a href="#a4bdf4f1a432b628d6c78a4942244c0fc">IITDescriptorKind</a> K, unsigned short Hi, unsigned short Lo)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>

</div>
</div>

### getVector() {#a2939c2224325c678cad4d045e7f8d791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IITDescriptor llvm::Intrinsic::IITDescriptor::getVector (unsigned Width, bool IsScalable)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a79ea372f9aa69492fccfafc0e5a1589c">llvm::ElementCount::get</a> and <a href="#a4bdf4f1a432b628d6c78a4942244c0fca04581b997ef295baa87e1221f1054236">Vector</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
