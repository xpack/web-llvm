---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/debugcounter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DebugCounter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DebugCounter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">llvm/Support/DebugCounter.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugcounter-cpp-/debugcounterowner">DebugCounterOwner</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/uniquevector">UniqueVector</a>&lt; std::string &gt; <a href="#a90ec8b395d535fd1335f0604cc18967c">CounterVector</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67552a8bdd1bd0df687842c7acf3efa3">push_back</a> (const std::string &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8cb43b6edd4b61f20a6f3264c3cc562">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad575354f42dae4499a5cf49177e8bdca">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74366ade377a1789f0427fc53dff6142">getCounterId</a> (const std::string &amp;Name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc8ca430d57b8617b681583975184180">getNumCounters</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; std::string, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674cbf881f2f3461e1c80bc3511eb8df">getCounterInfo</a> (unsigned ID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/uniquevector/#a008e639d554c69f4dad910cb9414208f">CounterVector::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aab40d1ff287d262e2ac5bf907bd4f3">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/uniquevector/#a008e639d554c69f4dad910cb9414208f">CounterVector::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34afbcefde648411e981d082f05bad4f">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a7d658467244eae745170838e92b3ee">addCounter</a> (const std::string &amp;Name, const std::string &amp;Desc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/debugcounter/counterinfo">CounterInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4712c75e0db127bb34154532b8fe8557">Counters</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a90ec8b395d535fd1335f0604cc18967c">CounterVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6254547abf5f544643098984650605ce">RegisteredCounters</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e16c989dc10f4b275ef398fbceb5837">Enabled</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9070d3561a7e94cb9ac92e9f6fa76783">ShouldPrintCounter</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52574a8c1b845df5c78d5a837a180f10">BreakOnLast</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a6098da614f4229dee3de0432aa83a">printChunks</a> (raw_ostream &amp;OS, ArrayRef&lt; Chunk &gt;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b40dda7a09e0c055d6138b404d0789">parseChunks</a> (StringRef Str, SmallVector&lt; Chunk &gt; &amp;Res)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true on parsing error and print the error message on the <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs()</a> <a href="#aa7b40dda7a09e0c055d6138b404d0789">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/debugcounter">DebugCounter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4330a5f1dff21ba1f4be59381832358">instance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the singleton instance. <a href="#ac4330a5f1dff21ba1f4be59381832358">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b490fa3426ad84d3956e05b09527a94">registerCounter</a> (StringRef Name, StringRef Desc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d21bcbf03ef9764e4363ae385d99579">shouldExecuteImpl</a> (unsigned CounterName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aace8653ce3726ef07194dcf6bce2bf">shouldExecute</a> (unsigned CounterName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50989c336e006eb7f8c168f04dbb32a4">isCounterSet</a> (unsigned ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/debugcounter/counterstate">CounterState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d24b64f2ea133f1848cea74562fabe8">getCounterState</a> (unsigned ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6101c8bdaddab8e9f6bbb138486230b">setCounterState</a> (unsigned ID, CounterState State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02d659d768b5a98297800f6f73d816c">enableAllCounters</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69784654584ad4bff747432cac8c4f88">isCountingEnabled</a> ()</td>
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


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CounterVector {#a90ec8b395d535fd1335f0604cc18967c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef UniqueVector&lt;std::string&gt; llvm::DebugCounter::CounterVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a3aab40d1ff287d262e2ac5bf907bd4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterVector::const_iterator llvm::DebugCounter::begin ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>Reference <a href="#a6254547abf5f544643098984650605ce">RegisteredCounters</a>.</p>

</div>
</div>

### dump() {#ad8cb43b6edd4b61f20a6f3264c3cc562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void DebugCounter::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/support/debugcounter-cpp">DebugCounter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ad575354f42dae4499a5cf49177e8bdca">print</a>.</p>

</div>
</div>

### end() {#a34afbcefde648411e981d082f05bad4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterVector::const_iterator llvm::DebugCounter::end ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>Reference <a href="#a6254547abf5f544643098984650605ce">RegisteredCounters</a>.</p>

</div>
</div>

### getCounterId() {#a74366ade377a1789f0427fc53dff6142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DebugCounter::getCounterId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>Reference <a href="#a6254547abf5f544643098984650605ce">RegisteredCounters</a>.</p>


<p>Referenced by <a href="#ad575354f42dae4499a5cf49177e8bdca">print</a> and <a href="#a67552a8bdd1bd0df687842c7acf3efa3">push_back</a>.</p>

</div>
</div>

### getCounterInfo() {#a674cbf881f2f3461e1c80bc3511eb8df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; std::string, std::string &gt; llvm::DebugCounter::getCounterInfo (unsigned ID)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>References <a href="#a4712c75e0db127bb34154532b8fe8557">Counters</a> and <a href="#a6254547abf5f544643098984650605ce">RegisteredCounters</a>.</p>

</div>
</div>

### getNumCounters() {#afc8ca430d57b8617b681583975184180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::DebugCounter::getNumCounters ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>Reference <a href="#a6254547abf5f544643098984650605ce">RegisteredCounters</a>.</p>

</div>
</div>

### print() {#ad575354f42dae4499a5cf49177e8bdca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugCounter::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/support/debugcounter-cpp">DebugCounter.cpp</a>.</p>


<p>References <a href="#a74366ade377a1789f0427fc53dff6142">getCounterId</a>, <a href="#ac4330a5f1dff21ba1f4be59381832358">instance</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5b1b4e94f62050dd1bccb48141ef4b9">llvm::left_justify</a>, <a href="#a21a6098da614f4229dee3de0432aa83a">printChunks</a>, <a href="#a6254547abf5f544643098984650605ce">RegisteredCounters</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#ad8cb43b6edd4b61f20a6f3264c3cc562">dump</a>.</p>

</div>
</div>

### push\_back() {#a67552a8bdd1bd0df687842c7acf3efa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugCounter::push_back (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/support/debugcounter-cpp">DebugCounter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/debugcounter/counterinfo/#aff89add25cfd93a5d70ce601bc95d813">llvm::DebugCounter::CounterInfo::Chunks</a>, <a href="#a4712c75e0db127bb34154532b8fe8557">Counters</a>, <a href="#aa02d659d768b5a98297800f6f73d816c">enableAllCounters</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a74366ade377a1789f0427fc53dff6142">getCounterId</a>, <a href="/web-llvm/docs/api/structs/llvm/debugcounter/counterinfo/#a774a4ba443fc381cf5cc400cb490b45e">llvm::DebugCounter::CounterInfo::IsSet</a>, <a href="#aa7b40dda7a09e0c055d6138b404d0789">parseChunks</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addCounter() {#a9a7d658467244eae745170838e92b3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DebugCounter::addCounter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Desc)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>References <a href="#a4712c75e0db127bb34154532b8fe8557">Counters</a> and <a href="#a6254547abf5f544643098984650605ce">RegisteredCounters</a>.</p>


<p>Referenced by <a href="#a8b490fa3426ad84d3956e05b09527a94">registerCounter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BreakOnLast {#a52574a8c1b845df5c78d5a837a180f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugCounter::BreakOnLast = false</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>

</div>
</div>

### Counters {#a4712c75e0db127bb34154532b8fe8557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, CounterInfo&gt; llvm::DebugCounter::Counters</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>Referenced by <a href="#a9a7d658467244eae745170838e92b3ee">addCounter</a>, <a href="#a674cbf881f2f3461e1c80bc3511eb8df">getCounterInfo</a>, <a href="#a50989c336e006eb7f8c168f04dbb32a4">isCounterSet</a> and <a href="#a67552a8bdd1bd0df687842c7acf3efa3">push_back</a>.</p>

</div>
</div>

### Enabled {#a7e16c989dc10f4b275ef398fbceb5837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugCounter::Enabled = false</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>Referenced by <a href="#aa02d659d768b5a98297800f6f73d816c">enableAllCounters</a> and <a href="#a69784654584ad4bff747432cac8c4f88">isCountingEnabled</a>.</p>

</div>
</div>

### RegisteredCounters {#a6254547abf5f544643098984650605ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterVector llvm::DebugCounter::RegisteredCounters</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>Referenced by <a href="#a9a7d658467244eae745170838e92b3ee">addCounter</a>, <a href="#a3aab40d1ff287d262e2ac5bf907bd4f3">begin</a>, <a href="#a34afbcefde648411e981d082f05bad4f">end</a>, <a href="#a74366ade377a1789f0427fc53dff6142">getCounterId</a>, <a href="#a674cbf881f2f3461e1c80bc3511eb8df">getCounterInfo</a>, <a href="#afc8ca430d57b8617b681583975184180">getNumCounters</a> and <a href="#ad575354f42dae4499a5cf49177e8bdca">print</a>.</p>

</div>
</div>

### ShouldPrintCounter {#a9070d3561a7e94cb9ac92e9f6fa76783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugCounter::ShouldPrintCounter = false</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>Referenced by <a href="#a69784654584ad4bff747432cac8c4f88">isCountingEnabled</a> and <a href="/web-llvm/docs/api/structs/anonymous-debugcounter-cpp-/debugcounterowner/#acd9a1f60cb5cc2cbcb22d4bb89e677d6">anonymous{DebugCounter.cpp}::DebugCounterOwner::~DebugCounterOwner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### enableAllCounters() {#aa02d659d768b5a98297800f6f73d816c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DebugCounter::enableAllCounters ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>References <a href="#a7e16c989dc10f4b275ef398fbceb5837">Enabled</a> and <a href="#ac4330a5f1dff21ba1f4be59381832358">instance</a>.</p>


<p>Referenced by <a href="#a67552a8bdd1bd0df687842c7acf3efa3">push_back</a>.</p>

</div>
</div>

### getCounterState() {#a1d24b64f2ea133f1848cea74562fabe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterState llvm::DebugCounter::getCounterState (unsigned ID)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac4330a5f1dff21ba1f4be59381832358">instance</a>.</p>

</div>
</div>

### instance() {#ac4330a5f1dff21ba1f4be59381832358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugCounter &amp; DebugCounter::instance ()</td>
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

<p>Returns a reference to the singleton instance.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/support/debugcounter-cpp">DebugCounter.cpp</a>.</p>


<p>Referenced by <a href="#aa02d659d768b5a98297800f6f73d816c">enableAllCounters</a>, <a href="#a1d24b64f2ea133f1848cea74562fabe8">getCounterState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4c8865e5ec32b9608c5ac5edba951767">llvm::initDebugCounterOptions</a>, <a href="#a50989c336e006eb7f8c168f04dbb32a4">isCounterSet</a>, <a href="#a69784654584ad4bff747432cac8c4f88">isCountingEnabled</a>, <a href="#ad575354f42dae4499a5cf49177e8bdca">print</a>, <a href="#a8b490fa3426ad84d3956e05b09527a94">registerCounter</a>, <a href="#af6101c8bdaddab8e9f6bbb138486230b">setCounterState</a> and <a href="#a7d21bcbf03ef9764e4363ae385d99579">shouldExecuteImpl</a>.</p>

</div>
</div>

### isCounterSet() {#a50989c336e006eb7f8c168f04dbb32a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugCounter::isCounterSet (unsigned ID)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>References <a href="#a4712c75e0db127bb34154532b8fe8557">Counters</a> and <a href="#ac4330a5f1dff21ba1f4be59381832358">instance</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a90a2b453bf3ce25f979403d9d95c7070">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::setForceEmitWaitcnt</a>.</p>

</div>
</div>

### isCountingEnabled() {#a69784654584ad4bff747432cac8c4f88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugCounter::isCountingEnabled ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>References <a href="#a7e16c989dc10f4b275ef398fbceb5837">Enabled</a>, <a href="#ac4330a5f1dff21ba1f4be59381832358">instance</a> and <a href="#a9070d3561a7e94cb9ac92e9f6fa76783">ShouldPrintCounter</a>.</p>


<p>Referenced by <a href="#a5aace8653ce3726ef07194dcf6bce2bf">shouldExecute</a>.</p>

</div>
</div>

### parseChunks() {#aa7b40dda7a09e0c055d6138b404d0789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugCounter::parseChunks (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/debugcounter/chunk">Chunk</a> &gt; &amp; Res)</td>
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

<p>Return true on parsing error and print the error message on the <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs()</a></p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/support/debugcounter-cpp">DebugCounter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfab2ee912b91d69b435159c7c3f6df7f5f">llvm::Number</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa93bf2cc29b3a2ad5056bea30a373d52">llvm::StringRef::take_until</a>.</p>


<p>Referenced by <a href="#a67552a8bdd1bd0df687842c7acf3efa3">push_back</a>.</p>

</div>
</div>

### printChunks() {#a21a6098da614f4229dee3de0432aa83a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DebugCounter::printChunks (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/debugcounter/chunk">Chunk</a> &gt; Chunks)</td>
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



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/support/debugcounter-cpp">DebugCounter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>.</p>


<p>Referenced by <a href="#ad575354f42dae4499a5cf49177e8bdca">print</a>.</p>

</div>
</div>

### registerCounter() {#a8b490fa3426ad84d3956e05b09527a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DebugCounter::registerCounter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Desc)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>References <a href="#a9a7d658467244eae745170838e92b3ee">addCounter</a> and <a href="#ac4330a5f1dff21ba1f4be59381832358">instance</a>.</p>

</div>
</div>

### setCounterState() {#af6101c8bdaddab8e9f6bbb138486230b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DebugCounter::setCounterState (unsigned ID, <a href="/web-llvm/docs/api/structs/llvm/debugcounter/counterstate">CounterState</a> State)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>Reference <a href="#ac4330a5f1dff21ba1f4be59381832358">instance</a>.</p>

</div>
</div>

### shouldExecute() {#a5aace8653ce3726ef07194dcf6bce2bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugCounter::shouldExecute (unsigned CounterName)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>.</p>


<p>References <a href="#a69784654584ad4bff747432cac8c4f88">isCountingEnabled</a> and <a href="#a7d21bcbf03ef9764e4363ae385d99579">shouldExecuteImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aadca3692ce40afeb83b7765b2d7dfc9c">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::build</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a4bbe548f3095c981a34533d7910a909d">checkCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dce-cpp/#ada357ebb15bf8c3cb88900273ec95888">DCEInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#acdd3b591101453540fdf4b9d17d49100">anonymous{DeadStoreElimination.cpp}::DSEState::eliminateDeadDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a4a8c56807dfa1a49f37218084fb6c044">findRenameRegForSameLdStRegPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5b33634e0aa97435f13845ce7e10411e">llvm::getKnowledgeFromBundle</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a5d9b598f1c0dd1ef47f78469582de44d">llvm::Attributor::getOrCreateAAFor</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#af6968bc7c8e7e0d6b3fcddb5a934a3c3">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::insertShadowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa054ca3a90996e96887be015cf288270">llvm::slpvectorizer::BoUpSLP::isTreeTinyAndNotFullyVectorizable</a>, <a href="/web-llvm/docs/api/classes/llvm/negator/#a2abe5e7f029b63c7b1bd29ac231ef7fa">llvm::Negator::Negate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a3c38fd13d9fa38356cca5ecdf7cfba23">optimizeSQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a90a2b453bf3ce25f979403d9d95c7070">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::setForceEmitWaitcnt</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a78793329d41f7e0ff3ab15f71b2f952c">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visit</a>.</p>

</div>
</div>

### shouldExecuteImpl() {#a7d21bcbf03ef9764e4363ae385d99579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DebugCounter::shouldExecuteImpl (unsigned CounterName)</td>
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



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/support/debugcounter-cpp">DebugCounter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/debugcounter/counterinfo/#aff89add25cfd93a5d70ce601bc95d813">llvm::DebugCounter::CounterInfo::Chunks</a>, <a href="/web-llvm/docs/api/structs/llvm/debugcounter/counterinfo/#a8765624fbf32b3745da4300914627b99">llvm::DebugCounter::CounterInfo::Count</a>, <a href="/web-llvm/docs/api/structs/llvm/debugcounter/counterinfo/#a2a89ee468fe720294cc92d41ae86fb19">llvm::DebugCounter::CounterInfo::CurrChunkIdx</a>, <a href="#ac4330a5f1dff21ba1f4be59381832358">instance</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a27f73a25903d2597cf044dbe59ddcea5">LLVM_BUILTIN_DEBUGTRAP</a>.</p>


<p>Referenced by <a href="#a5aace8653ce3726ef07194dcf6bce2bf">shouldExecute</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">DebugCounter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/debugcounter-cpp">DebugCounter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
