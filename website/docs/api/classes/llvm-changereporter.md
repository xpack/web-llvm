---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/changereporter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ChangeReporter` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT&gt;
class llvm::ChangeReporter&lt;IRUnitT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">llvm/Passes/StandardInstrumentations.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/textchangereporter">TextChangeReporter&lt;IRUnitT&gt;</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af02006f8d15a1d0e008c0c6f2774d0e0">ChangeReporter</a> (bool RunInVerboseMode)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af1c5e5a2cc196539deba0a27bc4c6d69">~ChangeReporter</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0cf6b2cb664ca54095b4f6dfc5e548cc">saveIRBeforePass</a> (Any IR, StringRef PassID, StringRef PassName)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a57fcd8f955992d5167dae6978748f2">handleIRAfterPass</a> (Any IR, StringRef PassID, StringRef PassName)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae18a0ee2e81ff1ec157aef055aea560d">handleInvalidatedPass</a> (StringRef PassID)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa2fb31feeaf10f23b54a75e244c80035">registerRequiredCallbacks</a> (PassInstrumentationCallbacks &amp;PIC)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fa0872bd1b79f2febb9d0d95c6e9feb">handleInitialIR</a> (Any IR)=0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b14d5da7cee7c1f361797aee3456a15">generateIRRepresentation</a> (Any IR, StringRef PassID, IRUnitT &amp;Output)=0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac26c95e64f2909319101c59db1fd0a11">omitAfter</a> (StringRef PassID, std::string &amp;Name)=0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1a276e4bf9b7de55680e1c6d7d9bdb47">handleAfter</a> (StringRef PassID, std::string &amp;Name, const IRUnitT &amp;Before, const IRUnitT &amp;After, Any)=0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa0f43c611d489f2d3d202e1c146e3369">handleInvalidated</a> (StringRef PassID)=0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1675521c5cead992cc80282706b8164e">handleFiltered</a> (StringRef PassID, std::string &amp;Name)=0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b1fcd7b1d849f1dd527ead4f68bfce9">handleIgnored</a> (StringRef PassID, std::string &amp;Name)=0</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; IRUnitT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf1e0029cea6b08522657a3b7f795bfc">BeforeStack</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a48ea4fee95bec21d3fc365158b2ecb60">InitialIR</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac0952fd97e4bf8100ea253b28af483af">VerboseMode</a></td>
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


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### ChangeReporter() {#af02006f8d15a1d0e008c0c6f2774d0e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ChangeReporter&lt; IRUnitT &gt;::ChangeReporter (bool RunInVerboseMode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Reference <a href="#ac0952fd97e4bf8100ea253b28af483af">llvm::ChangeReporter&lt; IRUnitT &gt;::VerboseMode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/textchangereporter/#a5463cbf4b9180422d433483572f9bde8">llvm::TextChangeReporter&lt; IRUnitT &gt;::TextChangeReporter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ChangeReporter() {#af1c5e5a2cc196539deba0a27bc4c6d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeReporter::~ChangeReporter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaf1e0029cea6b08522657a3b7f795bfc">llvm::ChangeReporter&lt; IRUnitT &gt;::BeforeStack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### handleInvalidatedPass() {#ae18a0ee2e81ff1ec157aef055aea560d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ChangeReporter::handleInvalidatedPass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaf1e0029cea6b08522657a3b7f795bfc">llvm::ChangeReporter&lt; IRUnitT &gt;::BeforeStack</a>, <a href="#aa0f43c611d489f2d3d202e1c146e3369">llvm::ChangeReporter&lt; IRUnitT &gt;::handleInvalidated</a> and <a href="#ac0952fd97e4bf8100ea253b28af483af">llvm::ChangeReporter&lt; IRUnitT &gt;::VerboseMode</a>.</p>


<p>Referenced by <a href="#aa2fb31feeaf10f23b54a75e244c80035">llvm::ChangeReporter&lt; IRUnitT &gt;::registerRequiredCallbacks</a>.</p>

</div>
</div>

### handleIRAfterPass() {#a7a57fcd8f955992d5167dae6978748f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ChangeReporter::handleIRAfterPass (<a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="#aaf1e0029cea6b08522657a3b7f795bfc">llvm::ChangeReporter&lt; IRUnitT &gt;::BeforeStack</a>, <a href="#a5b14d5da7cee7c1f361797aee3456a15">llvm::ChangeReporter&lt; IRUnitT &gt;::generateIRRepresentation</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a36e1a8f3f395e3a595cc1fa2e8c337b0">anonymous{StandardInstrumentations.cpp}::getIRName</a>, <a href="#a1a276e4bf9b7de55680e1c6d7d9bdb47">llvm::ChangeReporter&lt; IRUnitT &gt;::handleAfter</a>, <a href="#a1675521c5cead992cc80282706b8164e">llvm::ChangeReporter&lt; IRUnitT &gt;::handleFiltered</a>, <a href="#a2b1fcd7b1d849f1dd527ead4f68bfce9">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIgnored</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a4294d1c5a044f7d53d49e262b68c2955">anonymous{StandardInstrumentations.cpp}::isIgnored</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#aedc4f4ea606ac0d1b036400c31d43da9">anonymous{StandardInstrumentations.cpp}::isInteresting</a>, <a href="#ac26c95e64f2909319101c59db1fd0a11">llvm::ChangeReporter&lt; IRUnitT &gt;::omitAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#ac0952fd97e4bf8100ea253b28af483af">llvm::ChangeReporter&lt; IRUnitT &gt;::VerboseMode</a>.</p>


<p>Referenced by <a href="#aa2fb31feeaf10f23b54a75e244c80035">llvm::ChangeReporter&lt; IRUnitT &gt;::registerRequiredCallbacks</a>.</p>

</div>
</div>

### saveIRBeforePass() {#a0cf6b2cb664ca54095b4f6dfc5e548cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ChangeReporter::saveIRBeforePass (<a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#aaf1e0029cea6b08522657a3b7f795bfc">llvm::ChangeReporter&lt; IRUnitT &gt;::BeforeStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a5b14d5da7cee7c1f361797aee3456a15">llvm::ChangeReporter&lt; IRUnitT &gt;::generateIRRepresentation</a>, <a href="#a6fa0872bd1b79f2febb9d0d95c6e9feb">llvm::ChangeReporter&lt; IRUnitT &gt;::handleInitialIR</a>, <a href="#a48ea4fee95bec21d3fc365158b2ecb60">llvm::ChangeReporter&lt; IRUnitT &gt;::InitialIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#aedc4f4ea606ac0d1b036400c31d43da9">anonymous{StandardInstrumentations.cpp}::isInteresting</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#ac0952fd97e4bf8100ea253b28af483af">llvm::ChangeReporter&lt; IRUnitT &gt;::VerboseMode</a>.</p>


<p>Referenced by <a href="#aa2fb31feeaf10f23b54a75e244c80035">llvm::ChangeReporter&lt; IRUnitT &gt;::registerRequiredCallbacks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### generateIRRepresentation() {#a5b14d5da7cee7c1f361797aee3456a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ChangeReporter&lt; IRUnitT &gt;::generateIRRepresentation (<a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, IRUnitT &amp; Output)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>


<p>Referenced by <a href="#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a> and <a href="#a0cf6b2cb664ca54095b4f6dfc5e548cc">llvm::ChangeReporter&lt; IRUnitT &gt;::saveIRBeforePass</a>.</p>

</div>
</div>

### handleAfter() {#a1a276e4bf9b7de55680e1c6d7d9bdb47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ChangeReporter&lt; IRUnitT &gt;::handleAfter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> IRUnitT &amp; Before, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> IRUnitT &amp; After, <a href="/web-llvm/docs/api/classes/llvm/any">Any</a>)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>.</p>


<p>Referenced by <a href="#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a>.</p>

</div>
</div>

### handleFiltered() {#a1675521c5cead992cc80282706b8164e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ChangeReporter&lt; IRUnitT &gt;::handleFiltered (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a>.</p>

</div>
</div>

### handleIgnored() {#a2b1fcd7b1d849f1dd527ead4f68bfce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ChangeReporter&lt; IRUnitT &gt;::handleIgnored (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a>.</p>

</div>
</div>

### handleInitialIR() {#a6fa0872bd1b79f2febb9d0d95c6e9feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ChangeReporter&lt; IRUnitT &gt;::handleInitialIR (<a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>


<p>Referenced by <a href="#a0cf6b2cb664ca54095b4f6dfc5e548cc">llvm::ChangeReporter&lt; IRUnitT &gt;::saveIRBeforePass</a>.</p>

</div>
</div>

### handleInvalidated() {#aa0f43c611d489f2d3d202e1c146e3369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ChangeReporter&lt; IRUnitT &gt;::handleInvalidated (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID)</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#ae18a0ee2e81ff1ec157aef055aea560d">llvm::ChangeReporter&lt; IRUnitT &gt;::handleInvalidatedPass</a>.</p>

</div>
</div>

### omitAfter() {#ac26c95e64f2909319101c59db1fd0a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ChangeReporter&lt; IRUnitT &gt;::omitAfter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a>.</p>

</div>
</div>

### registerRequiredCallbacks() {#aa2fb31feeaf10f23b54a75e244c80035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ChangeReporter::registerRequiredCallbacks (<a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> &amp; PIC)</td>
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



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#ae18a0ee2e81ff1ec157aef055aea560d">llvm::ChangeReporter&lt; IRUnitT &gt;::handleInvalidatedPass</a>, <a href="#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a> and <a href="#a0cf6b2cb664ca54095b4f6dfc5e548cc">llvm::ChangeReporter&lt; IRUnitT &gt;::saveIRBeforePass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irchangedprinter/#a6ab3f8cc3d69d55488725e41bad5e578">llvm::IRChangedPrinter::registerCallbacks</a> and <a href="/web-llvm/docs/api/classes/llvm/irchangedtester/#abb9ab16c8277ed4b633ce6560a1f4fb3">llvm::IRChangedTester::registerCallbacks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BeforeStack {#aaf1e0029cea6b08522657a3b7f795bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;IRUnitT&gt; llvm::ChangeReporter&lt; IRUnitT &gt;::BeforeStack</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#ae18a0ee2e81ff1ec157aef055aea560d">llvm::ChangeReporter&lt; IRUnitT &gt;::handleInvalidatedPass</a>, <a href="#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a>, <a href="#a0cf6b2cb664ca54095b4f6dfc5e548cc">llvm::ChangeReporter&lt; IRUnitT &gt;::saveIRBeforePass</a> and <a href="#af1c5e5a2cc196539deba0a27bc4c6d69">llvm::ChangeReporter&lt; IRUnitT &gt;::~ChangeReporter</a>.</p>

</div>
</div>

### InitialIR {#a48ea4fee95bec21d3fc365158b2ecb60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ChangeReporter&lt; IRUnitT &gt;::InitialIR = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#a0cf6b2cb664ca54095b4f6dfc5e548cc">llvm::ChangeReporter&lt; IRUnitT &gt;::saveIRBeforePass</a>.</p>

</div>
</div>

### VerboseMode {#ac0952fd97e4bf8100ea253b28af483af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::ChangeReporter&lt; IRUnitT &gt;::VerboseMode</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#af02006f8d15a1d0e008c0c6f2774d0e0">llvm::ChangeReporter&lt; IRUnitT &gt;::ChangeReporter</a>, <a href="#ae18a0ee2e81ff1ec157aef055aea560d">llvm::ChangeReporter&lt; IRUnitT &gt;::handleInvalidatedPass</a>, <a href="#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a> and <a href="#a0cf6b2cb664ca54095b4f6dfc5e548cc">llvm::ChangeReporter&lt; IRUnitT &gt;::saveIRBeforePass</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
