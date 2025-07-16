---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/profiledata/instrprofwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `InstrProfWriter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofwriter-h">llvm/ProfileData/InstrProfWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profilesummary-h">llvm/IR/ProfileSummary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">llvm/ProfileData/MemProf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">llvm/ProfileData/ProfileCommon.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">llvm/Support/Compression.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">llvm/Support/OnDiskHashTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cstdint&gt;
#include &lt;ctime&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
#include "llvm/ProfileData/InstrProfData.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/patchitem">PatchItem</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait">InstrProfRecordWriterTrait</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31ee60a35ad56fd833b926a75756a33">setSummary</a> (IndexedInstrProf::Summary *TheSummary, ProfileSummary &amp;PS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe089e351de37cd105f3fae18a0bd13e">writeMemProfSchema</a> (ProfOStream &amp;OS, const memprof::MemProfSchema &amp;Schema)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38203c3ce4c256dc041166735c6e007e">writeMemProfRecords</a> (ProfOStream &amp;OS, llvm::MapVector&lt; GlobalValue::GUID, memprof::IndexedMemProfRecord &gt; &amp;MemProfRecordData, memprof::MemProfSchema *Schema, memprof::IndexedVersion Version, llvm::DenseMap&lt; memprof::CallStackId, memprof::LinearCallStackId &gt; *MemProfCallStackIndexes=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953c955a410efd221c0a76d209891718">writeMemProfFrames</a> (ProfOStream &amp;OS, llvm::MapVector&lt; memprof::FrameId, memprof::Frame &gt; &amp;MemProfFrameData)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ac8f2e9a6f336bcafc02bbe895a6bf6db">memprof::LinearFrameId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0bb182de61b858a03a99b3ea2662e1c">writeMemProfFrameArray</a> (ProfOStream &amp;OS, llvm::MapVector&lt; memprof::FrameId, memprof::Frame &gt; &amp;MemProfFrameData, llvm::DenseMap&lt; memprof::FrameId, memprof::FrameStat &gt; &amp;FrameHistogram)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433aa7814d2ec5eb3ff767522fcceef9">writeMemProfCallStacks</a> (ProfOStream &amp;OS, llvm::MapVector&lt; memprof::CallStackId, llvm::SmallVector&lt; memprof::FrameId &gt; &gt; &amp;MemProfCallStackData)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">memprof::CallStackId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a271f954222d61bd5dc7f5cb5dd836b52">memprof::LinearCallStackId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab055eb88701395ca69a88d4958bc2fda">writeMemProfCallStackArray</a> (ProfOStream &amp;OS, llvm::MapVector&lt; memprof::CallStackId, llvm::SmallVector&lt; memprof::FrameId &gt; &gt; &amp;MemProfCallStackData, llvm::DenseMap&lt; memprof::FrameId, memprof::LinearFrameId &gt; &amp;MemProfFrameIndexes, llvm::DenseMap&lt; memprof::FrameId, memprof::FrameStat &gt; &amp;FrameHistogram, unsigned &amp;NumElements)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a> (ProfOStream &amp;OS, memprof::IndexedMemProfData &amp;MemProfData, bool MemProfFullSchema)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a> (ProfOStream &amp;OS, memprof::IndexedMemProfData &amp;MemProfData, bool MemProfFullSchema)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42c6d1bc93da90ac48e60891f9ea18a8">writeMemProf</a> (ProfOStream &amp;OS, memprof::IndexedMemProfData &amp;MemProfData, memprof::IndexedVersion MemProfVersionRequested, bool MemProfFullSchema)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf31c7df7985f80e2f58bbec89c8e5c6">ValueProfKindStr</a>[]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2558cb097460e2dfa5315ec18c38c24">VALUE_PROF_KIND</a>(Enumerator, Value, Descr)&nbsp;&nbsp;&nbsp;#Enumerator,</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a991a4b9fc0060d2c13c2609e8dbd5c48">INSTR_PROF_VISIBILITY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a964fe748db42abb3035346a85f7aa3b9">INSTR_PROF_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fffbf1bcdf0b73994e7d71af9fda706">INSTR_PROF_VTABLE_DATA</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2039a5308a9a7aecdfc29f45d1a04fb7">INSTR_PROF_VALUE_NODE</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05e05e47a5f9945cf30597645458686">INSTR_PROF_RAW_HEADER</a>(Type, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b37e795b394a273b4adca2984d0c5c">VALUE_PROF_FUNC_PARAM</a>(ArgType, ArgName, ArgLLVMType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec3bc606baecfea5832789f9b4f998b">INSTR_PROF_COMMA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461567c719c6f8cd15517aec497c5ecf">INSTR_PROF_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b82a7fc9ea6b68d597e54245e85f21b">COVMAP_FUNC_RECORD</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac825b81edfa1cf2df4102c9c34f821e4">COVMAP_HEADER</a>(Type, LLVMType, Name, Initializer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0af632e6ce572cbccbe06f3cd5383e2">COVINIT_FUNC</a>(Type, LLVMType, Name, Initializer)</td>
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

### setSummary() {#ad31ee60a35ad56fd833b926a75756a33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setSummary (<a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary">IndexedInstrProf::Summary</a> * TheSummary, <a href="/web-llvm/docs/api/classes/llvm/profilesummary">ProfileSummary</a> &amp; PS)</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#a4030ad50199dc5c1adbf493beceab78c">llvm::ProfileSummary::getDetailedSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#a2b45f7c069fb55743e90cbd537ba3b0b">llvm::ProfileSummary::getMaxCount</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#ad64584022a9d193863c23f34527e52a0">llvm::ProfileSummary::getMaxFunctionCount</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#ab649e13a65d0e348612e3c5dc1b1d8d3">llvm::ProfileSummary::getMaxInternalCount</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#a7864c742b9f788e7f134832a80366dbc">llvm::ProfileSummary::getNumCounts</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#af697b9e7a965496ebb3cef13024041bf">llvm::ProfileSummary::getNumFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#a04347cbb2c52c51b44f7b7b91bb71686">llvm::ProfileSummary::getTotalCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary/#af2fabcffb86d5bb25c5e29970b37f87c">llvm::IndexedInstrProf::Summary::NumCutoffEntries</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary/#adb3d2713c181ce6c6c40511be19b88c0">llvm::IndexedInstrProf::Summary::NumSummaryFields</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary/#a50cf43c1108f78da3a26adbafeb86c23">llvm::IndexedInstrProf::Summary::set</a> and <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary/#a55a5013634d7fc600f627e0870a52511">llvm::IndexedInstrProf::Summary::setEntry</a>.</p>

</div>
</div>

### writeMemProf() {#a42c6d1bc93da90ac48e60891f9ea18a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error writeMemProf (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata">memprof::IndexedMemProfData</a> &amp; MemProfData, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">memprof::IndexedVersion</a> MemProfVersionRequested, bool MemProfFullSchema)</td>
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



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a229923f8cb950f9899eb443578242800">llvm::memprof::MaximumSupportedVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a721d2b84586b0bc5723c14c390570f61">llvm::memprof::MinimumSupportedVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2af01f2c39c66a1641045dd660e839b5">llvm::unsupported_version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbaa4580b818c5644cc40399914cc86c227">llvm::memprof::Version2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>, <a href="#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a> and <a href="#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a>.</p>

</div>
</div>

### writeMemProfCallStackArray() {#ab055eb88701395ca69a88d4958bc2fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenseMap&lt; memprof::CallStackId, memprof::LinearCallStackId &gt; writeMemProfCallStackArray (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">memprof::CallStackId</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a> &gt; &gt; &amp; MemProfCallStackData, <a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ac8f2e9a6f336bcafc02bbe895a6bf6db">memprof::LinearFrameId</a> &gt; &amp; MemProfFrameIndexes, <a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/framestat">memprof::FrameStat</a> &gt; &amp; FrameHistogram, unsigned &amp; NumElements)</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memprof/callstackradixtreebuilder/#a05db798ae8ae11328fce938cd0d012f9">llvm::memprof::CallStackRadixTreeBuilder&lt; FrameIdTy &gt;::build</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstackradixtreebuilder/#a952877a78325a5e2a3b1bd8cf623bb9b">llvm::memprof::CallStackRadixTreeBuilder&lt; FrameIdTy &gt;::getRadixArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstackradixtreebuilder/#ae5227f60eb0adb26e24a3d08457af5a5">llvm::memprof::CallStackRadixTreeBuilder&lt; FrameIdTy &gt;::takeCallStackPos</a> and <a href="/web-llvm/docs/api/classes/llvm/profostream/#aa2268681061e7755f52d4014f75071ce">llvm::ProfOStream::write32</a>.</p>


<p>Referenced by <a href="#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a>.</p>

</div>
</div>

### writeMemProfCallStacks() {#a433aa7814d2ec5eb3ff767522fcceef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t writeMemProfCallStacks (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">memprof::CallStackId</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a> &gt; &gt; &amp; MemProfCallStackData)</td>
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



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#a6004e80d1127db853be23ecabf61109e">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::Emit</a> and <a href="/web-llvm/docs/api/classes/llvm/profostream/#a0b9a2017697fb95a906f7d5259e3420d">llvm::ProfOStream::OS</a>.</p>


<p>Referenced by <a href="#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a>.</p>

</div>
</div>

### writeMemProfFrameArray() {#ae0bb182de61b858a03a99b3ea2662e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenseMap&lt; memprof::FrameId, memprof::LinearFrameId &gt; writeMemProfFrameArray (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/frame">memprof::Frame</a> &gt; &amp; MemProfFrameData, <a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/framestat">memprof::FrameStat</a> &gt; &amp; FrameHistogram)</td>
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



<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#ae091b147039557cf8ce505740e7ff7ac">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#a0b9a2017697fb95a906f7d5259e3420d">llvm::ProfOStream::OS</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#ae292a4b96e7f74eb95a4176ddba7b821">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#acf4c09e1f30cdd4e0b5b1b8a236ead34">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a>.</p>

</div>
</div>

### writeMemProfFrames() {#a953c955a410efd221c0a76d209891718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t writeMemProfFrames (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">memprof::FrameId</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/frame">memprof::Frame</a> &gt; &amp; MemProfFrameData)</td>
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



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mapvector/#ae091b147039557cf8ce505740e7ff7ac">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#a6004e80d1127db853be23ecabf61109e">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::Emit</a> and <a href="/web-llvm/docs/api/classes/llvm/profostream/#a0b9a2017697fb95a906f7d5259e3420d">llvm::ProfOStream::OS</a>.</p>


<p>Referenced by <a href="#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a>.</p>

</div>
</div>

### writeMemProfRecords() {#a38203c3ce4c256dc041166735c6e007e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t writeMemProfRecords (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord">memprof::IndexedMemProfRecord</a> &gt; &amp; MemProfRecordData, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">memprof::MemProfSchema</a> * Schema, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">memprof::IndexedVersion</a> Version, <a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">memprof::CallStackId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a271f954222d61bd5dc7f5cb5dd836b52">memprof::LinearCallStackId</a> &gt; * MemProfCallStackIndexes=nullptr)</td>
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



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mapvector/#ae091b147039557cf8ce505740e7ff7ac">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#a6004e80d1127db853be23ecabf61109e">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#a0b9a2017697fb95a906f7d5259e3420d">llvm::ProfOStream::OS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a> and <a href="#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a>.</p>

</div>
</div>

### writeMemProfSchema() {#afe089e351de37cd105f3fae18a0bd13e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeMemProfSchema (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">memprof::MemProfSchema</a> &amp; Schema)</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/profostream/#afb709e9ed0068ee21ae3bc153f5bef68">llvm::ProfOStream::write</a>.</p>


<p>Referenced by <a href="#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a> and <a href="#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a>.</p>

</div>
</div>

### writeMemProfV2() {#ac9e41242e334c46de6b89a79135b8ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error writeMemProfV2 (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata">memprof::IndexedMemProfData</a> &amp; MemProfData, bool MemProfFullSchema)</td>
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



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata/#a9c8a3dfd356ab2eb76f576f3f84de5dd">llvm::memprof::IndexedMemProfData::CallStacks</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata/#ae93d8c26ba2bca1d65a5613a611f9ba3">llvm::memprof::IndexedMemProfData::Frames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#aa4e49c91a6b2f7fef6298991217c929d">llvm::memprof::getFullSchema</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a34511491f5ee54fd1db6b472d9daf333">llvm::memprof::getHotColdSchema</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#a52299b07451a31e9fc5a62e305d5fe21">llvm::ProfOStream::patch</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata/#abc9decb5c94d07b0d4c4691bb1c830f4">llvm::memprof::IndexedMemProfData::Records</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#a191995415d5b2e7ca2709b6cd8dad00e">llvm::ProfOStream::tell</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbaa4580b818c5644cc40399914cc86c227">llvm::memprof::Version2</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#afb709e9ed0068ee21ae3bc153f5bef68">llvm::ProfOStream::write</a>, <a href="#a433aa7814d2ec5eb3ff767522fcceef9">writeMemProfCallStacks</a>, <a href="#a953c955a410efd221c0a76d209891718">writeMemProfFrames</a>, <a href="#a38203c3ce4c256dc041166735c6e007e">writeMemProfRecords</a> and <a href="#afe089e351de37cd105f3fae18a0bd13e">writeMemProfSchema</a>.</p>


<p>Referenced by <a href="#a42c6d1bc93da90ac48e60891f9ea18a8">writeMemProf</a>.</p>

</div>
</div>

### writeMemProfV3() {#a8cad3eb0bfb43723ba5976243ec78090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error writeMemProfV3 (<a href="/web-llvm/docs/api/classes/llvm/profostream">ProfOStream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata">memprof::IndexedMemProfData</a> &amp; MemProfData, bool MemProfFullSchema)</td>
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



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata/#a9c8a3dfd356ab2eb76f576f3f84de5dd">llvm::memprof::IndexedMemProfData::CallStacks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#af4e5be1dedc37673f64259d9247369c2">llvm::memprof::computeFrameHistogram</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata/#ae93d8c26ba2bca1d65a5613a611f9ba3">llvm::memprof::IndexedMemProfData::Frames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#aa4e49c91a6b2f7fef6298991217c929d">llvm::memprof::getFullSchema</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a34511491f5ee54fd1db6b472d9daf333">llvm::memprof::getHotColdSchema</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#a52299b07451a31e9fc5a62e305d5fe21">llvm::ProfOStream::patch</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata/#abc9decb5c94d07b0d4c4691bb1c830f4">llvm::memprof::IndexedMemProfData::Records</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#a191995415d5b2e7ca2709b6cd8dad00e">llvm::ProfOStream::tell</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#afb709e9ed0068ee21ae3bc153f5bef68">llvm::ProfOStream::write</a>, <a href="#ab055eb88701395ca69a88d4958bc2fda">writeMemProfCallStackArray</a>, <a href="#ae0bb182de61b858a03a99b3ea2662e1c">writeMemProfFrameArray</a>, <a href="#a38203c3ce4c256dc041166735c6e007e">writeMemProfRecords</a> and <a href="#afe089e351de37cd105f3fae18a0bd13e">writeMemProfSchema</a>.</p>


<p>Referenced by <a href="#a42c6d1bc93da90ac48e60891f9ea18a8">writeMemProf</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ValueProfKindStr {#adf31c7df7985f80e2f58bbec89c8e5c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* ValueProfKindStr[]</td>
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



<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a764569b7bb113502ca90fca3c07fa816">llvm::InstrProfWriter::writeRecordInText</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### COVINIT\_FUNC {#ae0af632e6ce572cbccbe06f3cd5383e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVINIT_FUNC(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_FUNC\_RECORD {#a4b82a7fc9ea6b68d597e54245e85f21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_FUNC_RECORD(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file InstrProfData.inc.</p>

</div>
</div>

### COVMAP\_HEADER {#ac825b81edfa1cf2df4102c9c34f821e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COVMAP_HEADER(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_COMMA {#a9ec3bc606baecfea5832789f9b4f998b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_COMMA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA {#a964fe748db42abb3035346a85f7aa3b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA\_DEFINED {#a461567c719c6f8cd15517aec497c5ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_RAW\_HEADER {#af05e05e47a5f9945cf30597645458686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_RAW_HEADER(Type, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VALUE\_NODE {#a2039a5308a9a7aecdfc29f45d1a04fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VALUE_NODE(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VISIBILITY {#a991a4b9fc0060d2c13c2609e8dbd5c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VISIBILITY</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VTABLE\_DATA {#a9fffbf1bcdf0b73994e7d71af9fda706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_PROF_VTABLE_DATA(Type, LLVMType, Name, Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file InstrProfData.inc.</p>

</div>
</div>

### VALUE\_PROF\_FUNC\_PARAM {#ad7b37e795b394a273b4adca2984d0c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_FUNC_PARAM(ArgType, ArgName, ArgLLVMType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file InstrProfData.inc.</p>

</div>
</div>

### VALUE\_PROF\_KIND {#ae2558cb097460e2dfa5315ec18c38c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VALUE_PROF_KIND(Enumerator, Value, Descr)&nbsp;&nbsp;&nbsp;#Enumerator,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
