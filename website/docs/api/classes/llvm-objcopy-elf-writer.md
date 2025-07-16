---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/elf/writer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Writer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::elf::Writer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ObjCopy/ELF/ELFObject.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter">ASCIIHexWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter">BinaryWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter">ELFWriter&lt;ELFT&gt;</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc515804e993cd6a1a37563b8ef05e1e">Writer</a> (Object &amp;O, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f57399b94731301d267ce10a2f52ea3">~Writer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce9ed786d6d6e992ca993389d338b74">finalize</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726d996516b35a7aaa997a8b010d8b00">write</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4df0d78579a2c7fae094d28ce9c3db8">Obj</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa60fbd08f1b1c6a7b9ce0b1e16ce6cb">Buf</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eee844a4c9e81d73a4771d162451471">Out</a></td>
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


<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Writer() {#afc515804e993cd6a1a37563b8ef05e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::elf::Writer::Writer (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>References <a href="#ad4df0d78579a2c7fae094d28ce9c3db8">Obj</a> and <a href="#a6eee844a4c9e81d73a4771d162451471">Out</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6250f22b5051b9ae63b3b6ef41b71edc">llvm::objcopy::elf::ASCIIHexWriter::ASCIIHexWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#a5f1e13881db470bb91ec7f5520ac2567">llvm::objcopy::elf::BinaryWriter::BinaryWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#ae97e9215e822175765b32148e0e329c9">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::ELFWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexwriter/#a55b825280ca6a39c6efb5dbe112deb24">llvm::objcopy::elf::IHexWriter::write</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecwriter/#a7a24531cda5be105db8d81756a3a9705">llvm::objcopy::elf::SRECWriter::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Writer() {#a6f57399b94731301d267ce10a2f52ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Writer::~Writer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalize() {#a6ce9ed786d6d6e992ca993389d338b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::objcopy::elf::Writer::finalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#ac889c429edbee2b4f43a2292ecb1ceb0">writeOutput</a>.</p>

</div>
</div>

### write() {#a726d996516b35a7aaa997a8b010d8b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::objcopy::elf::Writer::write ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#ac889c429edbee2b4f43a2292ecb1ceb0">writeOutput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Buf {#afa60fbd08f1b1c6a7b9ce0b1e16ce6cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;WritableMemoryBuffer&gt; llvm::objcopy::elf::Writer::Buf</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#ae97e9215e822175765b32148e0e329c9">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::ELFWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6c8bb3c922ce45c595377546d41f1222">llvm::objcopy::elf::ASCIIHexWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#a5b9da0f3636f00c8eb9dca28bf21e606">llvm::objcopy::elf::BinaryWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#a96ec94d70c19707787f756fa97cc3467">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#ac4946ac3df4a88e078136a4444ef1185">llvm::objcopy::elf::BinaryWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#afba8988590ae275a08b0efd42c27d274">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexwriter/#a55b825280ca6a39c6efb5dbe112deb24">llvm::objcopy::elf::IHexWriter::write</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecwriter/#a7a24531cda5be105db8d81756a3a9705">llvm::objcopy::elf::SRECWriter::write</a>.</p>

</div>
</div>

### Obj {#ad4df0d78579a2c7fae094d28ce9c3db8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Object&amp; llvm::objcopy::elf::Writer::Obj</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6250f22b5051b9ae63b3b6ef41b71edc">llvm::objcopy::elf::ASCIIHexWriter::ASCIIHexWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#a5f1e13881db470bb91ec7f5520ac2567">llvm::objcopy::elf::BinaryWriter::BinaryWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#ae97e9215e822175765b32148e0e329c9">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::ELFWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6c8bb3c922ce45c595377546d41f1222">llvm::objcopy::elf::ASCIIHexWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#a5b9da0f3636f00c8eb9dca28bf21e606">llvm::objcopy::elf::BinaryWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#a96ec94d70c19707787f756fa97cc3467">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexwriter/#a1c7e741201eefaddfbf5fb826ac2b903">llvm::objcopy::elf::IHexWriter::IHexWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecwriter/#ac8e6360aacf87a88ee8ef1f09c704868">llvm::objcopy::elf::SRECWriter::SRECWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#ac4946ac3df4a88e078136a4444ef1185">llvm::objcopy::elf::BinaryWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecwriter/#a7a24531cda5be105db8d81756a3a9705">llvm::objcopy::elf::SRECWriter::write</a> and <a href="#afc515804e993cd6a1a37563b8ef05e1e">Writer</a>.</p>

</div>
</div>

### Out {#a6eee844a4c9e81d73a4771d162451471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::objcopy::elf::Writer::Out</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#a5f1e13881db470bb91ec7f5520ac2567">llvm::objcopy::elf::BinaryWriter::BinaryWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexwriter/#a1c7e741201eefaddfbf5fb826ac2b903">llvm::objcopy::elf::IHexWriter::IHexWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#ac4946ac3df4a88e078136a4444ef1185">llvm::objcopy::elf::BinaryWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#afba8988590ae275a08b0efd42c27d274">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexwriter/#a55b825280ca6a39c6efb5dbe112deb24">llvm::objcopy::elf::IHexWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecwriter/#a7a24531cda5be105db8d81756a3a9705">llvm::objcopy::elf::SRECWriter::write</a> and <a href="#afc515804e993cd6a1a37563b8ef05e1e">Writer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
