---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-asmwriter-cpp-/mdfieldprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MDFieldPrinter` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AsmWriter.cpp}::MDFieldPrinter { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426a5ec679fc935027352c46c3bc0cbb">MDFieldPrinter</a> (raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac259d81224232774d46bc2876569d644">MDFieldPrinter</a> (raw_ostream &amp;Out, AsmWriterContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b204d399cf691b892395a9804639e58">printTag</a> (const DINode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2137ea7428ed1982a2ae6d0a2f8a2c35">printMacinfoType</a> (const DIMacroNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ca524a2627e241c8d818322dff9584">printChecksum</a> (const DIFile::ChecksumInfo&lt; StringRef &gt; &amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f04f6d8a07811a29dc14c7d56c27252">printString</a> (StringRef Name, StringRef Value, bool ShouldSkipEmpty=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19cf59d0aa8b7582f631f08efb4c1bc1">printMetadata</a> (StringRef Name, const Metadata *MD, bool ShouldSkipNull=true)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a526f30825aba3d2d2d4f1011f97ae4ac">printInt</a> (StringRef Name, IntTy Int, bool ShouldSkipZero=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded4f01d9d8122b933fb4459335809ea">printAPInt</a> (StringRef Name, const APInt &amp;Int, bool IsUnsigned, bool ShouldSkipZero)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9321d9a8daf949a241f1edaa09c19b46">printBool</a> (StringRef Name, bool Value, std::optional&lt; bool &gt; Default=std::nullopt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941fadcc66e266a39f624bc5c112371f">printDIFlags</a> (StringRef Name, DINode::DIFlags Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa3beee983c3c5ddd6a4b3fd43edced">printDISPFlags</a> (StringRef Name, DISubprogram::DISPFlags Flags)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntTy, class Stringifier&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a304508f1188672753c004e10607ae9e9">printDwarfEnum</a> (StringRef Name, IntTy Value, Stringifier toString, bool ShouldSkipZero=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e68548b639b11a055a7b6b9138430b8">printEmissionKind</a> (StringRef Name, DICompileUnit::DebugEmissionKind EK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73fbe10c61d14e300d2aecd1ba27cf40">printNameTableKind</a> (StringRef Name, DICompileUnit::DebugNameTableKind NTK)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5aaadd441eab003cc211edf7612a8ddf">printInt</a> (StringRef Name, IntTy Int, bool ShouldSkipZero)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntTy, class Stringifier&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8eb6721a50b974ca77066c7a5e96b7df">printDwarfEnum</a> (StringRef Name, IntTy Value, Stringifier toString, bool ShouldSkipZero)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/fieldseparator">FieldSeparator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/asmwritercontext">AsmWriterContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a945d6405ddc8b651a6ef87b3bd52910d">WriterCtx</a></td>
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


<p>Definition at line 1837 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MDFieldPrinter() {#a426a5ec679fc935027352c46c3bc0cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AsmWriter.cpp}::MDFieldPrinter::MDFieldPrinter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 1842 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a> and <a href="#a945d6405ddc8b651a6ef87b3bd52910d">WriterCtx</a>.</p>

</div>
</div>

### MDFieldPrinter() {#ac259d81224232774d46bc2876569d644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AsmWriter.cpp}::MDFieldPrinter::MDFieldPrinter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/asmwritercontext">AsmWriterContext</a> &amp; Ctx)</td>
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



<p>Definition at line 1844 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a> and <a href="#a945d6405ddc8b651a6ef87b3bd52910d">WriterCtx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printAPInt() {#aded4f01d9d8122b933fb4459335809ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printAPInt (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Int, bool IsUnsigned, bool ShouldSkipZero)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1856 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a> and <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a>.</p>


<p>Referenced by <a href="#a526f30825aba3d2d2d4f1011f97ae4ac">printInt</a>.</p>

</div>
</div>

### printBool() {#a9321d9a8daf949a241f1edaa09c19b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printBool (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool Value, std::optional&lt; bool &gt; Default=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1858 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aaf2a32c0f2738e57cac623b73b2c88aba79935518a3889663d8688b6b01fff051">Default</a>, <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a> and <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a>.</p>


<p>Referenced by <a href="#a526f30825aba3d2d2d4f1011f97ae4ac">printInt</a>.</p>

</div>
</div>

### printChecksum() {#a33ca524a2627e241c8d818322dff9584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printChecksum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/difile/checksuminfo">DIFile::ChecksumInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1849 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="/web-llvm/docs/api/structs/llvm/difile/checksuminfo/#afaa59ea539d7165cf0e2d430647146c1">llvm::DIFile::ChecksumInfo&lt; T &gt;::getKindAsString</a>, <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a>, <a href="#a1f04f6d8a07811a29dc14c7d56c27252">printString</a> and <a href="/web-llvm/docs/api/structs/llvm/difile/checksuminfo/#a0b30b09229fb5f15a09598f1395594e0">llvm::DIFile::ChecksumInfo&lt; T &gt;::Value</a>.</p>

</div>
</div>

### printDIFlags() {#a941fadcc66e266a39f624bc5c112371f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printDIFlags (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1860 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#ac3ac75a45dc84dddab171ec387721eb4">llvm::DINode::getFlagString</a>, <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a> and <a href="/web-llvm/docs/api/classes/llvm/dinode/#a63a4694d7a6c8da554e27cf83c212670">llvm::DINode::splitFlags</a>.</p>


<p>Referenced by <a href="#a526f30825aba3d2d2d4f1011f97ae4ac">printInt</a>.</p>

</div>
</div>

### printDISPFlags() {#a0fa3beee983c3c5ddd6a4b3fd43edced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printDISPFlags (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#aee46b4d49ad15932fe2706f1d308d4e9">DISubprogram::DISPFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1861 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#ad1249f3f7336f9d847627f923b0e3dd4">llvm::DISubprogram::getFlagString</a>, <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a> and <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#ab966032279468f2b354f2dc8dec9836e">llvm::DISubprogram::splitFlags</a>.</p>


<p>Referenced by <a href="#a526f30825aba3d2d2d4f1011f97ae4ac">printInt</a>.</p>

</div>
</div>

### printDwarfEnum() {#a304508f1188672753c004e10607ae9e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntTy, class Stringifier&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmWriter.cpp}::MDFieldPrinter::printDwarfEnum (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IntTy Value, Stringifier toString, bool ShouldSkipZero=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1863 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a3e68548b639b11a055a7b6b9138430b8">printEmissionKind</a>, <a href="#a73fbe10c61d14e300d2aecd1ba27cf40">printNameTableKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

### printDwarfEnum() {#a8eb6721a50b974ca77066c7a5e96b7df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntTy, class Stringifier&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmWriter.cpp}::MDFieldPrinter::printDwarfEnum (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IntTy Value, Stringifier toString, bool ShouldSkipZero)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2005 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

### printEmissionKind() {#a3e68548b639b11a055a7b6b9138430b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printEmissionKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66d">DICompileUnit::DebugEmissionKind</a> EK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1865 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a168bde7847da28592f7c592d0eed28c8">llvm::DICompileUnit::emissionKindString</a>, <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a> and <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a>.</p>


<p>Referenced by <a href="#a304508f1188672753c004e10607ae9e9">printDwarfEnum</a>.</p>

</div>
</div>

### printInt() {#a526f30825aba3d2d2d4f1011f97ae4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmWriter.cpp}::MDFieldPrinter::printInt (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IntTy Int, bool ShouldSkipZero=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1855 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aaf2a32c0f2738e57cac623b73b2c88aba79935518a3889663d8688b6b01fff051">Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="#aded4f01d9d8122b933fb4459335809ea">printAPInt</a>, <a href="#a9321d9a8daf949a241f1edaa09c19b46">printBool</a>, <a href="#a941fadcc66e266a39f624bc5c112371f">printDIFlags</a> and <a href="#a0fa3beee983c3c5ddd6a4b3fd43edced">printDISPFlags</a>.</p>

</div>
</div>

### printInt() {#a5aaadd441eab003cc211edf7612a8ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmWriter.cpp}::MDFieldPrinter::printInt (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IntTy Int, bool ShouldSkipZero)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1926 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a> and <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a>.</p>

</div>
</div>

### printMacinfoType() {#a2137ea7428ed1982a2ae6d0a2f8a2c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printMacinfoType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dimacronode">DIMacroNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1848 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gad07ea9fcc31eab665ecf3004109a59bb">llvm::dwarf::MacinfoString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a>.</p>

</div>
</div>

### printMetadata() {#a19cf59d0aa8b7582f631f08efb4c1bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD, bool ShouldSkipNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1852 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a060c83e55e124b32a1b41542ee254d98">writeMetadataAsOperand</a> and <a href="#a945d6405ddc8b651a6ef87b3bd52910d">WriterCtx</a>.</p>

</div>
</div>

### printNameTableKind() {#a73fbe10c61d14e300d2aecd1ba27cf40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printNameTableKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01">DICompileUnit::DebugNameTableKind</a> NTK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1866 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01a7a1920d61156abc05a60135aefe8bc67">llvm::DICompileUnit::Default</a>, <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a153271fe0f31039d8c15c519611204cc">llvm::DICompileUnit::nameTableKindString</a> and <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a>.</p>


<p>Referenced by <a href="#a304508f1188672753c004e10607ae9e9">printDwarfEnum</a>.</p>

</div>
</div>

### printString() {#a1f04f6d8a07811a29dc14c7d56c27252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value, bool ShouldSkipEmpty=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1850 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a> and <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a>.</p>


<p>Referenced by <a href="#a33ca524a2627e241c8d818322dff9584">printChecksum</a>.</p>

</div>
</div>

### printTag() {#a9b204d399cf691b892395a9804639e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDFieldPrinter::printTag (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1847 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a2bab54f9570c4249a9980ddc0a33a30e">FS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a354e4ed611d7e8733ea1535197f3940b">Out</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf17a843ca40c67635b127ba50ad45bdf">llvm::dwarf::TagString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FS {#a2bab54f9570c4249a9980ddc0a33a30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FieldSeparator anonymous{AsmWriter.cpp}::MDFieldPrinter::FS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1839 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Referenced by <a href="#aded4f01d9d8122b933fb4459335809ea">printAPInt</a>, <a href="#a9321d9a8daf949a241f1edaa09c19b46">printBool</a>, <a href="#a33ca524a2627e241c8d818322dff9584">printChecksum</a>, <a href="#a941fadcc66e266a39f624bc5c112371f">printDIFlags</a>, <a href="#a0fa3beee983c3c5ddd6a4b3fd43edced">printDISPFlags</a>, <a href="#a8eb6721a50b974ca77066c7a5e96b7df">printDwarfEnum</a>, <a href="#a3e68548b639b11a055a7b6b9138430b8">printEmissionKind</a>, <a href="#a5aaadd441eab003cc211edf7612a8ddf">printInt</a>, <a href="#a2137ea7428ed1982a2ae6d0a2f8a2c35">printMacinfoType</a>, <a href="#a19cf59d0aa8b7582f631f08efb4c1bc1">printMetadata</a>, <a href="#a73fbe10c61d14e300d2aecd1ba27cf40">printNameTableKind</a>, <a href="#a1f04f6d8a07811a29dc14c7d56c27252">printString</a> and <a href="#a9b204d399cf691b892395a9804639e58">printTag</a>.</p>

</div>
</div>

### Out {#a354e4ed611d7e8733ea1535197f3940b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; anonymous{AsmWriter.cpp}::MDFieldPrinter::Out</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1838 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Referenced by <a href="#a426a5ec679fc935027352c46c3bc0cbb">MDFieldPrinter</a>, <a href="#ac259d81224232774d46bc2876569d644">MDFieldPrinter</a>, <a href="#aded4f01d9d8122b933fb4459335809ea">printAPInt</a>, <a href="#a9321d9a8daf949a241f1edaa09c19b46">printBool</a>, <a href="#a33ca524a2627e241c8d818322dff9584">printChecksum</a>, <a href="#a941fadcc66e266a39f624bc5c112371f">printDIFlags</a>, <a href="#a0fa3beee983c3c5ddd6a4b3fd43edced">printDISPFlags</a>, <a href="#a8eb6721a50b974ca77066c7a5e96b7df">printDwarfEnum</a>, <a href="#a3e68548b639b11a055a7b6b9138430b8">printEmissionKind</a>, <a href="#a5aaadd441eab003cc211edf7612a8ddf">printInt</a>, <a href="#a2137ea7428ed1982a2ae6d0a2f8a2c35">printMacinfoType</a>, <a href="#a19cf59d0aa8b7582f631f08efb4c1bc1">printMetadata</a>, <a href="#a73fbe10c61d14e300d2aecd1ba27cf40">printNameTableKind</a>, <a href="#a1f04f6d8a07811a29dc14c7d56c27252">printString</a> and <a href="#a9b204d399cf691b892395a9804639e58">printTag</a>.</p>

</div>
</div>

### WriterCtx {#a945d6405ddc8b651a6ef87b3bd52910d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmWriterContext&amp; anonymous{AsmWriter.cpp}::MDFieldPrinter::WriterCtx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1840 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Referenced by <a href="#a426a5ec679fc935027352c46c3bc0cbb">MDFieldPrinter</a>, <a href="#ac259d81224232774d46bc2876569d644">MDFieldPrinter</a> and <a href="#a19cf59d0aa8b7582f631f08efb4c1bc1">printMetadata</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
