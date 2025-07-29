---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvreaderhandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LVReaderHandler` Class



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVReaderHandler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">llvm/DebugInfo/LogicalView/LVReaderHandler.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8575d32d94456504e295f45cd2a5ad3d">LVReaderHandler</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dfb6dcf26b385963a2173d60a39ebaf">LVReaderHandler</a> (ArgVector &amp;Objects, ScopedPrinter &amp;W, LVOptions &amp;ReaderOptions)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab63cd266e6eb95b9674dc12253cbb8ea">LVReaderHandler</a> (const LVReaderHandler &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreaderhandler">LVReaderHandler</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa480522f8645aa79e400216f3e1b1492">operator=</a> (const LVReaderHandler &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4c51a1f9e6096d272656850d480078">createReader</a> (StringRef Filename, LVReaders &amp;Readers)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e264d08d01c80cc51982befc59eb6c3">process</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader">LVReader</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c73b152ea886d86f13160820e4b758">createReader</a> (StringRef Pathname)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8100326175da04d91e51ef5cbaf2b01b">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac70ac2d120eea93633680f1155a55037">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac09f0c7754ac2c529417c3a504b8f1d1">createReaders</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8941bd7eda515bd1e7eaac800360fe6">printReaders</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4855d9511c9636960fcb42a92e86d94">compareReaders</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707ee6d45375c0ae9b23595904e35d82">handleArchive</a> (LVReaders &amp;Readers, StringRef Filename, object::Archive &amp;Arch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a0a2e65a4c747e32e44ebb15ebb8ba">handleBuffer</a> (LVReaders &amp;Readers, StringRef Filename, MemoryBufferRef Buffer, StringRef ExePath={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fbb906aebc200da24fed07a9224b56a">handleFile</a> (LVReaders &amp;Readers, StringRef Filename, StringRef ExePath={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace719680c9e0d0b9434241aea4717802">handleMach</a> (LVReaders &amp;Readers, StringRef Filename, object::MachOUniversalBinary &amp;Mach)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d242d56044538b8461d3d2f2839d4c">handleObject</a> (LVReaders &amp;Readers, StringRef Filename, object::Binary &amp;Binary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a849da2c17f236c79cdc24e302b8acd25">handleObject</a> (LVReaders &amp;Readers, StringRef Filename, StringRef Buffer, StringRef ExePath)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf03c2113c03c9b0020ebf08045c8039">createReader</a> (StringRef Filename, LVReaders &amp;Readers, PdbOrObj &amp;Input, StringRef FileFormatName, StringRef ExePath={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ac73729dedc69cf806247950862a2d102">ArgVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b267902289c2d0de513140673043d6b">Objects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6735d487c0a54f57d120eeb375317a8b">W</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa19ee2952b555c86bfc99dce3634c785">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a337a8b60c1263ff7845edd8061455c01">LVReaders</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c9a53e5fc1ff9c99a4e5098da3dbf67">TheReaders</a></td>
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


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LVReaderHandler() {#a8575d32d94456504e295f45cd2a5ad3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVReaderHandler::LVReaderHandler ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>


<p>Referenced by <a href="#ab63cd266e6eb95b9674dc12253cbb8ea">LVReaderHandler</a> and <a href="#aa480522f8645aa79e400216f3e1b1492">operator=</a>.</p>

</div>
</div>

### LVReaderHandler() {#a3dfb6dcf26b385963a2173d60a39ebaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVReaderHandler::LVReaderHandler (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ac73729dedc69cf806247950862a2d102">ArgVector</a> &amp; Objects, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvoptions">LVOptions</a> &amp; ReaderOptions)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a2db520a2a4d7186c15c841cb81e93354">llvm::logicalview::setOptions</a>.</p>

</div>
</div>

### LVReaderHandler() {#ab63cd266e6eb95b9674dc12253cbb8ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVReaderHandler::LVReaderHandler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreaderhandler">LVReaderHandler</a> &amp;)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>


<p>Reference <a href="#a8575d32d94456504e295f45cd2a5ad3d">LVReaderHandler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aa480522f8645aa79e400216f3e1b1492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVReaderHandler &amp; llvm::logicalview::LVReaderHandler::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreaderhandler">LVReaderHandler</a> &amp;)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>


<p>Reference <a href="#a8575d32d94456504e295f45cd2a5ad3d">LVReaderHandler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createReader() {#a6f4c51a1f9e6096d272656850d480078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::logicalview::LVReaderHandler::createReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a337a8b60c1263ff7845edd8061455c01">LVReaders</a> &amp; Readers)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa1351017ac6423911223bc19a8cb7c653">llvm::logicalview::Filename</a>.</p>

</div>
</div>

### createReader() {#a93c73b152ea886d86f13160820e4b758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; LVReader &gt; &gt; llvm::logicalview::LVReaderHandler::createReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pathname)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa10b38d3f13f0f2c533f5ce5616b017b5">llvm::logicalview::Pathname</a>.</p>

</div>
</div>

### dump() {#ac70ac2d120eea93633680f1155a55037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReaderHandler::dump ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a8100326175da04d91e51ef5cbaf2b01b">print</a>.</p>

</div>
</div>

### print() {#a8100326175da04d91e51ef5cbaf2b01b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVReaderHandler::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>


<p>Referenced by <a href="#ac70ac2d120eea93633680f1155a55037">dump</a>.</p>

</div>
</div>

### process() {#a9e264d08d01c80cc51982befc59eb6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::process ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### compareReaders() {#ae4855d9511c9636960fcb42a92e86d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::compareReaders ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

### createReader() {#adf03c2113c03c9b0020ebf08045c8039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::createReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a337a8b60c1263ff7845edd8061455c01">LVReaders</a> &amp; Readers, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad6a5e913488f632cb1200b989b8131b3">PdbOrObj</a> &amp; Input, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileFormatName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExePath={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

### createReaders() {#ac09f0c7754ac2c529417c3a504b8f1d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::createReaders ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

### handleArchive() {#a707ee6d45375c0ae9b23595904e35d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::handleArchive (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a337a8b60c1263ff7845edd8061455c01">LVReaders</a> &amp; Readers, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/object/archive">object::Archive</a> &amp; Arch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

### handleBuffer() {#a31a0a2e65a4c747e32e44ebb15ebb8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::handleBuffer (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a337a8b60c1263ff7845edd8061455c01">LVReaders</a> &amp; Readers, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExePath={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

### handleFile() {#a1fbb906aebc200da24fed07a9224b56a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::handleFile (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a337a8b60c1263ff7845edd8061455c01">LVReaders</a> &amp; Readers, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExePath={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

### handleMach() {#ace719680c9e0d0b9434241aea4717802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::handleMach (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a337a8b60c1263ff7845edd8061455c01">LVReaders</a> &amp; Readers, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary">object::MachOUniversalBinary</a> &amp; Mach)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

### handleObject() {#a19d242d56044538b8461d3d2f2839d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::handleObject (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a337a8b60c1263ff7845edd8061455c01">LVReaders</a> &amp; Readers, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/object/binary">object::Binary</a> &amp; Binary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

### handleObject() {#a849da2c17f236c79cdc24e302b8acd25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::handleObject (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a337a8b60c1263ff7845edd8061455c01">LVReaders</a> &amp; Readers, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

### printReaders() {#ad8941bd7eda515bd1e7eaac800360fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReaderHandler::printReaders ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Objects {#a0b267902289c2d0de513140673043d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgVector&amp; llvm::logicalview::LVReaderHandler::Objects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>

</div>
</div>

### OS {#aa19ee2952b555c86bfc99dce3634c785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::logicalview::LVReaderHandler::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>

</div>
</div>

### TheReaders {#a3c9a53e5fc1ff9c99a4e5098da3dbf67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVReaders llvm::logicalview::LVReaderHandler::TheReaders</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>

</div>
</div>

### W {#a6735d487c0a54f57d120eeb375317a8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedPrinter&amp; llvm::logicalview::LVReaderHandler::W</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/lvreaderhandler-h">LVReaderHandler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp">LVReaderHandler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
