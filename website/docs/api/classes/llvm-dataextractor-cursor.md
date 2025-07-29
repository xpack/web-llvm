---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dataextractor/cursor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Cursor` Class

<p>A class representing a position in a <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a>, as well as any error encountered during extraction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DataExtractor::Cursor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31389dac36fc08c2764c78ed1d79356d">DataExtractor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c89df5636eb7b6732c681000ab55264">Cursor</a> (uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a cursor for extraction from the given offset. <a href="#a0c89df5636eb7b6732c681000ab55264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8ea772bb8ca0473e3ecda933781962">operator bool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks whether the cursor is valid (i.e. <a href="#aaf8ea772bb8ca0473e3ecda933781962">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c134bb6de5493faf9c7076ef4dfcac">tell</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current position of this <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a>. <a href="#a22c134bb6de5493faf9c7076ef4dfcac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a117d933803fca18d08b4a4a3f2e266">seek</a> (uint64_t NewOffSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the cursor to the new offset. This does not impact the error state. <a href="#a8a117d933803fca18d08b4a4a3f2e266">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3453d69f4b4b74c0cf69808bc7d1c8b0">takeError</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return error contained inside this <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a>, if any. <a href="#a3453d69f4b4b74c0cf69808bc7d1c8b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a978e5074bb4515d21028c4fe300263b4">Offset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a580db043c4f247015cc1473c7a98c41c">Err</a></td>
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

<p>A class representing a position in a <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a>, as well as any error encountered during extraction.</p>


<p>It enables one to extract a sequence of values without error-checking and then checking for errors in bulk at the end. The class holds an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object, so failing to check the result of the parse will result in a runtime error. The error flag is sticky and will cause all subsequent extraction functions to fail without even attempting to parse and without updating the <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> offset. After clearing the error flag, one can again use the <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> object for parsing.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<div class="doxySectionDef">

## Friends

### DataExtractor {#a31389dac36fc08c2764c78ed1d79356d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Reference <a href="#a31389dac36fc08c2764c78ed1d79356d">DataExtractor</a>.</p>


<p>Referenced by <a href="#a31389dac36fc08c2764c78ed1d79356d">DataExtractor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Cursor() {#a0c89df5636eb7b6732c681000ab55264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DataExtractor::Cursor::Cursor (uint64_t Offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a cursor for extraction from the given offset.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aea6e51b13067f27d5b9bd39d1f44b670">llvm::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#aaf8ea772bb8ca0473e3ecda933781962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DataExtractor::Cursor::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks whether the cursor is valid (i.e.</p>


<p>no errors were encountered). In case of errors, this does not clear the error flag – one must call <a href="#a3453d69f4b4b74c0cf69808bc7d1c8b0">takeError()</a> instead.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### seek() {#a8a117d933803fca18d08b4a4a3f2e266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DataExtractor::Cursor::seek (uint64_t NewOffSet)</td>
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

<p>Set the cursor to the new offset. This does not impact the error state.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>

</div>
</div>

### takeError() {#a3453d69f4b4b74c0cf69808bc7d1c8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DataExtractor::Cursor::takeError ()</td>
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

<p>Return error contained inside this <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a>, if any.</p>


<p>Clears the internal <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> state.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a0752ad646759ea4a034a218da571ab8b">llvm::object::ELFFile&lt; ELFT &gt;::android_relas</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab0f852d38471e3013e30ec9c1241edfe">llvm::object::decodeCrel</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a5d63a698aa61a9d04d1826b1f91a0b43">llvm::DWARFDebugLine::Prologue::parse</a>.</p>

</div>
</div>

### tell() {#a22c134bb6de5493faf9c7076ef4dfcac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DataExtractor::Cursor::tell ()</td>
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

<p>Return the current position of this <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a>.</p>


<p>In the error state this is the position of the <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> before the first error was encountered.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1ec298d8a742a9519e6dc0903f822f2b">llvm::AMDGPUDisassembler::decodeKernelDescriptorDirective</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a5d63a698aa61a9d04d1826b1f91a0b43">llvm::DWARFDebugLine::Prologue::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#a817b6babbfd3e8ca145b869d93903f26">readULEB128As</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Err {#a580db043c4f247015cc1473c7a98c41c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DataExtractor::Cursor::Err</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>

</div>
</div>

### Offset {#a978e5074bb4515d21028c4fe300263b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DataExtractor::Cursor::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
