---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `SymbolRecordMapping.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">llvm/DebugInfo/CodeView/SymbolRecordMapping.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-symbolrecordmapping-cpp-">anonymous{SymbolRecordMapping.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-symbolrecordmapping-cpp-/mapgap">MapGap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024855fc9193609b0d2f21c414c99f16">mapLocalVariableAddrRange</a> (CodeViewRecordIO &amp;IO, LocalVariableAddrRange &amp;Range)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>(X)&nbsp;&nbsp;&nbsp;...</td>
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

## Functions

### mapLocalVariableAddrRange() {#a024855fc9193609b0d2f21c414c99f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error mapLocalVariableAddrRange (<a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio">CodeViewRecordIO</a> &amp; IO, <a href="/web-llvm/docs/api/structs/llvm/codeview/localvariableaddrrange">LocalVariableAddrRange</a> &amp; Range)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp">SymbolRecordMapping.cpp</a>.</p>


<p>References <a href="#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a5d36269fb288350b629675233d6bdf16">llvm::codeview::CodeViewRecordIO::mapInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### error {#a9cdf893c7d17e47fa1ed8bebf92a5da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define error(X)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (auto EC = <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>)                                                             \
    return EC;
</div>
</dd>
</dl>

<p>Definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp">SymbolRecordMapping.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a3ec8976026c84988b82407550984aeed">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::checkDataSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a820bfb5af5692fdc662f2a2157d8830f">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::checkForP2AlignIfLoadStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a405b6cecd013148b4b443dd37854b4c4">llvm::decodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4900b597092f0dcdc7beed82d66e64eb">llvm::decodeSLEB128AndInc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3720bbfe79232f7792ab4b969dfbeed0">llvm::decodeULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4bf1e06696f761b02872434c1996cd28">llvm::decodeULEB128AndInc</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a2b03993e7552927412e8080455f7e6db">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::ensureEmptyNestingStack</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a3dc4a2fe21b3ba008ab4f2b3d937b7b6">anonymous{MIParser.cpp}::MIParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#ad76e0f6d5eb7cc49c6f72d861cafb10b">llvm::cl::Option::error</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata/#a7568407b9d745b41102b67fab20774a6">llvm::dwarf_linker::parallel::LinkingGlobalData::error</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#a92e0bbe12bdf67cbb1ad0ffe83ec982c">anonymous{WasmAsmParser.cpp}::WasmAsmParser::expect</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a37491eb33f82999c868246bb667b387a">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::expect</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a5bd77a86fbbad90c5d3df851b74c7635">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::expectIdent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a3d0c0fef256a92c13760a52971b805b5">getEnableSplitLTOUnitAndUnifiedFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a2d771e664c8cbfcf4ed1e5a51d052b29">llvm::IndexedInstrProfReader::getFunctionBitmap</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#abba771a0da60c937589b51b08c1f032d">llvm::IndexedInstrProfReader::getFunctionCounts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac94cf747f5fb3d8bef69ba5168873f55">llvm::getGCStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a8a83ecab002375cf09cf04f12470bf0e">llvm::IndexedInstrProfReader::getInstrProfRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac1eb4b5b3f31528f4b6fca7f19910e37">llvm::HexagonSubtarget::getIntrinsicId</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp/#a8aac3d1bd9fe9005fb56a087e0a824e2">getLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a9508697fd741b13841d7563c897e01f3">llvm::BitcodeModule::getLTOInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection/#a8eb7b146a5032a7f0f411dcdcbb8b4b3">llvm::codeview::LazyRandomTypeCollection::getOffsetOfType</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aaa1a1464db1a7a577a3c9fb3e76e6f75">getSingleModule</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a539ed03ca959115bcc032f7e7d655d42">llvm::IndexedInstrProfReader::getSymtab</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection/#a4c9f32907d1d49ee8974b2f68ce2cdf6">llvm::codeview::LazyRandomTypeCollection::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aac3e993fa38b2fd4caaacd62e4e152a4">hasObjCCategory</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a62f979fde2fca6e52e8789ff96ad830e">hasObjCCategoryInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#aea53e647298055af644a50c3a29e1411">llvm::MIRParserImpl::initializeCallSiteInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a69398364db52b18db9d922fec6d8eb87">llvm::MIRParserImpl::initializeConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a4e8962fa2139c288809acff971691109">llvm::MIRParserImpl::initializeJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab5a82b3045c92ee732ddca71ea91a65d">initStream</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a5fca99afcf20fdf62a04843e8825d03f">jumpToValueSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachinec-cpp/#a380dad8a77bc823770e1488a704ae8ca">LLVMTargetMachineEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportentry/#abd7a652c1046385908bf8934960d6c45">llvm::object::ExportEntry::MachOObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry/#abd7a652c1046385908bf8934960d6c45">llvm::object::MachOBindEntry::MachOObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machorebaseentry/#abd7a652c1046385908bf8934960d6c45">llvm::object::MachORebaseEntry::MachOObjectFile</a>, <a href="#a024855fc9193609b0d2f21c414c99f16">mapLocalVariableAddrRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#aa1cc88efb5daea0ae73b93eb7bc1ebd7">anonymous{BitcodeReader.cpp}::BitcodeReader::materializeForwardReferencedFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9f4458f3a19b697e8e24c4ebd319b35b">anonymous{BitcodeReader.cpp}::BitcodeReader::materializeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry/#a4a875fa809c0df5dff3223d539ae4c7c">llvm::object::MachOBindEntry::moveNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machorebaseentry/#aa36d5eb1318336e34265a7c2cc87b604">llvm::object::MachORebaseEntry::moveNext</a>, <a href="/web-llvm/docs/api/structs/anonymous-symbolrecordmapping-cpp-/mapgap/#a643b48d887def1d42e3e35ef38bf209c">anonymous{SymbolRecordMapping.cpp}::MapGap::operator()</a>, <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a9d7f3f2b0dc486075d4d462b7d744174">anonymous{MIParser.cpp}::MIParser::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystemparser/#acd3c926d77e4a86b21ee38acf61ebd32">llvm::vfs::RedirectingFileSystemParser::parse</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#abd8f29ecab2bd9275731d9762e4707b3">anonymous{MIParser.cpp}::MIParser::parseAddrspace</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4db9053414b75c0c90cb830a6b06b659">anonymous{MIParser.cpp}::MIParser::parseAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a28645da3fb06003fe7d32756e5ff929b">anonymous{MIParser.cpp}::MIParser::parseBasicBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aee1834e01cdaec2445802850ce7e92b4">anonymous{MIParser.cpp}::MIParser::parseBasicBlockDefinition</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a043bc88be0f1b6eac408827079cfcdf9">anonymous{MIParser.cpp}::MIParser::parseBasicBlockDefinitions</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ade810268bd683de9734a8fc78cc09266">anonymous{MIParser.cpp}::MIParser::parseBasicBlockLiveins</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ace3ad3f99a9b90046e398bc0c09d372b">anonymous{MIParser.cpp}::MIParser::parseBasicBlockSuccessors</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac3eddaf93bd102b2ee5c2d357f439000">anonymous{MIParser.cpp}::MIParser::parseBBID</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a77f5672641188aaed10066f78ebb24af">anonymous{MIParser.cpp}::MIParser::parseBlockAddressOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a9d55670b674a7d3bc9f2df1668d63be8">llvm::MIRParserImpl::parseCalledGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#abcac742b9eada6520eb78f1fcc9ba35d">llvm::MIRParserImpl::parseCalleeSavedRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#af740a2ed2a8eef5fe4c7c4fc710fd77b">anonymous{MIParser.cpp}::MIParser::parseCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4009b2b10bf09c0de7daf3062a89d803">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseCatchList</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a025beb578c2bc100c73a38c7d1b89a6d">anonymous{MIParser.cpp}::MIParser::parseCFIAddressSpace</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#afb68fcdc971343ff6082386d506d8cb8">anonymous{MIParser.cpp}::MIParser::parseCFIEscapeValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#af8e8e9f4122f068cfa33e5f17879c2ca">anonymous{MIParser.cpp}::MIParser::parseCFIOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7954356a1d4fe56e90cf50b2820cd502">anonymous{MIParser.cpp}::MIParser::parseCFIRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aa736beb031d297f0eade73ddf496a663">anonymous{MIParser.cpp}::MIParser::parseConstantPoolIndexOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a115cf2109c3a6f662603ef7879242c59">anonymous{MIParser.cpp}::MIParser::parseCustomRegisterMaskOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1c86a488cc8a95190bc351fac90405e2">anonymous{MIParser.cpp}::MIParser::parseDbgInstrRefOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a8ab2f664870f2d3c5f2036875672cf2a">anonymous{MIParser.cpp}::MIParser::parseDIExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a3ac7a622a7557191953d14a7961a79fa">anonymous{MIParser.cpp}::MIParser::parseDILocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ade676363a04db5e47aa6745312ca1ac6">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseDirectiveType</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a978abc1545ddae1a0e2cae4c02ab84b4">anonymous{MIParser.cpp}::MIParser::parseFixedStackFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4175071c6efe1557747e226a1e8fe2e2">anonymous{MIParser.cpp}::MIParser::parseFPImmediateOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a5ce71fb49004a1d688feb4434a27ab44">anonymous{MIParser.cpp}::MIParser::parseGlobalValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a9d2304dd85a4ed00a421fad88a95e33d">anonymous{MIParser.cpp}::MIParser::parseHeapAllocMarker</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d7396e09a5fcf968a2536b1375c356f">anonymous{MIParser.cpp}::MIParser::parseImmediateOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a02ce808485bec6d45ce163e0d50bb061">anonymous{MIParser.cpp}::MIParser::parseIntrinsicOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a9f34c58afe83b8b8dcc0299d74238a5a">anonymous{MIParser.cpp}::MIParser::parseIRBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1d3978999a978f56f13fb8aae7348436">anonymous{MIParser.cpp}::MIParser::parseIRBlockAddressTaken</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a08b018143e68b6cc36ab362d8b3b2626">anonymous{MIParser.cpp}::MIParser::parseIRConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4b9a684b49a12183c3ace195827aa01e">anonymous{MIParser.cpp}::MIParser::parseIRValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a0688b95ba758f0bdee953833ccbd7a4d">anonymous{MIParser.cpp}::MIParser::parseJumpTableIndexOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a702fc90a2ff78d5a79bfefb9022bffd6">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseLimits</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ae35da4f6e23c51b04dc46d9fcfc7c066">anonymous{MIParser.cpp}::MIParser::parseLiveoutRegisterMaskOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1119c30ad17d23efa29bf5593774867d">anonymous{MIParser.cpp}::MIParser::parseLowLevelType</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#afbccb941c0215a918667f3a574b976b9">llvm::MIRParserImpl::parseMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">anonymous{MIParser.cpp}::MIParser::parseMachineMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#af71425aaaccfd0af24609329584e5937">anonymous{MIParser.cpp}::MIParser::parseMachineMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#add4fede1a05c8d8148b6ef72f2da3494">llvm::MIRParserImpl::parseMachineMetadataNodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#af7b186f0f87ad315cbd814abed5dab72">anonymous{MIParser.cpp}::MIParser::parseMachineOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#adf35a52665d3f70d22acefe2846cb50f">anonymous{MIParser.cpp}::MIParser::parseMachineOperandAndTargetFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a0e477b282f9f9b58b7a5b2f9b0e4fdee">anonymous{MIParser.cpp}::MIParser::parseMachinePointerInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4324e2adebdc2aaca8ead3ed32de1667">anonymous{MIParser.cpp}::MIParser::parseMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/llparser/#a48a9cfa41a13b34d64b9dcb824d9075a">llvm::LLParser::parseMDField</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a47550df64460e1d79194f04e687fd4bc">anonymous{MIParser.cpp}::MIParser::parseMDNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ae1c0498b0c1e685f7decf651532fc0d9">anonymous{MIParser.cpp}::MIParser::parseMDNodeVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#adb56879a68087d3940588f0c5e124c4c">anonymous{MIParser.cpp}::MIParser::parseMemoryOperandFlag</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a58471cf0d31837efb05a35712ce9ad7c">anonymous{MIParser.cpp}::MIParser::parseMemoryPseudoSourceValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a83428d68b950a2dd6afc4c3292a82f49">anonymous{MIParser.cpp}::MIParser::parseMetadata</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#ab5d5351419b40a9f891e4506bc2cae29">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadata</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a4a81e1117a068de8d409b76e45c3e494">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataAttachment</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a71350293eab7be254484af9024a93da4">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataKinds</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1e4a55a09d735c80c50bbb0bc0f93158">anonymous{MIParser.cpp}::MIParser::parseNamedRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a9aaa7797bd399f29fdd9f7c55e2d182a">anonymous{MIParser.cpp}::MIParser::parseOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7eb95d6aa8ae9f89008ea38203b6e894">anonymous{MIParser.cpp}::MIParser::parseOptionalAtomicOrdering</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a62edb7a01e25422fd05722f2dc31445c">anonymous{MIParser.cpp}::MIParser::parseOptionalScope</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a16226e28e8a3155a820ac00075ed1892">anonymous{MIParser.cpp}::MIParser::parsePCSections</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4590f4e05f484028f3b4bf3387955427">anonymous{MIParser.cpp}::MIParser::parsePredicateOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a2c772f7f4d284b2ad112741a2f451bf4">anonymous{MIParser.cpp}::MIParser::parsePreOrPostInstrSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a6e4e4f98e1264c57604c033122d6fceb">anonymous{MIParser.cpp}::MIParser::parseRegisterClassOrBank</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a04eaad27a8fb5a2f35432c4a09fa2221">anonymous{MIParser.cpp}::MIParser::parseRegisterFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0cd181d3140028362e24cdc5d675ac16">llvm::MIRParserImpl::parseRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ad4d22d791beba2d17644bc14544e3877">anonymous{MIParser.cpp}::MIParser::parseRegisterOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4a9e6ec38e90a9bb7a0ee15119e1e709">anonymous{MIParser.cpp}::MIParser::parseRegisterTiedDefIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#ae7ca0cd3a609ecb42b8e91531f48bc28">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseRegTypeList</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a5b4cb75e4b5f5a31d24d90dcebed12e3">anonymous{MIParser.cpp}::MIParser::parseSectionID</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a70c970df35e9a1ebde9a6371fb8a6bc6">anonymous{MIParser.cpp}::MIParser::parseShuffleMaskOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a5b552ef481435267fbd31f081a657dcb">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseSingleFloat</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a453f3120ed4a899975ffac8bdda7417a">anonymous{MIParser.cpp}::MIParser::parseStackFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/llparser/#ab0a8518366b4a3c7ae8ffcfa342f7137">llvm::LLParser::parseStandaloneConstantValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a8b6fb16ad1a073527ca219f25f242b9d">anonymous{MIParser.cpp}::MIParser::parseStandaloneMBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ad9870bb0f0c1501dfa004566dbd5194b">anonymous{MIParser.cpp}::MIParser::parseStandaloneMDNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#afbc0c7f10ce30d72b70bd6982596e10b">anonymous{MIParser.cpp}::MIParser::parseStandaloneNamedRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a0e113b6be43fae44b91eaac633118ba8">anonymous{MIParser.cpp}::MIParser::parseStandaloneRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#af08d4f3585dbd246421362d8e6460e4a">anonymous{MIParser.cpp}::MIParser::parseStandaloneStackObject</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ab9db1ce7c4830ea5a0c54b0d843b5363">anonymous{MIParser.cpp}::MIParser::parseStandaloneVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a68d5b2d8a31ebf3554d265357f1baf28">anonymous{MIParser.cpp}::MIParser::parseSubRegisterIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a0c8d28ec07b076990dfad603aa041f9b">anonymous{MIParser.cpp}::MIParser::parseSubRegisterIndexOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a6273fafa595d2e1f8940595b5dccc8dc">anonymous{MIParser.cpp}::MIParser::parseTargetIndexOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a96f48f9a5690ef01b9d2574472e1f7e2">anonymous{MIParser.cpp}::MIParser::parseTypedImmediateOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#a07768b10e40ef48e376f169fa695357b">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::parseVersionRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abffa9a539aefe80919f291cd274faafb">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::pop</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4a69d0dfd4a74bd71f02776f7c275b38">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::popAndPushWithSameSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedcodegendatareader/#a3f022987ea846df57d06f91074954335">llvm::IndexedCodeGenDataReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader/#a6a6f3695c97c301eee0369ec5e669c61">llvm::TextCodeGenDataReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a18edc8cef7ae17b03b6d4f3ad2cda8b3">llvm::BitstreamCursor::ReadAbbrevRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ad3dcdf576f07a261c70f7eac121b3eec">readBlobInRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#ad04f7d6a08ad25b673e16a64825f640c">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::readBlockInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a172a26066ad6417d3ee4b506f7b441e8">llvm::IndexedInstrProfReader::readHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a08d4b82d8031b3254c5b3609e86583df">llvm::RawInstrProfReader&lt; IntPtrT &gt;::readHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/textinstrprofreader/#aef869625c91dde9e5539eb2a417eaef4">llvm::TextInstrProfReader::readHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#adfdf631a8d0d417904f24c6ff6d9ed03">readIdentificationBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a9f6235e5cdcd03f0d0dbb533debac0d9">readIdentificationCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#afa9c01a1d03b3af4714df3976056d46b">readModuleTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a05a803cfcad115ccd2b27e0ab751a078">llvm::IndexedInstrProfReader::readNextRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a0c2ab2403722f1441ecf1037c7e8ce7c">llvm::RawInstrProfReader&lt; IntPtrT &gt;::readNextRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/textinstrprofreader/#a7d3a3124492d7f44aeebfea0d19e0e37">llvm::TextInstrProfReader::readNextRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a42cc3ae15d37346d7ca743801b572770">readTriple</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-regex-cpp-/#a2cf0de01ea6bd871ff2bc908265cb0f0">anonymous{Regex.cpp}::RegexErrorToString</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection/#a88666e96d35b7e7e26892eb8424728b3">llvm::codeview::LazyRandomTypeCollection::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/llparser/#aeabb9a69009bc6019e909b931db71937">llvm::LLParser::Run</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/alias/#a9ed0b7cd9d3e9617f8e4b36ccc384206">llvm::cl::alias::setAliasFor</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0909a505055aae0cb9dee8e5730b3724">llvm::MIRParserImpl::setupRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#a1ef2fb8f19fa17d3e0445cc0f00b8a9a">llvm::CodeGenDataReader::success</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#a6fd927accec00ab7a4178b5290fcdb4b">llvm::InstrProfReader::success</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#acc7f16c0553ca0c637b42907ff64b9f5">llvm::DWARFVerifier::summarize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#a5188e82473da31b6460f80c0612b4d79">llvm::DWARFVerifier::verifyDebugStrOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#a17748af8672ec69e3715d19c6f1d21c8">llvm::codeview::TypeRecordMapping::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#abacef635e983790e9987ec66c97741f9">llvm::codeview::TypeRecordMapping::visitMemberEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecordmapping/#ac071b7f9eb995f4bbc5adde6f938b536">llvm::codeview::SymbolRecordMapping::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecordmapping/#a1aae7efbe35d635a423c6459f25f5a04">llvm::codeview::SymbolRecordMapping::visitSymbolEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#a0b455766e2cade6732d4d6680e4512e4">llvm::codeview::TypeRecordMapping::visitTypeBegin</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#ab16fc3b46e5820e7fa3fbcdc28fbe95c">llvm::codeview::TypeRecordMapping::visitTypeEnd</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
