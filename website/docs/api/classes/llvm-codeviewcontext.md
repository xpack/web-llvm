---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeviewcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CodeViewContext` Class Reference

<p>Holds state from .cv_file and .cv_loc directives for later emission. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CodeViewContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">llvm/MC/MCCodeView.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6732108d29794003ce82213108571835">CodeViewContext</a> (MCContext *MCCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3170fa30a2a74dbe2cdfddaaa1edb31">CodeViewContext</a> (const CodeViewContext &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeviewcontext">CodeViewContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f56fc0a158554f2b1ef6cdf754a76d1">operator=</a> (const CodeViewContext &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad02d00947f1c26cb88d05a8ac9ea8aaa">finish</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40a7e68d6b869a14cd6505e2963afcd">isValidFileNumber</a> (unsigned FileNumber) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a valid number for use with .cv_loc if we've already seen a .cv_file for it. <a href="#ae40a7e68d6b869a14cd6505e2963afcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63aca47ba5a5a2895c8ffd1e262ced59">addFile</a> (MCStreamer &amp;OS, unsigned FileNumber, StringRef Filename, ArrayRef&lt; uint8_t &gt; ChecksumBytes, uint8_t ChecksumKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b10e7a8e70b8cfea1eb3a1ef21f101">recordFunctionId</a> (unsigned FuncId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records the function id of a normal function. <a href="#a72b10e7a8e70b8cfea1eb3a1ef21f101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b7a64fbcdebe1bf6c4ad0bda073df4">recordInlinedCallSiteId</a> (unsigned FuncId, unsigned IAFunc, unsigned IAFile, unsigned IALine, unsigned IACol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records the function id of an inlined call site. <a href="#aa4b7a64fbcdebe1bf6c4ad0bda073df4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo">MCCVFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c19ae3d8fe0211fe3ae87659d9ee378">getCVFunctionInfo</a> (unsigned FuncId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retreive the function info if this is a valid function id, or nullptr. <a href="#a6c19ae3d8fe0211fe3ae87659d9ee378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a467266ca2ef14f8cf52c71ee80c42be2">recordCVLoc</a> (MCContext &amp;Ctx, const MCSymbol *Label, unsigned FunctionId, unsigned FileNo, unsigned Line, unsigned Column, bool PrologueEnd, bool IsStmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Saves the information from the currently parsed .cv_loc directive and sets CVLocSeen. <a href="#a467266ca2ef14f8cf52c71ee80c42be2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6bc6e5d8da43506f37b33b053192fc">addLineEntry</a> (const MCCVLoc &amp;LineEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a line entry. <a href="#a9d6bc6e5d8da43506f37b33b053192fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mccvloc">MCCVLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959bbaf3c63e93e00c5f5c2df6a1af19">getFunctionLineEntries</a> (unsigned FuncId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; size_t, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3df4fb482ededcf17bd2f83d00e660">getLineExtent</a> (unsigned FuncId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; size_t, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab789beed200191eaf4736b9ab5d734b1">getLineExtentIncludingInlinees</a> (unsigned FuncId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mccvloc">MCCVLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9043bbc90a9757b00951cfd2e37620">getLinesForExtent</a> (size_t L, size_t R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d5b340b9ff61eae3ea229bce6572678">emitLineTableForFunction</a> (MCObjectStreamer &amp;OS, unsigned FuncId, const MCSymbol *FuncBegin, const MCSymbol *FuncEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a line table substream. <a href="#a3d5b340b9ff61eae3ea229bce6572678">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1e5820b0d08f0ec7c8c66034df72edc">emitInlineLineTableForFunction</a> (MCObjectStreamer &amp;OS, unsigned PrimaryFunctionId, unsigned SourceFileId, unsigned SourceLineNum, const MCSymbol *FnStartSym, const MCSymbol *FnEndSym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c00c11ef810b9f4ca1781a341de60d3">encodeInlineLineTable</a> (const MCAssembler &amp;Asm, MCCVInlineLineTableFragment &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encodes the binary annotations once we have a layout. <a href="#a2c00c11ef810b9f4ca1781a341de60d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ad872779fc9a351f5a67722b370348">emitDefRange</a> (MCObjectStreamer &amp;OS, ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, StringRef FixedSizePortion)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea53ea050c3442abffd1c991f4c7213a">encodeDefRange</a> (const MCAssembler &amp;Asm, MCCVDefRangeFragment &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43adc5b7e0fcb43103dfe2e1acac4f2">emitStringTable</a> (MCObjectStreamer &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the string table substream. <a href="#ad43adc5b7e0fcb43103dfe2e1acac4f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43decaae146363e80c3ba5b685016bb5">emitFileChecksums</a> (MCObjectStreamer &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the file checksum substream. <a href="#a43decaae146363e80c3ba5b685016bb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ba925c2a5e09782525ede9dc691059">emitFileChecksumOffset</a> (MCObjectStreamer &amp;OS, unsigned FileNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the offset into the checksum table of the given file number. <a href="#a73ba925c2a5e09782525ede9dc691059">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af677ac4a1dd3fc158ef8e23a8811bc54">addToStringTable</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add something to the string table. <a href="#af677ac4a1dd3fc158ef8e23a8811bc54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb4c36520d3dfd625ea0bda895db13f">getStringTableOffset</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a string table offset. <a href="#aceb4c36520d3dfd625ea0bda895db13f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a559aa6b27def469f54a6ca1429afaa14">MCCtx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc28a8a76f9955e31dcc41b81c3becc5">StringTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from string to string table offset. <a href="#abc28a8a76f9955e31dcc41b81c3becc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdatafragment">MCDataFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45797bda284aba0a5e8bcc33aa4024bd">StrTabFragment</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The fragment that ultimately holds our strings. <a href="#a45797bda284aba0a5e8bcc33aa4024bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a8072b745c2577c863e05a2d2219607">StrTab</a> = {'\0'}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; FileInfo, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677b3f4852a5e663f90b9f44cab3a6aa">Files</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Array storing added file information. <a href="#a677b3f4852a5e663f90b9f44cab3a6aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, std::pair&lt; size_t, size_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36ad0c1886c290a5730bba6fd5f48a8">MCCVLineStartStop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The offset of the first and last .cv_loc directive for a given function id. <a href="#af36ad0c1886c290a5730bba6fd5f48a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mccvloc">MCCVLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68103ff8abbf84d23ee1aa977642c12">MCCVLines</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A collection of <a href="/web-llvm/docs/api/classes/llvm/mccvloc">MCCVLoc</a> for each section. <a href="#af68103ff8abbf84d23ee1aa977642c12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo">MCCVFunctionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c31ea1b7fff944b47de069e551c098f">Functions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All known functions and inlined call sites, indexed by function id. <a href="#a4c31ea1b7fff944b47de069e551c098f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1c1c9e5908ad7fa5106d1b84034618">ChecksumOffsetsAssigned</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate whether we have already laid out the checksum table addresses or not. <a href="#a4a1c1c9e5908ad7fa5106d1b84034618">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Holds state from .cv_file and .cv_loc directives for later emission.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CodeViewContext() {#a6732108d29794003ce82213108571835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeViewContext::CodeViewContext (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * MCCtx)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<p>Referenced by <a href="#ab3170fa30a2a74dbe2cdfddaaa1edb31">CodeViewContext</a> and <a href="#a5f56fc0a158554f2b1ef6cdf754a76d1">operator=</a>.</p>

</div>
</div>

### CodeViewContext() {#ab3170fa30a2a74dbe2cdfddaaa1edb31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeViewContext::CodeViewContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext">CodeViewContext</a> &amp; other)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<p>References <a href="#a6732108d29794003ce82213108571835">CodeViewContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a5f56fc0a158554f2b1ef6cdf754a76d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewContext &amp; llvm::CodeViewContext::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext">CodeViewContext</a> &amp; other)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<p>Reference <a href="#a6732108d29794003ce82213108571835">CodeViewContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFile() {#a63aca47ba5a5a2895c8ffd1e262ced59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeViewContext::addFile (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS, unsigned FileNumber, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; ChecksumBytes, uint8_t ChecksumKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="#af677ac4a1dd3fc158ef8e23a8811bc54">addToStringTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a33c2e7b8c7463f2698a3132452cc4d12">llvm::MCStreamer::emitCVFileDirective</a>.</p>

</div>
</div>

### addLineEntry() {#a9d6bc6e5d8da43506f37b33b053192fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::addLineEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccvloc">MCCVLoc</a> &amp; LineEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a line entry.</p>

<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccvloc/#af1f5888094a284b7e63433a23deb5c1a">llvm::MCCVLoc::getFunctionId</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a467266ca2ef14f8cf52c71ee80c42be2">recordCVLoc</a>.</p>

</div>
</div>

### addToStringTable() {#af677ac4a1dd3fc158ef8e23a8811bc54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; StringRef, unsigned &gt; CodeViewContext::addToStringTable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add something to the string table.</p>


<p>Returns the final string as well as offset into the string table.</p>


<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>Referenced by <a href="#a63aca47ba5a5a2895c8ffd1e262ced59">addFile</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#ac60cbf99d76cbbbbc3c094a7d78fb834">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::emitFrameDataRecord</a>.</p>

</div>
</div>

### emitDefRange() {#af2ad872779fc9a351f5a67722b370348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * CodeViewContext::emitDefRange (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FixedSizePortion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a7f014c82821d76aff471c10829f336c6">llvm::MCObjectStreamer::emitCVDefRangeDirective</a>.</p>

</div>
</div>

### emitFileChecksumOffset() {#a73ba925c2a5e09782525ede9dc691059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::emitFileChecksumOffset (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS, unsigned FileNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits the offset into the checksum table of the given file number.</p>

<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7865bd61cd2c65b2d94c58dd1523bb75">llvm::MCStreamer::emitSymbolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#adf42e6aacb6951ef0ed334e1526d7678">llvm::MCObjectStreamer::emitCVFileChecksumOffsetDirective</a>.</p>

</div>
</div>

### emitFileChecksums() {#a43decaae146363e80c3ba5b685016bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::emitFileChecksums (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits the file checksum substream.</p>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afe30d1dfbe988401ae6ded700dd877bc">llvm::MCObjectStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a2cff84e102389b6f127a6051d9ff062a">llvm::MCObjectStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9924d739e3dc812b561931a1ad6eb5cf">llvm::MCObjectStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a21d70037ecf679b5f8d13af07f8f136a">llvm::MCObjectStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa7e535ad489b8edccb926a573844dd1c8">llvm::codeview::FileChecksums</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#af3ddec166c838e59362d5b7a85f50384">llvm::MCObjectStreamer::emitCVFileChecksumsDirective</a>.</p>

</div>
</div>

### emitInlineLineTableForFunction() {#ac1e5820b0d08f0ec7c8c66034df72edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::emitInlineLineTableForFunction (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS, unsigned PrimaryFunctionId, unsigned SourceFileId, unsigned SourceLineNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnStartSym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnEndSym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3590fc09ce2f93b9c19c488fb5cc3645">llvm::MCObjectStreamer::emitCVInlineLinetableDirective</a>.</p>

</div>
</div>

### emitLineTableForFunction() {#a3d5b340b9ff61eae3ea229bce6572678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::emitLineTableForFunction (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS, unsigned FuncId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FuncBegin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FuncEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits a line table substream.</p>

<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64eafd6bed9f342e423e74a93223135c">llvm::MCStreamer::AddComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afe30d1dfbe988401ae6ded700dd877bc">llvm::MCObjectStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a714de05372be0237bac97ad800dd2b52">llvm::MCStreamer::emitCOFFSecRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a825998894ce032cf0eb7c76df0c1050b">llvm::MCStreamer::emitCOFFSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#adf42e6aacb6951ef0ed334e1526d7678">llvm::MCObjectStreamer::emitCVFileChecksumOffsetDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d412a2cef594fc0f45de176d51fee3b">llvm::MCStreamer::emitInt16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9924d739e3dc812b561931a1ad6eb5cf">llvm::MCObjectStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvloc/#ae04e7499c14a2f64a949fba666f04b1b">llvm::MCCVLoc::getColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="#a959bbaf3c63e93e00c5f5c2df6a1af19">getFunctionLineEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3871bade894b1a946ca1e99876b79b26a2bd22ec907c4c8a5e437e96d426ee4e8">llvm::codeview::LF_HaveColumns</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afaa0b0293a2db49f5f93c15a62e095c819">llvm::codeview::Lines</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/lineinfo/#a61ee4e4da32bcded51540eecc08224d2a1181e4a1a533198a7dc59872a9c1e873">llvm::codeview::LineInfo::StatementFlag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#af86cdbc272816dffaa30c62bdd8ec4b1">llvm::MCObjectStreamer::emitCVLinetableDirective</a>.</p>

</div>
</div>

### emitStringTable() {#ad43adc5b7e0fcb43103dfe2e1acac4f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::emitStringTable (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits the string table substream.</p>

<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afe30d1dfbe988401ae6ded700dd877bc">llvm::MCObjectStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9924d739e3dc812b561931a1ad6eb5cf">llvm::MCObjectStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a21d70037ecf679b5f8d13af07f8f136a">llvm::MCObjectStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afafee465e31ac15d7b21d8ca9d6f5ac685">llvm::codeview::StringTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3b37cee5f8e850d8bbe6e9086a4e3733">llvm::MCObjectStreamer::emitCVStringTableDirective</a>.</p>

</div>
</div>

### encodeDefRange() {#aea53ea050c3442abffd1c991f4c7213a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::encodeDefRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/mccvdefrangefragment">MCCVDefRangeFragment</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp/#a2ea528bf7b0254b3ae2e1c0864022767">computeLabelDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a128346d352fde2e704c07867f4d82eef">llvm::FK_SecRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a8b2acba82b6d0830ab47d67eb8f1ccf0">llvm::FK_SecRel_4</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#adeb8e72f8eb5703650627d39457436dd">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getContents</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvdefrangefragment/#a6ac329b00989fb4830246ea923755597">llvm::MCCVDefRangeFragment::getFixedSizePortion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#a8a0daac469ed602d68174c8efae89b22">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvdefrangefragment/#a3959776b75cad0ae0cb14c16b2454150">llvm::MCCVDefRangeFragment::getRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a25ab8c1ee55e8f8046faa4da99da5f55a2fa4bac49a23af56c1a3fcd0da807d44">llvm::codeview::MaxDefRange</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#a16a69d4248bb11c84536099421ea833b">llvm::support::endian::Writer::write</a>.</p>

</div>
</div>

### encodeInlineLineTable() {#a2c00c11ef810b9f4ca1781a341de60d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::encodeInlineLineTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/mccvinlinelinetablefragment">MCCVInlineLineTableFragment</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encodes the binary annotations once we have a layout.</p>

<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372a9247192b52c418519a5f4cc82d460ffb">llvm::codeview::ChangeCodeLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372ac8d46e9b8b90465f265a773672338e70">llvm::codeview::ChangeCodeOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372afd958fe410ae43d1681f8802c0ec60c9">llvm::codeview::ChangeCodeOffsetAndLineOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372a235411def9e0c5f5a4bad7f98275eb48">llvm::codeview::ChangeFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372a8bb0c4a1dc3752b8f6edaea47d1bdb22">llvm::codeview::ChangeLineOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp/#ab3c3e06f7218bbfcf31026d85093efe7">compressAnnotation</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp/#a2ea528bf7b0254b3ae2e1c0864022767">computeLabelDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp/#a86e96a17356fc996c7ea03da984278bb">encodeSignedNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/lineinfo/#a3f109bbdca3146660390d3861c62e25e">llvm::MCCVFunctionInfo::LineInfo::File</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvinlinelinetablefragment/#ae86bb039576981f531b8ebed7eeb20aa">llvm::MCCVInlineLineTableFragment::getContents</a>, <a href="#a6c19ae3d8fe0211fe3ae87659d9ee378">getCVFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvinlinelinetablefragment/#ad5b6fb85f5bff2aa22a04c1c24722d15">llvm::MCCVInlineLineTableFragment::getFnEndSym</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvinlinelinetablefragment/#a8fc66977127329e7998c6c3b4e3b9359">llvm::MCCVInlineLineTableFragment::getFnStartSym</a>, <a href="#ab789beed200191eaf4736b9ab5d734b1">getLineExtentIncludingInlinees</a>, <a href="#a0c9043bbc90a9757b00951cfd2e37620">getLinesForExtent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/#ae30c8d77d4c26d16cc60ebd3de0f3b26">llvm::MCCVFunctionInfo::InlinedAtMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/lineinfo/#a12648fbbd9e74ae78fb374d36bda03dd">llvm::MCCVFunctionInfo::LineInfo::Line</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a77953260dd85922d9583bf426f89787aa30d8ae376cd42fd999ac8713cf85be2e">llvm::codeview::MaxRecordLength</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvloc/#a09de150a6b6188dce119ce08d5c64611">llvm::MCCVLoc::setFileNum</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvloc/#add0f1662df4919cd84703ac02dd63eca">llvm::MCCVLoc::setLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvloc/#af82b54ed7acf156dd92d0f31eab03731">llvm::MCCVLoc::setLine</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### finish() {#ad02d00947f1c26cb88d05a8ac9ea8aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::finish ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a7f964c60245b61612ddd6509cba7eb74">llvm::MCWinCOFFStreamer::finishImpl</a>.</p>

</div>
</div>

### getCVFunctionInfo() {#a6c19ae3d8fe0211fe3ae87659d9ee378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCVFunctionInfo * CodeViewContext::getCVFunctionInfo (unsigned FuncId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retreive the function info if this is a valid function id, or nullptr.</p>

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a79e4fddfcfc0d5ed30a1b811fcd17a6e">llvm::MCStreamer::checkCVLocSection</a>, <a href="#a2c00c11ef810b9f4ca1781a341de60d3">encodeInlineLineTable</a>, <a href="#a959bbaf3c63e93e00c5f5c2df6a1af19">getFunctionLineEntries</a>, <a href="#ab789beed200191eaf4736b9ab5d734b1">getLineExtentIncludingInlinees</a> and <a href="#aa4b7a64fbcdebe1bf6c4ad0bda073df4">recordInlinedCallSiteId</a>.</p>

</div>
</div>

### getFunctionLineEntries() {#a959bbaf3c63e93e00c5f5c2df6a1af19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; MCCVLoc &gt; CodeViewContext::getFunctionLineEntries (unsigned FuncId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="#a6c19ae3d8fe0211fe3ae87659d9ee378">getCVFunctionInfo</a>, <a href="#ab789beed200191eaf4736b9ab5d734b1">getLineExtentIncludingInlinees</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/#ae30c8d77d4c26d16cc60ebd3de0f3b26">llvm::MCCVFunctionInfo::InlinedAtMap</a>.</p>


<p>Referenced by <a href="#a3d5b340b9ff61eae3ea229bce6572678">emitLineTableForFunction</a>.</p>

</div>
</div>

### getLineExtent() {#a0e3df4fb482ededcf17bd2f83d00e660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; size_t, size_t &gt; CodeViewContext::getLineExtent (unsigned FuncId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ab789beed200191eaf4736b9ab5d734b1">getLineExtentIncludingInlinees</a>.</p>

</div>
</div>

### getLineExtentIncludingInlinees() {#ab789beed200191eaf4736b9ab5d734b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; size_t, size_t &gt; CodeViewContext::getLineExtentIncludingInlinees (unsigned FuncId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="#a6c19ae3d8fe0211fe3ae87659d9ee378">getCVFunctionInfo</a>, <a href="#a0e3df4fb482ededcf17bd2f83d00e660">getLineExtent</a> and <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/#ae30c8d77d4c26d16cc60ebd3de0f3b26">llvm::MCCVFunctionInfo::InlinedAtMap</a>.</p>


<p>Referenced by <a href="#a2c00c11ef810b9f4ca1781a341de60d3">encodeInlineLineTable</a> and <a href="#a959bbaf3c63e93e00c5f5c2df6a1af19">getFunctionLineEntries</a>.</p>

</div>
</div>

### getLinesForExtent() {#a0c9043bbc90a9757b00951cfd2e37620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCCVLoc &gt; CodeViewContext::getLinesForExtent (size_t L, size_t R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>


<p>Referenced by <a href="#a2c00c11ef810b9f4ca1781a341de60d3">encodeInlineLineTable</a>.</p>

</div>
</div>

### isValidFileNumber() {#ae40a7e68d6b869a14cd6505e2963afcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeViewContext::isValidFileNumber (unsigned FileNumber)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a valid number for use with .cv_loc if we've already seen a .cv_file for it.</p>

<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>

</div>
</div>

### recordCVLoc() {#a467266ca2ef14f8cf52c71ee80c42be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewContext::recordCVLoc (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label, unsigned FunctionId, unsigned FileNo, unsigned Line, unsigned Column, bool PrologueEnd, bool IsStmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Saves the information from the currently parsed .cv_loc directive and sets CVLocSeen.</p>


<p>When the next instruction is assembled an entry in the line number table with this information and the address of the instruction will be created.</p>


<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>Reference <a href="#a9d6bc6e5d8da43506f37b33b053192fc">addLineEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a61b27602b6cd429e5c1e226117c6da67">llvm::MCObjectStreamer::emitCVLocDirective</a>.</p>

</div>
</div>

### recordFunctionId() {#a72b10e7a8e70b8cfea1eb3a1ef21f101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeViewContext::recordFunctionId (unsigned FuncId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records the function id of a normal function.</p>


<p>Returns false if the function id has already been used, and true otherwise.</p>


<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/#a483f476cd95fc83549dce653648091bbab32b95a936d6a5df6c580b24b5a4b1f1">llvm::MCCVFunctionInfo::FunctionSentinel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a13ac5fe9bbe382dd5e366288ba91fa43">llvm::MCStreamer::emitCVFuncIdDirective</a>.</p>

</div>
</div>

### recordInlinedCallSiteId() {#aa4b7a64fbcdebe1bf6c4ad0bda073df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeViewContext::recordInlinedCallSiteId (unsigned FuncId, unsigned IAFunc, unsigned IAFile, unsigned IALine, unsigned IACol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records the function id of an inlined call site.</p>


<p>Records the "inlined at" location info of the call site, including what function or inlined call site it was inlined into. Returns false if the function id has already been used, and true otherwise.</p>


<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/lineinfo/#adb775109e03894433d2ae9a43844f6eb">llvm::MCCVFunctionInfo::LineInfo::Col</a>, <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/lineinfo/#a3f109bbdca3146660390d3861c62e25e">llvm::MCCVFunctionInfo::LineInfo::File</a>, <a href="#a6c19ae3d8fe0211fe3ae87659d9ee378">getCVFunctionInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/lineinfo/#a12648fbbd9e74ae78fb374d36bda03dd">llvm::MCCVFunctionInfo::LineInfo::Line</a> and <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/#a6501b119f7ba7b15237d1f43dd16ccbc">llvm::MCCVFunctionInfo::ParentFuncIdPlusOne</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aea7cedf9c3df1534425168ee9969871c">llvm::MCStreamer::emitCVInlineSiteIdDirective</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getStringTableOffset() {#aceb4c36520d3dfd625ea0bda895db13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CodeViewContext::getStringTableOffset (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a string table offset.</p>

<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ChecksumOffsetsAssigned {#a4a1c1c9e5908ad7fa5106d1b84034618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeViewContext::ChecksumOffsetsAssigned = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate whether we have already laid out the checksum table addresses or not.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

### Files {#a677b3f4852a5e663f90b9f44cab3a6aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;FileInfo, 4&gt; llvm::CodeViewContext::Files</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Array storing added file information.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

### Functions {#a4c31ea1b7fff944b47de069e551c098f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MCCVFunctionInfo&gt; llvm::CodeViewContext::Functions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All known functions and inlined call sites, indexed by function id.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

### MCCtx {#a559aa6b27def469f54a6ca1429afaa14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext* llvm::CodeViewContext::MCCtx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

### MCCVLines {#af68103ff8abbf84d23ee1aa977642c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MCCVLoc&gt; llvm::CodeViewContext::MCCVLines</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A collection of <a href="/web-llvm/docs/api/classes/llvm/mccvloc">MCCVLoc</a> for each section.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

### MCCVLineStartStop {#af36ad0c1886c290a5730bba6fd5f48a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, std::pair&lt;size_t, size_t&gt; &gt; llvm::CodeViewContext::MCCVLineStartStop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The offset of the first and last .cv_loc directive for a given function id.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

### StringTable {#abc28a8a76f9955e31dcc41b81c3becc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned&gt; llvm::CodeViewContext::StringTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from string to string table offset.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

### StrTab {#a5a8072b745c2577c863e05a2d2219607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;char, 0&gt; llvm::CodeViewContext::StrTab = {'\0'}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

### StrTabFragment {#a45797bda284aba0a5e8bcc33aa4024bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDataFragment* llvm::CodeViewContext::StrTabFragment = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The fragment that ultimately holds our strings.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp">MCCodeView.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
