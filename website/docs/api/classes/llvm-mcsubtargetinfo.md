---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsubtargetinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCSubtargetInfo` Class Reference

<p>Generic base class for all target subtargets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCSubtargetInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> - Generic base class for all target subtargets. <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">HwModeType { <a href="#a552221db0b212c6317a281d5b1526ea1">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HwMode IDs are stored and accessed in a bit set format, enabling users to efficiently retrieve specific IDs, such as the <a href="/web-llvm/docs/api/structs/reginfo">RegInfo</a> HwMode <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, from the set as required. <a href="#a552221db0b212c6317a281d5b1526ea1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd6b8a57e9cc0d8ccf8e91a08937bbdf">MCSubtargetInfo</a> (const MCSubtargetInfo &amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c2da232cc1ad3f4633cb297c134e056">MCSubtargetInfo</a> (const Triple &amp;TT, StringRef CPU, StringRef TuneCPU, StringRef FS, ArrayRef&lt; StringRef &gt; PN, ArrayRef&lt; SubtargetFeatureKV &gt; PF, ArrayRef&lt; SubtargetSubTypeKV &gt; PD, const MCWriteProcResEntry *WPR, const MCWriteLatencyEntry *WL, const MCReadAdvanceEntry *RA, const InstrStage *IS, const unsigned *OC, const unsigned *FP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860e8cc7a236a7e1f0d04ecfdffeba35">MCSubtargetInfo</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a801deb3923c341f6cf240d9fbdc9cdc2">~MCSubtargetInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ece6d9a174fb7305138b8dd452d88f">operator=</a> (const MCSubtargetInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f7fb254f30336ddb9d13c8ce562fdc">operator=</a> (MCSubtargetInfo &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef6ef4ff039e873e9f66e21e3e55e26">getTargetTriple</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d5452528429597f223826cbc63ca867">getCPU</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ad1b628c02f5e23a256ea858ea75efe">getTuneCPU</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53afee158973a8af8c60263ddb5b2d07">getFeatureBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a163ce14824b63240eb1065b2ff583a8b">setFeatureBits</a> (const FeatureBitset &amp;FeatureBits_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149e626e2c29c99e669dc773c99e2b87">getFeatureString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ad14e9a81239b54fd64089b3290bfde">hasFeature</a> (unsigned Feature) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac717fb0e66df93c662f97cc56de7d1f3">setDefaultFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the features to the default for the given CPU and TuneCPU, with ano appended feature string. <a href="#ac717fb0e66df93c662f97cc56de7d1f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa1de0987d9c003e41c92f310c45746">ToggleFeature</a> (uint64_t FB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Toggle a feature and return the re-computed feature bits. <a href="#acaa1de0987d9c003e41c92f310c45746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f267aeb0a0e8878429f5bc98839b463">ToggleFeature</a> (const FeatureBitset &amp;FB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Toggle a feature and return the re-computed feature bits. <a href="#a4f267aeb0a0e8878429f5bc98839b463">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2624192c54a92722351fa791af3e862d">ToggleFeature</a> (StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Toggle a set of features and return the re-computed feature bits. <a href="#a2624192c54a92722351fa791af3e862d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a861526a1ea6a99e7e013f7be0998b89e">ApplyFeatureFlag</a> (StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a feature flag and return the re-computed feature bits, including all feature bits implied by the flag. <a href="#a861526a1ea6a99e7e013f7be0998b89e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930d94c27661f22a8f6959e3cab4ffda">SetFeatureBitsTransitively</a> (const FeatureBitset &amp;FB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set/clear additional feature bits, including all other bits they imply. <a href="#a930d94c27661f22a8f6959e3cab4ffda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4b8dd4ace194f4d2fd90bc1c7cc9e61">ClearFeatureBitsTransitively</a> (const FeatureBitset &amp;FB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f9740fb6022c141b98c6b1af02d29b">checkFeatures</a> (StringRef FS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the subtarget features are enabled/disabled as per the provided string, ignoring all other features. <a href="#a02f9740fb6022c141b98c6b1af02d29b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eddfb1a986d95b7f9e8e0988f72960c">getSchedModelForCPU</a> (StringRef CPU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the machine model of a CPU. <a href="#a2eddfb1a986d95b7f9e8e0988f72960c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af907ecc18c1f4f0bce8a9e2eb449ffb8">getSchedModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the machine model for this subtarget's CPU. <a href="#af907ecc18c1f4f0bce8a9e2eb449ffb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwriteprocresentry">MCWriteProcResEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af31aa7690c77c36f2ffeb083b9917804">getWriteProcResBegin</a> (const MCSchedClassDesc *SC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator at the first process resource consumed by the given scheduling class. <a href="#af31aa7690c77c36f2ffeb083b9917804">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwriteprocresentry">MCWriteProcResEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08d8cf817aece246e6f804227cfbea77">getWriteProcResEnd</a> (const MCSchedClassDesc *SC) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwritelatencyentry">MCWriteLatencyEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36abba0bcbba153c7227e631eae79e7a">getWriteLatencyEntry</a> (const MCSchedClassDesc *SC, unsigned DefIdx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1060a7c37903fcc791a20d9d0c994c25">getReadAdvanceCycles</a> (const MCSchedClassDesc *SC, unsigned UseIdx, unsigned WriteResID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcreadadvanceentry">MCReadAdvanceEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc4de7e248068de6a6ab576fcb60f9d">getReadAdvanceEntries</a> (const MCSchedClassDesc &amp;SC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the set of ReadAdvance entries declared by the scheduling class descriptor in input. <a href="#a2dc4de7e248068de6a6ab576fcb60f9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1512f856548a309c48c6dc944d7db7e">getInstrItineraryForCPU</a> (StringRef CPU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get scheduling itinerary of a CPU. <a href="#ab1512f856548a309c48c6dc944d7db7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1487bf00f68f02583117ffa23d79619">initInstrItins</a> (InstrItineraryData &amp;InstrItins) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize an <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> instance. <a href="#af1487bf00f68f02583117ffa23d79619">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18de37f60c9c80f7974dbf8dfd3795cb">resolveVariantSchedClass</a> (unsigned SchedClass, const MCInst *MI, const MCInstrInfo *MCII, unsigned CPUID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve a variant scheduling class for the given <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> and CPU. <a href="#a18de37f60c9c80f7974dbf8dfd3795cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86f7785b0fcd57aa9ed81c8d897002e">isCPUStringValid</a> (StringRef CPU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the CPU string is valid. <a href="#ad86f7785b0fcd57aa9ed81c8d897002e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetsubtypekv">SubtargetSubTypeKV</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283d4d49744945ebc79f88352ef9c811">getAllProcessorDescriptions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return processor descriptions. <a href="#a283d4d49744945ebc79f88352ef9c811">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e3e638e179b49526e659a066fba0fb0">getAllProcessorFeatures</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return processor features. <a href="#a7e3e638e179b49526e659a066fba0fb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84cc57953f28b29bcd9b95b41d71a58c">getEnabledProcessorFeatures</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the list of processor features currently enabled. <a href="#a84cc57953f28b29bcd9b95b41d71a58c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73542c91c4170de87ad812a3c25252b">getHwModeSet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a bit set containing all HwMode IDs of the current subtarget. <a href="#ae73542c91c4170de87ad812a3c25252b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38282a3546378eaf36746259f78421f">getHwMode</a> (enum HwModeType type=HwMode_Default) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HwMode <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> corresponding to the 'type' parameter is retrieved from the HwMode bit set of the current subtarget. <a href="#af38282a3546378eaf36746259f78421f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0c62ec60a1df0ee43e1842e9c18f02">getCacheSize</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cache size in bytes for the given level of cache. <a href="#a1c0c62ec60a1df0ee43e1842e9c18f02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c7ae17909b79cc88dddd82d994e0819">getCacheAssociativity</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cache associatvity for the given level of cache. <a href="#a8c7ae17909b79cc88dddd82d994e0819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4be4ef1a969f0da1aa2da9aa5ccfe45">getCacheLineSize</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the target cache line size in bytes at a given level. <a href="#ac4be4ef1a969f0da1aa2da9aa5ccfe45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01d1119c1464deb554803c0d3a09ea2a">getCacheLineSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the target cache line size in bytes. <a href="#a01d1119c1464deb554803c0d3a09ea2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813b24d9dee648c2fed114b976db4582">getPrefetchDistance</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the preferred prefetch distance in terms of instructions. <a href="#a813b24d9dee648c2fed114b976db4582">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a771ba0e5f12fe44544c500f928850c3d">getMaxPrefetchIterationsAhead</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum prefetch distance in terms of loop iterations. <a href="#a771ba0e5f12fe44544c500f928850c3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0cea4a91c550f7e27236adf3f0f301">enableWritePrefetching</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63122a093c3c10835985d504062c4554">getMinPrefetchStride</a> (unsigned NumMemAccesses, unsigned NumStridedMemAccesses, unsigned NumPrefetches, bool HasCall) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimum stride necessary to trigger software prefetching. <a href="#a63122a093c3c10835985d504062c4554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a273eb79f44bfd3f16a87fa75003517fa">shouldPrefetchAddressSpace</a> (unsigned AS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea593fdfefa11ea2aa7ed07d9df6155">InitMCProcessorInfo</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the scheduling model and feature bits. <a href="#adea593fdfefa11ea2aa7ed07d9df6155">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab69a53ae01aa26a89807f2c4f6bfca54">TargetTriple</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6363980fb6547e299e5485aeb092f706">CPU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb27e0727627d3e942b253ecd136de4">TuneCPU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7118621c50bb55b5e242dffd677b0bd">ProcNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3bd2c64941c9ebbc335a3ee500fdf7">ProcFeatures</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetsubtypekv">SubtargetSubTypeKV</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c12777e9fe49103d0955e9224eda7c">ProcDesc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwriteprocresentry">MCWriteProcResEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e38f7005146c7200047576966b6ba1d">WriteProcResTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwritelatencyentry">MCWriteLatencyEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89fa708ac2fd4ebd5120527020183bb4">WriteLatencyTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcreadadvanceentry">MCReadAdvanceEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace0c1d26a71ad0e5cad7b712a432b95e">ReadAdvanceTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28370d04e76df3d597f9d7d7d1d1a815">CPUSchedModel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrstage">InstrStage</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9888377eec6c632750215fafef01de0">Stages</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6944a8b17a19321266590e3a7c592c52">OperandCycles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6ecbfa44815ecac602c4464b8c89b7">ForwardingPaths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05bd3d313328463e8a6b38572c670af7">FeatureBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa844e3492964a73c3f1a8d9a5694f807">FeatureString</a></td>
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

## Description {#details}

<p>Generic base class for all target subtargets.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### HwModeType {#a552221db0b212c6317a281d5b1526ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSubtargetInfo::HwModeType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HwMode IDs are stored and accessed in a bit set format, enabling users to efficiently retrieve specific IDs, such as the <a href="/web-llvm/docs/api/structs/reginfo">RegInfo</a> HwMode <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, from the set as required.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HwMode_Default<a id="a552221db0b212c6317a281d5b1526ea1a5b453e307ff47174c056732c7ec30f13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HwMode_ValueType<a id="a552221db0b212c6317a281d5b1526ea1a68071036fce39ffb8575399199660c02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HwMode_RegInfo<a id="a552221db0b212c6317a281d5b1526ea1a764f5038bd82e3a7058768002532e596"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HwMode_EncodingInfo<a id="a552221db0b212c6317a281d5b1526ea1a910a78a6661e7f860a0a44fa232feecf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>Using this approach, various types of HwMode IDs can be added to a subtarget to manage different attributes within that subtarget, significantly enhancing the scalability and usability of HwMode. Moreover, to ensure compatibility, this method also supports controlling multiple attributes with a single HwMode <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, just as was done previously.</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCSubtargetInfo() {#acd6b8a57e9cc0d8ccf8e91a08937bbdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSubtargetInfo::MCSubtargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="#acd6b8a57e9cc0d8ccf8e91a08937bbdf">MCSubtargetInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>


<p>Referenced by <a href="#acd6b8a57e9cc0d8ccf8e91a08937bbdf">MCSubtargetInfo</a>, <a href="#a42ece6d9a174fb7305138b8dd452d88f">operator=</a>, <a href="#a45f7fb254f30336ddb9d13c8ce562fdc">operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a7850b7517ef8d967cbda198d068f2c0e">llvm::TargetSubtargetInfo::TargetSubtargetInfo</a>.</p>

</div>
</div>

### MCSubtargetInfo() {#a0c2da232cc1ad3f4633cb297c134e056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo::MCSubtargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; PN, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt; PF, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetsubtypekv">SubtargetSubTypeKV</a> &gt; PD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwriteprocresentry">MCWriteProcResEntry</a> * WPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwritelatencyentry">MCWriteLatencyEntry</a> * WL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcreadadvanceentry">MCReadAdvanceEntry</a> * RA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrstage">InstrStage</a> * IS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned * OC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned * FP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="#adea593fdfefa11ea2aa7ed07d9df6155">InitMCProcessorInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>

</div>
</div>

### MCSubtargetInfo() {#a860e8cc7a236a7e1f0d04ecfdffeba35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSubtargetInfo::MCSubtargetInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCSubtargetInfo() {#a801deb3923c341f6cf240d9fbdc9cdc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::MCSubtargetInfo::~MCSubtargetInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a42ece6d9a174fb7305138b8dd452d88f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo &amp; llvm::MCSubtargetInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Reference <a href="#acd6b8a57e9cc0d8ccf8e91a08937bbdf">MCSubtargetInfo</a>.</p>

</div>
</div>

### operator=() {#a45f7fb254f30336ddb9d13c8ce562fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo &amp; llvm::MCSubtargetInfo::operator= (<a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Reference <a href="#acd6b8a57e9cc0d8ccf8e91a08937bbdf">MCSubtargetInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### ApplyFeatureFlag() {#a861526a1ea6a99e7e013f7be0998b89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset MCSubtargetInfo::ApplyFeatureFlag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply a feature flag and return the re-computed feature bits, including all feature bits implied by the flag.</p>

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="#a861526a1ea6a99e7e013f7be0998b89e">ApplyFeatureFlag</a>.</p>


<p>Referenced by <a href="#a861526a1ea6a99e7e013f7be0998b89e">ApplyFeatureFlag</a> and <a href="#a02f9740fb6022c141b98c6b1af02d29b">checkFeatures</a>.</p>

</div>
</div>

### checkFeatures() {#a02f9740fb6022c141b98c6b1af02d29b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCSubtargetInfo::checkFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the subtarget features are enabled/disabled as per the provided string, ignoring all other features.</p>

<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27ab1c94ca2fbc3e78fc30069c8d0f01680">llvm::All</a>, <a href="#a861526a1ea6a99e7e013f7be0998b89e">ApplyFeatureFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### ClearFeatureBitsTransitively() {#af4b8dd4ace194f4d2fd90bc1c7cc9e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset MCSubtargetInfo::ClearFeatureBitsTransitively (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; FB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#ad95f670b9a1cbb21ad61a831fa26a2ce">ClearImpliedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#aec33832bdf233909649a8632be33aa0c">llvm::FeatureBitset::size</a>.</p>

</div>
</div>

### enableWritePrefetching() {#a6b0cea4a91c550f7e27236adf3f0f301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCSubtargetInfo::enableWritePrefetching ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if prefetching should also be done for writes.</p></dd>
</dl>


<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>

</div>
</div>

### getAllProcessorDescriptions() {#a283d4d49744945ebc79f88352ef9c811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SubtargetSubTypeKV &gt; llvm::MCSubtargetInfo::getAllProcessorDescriptions ()</td>
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

<p>Return processor descriptions.</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### getAllProcessorFeatures() {#a7e3e638e179b49526e659a066fba0fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SubtargetFeatureKV &gt; llvm::MCSubtargetInfo::getAllProcessorFeatures ()</td>
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

<p>Return processor features.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### getCacheAssociativity() {#a8c7ae17909b79cc88dddd82d994e0819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; MCSubtargetInfo::getCacheAssociativity (unsigned Level)</td>
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

<p>Return the cache associatvity for the given level of cache.</p>


<p>Level is zero-based, so a value of zero means the first level of cache.</p>


<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>

</div>
</div>

### getCacheLineSize() {#ac4be4ef1a969f0da1aa2da9aa5ccfe45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; MCSubtargetInfo::getCacheLineSize (unsigned Level)</td>
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

<p>Return the target cache line size in bytes at a given level.</p>

<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>

</div>
</div>

### getCacheLineSize() {#a01d1119c1464deb554803c0d3a09ea2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::MCSubtargetInfo::getCacheLineSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the target cache line size in bytes.</p>


<p>By default, return the line size for the bottom-most level of cache. This provides a more convenient interface for the common case where all cache levels have the same line size. Return zero if there is no cache model.</p>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>References <a href="#a01d1119c1464deb554803c0d3a09ea2a">getCacheLineSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a01d1119c1464deb554803c0d3a09ea2a">getCacheLineSize</a>.</p>

</div>
</div>

### getCacheSize() {#a1c0c62ec60a1df0ee43e1842e9c18f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; MCSubtargetInfo::getCacheSize (unsigned Level)</td>
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

<p>Return the cache size in bytes for the given level of cache.</p>


<p>Level is zero-based, so a value of zero means the first level of cache.</p>


<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>

</div>
</div>

### getCPU() {#a5d5452528429597f223826cbc63ca867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSubtargetInfo::getCPU ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#ab3006e90ba5c4717808c3c35e1a778a5">llvm::Hexagon_MC::addArchSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac4e5dcb952f0c76bcbb366a37077ecce">llvm::MCSchedModel::computeInstrLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72eaee9433568ed277e40ed923f7bb50">llvm::createHexagonAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af07717de265cdc07e01ca26be29c1a60">llvm::createMipsAsmBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#abf468fdf1fecb6e06d29a8cbfaa808bb">llvm::AMDGPUTargetAsmStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a17b7b6be8c77b055cf79259a4af7ff0c">llvm::ARMTargetStreamer::emitTargetAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a7baaa91927748c04ac388e82788a973d">llvm::AMDGPU::IsaInfo::getAddressableNumSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp/#aaf6e4a38fe1be7aab9c4e702d9dbb396">getArchForCPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#a42d7fe1ef88cc2906006661704af630f">llvm::Hexagon_MC::getArchSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#ae427ea6c3fad2449f851240892963b14">llvm::AMDGPU::MCKernelDescriptor::getDefaultAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#a14ab5a27df8fdb9f291f2545ffb610a3">llvm::Hexagon_MC::GetELFFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a98803f3d3a9a7e50ad0f40bdf8cd8190">llvm::AMDGPU::IsaInfo::getMaxNumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a8712096d79b8b76954f261f06351c34f">llvm::AMDGPU::IsaInfo::getMinNumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a329c56090fef55473ff6ae5bc6e8d9b8">llvm::AMDGPU::getNSAMaxSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a4f0de0c1180aa2d8965d9cdddfde84a5">llvm::AMDGPU::IsaInfo::getNumExtraSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#aa82573eec93913f61c5fe97062d60c7e">llvm::AMDGPU::IsaInfo::getSGPRAllocGranule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#afeb7e0bccf88c9d23d02454609eb431a">llvm::AMDGPU::IsaInfo::getTotalNumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a09ddc9ac2f9a0ce92be5565eff4f3869">llvm::HexagonMCInstrInfo::isOrderedDuplexPair</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#acba21cba8f1d8a8cfccb2ac4f51f3bfd">llvm::AMDGPUInstPrinter::printSWaitCnt</a>.</p>

</div>
</div>

### getEnabledProcessorFeatures() {#a84cc57953f28b29bcd9b95b41d71a58c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; SubtargetFeatureKV &gt; MCSubtargetInfo::getEnabledProcessorFeatures ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the list of processor features currently enabled.</p>

<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a4d13fd05401d8eb0c97b9864a0eb6028">llvm::copy_if</a>.</p>

</div>
</div>

### getFeatureBits() {#a53afee158973a8af8c60263ddb5b2d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FeatureBitset &amp; llvm::MCSubtargetInfo::getFeatureBits ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrelfstreamer/#a680bdc9c72ca2dfa148f8b0092a75337">llvm::AVRELFStreamer::AVRELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a05c04a32ecd794f1e86cfb753ed1f5c2">cannotInsertTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetelfstreamer/#abf82dd0f77b8b6f952a76e02acc74c64">llvm::CSKYTargetELFStreamer::CSKYTargetELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a18e42ac75374f92b3e9f5f14f755b180">DecodeGPRPairRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ae96b7f8b4b8e35d28617a90604289b0b">DecodeHINTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4ee0d80338b8a6c928f2322e35a21c37">DecodeSETPANInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a7b91a2080aef66711a9a59c0fc2bc78c">DecodeSystemPStateImm0_15Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a47610006b53563d90c891dbb2f2a21cf">DecodeSystemPStateImm0_1Instruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetstreamer/#a5054529ea7e565e73dfc1d396dc50303">llvm::HexagonTargetStreamer::emitTargetAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetstreamer/#a762f3b75bc1c039e73a809ddabc26065">llvm::RISCVTargetStreamer::emitTargetAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#abb7cbfc91aec970d7d9b935b81f8db66">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandFunctionCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a6f199c1f3d13e403d252d9b028b4c7a0">llvm::AMDGPU::IsaInfo::getAddressableLocalMemorySize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a7baaa91927748c04ac388e82788a973d">llvm::AMDGPU::IsaInfo::getAddressableNumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a842a99d2928e264423f0ac73b0910ec9">llvm::AMDGPU::IsaInfo::getAddressableNumVGPRs</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#ae427ea6c3fad2449f851240892963b14">llvm::AMDGPU::MCKernelDescriptor::getDefaultAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a7c570149fbd98b77ba4944f29216a6ec">llvm::MCInstrInfo::getDeprecatedInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a705a7512f5b23ec9b3bb19f032040285">llvm::AMDGPU::IsaInfo::getEUsPerCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a6a404dcfcc397b46c1658356bbae054f">llvm::AMDGPU::IsaInfo::getLocalMemorySize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a98803f3d3a9a7e50ad0f40bdf8cd8190">llvm::AMDGPU::IsaInfo::getMaxNumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a2d0c61cd3e4d53626ffdb34031766f08">llvm::AMDGPU::IsaInfo::getMaxWorkGroupsPerCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a8712096d79b8b76954f261f06351c34f">llvm::AMDGPU::IsaInfo::getMinNumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#aae419e2ff2e3882dd0d8e99c97add6b1">llvm::AMDGPU::IsaInfo::getNumExtraSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a4f0de0c1180aa2d8965d9cdddfde84a5">llvm::AMDGPU::IsaInfo::getNumExtraSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a14accda22ecd133d48fa434165e690a0">llvm::AMDGPU::IsaInfo::getTotalNumVGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ae47a2723f63ec4e85b4228b56e5d759c">llvm::AMDGPU::IsaInfo::getVGPRAllocGranule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a00ddec6f625f5fdc41b2ee64b272b5b9">llvm::AMDGPU::IsaInfo::getVGPREncodingGranule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a20f21352639512a028b2297e3cba9094">llvm::AMDGPU::IsaInfo::getWavefrontSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa0721d3bbb1b2d35497921b9600c4b6d">llvm::ARM::isCDECoproc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7b0ac753cc89fce435513a67b4014bd8">llvm::AMDGPU::isGFX12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64instprinter-cpp/#a999c6cf9cdcc9f0e69e737ab3e280e25">isValidSysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetelfstreamer/#aedd14021422c2f6fba707ef8188d6d28">llvm::LoongArchTargetELFStreamer::LoongArchTargetELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp/#aad70fb95e1855cf69dfefcf98e2d5e8b">matchAliasCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a321c1863f0f95dd6d0908504f4bc4b2b">llvm::RISCVInstPrinter::printCSRSystemRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ab13eadce6a8a7cf7700d772fa45852a8">llvm::ARMInstPrinter::printMSRMaskOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a1574059a04c27b4f6566b7d4054afc33">llvm::AArch64InstPrinter::printPrefetchOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a4ef893dbd3ef72a8e049fe401fcb39e5">llvm::AArch64InstPrinter::printSysAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a9e514c9fdf6eaec2a8f8baf8a8dce29b">llvm::AArch64InstPrinter::printSyspAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a2cdc4ea363a73fc772d36d9fb5911adb">llvm::AArch64InstPrinter::printSystemPStateField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ac5fca0a3b40921b5bedfa3303b5158f3">llvm::HexagonMCInstrInfo::requiresSlot</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#a9c657032eafd38a8fa07606efe9af3a7">llvm::RISCVTargetELFStreamer::RISCVTargetELFStreamer</a>.</p>

</div>
</div>

### getFeatureString() {#a149e626e2c29c99e669dc773c99e2b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSubtargetInfo::getFeatureString ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### getHwMode() {#af38282a3546378eaf36746259f78421f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::MCSubtargetInfo::getHwMode (enum <a href="#a552221db0b212c6317a281d5b1526ea1">HwModeType</a> type=<a href="#a552221db0b212c6317a281d5b1526ea1a5b453e307ff47174c056732c7ec30f13">HwMode_Default</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HwMode <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> corresponding to the 'type' parameter is retrieved from the HwMode bit set of the current subtarget.</p>


<p>It’s important to note that if the current subtarget possesses two HwMode IDs and both control a single attribute (such as <a href="/web-llvm/docs/api/structs/reginfo">RegInfo</a>), this interface will result in an error.</p>


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Reference <a href="#a552221db0b212c6317a281d5b1526ea1a5b453e307ff47174c056732c7ec30f13">HwMode_Default</a>.</p>

</div>
</div>

### getHwModeSet() {#ae73542c91c4170de87ad812a3c25252b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::MCSubtargetInfo::getHwModeSet ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a bit set containing all HwMode IDs of the current subtarget.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### getInstrItineraryForCPU() {#ab1512f856548a309c48c6dc944d7db7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrItineraryData MCSubtargetInfo::getInstrItineraryForCPU (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get scheduling itinerary of a CPU.</p>

<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="#a2eddfb1a986d95b7f9e8e0988f72960c">getSchedModelForCPU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac4e5dcb952f0c76bcbb366a37077ecce">llvm::MCSchedModel::computeInstrLatency</a>.</p>

</div>
</div>

### getMaxPrefetchIterationsAhead() {#a771ba0e5f12fe44544c500f928850c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCSubtargetInfo::getMaxPrefetchIterationsAhead ()</td>
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

<p>Return the maximum prefetch distance in terms of loop iterations.</p>

<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>

</div>
</div>

### getMinPrefetchStride() {#a63122a093c3c10835985d504062c4554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCSubtargetInfo::getMinPrefetchStride (unsigned NumMemAccesses, unsigned NumStridedMemAccesses, unsigned NumPrefetches, bool HasCall)</td>
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

<p>Return the minimum stride necessary to trigger software prefetching.</p>

<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>

</div>
</div>

### getPrefetchDistance() {#a813b24d9dee648c2fed114b976db4582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCSubtargetInfo::getPrefetchDistance ()</td>
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

<p>Return the preferred prefetch distance in terms of instructions.</p>

<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>

</div>
</div>

### getReadAdvanceCycles() {#a1060a7c37903fcc791a20d9d0c994c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MCSubtargetInfo::getReadAdvanceCycles (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC, unsigned UseIdx, unsigned WriteResID)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#aa27ad78489e8c685d427e45e6c4bc14d">llvm::mca::RegisterFile::addRegisterRead</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a6f9761f8807ef5c507cadfd2e1e99cd9">llvm::mca::RegisterFile::checkRAWHazards</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>.</p>

</div>
</div>

### getReadAdvanceEntries() {#a2dc4de7e248068de6a6ab576fcb60f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCReadAdvanceEntry &gt; llvm::MCSubtargetInfo::getReadAdvanceEntries (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> &amp; SC)</td>
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

<p>Return the set of ReadAdvance entries declared by the scheduling class descriptor in input.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### getSchedModel() {#af907ecc18c1f4f0bce8a9e2eb449ffb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedModel &amp; llvm::MCSubtargetInfo::getSchedModel ()</td>
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

<p>Get the machine model for this subtarget's CPU.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#aa27ad78489e8c685d427e45e6c4bc14d">llvm::mca::RegisterFile::addRegisterRead</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a6f9761f8807ef5c507cadfd2e1e99cd9">llvm::mca::RegisterFile::checkRAWHazards</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/dispatchstage/#ad86d7a96f763205596d8770f8ebf5d6e">llvm::mca::DispatchStage::DispatchStage</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a98f815de250b90a65a5f83503fc7b288">emitComments</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#ad7331753737602bb545def2c960c209d">emitLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ad8d442c18b35ab8bc3468c1e9de23791">llvm::TargetSubtargetInfo::enablePostRAScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a2913834d48cd087ac10ba131aae887a4">llvm::HexagonMCInstrInfo::getCVIResources</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ab488aa3ae070d9de98e958be991ea9cc">llvm::HexagonMCInstrInfo::getOtherReservedSlots</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ae119a8f604442c5d6b0abb586d6aa03e">llvm::MCSchedModel::getReciprocalThroughput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a9211aa0b9d52257601df75d2818dab7c">llvm::HexagonMCInstrInfo::getUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#ab357b39c47df52a19882a831feda1b6f">llvm::TargetSchedModel::init</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>, <a href="#af1487bf00f68f02583117ffa23d79619">initInstrItins</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifconverter/#a0275a0186010a2c4472194dc40f10f01">anonymous{EarlyIfConversion.cpp}::EarlyIfConverter::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/aarch64conditionalcompares/#af7b7982c58340c2b9b066e30a4fd558f">anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::runOnMachineFunction</a>.</p>

</div>
</div>

### getSchedModelForCPU() {#a2eddfb1a986d95b7f9e8e0988f72960c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedModel &amp; MCSubtargetInfo::getSchedModelForCPU (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the machine model of a CPU.</p>

<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a090d8f8a40ae8bd7f4ac776d186d0203">llvm::MCSchedModel::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a08e140d603b53c440c54cffc85131c8f">Find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a> and <a href="/web-llvm/docs/api/structs/llvm/subtargetsubtypekv/#a0a93c69eb1278bc8e0c651abc768d526">llvm::SubtargetSubTypeKV::SchedModel</a>.</p>


<p>Referenced by <a href="#ab1512f856548a309c48c6dc944d7db7e">getInstrItineraryForCPU</a> and <a href="#adea593fdfefa11ea2aa7ed07d9df6155">InitMCProcessorInfo</a>.</p>

</div>
</div>

### getTargetTriple() {#a1ef6ef4ff039e873e9f66e21e3e55e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::MCSubtargetInfo::getTargetTriple ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#ab3006e90ba5c4717808c3c35e1a778a5">llvm::Hexagon_MC::addArchSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acd2d48bd67d42ac499c2b0acdef4c2c3">llvm::ARMAsmBackend::adjustFixupValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad838b75c8aa824335f1f1642d5d78545">llvm::createAArch64beAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a676b531bfbeddd2a9614c12d21ad4c88">llvm::createAArch64leAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2532a17ecee4a1e1ad34b08fbebee2c">llvm::createAArch64ObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2362f0ccdeb00d23623925b59b639c26">llvm::createAMDGPUAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#a8f6ab6658167369fdde830fd3c8d287c">createARMAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfabe5238580347c762326c1305bec32">llvm::createARMObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a78886ce504500cae8267474f087e61ef">createAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acdca173360fb2277a90f6e69685ce295">llvm::createAVRAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a44fbe4055845a7c4dcb097c1502a1787">createCSKYObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72eaee9433568ed277e40ed923f7bb50">llvm::createHexagonAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74ddabf619ec8214e788b4259c7e419e">llvm::createLanaiAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6fcb1c02cdb9586108ab2f9100a56ec9">llvm::createLoongArchAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a281fbab0216589c202c46b283aaca393">createLoongArchObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a691c09716f1274d5e4c4b8f35393f2da">llvm::createM68kAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af07717de265cdc07e01ca26be29c1a60">llvm::createMipsAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a278fb00410ab9c2f73d3578f7b4490ff">createMipsObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a328d980049816fab8524f04b1779a2bc">llvm::createMSP430ObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a9d80fcf3535aa6bff5b91e9630b3bcdd">createObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45ec52ed08b28acb5bc5295d3ca56d17">llvm::createPPCAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaad4014f90f33f9d7d02fa9ceec91467">llvm::createRISCVAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a99d87347a806a5998538498ac7b015df">createRISCVObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9f09be1a3af90f08040057a4a330a73">llvm::createSparcAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e2f30307ffe41c5d4e80899ee135826">llvm::createSystemZMCAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b0f671e47ceee3b9db1be426a79e779">llvm::createVEAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae35ef2e57b2c31572d967cb78484ffaa">llvm::createX86_32AsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a306674e8951ad0f9c77cda2f70219ab9">llvm::createX86_64AsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a156c0ad16b9a22a06c6502f59f207f2a">llvm::createX86ObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af32e200fafb3ce3f4a7ed1546ab34219">llvm::createXtensaMCAsmBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa4e7f162a6130db44eb584e71f19ae67">llvm::AMDGPUAsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a339bb20fead6005cd1cc37f479650617">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcasminfo/#a081e0d017dbcb21393b0e55d70d4550c">llvm::AMDGPUMCAsmInfo::getMaxInstLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a2d0c61cd3e4d53626ffdb34031766f08">llvm::AMDGPU::IsaInfo::getMaxWorkGroupsPerCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a12457438c2b018b673e22e0253e466c4">llvm::AMDGPU::getMCReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a7759c46e30fcf1d9af690f2788cac998">llvm::PPCMCCodeEmitter::getTLSRegEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3d357ec8432b58835aaa34defcc4eff9">llvm::AMDGPU::isHsaAbi</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#abe5c0fa37d55abab3787bc0a4100cab4">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::isTargetMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetelfstreamer/#aedd14021422c2f6fba707ef8188d6d28">llvm::LoongArchTargetELFStreamer::LoongArchTargetELFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a8d6169e2e4a0e60c74e95dab53907e2f">lowerMSASplatZExt</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#a96cded7294d54537fbb8eb5a6148448a">anonymous{MipsAsmParser.cpp}::MipsAsmParser::MipsAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#a9c657032eafd38a8fa07606efe9af3a7">llvm::RISCVTargetELFStreamer::RISCVTargetELFStreamer</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a601c710d4a4ed9a073bd55ea552d5645">truncateVecElts</a>.</p>

</div>
</div>

### getTuneCPU() {#a9ad1b628c02f5e23a256ea858ea75efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSubtargetInfo::getTuneCPU ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### getWriteLatencyEntry() {#a36abba0bcbba153c7227e631eae79e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCWriteLatencyEntry * llvm::MCSubtargetInfo::getWriteLatencyEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC, unsigned DefIdx)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a87b307b08bc0acbbf95fab6bca87983c">llvm::MCSchedModel::computeInstrLatency</a>.</p>

</div>
</div>

### getWriteProcResBegin() {#af31aa7690c77c36f2ffeb083b9917804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCWriteProcResEntry * llvm::MCSubtargetInfo::getWriteProcResBegin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC)</td>
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

<p>Return an iterator at the first process resource consumed by the given scheduling class.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ae119a8f604442c5d6b0abb586d6aa03e">llvm::MCSchedModel::getReciprocalThroughput</a>, <a href="#a08d8cf817aece246e6f804227cfbea77">getWriteProcResEnd</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>.</p>

</div>
</div>

### getWriteProcResEnd() {#a08d8cf817aece246e6f804227cfbea77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCWriteProcResEntry * llvm::MCSubtargetInfo::getWriteProcResEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Reference <a href="#af31aa7690c77c36f2ffeb083b9917804">getWriteProcResBegin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ae119a8f604442c5d6b0abb586d6aa03e">llvm::MCSchedModel::getReciprocalThroughput</a>.</p>

</div>
</div>

### hasFeature() {#a0ad14e9a81239b54fd64089b3290bfde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSubtargetInfo::hasFeature (unsigned Feature)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acd2d48bd67d42ac499c2b0acdef4c2c3">llvm::ARMAsmBackend::adjustFixupValue</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#ad6888126cb2adb886258b17447e5a205">adjust::adjustRelativeBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmcinstrinfo-cpp-/#abda7c7a2d206ce064b97412b007ea5af">anonymous{HexagonMCInstrInfo.cpp}::canonicalizePacketImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ae64b1825b82ce592840287c8ebad2d2a">checkFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a499b9606a8f1365f4515e3cce4f14474">clearFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#a54ce870f13edcb1e43823a997d5ddaf7">createAMDGPUMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#adf4c8c30d4ab86250b70367ddd123ae7">decodeFPUV3Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a52685adb34dcf188c60c2ba51d525985">DecodeGPRF16RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#ac1ab8132c146da3c4dba810064ac142a">DecodeGPRF32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#aedf05d82c0c624910fd446082c570568">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a1c3fc03976ed07efe25c98fabf3413a2">decodeUImmLog2XLenOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada43bee484c2300200c9ab0884003563">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitDirectiveOptionArch</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada96d67c594bff6ca1c65fb281f82ca5">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a17b7b6be8c77b055cf79259a4af7ff0c">llvm::ARMTargetStreamer::emitTargetAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetstreamer/#a762f3b75bc1c039e73a809ddabc26065">llvm::RISCVTargetStreamer::emitTargetAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumccodeemitter-cpp-/amdgpumccodeemitter/#a57c601613d1b256c59417e392d0575bf">anonymous{AMDGPUMCCodeEmitter.cpp}::AMDGPUMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600mccodeemitter-cpp-/r600mccodeemitter/#ab11d9390008179d60f46f29f7781183c">anonymous{R600MCCodeEmitter.cpp}::R600MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a326c8dcef7365124098e7573ebe4bd31">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmctargetdesc-cpp-/armmcinstranalysis/#a49422093293e285d52290f1491a42f33">anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::evaluateMemoryOperandAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#ac6740cbf8bbdd52574f85db63500cd25">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#afa2b2e58e0859c0608b6f10a8ad1c79f">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a4a7ca70410938579ebcd69725c1abab0">llvm::CSKYMCCodeEmitter::expandJBTF</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#aa9f55bb589105b8751fa61098690db0b">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandLongCondBr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a163e06959afb15ae88efade9bb975e27">llvm::RISCVMatInt::generateInstSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmatint-cpp/#ad73c63728a69d031ddfe0cf467072ad0">generateInstSeqImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmatint-cpp/#ab9f36d4e7420ac603ea578f39ab9aeea">generateInstSeqLeadingZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a6eff34ee491c7f6124b3f21768d8d79f">llvm::RISCVMatInt::generateTwoRegInstSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp/#aaf6e4a38fe1be7aab9c4e702d9dbb396">getArchForCPU</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a0d1a03784a748be72ac0447bf24aef7a">getARMLoadDeprecationInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a0c8fda450af15c6221ae4f6ef5f6ff24">getARMStoreDeprecationInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-cpp/#ad1056bb7dab91f46fde103c031ba994d">getEFlagsForFeatureSet</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a496a589a4ca89aafae1db05782b62cde">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::getExprOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#a847e5bb4507e49e9af8582df2cb12f50">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::getImmOpValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a392b6c8a7962feed988bf14017205f4b">llvm::RISCVMatInt::getIntMatCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumccodeemitter-cpp/#aa3aaa3d73b67acb971ad52364f8c0379">getLit16Encoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumccodeemitter-cpp/#af8b95b71f162123cc281696dcabdb9ee">getLit32Encoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumccodeemitter-cpp/#a55d672e564e81cbe3051b51fd5686967">getLit64Encoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a2d298529e6e847055ce47f80d60576d1">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcasminfo/#a081e0d017dbcb21393b0e55d70d4550c">llvm::AMDGPUMCAsmInfo::getMaxInstLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a7d9b81caded54a832c1ea707e1c189af">getMCRDeprecationInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#acd2a2ba2a82e6388c9b7e00e38c7b24f">getMRCDeprecationInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#ab9ee4cfb1ef279fef4911d050f67ec1e">llvm::ARMAsmBackend::getRelaxedOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcobjectfileinfo/#a57dd15b4815c60952a0ff2831512fe4c">llvm::RISCVMCObjectFileInfo::getTextSectionAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3098cf72c541f769b52598ff4e7dba74">llvm::AMDGPU::hasA16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa22d12557395f76722ef205293aa4a3c">llvm::AMDGPU::hasArchitectedFlatScratch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac438217e95bac185ceb0c4b6d63d3ed9">llvm::AMDGPU::hasDPPSrc1SGPR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9adcf3cabdbd72a34b34f13f2826314b">llvm::AMDGPU::hasG16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac06f184d382ba9a26ef8deaea0b31cd8">llvm::AMDGPU::hasGDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a98f3297011ab8da601c7cce576c3353f">llvm::AMDGPU::hasGFX10_3Insts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#adbe8b2394969d3cf98b70d46ce725354">llvm::AMDGPU::hasKernargPreload</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a870995a1f4af9ef3c31714595da7399f">llvm::AMDGPU::hasMAIInsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9896067acfdb72b73caeb1ede75c9479">llvm::AMDGPU::hasMIMG_R128</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#aa989296bab9644b587d977a65b455d91">llvm::ARMAsmBackend::hasNOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3856884676648fe8f7af93f6c5e60e1f">llvm::AMDGPU::hasPackedD16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6ce57c75a70c3b721b00dede60435d7a">llvm::AMDGPU::hasSRAMECC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af277efe76de2cd454da028d38646f2b5">llvm::AMDGPU::hasVOPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4db49adcedbc90eef2e5c105510f7811">llvm::AMDGPU::hasXNACK</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#ad60d0495301b78e11523def2cb8b2b59">llvm::ARMElfTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#a4c4cc9236e2a4f99e7e616a7f6740f16">llvm::X86_MC::is16BitMemOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ade135e9169df98a7457505a0ea5b6179">llvm::AMDGPU::isCI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a00cd25f8d9ef48abfa9b651262d6c741">llvm::AMDGPU::isGCN3Encoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27e5626ce22d0cd09916837dc88b7efe">llvm::AMDGPU::isGFX10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a65249b090745fad14294b652b417566b">llvm::AMDGPU::isGFX10_AEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a03038e2ec3d91a361fbbb066e575de9a">llvm::AMDGPU::isGFX10_BEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3d6f72ac6639b51b7a8a54368ad6332e">llvm::AMDGPU::isGFX11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a626413fe751b97e13812bb7b635e6dd5">llvm::AMDGPU::isGFX9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6927ea03a5a90995645230645e0fbd89">llvm::AMDGPU::isGFX90A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3aa6cae3cc5611453bbb619f354ea415">llvm::AMDGPU::isGFX940</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp/#a3b2972af3f99405c0dda2d67d9155225">isMicroMips</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp/#a63320f216609dcccd140b96d0d557f84">isMips32r6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a58f60f9ac04e27846a67a951d920837e">llvm::AMDGPU::isSI</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a5f19566522cbcd4812b5fea812847616">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::isThumb</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a2368235ddbd4b65c66fdca0a42b1ab64">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::isThumb2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp/#a482a1a87ca8a29083e5c88eac796ed62">isV8M</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter/#a3ac3630cb8cc41b1e66fd0523e806096">llvm::SparcInstPrinter::isV9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad198ccff657f64471c12cc36d9aa1969">llvm::AMDGPU::isVI</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4e7be374a3346400a32967d91108c3e">llvm::LoongArchTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a6349367781dae3049ca7dc31906fe3e7">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::mayNeedRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#a4315216f104f0f7963b4ba8e6f85d01d">llvm::CSKYAsmBackend::mayNeedRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetelfstreamer/#a08e72085c1973f94f76c4444c65e35e5">llvm::MSP430TargetELFStreamer::MSP430TargetELFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#aa70e27203f31ce8fcdd19e77996a12f8">llvm::X86_MC::needsAddressSizeOverride</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ad6600c9ef01f540a9d8a3991c2b13d25">llvm::HexagonMCInstrInfo::packetSizeSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ad68b53f833debb000d3141302ac9705f">llvm::RISCVInstPrinter::printBranchOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpuinstprinter-cpp/#a1e5d1000c3b8d567a908476ccd19982f">printImmediateBFloat16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpuinstprinter-cpp/#ad83604e400c625bc27c8710eac8e55f1">printImmediateFP16</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a6cd305cb01305d4c101633f77bf6e4bc">llvm::PPCInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ac2345780b2997c9882b808140bce11fa">llvm::X86ATTInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#ae9718621d043eee9b485afd90cd062b6">llvm::X86IntelInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a9e01cbc62f1eb3379712051ded643013">llvm::X86InstPrinterCommon::printInstFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a89240de7c30d000b1e6698e0c259d7ef">llvm::ARMInstPrinter::printMemBOption</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a2512f7ec6f3ac947fb398d135929fe60">llvm::CSKYInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ad10e372bdad63fb7b26aef3ea2e33fc9">llvm::RISCVInstPrinter::printStackAdj</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a4ef893dbd3ef72a8e049fe401fcb39e5">llvm::AArch64InstPrinter::printSysAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a9e514c9fdf6eaec2a8f8baf8a8dce29b">llvm::AArch64InstPrinter::printSyspAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#ade0613efda90a350f47392d0b721b1f8">llvm::CSKYAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#a9c657032eafd38a8fa07606efe9af3a7">llvm::RISCVTargetELFStreamer::RISCVTargetELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetstreamer/#a77c52829c20b2ac68628b01d1cc5cdf3">llvm::RISCVTargetStreamer::setFlagsFromFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#aa05af02ae909fc030207294fa161cd08">llvm::LoongArchAsmBackend::shouldInsertExtraNopBytesForCodeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a6df2a46541fffb2b35320ae71b7fe26c">llvm::RISCVAsmBackend::shouldInsertExtraNopBytesForCodeAlign</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a>.</p>

</div>
</div>

### initInstrItins() {#af1487bf00f68f02583117ffa23d79619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSubtargetInfo::initInstrItins (<a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> &amp; InstrItins)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize an <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> instance.</p>

<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="#af907ecc18c1f4f0bce8a9e2eb449ffb8">getSchedModel</a>.</p>

</div>
</div>

### isCPUStringValid() {#ad86f7785b0fcd57aa9ed81c8d897002e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCSubtargetInfo::isCPUStringValid (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the CPU string is valid.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>

</div>
</div>

### resolveVariantSchedClass() {#a18de37f60c9c80f7974dbf8dfd3795cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::MCSubtargetInfo::resolveVariantSchedClass (unsigned SchedClass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> * MCII, unsigned CPUID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve a variant scheduling class for the given <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> and CPU.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ad09947650a7df617e008df474a1388b6">llvm::MCSchedModel::computeInstrLatency</a> and <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac080bbec97a31ee8728ca9828700ad45">llvm::MCSchedModel::getReciprocalThroughput</a>.</p>

</div>
</div>

### setDefaultFeatures() {#ac717fb0e66df93c662f97cc56de7d1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSubtargetInfo::setDefaultFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the features to the default for the given CPU and TuneCPU, with ano appended feature string.</p>

<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a>.</p>

</div>
</div>

### setFeatureBits() {#a163ce14824b63240eb1065b2ff583a8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSubtargetInfo::setFeatureBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; FeatureBits_)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#accd817bab317ddec52d5a38a4e4c4adc">llvm::CSKYAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### SetFeatureBitsTransitively() {#a930d94c27661f22a8f6959e3cab4ffda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset MCSubtargetInfo::SetFeatureBitsTransitively (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; FB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set/clear additional feature bits, including all other bits they imply.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a09e4ddb5c9eead1f368615b3bde65f92">SetImpliedBits</a>.</p>

</div>
</div>

### shouldPrefetchAddressSpace() {#a273eb79f44bfd3f16a87fa75003517fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCSubtargetInfo::shouldPrefetchAddressSpace (unsigned AS)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>if target want to issue a prefetch in address space <span class="doxyComputerOutput">AS</span>.</p></dd>
</dl>


<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>

</div>
</div>

### ToggleFeature() {#acaa1de0987d9c003e41c92f310c45746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset MCSubtargetInfo::ToggleFeature (uint64_t FB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Toggle a feature and return the re-computed feature bits.</p>


<p>This version does not change the implied bits.</p>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a54ab816fd39422eb444d7d1e01b50dd0">llvm::FeatureBitset::flip</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a499b9606a8f1365f4515e3cce4f14474">clearFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#a54ce870f13edcb1e43823a997d5ddaf7">createAMDGPUMCSubtargetInfo</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada96d67c594bff6ca1c65fb281f82ca5">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### ToggleFeature() {#a4f267aeb0a0e8878429f5bc98839b463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset MCSubtargetInfo::ToggleFeature (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; FB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Toggle a feature and return the re-computed feature bits.</p>


<p>This version does not change the implied bits.</p>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>

</div>
</div>

### ToggleFeature() {#a2624192c54a92722351fa791af3e862d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset MCSubtargetInfo::ToggleFeature (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Toggle a set of features and return the re-computed feature bits.</p>


<p>This version will also change all implied bits.</p>


<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#ad95f670b9a1cbb21ad61a831fa26a2ce">ClearImpliedBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a08e140d603b53c440c54cffc85131c8f">Find</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitarray/#ac4a0360586ccc1be7d8ec4e824778e1a">llvm::FeatureBitArray::getAsBitset</a>, <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv/#aa8238dd9dd2289c37c52823f01dfe460">llvm::SubtargetFeatureKV::Implies</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a09e4ddb5c9eead1f368615b3bde65f92">SetImpliedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a8de4cf7f3a21b57333330349f1f32ff3">llvm::SubtargetFeatures::StripFlag</a> and <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv/#a7052536ef4db759fa568ba0541e6170e">llvm::SubtargetFeatureKV::Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### InitMCProcessorInfo() {#adea593fdfefa11ea2aa7ed07d9df6155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSubtargetInfo::InitMCProcessorInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
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

<p>Initialize the scheduling model and feature bits.</p>


<p>FIXME: Find a way to stick this in the constructor, since it should only be called during initialization.</p>


<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a090d8f8a40ae8bd7f4ac776d186d0203">llvm::MCSchedModel::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a> and <a href="#a2eddfb1a986d95b7f9e8e0988f72960c">getSchedModelForCPU</a>.</p>


<p>Referenced by <a href="#a0c2da232cc1ad3f4633cb297c134e056">MCSubtargetInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CPU {#a6363980fb6547e299e5485aeb092f706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCSubtargetInfo::CPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### CPUSchedModel {#a28370d04e76df3d597f9d7d7d1d1a815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedModel* llvm::MCSubtargetInfo::CPUSchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### FeatureBits {#a05bd3d313328463e8a6b38572c670af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset llvm::MCSubtargetInfo::FeatureBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### FeatureString {#aa844e3492964a73c3f1a8d9a5694f807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCSubtargetInfo::FeatureString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### ForwardingPaths {#afa6ecbfa44815ecac602c4464b8c89b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned* llvm::MCSubtargetInfo::ForwardingPaths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### OperandCycles {#a6944a8b17a19321266590e3a7c592c52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned* llvm::MCSubtargetInfo::OperandCycles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### ProcDesc {#a72c12777e9fe49103d0955e9224eda7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;SubtargetSubTypeKV&gt; llvm::MCSubtargetInfo::ProcDesc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### ProcFeatures {#a1b3bd2c64941c9ebbc335a3ee500fdf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;SubtargetFeatureKV&gt; llvm::MCSubtargetInfo::ProcFeatures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### ProcNames {#ad7118621c50bb55b5e242dffd677b0bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;StringRef&gt; llvm::MCSubtargetInfo::ProcNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### ReadAdvanceTable {#ace0c1d26a71ad0e5cad7b712a432b95e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCReadAdvanceEntry* llvm::MCSubtargetInfo::ReadAdvanceTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### Stages {#ac9888377eec6c632750215fafef01de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrStage* llvm::MCSubtargetInfo::Stages</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### TargetTriple {#ab69a53ae01aa26a89807f2c4f6bfca54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::MCSubtargetInfo::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### TuneCPU {#a2bb27e0727627d3e942b253ecd136de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCSubtargetInfo::TuneCPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### WriteLatencyTable {#a89fa708ac2fd4ebd5120527020183bb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCWriteLatencyEntry* llvm::MCSubtargetInfo::WriteLatencyTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

### WriteProcResTable {#a6e38f7005146c7200047576966b6ba1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCWriteProcResEntry* llvm::MCSubtargetInfo::WriteProcResTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">MCSubtargetInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
