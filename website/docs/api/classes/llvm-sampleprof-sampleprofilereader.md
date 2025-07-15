---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/sampleprofilereader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleProfileReader` Class Reference

<p>Sample-based profile reader. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleProfileReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">llvm/ProfileData/SampleProfReader.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary">SampleProfileReaderBinary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc">SampleProfileReaderGCC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext">SampleProfileReaderText</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df3a90aaf7409ace0a2a56f5e539477">SampleProfileReader</a> (std::unique_ptr&lt; MemoryBuffer &gt; B, LLVMContext &amp;C, SampleProfileFormat Format=SPF_None)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc72083ad71103e9d6f2fd0a1b809ce">~SampleProfileReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a4501bd06c107c0864feb26f769225">readHeader</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read and validate the file header. <a href="#ae5a4501bd06c107c0864feb26f769225">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa462beca1930492cde15612a931fc98a">setDiscriminatorMaskedBitFrom</a> (FSDiscriminatorPass P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the bits for FS discriminators. <a href="#aa462beca1930492cde15612a931fc98a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0b29b235366b7d2447ab4dc39398ed">getDiscriminatorMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the bitmask the discriminators: For FS profiles, return the bit mask for this pass. <a href="#a8c0b29b235366b7d2447ab4dc39398ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bdbf84fa8e3f0e789653587d5c85515">read</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The interface to read sample profiles from the associated file. <a href="#a3bdbf84fa8e3f0e789653587d5c85515">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5401478f3b22021f2cd1a363e0ca63cb">read</a> (const DenseSet&lt; StringRef &gt; &amp;FuncsToUse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read sample profiles for the given functions. <a href="#a5401478f3b22021f2cd1a363e0ca63cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd9310a980c14646a01fe1960e72575">readImpl</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The implementaion to read sample profiles from the associated file. <a href="#affd9310a980c14646a01fe1960e72575">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec68a6075c99a337ba44070108ec9bac">dumpFunctionProfile</a> (const FunctionSamples &amp;FS, raw_ostream &amp;OS=dbgs())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the profile for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a></span> on stream <span class="doxyComputerOutput">OS</span>. <a href="#aec68a6075c99a337ba44070108ec9bac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc0f7bf9921713c80c3c67aca32fd05">collectFuncsFromModule</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect functions with definitions in <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> M. <a href="#abfc0f7bf9921713c80c3c67aca32fd05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241493be5796817782fda51d1b3fa61d">dump</a> (raw_ostream &amp;OS=dbgs())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print all the profiles on stream <span class="doxyComputerOutput">OS</span>. <a href="#a241493be5796817782fda51d1b3fa61d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a3cf9f9ad94831f204a4654a423906">dumpJson</a> (raw_ostream &amp;OS=dbgs())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print all the profiles on stream <span class="doxyComputerOutput">OS</span> in the JSON format. <a href="#ad1a3cf9f9ad94831f204a4654a423906">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a231496cee212bad0c2b9fa7877dc0cb4">getSamplesFor</a> (const Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the samples collected for function <span class="doxyComputerOutput">F</span>. <a href="#a231496cee212bad0c2b9fa7877dc0cb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e1a3ce2a89a49b285c8821f490858d">getSamplesFor</a> (StringRef Fname)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the samples collected for function <span class="doxyComputerOutput">F</span>. <a href="#ac4e1a3ce2a89a49b285c8821f490858d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19892ef729b441b25d21f69ea15c9118">getProfiles</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all the profiles. <a href="#a19892ef729b441b25d21f69ea15c9118">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7db78adf47785867ea84d77ace26cc6">reportError</a> (int64_t LineNumber, const Twine &amp;Msg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report a parse error message. <a href="#af7db78adf47785867ea84d77ace26cc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummary">ProfileSummary</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7870bf43f8e5b80b21caea5ea2e23977">getSummary</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the profile summary. <a href="#a7870bf43f8e5b80b21caea5ea2e23977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43723603831c71999b23415970521f78">getBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1777c98ca71ef45d5989b2d8bd6ad07">getFormat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the profile format. <a href="#aa1777c98ca71ef45d5989b2d8bd6ad07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f372a7784eaec8c761af0ed7c38b1b2">profileIsProbeBased</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether input profile is based on pseudo probes. <a href="#a1f372a7784eaec8c761af0ed7c38b1b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2258ff0986bd6227697d76e9001406d">profileIsCS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether input profile is fully context-sensitive. <a href="#ab2258ff0986bd6227697d76e9001406d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b0eeddd296ef6f073c94f1399672dfb">profileIsPreInlined</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether input profile contains ShouldBeInlined contexts. <a href="#a3b0eeddd296ef6f073c94f1399672dfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4196c502c66af04d2b595e8d81ef7bef">profileIsFS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether input profile is flow-sensitive. <a href="#a4196c502c66af04d2b595e8d81ef7bef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profilesymbollist">ProfileSymbolList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9976cd2d8ddf787f19d5dbca4530fa6">getProfileSymbolList</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf6b062ae315c31461ffdeef36b5c80">getNameTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It includes all the names that have samples either in outline instance or inline instance. <a href="#aaaf6b062ae315c31461ffdeef36b5c80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b6bef1d2a846490e4f2a50602b561e5">dumpSectionInfo</a> (raw_ostream &amp;OS=dbgs())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b5f844964866320a86d8bb53c84e6eb">useMD5</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether names in the profile are all <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> numbers. <a href="#a2b5f844964866320a86d8bb53c84e6eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa18ef5c27c8814beaf09961918ff6a34">setProfileUseMD5</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Force the profile to use <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> in Sample contexts, even if function names are present. <a href="#aa18ef5c27c8814beaf09961918ff6a34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5cc900a86781c28fb6b6dd00ed94872">setSkipFlatProf</a> (bool Skip)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Don't read profile without context if the flag is set. <a href="#ae5cc900a86781c28fb6b6dd00ed94872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85697d878bb59b3f4768560065e708d2">hasUniqSuffix</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether any name in the profile contains ".__uniq." suffix. <a href="#a85697d878bb59b3f4768560065e708d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderitaniumremapper">SampleProfileReaderItaniumRemapper</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a530222c3b645acc9170003d046753e94">getRemapper</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f2425598ac25a3e028f96ac39a56ce">setModule</a> (const Module *Mod)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9734347ce96e871b96518cf49d6c545">setFuncNameToProfNameMap</a> (const HashKeyMap&lt; std::unordered_map, FunctionId, FunctionId &gt; &amp;FPMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a862a85fc052e3da0f7109bc54ef4998d">computeSummary</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute summary for this profile. <a href="#a862a85fc052e3da0f7109bc54ef4998d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa52c8c849b7815a0c717b8048a1af759">read</a> (const DenseSet&lt; StringRef &gt; &amp;FuncsToUse, SampleProfileMap &amp;Profiles)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read sample profiles for the given functions and write them to the given profile map. <a href="#aa52c8c849b7815a0c717b8048a1af759">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31357a0bab13543c1d9e22e22f33ec4">Profiles</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map every function to its associated profile. <a href="#ad31357a0bab13543c1d9e22e22f33ec4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe19488a2996e10c93bccbe3d332ca93">Ctx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM context used to emit diagnostics. <a href="#afe19488a2996e10c93bccbe3d332ca93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a317d9b9a39f8213c84429fbf54a7055f">Buffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> buffer holding the profile file. <a href="#a317d9b9a39f8213c84429fbf54a7055f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/profilesummary">ProfileSummary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808d204826972c99cd36562eea139d23">Summary</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profile summary information. <a href="#a808d204826972c99cd36562eea139d23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderitaniumremapper">SampleProfileReaderItaniumRemapper</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a0b1a6e53cb0a08dbf78fc3cebc224">Remapper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4518eb71be9fbc06834f0e817c1525ff">FuncNameToProfNameMap</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; uint64_t, std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2d3f775d9437f33d03a025671010a9">FuncMetadataIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03fdd01c4b2069f558380547824c7373">ProfileSecRange</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3493b1a9313f04d70a4c843d827d42a9">ProfileHasAttribute</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the profile has attribute metadata. <a href="#a3493b1a9313f04d70a4c843d827d42a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bd0368cb44b2cc97123f03de71efaa">ProfileIsProbeBased</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether samples are collected based on pseudo probes. <a href="#af3bd0368cb44b2cc97123f03de71efaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53cef5334d9e6535928ce4d79e7529e3">ProfileIsCS</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether function profiles are context-sensitive flat profiles. <a href="#a53cef5334d9e6535928ce4d79e7529e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09599626d454548b75a8508733b742ce">ProfileIsPreInlined</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether function profile contains ShouldBeInlined contexts. <a href="#a09599626d454548b75a8508733b742ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bd87b526bf1a09487cf4d75d9e638ef">CSProfileCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of context-sensitive profiles. <a href="#a1bd87b526bf1a09487cf4d75d9e638ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c8e7a5bebd5fa73b577fdc7677f7a5">ProfileIsFS</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the function profiles use FS discriminators. <a href="#ab3c8e7a5bebd5fa73b577fdc7677f7a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cddd27e849335a576339995fc8feaa7">Format</a> = <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca71fa511e217d0835567f7d919aab6d02">SPF_None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The format of sample. <a href="#a7cddd27e849335a576339995fc8feaa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be68a56c1386faa6c75baf21a462df7">M</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current module being compiled if <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a> is used by compiler. <a href="#a2be68a56c1386faa6c75baf21a462df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01904e1eb14d24c6c8dc095c102815a7">MaskedBitFrom</a> = 31</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Zero out the discriminator bits higher than bit MaskedBitFrom (0 based). <a href="#a01904e1eb14d24c6c8dc095c102815a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a549796a96109cea2cceae7d708fa5955">ProfileIsMD5</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the profile uses <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> for Sample Contexts and function names. <a href="#a549796a96109cea2cceae7d708fa5955">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a8cd3b6849f62c8ff4b44233374747d">SkipFlatProf</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If SkipFlatProf is true, skip functions marked with !Flat in text mode or sections with SecFlagFlat flag in ExtBinary mode. <a href="#a3a8cd3b6849f62c8ff4b44233374747d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f2d1c30eab01a2f5ae485d3c3cbf5b4">create</a> (StringRef Filename, LLVMContext &amp;C, vfs::FileSystem &amp;FS, FSDiscriminatorPass P=FSDiscriminatorPass::Base, StringRef RemapFilename="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a sample profile reader appropriate to the file format. <a href="#a1f2d1c30eab01a2f5ae485d3c3cbf5b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13d9a01b470d4ae7e0f1ea117f2e3dc">create</a> (std::unique_ptr&lt; MemoryBuffer &gt; &amp;B, LLVMContext &amp;C, vfs::FileSystem &amp;FS, FSDiscriminatorPass P=FSDiscriminatorPass::Base, StringRef RemapFilename="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a sample profile reader from the supplied memory buffer. <a href="#aa13d9a01b470d4ae7e0f1ea117f2e3dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/profilesummary">ProfileSummary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a721924780859cc437b2316fb29833af1">takeSummary</a> (SampleProfileReader &amp;Reader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take ownership of the summary of this reader. <a href="#a721924780859cc437b2316fb29833af1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Sample-based profile reader.</p>


<p>Each profile contains sample counts for all the functions executed. Inside each function, statements are annotated with the collected samples on all the instructions associated with that statement.</p>


<p>For this to produce meaningful data, the program needs to be compiled with some debug information (at minimum, line numbers: -gline-tables-only). Otherwise, it will be impossible to match IR instructions to the line numbers collected by the profiler.</p>


<p>From the profile file, we are interested in collecting the following information:</p>


<ul class="doxyList ">
<li>A list of functions included in the profile (mangled names).</li>
<li>For each function F:

<ol class="doxyList" type="1">
<li>The total number of samples collected in F.</li>
<li>The samples collected at each line in F. To provide some protection against source code shuffling, line numbers should be relative to the start of the function.</li>
</ol></li>
</ul>

<p>The reader supports two file formats: text and binary. The text format is useful for debugging and testing, while the binary format is more compact and I/O efficient. They can both be used interchangeably.</p>


<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SampleProfileReader() {#a7df3a90aaf7409ace0a2a56f5e539477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleProfileReader::SampleProfileReader (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; B, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a> Format=<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca71fa511e217d0835567f7d919aab6d02">SPF_None</a>)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a317d9b9a39f8213c84429fbf54a7055f">Buffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#afe19488a2996e10c93bccbe3d332ca93">Ctx</a>, <a href="#a7cddd27e849335a576339995fc8feaa7">Format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#ad31357a0bab13543c1d9e22e22f33ec4">Profiles</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca71fa511e217d0835567f7d919aab6d02">llvm::sampleprof::SPF_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a6e504be88a1ea38cddc31af56ab20fb7">llvm::sampleprof::SampleProfileReaderBinary::SampleProfileReaderBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a78d594511a420e0aa288e6cada80638a">llvm::sampleprof::SampleProfileReaderGCC::SampleProfileReaderGCC</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#a287358d6113997c07bad1ba25060c1fd">llvm::sampleprof::SampleProfileReaderText::SampleProfileReaderText</a> and <a href="#a721924780859cc437b2316fb29833af1">takeSummary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SampleProfileReader() {#a4cc72083ad71103e9d6f2fd0a1b809ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::sampleprof::SampleProfileReader::~SampleProfileReader ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectFuncsFromModule() {#abfc0f7bf9921713c80c3c67aca32fd05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::sampleprof::SampleProfileReader::collectFuncsFromModule ()</td>
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

<p>Collect functions with definitions in <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> M.</p>


<p>For reader which support loading function profiles on demand, return true when the reader has been given a module. Always return false for reader which doesn't support loading function profiles on demand.</p>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

### dump() {#a241493be5796817782fda51d1b3fa61d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileReader::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS=<a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print all the profiles on stream <span class="doxyComputerOutput">OS</span>.</p>


<p>Dump all the function profiles found on stream <span class="doxyComputerOutput">OS</span>.</p>


<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#aec68a6075c99a337ba44070108ec9bac">dumpFunctionProfile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad31357a0bab13543c1d9e22e22f33ec4">Profiles</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a11f675e2f1396d64eefeaf67cdce624e">llvm::sampleprof::sortFuncProfiles</a>.</p>

</div>
</div>

### dumpFunctionProfile() {#aec68a6075c99a337ba44070108ec9bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileReader::dumpFunctionProfile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; FS, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS=<a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the profile for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a></span> on stream <span class="doxyComputerOutput">OS</span>.</p>


<p>Dump the function profile for <span class="doxyComputerOutput">FName</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FContext</td>
<td class="doxyParamItemDescription"><p>Name + context of the function to print.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>Stream to emit the output to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>Referenced by <a href="#a241493be5796817782fda51d1b3fa61d">dump</a>.</p>

</div>
</div>

### dumpJson() {#ad1a3cf9f9ad94831f204a4654a423906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileReader::dumpJson (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS=<a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print all the profiles on stream <span class="doxyComputerOutput">OS</span> in the JSON format.</p>


<p>Dump all the function profiles found on stream <span class="doxyComputerOutput">OS</span> in the JSON format.</p>


<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a5741cf7e48bbab22369fa2aa8c9e151f">llvm::json::OStream::arrayBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#aa4ef0d3ce12400b17d9f9a5cd028a211">llvm::json::OStream::arrayEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad31357a0bab13543c1d9e22e22f33ec4">Profiles</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a11f675e2f1396d64eefeaf67cdce624e">llvm::sampleprof::sortFuncProfiles</a>.</p>

</div>
</div>

### dumpSectionInfo() {#a9b6bef1d2a846490e4f2a50602b561e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::sampleprof::SampleProfileReader::dumpSectionInfo (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS=<a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs</a>())</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

### getBuffer() {#a43723603831c71999b23415970521f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBuffer * llvm::sampleprof::SampleProfileReader::getBuffer ()</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a317d9b9a39f8213c84429fbf54a7055f">Buffer</a>.</p>

</div>
</div>

### getDiscriminatorMask() {#a8c0b29b235366b7d2447ab4dc39398ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sampleprof::SampleProfileReader::getDiscriminatorMask ()</td>
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

<p>Get the bitmask the discriminators: For FS profiles, return the bit mask for this pass.</p>


<p>For non FS profiles, return (unsigned) -1.</p>


<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa860d116fc20fde892f7485b706f9139">llvm::getN1Bits</a>, <a href="#a01904e1eb14d24c6c8dc095c102815a7">MaskedBitFrom</a> and <a href="#ab3c8e7a5bebd5fa73b577fdc7677f7a5">ProfileIsFS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a0320040b070e4fc2904794078a64e46c">llvm::sampleprof::SampleProfileReaderBinary::readProfile</a>.</p>

</div>
</div>

### getFormat() {#aa1777c98ca71ef45d5989b2d8bd6ad07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileFormat llvm::sampleprof::SampleProfileReader::getFormat ()</td>
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

<p>Return the profile format.</p>

<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a7cddd27e849335a576339995fc8feaa7">Format</a>.</p>

</div>
</div>

### getNameTable() {#aaaf6b062ae315c31461ffdeef36b5c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::vector&lt; FunctionId &gt; * llvm::sampleprof::SampleProfileReader::getNameTable ()</td>
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

<p>It includes all the names that have samples either in outline instance or inline instance.</p>

<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

### getProfiles() {#a19892ef729b441b25d21f69ea15c9118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileMap &amp; llvm::sampleprof::SampleProfileReader::getProfiles ()</td>
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

<p>Return all the profiles.</p>

<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#ad31357a0bab13543c1d9e22e22f33ec4">Profiles</a>.</p>

</div>
</div>

### getProfileSymbolList() {#af9976cd2d8ddf787f19d5dbca4530fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; ProfileSymbolList &gt; llvm::sampleprof::SampleProfileReader::getProfileSymbolList ()</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

### getRemapper() {#a530222c3b645acc9170003d046753e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileReaderItaniumRemapper * llvm::sampleprof::SampleProfileReader::getRemapper ()</td>
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



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a31a0b1a6e53cb0a08dbf78fc3cebc224">Remapper</a>.</p>

</div>
</div>

### getSamplesFor() {#a231496cee212bad0c2b9fa7877dc0cb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::sampleprof::SampleProfileReader::getSamplesFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Return the samples collected for function <span class="doxyComputerOutput">F</span>.</p>

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a> and <a href="#a231496cee212bad0c2b9fa7877dc0cb4">getSamplesFor</a>.</p>


<p>Referenced by <a href="#a231496cee212bad0c2b9fa7877dc0cb4">getSamplesFor</a>.</p>

</div>
</div>

### getSamplesFor() {#ac4e1a3ce2a89a49b285c8821f490858d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::sampleprof::SampleProfileReader::getSamplesFor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Fname)</td>
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

<p>Return the samples collected for function <span class="doxyComputerOutput">F</span>.</p>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="#a4518eb71be9fbc06834f0e817c1525ff">FuncNameToProfNameMap</a>, <a href="#ad31357a0bab13543c1d9e22e22f33ec4">Profiles</a> and <a href="#a31a0b1a6e53cb0a08dbf78fc3cebc224">Remapper</a>.</p>

</div>
</div>

### getSummary() {#a7870bf43f8e5b80b21caea5ea2e23977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummary &amp; llvm::sampleprof::SampleProfileReader::getSummary ()</td>
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

<p>Return the profile summary.</p>

<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a808d204826972c99cd36562eea139d23">Summary</a>.</p>

</div>
</div>

### hasUniqSuffix() {#a85697d878bb59b3f4768560065e708d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::sampleprof::SampleProfileReader::hasUniqSuffix ()</td>
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

<p>Return whether any name in the profile contains ".__uniq." suffix.</p>

<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

### profileIsCS() {#ab2258ff0986bd6227697d76e9001406d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::profileIsCS ()</td>
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

<p>Whether input profile is fully context-sensitive.</p>

<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a53cef5334d9e6535928ce4d79e7529e3">ProfileIsCS</a>.</p>

</div>
</div>

### profileIsFS() {#a4196c502c66af04d2b595e8d81ef7bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::profileIsFS ()</td>
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

<p>Whether input profile is flow-sensitive.</p>

<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#ab3c8e7a5bebd5fa73b577fdc7677f7a5">ProfileIsFS</a>.</p>

</div>
</div>

### profileIsPreInlined() {#a3b0eeddd296ef6f073c94f1399672dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::profileIsPreInlined ()</td>
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

<p>Whether input profile contains ShouldBeInlined contexts.</p>

<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a09599626d454548b75a8508733b742ce">ProfileIsPreInlined</a>.</p>

</div>
</div>

### profileIsProbeBased() {#a1f372a7784eaec8c761af0ed7c38b1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::profileIsProbeBased ()</td>
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

<p>Whether input profile is based on pseudo probes.</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#af3bd0368cb44b2cc97123f03de71efaa">ProfileIsProbeBased</a>.</p>

</div>
</div>

### read() {#a3bdbf84fa8e3f0e789653587d5c85515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sampleprof::SampleProfileReader::read ()</td>
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

<p>The interface to read sample profiles from the associated file.</p>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="#afe19488a2996e10c93bccbe3d332ca93">Ctx</a>, <a href="#affd9310a980c14646a01fe1960e72575">readImpl</a>, <a href="#a31a0b1a6e53cb0a08dbf78fc3cebc224">Remapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afddaa81316d56f125de69793e0ddb33c">llvm::sampleprof::FunctionSamples::UseMD5</a> and <a href="#a2b5f844964866320a86d8bb53c84e6eb">useMD5</a>.</p>


<p>Referenced by <a href="#a5401478f3b22021f2cd1a363e0ca63cb">read</a>.</p>

</div>
</div>

### read() {#a5401478f3b22021f2cd1a363e0ca63cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sampleprof::SampleProfileReader::read (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; FuncsToUse)</td>
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

<p>Read sample profiles for the given functions.</p>

<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="#ad31357a0bab13543c1d9e22e22f33ec4">Profiles</a>, <a href="#a3bdbf84fa8e3f0e789653587d5c85515">read</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

### readHeader() {#ae5a4501bd06c107c0864feb26f769225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::sampleprof::SampleProfileReader::readHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read and validate the file header.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

### readImpl() {#affd9310a980c14646a01fe1960e72575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::sampleprof::SampleProfileReader::readImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The implementaion to read sample profiles from the associated file.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a3bdbf84fa8e3f0e789653587d5c85515">read</a>.</p>

</div>
</div>

### reportError() {#af7db78adf47785867ea84d77ace26cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileReader::reportError (int64_t LineNumber, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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

<p>Report a parse error message.</p>

<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="#a317d9b9a39f8213c84429fbf54a7055f">Buffer</a> and <a href="#afe19488a2996e10c93bccbe3d332ca93">Ctx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a253ea7b225121d422aa3378a18dc2030">llvm::sampleprof::SampleProfileReaderBinary::readNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a3692dc50c07c5eda5e01f891cc03047c">llvm::sampleprof::SampleProfileReaderGCC::readNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a136a5648f006c4f55171f4559f5ce4b0">llvm::sampleprof::SampleProfileReaderBinary::readString</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9c60d8b65cd491edeafb796ba396acf8">llvm::sampleprof::SampleProfileReaderBinary::readUnencodedNumber</a>.</p>

</div>
</div>

### setDiscriminatorMaskedBitFrom() {#aa462beca1930492cde15612a931fc98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileReader::setDiscriminatorMaskedBitFrom (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fc">FSDiscriminatorPass</a> P)</td>
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

<p>Set the bits for FS discriminators.</p>


<p>Parameter <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> specify the sequence number, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> == i is for the i-th round of adding FS discriminators. <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> == 0 is for using base discriminators.</p>


<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a54f635dae16f504eb603ff2842f39d97">llvm::getFSPassBitEnd</a>, <a href="#a01904e1eb14d24c6c8dc095c102815a7">MaskedBitFrom</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### setFuncNameToProfNameMap() {#aa9734347ce96e871b96518cf49d6c545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileReader::setFuncNameToProfNameMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; &amp; FPMap)</td>
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



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a4518eb71be9fbc06834f0e817c1525ff">FuncNameToProfNameMap</a>.</p>

</div>
</div>

### setModule() {#a55f2425598ac25a3e028f96ac39a56ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileReader::setModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * Mod)</td>
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



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="#a2be68a56c1386faa6c75baf21a462df7">M</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>.</p>

</div>
</div>

### setProfileUseMD5() {#aa18ef5c27c8814beaf09961918ff6a34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sampleprof::SampleProfileReader::setProfileUseMD5 ()</td>
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

<p>Force the profile to use <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> in Sample contexts, even if function names are present.</p>

<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a549796a96109cea2cceae7d708fa5955">ProfileIsMD5</a>.</p>

</div>
</div>

### setSkipFlatProf() {#ae5cc900a86781c28fb6b6dd00ed94872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileReader::setSkipFlatProf (bool Skip)</td>
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

<p>Don't read profile without context if the flag is set.</p>

<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a3a8cd3b6849f62c8ff4b44233374747d">SkipFlatProf</a>.</p>

</div>
</div>

### useMD5() {#a2b5f844964866320a86d8bb53c84e6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::useMD5 ()</td>
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

<p>Return whether names in the profile are all <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> numbers.</p>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a549796a96109cea2cceae7d708fa5955">ProfileIsMD5</a>.</p>


<p>Referenced by <a href="#a3bdbf84fa8e3f0e789653587d5c85515">read</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a08a6c4a1c3536fa7e594a3151e0773f9">llvm::sampleprof::SampleProfileReaderBinary::readNameTable</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a749c376568365b892c49529c92ed7499">llvm::sampleprof::SampleProfileReaderExtBinaryBase::useFuncOffsetList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### computeSummary() {#a862a85fc052e3da0f7109bc54ef4998d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileReader::computeSummary ()</td>
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

<p>Compute summary for this profile.</p>

<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 2013 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#aa77c45e5b6c316812092a7e8a1e30143">llvm::SampleProfileSummaryBuilder::computeSummaryForProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a9b2e51220aabb88a132d3bc8fbdf5a66">llvm::ProfileSummaryBuilder::DefaultCutoffs</a>, <a href="#ad31357a0bab13543c1d9e22e22f33ec4">Profiles</a> and <a href="#a808d204826972c99cd36562eea139d23">Summary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#aa53d5b8b15dd26564754966d3159f822">llvm::sampleprof::SampleProfileReaderGCC::readFunctionProfiles</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>.</p>

</div>
</div>

### read() {#aa52c8c849b7815a0c717b8048a1af759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::sampleprof::SampleProfileReader::read (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; FuncsToUse, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; Profiles)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read sample profiles for the given functions and write them to the given profile map.</p>


<p>Currently it's only used for extended binary format to load the profiles on-demand.</p>


<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea63877363c706f5095d05a54f8b57b0ae">llvm::not_implemented</a> and <a href="#ad31357a0bab13543c1d9e22e22f33ec4">Profiles</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Buffer {#a317d9b9a39f8213c84429fbf54a7055f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::sampleprof::SampleProfileReader::Buffer</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> buffer holding the profile file.</p>

<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a43723603831c71999b23415970521f78">getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinary/#ac37600268c671eee29e31904b1532c17">llvm::sampleprof::SampleProfileReaderExtBinary::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#ade9bafe407ebfb2eed960233a4f5da22">llvm::sampleprof::SampleProfileReaderGCC::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderrawbinary/#ac52edce1e67044bb74c9839d0b91445e">llvm::sampleprof::SampleProfileReaderRawBinary::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#ac6f6906a46a807e4f041c463b04511fa">llvm::sampleprof::SampleProfileReaderText::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a36208a5b2efdedf5b0640c8b47e235b8">llvm::sampleprof::SampleProfileReaderBinary::readHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ae375ab166c92c7d215eea3a3f0277d46">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#aa3075229a3db86f1b533efcc85f82d97">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="#af7db78adf47785867ea84d77ace26cc6">reportError</a>, <a href="#a7df3a90aaf7409ace0a2a56f5e539477">SampleProfileReader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a78d594511a420e0aa288e6cada80638a">llvm::sampleprof::SampleProfileReaderGCC::SampleProfileReaderGCC</a>.</p>

</div>
</div>

### CSProfileCount {#a1bd87b526bf1a09487cf4d75d9e638ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sampleprof::SampleProfileReader::CSProfileCount = 0</td>
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

<p>Number of context-sensitive profiles.</p>

<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a52d0fff5d3fdc4368cb7b9a2edda2b6f">llvm::sampleprof::SampleProfileReaderBinary::readFuncProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a727bcceedcf0fe170cb330513c25ab2a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>.</p>

</div>
</div>

### Ctx {#afe19488a2996e10c93bccbe3d332ca93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::sampleprof::SampleProfileReader::Ctx</td>
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

<p>LLVM context used to emit diagnostics.</p>

<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a3bdbf84fa8e3f0e789653587d5c85515">read</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="#af7db78adf47785867ea84d77ace26cc6">reportError</a> and <a href="#a7df3a90aaf7409ace0a2a56f5e539477">SampleProfileReader</a>.</p>

</div>
</div>

### Format {#a7cddd27e849335a576339995fc8feaa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileFormat llvm::sampleprof::SampleProfileReader::Format = <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca71fa511e217d0835567f7d919aab6d02">SPF_None</a></td>
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

<p>The format of sample.</p>

<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#aa1777c98ca71ef45d5989b2d8bd6ad07">getFormat</a>, <a href="#a7df3a90aaf7409ace0a2a56f5e539477">SampleProfileReader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a6e504be88a1ea38cddc31af56ab20fb7">llvm::sampleprof::SampleProfileReaderBinary::SampleProfileReaderBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinary/#a94ba09b9a0e98ad630527780bbd33d12">llvm::sampleprof::SampleProfileReaderExtBinary::SampleProfileReaderExtBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab6ffdd6df239a2e84804f57c4b7c7317">llvm::sampleprof::SampleProfileReaderExtBinaryBase::SampleProfileReaderExtBinaryBase</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderrawbinary/#a90d37b805071293af6ee34041153f44b">llvm::sampleprof::SampleProfileReaderRawBinary::SampleProfileReaderRawBinary</a>.</p>

</div>
</div>

### FuncMetadataIndex {#a0e2d3f775d9437f33d03a025671010a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;uint64_t, std::pair&lt;const uint8_t *, const uint8_t *&gt; &gt; llvm::sampleprof::SampleProfileReader::FuncMetadataIndex</td>
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



<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a077db87ff742498d2add620c1a7130db">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a58cedb1356bab80647af0fa48bc1750a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>.</p>

</div>
</div>

### FuncNameToProfNameMap {#a4518eb71be9fbc06834f0e817c1525ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HashKeyMap&lt;std::unordered_map, FunctionId, FunctionId&gt;* llvm::sampleprof::SampleProfileReader::FuncNameToProfNameMap = nullptr</td>
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



<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#ac4e1a3ce2a89a49b285c8821f490858d">getSamplesFor</a> and <a href="#aa9734347ce96e871b96518cf49d6c545">setFuncNameToProfNameMap</a>.</p>

</div>
</div>

### M {#a2be68a56c1386faa6c75baf21a462df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module* llvm::sampleprof::SampleProfileReader::M = nullptr</td>
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

<p>The current module being compiled if <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a> is used by compiler.</p>


<p>If <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a> is used by other tools which are not compiler, M is usually nullptr.</p>


<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a0d0cdeb3cf9845558d9577f37fc326b3">llvm::sampleprof::SampleProfileReaderExtBinaryBase::collectFuncsFromModule</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a> and <a href="#a55f2425598ac25a3e028f96ac39a56ce">setModule</a>.</p>

</div>
</div>

### MaskedBitFrom {#a01904e1eb14d24c6c8dc095c102815a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sampleprof::SampleProfileReader::MaskedBitFrom = 31</td>
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

<p>Zero out the discriminator bits higher than bit MaskedBitFrom (0 based).</p>


<p>The default is to keep all the bits.</p>


<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a8c0b29b235366b7d2447ab4dc39398ed">getDiscriminatorMask</a> and <a href="#aa462beca1930492cde15612a931fc98a">setDiscriminatorMaskedBitFrom</a>.</p>

</div>
</div>

### ProfileHasAttribute {#a3493b1a9313f04d70a4c843d827d42a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::ProfileHasAttribute = false</td>
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

<p>Whether the profile has attribute metadata.</p>

<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a077db87ff742498d2add620c1a7130db">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a58cedb1356bab80647af0fa48bc1750a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>.</p>

</div>
</div>

### ProfileIsCS {#a53cef5334d9e6535928ce4d79e7529e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::ProfileIsCS = false</td>
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

<p>Whether function profiles are context-sensitive flat profiles.</p>

<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#ab2258ff0986bd6227697d76e9001406d">profileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a272ffb93f3958019735d7a4ef9bf22d2">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readCSNameTableSec</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a727bcceedcf0fe170cb330513c25ab2a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a08a6c4a1c3536fa7e594a3151e0773f9">llvm::sampleprof::SampleProfileReaderBinary::readNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a33a776d038d88cf9261e439f16455d50">llvm::sampleprof::SampleProfileReaderBinary::readSampleContextFromTable</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a749c376568365b892c49529c92ed7499">llvm::sampleprof::SampleProfileReaderExtBinaryBase::useFuncOffsetList</a>.</p>

</div>
</div>

### ProfileIsFS {#ab3c8e7a5bebd5fa73b577fdc7677f7a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::ProfileIsFS = false</td>
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

<p>Whether the function profiles use FS discriminators.</p>

<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a8c0b29b235366b7d2447ab4dc39398ed">getDiscriminatorMask</a>, <a href="#a4196c502c66af04d2b595e8d81ef7bef">profileIsFS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a5ad89ebfc9008ab04dbaf011e1f1e8db">llvm::sampleprof::SampleProfileReaderBinary::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>.</p>

</div>
</div>

### ProfileIsMD5 {#a549796a96109cea2cceae7d708fa5955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::ProfileIsMD5 = false</td>
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

<p>Whether the profile uses <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> for Sample Contexts and function names.</p>


<p>This can be one-way overriden by the user to force use <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a>.</p>


<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>, <a href="#aa18ef5c27c8814beaf09961918ff6a34">setProfileUseMD5</a> and <a href="#a2b5f844964866320a86d8bb53c84e6eb">useMD5</a>.</p>

</div>
</div>

### ProfileIsPreInlined {#a09599626d454548b75a8508733b742ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::ProfileIsPreInlined = false</td>
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

<p>Whether function profile contains ShouldBeInlined contexts.</p>

<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a3b0eeddd296ef6f073c94f1399672dfb">profileIsPreInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>.</p>

</div>
</div>

### ProfileIsProbeBased {#af3bd0368cb44b2cc97123f03de71efaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::ProfileIsProbeBased = false</td>
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

<p>Whether samples are collected based on pseudo probes.</p>

<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a1f372a7784eaec8c761af0ed7c38b1b2">profileIsProbeBased</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>.</p>

</div>
</div>

### Profiles {#ad31357a0bab13543c1d9e22e22f33ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileMap llvm::sampleprof::SampleProfileReader::Profiles</td>
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

<p>Map every function to its associated profile.</p>


<p>The profile of every function executed at runtime is collected in the structure <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a>. This maps function objects to their corresponding profiles.</p>


<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a862a85fc052e3da0f7109bc54ef4998d">computeSummary</a>, <a href="#a241493be5796817782fda51d1b3fa61d">dump</a>, <a href="#ad1a3cf9f9ad94831f204a4654a423906">dumpJson</a>, <a href="#a19892ef729b441b25d21f69ea15c9118">getProfiles</a>, <a href="#ac4e1a3ce2a89a49b285c8821f490858d">getSamplesFor</a>, <a href="#a5401478f3b22021f2cd1a363e0ca63cb">read</a>, <a href="#aa52c8c849b7815a0c717b8048a1af759">read</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a077db87ff742498d2add620c1a7130db">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a58cedb1356bab80647af0fa48bc1750a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#aa172ac1d7f119592a8ef1bdd63ff5ccf">llvm::sampleprof::SampleProfileReaderBinary::readFuncProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a52d0fff5d3fdc4368cb7b9a2edda2b6f">llvm::sampleprof::SampleProfileReaderBinary::readFuncProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a727bcceedcf0fe170cb330513c25ab2a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a> and <a href="#a7df3a90aaf7409ace0a2a56f5e539477">SampleProfileReader</a>.</p>

</div>
</div>

### ProfileSecRange {#a03fdd01c4b2069f558380547824c7373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt;const uint8_t *, const uint8_t *&gt; llvm::sampleprof::SampleProfileReader::ProfileSecRange</td>
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



<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>.</p>

</div>
</div>

### Remapper {#a31a0b1a6e53cb0a08dbf78fc3cebc224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SampleProfileReaderItaniumRemapper&gt; llvm::sampleprof::SampleProfileReader::Remapper</td>
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



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a530222c3b645acc9170003d046753e94">getRemapper</a>, <a href="#ac4e1a3ce2a89a49b285c8821f490858d">getSamplesFor</a>, <a href="#a3bdbf84fa8e3f0e789653587d5c85515">read</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a749c376568365b892c49529c92ed7499">llvm::sampleprof::SampleProfileReaderExtBinaryBase::useFuncOffsetList</a>.</p>

</div>
</div>

### SkipFlatProf {#a3a8cd3b6849f62c8ff4b44233374747d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileReader::SkipFlatProf = false</td>
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

<p>If SkipFlatProf is true, skip functions marked with !Flat in text mode or sections with SecFlagFlat flag in ExtBinary mode.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#aa3075229a3db86f1b533efcc85f82d97">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a> and <a href="#ae5cc900a86781c28fb6b6dd00ed94872">setSkipFlatProf</a>.</p>

</div>
</div>

### Summary {#a808d204826972c99cd36562eea139d23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ProfileSummary&gt; llvm::sampleprof::SampleProfileReader::Summary</td>
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

<p>Profile summary information.</p>

<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a862a85fc052e3da0f7109bc54ef4998d">computeSummary</a>, <a href="#a7870bf43f8e5b80b21caea5ea2e23977">getSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#aec2ab856ea5858bcc170eaaf185693d6">llvm::sampleprof::SampleProfileReaderBinary::readSummary</a> and <a href="#a721924780859cc437b2316fb29833af1">takeSummary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a1f2d1c30eab01a2f5ae485d3c3cbf5b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; SampleProfileReader &gt; &gt; SampleProfileReader::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &amp; FS, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fc">FSDiscriminatorPass</a> P=<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">FSDiscriminatorPass::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemapFilename="")</td>
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

<p>Create a sample profile reader appropriate to the file format.</p>


<p>Create a sample profile reader based on the format of the input file.</p>


<p>Create a remapper underlying if RemapFilename is not empty. Parameter P specifies the <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fc">FSDiscriminatorPass</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Filename</td>
<td class="doxyParamItemDescription"><p>The file to open.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">C</td>
<td class="doxyParamItemDescription"><p>The LLVM context to use to emit diagnostics.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">P</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fc">FSDiscriminatorPass</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RemapFilename</td>
<td class="doxyParamItemDescription"><p>The file used for profile remapping.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error code indicating the status of the created reader.</p></dd>
</dl>


<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1905 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a1f2d1c30eab01a2f5ae485d3c3cbf5b4">create</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0c339cfce77238670cd7657a636f4303">llvm::setupMemoryBuffer</a>.</p>


<p>Referenced by <a href="#a1f2d1c30eab01a2f5ae485d3c3cbf5b4">create</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a7cba8042f5f0daa198a43912b9bb3aa9">llvm::MIRProfileLoader::doInitialization</a>.</p>

</div>
</div>

### create() {#aa13d9a01b470d4ae7e0f1ea117f2e3dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; SampleProfileReader &gt; &gt; SampleProfileReader::create (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &amp; B, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &amp; FS, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fc">FSDiscriminatorPass</a> P=<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">FSDiscriminatorPass::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemapFilename="")</td>
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

<p>Create a sample profile reader from the supplied memory buffer.</p>


<p>Create a sample profile reader based on the format of the input data.</p>


<p>Create a remapper underlying if RemapFilename is not empty. Parameter P specifies the <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fc">FSDiscriminatorPass</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">B</td>
<td class="doxyParamItemDescription"><p>The memory buffer to create the reader from (assumes ownership).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">C</td>
<td class="doxyParamItemDescription"><p>The LLVM context to use to emit diagnostics.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">P</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fc">FSDiscriminatorPass</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RemapFilename</td>
<td class="doxyParamItemDescription"><p>The file used for profile remapping.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error code indicating the status of the created reader.</p></dd>
</dl>


<p>Declaration at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1976 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderitaniumremapper/#a2e6e6b82798c515f6161b9d05f404d83">llvm::sampleprof::SampleProfileReaderItaniumRemapper::create</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinary/#ac37600268c671eee29e31904b1532c17">llvm::sampleprof::SampleProfileReaderExtBinary::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#ade9bafe407ebfb2eed960233a4f5da22">llvm::sampleprof::SampleProfileReaderGCC::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderrawbinary/#ac52edce1e67044bb74c9839d0b91445e">llvm::sampleprof::SampleProfileReaderRawBinary::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#ac6f6906a46a807e4f041c463b04511fa">llvm::sampleprof::SampleProfileReaderText::hasFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbead5b649348c44c8f1f89cb53fe7604f64">llvm::unrecognized_format</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### takeSummary() {#a721924780859cc437b2316fb29833af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ProfileSummary &gt; llvm::sampleprof::SampleProfileReader::takeSummary (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a> &amp; Reader)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Take ownership of the summary of this reader.</p>

<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="#a7df3a90aaf7409ace0a2a56f5e539477">SampleProfileReader</a> and <a href="#a808d204826972c99cd36562eea139d23">Summary</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
