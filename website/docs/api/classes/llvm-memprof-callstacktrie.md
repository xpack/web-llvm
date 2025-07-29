---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memprof/callstacktrie
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CallStackTrie` Class

<p>Class to build a trie of call stack contexts for a particular profiled allocation call, along with their associated allocation types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::memprof::CallStackTrie { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">llvm/Analysis/MemoryProfileInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f2ad3f9b504bbc6ac5fbb306d74772">CallStackTrie</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6085c89d1a32486046c3fcfa61eee0">~CallStackTrie</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8764bb32436ceef74c9a8cdfc0da0e28">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d4df64225248afbae4f68c4f9501b1">addCallStack</a> (AllocationType AllocType, ArrayRef&lt; uint64_t &gt; StackIds, std::vector&lt; ContextTotalSize &gt; ContextSizeInfo={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a call stack context with the given allocation type to the Trie. <a href="#a87d4df64225248afbae4f68c4f9501b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a4dd5e0dc9edbcc395f80456856acb0">addCallStack</a> (MDNode *MIB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the call stack context along with its allocation type from the MIB metadata to the Trie. <a href="#a0a4dd5e0dc9edbcc395f80456856acb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f10c4267af88a1bd143a7260d2ac8f">buildAndAttachMIBMetadata</a> (CallBase *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and attach the minimal necessary MIB metadata. <a href="#ab9f10c4267af88a1bd143a7260d2ac8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93eab9244b86ce5f52aa4f15a71741be">addSingleAllocTypeAttribute</a> (CallBase *CI, AllocationType AT, StringRef Descriptor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an attribute for the given allocation type to the call instruction. <a href="#a93eab9244b86ce5f52aa4f15a71741be">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35b62f028e7a3c3fe11b7e64800eab6">deleteTrieNode</a> (CallStackTrieNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33cea5b245ab007bd11a8df7d1f2a289">collectContextSizeInfo</a> (CallStackTrieNode *Node, std::vector&lt; ContextTotalSize &gt; &amp;ContextSizeInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107ae83fb5830a013e38271cb1a78396">convertHotToNotCold</a> (CallStackTrieNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a47405d341a47bc4e9573bc8e0172d">buildMIBNodes</a> (CallStackTrieNode *Node, LLVMContext &amp;Ctx, std::vector&lt; uint64_t &gt; &amp;MIBCallStack, std::vector&lt; Metadata * &gt; &amp;MIBNodes, bool CalleeHasAmbiguousCallerContext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">CallStackTrieNode *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea696f31bee6f57d4ef0b6a136df840">Alloc</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8535e47f0fea87290f6fb3989d750054">AllocStackId</a> = 0</td>
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

<p>Class to build a trie of call stack contexts for a particular profiled allocation call, along with their associated allocation types.</p>


<p>The allocation will be at the root of the trie, which is then used to compute the minimum lists of context ids needed to associate a call context with a single allocation type.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallStackTrie() {#a49f2ad3f9b504bbc6ac5fbb306d74772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::CallStackTrie::CallStackTrie ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CallStackTrie() {#aea6085c89d1a32486046c3fcfa61eee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::CallStackTrie::~CallStackTrie ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCallStack() {#a87d4df64225248afbae4f68c4f9501b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallStackTrie::addCallStack (<a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AllocType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; StackIds, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/contexttotalsize">ContextTotalSize</a> &gt; ContextSizeInfo={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a call stack context with the given allocation type to the Trie.</p>


<p>The context is represented by the list of stack ids (computed during matching via a debug location hash), expected to be in order from the allocation call down to the bottom of the call stack (i.e. callee to caller order).</p>


<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#ae6c3c6c5044d97b7a9ec75b6105f68d8">addCallStack</a> and <a href="#a0a4dd5e0dc9edbcc395f80456856acb0">addCallStack</a>.</p>

</div>
</div>

### addCallStack() {#a0a4dd5e0dc9edbcc395f80456856acb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallStackTrie::addCallStack (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the call stack context along with its allocation type from the MIB metadata to the Trie.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>References <a href="#a87d4df64225248afbae4f68c4f9501b1">addCallStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad7ca5290dc5789cbeae763690e6edccf">llvm::mdconst::dyn_extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a6adf5ed44d664399d019ab3727dc5bd9">llvm::memprof::getMIBAllocType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ab5636c9dedf3853480a075cefc7cc1fa">llvm::memprof::getMIBStackNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a571612461ea4af620bc4c441d61579a3">llvm::MDNode::operands</a>.</p>

</div>
</div>

### addSingleAllocTypeAttribute() {#a93eab9244b86ce5f52aa4f15a71741be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallStackTrie::addSingleAllocTypeAttribute (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CI, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Descriptor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an attribute for the given allocation type to the call instruction.</p>


<p>If hinted by reporting is enabled, a message is emitted with the given descriptor used to identify the category of single allocation type.</p>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#ade3d002f2a3c1617aacaddf25e561833">addAllocTypeAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#aafd414cdb5967be7eccd7a6f0d1ca76e">llvm::memprof::getAllocTypeAttributeString</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#a696467f077d0e94dc6b3f171acc6be25">MemProfReportHintedSizes</a>.</p>


<p>Referenced by <a href="#ab9f10c4267af88a1bd143a7260d2ac8f">buildAndAttachMIBMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#ac7cd1bb8cb4a4e4e1ec44f5097cb071f">readMemprof</a>.</p>

</div>
</div>

### buildAndAttachMIBMetadata() {#ab9f10c4267af88a1bd143a7260d2ac8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallStackTrie::buildAndAttachMIBMetadata (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and attach the minimal necessary MIB metadata.</p>


<p>If the alloc has a single allocation type, add a function attribute instead. The reason for adding an attribute in this case is that it matches how the behavior for allocation calls will be communicated to lib call simplification after cloning or another optimization to distinguish the allocation types, which is lower overhead and more direct than maintaining this metadata. Returns true if memprof metadata attached, false if not (attribute added).</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>, definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>References <a href="#a93eab9244b86ce5f52aa4f15a71741be">addSingleAllocTypeAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a89184869fe3acb3e39f0bfcb98378676">llvm::memprof::hasSingleAllocType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a4194726ee334e1085d93e002837b73f0">llvm::Hot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27ad814aa38fbac7f6d03b30741366aae56">llvm::NotCold</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#ac7cd1bb8cb4a4e4e1ec44f5097cb071f">readMemprof</a>.</p>

</div>
</div>

### empty() {#a8764bb32436ceef74c9a8cdfc0da0e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::CallStackTrie::empty ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#ac7cd1bb8cb4a4e4e1ec44f5097cb071f">readMemprof</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildMIBNodes() {#a64a47405d341a47bc4e9573bc8e0172d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallStackTrie::buildMIBNodes (CallStackTrieNode * Node, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, std::vector&lt; uint64_t &gt; &amp; MIBCallStack, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; MIBNodes, bool CalleeHasAmbiguousCallerContext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>

</div>
</div>

### collectContextSizeInfo() {#a33cea5b245ab007bd11a8df7d1f2a289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallStackTrie::collectContextSizeInfo (CallStackTrieNode * Node, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/contexttotalsize">ContextTotalSize</a> &gt; &amp; ContextSizeInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>

</div>
</div>

### convertHotToNotCold() {#a107ae83fb5830a013e38271cb1a78396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallStackTrie::convertHotToNotCold (CallStackTrieNode * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>

</div>
</div>

### deleteTrieNode() {#ac35b62f028e7a3c3fe11b7e64800eab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::CallStackTrie::deleteTrieNode (CallStackTrieNode * Node)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alloc {#a4ea696f31bee6f57d4ef0b6a136df840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallStackTrieNode* llvm::memprof::CallStackTrie::Alloc = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>

</div>
</div>

### AllocStackId {#a8535e47f0fea87290f6fb3989d750054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::CallStackTrie::AllocStackId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
