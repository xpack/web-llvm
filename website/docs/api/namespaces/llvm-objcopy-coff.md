---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/objcopy/coff
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `coff` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::objcopy::coff { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/relocation">Relocation</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/section">Section</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/auxsymbol">AuxSymbol</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/symbol">Symbol</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object">Object</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/coff/coffreader">COFFReader</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/coff/coffwriter">COFFWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/coff/coffobjectfile">COFFObjectFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03da0184bacf98a2a34f81413e7159b4">executeObjcopyOnBinary</a> (const CommonConfig &amp;Config, const COFFConfig &amp;, object::COFFObjectFile &amp;In, raw_ostream &amp;Out)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the transformations described by <span class="doxyComputerOutput">Config</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/objcopy/coffconfig">COFFConfig</a></span> to <span class="doxyComputerOutput">In</span> and writes the result into <span class="doxyComputerOutput">Out</span>. <a href="#a03da0184bacf98a2a34f81413e7159b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00788ca1cb49affa89933d0eb01101da">isDebugSection</a> (const Section &amp;Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9cc3787622f35ccb9722970c36dea9f">getNextRVA</a> (const Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdcc3a66137dcf1fb3dbdc7adaedc26c">createGnuDebugLinkSectionContents</a> (StringRef File)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a326436b39c57d0d075c20bc4fddd9d">addSection</a> (Object &amp;Obj, StringRef Name, ArrayRef&lt; uint8_t &gt; Contents, uint32_t Characteristics)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26907ff1b30d1236b06e5880af523d2">addGnuDebugLink</a> (Object &amp;Obj, StringRef DebugLinkFile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb5ea1628a004c71831099fe3609945">flagsToCharacteristics</a> (SectionFlag AllFlags, uint32_t OldChar)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81e88ae7d3e872ba0cdc367330b2974d">dumpSection</a> (Object &amp;O, StringRef SectionName, StringRef FileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa859579ac4adb9cbcebf0ddc98a085b">handleArgs</a> (const CommonConfig &amp;Config, const COFFConfig &amp;COFFConfig, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Symbol1Ty, class Symbol2Ty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f4e03df49ff52fb36573a91dbd23c67">copySymbol</a> (Symbol1Ty &amp;Dest, const Symbol2Ty &amp;Src)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PeHeader1Ty, class PeHeader2Ty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a61250bbdb8bca0ef99f4652f3a429fe9">copyPeHeader</a> (PeHeader1Ty &amp;Dest, const PeHeader2Ty &amp;Src)</td>
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

### addGnuDebugLink() {#ac26907ff1b30d1236b06e5880af523d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::objcopy::coff::addGnuDebugLink (<a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DebugLinkFile)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a>.</p>


<p>References <a href="#a2a326436b39c57d0d075c20bc4fddd9d">addSection</a>, <a href="#afdcc3a66137dcf1fb3dbdc7adaedc26c">createGnuDebugLinkSectionContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa5c5ea9353e663af52c356d43798701a1">llvm::COFF::IMAGE_SCN_MEM_DISCARDABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#aaa859579ac4adb9cbcebf0ddc98a085b">handleArgs</a>.</p>

</div>
</div>

### addSection() {#a2a326436b39c57d0d075c20bc4fddd9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::coff::addSection (<a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Contents, uint32_t Characteristics)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a80160cf4a1180428e5d529e3f0ba1e47">llvm::objcopy::coff::Object::addSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/llvm/object/pe32plus-header/#a9447c509980ccf155b0f89edba860928">llvm::object::pe32plus_header::FileAlignment</a>, <a href="#aa9cc3787622f35ccb9722970c36dea9f">getNextRVA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa447cfc2eddd86f9f90a054d3e111c6d9">llvm::COFF::IMAGE_SCN_MEM_EXECUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aac1dfcdc9a17df9b148557d4c01759767">llvm::COFF::IMAGE_SCN_MEM_WRITE</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a372a31deed6f440b5d367a3d317eecde">llvm::objcopy::coff::Object::IsPE</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a8223da50bdf4d393305551529b85f84f">llvm::objcopy::coff::Object::PeHeader</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/section/#a43d1a02e1a9f1ab501c83ea3e09d3523">llvm::objcopy::coff::Section::setOwnedContents</a>.</p>


<p>Referenced by <a href="#ac26907ff1b30d1236b06e5880af523d2">addGnuDebugLink</a> and <a href="#aaa859579ac4adb9cbcebf0ddc98a085b">handleArgs</a>.</p>

</div>
</div>

### copyPeHeader() {#a61250bbdb8bca0ef99f4652f3a429fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PeHeader1Ty, class PeHeader2Ty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::coff::copyPeHeader (PeHeader1Ty &amp; Dest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PeHeader2Ty &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobject-h">COFFObject.h</a>.</p>

</div>
</div>

### copySymbol() {#a0f4e03df49ff52fb36573a91dbd23c67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Symbol1Ty, class Symbol2Ty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::coff::copySymbol (Symbol1Ty &amp; Dest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Symbol2Ty &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobject-h">COFFObject.h</a>.</p>

</div>
</div>

### createGnuDebugLinkSectionContents() {#afdcc3a66137dcf1fb3dbdc7adaedc26c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; uint8_t &gt; &gt; llvm::objcopy::coff::createGnuDebugLinkSectionContents (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> File)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b39f29a121496d294af31158c65740b">llvm::crc32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a0b27918290ff5323bea1e3b78a9cf04e">llvm::objcopy::File</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4f05956d010455624c13f5eb2217bc8b">llvm::support::endian::write32le</a>.</p>


<p>Referenced by <a href="#ac26907ff1b30d1236b06e5880af523d2">addGnuDebugLink</a>.</p>

</div>
</div>

### dumpSection() {#a81e88ae7d3e872ba0cdc367330b2974d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::objcopy::coff::dumpSection (<a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object">Object</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb650e853db0ddbb60411b885c499737">llvm::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#a3a10ce8cad8fee5d6a4c55270866aa05">llvm::FileOutputBuffer::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/section/#a95a643ba0c8f490270cf524af4857e61">llvm::objcopy::coff::Section::getContents</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/section/#ab7fadec5aeb8eecc8049dfe85897ace9">llvm::objcopy::coff::Section::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#aaa859579ac4adb9cbcebf0ddc98a085b">handleArgs</a>.</p>

</div>
</div>

### executeObjcopyOnBinary() {#a03da0184bacf98a2a34f81413e7159b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::objcopy::coff::executeObjcopyOnBinary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/coffconfig">COFFConfig</a> &amp; COFFConfig, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">object::COFFObjectFile</a> &amp; In, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply the transformations described by <span class="doxyComputerOutput">Config</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/objcopy/coffconfig">COFFConfig</a></span> to <span class="doxyComputerOutput">In</span> and writes the result into <span class="doxyComputerOutput">Out</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>any <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> encountered whilst performing the operation.</p></dd>
</dl>


<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/coff/coffreader/#ad5bbf959c3d5d899e297759bc4172438">llvm::objcopy::coff::COFFReader::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#aaa859579ac4adb9cbcebf0ddc98a085b">handleArgs</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a24e1ca7d92cbc2a42152ac37dbc0e7ad">llvm::objcopy::CommonConfig::InputFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a8a04952cef062450e2bd671d5e4b3c0c">llvm::objcopy::CommonConfig::OutputFilename</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#af45b538ed42f9864350e9c38c168333e">llvm::objcopy::executeObjcopyOnBinary</a>.</p>

</div>
</div>

### flagsToCharacteristics() {#a2cb5ea1628a004c71831099fe3609945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::objcopy::coff::flagsToCharacteristics (<a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562">SectionFlag</a> AllFlags, uint32_t OldChar)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa1bbf9116aef9ec7f3cf42d8c0e9e0de2">llvm::COFF::IMAGE_SCN_ALIGN_1024BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa07c625e2888c76f1a4b75c1c6be0d851">llvm::COFF::IMAGE_SCN_ALIGN_128BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa80c93a2cbfeed79e08710abe42c600af">llvm::COFF::IMAGE_SCN_ALIGN_16BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa21fd30dd5b7f5e61ae45e4725b35bad9">llvm::COFF::IMAGE_SCN_ALIGN_1BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aabd2cb39592ec6cf025c397bc8310c015">llvm::COFF::IMAGE_SCN_ALIGN_2048BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa150200314be0f00386f359231fccf240">llvm::COFF::IMAGE_SCN_ALIGN_256BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aab3c7c3378d0458f4989c89b9b90e4ee1">llvm::COFF::IMAGE_SCN_ALIGN_2BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa9101ef5d44047784ffbdf912d07eeddf">llvm::COFF::IMAGE_SCN_ALIGN_32BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa63545970df991c827925606937bc43b6">llvm::COFF::IMAGE_SCN_ALIGN_4096BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa8e56a92024f9d15fa0ee42b68ca00e04">llvm::COFF::IMAGE_SCN_ALIGN_4BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa4cd4df3e0cf51df88bf693f443297120">llvm::COFF::IMAGE_SCN_ALIGN_512BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa0603f4e13f395b70d89519b3265dd15b">llvm::COFF::IMAGE_SCN_ALIGN_64BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6e4bd3367945e029a61523be5674be1f">llvm::COFF::IMAGE_SCN_ALIGN_8192BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa88c186e05b45bfa0468a57ead2951928">llvm::COFF::IMAGE_SCN_ALIGN_8BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa2b3dbe611464bb08a83985d56d7bc67b">llvm::COFF::IMAGE_SCN_CNT_CODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa4e1f40f2bdf9b194d4156c7707d047ba">llvm::COFF::IMAGE_SCN_CNT_UNINITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa24ac1300caa85825d3526b8baaec159f">llvm::COFF::IMAGE_SCN_LNK_REMOVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa5c5ea9353e663af52c356d43798701a1">llvm::COFF::IMAGE_SCN_MEM_DISCARDABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa447cfc2eddd86f9f90a054d3e111c6d9">llvm::COFF::IMAGE_SCN_MEM_EXECUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa0ea670a3976e63e9f4a36f4e4ca425bb">llvm::COFF::IMAGE_SCN_MEM_SHARED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aac1dfcdc9a17df9b148557d4c01759767">llvm::COFF::IMAGE_SCN_MEM_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a12597c230a14e9fecb20ea2533b1797e">llvm::objcopy::SecAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a1f15b014c010ed3abad6308840996d32">llvm::objcopy::SecCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a82493f280af5de115739e0bb8ad84249">llvm::objcopy::SecData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a3eef67d9a88c53e859e180bc3cec76f2">llvm::objcopy::SecDebug</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a83814f584ba89794f75bd604189af1f3">llvm::objcopy::SecExclude</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a3ba962ce443370e77abf4d098c833335">llvm::objcopy::SecLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a463608f99ea41e55c28ac94591e341af">llvm::objcopy::SecNoload</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a6ec694a128d394b84914de2af082b232">llvm::objcopy::SecReadonly</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562aa527b9d657d976d628c2dd572f86a0c4">llvm::objcopy::SecShare</a>.</p>


<p>Referenced by <a href="#aaa859579ac4adb9cbcebf0ddc98a085b">handleArgs</a>.</p>

</div>
</div>

### getNextRVA() {#aa9cc3787622f35ccb9722970c36dea9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::objcopy::coff::getNextRVA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#ac719da3d3c57f045cb5dd0f8cf98aa01">llvm::objcopy::coff::Object::getSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a372a31deed6f440b5d367a3d317eecde">llvm::objcopy::coff::Object::IsPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a8223da50bdf4d393305551529b85f84f">llvm::objcopy::coff::Object::PeHeader</a> and <a href="/web-llvm/docs/api/structs/llvm/object/pe32plus-header/#ad6e9355f84bf109dd8d0b05b922233c1">llvm::object::pe32plus_header::SectionAlignment</a>.</p>


<p>Referenced by <a href="#a2a326436b39c57d0d075c20bc4fddd9d">addSection</a>.</p>

</div>
</div>

### handleArgs() {#aaa859579ac4adb9cbcebf0ddc98a085b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::objcopy::coff::handleArgs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/coffconfig">COFFConfig</a> &amp; COFFConfig, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a59b34ccbf34cdf41e82b97304dee7bb0">llvm::objcopy::CommonConfig::AddGnuDebugLink</a>, <a href="#ac26907ff1b30d1236b06e5880af523d2">addGnuDebugLink</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a935828d3516e07952f9982eedb0af62f">llvm::objcopy::CommonConfig::AddSection</a>, <a href="#a2a326436b39c57d0d075c20bc4fddd9d">addSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#ad8575ac23541d1433a8e492cc876f75aab1c94ca2fbc3e78fc30069c8d0f01680">llvm::objcopy::All</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a5d5c6f0e1d23df171e3bdd1c027a06e1">llvm::object::coff_section::Characteristics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a7ca41c3715f6c35e3350f83e826cbd3e">llvm::objcopy::coff::Object::DataDirectories</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404ac180d06a50e9fc580140a835bb60fb8c">llvm::COFF::DEBUG_DIRECTORY</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#ac6efd384d0ad969083034e1205ec5166">llvm::objcopy::CommonConfig::DiscardMode</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a42cc07e96293a65eb61cf4ce8a489b41">llvm::objcopy::CommonConfig::DumpSection</a>, <a href="#a81e88ae7d3e872ba0cdc367330b2974d">dumpSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#ae37fd1e51553e31998f280b07d853e77">llvm::objcopy::NameMatcher::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a0b27918290ff5323bea1e3b78a9cf04e">llvm::objcopy::File</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="#a2cb5ea1628a004c71831099fe3609945">flagsToCharacteristics</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a9c09b790a977134d815a2d19aea3d552">llvm::objcopy::coff::Object::getMutableSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a2970c1b26252ab76b78fc4b45fcabac0">llvm::objcopy::coff::Object::getMutableSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/section/#a7c22d02ad3a096bf4d175972a2ed89c6">llvm::objcopy::coff::Section::Header</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa21fd30dd5b7f5e61ae45e4725b35bad9">llvm::COFF::IMAGE_SCN_ALIGN_1BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa2b3dbe611464bb08a83985d56d7bc67b">llvm::COFF::IMAGE_SCN_CNT_CODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa5c5ea9353e663af52c356d43798701a1">llvm::COFF::IMAGE_SCN_MEM_DISCARDABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afc617a23fd5e4cce7f2adfc7c2966e1c">llvm::COFF::IMAGE_SYM_CLASS_STATIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="#a00788ca1cb49affa89933d0eb01101da">isDebugSection</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a372a31deed6f440b5d367a3d317eecde">llvm::objcopy::coff::Object::IsPE</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coffconfig/#af6c9327e40a5497f28145f0e6e884c11">llvm::objcopy::COFFConfig::MajorSubsystemVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/object/pe32plus-header/#a5fd7b47dfaac82d9683d4ce008f585ff">llvm::object::pe32plus_header::MajorSubsystemVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#ae20d61d1b09ad5ca69701afe73043675">llvm::objcopy::coff::Object::markSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#a8fe6d6e80304c85e35c03066ae1bcfa9">llvm::objcopy::NameMatcher::matches</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coffconfig/#a1632cdddfa3165a990bec77eb4960219">llvm::objcopy::COFFConfig::MinorSubsystemVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/object/pe32plus-header/#a9259e1e1d673b65352a803baa6f6a787">llvm::object::pe32plus_header::MinorSubsystemVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/section/#ab7fadec5aeb8eecc8049dfe85897ace9">llvm::objcopy::coff::Section::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a44946f210492495ee1add2b497ddc31a">llvm::objcopy::CommonConfig::OnlyKeepDebug</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aba256fcc9763c4d144e805e67f6790f9">llvm::objcopy::CommonConfig::OnlySection</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a8a04952cef062450e2bd671d5e4b3c0c">llvm::objcopy::CommonConfig::OutputFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a8223da50bdf4d393305551529b85f84f">llvm::objcopy::coff::Object::PeHeader</a>, <a href="/web-llvm/docs/api/structs/llvm/object/data-directory/#abe92ae1acff82d60db89511e864c79b0">llvm::object::data_directory::RelativeVirtualAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/section/#a836259628d86d61d2f28090260e24e81">llvm::objcopy::coff::Section::Relocs</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a95463c813d6c4a15390dfe8a0a03bfda">llvm::objcopy::coff::Object::removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#adb4129c7b7fb10fedccaaa668094cb31">llvm::objcopy::coff::Object::removeSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a641257caac84236fba46e30aa91f6c7a">llvm::objcopy::NewSectionInfo::SectionData</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a05c34cfa6560e1e8b1aa9a540d5505e3">llvm::objcopy::NewSectionInfo::SectionName</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a89c18ab7386b44885ab7c4789d0f87f7">llvm::objcopy::CommonConfig::SetSectionFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/object/data-directory/#ac3e7ea32a6ce1290ca7eebf230ea1121">llvm::object::data_directory::Size</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a8882aa2bfacd40fbbd4bac3f492269c6">llvm::object::coff_section::SizeOfRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a9d5713c258905f31b34b13b07086b7c7">llvm::objcopy::CommonConfig::StripAll</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aef2d23d828ad0d0453f27d4720afeca6">llvm::objcopy::CommonConfig::StripAllGNU</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#abadfb5107f778ad8d81df7893db2c25e">llvm::objcopy::CommonConfig::StripDebug</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a978856b980f494b38439e6915ebb08ab">llvm::objcopy::CommonConfig::StripUnneeded</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coffconfig/#aaddd8d9782fd799449e5b06082eb2547">llvm::objcopy::COFFConfig::Subsystem</a>, <a href="/web-llvm/docs/api/structs/llvm/object/pe32plus-header/#ab262e355393c23b0cc55a97f08fdc1d8">llvm::object::pe32plus_header::Subsystem</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a1d8345e6518fe133dd67d094a69bb8c6">llvm::objcopy::CommonConfig::SymbolsToRemove</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#ae7d2b6748551fda8ea5d3757f96f7d0b">llvm::objcopy::CommonConfig::SymbolsToRename</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#addbcdc27b0e6e19fba3ec20ef5de05d9">llvm::objcopy::CommonConfig::ToRemove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a41639273bf671d1b1a59a5a48eb42ec8">llvm::objcopy::coff::Object::truncateSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a97da34bb10ec4abee4cf43b4271da29a">llvm::objcopy::CommonConfig::UnneededSymbolsToRemove</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a09e6e864fb7b362b8437042529fdb5be">llvm::objcopy::CommonConfig::UpdateSection</a> and <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#aa784468f9faf20b0d54bbe644a0b94f0">llvm::object::coff_section::VirtualAddress</a>.</p>


<p>Referenced by <a href="#a03da0184bacf98a2a34f81413e7159b4">executeObjcopyOnBinary</a>.</p>

</div>
</div>

### isDebugSection() {#a00788ca1cb49affa89933d0eb01101da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::coff::isDebugSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/section">Section</a> &amp; Sec)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/section/#ab7fadec5aeb8eecc8049dfe85897ace9">llvm::objcopy::coff::Section::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#aaa859579ac4adb9cbcebf0ddc98a085b">handleArgs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobjcopy-cpp">COFFObjcopy.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/coff/coffobject-h">COFFObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
