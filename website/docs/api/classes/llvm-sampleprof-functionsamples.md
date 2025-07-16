---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/functionsamples
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FunctionSamples` Class Reference

<p>Representation of the samples collected for a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::FunctionSamples { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">llvm/ProfileData/SampleProf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae163ef557cc1e4f04f97809938d12da8">FunctionSamples</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47d1f028cfdd0770debb75ffc2270490">operator==</a> (const FunctionSamples &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8740d169fca6417cee23b5d04429d4">operator!=</a> (const FunctionSamples &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adca18b92b535ad86d151efc86442027d">print</a> (raw_ostream &amp;OS=dbgs(), unsigned Indent=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the samples collected for a function on stream <span class="doxyComputerOutput">OS</span>. <a href="#adca18b92b535ad86d151efc86442027d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e740afafe2e17e2daf7892e794be34">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbe">sampleprof_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263b944b1e1d1b8906ccfa19a565d2ed">addTotalSamples</a> (uint64_t Num, uint64_t Weight=1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d9b9ee0725c4d3af6734f58fda163a3">removeTotalSamples</a> (uint64_t Num)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d5e7a6350d79258f5a8a4e1046e706">setTotalSamples</a> (uint64_t Num)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25159333c9041669c16dcc7ffab2f20d">setHeadSamples</a> (uint64_t Num)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbe">sampleprof_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dda47f9492c59e96d8b43fa6244af20">addHeadSamples</a> (uint64_t Num, uint64_t Weight=1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbe">sampleprof_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab38820a59b382631568b3735469b0890">addBodySamples</a> (uint32_t LineOffset, uint32_t Discriminator, uint64_t Num, uint64_t Weight=1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbe">sampleprof_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951ceadc1dc24cb5041d80ca661c8e3e">addCalledTargetSamples</a> (uint32_t LineOffset, uint32_t Discriminator, FunctionId Func, uint64_t Num, uint64_t Weight=1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbe">sampleprof_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e7908cf776a6963b9a75012c3b873c6">addSampleRecord</a> (LineLocation Location, const SampleRecord &amp;SampleRecord, uint64_t Weight=1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9061493fc416619fdf0a9336784c330b">removeCalledTargetAndBodySample</a> (uint32_t LineOffset, uint32_t Discriminator, FunctionId Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587a41f21d65b518e4cc77b2c705f8e6">removeAllCallsiteSamples</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b36020020e9ffbc6d3739ab7dd8e7e">updateCallsiteSamples</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2137413c9c2e159eb718bb5a797ccb22">updateTotalSamples</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe0ee51b3061c6dde4984d786065ac8">setContextSynthetic</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a6a16ea92ce0f4e3be34d342a496ac">mapIRLocToProfileLoc</a> (const LineLocation &amp;IRLoc) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a678aa3d221b10461f3de2134a14771fb">findSamplesAt</a> (uint32_t LineOffset, uint32_t Discriminator) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of samples collected at the given location. <a href="#a678aa3d221b10461f3de2134a14771fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a25d27170e0de5f9f6d999f8efa3cc32d">SampleRecord::CallTargetMap</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd03b8899e421aa9cab2850607a1b13">findCallTargetMapAt</a> (uint32_t LineOffset, uint32_t Discriminator) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the call target map collected at a given location. <a href="#acbd03b8899e421aa9cab2850607a1b13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a25d27170e0de5f9f6d999f8efa3cc32d">SampleRecord::CallTargetMap</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba4583a6dafd0cdc1c3515d3b2f7b1e">findCallTargetMapAt</a> (const LineLocation &amp;CallSite) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the call target map collected at a given location specified by <span class="doxyComputerOutput">CallSite</span>. <a href="#a6ba4583a6dafd0cdc1c3515d3b2f7b1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abc703dcbcd6d02b1cc94cdbaca94d728">FunctionSamplesMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb031e56118fb0d538ba72e408ec183">functionSamplesAt</a> (const LineLocation &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the function samples at the given callsite location. <a href="#a9cb031e56118fb0d538ba72e408ec183">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abc703dcbcd6d02b1cc94cdbaca94d728">FunctionSamplesMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a540b526d60eebd8bac90d3db8d39acac">findFunctionSamplesMapAt</a> (const LineLocation &amp;Loc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abc703dcbcd6d02b1cc94cdbaca94d728">FunctionSamplesMap</a> at the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>. <a href="#a540b526d60eebd8bac90d3db8d39acac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2590274bcc6c09009ed10feb5455243d">findFunctionSamplesAt</a> (const LineLocation &amp;Loc, StringRef CalleeName, SampleProfileReaderItaniumRemapper *Remapper, const HashKeyMap&lt; std::unordered_map, FunctionId, FunctionId &gt; *FuncNameToProfNameMap=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> at the given callsite location <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> with callee <span class="doxyComputerOutput">CalleeName</span>. <a href="#a2590274bcc6c09009ed10feb5455243d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1b0659ee7d8e17ab407b3bd902e280c">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2786061d3e569b42b7d661ccc57484">getTotalSamples</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the total number of samples collected inside the function. <a href="#adb2786061d3e569b42b7d661ccc57484">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6206d4ca96e6f63a40327a7fa147f2a4">getHeadSamples</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For top-level functions, return the total number of branch samples that have the function as the branch target (or 0 otherwise). <a href="#a6206d4ca96e6f63a40327a7fa147f2a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af757985efc97179779ea3fc9e84f4735">getHeadSamplesEstimate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an estimate of the sample count of the function entry basic block. <a href="#af757985efc97179779ea3fc9e84f4735">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af31c7db8783c9ab394f7479b2a188521">BodySampleMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd62779d71a74d2db69f4fde48b37893">getBodySamples</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all the samples collected in the body of the function. <a href="#afd62779d71a74d2db69f4fde48b37893">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a3b7c07d559f59a50dc34da6371f654ac">CallsiteSampleMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae216a9dc4cce5948cec7fbf16ff462dd">getCallsiteSamples</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all the callsite samples collected in the body of the function. <a href="#ae216a9dc4cce5948cec7fbf16ff462dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a61ffa619580862eac1a3a14a3ff61b">getMaxCountInside</a> (bool SkipCallSite=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum of sample counts in a function body. <a href="#a5a61ffa619580862eac1a3a14a3ff61b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbe">sampleprof_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfcf1b41d1251eac2f16312eec52b45a">merge</a> (const FunctionSamples &amp;Other, uint64_t Weight=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the samples in <span class="doxyComputerOutput">Other</span> into this one. <a href="#adfcf1b41d1251eac2f16312eec52b45a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11631d8c0f91d44ecdc7902a2d2c46cb">findInlinedFunctions</a> (DenseSet&lt; GlobalValue::GUID &gt; &amp;S, const HashKeyMap&lt; std::unordered_map, FunctionId, Function * &gt; &amp;SymbolMap, uint64_t Threshold) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively traverses all children, if the total sample count of the corresponding function is no less than <span class="doxyComputerOutput">Threshold</span>, add its corresponding GUID to <span class="doxyComputerOutput">S</span>. <a href="#a11631d8c0f91d44ecdc7902a2d2c46cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677a143b2118c3ffdf3ecf58384a49cd">setFunction</a> (FunctionId NewFunctionID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the name of the function. <a href="#a677a143b2118c3ffdf3ecf58384a49cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff8c2d016ae9169f35cdd1d1aaa1564">getFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the function name. <a href="#a7ff8c2d016ae9169f35cdd1d1aaa1564">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a46c80625ff1813b321b3a1d46ee37">getFuncName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the original function name. <a href="#aa9a46c80625ff1813b321b3a1d46ee37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac015e530d60203906c93e241682e8359">setFunctionHash</a> (uint64_t Hash)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ffff5be739dfce8ccdb944c3f485306">getFunctionHash</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ca0573ad090043f17127906d98e36b">setIRToProfileLocationMap</a> (const LocToLocMap *LTLM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88645b85849eea5e18797a2abe34fe30">getFuncName</a> (FunctionId Func) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Translate <span class="doxyComputerOutput">Func</span> into its original name. <a href="#a88645b85849eea5e18797a2abe34fe30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24141aebc0d8b15405be6bcb7b6319b">findFunctionSamples</a> (const DILocation *DIL, SampleProfileReaderItaniumRemapper *Remapper=nullptr, const HashKeyMap&lt; std::unordered_map, FunctionId, FunctionId &gt; *FuncNameToProfNameMap=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> of the inline instance where DIL originates from. <a href="#aa24141aebc0d8b15405be6bcb7b6319b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad117577730085f895045fc7ff90d8fc2">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6507284ccb03c1c44fe0e7d37650493">setContext</a> (const SampleContext &amp;FContext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb077bf8dc20e4016e83042d3f784d32">getGUID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the GUID of the context's name. <a href="#afb077bf8dc20e4016e83042d3f784d32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9bc1c5737890ec54fe6dac03c1ffdd0">findAllNames</a> (DenseSet&lt; FunctionId &gt; &amp;NameSet) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91af3b8d4902917c684804e96a7fe71a">GUIDToFuncNameMap</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GUIDToFuncNameMap saves the mapping from GUID to the symbol name, for all the function symbols defined or declared in current module. <a href="#a91af3b8d4902917c684804e96a7fe71a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a031cc2fe0a5d428cc02adfde5fdf9f77">FunctionHash</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CFG hash value for the function. <a href="#a031cc2fe0a5d428cc02adfde5fdf9f77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af3bde75aba0f8af5d1af3135136111">Context</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calling context for function profile. <a href="#a2af3bde75aba0f8af5d1af3135136111">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed1443daf6d8151f70b6dad718e92d1">TotalSamples</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total number of samples collected inside this function. <a href="#a7ed1443daf6d8151f70b6dad718e92d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8537545241265b6ba0f2d5ebba0701ad">TotalHeadSamples</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total number of samples collected at the head of the function. <a href="#a8537545241265b6ba0f2d5ebba0701ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af31c7db8783c9ab394f7479b2a188521">BodySampleMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6556cb0983d2d5e24305758a00e7c173">BodySamples</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map instruction locations to collected samples. <a href="#a6556cb0983d2d5e24305758a00e7c173">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a3b7c07d559f59a50dc34da6371f654ac">CallsiteSampleMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97dc6666aa6cfbb2439b1ac7d4e9a443">CallsiteSamples</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map call sites to collected samples for the called function. <a href="#a97dc6666aa6cfbb2439b1ac7d4e9a443">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ac5c498b2a2603e7b437b91b6dcd3a9f9">LocToLocMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a478b9f904d94a1166f0fe36e59fd58cc">IRToProfileLocationMap</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IR to profile location map generated by stale profile matching. <a href="#a478b9f904d94a1166f0fe36e59fd58cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7122a07ea48e47fc71083e68b829003">getCanonicalFnName</a> (const Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the canonical name for a function, taking into account suffix elision policy attributes. <a href="#aa7122a07ea48e47fc71083e68b829003">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b7e51dcb0e1efd0a84eb6398fd6301">getCanonicalFnName</a> (StringRef FnName, StringRef Attr="selected")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f00f222e6f6d30bc6a0fc7bf8396de">getOffset</a> (const DILocation *DIL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the line offset to the start line of the subprogram. <a href="#ab6f00f222e6f6d30bc6a0fc7bf8396de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea4c49a1040f9305f6a09d7d7815544">getCallSiteIdentifier</a> (const DILocation *DIL, bool ProfileIsFS=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a unique call site identifier for a given debug location of a call instruction. <a href="#aeea4c49a1040f9305f6a09d7d7815544">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fc907c22a54099eca9b792ab963b4a3">getCallSiteHash</a> (FunctionId Callee, const LineLocation &amp;Callsite)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a unique hash code for a combination of a callsite location and the callee function name. <a href="#a4fc907c22a54099eca9b792ab963b4a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8555584357a2929cd1746a5e23b95188">LLVMSuffix</a> = ".llvm."</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name suffixes which canonicalization should handle to avoid profile mismatch. <a href="#a8555584357a2929cd1746a5e23b95188">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4810779ce0c4abbfff59843113510764">PartSuffix</a> = ".part."</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c9ea2741f8ae073da01be9dfcae147a">UniqSuffix</a> = ".__uniq."</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa37fe7429ffcf70c306c27a55d714d31">ProfileIsProbeBased</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e19eb484a5eaa31b22894398e258c0">ProfileIsCS</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b33b498078ac3694a992f4ab8a5761">ProfileIsPreInlined</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afddaa81316d56f125de69793e0ddb33c">UseMD5</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the profile uses <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> to represent string. <a href="#afddaa81316d56f125de69793e0ddb33c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad20fb2a274b13a7820568739fbcba383">HasUniqSuffix</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the profile contains any ".__uniq." suffix in a name. <a href="#ad20fb2a274b13a7820568739fbcba383">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78db34e62da1555e9b84b5b5b1d907d">ProfileIsFS</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this profile uses flow sensitive discriminators. <a href="#ac78db34e62da1555e9b84b5b5b1d907d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Representation of the samples collected for a function.</p>


<p>This data structure contains all the collected samples for the body of a function. Each sample corresponds to a <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> instance within the body of the function.</p>


<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionSamples() {#ae163ef557cc1e4f04f97809938d12da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::FunctionSamples::FunctionSamples ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#aa24141aebc0d8b15405be6bcb7b6319b">findFunctionSamples</a>, <a href="#a2590274bcc6c09009ed10feb5455243d">findFunctionSamplesAt</a>, <a href="#adfcf1b41d1251eac2f16312eec52b45a">merge</a>, <a href="#a1e8740d169fca6417cee23b5d04429d4">operator!=</a> and <a href="#a47d1f028cfdd0770debb75ffc2270490">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a1e8740d169fca6417cee23b5d04429d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionSamples::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; Other)</td>
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



<p>Definition at line 1230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#ae163ef557cc1e4f04f97809938d12da8">FunctionSamples</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a47d1f028cfdd0770debb75ffc2270490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionSamples::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; Other)</td>
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



<p>Definition at line 1219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#ae163ef557cc1e4f04f97809938d12da8">FunctionSamples</a>, <a href="#a91af3b8d4902917c684804e96a7fe71a">GUIDToFuncNameMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBodySamples() {#ab38820a59b382631568b3735469b0890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sampleprof_error llvm::sampleprof::FunctionSamples::addBodySamples (uint32_t LineOffset, uint32_t Discriminator, uint64_t Num, uint64_t Weight=1)</td>
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



<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a0320040b070e4fc2904794078a64e46c">llvm::sampleprof::SampleProfileReaderBinary::readProfile</a>.</p>

</div>
</div>

### addCalledTargetSamples() {#a951ceadc1dc24cb5041d80ca661c8e3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sampleprof_error llvm::sampleprof::FunctionSamples::addCalledTargetSamples (uint32_t LineOffset, uint32_t Discriminator, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> Func, uint64_t Num, uint64_t Weight=1)</td>
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



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a0320040b070e4fc2904794078a64e46c">llvm::sampleprof::SampleProfileReaderBinary::readProfile</a>.</p>

</div>
</div>

### addHeadSamples() {#a8dda47f9492c59e96d8b43fa6244af20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sampleprof_error llvm::sampleprof::FunctionSamples::addHeadSamples (uint64_t Num, uint64_t Weight=1)</td>
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



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea5e8bae22cbd37f66c813d8a3749bda1c">llvm::counter_overflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84836a719cdf82a516d556ae66cc8dc0">llvm::SaturatingMultiplyAdd</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#adfcf1b41d1251eac2f16312eec52b45a">merge</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a52d0fff5d3fdc4368cb7b9a2edda2b6f">llvm::sampleprof::SampleProfileReaderBinary::readFuncProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a>.</p>

</div>
</div>

### addSampleRecord() {#a8e7908cf776a6963b9a75012c3b873c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sampleprof_error llvm::sampleprof::FunctionSamples::addSampleRecord (<a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> Location, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord">SampleRecord</a> &amp; SampleRecord, uint64_t Weight=1)</td>
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



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### addTotalSamples() {#a263b944b1e1d1b8906ccfa19a565d2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sampleprof_error llvm::sampleprof::FunctionSamples::addTotalSamples (uint64_t Num, uint64_t Weight=1)</td>
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



<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea5e8bae22cbd37f66c813d8a3749bda1c">llvm::counter_overflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84836a719cdf82a516d556ae66cc8dc0">llvm::SaturatingMultiplyAdd</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#adfcf1b41d1251eac2f16312eec52b45a">merge</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a0320040b070e4fc2904794078a64e46c">llvm::sampleprof::SampleProfileReaderBinary::readProfile</a> and <a href="#a2137413c9c2e159eb718bb5a797ccb22">updateTotalSamples</a>.</p>

</div>
</div>

### dump() {#ae4e740afafe2e17e2daf7892e794be34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void FunctionSamples::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#adca18b92b535ad86d151efc86442027d">print</a>.</p>

</div>
</div>

### empty() {#aa1b0659ee7d8e17ab407b3bd902e280c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionSamples::empty ()</td>
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



<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### findAllNames() {#aa9bc1c5737890ec54fe6dac03c1ffdd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionSamples::findAllNames (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; &amp; NameSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="#a7ff8c2d016ae9169f35cdd1d1aaa1564">getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>.</p>

</div>
</div>

### findCallTargetMapAt() {#acbd03b8899e421aa9cab2850607a1b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; const SampleRecord::CallTargetMap &amp; &gt; llvm::sampleprof::FunctionSamples::findCallTargetMapAt (uint32_t LineOffset, uint32_t Discriminator)</td>
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

<p>Returns the call target map collected at a given location.</p>


<p>Each location is specified by <span class="doxyComputerOutput">LineOffset</span> and <span class="doxyComputerOutput">Discriminator</span>. If the location is not found in profile, return error.</p>


<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="#a71a6a16ea92ce0f4e3be34d342a496ac">mapIRLocToProfileLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph/#acae2ab44bcb9d9add7c351061ac8e6f6">llvm::sampleprof::ProfiledCallGraph::ProfiledCallGraph</a>.</p>

</div>
</div>

### findCallTargetMapAt() {#a6ba4583a6dafd0cdc1c3515d3b2f7b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; const SampleRecord::CallTargetMap &amp; &gt; llvm::sampleprof::FunctionSamples::findCallTargetMapAt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; CallSite)</td>
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

<p>Returns the call target map collected at a given location specified by <span class="doxyComputerOutput">CallSite</span>.</p>


<p>If the location is not found in profile, return error.</p>


<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="#a71a6a16ea92ce0f4e3be34d342a496ac">mapIRLocToProfileLoc</a>.</p>

</div>
</div>

### findFunctionSamples() {#aa24141aebc0d8b15405be6bcb7b6319b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionSamples * FunctionSamples::findFunctionSamples (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DIL, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderitaniumremapper">SampleProfileReaderItaniumRemapper</a> * Remapper=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; * FuncNameToProfNameMap=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> of the inline instance where DIL originates from.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> of the instruction (Machine or IR) associated to <span class="doxyComputerOutput">DIL</span> is the inlined instance in which that instruction is coming from. We traverse the inline stack of that instruction, and match it with the tree nodes in the profile.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> pointer to the inlined instance. If <span class="doxyComputerOutput">Remapper</span> or <span class="doxyComputerOutput">FuncNameToProfNameMap</span> is not nullptr, it will be used to find matching <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> with not exactly the same but equivalent name.</p></dd>
</dl>


<p>Declaration at line 1180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#ae163ef557cc1e4f04f97809938d12da8">FunctionSamples</a>, <a href="#aeea4c49a1040f9305f6a09d7d7815544">getCallSiteIdentifier</a>, <a href="#ac78db34e62da1555e9b84b5b5b1d907d">ProfileIsFS</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-x86insertprefetch-cpp-/#a6bc620bb30e51cbda53a5936bc63064a">anonymous{X86InsertPrefetch.cpp}::getPrefetchHints</a>.</p>

</div>
</div>

### findFunctionSamplesAt() {#a2590274bcc6c09009ed10feb5455243d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionSamples * FunctionSamples::findFunctionSamplesAt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CalleeName, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderitaniumremapper">SampleProfileReaderItaniumRemapper</a> * Remapper, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; * FuncNameToProfNameMap=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> at the given callsite location <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> with callee <span class="doxyComputerOutput">CalleeName</span>.</p>


<p>If no callsite can be found, relax the restriction to return the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> at callsite location <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> with the maximum total sample count. If <span class="doxyComputerOutput">Remapper</span> or <span class="doxyComputerOutput">FuncNameToProfNameMap</span> is not nullptr, use them to find <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> with equivalent name as <span class="doxyComputerOutput">CalleeName</span>.</p>


<p>Declaration at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap/#ae4b75fa9a69ea101d484665ded779afa">llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::find</a>, <a href="#ae163ef557cc1e4f04f97809938d12da8">FunctionSamples</a>, <a href="#aa7122a07ea48e47fc71083e68b829003">getCanonicalFnName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a012731cbc58856aff956543ab824eb8d">llvm::sampleprof::getRepInFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderitaniumremapper/#ae86f8a71098cd0a7a0ccd0d2e9f9156f">llvm::sampleprof::SampleProfileReaderItaniumRemapper::lookUpNameInProfile</a> and <a href="#a71a6a16ea92ce0f4e3be34d342a496ac">mapIRLocToProfileLoc</a>.</p>

</div>
</div>

### findFunctionSamplesMapAt() {#a540b526d60eebd8bac90d3db8d39acac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionSamplesMap * llvm::sampleprof::FunctionSamples::findFunctionSamplesMapAt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; Loc)</td>
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

<p>Returns the <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abc703dcbcd6d02b1cc94cdbaca94d728">FunctionSamplesMap</a> at the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>.</p>

<p>Definition at line 912 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="#a71a6a16ea92ce0f4e3be34d342a496ac">mapIRLocToProfileLoc</a>.</p>

</div>
</div>

### findInlinedFunctions() {#a11631d8c0f91d44ecdc7902a2d2c46cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::findInlinedFunctions (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; SymbolMap, uint64_t Threshold)</td>
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

<p>Recursively traverses all children, if the total sample count of the corresponding function is no less than <span class="doxyComputerOutput">Threshold</span>, add its corresponding GUID to <span class="doxyComputerOutput">S</span>.</p>


<p>Also traverse the BodySamples to add hot CallTarget's GUID to <span class="doxyComputerOutput">S</span>.</p>


<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a7ff8c2d016ae9169f35cdd1d1aaa1564">getFunction</a>, <a href="#afb077bf8dc20e4016e83042d3f784d32">getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>.</p>

</div>
</div>

### findSamplesAt() {#a678aa3d221b10461f3de2134a14771fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; uint64_t &gt; llvm::sampleprof::FunctionSamples::findSamplesAt (uint32_t LineOffset, uint32_t Discriminator)</td>
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

<p>Return the number of samples collected at the given location.</p>


<p>Each location is specified by <span class="doxyComputerOutput">LineOffset</span> and <span class="doxyComputerOutput">Discriminator</span>. If the location is not found in profile, return error.</p>


<p>Definition at line 874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="#a71a6a16ea92ce0f4e3be34d342a496ac">mapIRLocToProfileLoc</a>.</p>

</div>
</div>

### functionSamplesAt() {#a9cb031e56118fb0d538ba72e408ec183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamplesMap &amp; llvm::sampleprof::FunctionSamples::functionSamplesAt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; Loc)</td>
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

<p>Return the function samples at the given callsite location.</p>

<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="#a71a6a16ea92ce0f4e3be34d342a496ac">mapIRLocToProfileLoc</a>.</p>


<p>Referenced by <a href="#adfcf1b41d1251eac2f16312eec52b45a">merge</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a0320040b070e4fc2904794078a64e46c">llvm::sampleprof::SampleProfileReaderBinary::readProfile</a>.</p>

</div>
</div>

### getBodySamples() {#afd62779d71a74d2db69f4fde48b37893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BodySampleMap &amp; llvm::sampleprof::FunctionSamples::getBodySamples ()</td>
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

<p>Return all the samples collected in the body of the function.</p>

<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a880b4a9e6f81baaa1c9a1fe9a2151cfd">llvm::sampleprof::SampleProfileWriterBinary::addNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>, <a href="#a5a61ffa619580862eac1a3a14a3ff61b">getMaxCountInside</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/candidatecomparer/#a81ad3aa9c9fb5b9d14bbdecf82cadfe5">anonymous{SampleProfile.cpp}::CandidateComparer::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ae7c088ecf1befc97ec9b4d36f30ae06d">llvm::sampleprof::SampleProfileWriterBinary::writeBody</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### getCallsiteSamples() {#ae216a9dc4cce5948cec7fbf16ff462dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallsiteSampleMap &amp; llvm::sampleprof::FunctionSamples::getCallsiteSamples ()</td>
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

<p>Return all the callsite samples collected in the body of the function.</p>

<p>Definition at line 976 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a880b4a9e6f81baaa1c9a1fe9a2151cfd">llvm::sampleprof::SampleProfileWriterBinary::addNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="#a5a61ffa619580862eac1a3a14a3ff61b">getMaxCountInside</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ae7c088ecf1befc97ec9b4d36f30ae06d">llvm::sampleprof::SampleProfileWriterBinary::writeBody</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a96315b9b9bda521e4026e537c7d9f139">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### getContext() {#ad117577730085f895045fc7ff90d8fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleContext &amp; llvm::sampleprof::FunctionSamples::getContext ()</td>
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



<p>Definition at line 1192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a75bd919afb45ef334b6e8fa723d4beb5">llvm::SampleContextTracker::getContextSamplesFor</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#aa144b495aee60da309a023d554952ac9">llvm::SampleContextTracker::markContextSamplesInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a3f0ac0cd0b840c490d896fd333c79c51">llvm::SampleContextTracker::populateFuncToCtxtMap</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profileconverter/#a8dd98bf48ac899ee7b412afab4c2f3d0">llvm::sampleprof::ProfileConverter::ProfileConverter</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a03cbc7841d2552fcd7639666975fa13c">llvm::SampleContextTracker::promoteMergeContextSamplesTree</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a58cedb1356bab80647af0fa48bc1750a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a518b0cf18edfb9fb05aaa530550af870">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ae7c088ecf1befc97ec9b4d36f30ae06d">llvm::sampleprof::SampleProfileWriterBinary::writeBody</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a96315b9b9bda521e4026e537c7d9f139">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#af5cddc155fef09dd03f4493e99524109">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeSample</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### getFuncName() {#aa9a46c80625ff1813b321b3a1d46ee37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sampleprof::FunctionSamples::getFuncName ()</td>
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

<p>Return the original function name.</p>

<p>Definition at line 1077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#aa9a46c80625ff1813b321b3a1d46ee37">getFuncName</a> and <a href="#a7ff8c2d016ae9169f35cdd1d1aaa1564">getFunction</a>.</p>


<p>Referenced by <a href="#aa9a46c80625ff1813b321b3a1d46ee37">getFuncName</a>.</p>

</div>
</div>

### getFuncName() {#a88645b85849eea5e18797a2abe34fe30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sampleprof::FunctionSamples::getFuncName (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> Func)</td>
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

<p>Translate <span class="doxyComputerOutput">Func</span> into its original name.</p>


<p>When profile doesn't use <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a>, <span class="doxyComputerOutput">Func</span> needs no translation. When profile uses <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a>, <span class="doxyComputerOutput">Func</span> in current <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> is actually GUID of the original function name. getFuncName will translate <span class="doxyComputerOutput">Func</span> in current <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> into its original name by looking up in the function map GUIDToFuncNameMap. If the original name doesn't exist in the map, return empty <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a91af3b8d4902917c684804e96a7fe71a">GUIDToFuncNameMap</a> and <a href="#afddaa81316d56f125de69793e0ddb33c">UseMD5</a>.</p>

</div>
</div>

### getFunction() {#a7ff8c2d016ae9169f35cdd1d1aaa1564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionId llvm::sampleprof::FunctionSamples::getFunction ()</td>
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

<p>Return the function name.</p>

<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a880b4a9e6f81baaa1c9a1fe9a2151cfd">llvm::sampleprof::SampleProfileWriterBinary::addNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="#aa9bc1c5737890ec54fe6dac03c1ffdd0">findAllNames</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>, <a href="#a11631d8c0f91d44ecdc7902a2d2c46cb">findInlinedFunctions</a>, <a href="#aa9a46c80625ff1813b321b3a1d46ee37">getFuncName</a>, <a href="#afb077bf8dc20e4016e83042d3f784d32">getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph/#acae2ab44bcb9d9add7c351061ac8e6f6">llvm::sampleprof::ProfiledCallGraph::ProfiledCallGraph</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ad5c772a0b61cb29106af3a4f9ae43d59">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryPromoteAndInlineCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### getFunctionHash() {#a7ffff5be739dfce8ccdb944c3f485306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::getFunctionHash ()</td>
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



<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#adca18b92b535ad86d151efc86442027d">print</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobemanager/#aa1eb96ee74fc6ee33a0f951b11dfa0fc">llvm::PseudoProbeManager::profileIsHashMismatched</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a96315b9b9bda521e4026e537c7d9f139">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### getGUID() {#afb077bf8dc20e4016e83042d3f784d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::getGUID ()</td>
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

<p>Return the GUID of the context's name.</p>


<p>If the context is already using <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a>, don't hash it again.</p>


<p>Definition at line 1211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#a7ff8c2d016ae9169f35cdd1d1aaa1564">getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid/#a5c097d6625bd9e8132f391309e787943">llvm::sampleprof::FunctionId::getHashCode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>, <a href="#a11631d8c0f91d44ecdc7902a2d2c46cb">findInlinedFunctions</a> and <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/candidatecomparer/#a81ad3aa9c9fb5b9d14bbdecf82cadfe5">anonymous{SampleProfile.cpp}::CandidateComparer::operator()</a>.</p>

</div>
</div>

### getHeadSamples() {#a6206d4ca96e6f63a40327a7fa147f2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::getHeadSamples ()</td>
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

<p>For top-level functions, return the total number of branch samples that have the function as the branch target (or 0 otherwise).</p>


<p>This is the raw data fetched from the profile. This should be equivalent to the sample of the first instruction of the symbol. But as we directly get this info for raw profile without referring to potentially inaccurate debug info, this gives more accurate profile data and is preferred for standalone symbols.</p>


<p>Definition at line 942 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="#af757985efc97179779ea3fc9e84f4735">getHeadSamplesEstimate</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#aa8f09f0411e75db5fd532622f3e169bc">llvm::sampleprof::SampleProfileWriterBinary::writeSample</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#af5cddc155fef09dd03f4493e99524109">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeSample</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### getHeadSamplesEstimate() {#af757985efc97179779ea3fc9e84f4735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::getHeadSamplesEstimate ()</td>
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

<p>Return an estimate of the sample count of the function entry basic block.</p>


<p>The function can be either a standalone symbol or an inlined function. For Context-Sensitive profiles, this will prefer returning the head samples (i.e. <a href="#a6206d4ca96e6f63a40327a7fa147f2a4">getHeadSamples()</a>), if non-zero. Otherwise it estimates from the function body's samples or callsite samples.</p>


<p>Definition at line 949 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a6206d4ca96e6f63a40327a7fa147f2a4">getHeadSamples</a> and <a href="#a67e19eb484a5eaa31b22894398e258c0">ProfileIsCS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a284bbebbcad19f7e38253a1a8df134b5">anonymous{SampleProfile.cpp}::SampleProfileLoader::getInlineCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph/#acae2ab44bcb9d9add7c351061ac8e6f6">llvm::sampleprof::ProfiledCallGraph::ProfiledCallGraph</a>.</p>

</div>
</div>

### getMaxCountInside() {#a5a61ffa619580862eac1a3a14a3ff61b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::getMaxCountInside (bool SkipCallSite=false)</td>
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

<p>Return the maximum of sample counts in a function body.</p>


<p>When SkipCallSite is false, which is the default, the return count includes samples in the inlined functions. When SkipCallSite is true, the return count only considers the body samples.</p>


<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#afd62779d71a74d2db69f4fde48b37893">getBodySamples</a> and <a href="#ae216a9dc4cce5948cec7fbf16ff462dd">getCallsiteSamples</a>.</p>

</div>
</div>

### getTotalSamples() {#adb2786061d3e569b42b7d661ccc57484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::getTotalSamples ()</td>
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

<p>Return the total number of samples collected inside the function.</p>

<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sampleprofutil/#ab6789a9522443425d339fa34c25f89d5">llvm::sampleprofutil::callsiteIsHot</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a53db652fc4a21c80c9094604ee15c334">llvm::ContextTrieNode::getHottestChildContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontexttrimmer/#ab47fa20fa1c0dd43ae044963ee59049c">llvm::sampleprof::SampleContextTrimmer::trimAndMergeColdContextProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ae7c088ecf1befc97ec9b4d36f30ae06d">llvm::sampleprof::SampleProfileWriterBinary::writeBody</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### mapIRLocToProfileLoc() {#a71a6a16ea92ce0f4e3be34d342a496ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LineLocation &amp; llvm::sampleprof::FunctionSamples::mapIRLocToProfileLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; IRLoc)</td>
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



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#a6ba4583a6dafd0cdc1c3515d3b2f7b1e">findCallTargetMapAt</a>, <a href="#acbd03b8899e421aa9cab2850607a1b13">findCallTargetMapAt</a>, <a href="#a2590274bcc6c09009ed10feb5455243d">findFunctionSamplesAt</a>, <a href="#a540b526d60eebd8bac90d3db8d39acac">findFunctionSamplesMapAt</a>, <a href="#a678aa3d221b10461f3de2134a14771fb">findSamplesAt</a> and <a href="#a9cb031e56118fb0d538ba72e408ec183">functionSamplesAt</a>.</p>

</div>
</div>

### merge() {#adfcf1b41d1251eac2f16312eec52b45a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sampleprof_error llvm::sampleprof::FunctionSamples::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; Other, uint64_t Weight=1)</td>
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

<p>Merge the samples in <span class="doxyComputerOutput">Other</span> into this one.</p>


<p>Optionally scale samples by <span class="doxyComputerOutput">Weight</span>.</p>


<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#a8dda47f9492c59e96d8b43fa6244af20">addHeadSamples</a>, <a href="#a263b944b1e1d1b8906ccfa19a565d2ed">addTotalSamples</a>, <a href="#ae163ef557cc1e4f04f97809938d12da8">FunctionSamples</a>, <a href="#a9cb031e56118fb0d538ba72e408ec183">functionSamplesAt</a>, <a href="#a91af3b8d4902917c684804e96a7fe71a">GUIDToFuncNameMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeacb2fe3792bca163395ce75d581440847">llvm::hash_mismatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#adfcf1b41d1251eac2f16312eec52b45a">merge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6af78b474302640c3fd76f2e8031f9f9">llvm::mergeSampleProfErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#ac5b41c4e8db4215ef2a11b40cca0525d">llvm::SampleContextTracker::createContextLessProfileMap</a>, <a href="#adfcf1b41d1251eac2f16312eec52b45a">merge</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a16e99ef185f55c3e45caf11c880998ff">anonymous{SampleProfile.cpp}::SampleProfileLoader::promoteMergeNotInlinedContextSamples</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontexttrimmer/#ab47fa20fa1c0dd43ae044963ee59049c">llvm::sampleprof::SampleContextTrimmer::trimAndMergeColdContextProfiles</a>.</p>

</div>
</div>

### print() {#adca18b92b535ad86d151efc86442027d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionSamples::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS=<a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs</a>(), unsigned Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the samples collected for a function on stream <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplesorter/#a63724eb0b03848a61809932b0d5a63a7">llvm::sampleprof::SampleSorter&lt; LocationT, SampleT &gt;::get</a>, <a href="#a7ffff5be739dfce8ccdb944c3f485306">getFunctionHash</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>.</p>


<p>Referenced by <a href="#ae4e740afafe2e17e2daf7892e794be34">dump</a>.</p>

</div>
</div>

### removeAllCallsiteSamples() {#a587a41f21d65b518e4cc77b2c705f8e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::removeAllCallsiteSamples ()</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### removeCalledTargetAndBodySample() {#a9061493fc416619fdf0a9336784c330b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::removeCalledTargetAndBodySample (uint32_t LineOffset, uint32_t Discriminator, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> Func)</td>
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



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### removeTotalSamples() {#a5d9b9ee0725c4d3af6734f58fda163a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::removeTotalSamples (uint64_t Num)</td>
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



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### setContext() {#ae6507284ccb03c1c44fe0e7d37650493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::setContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; FContext)</td>
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



<p>Definition at line 1194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a52d0fff5d3fdc4368cb7b9a2edda2b6f">llvm::sampleprof::SampleProfileReaderBinary::readFuncProfile</a>.</p>

</div>
</div>

### setContextSynthetic() {#abfe0ee51b3061c6dde4984d786065ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::setContextSynthetic ()</td>
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



<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8acab2e6b6d8b22672f40e617c7dfedd302a">llvm::sampleprof::SyntheticContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a16e99ef185f55c3e45caf11c880998ff">anonymous{SampleProfile.cpp}::SampleProfileLoader::promoteMergeNotInlinedContextSamples</a>.</p>

</div>
</div>

### setFunction() {#a677a143b2118c3ffdf3ecf58384a49cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::setFunction (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> NewFunctionID)</td>
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

<p>Set the name of the function.</p>

<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a0320040b070e4fc2904794078a64e46c">llvm::sampleprof::SampleProfileReaderBinary::readProfile</a>.</p>

</div>
</div>

### setFunctionHash() {#ac015e530d60203906c93e241682e8359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::setFunctionHash (uint64_t Hash)</td>
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



<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>.</p>

</div>
</div>

### setHeadSamples() {#a25159333c9041669c16dcc7ffab2f20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::setHeadSamples (uint64_t Num)</td>
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



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### setIRToProfileLocationMap() {#aa4ca0573ad090043f17127906d98e36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::setIRToProfileLocationMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ac5c498b2a2603e7b437b91b6dcd3a9f9">LocToLocMap</a> * LTLM)</td>
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



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### setTotalSamples() {#a02d5e7a6350d79258f5a8a4e1046e706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::setTotalSamples (uint64_t Num)</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#a2137413c9c2e159eb718bb5a797ccb22">updateTotalSamples</a>.</p>

</div>
</div>

### updateCallsiteSamples() {#a32b36020020e9ffbc6d3739ab7dd8e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::updateCallsiteSamples ()</td>
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



<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### updateTotalSamples() {#a2137413c9c2e159eb718bb5a797ccb22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::FunctionSamples::updateTotalSamples ()</td>
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



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#a263b944b1e1d1b8906ccfa19a565d2ed">addTotalSamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a02d5e7a6350d79258f5a8a4e1046e706">setTotalSamples</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### GUIDToFuncNameMap {#a91af3b8d4902917c684804e96a7fe71a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint64_t, StringRef&gt;* llvm::sampleprof::FunctionSamples::GUIDToFuncNameMap = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GUIDToFuncNameMap saves the mapping from GUID to the symbol name, for all the function symbols defined or declared in current module.</p>

<p>Definition at line 1207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#a88645b85849eea5e18797a2abe34fe30">getFuncName</a>, <a href="#adfcf1b41d1251eac2f16312eec52b45a">merge</a> and <a href="#a47d1f028cfdd0770debb75ffc2270490">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BodySamples {#a6556cb0983d2d5e24305758a00e7c173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BodySampleMap llvm::sampleprof::FunctionSamples::BodySamples</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map instruction locations to collected samples.</p>


<p>Each entry in this map contains the number of samples collected at the corresponding line offset. All line locations are an offset from the start of the function.</p>


<p>Definition at line 1257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### CallsiteSamples {#a97dc6666aa6cfbb2439b1ac7d4e9a443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteSampleMap llvm::sampleprof::FunctionSamples::CallsiteSamples</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map call sites to collected samples for the called function.</p>


<p>Each entry in this map corresponds to all the samples collected for the inlined function call at the given location. For example, given:</p>



<pre><code>void foo() {
</code></pre>


<p>1 bar(); ... 8 baz(); }</p>


<p>If the bar() and baz() calls were inlined inside foo(), this map will contain two entries. One for all the samples collected in the call to bar() at line offset 1, the other for all the samples collected in the call to baz() at line offset 8.</p>


<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### Context {#a2af3bde75aba0f8af5d1af3135136111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleContext llvm::sampleprof::FunctionSamples::Context</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calling context for function profile.</p>

<p>Definition at line 1239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### FunctionHash {#a031cc2fe0a5d428cc02adfde5fdf9f77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::FunctionHash = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CFG hash value for the function.</p>

<p>Definition at line 1236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### IRToProfileLocationMap {#a478b9f904d94a1166f0fe36e59fd58cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LocToLocMap* llvm::sampleprof::FunctionSamples::IRToProfileLocationMap = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IR to profile location map generated by stale profile matching.</p>


<p>Each entry is a mapping from the location on current build to the matched location in the "stale" profile. For example: Profiled source code: void foo() { 1 bar(); }</p>


<p>Current source code: void foo() { 1 // Code change 2 bar(); } Supposing the stale profile matching algorithm generated the mapping [2 -&gt; 1], the profile query using the location of bar on the IR which is 2 will be remapped to 1 and find the location of bar in the profile.</p>


<p>Definition at line 1294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### TotalHeadSamples {#a8537545241265b6ba0f2d5ebba0701ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::TotalHeadSamples = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total number of samples collected at the head of the function.</p>


<p>This is an approximation of the number of calls made to this function at runtime.</p>


<p>Definition at line 1250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### TotalSamples {#a7ed1443daf6d8151f70b6dad718e92d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::TotalSamples = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total number of samples collected inside this function.</p>


<p>Samples are cumulative, they include all the samples collected inside this function and all its inlined callees.</p>


<p>Definition at line 1245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getCallSiteHash() {#a4fc907c22a54099eca9b792ab963b4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionSamples::getCallSiteHash (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; Callsite)</td>
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

<p>Returns a unique hash code for a combination of a callsite location and the callee function name.</p>


<p>Guarantee <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> and non-MD5 representation of the same function results in the same hash.</p>


<p>Definition at line 1163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/sampleprof/samplecontextframe/#aa0f956365775a43dc8de83e5c0de36a6">llvm::sampleprof::SampleContextFrame::getHashCode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#ab05fd0aa0f2a966006e4b4bd448617e7">llvm::ContextTrieNode::getChildContext</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a0aa47b79624491957a2ba676d69bd886">llvm::ContextTrieNode::getOrCreateChildContext</a>, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/profileconverter/framenode/#aa392b994d1cf7abfc67e7fc7da1a5424">llvm::sampleprof::ProfileConverter::FrameNode::getOrCreateChildFrame</a> and <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a77604ff4be17a6eb893f38f8e57d437a">llvm::ContextTrieNode::removeChildContext</a>.</p>

</div>
</div>

### getCallSiteIdentifier() {#aeea4c49a1040f9305f6a09d7d7815544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineLocation FunctionSamples::getCallSiteIdentifier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DIL, bool ProfileIsFS=false)</td>
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

<p>Returns a unique call site identifier for a given debug location of a call instruction.</p>


<p>This is wrapper of two scenarios, the probe-based profile and regular profile, to hide implementation details from the sample loader and the context tracker.</p>


<p>Declaration at line 1156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/pseudoprobedwarfdiscriminator/#a5db4061b62e740850ad71806b1dbd60e">llvm::PseudoProbeDwarfDiscriminator::extractProbeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a959d7d5282de6f6f459425591e7482d7">llvm::DILocation::getBaseDiscriminator</a>, <a href="#ab6f00f222e6f6d30bc6a0fc7bf8396de">getOffset</a>, <a href="#ac78db34e62da1555e9b84b5b5b1d907d">ProfileIsFS</a> and <a href="#aa37fe7429ffcf70c306c27a55d714d31">ProfileIsProbeBased</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a219e9fac05a219d48a97e03304f84613">anonymous{SampleProfile.cpp}::SampleProfileLoader::findCalleeFunctionSamples</a>, <a href="#aa24141aebc0d8b15405be6bcb7b6319b">findFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#abf8457f6ea82a821ee3fb08dae6246d9">anonymous{SampleProfile.cpp}::SampleProfileLoader::findIndirectCallFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#af2c5a7cbd593261dc632d06d8225c04d">llvm::SampleContextTracker::getIndirectCalleeContextSamplesFor</a> and <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a03cbc7841d2552fcd7639666975fa13c">llvm::SampleContextTracker::promoteMergeContextSamplesTree</a>.</p>

</div>
</div>

### getCanonicalFnName() {#aa7122a07ea48e47fc71083e68b829003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sampleprof::FunctionSamples::getCanonicalFnName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Return the canonical name for a function, taking into account suffix elision policy attributes.</p>

<p>Definition at line 1090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#aa7122a07ea48e47fc71083e68b829003">getCanonicalFnName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#af64b545a1de5a343850725733d522546">anonymous{SampleProfile.cpp}::SampleProfileLoader::buildProfiledCallGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a0d0cdeb3cf9845558d9577f37fc326b3">llvm::sampleprof::SampleProfileReaderExtBinaryBase::collectFuncsFromModule</a>, <a href="#a2590274bcc6c09009ed10feb5455243d">findFunctionSamplesAt</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a83f63b9731fdab5bde79ae70ece636b9">llvm::SampleContextTracker::getAllContextSamplesFor</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a0b4a3e47e33b66648a8b870f6182c1f2">llvm::SampleContextTracker::getBaseSamplesFor</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#af9a5eace41510a920670a82474022c7a">llvm::SampleContextTracker::getCalleeContextSamplesFor</a>, <a href="#aa7122a07ea48e47fc71083e68b829003">getCanonicalFnName</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobemanager/#aaea75c52e4662f007940b2ebba65e6c0">llvm::PseudoProbeManager::getDesc</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord/#ace5015b378d124a205da5a1eaf98061e">llvm::memprof::IndexedMemProfRecord::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a231496cee212bad0c2b9fa7877dc0cb4">llvm::sampleprof::SampleProfileReader::getSamplesFor</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/guidtofuncnamemapper/#a0443cc3fdee8b10994d348458d6d9949">anonymous{SampleProfile.cpp}::GUIDToFuncNameMapper::GUIDToFuncNameMapper</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a16e99ef185f55c3e45caf11c880998ff">anonymous{SampleProfile.cpp}::SampleProfileLoader::promoteMergeNotInlinedContextSamples</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a358b28b8ab641a2a22ed8849a2dff2cf">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a25da45ec2b5b7dacb22e831cb7aef0c5">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnModule</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ad5c772a0b61cb29106af3a4f9ae43d59">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryPromoteAndInlineCandidate</a>.</p>

</div>
</div>

### getCanonicalFnName() {#a37b7e51dcb0e1efd0a84eb6398fd6301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sampleprof::FunctionSamples::getCanonicalFnName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Attr="selected")</td>
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



<p>Definition at line 1102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad20fb2a274b13a7820568739fbcba383">HasUniqSuffix</a>, <a href="#a8555584357a2929cd1746a5e23b95188">LLVMSuffix</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="#a4810779ce0c4abbfff59843113510764">PartSuffix</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a97d45ce069c1a09ca84672df63acf096">llvm::StringRef::rfind</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a> and <a href="#a2c9ea2741f8ae073da01be9dfcae147a">UniqSuffix</a>.</p>

</div>
</div>

### getOffset() {#ab6f00f222e6f6d30bc6a0fc7bf8396de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FunctionSamples::getOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DIL)</td>
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

<p>Returns the line offset to the start line of the subprogram.</p>


<p>We assume that a single function will not exceed 65535 LOC.</p>


<p>Declaration at line 1150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>Referenced by <a href="#aeea4c49a1040f9305f6a09d7d7815544">getCallSiteIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeightImpl</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-x86insertprefetch-cpp-/#a6bc620bb30e51cbda53a5936bc63064a">anonymous{X86InsertPrefetch.cpp}::getPrefetchHints</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### HasUniqSuffix {#ad20fb2a274b13a7820568739fbcba383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionSamples::HasUniqSuffix = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

<p>Whether the profile contains any ".__uniq." suffix in a name.</p>

<p>Definition at line 1200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#a37b7e51dcb0e1efd0a84eb6398fd6301">getCanonicalFnName</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>.</p>

</div>
</div>

### LLVMSuffix {#a8555584357a2929cd1746a5e23b95188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::sampleprof::FunctionSamples::LLVMSuffix = ".llvm."</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Name suffixes which canonicalization should handle to avoid profile mismatch.</p>

<p>Definition at line 1098 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#a37b7e51dcb0e1efd0a84eb6398fd6301">getCanonicalFnName</a>.</p>

</div>
</div>

### PartSuffix {#a4810779ce0c4abbfff59843113510764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::sampleprof::FunctionSamples::PartSuffix = ".part."</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#a37b7e51dcb0e1efd0a84eb6398fd6301">getCanonicalFnName</a>.</p>

</div>
</div>

### ProfileIsCS {#a67e19eb484a5eaa31b22894398e258c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionSamples::ProfileIsCS = false</td>
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



<p>Definition at line 1188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a0f9647d7bd1eb0c38198f05b3d34d4f3">anonymous{SampleProfile.cpp}::SampleProfileLoader::buildFunctionOrder</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#af64b545a1de5a343850725733d522546">anonymous{SampleProfile.cpp}::SampleProfileLoader::buildProfiledCallGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#aa77c45e5b6c316812092a7e8a1e30143">llvm::SampleProfileSummaryBuilder::computeSummaryForProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a61029509fbcbee90e8fc145701a79f07">llvm::sampleprof::SampleProfileWriter::create</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a219e9fac05a219d48a97e03304f84613">anonymous{SampleProfile.cpp}::SampleProfileLoader::findCalleeFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a2c88d6b3f033c87b7304db47133a930e">anonymous{SampleProfile.cpp}::SampleProfileLoader::findFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#abf8457f6ea82a821ee3fb08dae6246d9">anonymous{SampleProfile.cpp}::SampleProfileLoader::findIndirectCallFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="#af757985efc97179779ea3fc9e84f4735">getHeadSamplesEstimate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa583009e488330c099a4ab23e2536d2f">anonymous{SampleProfile.cpp}::SampleProfileLoader::getInstWeight</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ae0bf03df2431c543590180658ce4709d">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctionsWithPriority</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph/#ae5daf6edacb298caa44c8305b0b591a4">llvm::sampleprof::ProfiledCallGraph::ProfiledCallGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a358b28b8ab641a2a22ed8849a2dff2cf">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a25da45ec2b5b7dacb22e831cb7aef0c5">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofilematcher/#a5031837ecbfce3c5c2811da239ba777e">llvm::SampleProfileMatcher::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#adb1dafd461988f3d8e687eabb99e108d">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a96315b9b9bda521e4026e537c7d9f139">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a27bd438e566ec617ad7d33c562abae5c">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a3b40af607c43587edc28f8788e07cefd">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncOffsetTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a33203b3c9366fd57c4d7d30f1f4c83b3">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeOneSection</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### ProfileIsFS {#ac78db34e62da1555e9b84b5b5b1d907d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionSamples::ProfileIsFS = false</td>
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

<p>If this profile uses flow sensitive discriminators.</p>

<p>Definition at line 1203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#aa24141aebc0d8b15405be6bcb7b6319b">findFunctionSamples</a>, <a href="#aeea4c49a1040f9305f6a09d7d7815544">getCallSiteIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a5ad89ebfc9008ab04dbaf011e1f1e8db">llvm::sampleprof::SampleProfileReaderBinary::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a33203b3c9366fd57c4d7d30f1f4c83b3">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeOneSection</a>.</p>

</div>
</div>

### ProfileIsPreInlined {#a08b33b498078ac3694a992f4ab8a5761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionSamples::ProfileIsPreInlined = false</td>
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



<p>Definition at line 1190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a96315b9b9bda521e4026e537c7d9f139">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a27bd438e566ec617ad7d33c562abae5c">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a33203b3c9366fd57c4d7d30f1f4c83b3">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeOneSection</a>.</p>

</div>
</div>

### ProfileIsProbeBased {#aa37fe7429ffcf70c306c27a55d714d31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionSamples::ProfileIsProbeBased = false</td>
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



<p>Definition at line 1186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a61029509fbcbee90e8fc145701a79f07">llvm::sampleprof::SampleProfileWriter::create</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a6f70814abe4749ddb1e8356c3584b2ac">anonymous{SampleProfile.cpp}::SampleProfileLoader::emitAnnotations</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a2c88d6b3f033c87b7304db47133a930e">anonymous{SampleProfile.cpp}::SampleProfileLoader::findFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="#aeea4c49a1040f9305f6a09d7d7815544">getCallSiteIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa583009e488330c099a4ab23e2536d2f">anonymous{SampleProfile.cpp}::SampleProfileLoader::getInstWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a36557101a2fc2a308a4f6c5b51c6a739">llvm::MIRProfileLoader::getInstWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a4242a2c35893bbf85211387709d6a3d1">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#acdcff307bede233f8221f618d262b6df">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getProbeWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#abf1045cfa542c9bf01c10bcf99262a2c">anonymous{SampleProfile.cpp}::SampleProfileLoader::rejectHighStalenessProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a4582acc682e4769b7c2f57d38a153f8d">llvm::MIRProfileLoader::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a25da45ec2b5b7dacb22e831cb7aef0c5">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a96315b9b9bda521e4026e537c7d9f139">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a27bd438e566ec617ad7d33c562abae5c">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a33203b3c9366fd57c4d7d30f1f4c83b3">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeOneSection</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### UniqSuffix {#a2c9ea2741f8ae073da01be9dfcae147a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::sampleprof::FunctionSamples::UniqSuffix = ".__uniq."</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#a37b7e51dcb0e1efd0a84eb6398fd6301">getCanonicalFnName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3185cb2a23629ee9ed7ad67f719b60c">llvm::getUniqueInternalLinkagePostfix</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a01496927b6d3c4676bc9b45276fd4237">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeNameTableSection</a>.</p>

</div>
</div>

### UseMD5 {#afddaa81316d56f125de69793e0ddb33c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionSamples::UseMD5 = false</td>
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

<p>Whether the profile uses <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> to represent string.</p>

<p>Definition at line 1197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>, <a href="#a88645b85849eea5e18797a2abe34fe30">getFuncName</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a38619f3c2ad3874334865ce9543c03c6">llvm::SampleContextTracker::getFuncNameFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a012731cbc58856aff956543ab824eb8d">llvm::sampleprof::getRepInFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a3bdbf84fa8e3f0e789653587d5c85515">llvm::sampleprof::SampleProfileReader::read</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a358b28b8ab641a2a22ed8849a2dff2cf">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
