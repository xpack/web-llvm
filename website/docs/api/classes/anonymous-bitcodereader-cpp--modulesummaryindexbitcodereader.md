---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ModuleSummaryIndexBitcodeReader` Class

<p>Class to manage reading and parsing function summary index bitcode files/sections. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase">BitcodeReaderBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f120c3d0b6eac0bf0e5969e53e47fed">ModuleSummaryIndexBitcodeReader</a> (BitstreamCursor Stream, StringRef Strtab, ModuleSummaryIndex &amp;TheIndex, StringRef ModulePath, std::function&lt; bool(GlobalValue::GUID)&gt; IsPrevailing=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f86888a27590c2d447d2f98b5f7cf8">parseModule</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool AllowNullValueInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae17531812ba8dfbc196a2f1e89bbdda0">getValueInfoFromValueId</a> (unsigned ValueId) -&gt; std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a612cd865c73f46d94163180f99741cd6">setValueGUID</a> (uint64_t ValueID, StringRef ValueName, GlobalValue::LinkageTypes Linkage, StringRef SourceFileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f3a32d89e5649dd603fbde64cb28430">parseValueSymbolTable</a> (uint64_t Offset, DenseMap&lt; unsigned, GlobalValue::LinkageTypes &gt; &amp;ValueIdToLinkageMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda6e4bc6e7ca69e4526a3d9a083fa0c">makeRefList</a> (ArrayRef&lt; uint64_t &gt; Record)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/functionsummary/#a434edf3518376986c8bb393f5e0eec33">FunctionSummary::EdgeTy</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52a8da83eb14baf7bf00c773f35eed4">makeCallList</a> (ArrayRef&lt; uint64_t &gt; Record, bool IsOldProfileFormat, bool HasProfile, bool HasRelBF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ddd9d112399fff7785a5baa3db54fcc">parseEntireSummary</a> (unsigned ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ce6c80af6a632ce7737db724e2eca1">parseModuleStringTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9fc503c94c857f347d9a6b4be49f43">parseTypeIdCompatibleVtableSummaryRecord</a> (ArrayRef&lt; uint64_t &gt; Record)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb24a85fec2d4bf22414e486ac9d294">parseTypeIdCompatibleVtableInfo</a> (ArrayRef&lt; uint64_t &gt; Record, size_t &amp;Slot, TypeIdCompatibleVtableInfo &amp;TypeId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess">FunctionSummary::ParamAccess</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6363d0f4c85f7f5457211dc9cf8f6e44">parseParamAccesses</a> (ArrayRef&lt; uint64_t &gt; Record)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b04e7faa35898db460ba47114b110f5">parseAllocInfoContext</a> (ArrayRef&lt; uint64_t &gt; Record, unsigned &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool AllowNullValueInfo = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae17531812ba8dfbc196a2f1e89bbdda0">getValueInfoFromValueId</a> (unsigned ValueId) -&gt; std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22befe0376e6d75b62b04d96e3c2a79a">addThisModule</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a1295eb8bd6bd6cb19ab8e79f5eaa2ba9">ModuleSummaryIndex::ModuleInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f25885aa6bff749fb6c6e695386ffd">getThisModule</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e08f014dee904d885696cbab9e2b5e0">TheIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The module index built during parsing. <a href="#a9e08f014dee904d885696cbab9e2b5e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b70e69adb9e2ba212bff08d39b1703">SeenGlobalValSummary</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates whether we have encountered a global value summary section yet during parsing. <a href="#a04b70e69adb9e2ba212bff08d39b1703">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa90232f40cefda923f45ccd59fd81ba">SeenValueSymbolTable</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates whether we have already parsed the VST, used for error checking. <a href="#afa90232f40cefda923f45ccd59fd81ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626ab0cd3c37072e4e5e844cc8f863dd">VSTOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to the offset of the VST recorded in the MODULE_CODE_VSTOFFSET record. <a href="#a626ab0cd3c37072e4e5e844cc8f863dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad941e1b39236a2b5a3b145f16e87d2a6">ValueIdToValueInfoMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12e3d4826726b846f99bbc28c025ac78">ModuleIdMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map populated during module path string table parsing, from the module <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to a string reference owned by the index's module path string table, used to correlate with combined index summary records. <a href="#a12e3d4826726b846f99bbc28c025ac78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7cb9e093209fe88a03f17defd5476d5">SourceFileName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Original source file name recorded in a bitcode record. <a href="#ac7cb9e093209fe88a03f17defd5476d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5969817dd62b2fe69a74a887042007be">ModulePath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string identifier given to this module by the client, normally the path to the bitcode file. <a href="#a5969817dd62b2fe69a74a887042007be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a611e1fdd6d13f9b5cefd16c75746c13d">IsPrevailing</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback to ask whether a symbol is the prevailing copy when invoked during combined index building. <a href="#a611e1fdd6d13f9b5cefd16c75746c13d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1120cc9b5887948889750f76679d8f20">StackIds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Saves the stack ids from the STACK_IDS record to consult when adding stack ids from the lists in the callsite and alloc entries to the index. <a href="#a1120cc9b5887948889750f76679d8f20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9481cc26f9596e91cc102d677741ba47">RadixArray</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Linearized radix tree of allocation contexts. <a href="#a9481cc26f9596e91cc102d677741ba47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class to manage reading and parsing function summary index bitcode files/sections.</p>

<p>Definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ModuleSummaryIndexBitcodeReader() {#a0f120c3d0b6eac0bf0e5969e53e47fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSummaryIndexBitcodeReader::ModuleSummaryIndexBitcodeReader (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> Stream, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Strtab, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; TheIndex, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModulePath, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>)&gt; IsPrevailing=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#a5a0d125f481ab8e82010f86ab22bc3a3">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::BitcodeReaderBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#a591454abad1d73b04a12f610819bd8a9">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::Strtab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getValueInfoFromValueId() {#ae17531812ba8dfbc196a2f1e89bbdda0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool AllowNullValueInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; ValueInfo, GlobalValue::GUID &gt; anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::getValueInfoFromValueId (unsigned ValueId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7177 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### parseModule() {#ae9f86888a27590c2d447d2f98b5f7cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ModuleSummaryIndexBitcodeReader::parseModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a8cd4dd534ba6c31e93a88ca286c4f0e5a9c269366c4dc4af235c9bb24fa46f915">llvm::bitc::BLOCKINFO_BLOCK_ID</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a2d7d3464870033ae244f10f24678e945">convertToString</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daca3afe4e93910906ab7d0c2e3bd2b90e">llvm::bitc::FULL_LTO_GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a9049fa6f0ceaa6bacf0a9bf51c0a2770">getDecodedLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da642102503aff012fc2975f165138b454">llvm::bitc::GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81a9036417d96ab001e460a784ee529748c">llvm::bitc::MODULE_CODE_ALIAS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81a0f98ccf6b361c7d704a34ae3abb8e9cf">llvm::bitc::MODULE_CODE_FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81a71e354585ad9af847e81899d9e9045cc">llvm::bitc::MODULE_CODE_GLOBALVAR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81ab91f122af3779bc28dea7291c3c801a7">llvm::bitc::MODULE_CODE_HASH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81a19650d5060a76b566188987c86d79f74">llvm::bitc::MODULE_CODE_SOURCE_FILENAME</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81a163b11eb41c06566dbc6e03e9273cc59">llvm::bitc::MODULE_CODE_VERSION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81a7ecbb9458f443298c9f6e46cdfaa1ff2">llvm::bitc::MODULE_CODE_VSTOFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daca3ed786c04791d9c4961711ebf6c294">llvm::bitc::MODULE_STRTAB_BLOCK_ID</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#a07768b10e40ef48e376f169fa695357b">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::parseVersionRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#ad04f7d6a08ad25b673e16a64825f640c">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::readBlockInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#aafd9537e3f52adde4974da00a91cc31a">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::readNameFromStrtab</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#ad08058cbd0be023ecb41322986993cd7">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::Stream</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#a39904e89e51e7aeb6242100c6d008178">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::UseStrtab</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933dad03d0513adaa3462afbc7be6241b7db2">llvm::bitc::VALUE_SYMTAB_BLOCK_ID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addThisModule() {#a22befe0376e6d75b62b04d96e3c2a79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSummaryIndexBitcodeReader::addThisModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### getThisModule() {#ab9f25885aa6bff749fb6c6e695386ffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSummaryIndex::ModuleInfo * ModuleSummaryIndexBitcodeReader::getThisModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1028 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### getValueInfoFromValueId() {#ae17531812ba8dfbc196a2f1e89bbdda0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool AllowNullValueInfo = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; ValueInfo, GlobalValue::GUID &gt; anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::getValueInfoFromValueId (unsigned ValueId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### makeCallList() {#ab52a8da83eb14baf7bf00c773f35eed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; FunctionSummary::EdgeTy, 0 &gt; ModuleSummaryIndexBitcodeReader::makeCallList (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record, bool IsOldProfileFormat, bool HasProfile, bool HasRelBF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### makeRefList() {#afda6e4bc6e7ca69e4526a3d9a083fa0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; ValueInfo, 0 &gt; ModuleSummaryIndexBitcodeReader::makeRefList (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### parseAllocInfoContext() {#a8b04e7faa35898db460ba47114b110f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; unsigned &gt; ModuleSummaryIndexBitcodeReader::parseAllocInfoContext (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record, unsigned &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### parseEntireSummary() {#a7ddd9d112399fff7785a5baa3db54fcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ModuleSummaryIndexBitcodeReader::parseEntireSummary (unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1013 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### parseModuleStringTable() {#aa3ce6c80af6a632ce7737db724e2eca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ModuleSummaryIndexBitcodeReader::parseModuleStringTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### parseParamAccesses() {#a6363d0f4c85f7f5457211dc9cf8f6e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; FunctionSummary::ParamAccess &gt; ModuleSummaryIndexBitcodeReader::parseParamAccesses (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### parseTypeIdCompatibleVtableInfo() {#a4cb24a85fec2d4bf22414e486ac9d294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSummaryIndexBitcodeReader::parseTypeIdCompatibleVtableInfo (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record, size_t &amp; Slot, <a href="/web-llvm/docs/api/namespaces/llvm/#ada2485ca228b028f8639ad86ce41d6ec">TypeIdCompatibleVtableInfo</a> &amp; TypeId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### parseTypeIdCompatibleVtableSummaryRecord() {#a5c9fc503c94c857f347d9a6b4be49f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSummaryIndexBitcodeReader::parseTypeIdCompatibleVtableSummaryRecord (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1015 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### parseValueSymbolTable() {#a8f3a32d89e5649dd603fbde64cb28430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ModuleSummaryIndexBitcodeReader::parseValueSymbolTable (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> &gt; &amp; ValueIdToLinkageMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### setValueGUID() {#a612cd865c73f46d94163180f99741cd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSummaryIndexBitcodeReader::setValueGUID (uint64_t ValueID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ValueName, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SourceFileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1003 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsPrevailing {#a611e1fdd6d13f9b5cefd16c75746c13d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;bool(GlobalValue::GUID)&gt; anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::IsPrevailing</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback to ask whether a symbol is the prevailing copy when invoked during combined index building.</p>

<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### ModuleIdMap {#a12e3d4826726b846f99bbc28c025ac78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint64_t, StringRef&gt; anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::ModuleIdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map populated during module path string table parsing, from the module <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to a string reference owned by the index's module path string table, used to correlate with combined index summary records.</p>

<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### ModulePath {#a5969817dd62b2fe69a74a887042007be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::ModulePath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string identifier given to this module by the client, normally the path to the bitcode file.</p>

<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### RadixArray {#a9481cc26f9596e91cc102d677741ba47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::RadixArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Linearized radix tree of allocation contexts.</p>


<p>See the description above the CallStackRadixTreeBuilder class in <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">ProfileData/MemProf.h</a> for format.</p>


<p>Definition at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### SeenGlobalValSummary {#a04b70e69adb9e2ba212bff08d39b1703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::SeenGlobalValSummary = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates whether we have encountered a global value summary section yet during parsing.</p>

<p>Definition at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### SeenValueSymbolTable {#afa90232f40cefda923f45ccd59fd81ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::SeenValueSymbolTable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates whether we have already parsed the VST, used for error checking.</p>

<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### SourceFileName {#ac7cb9e093209fe88a03f17defd5476d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::SourceFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Original source file name recorded in a bitcode record.</p>

<p>Definition at line 976 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### StackIds {#a1120cc9b5887948889750f76679d8f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::StackIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Saves the stack ids from the STACK_IDS record to consult when adding stack ids from the lists in the callsite and alloc entries to the index.</p>

<p>Definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### TheIndex {#a9e08f014dee904d885696cbab9e2b5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSummaryIndex&amp; anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::TheIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The module index built during parsing.</p>

<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### ValueIdToValueInfoMap {#ad941e1b39236a2b5a3b145f16e87d2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, std::pair&lt;ValueInfo, GlobalValue::GUID&gt; &gt; anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::ValueIdToValueInfoMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### VSTOffset {#a626ab0cd3c37072e4e5e844cc8f863dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::VSTOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to the offset of the VST recorded in the MODULE_CODE_VSTOFFSET record.</p>


<p>Used to enable on-demand parsing of the VST.</p>


<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
