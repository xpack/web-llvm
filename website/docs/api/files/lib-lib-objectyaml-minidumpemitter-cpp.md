---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objectyaml/minidumpemitter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MinidumpEmitter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">llvm/ObjectYAML/MinidumpYAML.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/yaml2obj-h">llvm/ObjectYAML/yaml2obj.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">llvm/Support/ConvertUTF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-minidumpemitter-cpp-">anonymous{MinidumpEmitter.cpp}</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/yaml">yaml</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-minidumpemitter-cpp-/bloballocator">BlobAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper class to manage the placement of various structures into the final minidump binary. <a href="/web-llvm/docs/api/classes/anonymous-minidumpemitter-cpp-/bloballocator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/minidump/locationdescriptor">LocationDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1375be19b297c11722ddf58c29696dc1">layout</a> (BlobAllocator &amp;File, yaml::BinaryRef Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334ff5caec6d220747f8c58bc2778729">layout</a> (BlobAllocator &amp;File, MinidumpYAML::ExceptionStream &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1aec82bf8069960fd032d51cf5c77c9">layout</a> (BlobAllocator &amp;File, MinidumpYAML::Memory64ListStream &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9469f1ed98716c5dcba746f5a840488d">layout</a> (BlobAllocator &amp;File, MemoryListStream::entry_type &amp;Range)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a055235c1121d1f91eda30ef70af60fef">layout</a> (BlobAllocator &amp;File, ModuleListStream::entry_type &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ee39617462dbbfd6bc079c6a5bd323">layout</a> (BlobAllocator &amp;File, ThreadListStream::entry_type &amp;T)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename EntryT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3816448d4244b838a4d047dc9e0fb523">layout</a> (BlobAllocator &amp;File, MinidumpYAML::detail::ListStream&lt; EntryT &gt; &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/minidump/directory">Directory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9572de1ba76b89eae1eb07c8b446b143">layout</a> (BlobAllocator &amp;File, Stream &amp;S)</td>
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

### layout() {#a1375be19b297c11722ddf58c29696dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationDescriptor layout (BlobAllocator &amp; File, <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref">yaml::BinaryRef</a> Data)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp">MinidumpEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="#a9469f1ed98716c5dcba746f5a840488d">layout</a>, <a href="#a3816448d4244b838a4d047dc9e0fb523">layout</a>, <a href="#a334ff5caec6d220747f8c58bc2778729">layout</a>, <a href="#a055235c1121d1f91eda30ef70af60fef">layout</a>, <a href="#a9572de1ba76b89eae1eb07c8b446b143">layout</a>, <a href="#a12ee39617462dbbfd6bc079c6a5bd323">layout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aec505024f93ccc62d2b0214ac9bcb9f2">llvm::yaml::yaml2minidump</a>.</p>

</div>
</div>

### layout() {#a334ff5caec6d220747f8c58bc2778729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t layout (BlobAllocator &amp; File, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/exceptionstream">MinidumpYAML::ExceptionStream</a> &amp; S)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp">MinidumpEmitter.cpp</a>.</p>


<p>References <a href="#a1375be19b297c11722ddf58c29696dc1">layout</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/exceptionstream/#a628efc7b1f9a5920c74cd05ed2b29d84">llvm::MinidumpYAML::ExceptionStream::MDExceptionStream</a>, <a href="/web-llvm/docs/api/structs/llvm/minidump/exceptionstream/#a4d75699eed74bb2cd3f39f7f3f91d5c2">llvm::minidump::ExceptionStream::ThreadContext</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/exceptionstream/#afe626bc8a19acbb9c961d8f87936ad33">llvm::MinidumpYAML::ExceptionStream::ThreadContext</a>.</p>

</div>
</div>

### layout() {#af1aec82bf8069960fd032d51cf5c77c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t layout (BlobAllocator &amp; File, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/memory64liststream">MinidumpYAML::Memory64ListStream</a> &amp; S)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp">MinidumpEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidump/memory64listheader/#ad465c31a6e8a83d706bb8a3f1f3e9555">llvm::minidump::Memory64ListHeader::BaseRVA</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/detail/liststream/#ad2991cb1ec075ef5a105a6e717b36d31">llvm::MinidumpYAML::detail::ListStream&lt; EntryT &gt;::Entries</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/memory64liststream/#ae7a96c7fd3e0e54977bb719586d7c3e6">llvm::MinidumpYAML::Memory64ListStream::Header</a> and <a href="/web-llvm/docs/api/structs/llvm/minidump/memory64listheader/#a60efdfcb0248b6725b29a1539b31bf83">llvm::minidump::Memory64ListHeader::NumberOfMemoryRanges</a>.</p>

</div>
</div>

### layout() {#a9469f1ed98716c5dcba746f5a840488d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void layout (BlobAllocator &amp; File, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/detail/liststream/#ac92c3762b47cd727be57059b4b53514d">MemoryListStream::entry_type</a> &amp; Range)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp">MinidumpEmitter.cpp</a>.</p>


<p>References <a href="#a1375be19b297c11722ddf58c29696dc1">layout</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### layout() {#a055235c1121d1f91eda30ef70af60fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void layout (BlobAllocator &amp; File, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/detail/liststream/#ac92c3762b47cd727be57059b4b53514d">ModuleListStream::entry_type</a> &amp; M)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp">MinidumpEmitter.cpp</a>.</p>


<p>Reference <a href="#a1375be19b297c11722ddf58c29696dc1">layout</a>.</p>

</div>
</div>

### layout() {#a12ee39617462dbbfd6bc079c6a5bd323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void layout (BlobAllocator &amp; File, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/detail/liststream/#ac92c3762b47cd727be57059b4b53514d">ThreadListStream::entry_type</a> &amp; T)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp">MinidumpEmitter.cpp</a>.</p>


<p>References <a href="#a1375be19b297c11722ddf58c29696dc1">layout</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### layout() {#a3816448d4244b838a4d047dc9e0fb523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename EntryT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t layout (BlobAllocator &amp; File, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/detail/liststream">MinidumpYAML::detail::ListStream</a>&lt; EntryT &gt; &amp; S)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp">MinidumpEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/detail/liststream/#ad2991cb1ec075ef5a105a6e717b36d31">llvm::MinidumpYAML::detail::ListStream&lt; EntryT &gt;::Entries</a> and <a href="#a1375be19b297c11722ddf58c29696dc1">layout</a>.</p>

</div>
</div>

### layout() {#a9572de1ba76b89eae1eb07c8b446b143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Directory layout (BlobAllocator &amp; File, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream">Stream</a> &amp; S)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp">MinidumpEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/minidump/systeminfo/#a946ead3f1992dd60c5899abd88617817">llvm::minidump::SystemInfo::CSDVersionRVA</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abcab0d4998a26f5b5742ad38c4af8817e32">llvm::MinidumpYAML::Stream::Exception</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/memoryinfoliststream/#a9de6355421cb60263877a0f39e18f4a3">llvm::MinidumpYAML::MemoryInfoListStream::Infos</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a492be506d939f72ca251976bc543d2a0">llvm::MinidumpYAML::Stream::Kind</a>, <a href="#a1375be19b297c11722ddf58c29696dc1">layout</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abca91a770495b370d14c7644688a96dda8f">llvm::MinidumpYAML::Stream::Memory64List</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abca9c3d5de61a6e11627540121a95ec339f">llvm::MinidumpYAML::Stream::MemoryInfoList</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abca298f787bbcb87840abc9f5baf7e088a2">llvm::MinidumpYAML::Stream::MemoryList</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abca111f5174e3dcd05c98ca3a8c6b73a03b">llvm::MinidumpYAML::Stream::ModuleList</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abcac34949db9ce05a7dcfa4cf073b161233">llvm::MinidumpYAML::Stream::RawContent</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/rawcontentstream/#adcb3707edc430543bb6541aa0fc4445a">llvm::MinidumpYAML::RawContentStream::Size</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abca747dbff7cbf77d5d058c04fcde2c4901">llvm::MinidumpYAML::Stream::SystemInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abcae03ab724014b7833bdc333912ed9db12">llvm::MinidumpYAML::Stream::TextContent</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abca60b46fff743f2a9884558e7c97c99751">llvm::MinidumpYAML::Stream::ThreadList</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#ac752f3d2d3fbedb56cc912c2123d0a45">llvm::MinidumpYAML::Stream::Type</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
