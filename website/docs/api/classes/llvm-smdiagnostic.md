---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smdiagnostic
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SMDiagnostic` Class Reference

<p>Instances of this class encapsulate one diagnostic report, allowing printing to a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> as a caret diagnostic. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SMDiagnostic { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c6552311757bb0e9cc1ffe90c712c2b">SMDiagnostic</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623ed623cf8156f724dcfcaef3125a2e">SMDiagnostic</a> (StringRef filename, SourceMgr::DiagKind Knd, StringRef Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41952f4410b4b7d275359da823faf2b0">SMDiagnostic</a> (const SourceMgr &amp;sm, SMLoc L, StringRef FN, int Line, int Col, SourceMgr::DiagKind Kind, StringRef Msg, StringRef LineStr, ArrayRef&lt; std::pair&lt; unsigned, unsigned &gt; &gt; Ranges, ArrayRef&lt; SMFixIt &gt; FixIts={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbfc090a5cae08bf8e6502df3c713f8b">getSourceMgr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f7639f70813f4388a60639d770ae0de">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f09f2905c7fc42bb6fb32618da5619a">getFilename</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e31213069880653dafbc5530d17c25">getLineNo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd7c6b9946b58fcb4d9559ba04dd5db3">getColumnNo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777">SourceMgr::DiagKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d8b2d1fcb48a67f4d620f46bed2977">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a913f19e5ceb01ef21a40cf850d89e117">getMessage</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69f0b4810845dd500baa1edcec16fdca">getLineContents</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; unsigned, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a8be17683280c78d59d75a578460e6">getRanges</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46565924b7a5b227d9c993deef1ef5d">addFixIt</a> (const SMFixIt &amp;Hint)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smfixit">SMFixIt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a978764a9583fabc1a345f50a1a3f0a90">getFixIts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0653e9bbc6598528d50ec97cad565b74">print</a> (const char *ProgName, raw_ostream &amp;S, bool ShowColors=true, bool ShowKindLabel=true, bool ShowLocation=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe9302897a58c2f42b07b6a43d43db54">SM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47bd51afa8e16788a8f685112e9d13b5">Loc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0ada15be11223ae08aac5abc4e842f3">Filename</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5abbbcb8db00d2bf27d1f3baf45e03a0">LineNo</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e92dd88ff7e5a1bdc733a92b3f7176">ColumnNo</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777">SourceMgr::DiagKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7995a7d0edf2f316e19dd9fbcc411f7">Kind</a> = <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">SourceMgr::DK_Error</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac68b9cffc1e4a86933a68a5a30fbfdfe">Message</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafa678f993184fdb2f4bdaa695516248">LineContents</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; unsigned, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30cdd496b5872e58675c89d7a6f92aa1">Ranges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smfixit">SMFixIt</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a60e83b022efff10070402483bc194f">FixIts</a></td>
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

<p>Instances of this class encapsulate one diagnostic report, allowing printing to a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> as a caret diagnostic.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SMDiagnostic() {#a3c6552311757bb0e9cc1ffe90c712c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SMDiagnostic::SMDiagnostic ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### SMDiagnostic() {#a623ed623cf8156f724dcfcaef3125a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SMDiagnostic::SMDiagnostic (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> filename, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777">SourceMgr::DiagKind</a> Knd, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Msg)</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### SMDiagnostic() {#a41952f4410b4b7d275359da823faf2b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMDiagnostic::SMDiagnostic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; sm, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FN, int Line, int Col, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777">SourceMgr::DiagKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Msg, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LineStr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; unsigned, unsigned &gt; &gt; Ranges, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smfixit">SMFixIt</a> &gt; FixIts={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFixIt() {#ab46565924b7a5b227d9c993deef1ef5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SMDiagnostic::addFixIt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smfixit">SMFixIt</a> &amp; Hint)</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### getColumnNo() {#afd7c6b9946b58fcb4d9559ba04dd5db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMDiagnostic::getColumnNo ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a21ef92ee94136c11407030eee4319eab">parseIRConstant</a>.</p>

</div>
</div>

### getFilename() {#a2f09f2905c7fc42bb6fb32618da5619a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::SMDiagnostic::getFilename ()</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### getFixIts() {#a978764a9583fabc1a345f50a1a3f0a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SMFixIt &gt; llvm::SMDiagnostic::getFixIts ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>.</p>

</div>
</div>

### getKind() {#a17d8b2d1fcb48a67f4d620f46bed2977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr::DiagKind llvm::SMDiagnostic::getKind ()</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a081423ee9e0967e35ecfcad1af58be23">llvm::MIRParserImpl::reportDiagnostic</a>.</p>

</div>
</div>

### getLineContents() {#a69f0b4810845dd500baa1edcec16fdca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::SMDiagnostic::getLineContents ()</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>.</p>

</div>
</div>

### getLineNo() {#a57e31213069880653dafbc5530d17c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMDiagnostic::getLineNo ()</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>.</p>

</div>
</div>

### getLoc() {#a7f7639f70813f4388a60639d770ae0de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::SMDiagnostic::getLoc ()</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a> and <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a042b7e85ad239f80f6a079283a9faee6">llvm::SourceMgr::PrintMessage</a>.</p>

</div>
</div>

### getMessage() {#a913f19e5ceb01ef21a40cf850d89e117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::SMDiagnostic::getMessage ()</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9feb9f5ca88b1a9d4f6e702a39d35060">llvm::DWARFYAML::emitDebugSections</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a21ef92ee94136c11407030eee4319eab">parseIRConstant</a>.</p>

</div>
</div>

### getRanges() {#aa2a8be17683280c78d59d75a578460e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; unsigned, unsigned &gt; &gt; llvm::SMDiagnostic::getRanges ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>.</p>

</div>
</div>

### getSourceMgr() {#adbfc090a5cae08bf8e6502df3c713f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SourceMgr * llvm::SMDiagnostic::getSourceMgr ()</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>.</p>

</div>
</div>

### print() {#a0653e9bbc6598528d50ec97cad565b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SMDiagnostic::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ProgName, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; S, bool ShowColors=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool ShowKindLabel=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool ShowLocation=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a06b9281e396db002010bde1de57262eb">llvm::Auto</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a987811f4399e448a9e1223ee373c1e00">buildFixItLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2abcfaccebf745acfd5e75351095a5394a">llvm::Disable</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ae5a15719ab746bdc7713c4784fc1c6ea">llvm::SourceMgr::DK_Remark</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777a6bcc8ac9374461ed0599334db63365d0">llvm::SourceMgr::DK_Warning</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a59d59f7f8aa89b08f44ad6a87e8ebb1a">llvm::WithColor::error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ae56223ff7592f05301a6b496ae46299c">llvm::raw_ostream::GREEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a646e0a501c1d33d6d67a67f89cec37e1">isNonASCII</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#ab5313a760f20fc53b44cc8dbabfd1ae1">llvm::WithColor::note</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a9d20e2079dcd9a868d4b3af67510647b">printSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#afdcd08052180c0b87e06a2808b062c01">llvm::WithColor::remark</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad55e55b3692fe8ec3e8b724d3d5bade0">llvm::raw_ostream::SAVEDCOLOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a34e0396a4cc9f3450ef389281ea7d5f3">TabStop</a> and <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a237ad6eae22f6b2746a542c02d309a5b">llvm::WithColor::warning</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp/#a4c4cc7fd1400fb03f06f4254fc03db53">defaultDiagHandler</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#ab579a679ef1379aa93f97bca62dedd1c">handleDiagnostic</a>, <a href="/web-llvm/docs/api/groups/llvmccoreirreader/#ga319e4562ffb47ec6eba2eb70ffdbaa37">LLVMParseIRInContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a8cd36a34ea4adceda5576292e50cf883">loadFile</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinterrawostream/#a3b1c2cb30efb9c82a81bd8a39d6f4d84">llvm::DiagnosticPrinterRawOStream::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a042b7e85ad239f80f6a079283a9faee6">llvm::SourceMgr::PrintMessage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ColumnNo {#a05e92dd88ff7e5a1bdc733a92b3f7176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMDiagnostic::ColumnNo = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### Filename {#ac0ada15be11223ae08aac5abc4e842f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SMDiagnostic::Filename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### FixIts {#a0a60e83b022efff10070402483bc194f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SMFixIt, 4&gt; llvm::SMDiagnostic::FixIts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### Kind {#ab7995a7d0edf2f316e19dd9fbcc411f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr::DiagKind llvm::SMDiagnostic::Kind = <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">SourceMgr::DK_Error</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### LineContents {#aafa678f993184fdb2f4bdaa695516248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SMDiagnostic::LineContents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### LineNo {#a5abbbcb8db00d2bf27d1f3baf45e03a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMDiagnostic::LineNo = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### Loc {#a47bd51afa8e16788a8f685112e9d13b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::SMDiagnostic::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### Message {#ac68b9cffc1e4a86933a68a5a30fbfdfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SMDiagnostic::Message</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### Ranges {#a30cdd496b5872e58675c89d7a6f92aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;unsigned, unsigned&gt; &gt; llvm::SMDiagnostic::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### SM {#abe9302897a58c2f42b07b6a43d43db54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SourceMgr* llvm::SMDiagnostic::SM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
