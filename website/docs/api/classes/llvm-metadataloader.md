---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/metadataloader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MetadataLoader` Class Reference

<p>Helper class that handles loading Metadatas and keeping them available. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MetadataLoader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">Bitcode/Reader/MetadataLoader.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7663a50efd7b21f8483349b7e4d47408">MetadataLoader</a> (BitstreamCursor &amp;Stream, Module &amp;TheModule, BitcodeReaderValueList &amp;ValueList, bool IsImporting, MetadataLoaderCallbacks Callbacks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55afe4164d1610aaba4c543d21244c99">MetadataLoader</a> (MetadataLoader &amp;&amp;)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db417cf51f57ed1081e947f82d2db7e">~MetadataLoader</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadataloader">MetadataLoader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2a56fc8179345f30225758db4f6adb">operator=</a> (MetadataLoader &amp;&amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d55ca912c114ec1720fcaf32dd4360d">parseModuleMetadata</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7b1e6efd2239f16d80d9eebf7cf721">parseFunctionMetadata</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da07a79d3a7382bc009dbee67218741">setStripTBAA</a> (bool StripTBAA=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the mode to strip TBAA metadata on load. <a href="#a9da07a79d3a7382bc009dbee67218741">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d19527d8359961ed5060235b112fad">isStrippingTBAA</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the Loader is stripping TBAA metadata. <a href="#aa7d19527d8359961ed5060235b112fad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc84b9d84b7bac260ce37dae8a3107bf">hasFwdRefs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799cb501f821cc03e8dc95dea29d8787">getMetadataFwdRefOrLoad</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the given metadata, creating a replaceable forward reference if necessary. <a href="#a799cb501f821cc03e8dc95dea29d8787">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb386b970ebefd8a0e667b3574518f37">lookupSubprogramForFunction</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> metadata for a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> if any, null otherwise. <a href="#abb386b970ebefd8a0e667b3574518f37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa3cb789f207276c40bd0b3f5830299d">parseMetadataAttachment</a> (Function &amp;F, ArrayRef&lt; Instruction * &gt; InstructionList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a <span class="doxyComputerOutput">METADATA_ATTACHMENT</span> block for a function. <a href="#aaa3cb789f207276c40bd0b3f5830299d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d082cb18ad061683df8f6e3dc1b0959">parseMetadataKinds</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a <span class="doxyComputerOutput">METADATA_KIND</span> block for the current module. <a href="#a8d082cb18ad061683df8f6e3dc1b0959">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe51816119ee4f37ac90a14ed8d97e3b">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88ddd0875b67b0b3af1dd5da677d3ae4">shrinkTo</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820ffc587c59d62cf589b71d54bde022">upgradeDebugIntrinsics</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform bitcode upgrades on llvm.dbg.* calls. <a href="#a820ffc587c59d62cf589b71d54bde022">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85269e113046a90079005122ef0c2902">parseMetadata</a> (bool ModuleLevel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl">MetadataLoaderImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e6d0f1b4c3fbad676bd242fc32b5a9">Pimpl</a></td>
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

<p>Helper class that handles loading Metadatas and keeping them available.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MetadataLoader() {#a7663a50efd7b21f8483349b7e4d47408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MetadataLoader::MetadataLoader (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist">BitcodeReaderValueList</a> &amp; ValueList, bool IsImporting, <a href="/web-llvm/docs/api/structs/llvm/metadataloadercallbacks">MetadataLoaderCallbacks</a> Callbacks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2501 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a55afe4164d1610aaba4c543d21244c99">MetadataLoader</a>, <a href="#aed2a56fc8179345f30225758db4f6adb">operator=</a> and <a href="#a0db417cf51f57ed1081e947f82d2db7e">~MetadataLoader</a>.</p>

</div>
</div>

### MetadataLoader() {#a55afe4164d1610aaba4c543d21244c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MetadataLoader::MetadataLoader (<a href="/web-llvm/docs/api/classes/llvm/metadataloader">MetadataLoader</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2497 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>References <a href="#a7663a50efd7b21f8483349b7e4d47408">MetadataLoader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MetadataLoader() {#a0db417cf51f57ed1081e947f82d2db7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MetadataLoader::~MetadataLoader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>.</p>


<p>Reference <a href="#a7663a50efd7b21f8483349b7e4d47408">MetadataLoader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aed2a56fc8179345f30225758db4f6adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MetadataLoader &amp; MetadataLoader::operator= (<a href="/web-llvm/docs/api/classes/llvm/metadataloader">MetadataLoader</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2493 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="#a7663a50efd7b21f8483349b7e4d47408">MetadataLoader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMetadataFwdRefOrLoad() {#a799cb501f821cc03e8dc95dea29d8787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * MetadataLoader::getMetadataFwdRefOrLoad (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the given metadata, creating a replaceable forward reference if necessary.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2516 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### hasFwdRefs() {#afc84b9d84b7bac260ce37dae8a3107bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MetadataLoader::hasFwdRefs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2512 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### isStrippingTBAA() {#aa7d19527d8359961ed5060235b112fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MetadataLoader::isStrippingTBAA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the Loader is stripping TBAA metadata.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2537 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### lookupSubprogramForFunction() {#abb386b970ebefd8a0e667b3574518f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * MetadataLoader::lookupSubprogramForFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> metadata for a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> if any, null otherwise.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2520 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### parseFunctionMetadata() {#a1d7b1e6efd2239f16d80d9eebf7cf721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::parseFunctionMetadata ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#aee16ef63867cb58a1e046d39fb99e49f">parseMetadata</a>.</p>

</div>
</div>

### parseMetadataAttachment() {#aaa3cb789f207276c40bd0b3f5830299d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MetadataLoader::parseMetadataAttachment (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; InstructionList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a <span class="doxyComputerOutput">METADATA_ATTACHMENT</span> block for a function.</p>

<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2524 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### parseMetadataKinds() {#a8d082cb18ad061683df8f6e3dc1b0959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MetadataLoader::parseMetadataKinds ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a <span class="doxyComputerOutput">METADATA_KIND</span> block for the current module.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2529 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### parseModuleMetadata() {#a9d55ca912c114ec1720fcaf32dd4360d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::parseModuleMetadata ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#aee16ef63867cb58a1e046d39fb99e49f">parseMetadata</a>.</p>

</div>
</div>

### setStripTBAA() {#a9da07a79d3a7382bc009dbee67218741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MetadataLoader::setStripTBAA (bool StripTBAA=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the mode to strip TBAA metadata on load.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2533 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### shrinkTo() {#a88ddd0875b67b0b3af1dd5da677d3ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MetadataLoader::shrinkTo (unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2540 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### size() {#abe51816119ee4f37ac90a14ed8d97e3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MetadataLoader::size ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2539 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### upgradeDebugIntrinsics() {#a820ffc587c59d62cf589b71d54bde022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MetadataLoader::upgradeDebugIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform bitcode upgrades on llvm.dbg.* calls.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2542 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### parseMetadata() {#a85269e113046a90079005122ef0c2902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MetadataLoader::parseMetadata (bool ModuleLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>, definition at line 2508 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Pimpl {#a37e6d0f1b4c3fbad676bd242fc32b5a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MetadataLoaderImpl&gt; llvm::MetadataLoader::Pimpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
