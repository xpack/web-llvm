---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarffile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DwarfFile` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DwarfFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">CodeGen/AsmPrinter/DwarfFile.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c8d7ebae33cd232e94c79e0e7be59a">LabelList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbglabel">DbgLabel</a> *, 4 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of DbgLabels of each lexical scope. <a href="#a70c8d7ebae33cd232e94c79e0e7be59a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae72bc6de8d7034ef61711dfc5a60b7">DwarfFile</a> (AsmPrinter *AP, StringRef Pref, BumpPtrAllocator &amp;DA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffb045ffb46f04de150850b842042d8">getUnits</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint32_t, <a href="/web-llvm/docs/api/structs/llvm/rangespanlist">RangeSpanList</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab48a8e5f4dfb7f8d1b5ce5b2ea27bd3f">addRange</a> (const DwarfCompileUnit &amp;CU, SmallVector&lt; RangeSpan, 2 &gt; R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rangespanlist">RangeSpanList</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670be7a4b0b07c446a778eebea56e478">getRangeLists</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRangeLists - Get the vector of range lists. <a href="#a670be7a4b0b07c446a778eebea56e478">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d25783e3fd286b1fea14b6fafbf9f6">computeSizeAndOffset</a> (DIE &amp;Die, unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the size and offset of a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> given an incoming Offset. <a href="#a12d25783e3fd286b1fea14b6fafbf9f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ceeb48b8050cefe6caf715e13207e4">computeSizeAndOffsets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the size and offset of all the DIEs. <a href="#a37ceeb48b8050cefe6caf715e13207e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d1f7077f90348ee80ceb8885dd3930">computeSizeAndOffsetsForUnit</a> (DwarfUnit *TheU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the size and offset of all the DIEs in the given unit. <a href="#a61d1f7077f90348ee80ceb8885dd3930">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21979d7320f512e41e97b400017ad153">addUnit</a> (std::unique_ptr&lt; DwarfCompileUnit &gt; U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a unit to the list of CUs. <a href="#a21979d7320f512e41e97b400017ad153">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64235e366dc347388139f4fefbbeb64b">emitUnits</a> (bool UseOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all of the units to the section listed with the given abbreviation section. <a href="#a64235e366dc347388139f4fefbbeb64b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66056de6e47af980edacced419d5d0b8">emitUnit</a> (DwarfUnit *TheU, bool UseOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the given unit to its section. <a href="#a66056de6e47af980edacced419d5d0b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f9362d987b1da3c11de7b1a36b8879">emitAbbrevs</a> (MCSection *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a set of abbreviations to the specific section. <a href="#a88f9362d987b1da3c11de7b1a36b8879">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fcda32f38602d8abbbc9aa0291d13fe">emitStrings</a> (MCSection *StrSection, MCSection *OffsetSection=nullptr, bool UseRelativeOffsets=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all of the strings to the section given. <a href="#a9fcda32f38602d8abbbc9aa0291d13fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfstringpool">DwarfStringPool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c07fb1123154d97bfb41c34ac51325e">getStringPool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the string pool. <a href="#a7c07fb1123154d97bfb41c34ac51325e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d863842b802206c5c4242401772b817">getStringOffsetsStartSym</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acecd618104d0d597a528260e00f3ae8a">setStringOffsetsStartSym</a> (MCSymbol *Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7768ffc89068edb9c388c02b96d086cf">getRnglistsTableBaseSym</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a590dd1a0073f9187bf45366c69ba7c12">setRnglistsTableBaseSym</a> (MCSymbol *Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f1a3100af547885ca5a51e5fc9466a">addScopeVariable</a> (LexicalScope *LS, DbgVariable *Var)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1720ace58baf8676ff6a9cc841556310">addScopeLabel</a> (LexicalScope *LS, DbgLabel *Label)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *, ScopeVars &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aabf23e9fa9fce8c62ab9eb7adb6434">getScopeVariables</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">LabelList</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa038d0dd471530e90f730dc4b404162c">getScopeLabels</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8cd8ca930f87c88bc289ea70a3bd2fe">getAbstractScopeDIEs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a> &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5febe1e9b0d23b2f855fa6c171e19aac">getAbstractEntities</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb22aae7cd8675ba4aba88f76268045">insertDIE</a> (const MDNode *TypeMD, DIE *Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb414c66fe1303fa587fcf7b3087f81">getDIE</a> (const MDNode *TypeMD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd07d029e3767c5a702419dc8c01846">Asm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16572c99bb44bc4b61f68406f7f6e176">AbbrevAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieabbrevset">DIEAbbrevSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b3aa7ccf27dad383651ab453663dd7b">Abbrevs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &gt;, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7222b3acbece756152eaf573d4c23129">CUs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfstringpool">DwarfStringPool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5360d5f0e73887f176fd45d3c5516c96">StrPool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rangespanlist">RangeSpanList</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc8e675715d8df45f0e381a72f68827">CURangeLists</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6e36dc305750afffef1d11e0fb8344">StringOffsetsStartSym</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DWARF v5: The symbol that designates the start of the contribution to the string offsets table. <a href="#a8b6e36dc305750afffef1d11e0fb8344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7ef775a178b2d9db5e9007316b22fe4">RnglistsTableBaseSym</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DWARF v5: The symbol that designates the base of the range list table. <a href="#ad7ef775a178b2d9db5e9007316b22fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *, ScopeVars &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae120f6ea5a96c842c7758654dc4ea488">ScopeVariables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of DbgVariables of each lexical scope. <a href="#ae120f6ea5a96c842c7758654dc4ea488">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">LabelList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c9338eff4b870e677a178456646900">ScopeLabels</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a709ae797bc2627770e335144fca30">AbstractLocalScopeDIEs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e14f459d15f478b3d9d626cfdb1a00d">AbstractEntities</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d2476b373b3a297c5de571f1c8015e">DITypeNodeToDieMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps MDNodes for type system with the corresponding DIEs. <a href="#a68d2476b373b3a297c5de571f1c8015e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LabelList {#a70c8d7ebae33cd232e94c79e0e7be59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DwarfFile::LabelList =  SmallVector&lt;DbgLabel *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of DbgLabels of each lexical scope.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DwarfFile() {#a8ae72bc6de8d7034ef61711dfc5a60b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfFile::DwarfFile (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * AP, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pref, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; DA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRange() {#ab48a8e5f4dfb7f8d1b5ce5b2ea27bd3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint32_t, RangeSpanList * &gt; DwarfFile::addRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rangespan">RangeSpan</a>, 2 &gt; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>.</p>

</div>
</div>

### addScopeLabel() {#a1720ace58baf8676ff6a9cc841556310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfFile::addScopeLabel (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * LS, <a href="/web-llvm/docs/api/classes/llvm/dbglabel">DbgLabel</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### addScopeVariable() {#aa5f1a3100af547885ca5a51e5fc9466a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfFile::addScopeVariable (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * LS, <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> * Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#aa02c139b4ee7899f5a330299bb3a0f7f">llvm::DILocalVariable::getArg</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#a3f999918279bb2c923b2d35bec6fb01d">llvm::DbgVariable::getVariable</a>.</p>

</div>
</div>

### addUnit() {#a21979d7320f512e41e97b400017ad153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfFile::addUnit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &gt; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a unit to the list of CUs.</p>

<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>

</div>
</div>

### computeSizeAndOffset() {#a12d25783e3fd286b1fea14b6fafbf9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DwarfFile::computeSizeAndOffset (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, unsigned Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the size and offset of a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> given an incoming Offset.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">llvm::DIE::computeOffsetsAndAbbrevs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a61d1f7077f90348ee80ceb8885dd3930">computeSizeAndOffsetsForUnit</a>.</p>

</div>
</div>

### computeSizeAndOffsets() {#a37ceeb48b8050cefe6caf715e13207e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfFile::computeSizeAndOffsets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the size and offset of all the DIEs.</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>


<p>References <a href="#a61d1f7077f90348ee80ceb8885dd3930">computeSizeAndOffsetsForUnit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### computeSizeAndOffsetsForUnit() {#a61d1f7077f90348ee80ceb8885dd3930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DwarfFile::computeSizeAndOffsetsForUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> * TheU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the size and offset of all the DIEs in the given unit.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The size of the root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></dd>
</dl>


<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>


<p>References <a href="#a12d25783e3fd286b1fea14b6fafbf9f6">computeSizeAndOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8f45a669235b32b6a7e2d7e8a7b95f53">llvm::DwarfUnit::getHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a37ceeb48b8050cefe6caf715e13207e4">computeSizeAndOffsets</a>.</p>

</div>
</div>

### emitAbbrevs() {#a88f9362d987b1da3c11de7b1a36b8879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfFile::emitAbbrevs (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a set of abbreviations to the specific section.</p>

<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>

</div>
</div>

### emitStrings() {#a9fcda32f38602d8abbbc9aa0291d13fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfFile::emitStrings (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * StrSection, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * OffsetSection=nullptr, bool UseRelativeOffsets=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all of the strings to the section given.</p>


<p>If OffsetSection is non-null, emit a table of string offsets to it. If UseRelativeOffsets is false, emit absolute offsets to the strings. Otherwise, emit relocatable references to the strings if they are supported by the target.</p>


<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>

</div>
</div>

### emitUnit() {#a66056de6e47af980edacced419d5d0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfFile::emitUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> * TheU, bool UseOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the given unit to its section.</p>

<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a37e872823d52cafea3dca803cdc014e7">llvm::DwarfUnit::emitHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/iterator-range/#a06fff5bdd2bdf6d2c200e281787dc284">llvm::iterator_range&lt; IteratorT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abebd15dd4b82e33ca73757397490ea80">llvm::DwarfUnit::getCUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aab860a0ea2334cccbf45dc61e951f24c">llvm::DwarfUnit::getEndLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#aade914d8130df826d14059399caeb660">llvm::DIEUnit::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a36ac215f97478b9332071e06786aed77">llvm::DICompileUnit::isDebugDirectivesOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/dievaluelist/#aaac0a2276b1fe9c13ec247892a7c3703">llvm::DIEValueList::values</a>.</p>


<p>Referenced by <a href="#a64235e366dc347388139f4fefbbeb64b">emitUnits</a>.</p>

</div>
</div>

### emitUnits() {#a64235e366dc347388139f4fefbbeb64b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfFile::emitUnits (bool UseOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all of the units to the section listed with the given abbreviation section.</p>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a>.</p>


<p>Reference <a href="#a66056de6e47af980edacced419d5d0b8">emitUnit</a>.</p>

</div>
</div>

### getAbstractEntities() {#a5febe1e9b0d23b2f855fa6c171e19aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; const DINode *, std::unique_ptr&lt; DbgEntity &gt; &gt; &amp; llvm::DwarfFile::getAbstractEntities ()</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### getAbstractScopeDIEs() {#ac8cd8ca930f87c88bc289ea70a3bd2fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; const DILocalScope *, DIE * &gt; &amp; llvm::DwarfFile::getAbstractScopeDIEs ()</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### getDIE() {#aebb414c66fe1303fa587fcf7b3087f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * llvm::DwarfFile::getDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * TypeMD)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### getRangeLists() {#a670be7a4b0b07c446a778eebea56e478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; RangeSpanList &gt; &amp; llvm::DwarfFile::getRangeLists ()</td>
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

<p>getRangeLists - Get the vector of range lists.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a69aff64b0c559a54640422a7024e02a9">emitRnglistsTableHeader</a>.</p>

</div>
</div>

### getRnglistsTableBaseSym() {#a7768ffc89068edb9c388c02b96d086cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::DwarfFile::getRnglistsTableBaseSym ()</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a69aff64b0c559a54640422a7024e02a9">emitRnglistsTableHeader</a>.</p>

</div>
</div>

### getScopeLabels() {#aa038d0dd471530e90f730dc4b404162c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; LexicalScope *, LabelList &gt; &amp; llvm::DwarfFile::getScopeLabels ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### getScopeVariables() {#a5aabf23e9fa9fce8c62ab9eb7adb6434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; LexicalScope *, ScopeVars &gt; &amp; llvm::DwarfFile::getScopeVariables ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### getStringOffsetsStartSym() {#a6d863842b802206c5c4242401772b817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::DwarfFile::getStringOffsetsStartSym ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### getStringPool() {#a7c07fb1123154d97bfb41c34ac51325e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfStringPool &amp; llvm::DwarfFile::getStringPool ()</td>
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

<p>Returns the string pool.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### getUnits() {#acffb045ffb46f04de150850b842042d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; std::unique_ptr&lt; DwarfCompileUnit &gt; &gt; &amp; llvm::DwarfFile::getUnits ()</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### insertDIE() {#addb22aae7cd8675ba4aba88f76268045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfFile::insertDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * TypeMD, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### setRnglistsTableBaseSym() {#a590dd1a0073f9187bf45366c69ba7c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfFile::setRnglistsTableBaseSym (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3f59a82f48553634ac4625cb8166071e">llvm::DwarfDebug::beginModule</a>.</p>

</div>
</div>

### setStringOffsetsStartSym() {#acecd618104d0d597a528260e00f3ae8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfFile::setStringOffsetsStartSym (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AbbrevAllocator {#a16572c99bb44bc4b61f68406f7f6e176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::DwarfFile::AbbrevAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### Abbrevs {#a6b3aa7ccf27dad383651ab453663dd7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEAbbrevSet llvm::DwarfFile::Abbrevs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### AbstractEntities {#a6e14f459d15f478b3d9d626cfdb1a00d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DINode *, std::unique_ptr&lt;DbgEntity&gt; &gt; llvm::DwarfFile::AbstractEntities</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### AbstractLocalScopeDIEs {#a93a709ae797bc2627770e335144fca30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DILocalScope *, DIE *&gt; llvm::DwarfFile::AbstractLocalScopeDIEs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### Asm {#afcd07d029e3767c5a702419dc8c01846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter* llvm::DwarfFile::Asm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### CURangeLists {#accc8e675715d8df45f0e381a72f68827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RangeSpanList, 1&gt; llvm::DwarfFile::CURangeLists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### CUs {#a7222b3acbece756152eaf573d4c23129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;DwarfCompileUnit&gt;, 1&gt; llvm::DwarfFile::CUs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### DITypeNodeToDieMap {#a68d2476b373b3a297c5de571f1c8015e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MDNode *, DIE *&gt; llvm::DwarfFile::DITypeNodeToDieMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps MDNodes for type system with the corresponding DIEs.</p>


<p>These DIEs can be shared across CUs, that is why we keep the map here instead of in <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a>.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### RnglistsTableBaseSym {#ad7ef775a178b2d9db5e9007316b22fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::DwarfFile::RnglistsTableBaseSym = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DWARF v5: The symbol that designates the base of the range list table.</p>


<p>The table is shared by all units.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### ScopeLabels {#a28c9338eff4b870e677a178456646900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;LexicalScope *, LabelList&gt; llvm::DwarfFile::ScopeLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### ScopeVariables {#ae120f6ea5a96c842c7758654dc4ea488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;LexicalScope *, ScopeVars&gt; llvm::DwarfFile::ScopeVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of DbgVariables of each lexical scope.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### StringOffsetsStartSym {#a8b6e36dc305750afffef1d11e0fb8344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::DwarfFile::StringOffsetsStartSym = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DWARF v5: The symbol that designates the start of the contribution to the string offsets table.</p>


<p>The contribution is shared by all units.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

### StrPool {#a5360d5f0e73887f176fd45d3c5516c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfStringPool llvm::DwarfFile::StrPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-cpp">DwarfFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarffile-h">DwarfFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
