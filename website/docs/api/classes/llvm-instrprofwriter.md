---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instrprofwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstrProfWriter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::InstrProfWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">llvm/ProfileData/InstrProfWriter.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8307c49f2fa9f6b5d968b663105b5df">ProfilingData</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d08f898bf27f2ca8a20fe08e23b020">InstrProfWriter</a> (bool Sparse=false, uint64_t TemporalProfTraceReservoirSize=0, uint64_t MaxTemporalProfTraceLength=0, bool WritePrevVersion=false, memprof::IndexedVersion MemProfVersionRequested=static_cast&lt; memprof::IndexedVersion &gt;(memprof::MinimumSupportedVersion), bool MemProfFullSchema=false, bool MemprofGenerateRandomHotness=false, unsigned MemprofGenerateRandomHotnessSeed=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e0f9de2663ab52e28fb5e65535bf12">~InstrProfWriter</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="#ab8307c49f2fa9f6b5d968b663105b5df">ProfilingData</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad880af71be857e7c4c8ee2b57cc9c2af">getProfileData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80159a6def7a74a85d5f0592abb07a65">addRecord</a> (NamedInstrProfRecord &amp;&amp;I, uint64_t Weight, function_ref&lt; void(Error)&gt; Warn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add function counts for the given function. <a href="#a80159a6def7a74a85d5f0592abb07a65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa5eeeefece7dc425c48f87e4668f1b">addRecord</a> (NamedInstrProfRecord &amp;&amp;I, function_ref&lt; void(Error)&gt; Warn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ffa18a7702d5aee782d6e25a105ca8a">addVTableName</a> (StringRef VTableName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2713b4a910e8cfdceb4114823a49123d">addTemporalProfileTraces</a> (SmallVectorImpl&lt; TemporalProfTraceTy &gt; &amp;SrcTraces, uint64_t SrcStreamSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <span class="doxyComputerOutput">SrcTraces</span> using reservoir sampling where <span class="doxyComputerOutput">SrcStreamSize</span> is the total number of temporal profiling traces the source has seen. <a href="#a2713b4a910e8cfdceb4114823a49123d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade765798c3f446846b4c6771285a86b6">addMemProfData</a> (memprof::IndexedMemProfData Incoming, function_ref&lt; void(Error)&gt; Warn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the entire MemProfData <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a></span> to the writer context. <a href="#ade765798c3f446846b4c6771285a86b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b03d1480dc12839b1b66f2a1d69a79">addBinaryIds</a> (ArrayRef&lt; llvm::object::BuildID &gt; BIs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e2a95d34ae51ccf31e320d36bb0516c">mergeRecordsFromWriter</a> (InstrProfWriter &amp;&amp;IPW, function_ref&lt; void(Error)&gt; Warn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge existing function counts from the given writer. <a href="#a9e2a95d34ae51ccf31e320d36bb0516c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a49f43cb3ed032975144816e9884c5">write</a> (raw_fd_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the profile to <span class="doxyComputerOutput">OS</span>. <a href="#a20a49f43cb3ed032975144816e9884c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea67e7e8a34be965e9699bd9ecd885f">write</a> (raw_string_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the profile to a string output stream <span class="doxyComputerOutput">OS</span>. <a href="#a4ea67e7e8a34be965e9699bd9ecd885f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a76e869a218e271ec68f8a68968fde2">writeText</a> (raw_fd_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the profile in text format to <span class="doxyComputerOutput">OS</span>. <a href="#a2a76e869a218e271ec68f8a68968fde2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab803c3548558a7dd296a3b2be2ef9773">writeTextTemporalProfTraceData</a> (raw_fd_ostream &amp;OS, InstrProfSymtab &amp;Symtab)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write temporal profile trace data to the header in text format to <span class="doxyComputerOutput">OS</span>. <a href="#ab803c3548558a7dd296a3b2be2ef9773">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30e5f42e3c87128fe5530d937236c7b">validateRecord</a> (const InstrProfRecord &amp;Func)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb5997231c5c31ee92f0aec0807dbfb">writeBuffer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the profile, returning the raw data. For testing. <a href="#acbb5997231c5c31ee92f0aec0807dbfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3bfb53fa787d3dbea88bc35f498e461">mergeProfileKind</a> (const InstrProfKind Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the attributes of the current profile from the attributes specified. <a href="#aa3bfb53fa787d3dbea88bc35f498e461">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6">InstrProfKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf94a24c71cc9967ca8fd0b9b4ef5bf">getProfileKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9707029cf2b1e83ccbee02e3fd851a">hasSingleByteCoverage</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79fdf28a603e78b440613e2d0ea12919">setValueProfDataEndianness</a> (llvm::endianness Endianness)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5763fdd5ad3174639593cb6dc018f4d">setOutputSparse</a> (bool Sparse)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670e30844ea28837d8c9249f026111b3">setMemProfVersionRequested</a> (memprof::IndexedVersion Version)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2299f935ab595943d5498e9234f9012">setMemProfFullSchema</a> (bool Full)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2882c6d2a257083c160385fe493c0cf2">overlapRecord</a> (NamedInstrProfRecord &amp;&amp;Other, OverlapStats &amp;Overlap, OverlapStats &amp;FuncLevelOverlap, const OverlapFuncFilters &amp;FuncFilter)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3acd604bf7d17f43d19a2f3eb127d2b">addRecord</a> (StringRef Name, uint64_t Hash, InstrProfRecord &amp;&amp;I, uint64_t Weight, function_ref&lt; void(Error)&gt; Warn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54288b504bd672b06ff89a8f19cef82c">shouldEncodeData</a> (const ProfilingData &amp;PD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02eca83b2b5c9c9b365461599278008d">addTemporalProfileTrace</a> (TemporalProfTraceTy Trace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a></span> using reservoir sampling. <a href="#a02eca83b2b5c9c9b365461599278008d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c19161afc2a8ccad0071ce7d207ff8">addMemProfRecord</a> (const GlobalValue::GUID Id, const memprof::IndexedMemProfRecord &amp;Record)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a memprof record for a function identified by its <span class="doxyComputerOutput">Id</span>. <a href="#a54c19161afc2a8ccad0071ce7d207ff8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ebe6c95feb2a54d9c10e315be91ce0">addMemProfFrame</a> (const memprof::FrameId, const memprof::Frame &amp;F, function_ref&lt; void(Error)&gt; Warn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a memprof frame identified by the hash of the contents of the frame in <span class="doxyComputerOutput">FrameId</span>. <a href="#ad2ebe6c95feb2a54d9c10e315be91ce0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5d4e5b29605911a6885e0410354780">addMemProfCallStack</a> (const memprof::CallStackId CSId, const llvm::SmallVector&lt; memprof::FrameId &gt; &amp;CallStack, function_ref&lt; void(Error)&gt; Warn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a call stack identified by the hash of the contents of the call stack in <span class="doxyComputerOutput">CallStack</span>. <a href="#a7c5d4e5b29605911a6885e0410354780">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8260a74297ec19f8a13f2cb518c3af2">writeImpl</a> (ProfOStream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09af6c77825b78bf2f7d141bd1f9bbb">writeHeader</a> (const IndexedInstrProf::Header &amp;header, const bool WritePrevVersion, ProfOStream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2d782bce9594391774a186c186e40c">writeBinaryIds</a> (ProfOStream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1fc9fea50703f8f453f82279e59a01">writeVTableNames</a> (ProfOStream &amp;OS)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a410c6558fe8ec686bccef349fbcdb131">Sparse</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="#ab8307c49f2fa9f6b5d968b663105b5df">ProfilingData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3633e6228b395aff2d6f069907b947b0">FunctionData</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bacb955beb5c43a5af57892fd902600">MaxTemporalProfTraceLength</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum length of a single temporal profile trace. <a href="#a5bacb955beb5c43a5af57892fd902600">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21b13e2baa0953670f206071e68f96ce">TemporalProfTraceReservoirSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum number of stored temporal profile traces. <a href="#a21b13e2baa0953670f206071e68f96ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470fd866c8a7a1c5112ca99410034c37">TemporalProfTraceStreamSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The total number of temporal profile traces seen. <a href="#a470fd866c8a7a1c5112ca99410034c37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/temporalproftracety">TemporalProfTraceTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8a48e905931c9d421f7c700530fc84">TemporalProfTraces</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of temporal profile traces. <a href="#a9c8a48e905931c9d421f7c700530fc84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mt19937</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8848d2fe5a8725f8551a891d2baf207d">RNG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata">memprof::IndexedMemProfData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb0e6037c3d6b01a726f35bd628fe6d">MemProfData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a4304894bcf353bce5ba4d3dd7ff534d7">llvm::object::BuildID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72415a912620591e6b7289b608dfe5d0">BinaryIds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f0464ec50e6ccd812029fe7b36250d">VTableNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6">InstrProfKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af954a7d6f48fc5eb599a48b9ef298363">ProfileKind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a88183b946cc5f0e8c96b2e66e1c74a7e">InstrProfKind::Unknown</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait">InstrProfRecordWriterTrait</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c64e8d58c86e937a2183bf2e55fec49">InfoObj</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7513f31936cc2ca8f6df66fda71483">WritePrevVersion</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">memprof::IndexedVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f5c62c799635dc5090a85c23933f82">MemProfVersionRequested</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8a558f82a0d02c73b154b48e1ffa90">MemProfFullSchema</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf8299049ae2bb7c7b6aaaef341659cf">MemprofGenerateRandomHotness</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764569b7bb113502ca90fca3c07fa816">writeRecordInText</a> (StringRef Name, uint64_t Hash, const InstrProfRecord &amp;Counters, InstrProfSymtab &amp;Symtab, raw_fd_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/record">Record</a></span> in text format to <span class="doxyComputerOutput">OS</span>. <a href="#a764569b7bb113502ca90fca3c07fa816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ProfilingData {#ab8307c49f2fa9f6b5d968b663105b5df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfWriter::ProfilingData =  SmallDenseMap&lt;uint64_t, InstrProfRecord&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstrProfWriter() {#a13d08f898bf27f2ca8a20fe08e23b020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfWriter::InstrProfWriter (bool Sparse=false, uint64_t TemporalProfTraceReservoirSize=0, uint64_t MaxTemporalProfTraceLength=0, bool WritePrevVersion=false, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">memprof::IndexedVersion</a> MemProfVersionRequested=static_cast&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">memprof::IndexedVersion</a> &gt;(<a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a721d2b84586b0bc5723c14c390570f61">memprof::MinimumSupportedVersion</a>), bool MemProfFullSchema=false, bool MemprofGenerateRandomHotness=false, unsigned MemprofGenerateRandomHotnessSeed=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>.</p>


<p>Referenced by <a href="#a9e2a95d34ae51ccf31e320d36bb0516c">mergeRecordsFromWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InstrProfWriter() {#a98e0f9de2663ab52e28fb5e65535bf12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfWriter::~InstrProfWriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBinaryIds() {#a53b03d1480dc12839b1b66f2a1d69a79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::addBinaryIds (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a4304894bcf353bce5ba4d3dd7ff534d7">llvm::object::BuildID</a> &gt; BIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>.</p>


<p>Referenced by <a href="#a9e2a95d34ae51ccf31e320d36bb0516c">mergeRecordsFromWriter</a>.</p>

</div>
</div>

### addMemProfData() {#ade765798c3f446846b4c6771285a86b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrProfWriter::addMemProfData (<a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata">memprof::IndexedMemProfData</a> Incoming, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the entire MemProfData <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a></span> to the writer context.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### addRecord() {#a80159a6def7a74a85d5f0592abb07a65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::addRecord (<a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord">NamedInstrProfRecord</a> &amp;&amp; I, uint64_t Weight, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add function counts for the given function.</p>


<p>If there are already counts for this function and the hash and number of counts match, each counter is summed. Optionally scale counts by <span class="doxyComputerOutput">Weight</span>.</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="#a80159a6def7a74a85d5f0592abb07a65">addRecord</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a4aa5eeeefece7dc425c48f87e4668f1b">addRecord</a>, <a href="#a80159a6def7a74a85d5f0592abb07a65">addRecord</a> and <a href="#a9e2a95d34ae51ccf31e320d36bb0516c">mergeRecordsFromWriter</a>.</p>

</div>
</div>

### addRecord() {#a4aa5eeeefece7dc425c48f87e4668f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfWriter::addRecord (<a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord">NamedInstrProfRecord</a> &amp;&amp; I, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; Warn)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>


<p>References <a href="#a80159a6def7a74a85d5f0592abb07a65">addRecord</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### addTemporalProfileTraces() {#a2713b4a910e8cfdceb4114823a49123d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::addTemporalProfileTraces (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/temporalproftracety">TemporalProfTraceTy</a> &gt; &amp; SrcTraces, uint64_t SrcStreamSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add <span class="doxyComputerOutput">SrcTraces</span> using reservoir sampling where <span class="doxyComputerOutput">SrcStreamSize</span> is the total number of temporal profiling traces the source has seen.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a457abdc792a2b697c1031f09edb8492f">llvm::shuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/trace/#a76e72d971cfe4ce081116b6e7528e7db">llvm::Trace::size</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>


<p>Referenced by <a href="#a9e2a95d34ae51ccf31e320d36bb0516c">mergeRecordsFromWriter</a>.</p>

</div>
</div>

### addVTableName() {#a1ffa18a7702d5aee782d6e25a105ca8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfWriter::addVTableName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VTableName)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### getProfileData() {#ad880af71be857e7c4c8ee2b57cc9c2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt; ProfilingData &gt; &amp; llvm::InstrProfWriter::getProfileData ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### getProfileKind() {#a2cf94a24c71cc9967ca8fd0b9b4ef5bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfKind llvm::InstrProfWriter::getProfileKind ()</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### hasSingleByteCoverage() {#a0b9707029cf2b1e83ccbee02e3fd851a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfWriter::hasSingleByteCoverage ()</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a5505edfdbf5f7c9b5bd53a769be32faf">llvm::SingleByteCoverage</a>.</p>

</div>
</div>

### mergeProfileKind() {#aa3bfb53fa787d3dbea88bc35f498e461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfWriter::mergeProfileKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6">InstrProfKind</a> Other)</td>
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

<p>Update the attributes of the current profile from the attributes specified.</p>


<p>An error is returned if IR and FE profiles are mixed.</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a5b8e304d44bb4e39203ed9bc70168db9">llvm::FrontendInstrumentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a3d8a924372eb01d27427b757ba52d318">llvm::FunctionEntryInstrumentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a0e0f0e75dc57be5c12274ba6e78bc75a">llvm::FunctionEntryOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a2d0e271ef09b456a7c73384c7e787173">llvm::LoopEntriesInstrumentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2af01f2c39c66a1641045dd660e839b5">llvm::unsupported_version</a>.</p>

</div>
</div>

### mergeRecordsFromWriter() {#a9e2a95d34ae51ccf31e320d36bb0516c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::mergeRecordsFromWriter (<a href="/web-llvm/docs/api/classes/llvm/instrprofwriter">InstrProfWriter</a> &amp;&amp; IPW, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge existing function counts from the given writer.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="#a53b03d1480dc12839b1b66f2a1d69a79">addBinaryIds</a>, <a href="#a80159a6def7a74a85d5f0592abb07a65">addRecord</a>, <a href="#a2713b4a910e8cfdceb4114823a49123d">addTemporalProfileTraces</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a13d08f898bf27f2ca8a20fe08e23b020">InstrProfWriter</a>.</p>

</div>
</div>

### overlapRecord() {#a2882c6d2a257083c160385fe493c0cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::overlapRecord (<a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord">NamedInstrProfRecord</a> &amp;&amp; Other, <a href="/web-llvm/docs/api/structs/llvm/overlapstats">OverlapStats</a> &amp; Overlap, <a href="/web-llvm/docs/api/structs/llvm/overlapstats">OverlapStats</a> &amp; FuncLevelOverlap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/overlapfuncfilters">OverlapFuncFilters</a> &amp; FuncFilter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a0890bbfe709e212efce84003c8fb9469">llvm::OverlapStats::addOneMismatch</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a813dbcd2d37d971f1962238891728d87">llvm::OverlapStats::addOneUnique</a>, <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#aa86b18bf848839782dee252ea6871d00">llvm::CountSumOrPercent::CountSum</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapfuncfilters/#aa0caa29415e10ba9edbdd5e2ccfaa619">llvm::OverlapFuncFilters::NameFilter</a>, <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#ac6ee8e5f865571103ec74dd37837b70e">llvm::CountSumOrPercent::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a3427e5f987ace470105d11ad6c7a89a1">llvm::OverlapStats::Overlap</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ac9be35ce19db0a3b6de2350b5c2820f3">llvm::InstrProfRecord::overlap</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#aeacf37b436c25b1af9f22712417fef6c">llvm::OverlapStats::Test</a> and <a href="/web-llvm/docs/api/structs/llvm/overlapfuncfilters/#a6c46f67169d1a6984f7f07bea53d79b4">llvm::OverlapFuncFilters::ValueCutoff</a>.</p>

</div>
</div>

### setMemProfFullSchema() {#af2299f935ab595943d5498e9234f9012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfWriter::setMemProfFullSchema (bool Full)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad5b7ced2aa529c892b2219cd29b08760abbd47109890259c0127154db1af26c75">llvm::Full</a>.</p>

</div>
</div>

### setMemProfVersionRequested() {#a670e30844ea28837d8c9249f026111b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfWriter::setMemProfVersionRequested (<a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">memprof::IndexedVersion</a> Version)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

### setOutputSparse() {#ad5763fdd5ad3174639593cb6dc018f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::setOutputSparse (bool Sparse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### setValueProfDataEndianness() {#a79fdf28a603e78b440613e2d0ea12919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::setValueProfDataEndianness (<a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endianness)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### validateRecord() {#af30e5f42e3c87128fe5530d937236c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfWriter::validateRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086aca78730e8bc0cd42986be66e3f0dc14c">llvm::invalid_prof</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a2a76e869a218e271ec68f8a68968fde2">writeText</a>.</p>

</div>
</div>

### write() {#a20a49f43cb3ed032975144816e9884c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfWriter::write (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the profile to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 1030 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Referenced by <a href="#acbb5997231c5c31ee92f0aec0807dbfb">writeBuffer</a>.</p>

</div>
</div>

### write() {#a4ea67e7e8a34be965e9699bd9ecd885f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfWriter::write (<a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the profile to a string output stream <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### writeBuffer() {#acbb5997231c5c31ee92f0aec0807dbfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; InstrProfWriter::writeBuffer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the profile, returning the raw data. For testing.</p>

<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a> and <a href="#a20a49f43cb3ed032975144816e9884c5">write</a>.</p>

</div>
</div>

### writeText() {#a2a76e869a218e271ec68f8a68968fde2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfWriter::writeText (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the profile in text format to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#aab6da5958ec329a4ea11683d414e8366">llvm::InstrProfSymtab::addFuncName</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#a6e42074180a160835f3222c6d6017fc1">llvm::InstrProfSymtab::addVTableName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a087151dc0bb6ff33db94d0479b6bc2cf">llvm::ContextSensitive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a3d8a924372eb01d27427b757ba52d318">llvm::FunctionEntryInstrumentation</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a51056965b635025ecb4cdafb28bc1ae2">llvm::IRInstrumentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a2d0e271ef09b456a7c73384c7e787173">llvm::LoopEntriesInstrumentation</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a5505edfdbf5f7c9b5bd53a769be32faf">llvm::SingleByteCoverage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a3ef3ba43212f6a2779d594e507451d54">llvm::TemporalProfile</a>, <a href="#af30e5f42e3c87128fe5530d937236c7b">validateRecord</a>, <a href="#a764569b7bb113502ca90fca3c07fa816">writeRecordInText</a> and <a href="#ab803c3548558a7dd296a3b2be2ef9773">writeTextTemporalProfTraceData</a>.</p>

</div>
</div>

### writeTextTemporalProfTraceData() {#ab803c3548558a7dd296a3b2be2ef9773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::writeTextTemporalProfTraceData (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp; Symtab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write temporal profile trace data to the header in text format to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#a4368b520bb5883d23d6c2c59bf129b5a">llvm::InstrProfSymtab::getFuncOrVarName</a>.</p>


<p>Referenced by <a href="#a2a76e869a218e271ec68f8a68968fde2">writeText</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addMemProfCallStack() {#a7c5d4e5b29605911a6885e0410354780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrProfWriter::addMemProfCallStack (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">memprof::CallStackId</a> CSId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a> &gt; &amp; CallStack, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a call stack identified by the hash of the contents of the call stack in <span class="doxyComputerOutput">CallStack</span>.</p>

<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### addMemProfFrame() {#ad2ebe6c95feb2a54d9c10e315be91ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrProfWriter::addMemProfFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/frame">memprof::Frame</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a memprof frame identified by the hash of the contents of the frame in <span class="doxyComputerOutput">FrameId</span>.</p>

<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### addMemProfRecord() {#a54c19161afc2a8ccad0071ce7d207ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::addMemProfRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord">memprof::IndexedMemProfRecord</a> &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a memprof record for a function identified by its <span class="doxyComputerOutput">Id</span>.</p>

<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### addRecord() {#af3acd604bf7d17f43d19a2f3eb127d2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::addRecord (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Hash, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp;&amp; I, uint64_t Weight, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### addTemporalProfileTrace() {#a02eca83b2b5c9c9b365461599278008d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::addTemporalProfileTrace (<a href="/web-llvm/docs/api/structs/llvm/temporalproftracety">TemporalProfTraceTy</a> Trace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a></span> using reservoir sampling.</p>

<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### shouldEncodeData() {#a54288b504bd672b06ff89a8f19cef82c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrProfWriter::shouldEncodeData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8307c49f2fa9f6b5d968b663105b5df">ProfilingData</a> &amp; PD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### writeBinaryIds() {#a5c2d782bce9594391774a186c186e40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfWriter::writeBinaryIds (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### writeHeader() {#ad09af6c77825b78bf2f7d141bd1f9bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t InstrProfWriter::writeHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/header">IndexedInstrProf::Header</a> &amp; header, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool WritePrevVersion, <a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 792 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### writeImpl() {#ad8260a74297ec19f8a13f2cb518c3af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfWriter::writeImpl (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### writeVTableNames() {#a5c1fc9fea50703f8f453f82279e59a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfWriter::writeVTableNames (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BinaryIds {#a72415a912620591e6b7289b608dfe5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;llvm::object::BuildID&gt; llvm::InstrProfWriter::BinaryIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### FunctionData {#a3633e6228b395aff2d6f069907b947b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;ProfilingData&gt; llvm::InstrProfWriter::FunctionData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### InfoObj {#a0c64e8d58c86e937a2183bf2e55fec49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfRecordWriterTrait* llvm::InstrProfWriter::InfoObj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### MaxTemporalProfTraceLength {#a5bacb955beb5c43a5af57892fd902600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstrProfWriter::MaxTemporalProfTraceLength</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum length of a single temporal profile trace.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### MemProfData {#aceb0e6037c3d6b01a726f35bd628fe6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">memprof::IndexedMemProfData llvm::InstrProfWriter::MemProfData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### MemProfFullSchema {#aea8a558f82a0d02c73b154b48e1ffa90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfWriter::MemProfFullSchema</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### MemprofGenerateRandomHotness {#adf8299049ae2bb7c7b6aaaef341659cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfWriter::MemprofGenerateRandomHotness</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### MemProfVersionRequested {#af6f5c62c799635dc5090a85c23933f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">memprof::IndexedVersion llvm::InstrProfWriter::MemProfVersionRequested</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### ProfileKind {#af954a7d6f48fc5eb599a48b9ef298363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfKind llvm::InstrProfWriter::ProfileKind = <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a88183b946cc5f0e8c96b2e66e1c74a7e">InstrProfKind::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### RNG {#a8848d2fe5a8725f8551a891d2baf207d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mt19937 llvm::InstrProfWriter::RNG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### Sparse {#a410c6558fe8ec686bccef349fbcdb131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfWriter::Sparse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### TemporalProfTraceReservoirSize {#a21b13e2baa0953670f206071e68f96ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstrProfWriter::TemporalProfTraceReservoirSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum number of stored temporal profile traces.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### TemporalProfTraces {#a9c8a48e905931c9d421f7c700530fc84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TemporalProfTraceTy&gt; llvm::InstrProfWriter::TemporalProfTraces</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of temporal profile traces.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### TemporalProfTraceStreamSize {#a470fd866c8a7a1c5112ca99410034c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstrProfWriter::TemporalProfTraceStreamSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The total number of temporal profile traces seen.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### VTableNames {#a45f0464ec50e6ccd812029fe7b36250d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::InstrProfWriter::VTableNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

### WritePrevVersion {#a4e7513f31936cc2ca8f6df66fda71483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfWriter::WritePrevVersion = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### writeRecordInText() {#a764569b7bb113502ca90fca3c07fa816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfWriter::writeRecordInText (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Hash, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; Counters, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp; Symtab, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS)</td>
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

<p>Write <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/record">Record</a></span> in text format to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a>, definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#af7fa5af32e8d5c5142f7a39ae905681b">llvm::InstrProfSymtab::getFuncOrVarNameIfDefined</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#adf31c7df7985f80e2f58bbec89c8e5c6">ValueProfKindStr</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a37b5dd8a8b82f2818e0f4ea9699d8ae5">llvm::raw_ostream::write_hex</a>.</p>


<p>Referenced by <a href="#a2a76e869a218e271ec68f8a68968fde2">writeText</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">InstrProfWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
