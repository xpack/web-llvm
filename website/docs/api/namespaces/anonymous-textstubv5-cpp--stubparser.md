---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-textstubv5-cpp-/stubparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `StubParser` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{TextStubV5.cpp}::StubParser { ... }
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e889307eeaf9ab387f87dc4fb6db939">IFPtr</a> = std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac42c700535f05d4689644c1b5e6d5067">getVersion</a> (const Object *File)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac089ad7e9e01c5183ce6ba196ed6a9ba">TargetList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae32520c146488ec59560dd75567ba9b0">getTargets</a> (const Object *Section)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac089ad7e9e01c5183ce6ba196ed6a9ba">TargetList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a841ed7fbb14a5ba056989d1e19eef248">getTargetsSection</a> (const Object *Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c8a237a39436fb25894d198668f88f">collectSymbolsFromSegment</a> (const Object *Segment, TargetsToSymbols &amp;Result, SymbolFlags SectionFlag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b48d84adc69c4ec316b2f4643c2e83">getNameSection</a> (const Object *File)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a4f188aeb0008d9d35dc15e32a3ac0f40">TargetsToSymbols</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf9c0aea9c22aa6396990a3c9b72beb2">getSymbolSection</a> (const Object *File, TBDKey Key, TargetList &amp;Targets)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a9fb0bdd183f005b7192cf221d7dab722">AttrToTargets</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e72b5d7e60c25a1b92869fe06ef845f">getLibSection</a> (const Object *File, TBDKey Key, TBDKey SubKey, const TargetList &amp;Targets)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a9fb0bdd183f005b7192cf221d7dab722">AttrToTargets</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b701ffbdb1940d66dc5f254c3bc16ae">getUmbrellaSection</a> (const Object *File, const TargetList &amp;Targets)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbe5a3bb0b3fa7550dc6cda8bf451e1c">getSwiftVersion</a> (const Object *File)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/packedversion">PackedVersion</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb60bd8130621f33fdc8f14cc5faf7bc">getPackedVersion</a> (const Object *File, TBDKey Key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9">TBDFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a736134f0d04876e181e093887c0a5edd">getFlags</a> (const Object *File)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#a5e889307eeaf9ab387f87dc4fb6db939">IFPtr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a> (const Object *File)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="#a5e889307eeaf9ab387f87dc4fb6db939">IFPtr</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae33c03791e07abd4c25d2591e3e9e6b4">getInlinedLibs</a> (const Object *File)</td>
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

### IFPtr {#a5e889307eeaf9ab387f87dc4fb6db939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{TextStubV5.cpp}::StubParser::IFPtr =  std::unique_ptr&lt;InterfaceFile&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### collectSymbolsFromSegment() {#ae8c8a237a39436fb25894d198668f88f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{TextStubV5.cpp}::StubParser::collectSymbolsFromSegment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * Segment, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a4f188aeb0008d9d35dc15e32a3ac0f40">TargetsToSymbols</a> &amp; Result, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> SectionFlag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a454eefb23874609b98aa35d4d8cbfd38">anonymous{TextStubV5.cpp}::collectFromArray</a>, <a href="#ae8c8a237a39436fb25894d198668f88f">collectSymbolsFromSegment</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa426653d07c551d3092a6515150906380">anonymous{TextStubV5.cpp}::Globals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09adac49f2966d60d1973e56e22359e377e68">llvm::MachO::GlobalSymbol</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa606b90de9c892527f198b584c25f6ccb">anonymous{TextStubV5.cpp}::Name</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1af020ca062d3ff41454dd3bef3eac18">anonymous{TextStubV5.cpp}::ObjCClass</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa693e8acbda60d431e247d5ac1a721746">anonymous{TextStubV5.cpp}::ObjCEHType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa3f5dcf325688bef86add36358f09e519">anonymous{TextStubV5.cpp}::ObjCIvar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09adabadb331c797ea02208fed9025369cfb1">llvm::MachO::ObjectiveCClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ada54da6ac4046a5d0d1b4c31bc3dc43247">llvm::MachO::ObjectiveCClassEHType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ada305fbf91fddce55318beefeb7170a5af">llvm::MachO::ObjectiveCInstanceVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa5356306e635d37b73191de8f0fb44d20">anonymous{TextStubV5.cpp}::ThreadLocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a4514e0ecc0bca43f5fa805abf7d7f1da">llvm::MachO::ThreadLocalValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4aec0fc0100c4fc1ce4eea230c3dc10360">llvm::MachO::Undefined</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa2e6c12605b1e10338c757b0b02f8c3ee">anonymous{TextStubV5.cpp}::Weak</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a97a89195303306e8a5bacadf960312a9">llvm::MachO::WeakDefined</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a7c73b1797e3f46eb2dcb9d8d2d75805b">llvm::MachO::WeakReferenced</a>.</p>


<p>Referenced by <a href="#ae8c8a237a39436fb25894d198668f88f">collectSymbolsFromSegment</a> and <a href="#aaf9c0aea9c22aa6396990a3c9b72beb2">getSymbolSection</a>.</p>

</div>
</div>

### getFlags() {#a736134f0d04876e181e093887c0a5edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; TBDFlags &gt; anonymous{TextStubV5.cpp}::StubParser::getFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa4535eeef48d1e70cc3443556bb5d5dd2">anonymous{TextStubV5.cpp}::Attributes</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a454eefb23874609b98aa35d4d8cbfd38">anonymous{TextStubV5.cpp}::collectFromArray</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfab74797a67aabe2a47afe04d0a92997a0">anonymous{TextStubV5.cpp}::Flags</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ac8c901932d2e8f2ed7a2c695eba8b9c6">FlatNamespace</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#abdd39ea41cffb0041ffe6685c7033ce2">anonymous{TextStubV5.cpp}::getParseErrorMsg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ac9d3e887722f2bc482bcca9d41c512af">None</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9a6a9c8353be1f1cb8caffe162b55bfbe7">NotApplicationExtensionSafe</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ad93e8101951dcb34167984295e37e472">OSLibNotForSharedCache</a> and <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9a7cee22ba0016190fcebb9ba9cd494f15">SimulatorSupport</a>.</p>

</div>
</div>

### getInlinedLibs() {#ae33c03791e07abd4c25d2591e3e9e6b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; IFPtr &gt; &gt; anonymous{TextStubV5.cpp}::StubParser::getInlinedLibs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfad880b8ae46115265abe0f2ca6eab37eb">anonymous{TextStubV5.cpp}::Documents</a>, <a href="#ae33c03791e07abd4c25d2591e3e9e6b4">getInlinedLibs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a> and <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>.</p>


<p>Referenced by <a href="#ae33c03791e07abd4c25d2591e3e9e6b4">getInlinedLibs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a87d247041800a391e58d7e42c6286219">llvm::MachO::getInterfaceFileFromJSON</a>.</p>

</div>
</div>

### getLibSection() {#a6e72b5d7e60c25a1b92869fe06ef845f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; AttrToTargets &gt; anonymous{TextStubV5.cpp}::StubParser::getLibSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adf">TBDKey</a> Key, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adf">TBDKey</a> SubKey, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac089ad7e9e01c5183ce6ba196ed6a9ba">TargetList</a> &amp; Targets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a454eefb23874609b98aa35d4d8cbfd38">anonymous{TextStubV5.cpp}::collectFromArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#a6e72b5d7e60c25a1b92869fe06ef845f">getLibSection</a>, <a href="#ae32520c146488ec59560dd75567ba9b0">getTargets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1eb7e8cfb9fedbbf4d8f497fed784976">anonymous{TextStubV5.cpp}::Targets</a>.</p>


<p>Referenced by <a href="#a6e72b5d7e60c25a1b92869fe06ef845f">getLibSection</a> and <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>.</p>

</div>
</div>

### getNameSection() {#a29b48d84adc69c4ec316b2f4643c2e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; anonymous{TextStubV5.cpp}::StubParser::getNameSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a29b48d84adc69c4ec316b2f4643c2e83">getNameSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#abdd39ea41cffb0041ffe6685c7033ce2">anonymous{TextStubV5.cpp}::getParseErrorMsg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a4198fa1d6fe5b33ba619252e572c0a59">anonymous{TextStubV5.cpp}::getRequiredValue</a>, <a href="/web-llvm/docs/api/classes/llvm/json/object/#a3f5a1fac6edc9441441ce993e57dcafe">llvm::json::Object::getString</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa2b379332c96b957e66085b479d1cdec1">anonymous{TextStubV5.cpp}::InstallName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa606b90de9c892527f198b584c25f6ccb">anonymous{TextStubV5.cpp}::Name</a>.</p>


<p>Referenced by <a href="#a29b48d84adc69c4ec316b2f4643c2e83">getNameSection</a> and <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>.</p>

</div>
</div>

### getPackedVersion() {#acb60bd8130621f33fdc8f14cc5faf7bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; PackedVersion &gt; anonymous{TextStubV5.cpp}::StubParser::getPackedVersion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adf">TBDKey</a> Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="#acb60bd8130621f33fdc8f14cc5faf7bc">getPackedVersion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#abdd39ea41cffb0041ffe6685c7033ce2">anonymous{TextStubV5.cpp}::getParseErrorMsg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a4198fa1d6fe5b33ba619252e572c0a59">anonymous{TextStubV5.cpp}::getRequiredValue</a>, <a href="/web-llvm/docs/api/classes/llvm/json/object/#a3f5a1fac6edc9441441ce993e57dcafe">llvm::json::Object::getString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/packedversion/#a6954336e0b10193d5bea01a716c5f182">llvm::MachO::PackedVersion::parse64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aea6e51b13067f27d5b9bd39d1f44b670">llvm::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086aac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfaae3e15b3ca3cfb4bd480a8384f9cd0eb">anonymous{TextStubV5.cpp}::Version</a>.</p>


<p>Referenced by <a href="#acb60bd8130621f33fdc8f14cc5faf7bc">getPackedVersion</a> and <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>.</p>

</div>
</div>

### getSwiftVersion() {#abbe5a3bb0b3fa7550dc6cda8bf451e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint8_t &gt; anonymous{TextStubV5.cpp}::StubParser::getSwiftVersion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfab4689d5e531765b502380c113201e928">anonymous{TextStubV5.cpp}::ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/json/object/#a6f43eed548c5843a034256d003962856">llvm::json::Object::getInteger</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#abdd39ea41cffb0041ffe6685c7033ce2">anonymous{TextStubV5.cpp}::getParseErrorMsg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a4198fa1d6fe5b33ba619252e572c0a59">anonymous{TextStubV5.cpp}::getRequiredValue</a>, <a href="#abbe5a3bb0b3fa7550dc6cda8bf451e1c">getSwiftVersion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa7637bb12e5145f6a3cec062d4215c206">anonymous{TextStubV5.cpp}::SwiftABI</a>.</p>


<p>Referenced by <a href="#abbe5a3bb0b3fa7550dc6cda8bf451e1c">getSwiftVersion</a> and <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>.</p>

</div>
</div>

### getSymbolSection() {#aaf9c0aea9c22aa6396990a3c9b72beb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; TargetsToSymbols &gt; anonymous{TextStubV5.cpp}::StubParser::getSymbolSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adf">TBDKey</a> Key, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac089ad7e9e01c5183ce6ba196ed6a9ba">TargetList</a> &amp; Targets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="#ae8c8a237a39436fb25894d198668f88f">collectSymbolsFromSegment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa5dae40cd57d91a343a08470d0c2ec007">anonymous{TextStubV5.cpp}::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4af6068daa29dbb05a7ead1e3b5a48bbee">llvm::MachO::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/json/object/#a3c141439987df1fc2d6f0282a755cdcf">llvm::json::Object::getObject</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#abdd39ea41cffb0041ffe6685c7033ce2">anonymous{TextStubV5.cpp}::getParseErrorMsg</a>, <a href="#aaf9c0aea9c22aa6396990a3c9b72beb2">getSymbolSection</a>, <a href="#ae32520c146488ec59560dd75567ba9b0">getTargets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6adf97f83acf6453d4a6a4b1070f3754">llvm::MachO::None</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfacfd2adb123f170dce80a20438ab2951b">anonymous{TextStubV5.cpp}::Reexports</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6994917dfcfb9ef55fc6bce4b454f9a4">llvm::MachO::Rexported</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1eb7e8cfb9fedbbf4d8f497fed784976">anonymous{TextStubV5.cpp}::Targets</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa854fd39f168b7abc773a62be28560521">anonymous{TextStubV5.cpp}::Text</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a9dffbf69ffba8bc38bc4e01abf4b1675">llvm::MachO::Text</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4aec0fc0100c4fc1ce4eea230c3dc10360">llvm::MachO::Undefined</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1a9c95bb18e0be20b782d068de0d2b53">anonymous{TextStubV5.cpp}::Undefineds</a>.</p>


<p>Referenced by <a href="#aaf9c0aea9c22aa6396990a3c9b72beb2">getSymbolSection</a> and <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>.</p>

</div>
</div>

### getTargets() {#ae32520c146488ec59560dd75567ba9b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; TargetList &gt; anonymous{TextStubV5.cpp}::StubParser::getTargets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/target/#ac60f765fb1e3ea2626663548ace96890">llvm::MachO::Target::create</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#abdd39ea41cffb0041ffe6685c7033ce2">anonymous{TextStubV5.cpp}::getParseErrorMsg</a>, <a href="#ae32520c146488ec59560dd75567ba9b0">getTargets</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfae53e242fceae275aac3d6816388493a1">anonymous{TextStubV5.cpp}::Target</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1eb7e8cfb9fedbbf4d8f497fed784976">anonymous{TextStubV5.cpp}::Targets</a>.</p>


<p>Referenced by <a href="#a6e72b5d7e60c25a1b92869fe06ef845f">getLibSection</a>, <a href="#aaf9c0aea9c22aa6396990a3c9b72beb2">getSymbolSection</a>, <a href="#ae32520c146488ec59560dd75567ba9b0">getTargets</a> and <a href="#a7b701ffbdb1940d66dc5f254c3bc16ae">getUmbrellaSection</a>.</p>

</div>
</div>

### getTargetsSection() {#a841ed7fbb14a5ba056989d1e19eef248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; TargetList &gt; anonymous{TextStubV5.cpp}::StubParser::getTargetsSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/target/#ac60f765fb1e3ea2626663548ace96890">llvm::MachO::Target::create</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa06b97c30b6bf9ec35052b18be500f9bf">anonymous{TextStubV5.cpp}::Deployment</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#abdd39ea41cffb0041ffe6685c7033ce2">anonymous{TextStubV5.cpp}::getParseErrorMsg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a4198fa1d6fe5b33ba619252e572c0a59">anonymous{TextStubV5.cpp}::getRequiredValue</a>, <a href="/web-llvm/docs/api/classes/llvm/json/object/#a3f5a1fac6edc9441441ce993e57dcafe">llvm::json::Object::getString</a>, <a href="#a841ed7fbb14a5ba056989d1e19eef248">getTargetsSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a0c7a01c33f06ce5b51a5037522858155">llvm::MachO::getTargetTripleName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfae53e242fceae275aac3d6816388493a1">anonymous{TextStubV5.cpp}::Target</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfab31bbccbf05550eaee7286496db4b46b">anonymous{TextStubV5.cpp}::TargetInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1eb7e8cfb9fedbbf4d8f497fed784976">anonymous{TextStubV5.cpp}::Targets</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfaae3e15b3ca3cfb4bd480a8384f9cd0eb">anonymous{TextStubV5.cpp}::Version</a>.</p>


<p>Referenced by <a href="#a841ed7fbb14a5ba056989d1e19eef248">getTargetsSection</a> and <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>.</p>

</div>
</div>

### getUmbrellaSection() {#a7b701ffbdb1940d66dc5f254c3bc16ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; AttrToTargets &gt; anonymous{TextStubV5.cpp}::StubParser::getUmbrellaSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac089ad7e9e01c5183ce6ba196ed6a9ba">TargetList</a> &amp; Targets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#abdd39ea41cffb0041ffe6685c7033ce2">anonymous{TextStubV5.cpp}::getParseErrorMsg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a4198fa1d6fe5b33ba619252e572c0a59">anonymous{TextStubV5.cpp}::getRequiredValue</a>, <a href="/web-llvm/docs/api/classes/llvm/json/object/#a3f5a1fac6edc9441441ce993e57dcafe">llvm::json::Object::getString</a>, <a href="#ae32520c146488ec59560dd75567ba9b0">getTargets</a>, <a href="#a7b701ffbdb1940d66dc5f254c3bc16ae">getUmbrellaSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a15d47dd990e21acd5f1f2c8e9359b41f">anonymous{TextStubV5.cpp}::Keys</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa9a6ee2b880c9217fa15688729968b8ba">anonymous{TextStubV5.cpp}::ParentUmbrella</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1eb7e8cfb9fedbbf4d8f497fed784976">anonymous{TextStubV5.cpp}::Targets</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa573b6a97d47764913ee8a1a9c85e0693">anonymous{TextStubV5.cpp}::Umbrella</a>.</p>


<p>Referenced by <a href="#a7b701ffbdb1940d66dc5f254c3bc16ae">getUmbrellaSection</a> and <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>.</p>

</div>
</div>

### getVersion() {#ac42c700535f05d4689644c1b5e6d5067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; FileType &gt; anonymous{TextStubV5.cpp}::StubParser::getVersion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/json/object/#a6f43eed548c5843a034256d003962856">llvm::json::Object::getInteger</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a4198fa1d6fe5b33ba619252e572c0a59">anonymous{TextStubV5.cpp}::getRequiredValue</a>, <a href="#ac42c700535f05d4689644c1b5e6d5067">getVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3f7ae54a7045f6eb81648829a1167c3">llvm::MachO::TBD_V5</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1a74d1f8962e72d9c148f4e75a080e9a">anonymous{TextStubV5.cpp}::TBDVersion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a87d247041800a391e58d7e42c6286219">llvm::MachO::getInterfaceFileFromJSON</a> and <a href="#ac42c700535f05d4689644c1b5e6d5067">getVersion</a>.</p>

</div>
</div>

### parseToInterfaceFile() {#a513f7b203ab0641c05df11c260144622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; IFPtr &gt; anonymous{TextStubV5.cpp}::StubParser::parseToInterfaceFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa2522dd07161c4ca8fafba675b847c595">anonymous{TextStubV5.cpp}::AllowableClients</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa95749d288b55f7e1908fb83ec59964e6">anonymous{TextStubV5.cpp}::Clients</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfadff63c4963291ebc9f4e7e44335c2698">anonymous{TextStubV5.cpp}::CompatibilityVersion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa6d7cd3655df0474c9c4badbbf73648f6">anonymous{TextStubV5.cpp}::CurrentVersion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfafb8453aa7b9a2fc0a1bec1fd82f01c95">anonymous{TextStubV5.cpp}::Exports</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfab74797a67aabe2a47afe04d0a92997a0">anonymous{TextStubV5.cpp}::Flags</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ac8c901932d2e8f2ed7a2c695eba8b9c6">FlatNamespace</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a7a3ba7cd94762ae7f243367830320ca2">getFlags</a>, <a href="#a6e72b5d7e60c25a1b92869fe06ef845f">getLibSection</a>, <a href="#a29b48d84adc69c4ec316b2f4643c2e83">getNameSection</a>, <a href="#acb60bd8130621f33fdc8f14cc5faf7bc">getPackedVersion</a>, <a href="#abbe5a3bb0b3fa7550dc6cda8bf451e1c">getSwiftVersion</a>, <a href="#aaf9c0aea9c22aa6396990a3c9b72beb2">getSymbolSection</a>, <a href="#a841ed7fbb14a5ba056989d1e19eef248">getTargetsSection</a>, <a href="#a7b701ffbdb1940d66dc5f254c3bc16ae">getUmbrellaSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa606b90de9c892527f198b584c25f6ccb">anonymous{TextStubV5.cpp}::Name</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa638c40d9df2fbeba253de8cd53d19afd">anonymous{TextStubV5.cpp}::Names</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9a6a9c8353be1f1cb8caffe162b55bfbe7">NotApplicationExtensionSafe</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ad93e8101951dcb34167984295e37e472">OSLibNotForSharedCache</a>, <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfaa55015f2b0063e2314caede4ac9df141">anonymous{TextStubV5.cpp}::Paths</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfaa7891cbc501c4f44665099c75a685159">anonymous{TextStubV5.cpp}::ReexportLibs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfacfd2adb123f170dce80a20438ab2951b">anonymous{TextStubV5.cpp}::Reexports</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa24468be6ab878b0892d78b7005228ed5">anonymous{TextStubV5.cpp}::RPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9a7cee22ba0016190fcebb9ba9cd494f15">SimulatorSupport</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa7637bb12e5145f6a3cec062d4215c206">anonymous{TextStubV5.cpp}::SwiftABI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfae53e242fceae275aac3d6816388493a1">anonymous{TextStubV5.cpp}::Target</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1eb7e8cfb9fedbbf4d8f497fed784976">anonymous{TextStubV5.cpp}::Targets</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ad2f3f81faa370c8bf9a1f81612c90adfa1a9c95bb18e0be20b782d068de0d2b53">anonymous{TextStubV5.cpp}::Undefineds</a>.</p>


<p>Referenced by <a href="#ae33c03791e07abd4c25d2591e3e9e6b4">getInlinedLibs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a87d247041800a391e58d7e42c6286219">llvm::MachO::getInterfaceFileFromJSON</a> and <a href="#a513f7b203ab0641c05df11c260144622">parseToInterfaceFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubv5-cpp">TextStubV5.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
