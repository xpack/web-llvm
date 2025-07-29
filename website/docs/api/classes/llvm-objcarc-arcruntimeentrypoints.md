---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcarc/arcruntimeentrypoints
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARCRuntimeEntryPoints` Class

<p>Declarations for ObjC runtime functions and constants. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::objcarc::ARCRuntimeEntryPoints { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">Transforms/ObjCARC/ARCRuntimeEntryPoints.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a083983da9f74c1fe8e5f1a5650911405">ARCRuntimeEntryPoints</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad245a22b79f4982f4d74cb74f1c1a3f2">init</a> (Module *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99da12f4daa8b16a14bc097f8a31c7e3">get</a> (ARCRuntimeEntryPointKind kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af92f12e144751356f00f7db814c96e1a">getIntrinsicEntryPoint</a> (Function *&amp;Decl, Intrinsic::ID IntID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8c9c96e36cd1de53b7825c999a6d79">TheModule</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cached reference to the module which we will insert declarations into. <a href="#aff8c9c96e36cd1de53b7825c999a6d79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ca026d0393bfa8a2a8559551145b4c">AutoreleaseRV</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for ObjC runtime function objc_autoreleaseReturnValue. <a href="#a65ca026d0393bfa8a2a8559551145b4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a3c1f2a121cb0bfb5f6b0e729f2d4b1">Release</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for ObjC runtime function objc_release. <a href="#a9a3c1f2a121cb0bfb5f6b0e729f2d4b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8883407f47d4e771fc2b642f95828cb0">Retain</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for ObjC runtime function objc_retain. <a href="#a8883407f47d4e771fc2b642f95828cb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af65722928b3d5f5faeb03cba37579594">RetainBlock</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for ObjC runtime function objc_retainBlock. <a href="#af65722928b3d5f5faeb03cba37579594">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63e19c11e02b214ab705d3c7fc48f65">Autorelease</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for ObjC runtime function objc_autorelease. <a href="#aa63e19c11e02b214ab705d3c7fc48f65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ce80ab6ef2b6a7001ed4229c76cffff">StoreStrong</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for objc_storeStrong(). <a href="#a9ce80ab6ef2b6a7001ed4229c76cffff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d408d2936d9354e95e2d13c4b5fdd4a">RetainRV</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for objc_retainAutoreleasedReturnValue(). <a href="#a0d408d2936d9354e95e2d13c4b5fdd4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4323fda8c9908e88f235cabdd58d2c42">UnsafeClaimRV</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for objc_unsafeClaimAutoreleasedReturnValue(). <a href="#a4323fda8c9908e88f235cabdd58d2c42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b441498281235011198c36eaae7734">RetainAutorelease</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for objc_retainAutorelease(). <a href="#aa0b441498281235011198c36eaae7734">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb671ab2c78420292563e69333f8bd2">RetainAutoreleaseRV</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declaration for objc_retainAutoreleaseReturnValue(). <a href="#a9bb671ab2c78420292563e69333f8bd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Declarations for ObjC runtime functions and constants.</p>


<p>These are initialized lazily to avoid cluttering up the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> with unused declarations.</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARCRuntimeEntryPoints() {#a083983da9f74c1fe8e5f1a5650911405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcarc::ARCRuntimeEntryPoints::ARCRuntimeEntryPoints ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#a99da12f4daa8b16a14bc097f8a31c7e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::objcarc::ARCRuntimeEntryPoints::get (<a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644feb">ARCRuntimeEntryPointKind</a> kind)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644feba61710f61a521b1544f5f7ab5abac843d">llvm::objcarc::Autorelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644febac1dbc9b59747323224171927c310917d">llvm::objcarc::AutoreleaseRV</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644febab8e7b465df7c5979dc731d06e84ce2cf">llvm::objcarc::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644febaafece4245269582cb2f1009d4fb52047">llvm::objcarc::Retain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644febabb1c71135b6918c38ba5849bd7831df3">llvm::objcarc::RetainAutorelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644feba55348800790dfedea626658bdbae8f6f">llvm::objcarc::RetainAutoreleaseRV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644febaa5c9c22c7dedc1f8dd1d75b7c04460a9">llvm::objcarc::RetainBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644febaa1226b5450384ce6ea5ed47c317303ee">llvm::objcarc::RetainRV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644feba36fbf2cae591a406af658623583b0dba">llvm::objcarc::StoreStrong</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aa4b95e1b6c59a75f558794b32b644febae490705e8a3fd75e76afa1108289c24a">llvm::objcarc::UnsafeClaimRV</a>.</p>

</div>
</div>

### init() {#ad245a22b79f4982f4d74cb74f1c1a3f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::ARCRuntimeEntryPoints::init (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getIntrinsicEntryPoint() {#af92f12e144751356f00f7db814c96e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::objcarc::ARCRuntimeEntryPoints::getIntrinsicEntryPoint (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *&amp; Decl, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntID)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Autorelease {#aa63e19c11e02b214ab705d3c7fc48f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::Autorelease = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for ObjC runtime function objc_autorelease.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### AutoreleaseRV {#a65ca026d0393bfa8a2a8559551145b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::AutoreleaseRV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for ObjC runtime function objc_autoreleaseReturnValue.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### Release {#a9a3c1f2a121cb0bfb5f6b0e729f2d4b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::Release = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for ObjC runtime function objc_release.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### Retain {#a8883407f47d4e771fc2b642f95828cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::Retain = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for ObjC runtime function objc_retain.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### RetainAutorelease {#aa0b441498281235011198c36eaae7734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::RetainAutorelease = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for objc_retainAutorelease().</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### RetainAutoreleaseRV {#a9bb671ab2c78420292563e69333f8bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::RetainAutoreleaseRV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for objc_retainAutoreleaseReturnValue().</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### RetainBlock {#af65722928b3d5f5faeb03cba37579594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::RetainBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for ObjC runtime function objc_retainBlock.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### RetainRV {#a0d408d2936d9354e95e2d13c4b5fdd4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::RetainRV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for objc_retainAutoreleasedReturnValue().</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### StoreStrong {#a9ce80ab6ef2b6a7001ed4229c76cffff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::StoreStrong = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for objc_storeStrong().</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### TheModule {#aff8c9c96e36cd1de53b7825c999a6d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* llvm::objcarc::ARCRuntimeEntryPoints::TheModule = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cached reference to the module which we will insert declarations into.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

### UnsafeClaimRV {#a4323fda8c9908e88f235cabdd58d2c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::objcarc::ARCRuntimeEntryPoints::UnsafeClaimRV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declaration for objc_unsafeClaimAutoreleasedReturnValue().</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/arcruntimeentrypoints-h">ARCRuntimeEntryPoints.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
