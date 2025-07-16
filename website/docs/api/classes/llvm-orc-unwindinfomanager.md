---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/unwindinfomanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UnwindInfoManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::UnwindInfoManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">llvm/ExecutionEngine/Orc/TargetProcess/UnwindInfoManager.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a13dbe599b656dab5995830f52fbea8">UnwindInfoManager</a> (UnwindInfoManager &amp;&amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3beba613ae3f223b2186f8e5d9fca16">UnwindInfoManager</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf320e4ffb2cf6a71904132843202d6f">~UnwindInfoManager</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager">UnwindInfoManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae29add448191f1ccd3443de11f006ee7">operator=</a> (UnwindInfoManager &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6096491248b410844cdb603f297c95d">findSectionsImpl</a> (uintptr_t Addr, UnwindSections *Info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae51cffee66336b0d5ff385e82be77403">registerSectionsImpl</a> (ArrayRef&lt; orc::ExecutorAddrRange &gt; CodeRanges, orc::ExecutorAddr DSOBase, orc::ExecutorAddrRange DWARFEHFrame, orc::ExecutorAddrRange CompactUnwind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b84de763aab9dd8da96493ca6349a77">deregisterSectionsImpl</a> (ArrayRef&lt; orc::ExecutorAddrRange &gt; CodeRanges)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60437eeb008ed2c09f06f47b378007fa">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; uintptr_t, <a href="/web-llvm/docs/api/structs/llvm/orc/unwindinfomanager/unwindsections">UnwindSections</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7cff35c5633531820ada766926523e7">UWSecs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51bab61aaf00c3a0395daa426022ada3">TryEnable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the libunwind find-dynamic-unwind-info callback registration APIs are available then this method will instantiate a global <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager">UnwindInfoManager</a> instance suitable for the process and return true. <a href="#a51bab61aaf00c3a0395daa426022ada3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cfb7c36eddb6eeab4a0dbece2b7f21c">addBootstrapSymbols</a> (StringMap&lt; ExecutorAddr &gt; &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdda747ca74c5dfd5f79c296d5d60332">registerSections</a> (ArrayRef&lt; orc::ExecutorAddrRange &gt; CodeRanges, orc::ExecutorAddr DSOBase, orc::ExecutorAddrRange DWARFEHFrame, orc::ExecutorAddrRange CompactUnwind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77962f30a5593b989924def76d5ea7a7">deregisterSections</a> (ArrayRef&lt; orc::ExecutorAddrRange &gt; CodeRanges)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3b5ab316cec8dffe1c0d9a086d9d82">findSections</a> (uintptr_t Addr, UnwindSections *Info)</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UnwindInfoManager() {#a5a13dbe599b656dab5995830f52fbea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::UnwindInfoManager::UnwindInfoManager (<a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager">UnwindInfoManager</a> &amp;&amp;)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>.</p>


<p>Reference <a href="#a5a13dbe599b656dab5995830f52fbea8">UnwindInfoManager</a>.</p>


<p>Referenced by <a href="#ae29add448191f1ccd3443de11f006ee7">operator=</a>, <a href="#a51bab61aaf00c3a0395daa426022ada3">TryEnable</a> and <a href="#a5a13dbe599b656dab5995830f52fbea8">UnwindInfoManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### UnwindInfoManager() {#ae3beba613ae3f223b2186f8e5d9fca16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::UnwindInfoManager::UnwindInfoManager ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~UnwindInfoManager() {#abf320e4ffb2cf6a71904132843202d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::UnwindInfoManager::~UnwindInfoManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ab3f096b8bf12d5e38c7cfd994b8dab3e">llvm::orc::RemoveFindDynamicUnwindSections</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a91924a60372d1f5f72ede0842ff55083">llvm::orc::RemoveFnName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ae29add448191f1ccd3443de11f006ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindInfoManager &amp; llvm::orc::UnwindInfoManager::operator= (<a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager">UnwindInfoManager</a> &amp;&amp;)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="#a5a13dbe599b656dab5995830f52fbea8">UnwindInfoManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### deregisterSectionsImpl() {#a7b84de763aab9dd8da96493ca6349a77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::UnwindInfoManager::deregisterSectionsImpl (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> &gt; CodeRanges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>

</div>
</div>

### findSectionsImpl() {#aa6096491248b410844cdb603f297c95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::orc::UnwindInfoManager::findSectionsImpl (uintptr_t Addr, <a href="/web-llvm/docs/api/structs/llvm/orc/unwindinfomanager/unwindsections">UnwindSections</a> * Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>

</div>
</div>

### registerSectionsImpl() {#ae51cffee66336b0d5ff385e82be77403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::UnwindInfoManager::registerSectionsImpl (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> &gt; CodeRanges, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a> DSOBase, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> DWARFEHFrame, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> CompactUnwind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### M {#a60437eeb008ed2c09f06f47b378007fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::UnwindInfoManager::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>.</p>

</div>
</div>

### UWSecs {#aa7cff35c5633531820ada766926523e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;uintptr_t, UnwindSections&gt; llvm::orc::UnwindInfoManager::UWSecs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### addBootstrapSymbols() {#a6cfb7c36eddb6eeab4a0dbece2b7f21c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::UnwindInfoManager::addBootstrapSymbols (<a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt; &amp; M)</td>
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



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a8adb0ae35f7e95c960c86cfe19bc7215">llvm::orc::ExecutorAddr::fromPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp/#a2b640b8a6b047c09de51d6e52697d6fe">llvm_orc_rt_alt_UnwindInfoManager_deregister</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp/#abff8aeb48d20e809b4a16fbd321ac7e2">llvm_orc_rt_alt_UnwindInfoManager_register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-alt/#a11e6b5673a2ef4f15613d83b000dea48">llvm::orc::rt_alt::UnwindInfoManagerDeregisterActionName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-alt/#a7f3a9b9ae915debaec6c11b4ef8bf5df">llvm::orc::rt_alt::UnwindInfoManagerRegisterActionName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a>.</p>

</div>
</div>

### deregisterSections() {#a77962f30a5593b989924def76d5ea7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::UnwindInfoManager::deregisterSections (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> &gt; CodeRanges)</td>
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



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8cf1abfcc22cc04521e19405a53783b8">llvm::orc::Instance</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp/#a2b640b8a6b047c09de51d6e52697d6fe">llvm_orc_rt_alt_UnwindInfoManager_deregister</a>.</p>

</div>
</div>

### registerSections() {#afdda747ca74c5dfd5f79c296d5d60332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::UnwindInfoManager::registerSections (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> &gt; CodeRanges, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a> DSOBase, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> DWARFEHFrame, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> CompactUnwind)</td>
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



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8cf1abfcc22cc04521e19405a53783b8">llvm::orc::Instance</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp/#abff8aeb48d20e809b4a16fbd321ac7e2">llvm_orc_rt_alt_UnwindInfoManager_register</a>.</p>

</div>
</div>

### TryEnable() {#a51bab61aaf00c3a0395daa426022ada3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::UnwindInfoManager::TryEnable ()</td>
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

<p>If the libunwind find-dynamic-unwind-info callback registration APIs are available then this method will instantiate a global <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager">UnwindInfoManager</a> instance suitable for the process and return true.</p>


<p>Otherwise it will return false.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#add900ceff5a2bfd40d1490afe9c8b8bc">llvm::orc::AddFnName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8cf1abfcc22cc04521e19405a53783b8">llvm::orc::Instance</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ab3f096b8bf12d5e38c7cfd994b8dab3e">llvm::orc::RemoveFindDynamicUnwindSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a91924a60372d1f5f72ede0842ff55083">llvm::orc::RemoveFnName</a> and <a href="#a5a13dbe599b656dab5995830f52fbea8">UnwindInfoManager</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### findSections() {#a8b3b5ab316cec8dffe1c0d9a086d9d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::orc::UnwindInfoManager::findSections (uintptr_t Addr, <a href="/web-llvm/docs/api/structs/llvm/orc/unwindinfomanager/unwindsections">UnwindSections</a> * Info)</td>
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



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/unwindinfomanager-h">UnwindInfoManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/unwindinfomanager-cpp">UnwindInfoManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
