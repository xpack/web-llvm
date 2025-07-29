---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/tarwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `TarWriter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tarwriter-h">llvm/Support/TarWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/ustarheader">UstarHeader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/ustarheader">UstarHeader</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7196548a41a8c67a20f285e1957664e">makeUstarHeader</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6234057413147a09e2c1a0301ed7d452">formatPax</a> (StringRef Key, StringRef Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a498738d65e5a3c57d210f97b7a475d54">pad</a> (raw_fd_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe94ad0443f9d2332ed3867b2885f46">computeChecksum</a> (UstarHeader &amp;Hdr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21469ca51d37823d39509ab008a2a7d8">writePaxHeader</a> (raw_fd_ostream &amp;OS, StringRef Path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed916c3e798f8216e719e7509db44dff">splitUstar</a> (StringRef Path, StringRef &amp;Prefix, StringRef &amp;Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31dfcf5521eddbf141e3299c6e316c66">writeUstarHeader</a> (raw_fd_ostream &amp;OS, StringRef Prefix, StringRef Name, size_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac035f4156e2604bfa42ba22c17b83ee">BlockSize</a> = 512</td>
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

### computeChecksum() {#acbe94ad0443f9d2332ed3867b2885f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeChecksum (<a href="/web-llvm/docs/api/structs/ustarheader">UstarHeader</a> &amp; Hdr)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp">TarWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/ustarheader/#a4f3128c93a842d7ec13b49f98ff23565">UstarHeader::Checksum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a21469ca51d37823d39509ab008a2a7d8">writePaxHeader</a> and <a href="#a31dfcf5521eddbf141e3299c6e316c66">writeUstarHeader</a>.</p>

</div>
</div>

### formatPax() {#a6234057413147a09e2c1a0301ed7d452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string formatPax (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Val)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp">TarWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>


<p>Referenced by <a href="#a21469ca51d37823d39509ab008a2a7d8">writePaxHeader</a>.</p>

</div>
</div>

### makeUstarHeader() {#aa7196548a41a8c67a20f285e1957664e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UstarHeader makeUstarHeader ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp">TarWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/ustarheader/#ae947129034f6a78b9e4bc1ff88e30bce">UstarHeader::Magic</a> and <a href="/web-llvm/docs/api/structs/ustarheader/#ad4b9f44ee6ac76b66287bfc8387fd3d4">UstarHeader::Version</a>.</p>


<p>Referenced by <a href="#a21469ca51d37823d39509ab008a2a7d8">writePaxHeader</a> and <a href="#a31dfcf5521eddbf141e3299c6e316c66">writeUstarHeader</a>.</p>

</div>
</div>

### pad() {#a498738d65e5a3c57d210f97b7a475d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void pad (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp">TarWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="#aac035f4156e2604bfa42ba22c17b83ee">BlockSize</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a9e2a27de71f137279ac47e6edd4abc47">llvm::raw_fd_ostream::seek</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tarwriter/#a75d868e42d390e529a8b7aa0d41362ed">llvm::TarWriter::append</a> and <a href="#a21469ca51d37823d39509ab008a2a7d8">writePaxHeader</a>.</p>

</div>
</div>

### splitUstar() {#aed916c3e798f8216e719e7509db44dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool splitUstar (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Prefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp">TarWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/ustarheader/#a1fcc48d5a9dfbf9b8b005bfcfe0a8e04">UstarHeader::Name</a> and <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tarwriter/#a75d868e42d390e529a8b7aa0d41362ed">llvm::TarWriter::append</a>.</p>

</div>
</div>

### writePaxHeader() {#a21469ca51d37823d39509ab008a2a7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writePaxHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp">TarWriter.cpp</a>.</p>


<p>References <a href="#acbe94ad0443f9d2332ed3867b2885f46">computeChecksum</a>, <a href="#a6234057413147a09e2c1a0301ed7d452">formatPax</a>, <a href="#aa7196548a41a8c67a20f285e1957664e">makeUstarHeader</a>, <a href="#a498738d65e5a3c57d210f97b7a475d54">pad</a>, <a href="/web-llvm/docs/api/structs/ustarheader/#a846a37a8885b0fa9083c765a8aacef70">UstarHeader::Size</a> and <a href="/web-llvm/docs/api/structs/ustarheader/#ad52e2807fb021386c7ff17f210fddd0f">UstarHeader::TypeFlag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tarwriter/#a75d868e42d390e529a8b7aa0d41362ed">llvm::TarWriter::append</a>.</p>

</div>
</div>

### writeUstarHeader() {#a31dfcf5521eddbf141e3299c6e316c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeUstarHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, size_t Size)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp">TarWriter.cpp</a>.</p>


<p>References <a href="#acbe94ad0443f9d2332ed3867b2885f46">computeChecksum</a>, <a href="#aa7196548a41a8c67a20f285e1957664e">makeUstarHeader</a>, <a href="/web-llvm/docs/api/structs/ustarheader/#af2953283aeb2ff060470ac711d95d6ff">UstarHeader::Mode</a>, <a href="/web-llvm/docs/api/structs/ustarheader/#a1fcc48d5a9dfbf9b8b005bfcfe0a8e04">UstarHeader::Name</a>, <a href="/web-llvm/docs/api/structs/ustarheader/#a5dc8ba399254e5bcbd97a3ab215f02f3">UstarHeader::Prefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/ustarheader/#a846a37a8885b0fa9083c765a8aacef70">UstarHeader::Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tarwriter/#a75d868e42d390e529a8b7aa0d41362ed">llvm::TarWriter::append</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BlockSize {#aac035f4156e2604bfa42ba22c17b83ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int BlockSize = 512</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp">TarWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tarwriter/#a75d868e42d390e529a8b7aa0d41362ed">llvm::TarWriter::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a249763e47d375bbd4d125417d8d62728">llvm::msf::blockToOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#abe111677aa4b3df2bb68f54d4351a72d">llvm::msf::bytesToBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/lineprinter-cpp/#abb45fec195a32d6c9255a3d626d41771">computeBlockRuns</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a6c42cfee05f0fe24263048d961ca5d9b">anonymous{PPCBranchSelector.cpp}::PPCBSel::ComputeBlockSizes</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a1d0cc695b52f5a60416c542723f40b2f">llvm::msf::WritableMappedBlockStream::createStream</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvevptblockpass-cpp/#a173df60eae8081683241de7888b84be8">CreateVPTBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab04f9a9acf8cd97627dc9b522188b0e8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::emitMatrixMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad865338e071057b5d2a249902281063a">llvm::MachineFunction::estimateFunctionSizeInBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvevptblockpass-cpp/#a14d46fbaaffa4b6f6a1e4d51c5a4af62">GetInitialBlockMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#acb5e8cdebbda70dcd40a3c12c97ad649">llvm::msf::getNumFpmIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#aa83f310901cbf7688e792d7b1dcbd58f">llvm::pdb::PDBFileBuilder::initialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83f67cbf085fcd2c92b4e126c42c779e">llvm::isREVMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5ed6a1c7f9a09c16fc02c716d3f32f9">llvm::isVREVMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a670137fe83c1213c3c2e82b8144e9af3">isWideDUPMask</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#a1a4c51fe402b298829077a3295d892e3">llvm::pdb::PDBFileBuilder::operator=</a>, <a href="#a498738d65e5a3c57d210f97b7a475d54">pad</a> and <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a54041159b8c116fedec43c2b81807c41">llvm::msf::WritableMappedBlockStream::WritableMappedBlockStream</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
