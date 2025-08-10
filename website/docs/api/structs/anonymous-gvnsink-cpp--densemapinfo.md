---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-gvnsink-cpp-/densemapinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DenseMapInfo` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename ModelledPHI&gt;
struct anonymous{GVNSink.cpp}::DenseMapInfo&lt;ModelledPHI&gt; { ... }
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ModelledPHI&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi">ModelledPHI</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1423601a8e4ec304e0756df4e761ebbb">getEmptyKey</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ModelledPHI&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi">ModelledPHI</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9571e26b946751eaf015a9b8dc508be9">getTombstoneKey</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ModelledPHI&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a86544e5fd2336905e43348d2fd546094">getHashValue</a> (const ModelledPHI &amp;V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ModelledPHI&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a17c9fc217e2ec4f12e8c2a27f783bcae">isEqual</a> (const ModelledPHI &amp;LHS, const ModelledPHI &amp;RHS)</td>
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


<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getEmptyKey() {#a1423601a8e4ec304e0756df4e761ebbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ModelledPHI&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModelledPHI &amp; anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey ()</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi/#a9e315ee3f034c5d47eb479382bcad6d5">anonymous{GVNSink.cpp}::ModelledPHI::createDummy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#af4d4bfb09d6c352cfd4373d1e71ff8c8">llvm::object::MinidumpFile::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopvectorize-cpp-/csedensemapinfo/#a658190e47d719896a310288b63b7e67c">anonymous{LoopVectorize.cpp}::CSEDenseMapInfo::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/anonstructtypekeyinfo/#a3dc4791523ef39529b94ae2ac74c7175">llvm::AnonStructTypeKeyInfo::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a2c94f3689753f814562b13d0c7f926b/#aea1489296ea61ec5d26960999c4ee785">llvm::DenseMapInfo&lt; AA::RangeTy &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-00c712b9f8119dbcd9df11fd9c730cfe/#a465ef31db4862b716965f971782c116c">llvm::DenseMapInfo&lt; AACacheLoc &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2fb65b0a1a0a6b552e5196839bac56e7/#a0551e3c37dcb26e5d92004efafcaec0d">llvm::DenseMapInfo&lt; AAMDNodes &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-75d9b96a5bc6b9a604536279a1a95d7e/#affe39e858a140961d7340f2b8d684741">llvm::DenseMapInfo&lt; APFixedPoint &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-0f253a473d8d464a041ca5a9506bff11/#a1cea64b6278ab66f336046c90371cce4">llvm::DenseMapInfo&lt; APSInt, void &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-339e92432108a12c437bc5c3804a88b0/#a95cb0505b2ba4d8077e17b88f59bed38">llvm::DenseMapInfo&lt; at::VarRecord &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a04d74e4f379575f260e088ee7b633ff/#a3ccffdb7a0dd79a29639ee57325c12af">llvm::DenseMapInfo&lt; CachedHashStringRef &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-8cd2653b8375ccc7028cd1fd71875103/#abe0f1875010e7a2cb15ea711165c8f3a">llvm::DenseMapInfo&lt; CallValue &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-c8d484646dba98501f9b84f048d66ace/#ad8118c6f67018eac6b833e835875ef26">llvm::DenseMapInfo&lt; codeview::TypeIndex &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#a18c61803796493f72b0586769c4a4411">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2d0489b7ff465b00b1924bf0f5134b07/#a165f7260533cffefcd1f0428d469dbca">llvm::DenseMapInfo&lt; FrozenIndPHIInfo &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-e59b5bf2cc70d18adda69217a6ba3ef2/#af5a080ccf053b9664f6dda5bedc723e3">llvm::DenseMapInfo&lt; GEPValue &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-5591f21651d12162b1c376a5f4e15eb4/#ae2648b81dbd36a455a01075f36c695c0">llvm::DenseMapInfo&lt; gsym::FileEntry &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-f25b6c8d7819e772b81b8f6ba4da34ed/#ade9c71940a71308e78727b9187d6d69b">llvm::DenseMapInfo&lt; MCRegister &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-4f2a5bd91682bf5740574941f9d3c82c/#aa2220487d96b01b1cb4b1c4dfd01d798">llvm::DenseMapInfo&lt; MemoryLocation &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-ac8f46afffb89cdee88eb84de0c5ff04/#ac9f27c5f4b485fa4c3101856d82d40bc">llvm::DenseMapInfo&lt; MemoryLocOrCall &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a38f6a722ee6303b849007724d9da2bb/#ab1d92916d2d67b444a4defef244aaff1">llvm::DenseMapInfo&lt; orc::ExecutorAddr &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9b46fd3afaa0cf1f8c6be79306c49695/#afa6382015a673a11e47d6cdd9d4d29bf">llvm::DenseMapInfo&lt; PoisoningVH&lt; T &gt; &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-1fffb1beefe8443d1c161dda7a88fc8c/#a42cb3e178d0e0a3c2e9fa89c4e899cdb">llvm::DenseMapInfo&lt; SimpleValue &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-52732d196168d4457ac8b19ac19fffa7/#af0476dea2b383630376dc0e175533294">llvm::DenseMapInfo&lt; std::tuple&lt; Ts... &gt; &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-f0f922b85f106c4a3f6f55bfb8e595ef/#a591d7cc8f55f1d902f42d888187dd512">llvm::DenseMapInfo&lt; std::variant&lt; Ts... &gt; &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a5e8ac4b4d72810d165b1ceb2eae9222/#a3f37aec789d75e38d285b6bc5e953d77">llvm::DenseMapInfo&lt; UniqueBBID &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-cf976c6008d17910e6e4c099545e7635/#a5acffc352bb8021da0595e1a48e309a5">llvm::DenseMapInfo&lt; ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt; &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-fbbd89e197847d24411e9fd99b4d0911/#a24348df7590289de0c324dfb6994fa1a">llvm::DenseMapInfo&lt; VTableSlot &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b15fb43ec6f8abbffe4d2a73ea4ec543/#ae865988944d12c74816611b169387dd1">llvm::DenseMapInfo&lt; VTableSlotSummary &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2a7e6051b930a8ee63f30351950c0c61/#a41d949ef50ef7e871403a9b778f74776">llvm::DenseMapInfo&lt; wasm::WasmTableType, void &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-0a20a4520b751e0749348b099f298bed/#a416b7bf5cde9bc72df5e5fc07ce56abf">llvm::DenseMapInfo&lt; WeakVH &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/diarglistinfo/#a16cbe9ea4980b0b809ffa0a8d185a7ca">llvm::DIArgListInfo::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/functiontypekeyinfo/#af937bc033775d01ffda2374fadfe8278">llvm::FunctionTypeKeyInfo::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodeinfo/#afe0b73955622d00afba81803c5f5de53">llvm::MDNodeInfo&lt; NodeTy &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/llvm/targetexttypekeyinfo/#a9775b5be57e9a4b0a752163c78f04b67">llvm::TargetExtTypeKeyInfo::getEmptyKey</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#ad2398638cf12a8318566a3fc6cc0e771">llvm::InterleaveGroup&lt; InstTy &gt;::insertMember</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a76ed047b551aad831e63f153678d6d85">anonymous{MachineOutliner.cpp}::InstructionMapper::InstructionMapper</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#ab074cefd064d3c9f84f7207dbee71724">llvm::IRSimilarity::IRInstructionMapper::IRInstructionMapper</a>, <a href="/web-llvm/docs/api/classes/llvm/iroutliner/#a4dfb1b9b4add772840b18038df972d59">llvm::IROutliner::IROutliner</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#afd0535a9a9691fbeaf8a97077837bff9">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/callvalue/#a25dbdb2ff9c35d8ab35075c2fed0763e">anonymous{EarlyCSE.cpp}::CallValue::isSentinel</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/gepvalue/#a92402c4f4323c8e00de8fc02b6d873f2">anonymous{EarlyCSE.cpp}::GEPValue::isSentinel</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/simplevalue/#a750edb5f184ad6f60c0a53b7eb720dab">anonymous{EarlyCSE.cpp}::SimpleValue::isSentinel</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a567c4f57a2f3aaeb6daee72ec39fb073">llvm::ValueHandleBase::isValid</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a4f2bae254fbc6babdf14612c7b20b512">anonymous{MachineOutliner.cpp}::InstructionMapper::mapToIllegalUnsigned</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#aee2e5f8ff22ce6063643fea5c5b282d5">llvm::IRSimilarity::IRInstructionMapper::mapToIllegalUnsigned</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a0ad5905b935c2e08e68fa162f6950233">anonymous{MachineOutliner.cpp}::InstructionMapper::mapToLegalUnsigned</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#ae392ae2bd47b6a65a6d70f61ad7225a3">llvm::IRSimilarity::IRInstructionMapper::mapToLegalUnsigned</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>.</p>

</div>
</div>

### getHashValue() {#a86544e5fd2336905e43348d2fd546094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ModelledPHI&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DenseMapInfo::getHashValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi">ModelledPHI</a> &amp; V)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a2c94f3689753f814562b13d0c7f926b/#ac3f4e64adbcf72035a5ba27d1cc69acc">llvm::DenseMapInfo&lt; AA::RangeTy &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-00c712b9f8119dbcd9df11fd9c730cfe/#af571d431080d9ae43473571163bf9739">llvm::DenseMapInfo&lt; AACacheLoc &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2fb65b0a1a0a6b552e5196839bac56e7/#a63412da22c3f0c661331ab7d225502cc">llvm::DenseMapInfo&lt; AAMDNodes &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-0f253a473d8d464a041ca5a9506bff11/#ad206c527b9c43a2d976fb4eeb3b43d1a">llvm::DenseMapInfo&lt; APSInt, void &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-333ebb6b07f3716a084b17bee52e7bf9/#a1658ec5ae9988c37c80c1cf07ae31f91">llvm::DenseMapInfo&lt; BasicBlock::iterator &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-c8d484646dba98501f9b84f048d66ace/#a8ad7d8b778f8ae001155eecddff9cb03">llvm::DenseMapInfo&lt; codeview::TypeIndex &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-d9260256454227ba56509068a639c749/#a847d943a70fab55cf3a1995a7a3b4026">llvm::DenseMapInfo&lt; CSKYTargetStreamer::SymbolIndex &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-d853938abcd0ac398d73365f23e9c263/#a1641d206203860aa81ca22f560afd1a5">llvm::DenseMapInfo&lt; DebugVariable &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2d0489b7ff465b00b1924bf0f5134b07/#a429bb641b9336d41162bc2135d68b4bf">llvm::DenseMapInfo&lt; FrozenIndPHIInfo &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-5591f21651d12162b1c376a5f4e15eb4/#a85ceb710030ccf5cf90a0a1679c932d2">llvm::DenseMapInfo&lt; gsym::FileEntry &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9f64d73143315c4916785a7d42181db8/#aee1836009a97cfc6536ac14329d1a733">llvm::DenseMapInfo&lt; IRPosition &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-54fd47fa7f6e6c428354f053a15b186e/#ae7f96af9cdb554b8e5529fc7d3d26240">llvm::DenseMapInfo&lt; LLT &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b3f02d53fe13cccf1ed6335c94eda135/#aefced0f3f3bbaf3384b29c02d7f653ce">llvm::DenseMapInfo&lt; LocationSize &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-c9a0a95ddb70684cccffcc2c60e67387/#a7b37a8b69d44fe5ed9f17c311bcdc6ea">llvm::DenseMapInfo&lt; LoweredPHIRecord &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-f25b6c8d7819e772b81b8f6ba4da34ed/#a6d7a1ea6e86abfe9ed75a7a82417cd61">llvm::DenseMapInfo&lt; MCRegister &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-4f2a5bd91682bf5740574941f9d3c82c/#af947d8fcd9b31cabaaecff33b00611e7">llvm::DenseMapInfo&lt; MemoryLocation &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-ac8f46afffb89cdee88eb84de0c5ff04/#a8067c360f88c5012f1ffebb342f72d36">llvm::DenseMapInfo&lt; MemoryLocOrCall &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-810b3658213714669e49aff43025bdaf/#a03a2f0fb6debf626126a2fc0d346de28">llvm::DenseMapInfo&lt; minidump::StreamType &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-334b1662ac84e69c318c2b8f38068356/#afe84ed8184725df0c11d519f06c60b89">llvm::DenseMapInfo&lt; orc::AllocGroup &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a38f6a722ee6303b849007724d9da2bb/#a568b12cdf09ec965eda751542a13fdf2">llvm::DenseMapInfo&lt; orc::ExecutorAddr &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-caf8bdd98d3fecb221c25b8a02d22a25/#af59938fdea98d5228f94640c7582a8df">llvm::DenseMapInfo&lt; orc::MemProt &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-cb18a88863893e929978bd24e76ad00a/#a77a9821885c1a4c8e8b5a7868169f9da">llvm::DenseMapInfo&lt; orc::SymbolStringPtr &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-22187bcc0451f0229d0ee3a45fd27f8c/#a23357deee1a172e15c3e8cfd9a3a06ea">llvm::DenseMapInfo&lt; PointerUnion&lt; PTs... &gt; &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9b46fd3afaa0cf1f8c6be79306c49695/#a6b24f73acc463a46b09e4de49893d91e">llvm::DenseMapInfo&lt; PoisoningVH&lt; T &gt; &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9b46fd3afaa0cf1f8c6be79306c49695/#a557aafde6241f1c99c78486832e7304c">llvm::DenseMapInfo&lt; PoisoningVH&lt; T &gt; &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-564b5535152d24fb29cfa12049cca653/#ac6b3b364eb359f1a89ad6f464120af09">llvm::DenseMapInfo&lt; SlotWithTag &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-5241fa1fbb6a12b3cf49bd28ddb26e8e/#a069a8d402cabf257f57764488b5a1a2a">llvm::DenseMapInfo&lt; std::pair&lt; const MCSymbol *, MCSymbolRefExpr::VariantKind &gt; &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-d398ffa29a33f62f70c5623cea74fade/#a7959006a8f245a63d252d5f436c8c173">llvm::DenseMapInfo&lt; unsigned long &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-cf976c6008d17910e6e4c099545e7635/#a0e56ab6c7a399934e3c0f4e58400343b">llvm::DenseMapInfo&lt; ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt; &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-cf976c6008d17910e6e4c099545e7635/#ac6bcc5488bf59d6bb2a04bb8cad5c86e">llvm::DenseMapInfo&lt; ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt; &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-fbbd89e197847d24411e9fd99b4d0911/#af4a2d208e6fb17c220461fd87d8b8a62">llvm::DenseMapInfo&lt; VTableSlot &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b15fb43ec6f8abbffe4d2a73ea4ec543/#a521955039ce21eb486aefe1a705a7da3">llvm::DenseMapInfo&lt; VTableSlotSummary &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2a7e6051b930a8ee63f30351950c0c61/#a33f732c96340242d31e7edf521649d6b">llvm::DenseMapInfo&lt; wasm::WasmTableType, void &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-0a20a4520b751e0749348b099f298bed/#a120cb970f368f6cd7c49cea56f139ac4">llvm::DenseMapInfo&lt; WeakVH &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-52732d196168d4457ac8b19ac19fffa7/#a3ff485875fe2d486b95dbc84109cd96e">llvm::DenseMapInfo&lt; std::tuple&lt; Ts... &gt; &gt;::getHashValueImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a4428329047c5c44d2157e24986cc9802">llvm::rdf::RegisterAggr::hash</a>.</p>

</div>
</div>

### getTombstoneKey() {#a9571e26b946751eaf015a9b8dc508be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ModelledPHI&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModelledPHI &amp; anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey ()</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi/#a9e315ee3f034c5d47eb479382bcad6d5">anonymous{GVNSink.cpp}::ModelledPHI::createDummy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#af4d4bfb09d6c352cfd4373d1e71ff8c8">llvm::object::MinidumpFile::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopvectorize-cpp-/csedensemapinfo/#a08a2129253b9049a133a8e83c54022ee">anonymous{LoopVectorize.cpp}::CSEDenseMapInfo::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/anonstructtypekeyinfo/#ac85db2d9611ef2d17f9d2d2f43fe01c0">llvm::AnonStructTypeKeyInfo::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a2c94f3689753f814562b13d0c7f926b/#a9332de826fa0d7e33daa07e7730a6547">llvm::DenseMapInfo&lt; AA::RangeTy &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-00c712b9f8119dbcd9df11fd9c730cfe/#af94c13aa1c668a7860c05d241f495894">llvm::DenseMapInfo&lt; AACacheLoc &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2fb65b0a1a0a6b552e5196839bac56e7/#a9d0f2f4dd473d47bdd209fd486974512">llvm::DenseMapInfo&lt; AAMDNodes &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-75d9b96a5bc6b9a604536279a1a95d7e/#a519d6c97ce025b0f3562fecf2d7d558b">llvm::DenseMapInfo&lt; APFixedPoint &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-0f253a473d8d464a041ca5a9506bff11/#ac464bcef3e7a5b9f80ea3174d67d9fcd">llvm::DenseMapInfo&lt; APSInt, void &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-339e92432108a12c437bc5c3804a88b0/#aef7884092c1ace32396a4b76138ff75f">llvm::DenseMapInfo&lt; at::VarRecord &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a04d74e4f379575f260e088ee7b633ff/#a88e1d8df40ef9bcbb7b2566eef375329">llvm::DenseMapInfo&lt; CachedHashStringRef &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-8cd2653b8375ccc7028cd1fd71875103/#a5009fb4a99f280d50aefaa984cf7ecda">llvm::DenseMapInfo&lt; CallValue &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-c8d484646dba98501f9b84f048d66ace/#acd203fadcff9cdcffaf2e22154d78ff8">llvm::DenseMapInfo&lt; codeview::TypeIndex &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#a363139e6f6560336e87f213cc356cc29">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2d0489b7ff465b00b1924bf0f5134b07/#a368c373c5f75b5aa6bf7540dad7ded87">llvm::DenseMapInfo&lt; FrozenIndPHIInfo &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-e59b5bf2cc70d18adda69217a6ba3ef2/#af12fdaa590f0a9efd293c30e38a945e7">llvm::DenseMapInfo&lt; GEPValue &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-5591f21651d12162b1c376a5f4e15eb4/#abcc4b05afdb5aef02ff52d8e3b157a69">llvm::DenseMapInfo&lt; gsym::FileEntry &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-f25b6c8d7819e772b81b8f6ba4da34ed/#a68ba5ff029be80f6cc08ef7d2cb6074b">llvm::DenseMapInfo&lt; MCRegister &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-4f2a5bd91682bf5740574941f9d3c82c/#a966a657f11c0921b33f03dbbab567731">llvm::DenseMapInfo&lt; MemoryLocation &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-ac8f46afffb89cdee88eb84de0c5ff04/#afeeee37d51ca9e41d7ef8d85fc47e807">llvm::DenseMapInfo&lt; MemoryLocOrCall &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a38f6a722ee6303b849007724d9da2bb/#ab11387e0074d8c9aebfd0b39ec3f95da">llvm::DenseMapInfo&lt; orc::ExecutorAddr &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9b46fd3afaa0cf1f8c6be79306c49695/#a0c4c62d5f20dee28bee3a422c7fc1184">llvm::DenseMapInfo&lt; PoisoningVH&lt; T &gt; &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-1fffb1beefe8443d1c161dda7a88fc8c/#af849f36daad932f29785abb4ebcad17f">llvm::DenseMapInfo&lt; SimpleValue &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-52732d196168d4457ac8b19ac19fffa7/#a92ee6feb0b771fcdbe708e71046b4106">llvm::DenseMapInfo&lt; std::tuple&lt; Ts... &gt; &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-f0f922b85f106c4a3f6f55bfb8e595ef/#afb2b2764884ec7e4f67f8b5c7b676e63">llvm::DenseMapInfo&lt; std::variant&lt; Ts... &gt; &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a5e8ac4b4d72810d165b1ceb2eae9222/#af7fceedbbdc6ccb58f18075f5ba2644a">llvm::DenseMapInfo&lt; UniqueBBID &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-cf976c6008d17910e6e4c099545e7635/#a3191db70e2e8cc60042265b36c5fa8eb">llvm::DenseMapInfo&lt; ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt; &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-fbbd89e197847d24411e9fd99b4d0911/#a1c80e25a1ca5f47d5db81fb5fe90b3c9">llvm::DenseMapInfo&lt; VTableSlot &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b15fb43ec6f8abbffe4d2a73ea4ec543/#ad09107f738d6745fda7cb3ba4cfb6224">llvm::DenseMapInfo&lt; VTableSlotSummary &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2a7e6051b930a8ee63f30351950c0c61/#a489b1e1bf3e1c8953a7b911e80737717">llvm::DenseMapInfo&lt; wasm::WasmTableType, void &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-0a20a4520b751e0749348b099f298bed/#a7913b1f1c83ffdfede51158c21d2ef19">llvm::DenseMapInfo&lt; WeakVH &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/diarglistinfo/#add6050ccae8d05b49bf8fed78bd15c90">llvm::DIArgListInfo::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/functiontypekeyinfo/#a3e8b826d0f5f58e4ceced4103ed5d5ea">llvm::FunctionTypeKeyInfo::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodeinfo/#ae0cf1c483489b661ce8de2dd15e64219">llvm::MDNodeInfo&lt; NodeTy &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/targetexttypekeyinfo/#a94c811fc78bf33ab7c2e05bcce7ac1d8">llvm::TargetExtTypeKeyInfo::getTombstoneKey</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#ad2398638cf12a8318566a3fc6cc0e771">llvm::InterleaveGroup&lt; InstTy &gt;::insertMember</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a76ed047b551aad831e63f153678d6d85">anonymous{MachineOutliner.cpp}::InstructionMapper::InstructionMapper</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#ab074cefd064d3c9f84f7207dbee71724">llvm::IRSimilarity::IRInstructionMapper::IRInstructionMapper</a>, <a href="/web-llvm/docs/api/classes/llvm/iroutliner/#a4dfb1b9b4add772840b18038df972d59">llvm::IROutliner::IROutliner</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#afd0535a9a9691fbeaf8a97077837bff9">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/callvalue/#a25dbdb2ff9c35d8ab35075c2fed0763e">anonymous{EarlyCSE.cpp}::CallValue::isSentinel</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/gepvalue/#a92402c4f4323c8e00de8fc02b6d873f2">anonymous{EarlyCSE.cpp}::GEPValue::isSentinel</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/simplevalue/#a750edb5f184ad6f60c0a53b7eb720dab">anonymous{EarlyCSE.cpp}::SimpleValue::isSentinel</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a567c4f57a2f3aaeb6daee72ec39fb073">llvm::ValueHandleBase::isValid</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a4f2bae254fbc6babdf14612c7b20b512">anonymous{MachineOutliner.cpp}::InstructionMapper::mapToIllegalUnsigned</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#aee2e5f8ff22ce6063643fea5c5b282d5">llvm::IRSimilarity::IRInstructionMapper::mapToIllegalUnsigned</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a0ad5905b935c2e08e68fa162f6950233">anonymous{MachineOutliner.cpp}::InstructionMapper::mapToLegalUnsigned</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#ae392ae2bd47b6a65a6d70f61ad7225a3">llvm::IRSimilarity::IRInstructionMapper::mapToLegalUnsigned</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>.</p>

</div>
</div>

### isEqual() {#a17c9fc217e2ec4f12e8c2a27f783bcae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ModelledPHI&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DenseMapInfo::isEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi">ModelledPHI</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi">ModelledPHI</a> &amp; RHS)</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cachedhashstring/#a4f00fd7d62074e6b3b97b6677dba3713">llvm::CachedHashString::DenseMapInfo&lt; CachedHashString &gt;</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-53ae3e3da76d4a953c54bf91fcf8ff03/#ae71eda11e54f4b701cb57495c25af2f3">llvm::DenseMapInfo&lt; FunctionSummary::ConstVCall &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a38f6a722ee6303b849007724d9da2bb/#a715f23220f775a7832b3e5b8d9060c2b">llvm::DenseMapInfo&lt; orc::ExecutorAddr &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9b46fd3afaa0cf1f8c6be79306c49695/#ac0f5d33fc0e3d82f6ebd15b4c4d6b519">llvm::DenseMapInfo&lt; PoisoningVH&lt; T &gt; &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9b46fd3afaa0cf1f8c6be79306c49695/#a08ec9de52003611d228bef5e1038c530">llvm::DenseMapInfo&lt; PoisoningVH&lt; T &gt; &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-f0f922b85f106c4a3f6f55bfb8e595ef/#adea248b2d1c9628e4c24fe9cd6ea9d28">llvm::DenseMapInfo&lt; std::variant&lt; Ts... &gt; &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a5e8ac4b4d72810d165b1ceb2eae9222/#a3bac0641fb9de287bac838a1f0295e0e">llvm::DenseMapInfo&lt; UniqueBBID &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-0a20a4520b751e0749348b099f298bed/#a102019014490cdda6c667387e9e7956d">llvm::DenseMapInfo&lt; WeakVH &gt;::isEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-52732d196168d4457ac8b19ac19fffa7/#a45dde070a5e9e70583a4bd31bdbf0cf1">llvm::DenseMapInfo&lt; std::tuple&lt; Ts... &gt; &gt;::isEqualImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#aafe24ed31fe73055eec759c1f53ac26e">llvm::rdf::RegisterAggr::operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
