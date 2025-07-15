---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/staticdatasplitter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `StaticDataSplitter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scopeexit-h">llvm/ADT/ScopeExit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/mbfiwrapper-h">llvm/CodeGen/MBFIWrapper.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">llvm/CodeGen/MachineBranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">llvm/CodeGen/MachineConstantPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">llvm/CodeGen/MachineJumpTableInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/staticdatasplitter">StaticDataSplitter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f2bea5bed4b5891545e7fb4a75f9276">STATISTIC</a> (NumHotJumpTables, "Number of hot jump tables seen")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d003fe5a107b9a45c50fe291987146">STATISTIC</a> (NumColdJumpTables, "Number of cold jump tables seen")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb60e23ff333fa1ca69fc727988503d">STATISTIC</a> (NumUnknownJumpTables, "Number of jump tables with unknown hotness. Option " "-static-data-default-hotness specifies the hotness.")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8929a6375e9d84ce1c667aa9e961de44">INITIALIZE_PASS_BEGIN</a> (StaticDataSplitter, DEBUG_TYPE, "Split static data", false, false) INITIALIZE_PASS_END(StaticDataSplitter</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a59c007354dfad2f618a37e6efaf7cd9b">MachineFunctionDataHotness</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5724fb13d79f5b64a503344b91eb169f">StaticDataDefaultHotness</a>("static-data-default-hotness", cl::Hidden, cl::desc("This option specifies the hotness of static data when profile " "information is unavailable"), cl::init(MachineFunctionDataHotness::Hot), cl::values(clEnumValN(MachineFunctionDataHotness::Hot, "hot", "Hot"), clEnumValN(MachineFunctionDataHotness::Cold, "cold", "Cold")))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Split</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Split</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c84512299ffc3cdce9e7cc96161e2d">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"static-<a href="#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>-splitter"</td>
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

### INITIALIZE\_PASS\_BEGIN() {#a8929a6375e9d84ce1c667aa9e961de44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/staticdatasplitter">StaticDataSplitter</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Split static data", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp">StaticDataSplitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### STATISTIC() {#a2f2bea5bed4b5891545e7fb4a75f9276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumHotJumpTables, "Number of hot jump tables seen")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp">StaticDataSplitter.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#af1d003fe5a107b9a45c50fe291987146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumColdJumpTables, "Number of cold jump tables seen")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp">StaticDataSplitter.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aaeb60e23ff333fa1ca69fc727988503d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumUnknownJumpTables, "Number of jump tables with unknown hotness. Option " "-static-<a href="#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>-default-hotness specifies the hotness.")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp">StaticDataSplitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### data {#ad2fefd8832b4b1ea3dbb1f621063bbff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Split data</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp">StaticDataSplitter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acf8f1219dc8b656e8e11c4b08edc8979">llvm::AArch64TargetLowering::AArch64TargetLowering</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a404cacae16324605710710194e08e5ca">llvm::dwarf_linker::parallel::SectionDescriptor::applyIntVal</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a4c0cd7586ca23f44571c798723fee65f">llvm::dwarf_linker::parallel::SectionDescriptor::applySLEB128</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a4e237e34d55840912a54fbef648eea92">llvm::dwarf_linker::parallel::SectionDescriptor::applyULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6bb52c5e399743f3422396aad97e704e">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0cb77086257991872561f79db33d3142">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bcchar6/#a9cbe2ed97afb0069d6b245d5cfa1ab89">llvm::BCChar6::assertValid</a>, <a href="/web-llvm/docs/api/classes/llvm/bcfixed/#a7a6e66441b8b3154728b53f45e6903be">llvm::BCFixed&lt; Width &gt;::assertValid</a>, <a href="/web-llvm/docs/api/classes/llvm/bcfixed/#ac9bad92da321e9d52eedbca3ad8c98e1">llvm::BCFixed&lt; Width &gt;::assertValid</a>, <a href="/web-llvm/docs/api/classes/llvm/bcliteral/#af978d1cd0c08d017f033c4a993a568a5">llvm::BCLiteral&lt; Value &gt;::assertValid</a>, <a href="/web-llvm/docs/api/classes/llvm/bcvbr/#a7abfc3127e42bd961c89e40cf102fdb2">llvm::BCVBR&lt; Width &gt;::assertValid</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcfield/#a7c1819fe0bf37a3e7aad2fa3a5aa4d10">llvm::detail::BCField&lt; Compound &gt;::assertValid</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#aaf7853428d9cb2b59fe268b757e3dc16">llvm::MutableArrayRef&lt; uint8_t &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5b6faabb08339ea1dd11e9d37a668634">llvm::StringRef::back</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#aae2bf8b46988a2fc0589e95903930c19">llvm::MutableArrayRef&lt; uint8_t &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ade4b8410fbe0406fc61d1db65d1cfa12">llvm::SmallString&lt; 0 &gt;::c_str</a>, <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-combine-recursive-helper/#a87cb33524db506474a9207907036a397">llvm::hashing::detail::hash_combine_recursive_helper::combine_data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae0c6424784f132b91eb387a3ee0b57c9">llvm::StringRef::compare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a805f6e017afb868ed3f50b1b76d35468">llvm::yaml::convertYAML</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ac2c31b7b3c778d12aa176f9253511f37">llvm::StringRef::count</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a80db7425f3e992ef519e25179f94fb56">llvm::DataExtractor::DataExtractor</a>, <a href="/web-llvm/docs/api/structs/llvm/object/dataregion/#aa114b224ab74aa54f72ef3f9d238b84d">llvm::object::DataRegion&lt; T &gt;::DataRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9202ca0a40ca22c6198342cf8b0dc050">llvm::StringRef::detectEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a9c4e8cde73237ab00ac91c380ff95f38">llvm::DWARFDataExtractor::DWARFDataExtractor</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a57f3eea5ad36a6b82ec5bb2b63363227">llvm::sys::DynamicLibrary::DynamicLibrary</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#a58810c8da2487ffae1714a997321c58e">llvm::DIEAbbrev::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/bcgenericrecordlayout/#affac6c467a59df0f58e3afdbeced562c">llvm::BCGenericRecordLayout&lt; BCLiteral&lt; RecordCode &gt;, Fields... &gt;::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/bcrecordlayout/#a7a4953a7566d6c135935985355fda247">llvm::BCRecordLayout&lt; RecordCode, Fields &gt;::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding/#ab6e68e79dc245aeff38c710e106e0b29">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-e92e567fbcfc8afd44242d623ff29b96/#a707d66256835aaba5f53cf6157df99ad">llvm::detail::BCRecordCoding&lt; BCArray&lt; ElementTy &gt; &gt;::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-e92e567fbcfc8afd44242d623ff29b96/#a2d08ccaf46363d002d905b3f3beb50fb">llvm::detail::BCRecordCoding&lt; BCArray&lt; ElementTy &gt; &gt;::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-b9c0cc53cb17fcebab888745f2cdc703/#a044776af18211267893a1a87eaff5c19">llvm::detail::BCRecordCoding&lt; BCBlob &gt;::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-7416a4930392106d56f3af1734eb69d7/#a7b37e8210c0732bf6de45a3216e1702e">llvm::detail::BCRecordCoding&lt; ElementTy &gt;::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/bcgenericrecordlayout/#ae7d7f30535b188ea68c4b3b617ad0483">llvm::BCGenericRecordLayout&lt; BCLiteral&lt; RecordCode &gt;, Fields... &gt;::emitRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/bcrecordlayout/#a9b33a4eb852189e7450033a30a34559d">llvm::BCRecordLayout&lt; RecordCode, Fields &gt;::emitRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a7dd171407e8c0e19195ea2039f3f83b6">llvm::RuntimeDyldImpl::emitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a9d959094f4544749c129c46034cbed67">llvm::MutableArrayRef&lt; uint8_t &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugarangeset/#a81576979ca20731e32ff1b245df0c5f3">llvm::DWARFDebugArangeSet::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist/#a25597c272c2c6da035416f2331dccfbd">llvm::DWARFDebugRangeList::extract</a>, <a href="/web-llvm/docs/api/structs/llvm/rangelistentry/#a02b8d98254f6a78f14c66d249db3bfc4">llvm::RangeListEntry::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a6fb86e9e92241fe6fe6b2058650e3a67">llvm::MutableArrayRef&lt; uint8_t &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid/#a00a95f6c10a5942e4d8d38ec5df0550a">llvm::sampleprof::FunctionId::FunctionId</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-764fe38a670fa71a18e1c5f119bcef9d/#a2895334c043839ae91cec9fc7eb3eded">llvm::DenseMapInfo&lt; ArrayRef&lt; T &gt;, void &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a6e4cc243fb344193485e9e4fe79399c7">llvm::dwarf_linker::parallel::SectionDescriptor::getIntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac17a520cef18422636f0fbdd13061acf">llvm::DWARFDie::getLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typetablecollection/#a6c3f409e4493fda630c4b0a267cd1e10">llvm::codeview::TypeTableCollection::getTypeName</a>, <a href="/web-llvm/docs/api/structs/llvm/md5/md5result/#a6cb733f826e3afeef8dea5b75abf2b04">llvm::MD5::MD5Result::high</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-764fe38a670fa71a18e1c5f119bcef9d/#a05dc2681024b3fb98cf31d200f4a6efe">llvm::DenseMapInfo&lt; ArrayRef&lt; T &gt;, void &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b371e12e065ff9d7153e1c150c733644/#a547adc894b538eab863a2c963f5015e1">llvm::DenseMapInfo&lt; StringRef, void &gt;::isEqual</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga2350c332ed29d2aa178ce014d01e9d1e">LLVMGetHostCPUName</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a7851b0072b1b5a3330cda84355b476d3">loadTestingFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/resolvererror/#a3f95909d868460a8b2582e1220bf6e86">llvm::ResolverError::log</a>, <a href="/web-llvm/docs/api/structs/llvm/md5/md5result/#a0c78a5721bb5677678f80f9d0589f028">llvm::MD5::MD5Result::low</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a9f5a19c97b7d16ce2d6b911af8848e0f">AbstractManglingParser&lt; Derived, Alloc &gt;::makeNodeArray</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldchecker/memoryregioninfo/#a55c6d739876650c3fd0c8eef99b7ab9e">llvm::RuntimeDyldChecker::MemoryRegionInfo::MemoryRegionInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a6d701804353d5d1bde8b11d46e945a">llvm::MutableArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ace9945d0e32337f9101716f572df0885">llvm::MCJIT::notifyFreeingObject</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a4c77fd10082d414ff13ef63a7655fde6">llvm::MCJIT::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ab9d50c6284d5976200ef42a076d3fb02">llvm::SmallString&lt; 0 &gt;::operator std::string</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aed45f95729e679cb0c160456fe94602b">llvm::StringRef::operator std::string_view</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36ad912277e94ac8b0db66aae63e49ad">llvm::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#aaed2ef7ac9490f46b0eacddd11dd015d">llvm::MutableArrayRef&lt; uint8_t &gt;::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3ae8d94051e57dabbf8ffabfcbc9063d">llvm::StringRef::operator[]</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#ac61404d428edea90fb2c5b180daf5361">llvm::jitlink::x86_64::optimizeGOTAndStubAccesses</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a7bc472aa7f200453c2fb1d5fbc404b66">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::populateSwMetadataGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding/#a899ed81dbda72496c2d105042da6acef">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding/#af455dc61361369b5ef61f16db37c3c66">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-b9c0cc53cb17fcebab888745f2cdc703/#a7d8cac6168225af1596b08e7c8ea0e0f">llvm::detail::BCRecordCoding&lt; BCBlob &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-7416a4930392106d56f3af1734eb69d7/#abcef45d7793b7eae2f2789356d2f34bd">llvm::detail::BCRecordCoding&lt; ElementTy &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/bcgenericrecordlayout/#add884a0033e0ba600114f12cc3ccd229">llvm::BCGenericRecordLayout&lt; BCLiteral&lt; RecordCode &gt;, Fields... &gt;::readRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/bcgenericrecordlayout/#aa8a015d7d91c6367f5c59c47f7303eb0">llvm::BCGenericRecordLayout&lt; BCLiteral&lt; RecordCode &gt;, Fields... &gt;::readRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ab6717ca91fe3922480a18f3e4250e611">llvm::object::MachOObjectFile::ReadULEB128s</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a97d45ce069c1a09ca84672df63acf096">llvm::StringRef::rfind</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#ae671f7b11f895cb673f6ee9a3c694359">llvm::MutableArrayRef&lt; uint8_t &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; 0 &gt;::str</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#a6ea6749cdcd6c8b985d67441ab66180c">llvm::object::IRObjectFile::symbol_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#a90838b84033f2f9576def8909bac94b7">llvm::object::IRObjectFile::symbol_end</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/symbollistwrapper/#a6314140be196f431a2944cb39b664abb">llvm::pdb::SymbolListWrapper::SymbolListWrapper</a>, <a href="/web-llvm/docs/api/groups/llvmctlto/#gaa9e95873812d6c95eaed4669f5a8e218">thinlto_codegen_add_module</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a6062a9632d9d9c4d35afd3e82970887e">validateMagicNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockverifier/#a358157e2ac5a3e8e85ed759cec5e1798">llvm::xray::BlockVerifier::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/writer/#a0c6b0217a29520ff740cb32952eac94f">llvm::objcopy::wasm::Writer::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a498db3edd7603cb3f985a6cde33c6827">llvm::xxh3_128bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23db35042db15bf83edbd2250ea0ee90">llvm::xxh3_64bits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a965bc5165ccf3827459771fa916d7a39">llvm::xxh3_64bits</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp">StaticDataSplitter.cpp</a>.</p>

</div>
</div>

### false {#ab0c84512299ffc3cdce9e7cc96161e2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Split false</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp">StaticDataSplitter.cpp</a>.</p>

</div>
</div>

### StaticDataDefaultHotness {#a5724fb13d79f5b64a503344b91eb169f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; MachineFunctionDataHotness &gt; StaticDataDefaultHotness("static-data-default-hotness", cl::Hidden, cl::desc("This option specifies the hotness of static data when profile " "information is unavailable"), cl::init(MachineFunctionDataHotness::Hot), cl::values(clEnumValN(MachineFunctionDataHotness::Hot, "hot", "Hot"), clEnumValN(MachineFunctionDataHotness::Cold, "cold", "Cold")))</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp">StaticDataSplitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"static-<a href="#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>-splitter"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp">StaticDataSplitter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
