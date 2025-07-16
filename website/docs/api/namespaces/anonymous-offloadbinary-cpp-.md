---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-offloadbinary-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{OffloadBinary.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{OffloadBinary.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67bf5d7f987fa670edc3e7948bac2a07">extractOffloadFiles</a> (MemoryBufferRef Contents, SmallVectorImpl&lt; OffloadFile &gt; &amp;Binaries)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to extract all the embedded device images contained inside the buffer <span class="doxyComputerOutput">Contents</span>. <a href="#a67bf5d7f987fa670edc3e7948bac2a07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426a48f358aaf6be7a95428dae0d4f31">extractFromObject</a> (const ObjectFile &amp;Obj, SmallVectorImpl&lt; OffloadFile &gt; &amp;Binaries)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f076ea04eda5249d0527c704881cdf1">extractFromBitcode</a> (MemoryBufferRef Buffer, SmallVectorImpl&lt; OffloadFile &gt; &amp;Binaries)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2f8f902ed35880d4ccb900b4ddbe2c1">extractFromArchive</a> (const Archive &amp;Library, SmallVectorImpl&lt; OffloadFile &gt; &amp;Binaries)</td>
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

### extractFromArchive() {#aa2f8f902ed35880d4ccb900b4ddbe2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{OffloadBinary.cpp}::extractFromArchive (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> &amp; Library, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/offloadfile">OffloadFile</a> &gt; &amp; Binaries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/object/offloadbinary-cpp">OffloadBinary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a6f1e06f3450b7f027dfac3a136c3f547">llvm::object::Archive::children</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a214181fcdbdcdd2ce1d22fe395716abc">llvm::object::extractOffloadBinaries</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a084b7cfd2acc52fcfd2121bad6608ba8">llvm::object::OffloadBinary::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af9992f46ab43b45770fddfdefef7c237">llvm::isAddrAligned</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### extractFromBitcode() {#a0f076ea04eda5249d0527c704881cdf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{OffloadBinary.cpp}::extractFromBitcode (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/offloadfile">OffloadFile</a> &gt; &amp; Binaries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/object/offloadbinary-cpp">OffloadBinary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a2d40c0621205b0cbd5f642d970cbb896">llvm::mdconst::dyn_extract_or_null</a>, <a href="#a67bf5d7f987fa670edc3e7948bac2a07">extractOffloadFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0698d5bcabbfbca4f56a9d7a81cecb25">llvm::GlobalVariable::getInitializer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afab90ce1024ba9b690f64237fa1a2b9b">llvm::getLazyIRModule</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#ae44259d9edd71181ea8b89d18f27a967">llvm::MDString::getString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### extractFromObject() {#a426a48f358aaf6be7a95428dae0d4f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{OffloadBinary.cpp}::extractFromObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/offloadfile">OffloadFile</a> &gt; &amp; Binaries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/object/offloadbinary-cpp">OffloadBinary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a67bf5d7f987fa670edc3e7948bac2a07">extractOffloadFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#acecdb20a61e1b407af83d42e1ad9a3f3">llvm::object::Binary::getFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsectionref/#ab50a33a2b9a8bb4f0308ac8ae8e614d3">llvm::object::ELFSectionRef::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac391f637f5960964588dfac009094396">llvm::object::Binary::isCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ae470b1ff27e3d72e61fcb4a97fd0a461">llvm::object::Binary::isELF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca74f197262c720223d22a582814c4482d">llvm::ELF::SHT_LLVM_OFFLOADING</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### extractOffloadFiles() {#a67bf5d7f987fa670edc3e7948bac2a07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{OffloadBinary.cpp}::extractOffloadFiles (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Contents, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/offloadfile">OffloadFile</a> &gt; &amp; Binaries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to extract all the embedded device images contained inside the buffer <span class="doxyComputerOutput">Contents</span>.</p>


<p>The buffer is expected to contain a valid offloading binary format.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/object/offloadbinary-cpp">OffloadBinary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#ab1f06bb87aef1053996ec05424135d82">llvm::object::OffloadBinary::create</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a084b7cfd2acc52fcfd2121bad6608ba8">llvm::object::OffloadBinary::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a3201ce149cba3920fc965378ceddbcb8">llvm::MemoryBufferRef::getBufferIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af9992f46ab43b45770fddfdefef7c237">llvm::isAddrAligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa28286a33491b5d9a936fb6ae853baee">llvm::StringRef::take_front</a>.</p>


<p>Referenced by <a href="#a0f076ea04eda5249d0527c704881cdf1">extractFromBitcode</a> and <a href="#a426a48f358aaf6be7a95428dae0d4f31">extractFromObject</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/offloadbinary-cpp">OffloadBinary.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
