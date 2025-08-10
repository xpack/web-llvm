---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-sanitizerbinarymetadata-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{SanitizerBinaryMetadata.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{SanitizerBinaryMetadata.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/machinesanitizerbinarymetadata">MachineSanitizerBinaryMetadata</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/metadatainfo">MetadataInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/sanitizerbinarymetadata">SanitizerBinaryMetadata</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac187378a0f56ec05fb9cc1661ae34207">MetadataInfoSet</a> = <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/metadatainfo">MetadataInfo</a> * &gt;</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace852e70dff0ecef1b5cc94cc123f1f5">STATISTIC</a> (NumMetadataCovered, "Metadata attached to covered functions")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46c8d25d37903e38762e4f5339feee4e">STATISTIC</a> (NumMetadataAtomics, "Metadata attached to atomics")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76462ca6bbe507a06d0a150aa68692b9">STATISTIC</a> (NumMetadataUAR, "Metadata attached to UAR functions")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sanitizerbinarymetadataoptions">SanitizerBinaryMetadataOptions</a> &amp;&amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a42dd1295f96a6a21d020a66f2e622">transformOptionsFromCl</a> (SanitizerBinaryMetadataOptions &amp;&amp;Opts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c12445454ce9ee3832e5b4b993b966">isUARSafeCall</a> (CallInst *CI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd05beff43e8533c652627d0f54ccbff">hasUseAfterReturnUnsafeUses</a> (Value &amp;V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe399ce3539695c0fe4afd689f4b6166">useAfterReturnUnsafe</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89d4abcbb96779cc08e69bd19abbac1d">maybeSharedMutable</a> (const Value *Addr)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf67b00f34ec08f2553419101c549cd">kVersionBase</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0060f3756ccadcd395bad43528c85090">kVersionPtrSizeRel</a> = (1u &lt;&lt; 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50d01beeac14c11daca9bcddc348246e">kCtorDtorPriority</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056efb5b02b6594fe9bf44f653857530">ClWeakCallbacks</a>("sanitizer-metadata-weak-callbacks", cl::desc("Declare callbacks extern weak, and only call if non-null."), cl::Hidden, cl::init(true))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cce364e05d0369c95d2083208b7a666">ClNoSanitize</a>("sanitizer-metadata-nosanitize-attr", cl::desc("Mark some metadata features uncovered in functions " "with associated no_sanitize attributes."), cl::Hidden, cl::init(true))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97dae3e1f5e240e62afc808354278a8d">ClEmitCovered</a>("sanitizer-metadata-covered", cl::desc("Emit PCs for covered functions."), cl::Hidden, cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9db1e448a261de3698ce53c6e8c592">ClEmitAtomics</a>("sanitizer-metadata-atomics", cl::desc("Emit PCs for atomic operations."), cl::Hidden, cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6679da1830d74d3b7874a97416622146">ClEmitUAR</a>("sanitizer-metadata-uar", cl::desc("Emit PCs for start of functions that are " "subject for use-after-return checking"), cl::Hidden, cl::init(false))</td>
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


<div class="doxySectionDef">

## Typedefs

### MetadataInfoSet {#ac187378a0f56ec05fb9cc1661ae34207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SanitizerBinaryMetadata.cpp}::MetadataInfoSet =  SetVector&lt;const MetadataInfo *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### hasUseAfterReturnUnsafeUses() {#abd05beff43e8533c652627d0f54ccbff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SanitizerBinaryMetadata.cpp}::hasUseAfterReturnUnsafeUses (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#abd05beff43e8533c652627d0f54ccbff">hasUseAfterReturnUnsafeUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aa1c12445454ce9ee3832e5b4b993b966">isUARSafeCall</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#abd05beff43e8533c652627d0f54ccbff">hasUseAfterReturnUnsafeUses</a> and <a href="#afe399ce3539695c0fe4afd689f4b6166">useAfterReturnUnsafe</a>.</p>

</div>
</div>

### isUARSafeCall() {#aa1c12445454ce9ee3832e5b4b993b966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SanitizerBinaryMetadata.cpp}::isUARSafeCall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>.</p>


<p>Referenced by <a href="#abd05beff43e8533c652627d0f54ccbff">hasUseAfterReturnUnsafeUses</a> and <a href="#afe399ce3539695c0fe4afd689f4b6166">useAfterReturnUnsafe</a>.</p>

</div>
</div>

### maybeSharedMutable() {#a89d4abcbb96779cc08e69bd19abbac1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SanitizerBinaryMetadata.cpp}::maybeSharedMutable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7912b6c9e7843ca9fd5a11e199bef617">llvm::PointerMayBeCaptured</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a3ed745230c0e6c52f4b1ec0dae8c07fb">llvm::Value::stripInBoundsOffsets</a>.</p>

</div>
</div>

### STATISTIC() {#ace852e70dff0ecef1b5cc94cc123f1f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SanitizerBinaryMetadata.cpp}::STATISTIC (NumMetadataCovered, "Metadata attached to covered functions")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a46c8d25d37903e38762e4f5339feee4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SanitizerBinaryMetadata.cpp}::STATISTIC (NumMetadataAtomics, "Metadata attached to atomics")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a76462ca6bbe507a06d0a150aa68692b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SanitizerBinaryMetadata.cpp}::STATISTIC (NumMetadataUAR, "Metadata attached to UAR functions")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>

</div>
</div>

### transformOptionsFromCl() {#a95a42dd1295f96a6a21d020a66f2e622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SanitizerBinaryMetadataOptions &amp;&amp; anonymous{SanitizerBinaryMetadata.cpp}::transformOptionsFromCl (<a href="/web-llvm/docs/api/structs/llvm/sanitizerbinarymetadataoptions">SanitizerBinaryMetadataOptions</a> &amp;&amp; Opts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>References <a href="#abb9db1e448a261de3698ce53c6e8c592">ClEmitAtomics</a>, <a href="#a97dae3e1f5e240e62afc808354278a8d">ClEmitCovered</a>, <a href="#a6679da1830d74d3b7874a97416622146">ClEmitUAR</a> and <a href="/web-llvm/docs/api/structs/llvm/sanitizerbinarymetadataoptions/#a56d8d769734eae6aeea0510cc8b6fb00">llvm::SanitizerBinaryMetadataOptions::Covered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/sanitizerbinarymetadata/#aee1947e945b89601cbdc7d19bd2c4ce8">anonymous{SanitizerBinaryMetadata.cpp}::SanitizerBinaryMetadata::SanitizerBinaryMetadata</a>.</p>

</div>
</div>

### useAfterReturnUnsafe() {#afe399ce3539695c0fe4afd689f4b6166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SanitizerBinaryMetadata.cpp}::useAfterReturnUnsafe (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#abd05beff43e8533c652627d0f54ccbff">hasUseAfterReturnUnsafeUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#aa1c12445454ce9ee3832e5b4b993b966">isUARSafeCall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ClEmitAtomics {#abb9db1e448a261de3698ce53c6e8c592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{SanitizerBinaryMetadata.cpp}::ClEmitAtomics("sanitizer-metadata-atomics", cl::desc("Emit PCs for atomic operations."), cl::Hidden, cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>Referenced by <a href="#a95a42dd1295f96a6a21d020a66f2e622">transformOptionsFromCl</a>.</p>

</div>
</div>

### ClEmitCovered {#a97dae3e1f5e240e62afc808354278a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{SanitizerBinaryMetadata.cpp}::ClEmitCovered("sanitizer-metadata-covered", cl::desc("Emit PCs for covered functions."), cl::Hidden, cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>Referenced by <a href="#a95a42dd1295f96a6a21d020a66f2e622">transformOptionsFromCl</a>.</p>

</div>
</div>

### ClEmitUAR {#a6679da1830d74d3b7874a97416622146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{SanitizerBinaryMetadata.cpp}::ClEmitUAR("sanitizer-metadata-uar", cl::desc("Emit PCs for start of functions that are " "subject for use-after-return checking"), cl::Hidden, cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>Referenced by <a href="#a95a42dd1295f96a6a21d020a66f2e622">transformOptionsFromCl</a>.</p>

</div>
</div>

### ClNoSanitize {#a9cce364e05d0369c95d2083208b7a666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{SanitizerBinaryMetadata.cpp}::ClNoSanitize("sanitizer-metadata-nosanitize-attr", cl::desc("Mark some metadata features uncovered in functions " "with associated no_sanitize attributes."), cl::Hidden, cl::init(true))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>

</div>
</div>

### ClWeakCallbacks {#a056efb5b02b6594fe9bf44f653857530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{SanitizerBinaryMetadata.cpp}::ClWeakCallbacks("sanitizer-metadata-weak-callbacks", cl::desc("Declare callbacks extern weak, and only call if non-null."), cl::Hidden, cl::init(true))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/sanitizerbinarymetadata/#aeda46a0421732a3d803584285212162f">anonymous{SanitizerBinaryMetadata.cpp}::SanitizerBinaryMetadata::run</a>.</p>

</div>
</div>

### kCtorDtorPriority {#a50d01beeac14c11daca9bcddc348246e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{SanitizerBinaryMetadata.cpp}::kCtorDtorPriority = 2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/sanitizerbinarymetadata/#aeda46a0421732a3d803584285212162f">anonymous{SanitizerBinaryMetadata.cpp}::SanitizerBinaryMetadata::run</a>.</p>

</div>
</div>

### kVersionBase {#acdf67b00f34ec08f2553419101c549cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{SanitizerBinaryMetadata.cpp}::kVersionBase = 2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>

</div>
</div>

### kVersionPtrSizeRel {#a0060f3756ccadcd395bad43528c85090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{SanitizerBinaryMetadata.cpp}::kVersionPtrSizeRel = (1u &lt;&lt; 16)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizerbinarymetadata-cpp">SanitizerBinaryMetadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
