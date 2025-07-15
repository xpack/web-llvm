---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dotcfgchangereporter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DotCfgChangeReporter` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DotCfgChangeReporter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">llvm/Passes/StandardInstrumentations.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/changereporter">ChangeReporter&lt;IRUnitT&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8722a6ca981827a0250d5e95ef608ef2">DotCfgChangeReporter</a> (bool Verbose)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaea4b10e654d12cf04d0569be0bd918">~DotCfgChangeReporter</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8561a3cb89ee3981d033ad4f4074bd07">registerCallbacks</a> (PassInstrumentationCallbacks &amp;PIC)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2472b6d4dfa6ae7551842286161c53f2">initializeHTML</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615c5ec895d4fc067bccdf23990d691e">handleInitialIR</a> (Any IR) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac37a6f140c650acd870e4c5713660f">generateIRRepresentation</a> (Any IR, StringRef PassID, IRDataT&lt; DCData &gt; &amp;Output) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6559bfb1aef25e733a72bc60f106d13">omitAfter</a> (StringRef PassID, std::string &amp;Name) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdd394d923544b065d3bacb30ab0eb14">handleAfter</a> (StringRef PassID, std::string &amp;Name, const IRDataT&lt; DCData &gt; &amp;Before, const IRDataT&lt; DCData &gt; &amp;After, Any) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a0cb76abf43a111f7bb8a50184ab55e">handleInvalidated</a> (StringRef PassID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addfebc870fe0de7c6a0c6402201b50ee">handleFiltered</a> (StringRef PassID, std::string &amp;Name) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e835664460ed0c0e05f5209f2ea3998">handleIgnored</a> (StringRef PassID, std::string &amp;Name) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cfdf685d3e6d53df20862a50ccea04c">handleFunctionCompare</a> (StringRef Name, StringRef Prefix, StringRef PassID, StringRef Divider, bool InModule, unsigned Minor, const FuncDataT&lt; DCData &gt; &amp;Before, const FuncDataT&lt; DCData &gt; &amp;After)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eba2b4a73188fbeef4cd4fd486b98da">N</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59364db4f35eb6929a72d9589afa2718">genHTML</a> (StringRef Text, StringRef DotFile, StringRef PDFFileName)</td>
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


<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DotCfgChangeReporter() {#a8722a6ca981827a0250d5e95ef608ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DotCfgChangeReporter::DotCfgChangeReporter (bool Verbose)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2233 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/changereporter/#af02006f8d15a1d0e008c0c6f2774d0e0">llvm::ChangeReporter&lt; IRDataT&lt; DCData &gt; &gt;::ChangeReporter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DotCfgChangeReporter() {#aaaea4b10e654d12cf04d0569be0bd918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DotCfgChangeReporter::~DotCfgChangeReporter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2412 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### registerCallbacks() {#a8561a3cb89ee3981d033ad4f4074bd07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DotCfgChangeReporter::registerCallbacks (<a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> &amp; PIC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2437 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ade4b8410fbe0406fc61d1db65d1cfa12">llvm::SmallString&lt; InternalLen &gt;::c_str</a>, <a href="/web-llvm/docs/api/classes/llvm/changereporter/#af02006f8d15a1d0e008c0c6f2774d0e0">llvm::ChangeReporter&lt; IRDataT&lt; DCData &gt; &gt;::ChangeReporter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a37ac838dd136af402a8651b39bedc7a0">DotCfgDir</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d9d5328bc7a7ba4906fb7a366cc9a32a547b6191e6830ea05f44c5792e6a6879">llvm::DotCfgQuiet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d9d5328bc7a7ba4906fb7a366cc9a32a6bace5799365851d0c9848757b5d2e62">llvm::DotCfgVerbose</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5545f335cfa8ce28433826a14730a3a2">llvm::sys::fs::expand_tilde</a>, <a href="#a2472b6d4dfa6ae7551842286161c53f2">initializeHTML</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5074e520089f2472cad6437fe736eef2">llvm::PrintChanged</a> and <a href="/web-llvm/docs/api/classes/llvm/changereporter/#aa2fb31feeaf10f23b54a75e244c80035">llvm::ChangeReporter&lt; IRDataT&lt; DCData &gt; &gt;::registerRequiredCallbacks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### generateIRRepresentation() {#a3ac37a6f140c650acd870e4c5713660f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DotCfgChangeReporter::generateIRRepresentation (<a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/classes/llvm/irdatat">IRDataT</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dcdata">DCData</a> &gt; &amp; Output)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2321 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ircomparer/#a8760ed87ce8c468e4567141d3000e67c">llvm::IRComparer&lt; T &gt;::analyzeIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

### handleAfter() {#abdd394d923544b065d3bacb30ab0eb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DotCfgChangeReporter::handleAfter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irdatat">IRDataT</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dcdata">DCData</a> &gt; &amp; Before, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irdatat">IRDataT</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dcdata">DCData</a> &gt; &amp; After, <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2335 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/classes/llvm/ircomparer/#ab12e7da19a8a01d2ee492ae7cb7d0831">llvm::IRComparer&lt; T &gt;::compare</a>, <a href="#a7cfdf685d3e6d53df20862a50ccea04c">handleFunctionCompare</a>, <a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="#a6eba2b4a73188fbeef4cd4fd486b98da">N</a>.</p>

</div>
</div>

### handleFiltered() {#addfebc870fe0de7c6a0c6402201b50ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DotCfgChangeReporter::handleFiltered (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2359 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a> and <a href="#a6eba2b4a73188fbeef4cd4fd486b98da">N</a>.</p>

</div>
</div>

### handleFunctionCompare() {#a7cfdf685d3e6d53df20862a50ccea04c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DotCfgChangeReporter::handleFunctionCompare (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Divider, bool InModule, unsigned Minor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/funcdatat">FuncDataT</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dcdata">DCData</a> &gt; &amp; Before, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/funcdatat">FuncDataT</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dcdata">DCData</a> &gt; &amp; After)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2236 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aa37537b95a42a73ea04d8dd2803378da">llvm::sys::fs::createUniquePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a59364db4f35eb6929a72d9589afa2718">genHTML</a>, <a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a>, <a href="#a6eba2b4a73188fbeef4cd4fd486b98da">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfab2ee912b91d69b435159c7c3f6df7f5f">llvm::Number</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>


<p>Referenced by <a href="#abdd394d923544b065d3bacb30ab0eb14">handleAfter</a> and <a href="#a615c5ec895d4fc067bccdf23990d691e">handleInitialIR</a>.</p>

</div>
</div>

### handleIgnored() {#a8e835664460ed0c0e05f5209f2ea3998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DotCfgChangeReporter::handleIgnored (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2368 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a> and <a href="#a6eba2b4a73188fbeef4cd4fd486b98da">N</a>.</p>

</div>
</div>

### handleInitialIR() {#a615c5ec895d4fc067bccdf23990d691e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DotCfgChangeReporter::handleInitialIR (<a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2297 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/classes/llvm/ircomparer/#a8760ed87ce8c468e4567141d3000e67c">llvm::IRComparer&lt; T &gt;::analyzeIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/classes/llvm/ircomparer/#ab12e7da19a8a01d2ee492ae7cb7d0831">llvm::IRComparer&lt; T &gt;::compare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a7cfdf685d3e6d53df20862a50ccea04c">handleFunctionCompare</a>, <a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="#a6eba2b4a73188fbeef4cd4fd486b98da">N</a>.</p>

</div>
</div>

### handleInvalidated() {#a2a0cb76abf43a111f7bb8a50184ab55e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DotCfgChangeReporter::handleInvalidated (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2351 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a> and <a href="#a6eba2b4a73188fbeef4cd4fd486b98da">N</a>.</p>

</div>
</div>

### initializeHTML() {#a2472b6d4dfa6ae7551842286161c53f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DotCfgChangeReporter::initializeHTML ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2376 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a37ac838dd136af402a8651b39bedc7a0">DotCfgDir</a> and <a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a>.</p>


<p>Referenced by <a href="#a8561a3cb89ee3981d033ad4f4074bd07">registerCallbacks</a>.</p>

</div>
</div>

### omitAfter() {#af6559bfb1aef25e733a72bc60f106d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DotCfgChangeReporter::omitAfter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2326 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a29ade8d6d50a9e3bb7f95b6276f752e2">HTML</a> and <a href="#a6eba2b4a73188fbeef4cd4fd486b98da">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### HTML {#a29ade8d6d50a9e3bb7f95b6276f752e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;raw_fd_ostream&gt; llvm::DotCfgChangeReporter::HTML</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#abdd394d923544b065d3bacb30ab0eb14">handleAfter</a>, <a href="#addfebc870fe0de7c6a0c6402201b50ee">handleFiltered</a>, <a href="#a7cfdf685d3e6d53df20862a50ccea04c">handleFunctionCompare</a>, <a href="#a8e835664460ed0c0e05f5209f2ea3998">handleIgnored</a>, <a href="#a615c5ec895d4fc067bccdf23990d691e">handleInitialIR</a>, <a href="#a2a0cb76abf43a111f7bb8a50184ab55e">handleInvalidated</a>, <a href="#a2472b6d4dfa6ae7551842286161c53f2">initializeHTML</a>, <a href="#af6559bfb1aef25e733a72bc60f106d13">omitAfter</a> and <a href="#aaaea4b10e654d12cf04d0569be0bd918">~DotCfgChangeReporter</a>.</p>

</div>
</div>

### N {#a6eba2b4a73188fbeef4cd4fd486b98da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DotCfgChangeReporter::N = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#abdd394d923544b065d3bacb30ab0eb14">handleAfter</a>, <a href="#addfebc870fe0de7c6a0c6402201b50ee">handleFiltered</a>, <a href="#a7cfdf685d3e6d53df20862a50ccea04c">handleFunctionCompare</a>, <a href="#a8e835664460ed0c0e05f5209f2ea3998">handleIgnored</a>, <a href="#a615c5ec895d4fc067bccdf23990d691e">handleInitialIR</a>, <a href="#a2a0cb76abf43a111f7bb8a50184ab55e">handleInvalidated</a> and <a href="#af6559bfb1aef25e733a72bc60f106d13">omitAfter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### genHTML() {#a59364db4f35eb6929a72d9589afa2718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DotCfgChangeReporter::genHTML (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Text, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DotFile, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PDFFileName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 2278 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ade4b8410fbe0406fc61d1db65d1cfa12">llvm::SmallString&lt; InternalLen &gt;::c_str</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a7fe10355854aac986d063bc1f45ccf87">DotBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a37ac838dd136af402a8651b39bedc7a0">DotCfgDir</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#abb13fbc7f52c659966b05092b19e6e19">llvm::sys::ExecuteAndWait</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ae87ab32d0995f94193aff5e380c8d251">llvm::sys::findProgramByName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>.</p>


<p>Referenced by <a href="#a7cfdf685d3e6d53df20862a50ccea04c">handleFunctionCompare</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
