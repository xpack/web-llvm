---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/xcoff/xcoffwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `XCOFFWriter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::xcoff::XCOFFWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">ObjCopy/XCOFF/XCOFFWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f95f07ae12369a47277ec4ac1ef834">XCOFFWriter</a> (Object &amp;Obj, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78df16d86f31927e7f6f53de34594704">~XCOFFWriter</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3adedc8850f537a3ba8e71bba9d9934">write</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05236ffe1d43bb12e1aff0d200d5179d">finalizeHeaders</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452ecde6ffb29e163123985a1076a4df">finalizeSections</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac858d0c751c781d404eb4c8e108500ef">finalizeSymbolStringTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc2ec07e99fdb06d30b639cc2fcf3864">finalize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadee2dd2246f5dc9b16c665285f7dab9">writeHeaders</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb5d1a5be88e3d0245b91a987add1ea3">writeSections</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0d149b501169c4cdb1bf12d19b087c">writeSymbolStringTable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/xcoff/object">Object</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6ec186dc6c5cbbf1a983134dc1e80a">Obj</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ff542c16b9e5853217e793a55c0651">Out</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a258d9ea01191e6901a71c2019e84bbf1">Buf</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bb05a194560f0b71e0032d8a33fa13f">FileSize</a></td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### XCOFFWriter() {#ac6f95f07ae12369a47277ec4ac1ef834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::xcoff::XCOFFWriter::XCOFFWriter (<a href="/web-llvm/docs/api/structs/llvm/objcopy/xcoff/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~XCOFFWriter() {#a78df16d86f31927e7f6f53de34594704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::objcopy::xcoff::XCOFFWriter::~XCOFFWriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### write() {#af3adedc8850f537a3ba8e71bba9d9934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::objcopy::xcoff::XCOFFWriter::write ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-cpp">XCOFFWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp/#a8e08eb3768ea6054b445ad1e5f0b9bba">finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a3ba0db4e545291ac0dbf07804f13d351">llvm::WritableMemoryBuffer::getNewMemBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baafdb5594dc3e484fc1bfd7c564d550c1">llvm::not_enough_memory</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/xcoff/#a7de8195508237e49f93b19619c37707b">llvm::objcopy::xcoff::executeObjcopyOnBinary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### finalize() {#adc2ec07e99fdb06d30b639cc2fcf3864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::xcoff::XCOFFWriter::finalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-cpp">XCOFFWriter.cpp</a>.</p>

</div>
</div>

### finalizeHeaders() {#a05236ffe1d43bb12e1aff0d200d5179d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::xcoff::XCOFFWriter::finalizeHeaders ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-cpp">XCOFFWriter.cpp</a>.</p>

</div>
</div>

### finalizeSections() {#a452ecde6ffb29e163123985a1076a4df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::xcoff::XCOFFWriter::finalizeSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-cpp">XCOFFWriter.cpp</a>.</p>

</div>
</div>

### finalizeSymbolStringTable() {#ac858d0c751c781d404eb4c8e108500ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::xcoff::XCOFFWriter::finalizeSymbolStringTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-cpp">XCOFFWriter.cpp</a>.</p>

</div>
</div>

### writeHeaders() {#aadee2dd2246f5dc9b16c665285f7dab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::xcoff::XCOFFWriter::writeHeaders ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-cpp">XCOFFWriter.cpp</a>.</p>

</div>
</div>

### writeSections() {#aeb5d1a5be88e3d0245b91a987add1ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::xcoff::XCOFFWriter::writeSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-cpp">XCOFFWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolStringTable() {#aec0d149b501169c4cdb1bf12d19b087c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::xcoff::XCOFFWriter::writeSymbolStringTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-cpp">XCOFFWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buf {#a258d9ea01191e6901a71c2019e84bbf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;WritableMemoryBuffer&gt; llvm::objcopy::xcoff::XCOFFWriter::Buf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>.</p>

</div>
</div>

### FileSize {#a7bb05a194560f0b71e0032d8a33fa13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::objcopy::xcoff::XCOFFWriter::FileSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>.</p>

</div>
</div>

### Obj {#a5d6ec186dc6c5cbbf1a983134dc1e80a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Object&amp; llvm::objcopy::xcoff::XCOFFWriter::Obj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>.</p>

</div>
</div>

### Out {#ae0ff542c16b9e5853217e793a55c0651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::objcopy::xcoff::XCOFFWriter::Out</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-cpp">XCOFFWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/xcoff/xcoffwriter-h">XCOFFWriter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
