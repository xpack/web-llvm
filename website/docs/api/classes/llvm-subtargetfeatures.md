---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/subtargetfeatures
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SubtargetFeatures` Class Reference

<p>Manages the enabling and disabling of subtarget specific features. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SubtargetFeatures { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac09c9a27c28af87d66d83f47ce6ffe37">SubtargetFeatures</a> (StringRef Initial="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9679917091c7e93f866894599f923e">getString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns features as a string. <a href="#aaa9679917091c7e93f866894599f923e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af579a881fa0a6fe785ecf91fcc9ccaaa">AddFeature</a> (StringRef String, bool Enable=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds Features. <a href="#af579a881fa0a6fe785ecf91fcc9ccaaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe3c388c22fe55467e7f2847d7ec2fd">addFeaturesVector</a> (const ArrayRef&lt; std::string &gt; OtherFeatures)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a9e8ebdc3fdfb710357fdb5e724abe">getFeatures</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the vector of individual subtarget features. <a href="#a39a9e8ebdc3fdfb710357fdb5e724abe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97fdab1958ed9881492407bf359309d2">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prints feature string. <a href="#a97fdab1958ed9881492407bf359309d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb795e29b0d98b3f34cab49960a2798">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a24823d504d2c91c152e69250b2197d">getDefaultSubtargetFeatures</a> (const Triple &amp;Triple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the default features for the specified target triple. <a href="#a5a24823d504d2c91c152e69250b2197d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad1832bda75b077ac4d7de7004b20b4">Features</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtarget features as a vector. <a href="#acad1832bda75b077ac4d7de7004b20b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a75c4defaf794fb1baf8afe140c0fe7">hasFlag</a> (StringRef Feature)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if a feature has a flag; '+' or '-'. <a href="#a8a75c4defaf794fb1baf8afe140c0fe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de4cf7f3a21b57333330349f1f32ff3">StripFlag</a> (StringRef Feature)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return string stripped of flag. <a href="#a8de4cf7f3a21b57333330349f1f32ff3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae07a5960fad31a5e146cb9d81dd15b47">isEnabled</a> (StringRef Feature)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if enable flag; '+'. <a href="#ae07a5960fad31a5e146cb9d81dd15b47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10aa0138f3edcc0641294b19c7fdebbb">Split</a> (std::vector&lt; std::string &gt; &amp;V, StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splits a string of comma separated items in to a vector of strings. <a href="#a10aa0138f3edcc0641294b19c7fdebbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Manages the enabling and disabling of subtarget specific features.</p>


<p>Features are encoded as a string of the form "+attr1,+attr2,-attr3,...,+attrN" A comma separates each feature from the next (all lowercase.) Each of the remaining features is prefixed with + or - indicating whether that feature should be enabled or disabled contrary to the cpu specification.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SubtargetFeatures() {#ac09c9a27c28af87d66d83f47ce6ffe37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubtargetFeatures::SubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Initial="")</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/subtargetfeature-cpp">SubtargetFeature.cpp</a>.</p>


<p>Reference <a href="#a10aa0138f3edcc0641294b19c7fdebbb">Split</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddFeature() {#af579a881fa0a6fe785ecf91fcc9ccaaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SubtargetFeatures::AddFeature (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String, bool Enable=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds Features.</p>

<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/subtargetfeature-cpp">SubtargetFeature.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a>, <a href="#a8a75c4defaf794fb1baf8afe140c0fe7">hasFlag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder/#aa67d14db111b10a6a09cb70fa5f4e084">llvm::orc::JITTargetMachineBuilder::detectHost</a>, <a href="#a5a24823d504d2c91c152e69250b2197d">getDefaultSubtargetFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#a6d80984ae9400c5f6fc20ac6eec8f6e1">llvm::codegen::getFeatureList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#a1b18aa9e75372c814e4d5207dce6b933">llvm::codegen::getFeaturesStr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac33e274ca277cfe840f699acc1b8a814">llvm::HexagonSubtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga1186db08841661c3349d23a4344edd38">LLVMGetHostCPUFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a7ef5bb146eb2c0e3a609a6a169ac4f44">llvm::EngineBuilder::selectTarget</a>.</p>

</div>
</div>

### addFeaturesVector() {#afbe3c388c22fe55467e7f2847d7ec2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SubtargetFeatures::addFeaturesVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; OtherFeatures)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/subtargetfeature-cpp">SubtargetFeature.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>.</p>

</div>
</div>

### dump() {#abdb795e29b0d98b3f34cab49960a2798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SubtargetFeatures::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/subtargetfeature-cpp">SubtargetFeature.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a97fdab1958ed9881492407bf359309d2">print</a>.</p>

</div>
</div>

### getDefaultSubtargetFeatures() {#a5a24823d504d2c91c152e69250b2197d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SubtargetFeatures::getDefaultSubtargetFeatures (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Triple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds the default features for the specified target triple.</p>

<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/subtargetfeature-cpp">SubtargetFeature.cpp</a>.</p>


<p>References <a href="#af579a881fa0a6fe785ecf91fcc9ccaaa">AddFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca674d908c8b0ebe1880f8c8d651eda9e2">llvm::Triple::Apple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ab4d9af9c278219b313508fce336b7d83">llvm::Triple::getVendor</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">llvm::Triple::ppc</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thinltocodegeneratorimpl/targetmachinebuilder/#a057a55d2ecdfd54087c9d8ffbe9f9c2a">llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::create</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a>.</p>

</div>
</div>

### getFeatures() {#a39a9e8ebdc3fdfb710357fdb5e724abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; std::string &gt; &amp; llvm::SubtargetFeatures::getFeatures ()</td>
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

<p>Returns the vector of individual subtarget features.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#a6d80984ae9400c5f6fc20ac6eec8f6e1">llvm::codegen::getFeatureList</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac33e274ca277cfe840f699acc1b8a814">llvm::HexagonSubtarget::initializeSubtargetDependencies</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid/#a08b8980d20ebca6171b8139f4dadc3eb">llvm::AMDGPU::IsaInfo::AMDGPUTargetID::setTargetIDFromFeaturesString</a>.</p>

</div>
</div>

### getString() {#aaa9679917091c7e93f866894599f923e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string SubtargetFeatures::getString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns features as a string.</p>

<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/subtargetfeature-cpp">SubtargetFeature.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thinltocodegeneratorimpl/targetmachinebuilder/#a057a55d2ecdfd54087c9d8ffbe9f9c2a">llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#a1b18aa9e75372c814e4d5207dce6b933">llvm::codegen::getFeaturesStr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac33e274ca277cfe840f699acc1b8a814">llvm::HexagonSubtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga1186db08841661c3349d23a4344edd38">LLVMGetHostCPUFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a7ef5bb146eb2c0e3a609a6a169ac4f44">llvm::EngineBuilder::selectTarget</a>.</p>

</div>
</div>

### print() {#a97fdab1958ed9881492407bf359309d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SubtargetFeatures::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prints feature string.</p>

<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/subtargetfeature-cpp">SubtargetFeature.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#abdb795e29b0d98b3f34cab49960a2798">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Features {#acad1832bda75b077ac4d7de7004b20b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::SubtargetFeatures::Features</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtarget features as a vector.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hasFlag() {#a8a75c4defaf794fb1baf8afe140c0fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SubtargetFeatures::hasFlag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Feature)</td>
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

<p>Determine if a feature has a flag; '+' or '-'.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>


<p>Referenced by <a href="#af579a881fa0a6fe785ecf91fcc9ccaaa">AddFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a00ea531f15b6ca7bac68acbd9e89082d">ApplyFeatureFlag</a> and <a href="#a8de4cf7f3a21b57333330349f1f32ff3">StripFlag</a>.</p>

</div>
</div>

### isEnabled() {#ae07a5960fad31a5e146cb9d81dd15b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SubtargetFeatures::isEnabled (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Feature)</td>
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

<p>Return true if enable flag; '+'.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a00ea531f15b6ca7bac68acbd9e89082d">ApplyFeatureFlag</a>.</p>

</div>
</div>

### Split() {#a10aa0138f3edcc0641294b19c7fdebbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SubtargetFeatures::Split (std::vector&lt; std::string &gt; &amp; V, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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

<p>Splits a string of comma separated items in to a vector of strings.</p>

<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/subtargetfeature-cpp">SubtargetFeature.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ac09c9a27c28af87d66d83f47ce6ffe37">SubtargetFeatures</a>.</p>

</div>
</div>

### StripFlag() {#a8de4cf7f3a21b57333330349f1f32ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::SubtargetFeatures::StripFlag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Feature)</td>
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

<p>Return string stripped of flag.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="#a8a75c4defaf794fb1baf8afe140c0fe7">hasFlag</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a00ea531f15b6ca7bac68acbd9e89082d">ApplyFeatureFlag</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a2624192c54a92722351fa791af3e862d">llvm::MCSubtargetInfo::ToggleFeature</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/subtargetfeature-cpp">SubtargetFeature.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
