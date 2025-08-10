---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/metadataloader/metadataloaderimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MetadataLoaderImpl` Class



## Declaration

<div class="doxyDeclaration">
class MetadataLoader::MetadataLoaderImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb7520e1af4a8c67e5e748c318661cf">MetadataLoaderImpl</a> (BitstreamCursor &amp;Stream, Module &amp;TheModule, BitcodeReaderValueList &amp;ValueList, MetadataLoaderCallbacks Callbacks, bool IsImporting)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5d5351419b40a9f891e4506bc2cae29">parseMetadata</a> (bool ModuleLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a METADATA_BLOCK. <a href="#ab5d5351419b40a9f891e4506bc2cae29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ecd201462122f9335d34acbffe539b">hasFwdRefs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c03dfb2b57239c6bd373c318367e898">getMetadataFwdRefOrLoad</a> (unsigned ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6642b0f5764b8789c6438e8d67ef2b3">lookupSubprogramForFunction</a> (Function *F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbcf75384a4053dc911ab2a0e925e802">hasSeenOldLoopTags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a81e1117a068de8d409b76e45c3e494">parseMetadataAttachment</a> (Function &amp;F, ArrayRef&lt; Instruction * &gt; InstructionList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse metadata attachments. <a href="#a4a81e1117a068de8d409b76e45c3e494">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71350293eab7be254484af9024a93da4">parseMetadataKinds</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the metadata kinds out of the METADATA_KIND_BLOCK. <a href="#a71350293eab7be254484af9024a93da4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a724b099962fdd048aae919e5c40b06bd">setStripTBAA</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc17ec8ee366779a066e10c220abcc92">isStrippingTBAA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b335d35488bd607bc0a4a493c1d93c0">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae39a61410ac4b8fa5f7714c9e1c102">shrinkTo</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75ca9c5e196ffeed4bb2048e629f41f">upgradeDebugIntrinsics</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711c0a90a8b0ebf05cdc4637784abda2">lazyLoadOneMDString</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>On-demand loading of a single <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a>. <a href="#a711c0a90a8b0ebf05cdc4637784abda2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2a509d1db2f004df776209d1eb2462">loadGlobalDeclAttachments</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load the global decl attachments, using the index built for lazy loading. <a href="#a2a2a509d1db2f004df776209d1eb2462">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4a26e753a73a273ff4f693ebeb4aac">lazyLoadModuleMetadataBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate the index above to enable lazily loading of metadata, and load the named metadata as well as the transitively referenced global <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>. <a href="#afe4a26e753a73a273ff4f693ebeb4aac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2225a8a161b9632d9dc8e82bacb0bd">lazyLoadOneMetadata</a> (unsigned Idx, PlaceholderQueue &amp;Placeholders)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>On-demand loading of a single metadata. <a href="#aed2225a8a161b9632d9dc8e82bacb0bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af002d81182c70e6eb490a31bfb64b36d">parseOneMetadata</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Code, PlaceholderQueue &amp;Placeholders, StringRef Blob, unsigned &amp;NextMetadataNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17883251ae95b50884ad38dfe7bc05ce">parseMetadataStrings</a> (ArrayRef&lt; uint64_t &gt; Record, StringRef Blob, function_ref&lt; void(StringRef)&gt; CallBack)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade272af99cf8ca4c20f6a62b6188b516">parseGlobalObjectAttachment</a> (GlobalObject &amp;GO, ArrayRef&lt; uint64_t &gt; Record)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35891085acec9ea38cb89bbf70c5f9a">parseMetadataKindRecord</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Record)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a single METADATA_KIND record, inserting result in MDKindMap. <a href="#ac35891085acec9ea38cb89bbf70c5f9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068e4d6bf55c11e2fc827c16eb36a291">resolveForwardRefsAndPlaceholders</a> (PlaceholderQueue &amp;Placeholders)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure that all forward-references and placeholders are resolved. <a href="#a068e4d6bf55c11e2fc827c16eb36a291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a162863a17294ec674f94e1da81055b52">upgradeCUSubprograms</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Upgrade old-style <a href="/web-llvm/docs/api/namespaces/cu">CU</a> &lt;-&gt; SP pointers to point from SP to <a href="/web-llvm/docs/api/namespaces/cu">CU</a>. <a href="#a162863a17294ec674f94e1da81055b52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b7112aa6dc07fd8a38db673498b05b">upgradeCUVariables</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Upgrade old-style bare DIGlobalVariables to DIGlobalVariableExpressions. <a href="#af5b7112aa6dc07fd8a38db673498b05b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ed66145175016331e7bf9d639b11a3">findEnclosingSubprogram</a> (DILocalScope *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29facee892dfc945b0e6e2b83d1d265c">upgradeCULocals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move local imports from <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a>'s 'imports' field to <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a>'s retainedNodes. <a href="#a29facee892dfc945b0e6e2b83d1d265c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a5da0dccf963bcd685ad94aba2acbe7">upgradeDeclareExpressions</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a leading DW_OP_deref from DIExpressions in a dbg.declare that describes a function argument. <a href="#a5a5da0dccf963bcd685ad94aba2acbe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a110b9e4e86d5ee827f1181ad115dc7">upgradeDIExpression</a> (uint64_t FromVersion, MutableArrayRef&lt; uint64_t &gt; &amp;Expr, SmallVectorImpl&lt; uint64_t &gt; &amp;Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Upgrade the expression from previous versions. <a href="#a6a110b9e4e86d5ee827f1181ad115dc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592cce8173f36d85d856abc3ff11e4f6">upgradeDebugInfo</a> (bool ModuleLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422b4e8e43cc609316aafeee64e0958d">callMDTypeCallback</a> (Metadata **Val, unsigned TypeID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">BitcodeReaderMetadataList</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a464d190abbb8fafedbe77db2c1354b49">MetadataList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist">BitcodeReaderValueList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449d88469d1128e5974acc8854cde1a9">ValueList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e1a727f1652da978021c816bee3afca">Stream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6573a074878e10c898f808b751368c">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad40965686534c20906488db439f4e4">TheModule</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/metadataloadercallbacks">MetadataLoaderCallbacks</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3becabb5384ba6bd1b910a082da6d51">Callbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1514ec2329a4d918fa765e81515856b9">IndexCursor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cursor associated with the lazy-loading of <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>. <a href="#a1514ec2329a4d918fa765e81515856b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f953889ab84011b778fe8782137b41">MDStringRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index that keeps track of <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> values. <a href="#a66f953889ab84011b778fe8782137b41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f611492f57956ed7f40e711f827b44b">GlobalMetadataBitPosIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index that keeps track of where to find a metadata record in the stream. <a href="#a8f611492f57956ed7f40e711f827b44b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a981d6cb98d3ab974aeb02a67c127ee98">GlobalDeclAttachmentPos</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cursor position of the start of the global decl attachments, to enable loading using the index built for lazy loading, instead of forward references. <a href="#a981d6cb98d3ab974aeb02a67c127ee98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad89c1d0136363f9245a3c7f58162e5b2">NumGlobalDeclAttachSkipped</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Baisic correctness check that we end up parsing all of the global decl attachments. <a href="#ad89c1d0136363f9245a3c7f58162e5b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d8a65f209e214b17c929d48f29c156">NumGlobalDeclAttachParsed</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> *, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614bb1d15798308b5badc991d8b3193e">CUSubprograms</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0969de6a0c143c251a2f682c31a78469">FunctionsWithSPs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functions that need to be matched with subprograms when upgrading old metadata. <a href="#a0969de6a0c143c251a2f682c31a78469">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8083b33c02434abec0f72d86df60408">MDKindMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e20ea5b301c8decef4245799d23d2e">StripTBAA</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9e58d8ab827a623af3f2e87d93e703">HasSeenOldLoopTags</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb0db0c443614b039f0404cc23051054">NeedUpgradeToDIGlobalVariableExpression</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa842756dd43d9f356e80160f8a3ff972">NeedDeclareExpressionUpgrade</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b69aefa6ebea6a5adf31c4fa0a207a8">ParentSubprogram</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> to the enclosing <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a>, if any. <a href="#a8b69aefa6ebea6a5adf31c4fa0a207a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88e88c0d8b0747a5ef58525d142978d">IsImporting</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if metadata is being parsed for a module being ThinLTO imported. <a href="#ae88e88c0d8b0747a5ef58525d142978d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MetadataLoaderImpl() {#a5bb7520e1af4a8c67e5e748c318661cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MetadataLoader::MetadataLoaderImpl::MetadataLoaderImpl (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist">BitcodeReaderValueList</a> &amp; ValueList, <a href="/web-llvm/docs/api/structs/llvm/metadataloadercallbacks">MetadataLoaderCallbacks</a> Callbacks, bool IsImporting)</td>
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



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMetadataFwdRefOrLoad() {#a2c03dfb2b57239c6bd373c318367e898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::MetadataLoader::MetadataLoaderImpl::getMetadataFwdRefOrLoad (unsigned ID)</td>
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



<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### hasFwdRefs() {#a55ecd201462122f9335d34acbffe539b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataLoader::MetadataLoaderImpl::hasFwdRefs ()</td>
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



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### hasSeenOldLoopTags() {#adbcf75384a4053dc911ab2a0e925e802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataLoader::MetadataLoaderImpl::hasSeenOldLoopTags ()</td>
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



<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### isStrippingTBAA() {#acc17ec8ee366779a066e10c220abcc92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataLoader::MetadataLoaderImpl::isStrippingTBAA ()</td>
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



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### lookupSubprogramForFunction() {#ae6642b0f5764b8789c6438e8d67ef2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * llvm::MetadataLoader::MetadataLoaderImpl::lookupSubprogramForFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### parseMetadata() {#ab5d5351419b40a9f891e4506bc2cae29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::MetadataLoaderImpl::parseMetadata (bool ModuleLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a METADATA_BLOCK.</p>


<p>If ModuleLevel is true then we are parsing module level metadata.</p>


<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp/#a21f0c64b20f0d34490ab42ee33674bab">DisableLazyLoading</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da6d85c95035de79006ae3a5dac19ee4a2">llvm::bitc::METADATA_BLOCK_ID</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### parseMetadataAttachment() {#a4a81e1117a068de8d409b76e45c3e494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataAttachment (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; InstructionList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse metadata attachments.</p>

<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a4a3aafff3f29eba4c6d639e6648c330c">llvm::MDNode::isTemporary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a1439ec3246fdaf3a3b4fb4f4e2683c5ca6a68c84bdb7ea2c3c9605c493f95f3e4">llvm::bitc::METADATA_ATTACHMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da6553316df9fbe50417fd8e4630b90ef4">llvm::bitc::METADATA_ATTACHMENT_ID</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a331b2acd066a224f2e98163aee07bf96">llvm::upgradeInstructionLoopAttachment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae7ee47904c2a7f2c3af3824c90b5a2ec">llvm::UpgradeTBAANode</a>.</p>

</div>
</div>

### parseMetadataKinds() {#a71350293eab7be254484af9024a93da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataKinds ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the metadata kinds out of the METADATA_KIND_BLOCK.</p>

<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a1439ec3246fdaf3a3b4fb4f4e2683c5cacd9207463da1cc7603576917ab4296d8">llvm::bitc::METADATA_KIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da5747b302b28e31fd8879df26646da087">llvm::bitc::METADATA_KIND_BLOCK_ID</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### setStripTBAA() {#a724b099962fdd048aae919e5c40b06bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::setStripTBAA (bool Value)</td>
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



<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### shrinkTo() {#a3ae39a61410ac4b8fa5f7714c9e1c102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::shrinkTo (unsigned N)</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### size() {#a2b335d35488bd607bc0a4a493c1d93c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MetadataLoader::MetadataLoaderImpl::size ()</td>
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



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### upgradeDebugIntrinsics() {#af75ca9c5e196ffeed4bb2048e629f41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::upgradeDebugIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### callMDTypeCallback() {#a422b4e8e43cc609316aafeee64e0958d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::callMDTypeCallback (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> ** Val, unsigned TypeID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### findEnclosingSubprogram() {#a12ed66145175016331e7bf9d639b11a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * llvm::MetadataLoader::MetadataLoaderImpl::findEnclosingSubprogram (<a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * S)</td>
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



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### lazyLoadModuleMetadataBlock() {#afe4a26e753a73a273ff4f693ebeb4aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; llvm::MetadataLoader::MetadataLoaderImpl::lazyLoadModuleMetadataBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate the index above to enable lazily loading of metadata, and load the named metadata as well as the transitively referenced global <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>.</p>

<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### lazyLoadOneMDString() {#a711c0a90a8b0ebf05cdc4637784abda2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * llvm::MetadataLoader::MetadataLoaderImpl::lazyLoadOneMDString (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>On-demand loading of a single <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a>.</p>


<p>Requires the index above to be populated.</p>


<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### lazyLoadOneMetadata() {#aed2225a8a161b9632d9dc8e82bacb0bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::lazyLoadOneMetadata (unsigned Idx, PlaceholderQueue &amp; Placeholders)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>On-demand loading of a single metadata.</p>


<p>Requires the index above to be populated.</p>


<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### loadGlobalDeclAttachments() {#a2a2a509d1db2f004df776209d1eb2462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; llvm::MetadataLoader::MetadataLoaderImpl::loadGlobalDeclAttachments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Load the global decl attachments, using the index built for lazy loading.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### parseGlobalObjectAttachment() {#ade272af99cf8ca4c20f6a62b6188b516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::MetadataLoaderImpl::parseGlobalObjectAttachment (<a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> &amp; GO, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### parseMetadataKindRecord() {#ac35891085acec9ea38cb89bbf70c5f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataKindRecord (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a single METADATA_KIND record, inserting result in MDKindMap.</p>

<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### parseMetadataStrings() {#a17883251ae95b50884ad38dfe7bc05ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataStrings (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; CallBack)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### parseOneMetadata() {#af002d81182c70e6eb490a31bfb64b36d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::MetadataLoaderImpl::parseOneMetadata (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Code, PlaceholderQueue &amp; Placeholders, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob, unsigned &amp; NextMetadataNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### resolveForwardRefsAndPlaceholders() {#a068e4d6bf55c11e2fc827c16eb36a291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::resolveForwardRefsAndPlaceholders (PlaceholderQueue &amp; Placeholders)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ensure that all forward-references and placeholders are resolved.</p>


<p>Iteratively lazy-loading metadata on-demand if needed.</p>


<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### upgradeCULocals() {#a29facee892dfc945b0e6e2b83d1d265c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::upgradeCULocals ()</td>
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

<p>Move local imports from <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a>'s 'imports' field to <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a>'s retainedNodes.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### upgradeCUSubprograms() {#a162863a17294ec674f94e1da81055b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::upgradeCUSubprograms ()</td>
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

<p>Upgrade old-style <a href="/web-llvm/docs/api/namespaces/cu">CU</a> &lt;-&gt; SP pointers to point from SP to <a href="/web-llvm/docs/api/namespaces/cu">CU</a>.</p>

<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### upgradeCUVariables() {#af5b7112aa6dc07fd8a38db673498b05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::upgradeCUVariables ()</td>
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

<p>Upgrade old-style bare DIGlobalVariables to DIGlobalVariableExpressions.</p>

<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### upgradeDebugInfo() {#a592cce8173f36d85d856abc3ff11e4f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::upgradeDebugInfo (bool ModuleLevel)</td>
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



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### upgradeDeclareExpressions() {#a5a5da0dccf963bcd685ad94aba2acbe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataLoader::MetadataLoaderImpl::upgradeDeclareExpressions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Remove a leading DW_OP_deref from DIExpressions in a dbg.declare that describes a function argument.</p>

<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### upgradeDIExpression() {#a6a110b9e4e86d5ee827f1181ad115dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::MetadataLoader::MetadataLoaderImpl::upgradeDIExpression (uint64_t FromVersion, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; uint64_t &gt; &amp; Expr, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Buffer)</td>
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

<p>Upgrade the expression from previous versions.</p>

<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Callbacks {#ad3becabb5384ba6bd1b910a082da6d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MetadataLoaderCallbacks llvm::MetadataLoader::MetadataLoaderImpl::Callbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### Context {#a9c6573a074878e10c898f808b751368c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::MetadataLoader::MetadataLoaderImpl::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### CUSubprograms {#a614bb1d15798308b5badc991d8b3193e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;DICompileUnit *, Metadata *&gt; &gt; llvm::MetadataLoader::MetadataLoaderImpl::CUSubprograms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### FunctionsWithSPs {#a0969de6a0c143c251a2f682c31a78469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;Function *, DISubprogram *, 16&gt; llvm::MetadataLoader::MetadataLoaderImpl::FunctionsWithSPs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Functions that need to be matched with subprograms when upgrading old metadata.</p>

<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### GlobalDeclAttachmentPos {#a981d6cb98d3ab974aeb02a67c127ee98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MetadataLoader::MetadataLoaderImpl::GlobalDeclAttachmentPos = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cursor position of the start of the global decl attachments, to enable loading using the index built for lazy loading, instead of forward references.</p>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### GlobalMetadataBitPosIndex {#a8f611492f57956ed7f40e711f827b44b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; llvm::MetadataLoader::MetadataLoaderImpl::GlobalMetadataBitPosIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index that keeps track of where to find a metadata record in the stream.</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### HasSeenOldLoopTags {#a0f9e58d8ab827a623af3f2e87d93e703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataLoader::MetadataLoaderImpl::HasSeenOldLoopTags = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### IndexCursor {#a1514ec2329a4d918fa765e81515856b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamCursor llvm::MetadataLoader::MetadataLoaderImpl::IndexCursor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cursor associated with the lazy-loading of <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>.</p>


<p>This is the easy way to keep around the right "context" (Abbrev list) to be able to jump in the middle of the metadata block and load any record.</p>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### IsImporting {#ae88e88c0d8b0747a5ef58525d142978d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataLoader::MetadataLoaderImpl::IsImporting = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if metadata is being parsed for a module being ThinLTO imported.</p>

<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### MDKindMap {#ae8083b33c02434abec0f72d86df60408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; llvm::MetadataLoader::MetadataLoaderImpl::MDKindMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### MDStringRef {#a66f953889ab84011b778fe8782137b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StringRef&gt; llvm::MetadataLoader::MetadataLoaderImpl::MDStringRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index that keeps track of <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> values.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### MetadataList {#a464d190abbb8fafedbe77db2c1354b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitcodeReaderMetadataList llvm::MetadataLoader::MetadataLoaderImpl::MetadataList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### NeedDeclareExpressionUpgrade {#aa842756dd43d9f356e80160f8a3ff972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataLoader::MetadataLoaderImpl::NeedDeclareExpressionUpgrade = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### NeedUpgradeToDIGlobalVariableExpression {#afb0db0c443614b039f0404cc23051054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataLoader::MetadataLoaderImpl::NeedUpgradeToDIGlobalVariableExpression = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### NumGlobalDeclAttachParsed {#a52d8a65f209e214b17c929d48f29c156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MetadataLoader::MetadataLoaderImpl::NumGlobalDeclAttachParsed = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### NumGlobalDeclAttachSkipped {#ad89c1d0136363f9245a3c7f58162e5b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MetadataLoader::MetadataLoaderImpl::NumGlobalDeclAttachSkipped = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Baisic correctness check that we end up parsing all of the global decl attachments.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### ParentSubprogram {#a8b69aefa6ebea6a5adf31c4fa0a207a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;DILocalScope *, DISubprogram *&gt; llvm::MetadataLoader::MetadataLoaderImpl::ParentSubprogram</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> to the enclosing <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a>, if any.</p>

<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### Stream {#a8e1a727f1652da978021c816bee3afca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamCursor&amp; llvm::MetadataLoader::MetadataLoaderImpl::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### StripTBAA {#aa5e20ea5b301c8decef4245799d23d2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataLoader::MetadataLoaderImpl::StripTBAA = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### TheModule {#a7ad40965686534c20906488db439f4e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; llvm::MetadataLoader::MetadataLoaderImpl::TheModule</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

### ValueList {#a449d88469d1128e5974acc8854cde1a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitcodeReaderValueList&amp; llvm::MetadataLoader::MetadataLoaderImpl::ValueList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
