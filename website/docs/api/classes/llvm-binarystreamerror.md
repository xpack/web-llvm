---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binarystreamerror
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BinaryStreamError` Class Reference

<p>Base class for errors originating when parsing raw PDB files. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BinaryStreamError { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">llvm/Support/BinaryStreamError.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/errorinfo">ErrorInfo&lt;ThisErrT, ParentErrT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for user error types. <a href="/web-llvm/docs/api/classes/llvm/errorinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838d7f2cbe31c17bee3c1fb18ea832aa">BinaryStreamError</a> (stream_error_code C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47d1f738c6efd2e58fc0d296a6430136">BinaryStreamError</a> (StringRef Context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3d0d04dd2e1daaa889030cc7ef2c1b">BinaryStreamError</a> (stream_error_code C, StringRef Context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d343b8585f3d82a91ba629046390815">log</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print an error message to an output stream. <a href="#a9d343b8585f3d82a91ba629046390815">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a9a143295407ff8b787471f2481ebbf">convertToErrorCode</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this error to a std::error_code. <a href="#a4a9a143295407ff8b787471f2481ebbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0c0a3fc0d5ade86d106150ea1fa1ed0">getErrorMessage</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89d">stream_error_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6b931ab3d6f06f7fb09db061637df15">getErrorCode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6d94a1add52a7810e2a83ab5ca6b23">ErrMsg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89d">stream_error_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adab632c28b234a60ce1e5658e20c8206">Code</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d955023ca0985818cb1b1f425c0567">ID</a> = 0</td>
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

<p>Base class for errors originating when parsing raw PDB files.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BinaryStreamError() {#a838d7f2cbe31c17bee3c1fb18ea832aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamError::BinaryStreamError (<a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89d">stream_error_code</a> C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamerror-cpp">BinaryStreamError.cpp</a>.</p>


<p>References <a href="#a838d7f2cbe31c17bee3c1fb18ea832aa">BinaryStreamError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a838d7f2cbe31c17bee3c1fb18ea832aa">BinaryStreamError</a> and <a href="#a47d1f738c6efd2e58fc0d296a6430136">BinaryStreamError</a>.</p>

</div>
</div>

### BinaryStreamError() {#a47d1f738c6efd2e58fc0d296a6430136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamError::BinaryStreamError (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Context)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamerror-cpp">BinaryStreamError.cpp</a>.</p>


<p>References <a href="#a838d7f2cbe31c17bee3c1fb18ea832aa">BinaryStreamError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89dad415f0e30c471dfdd9bc4f827329ef48">llvm::unspecified</a>.</p>

</div>
</div>

### BinaryStreamError() {#a8a3d0d04dd2e1daaa889030cc7ef2c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamError::BinaryStreamError (<a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89d">stream_error_code</a> C, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamerror-cpp">BinaryStreamError.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89da71b8619c23e0ef128682c5871446c690">llvm::filesystem_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89da11f674242a86a560ba9f4b389bb0fc5a">llvm::invalid_array_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89daf6579f9fbeb5034d9165fe820866b23b">llvm::invalid_offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89dad88b43968f2dd7eb3d9d40060fbacc98">llvm::stream_too_short</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89dad415f0e30c471dfdd9bc4f827329ef48">llvm::unspecified</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertToErrorCode() {#a4a9a143295407ff8b787471f2481ebbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code BinaryStreamError::convertToErrorCode ()</td>
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

<p>Convert this error to a std::error_code.</p>


<p>This is a temporary crutch to enable interaction with code still using std::error_code. It will be removed in the future.</p>


<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamerror-cpp">BinaryStreamError.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>.</p>

</div>
</div>

### getErrorCode() {#af6b931ab3d6f06f7fb09db061637df15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">stream_error_code llvm::BinaryStreamError::getErrorCode ()</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>.</p>

</div>
</div>

### getErrorMessage() {#aa0c0a3fc0d5ade86d106150ea1fa1ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef BinaryStreamError::getErrorMessage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamerror-cpp">BinaryStreamError.cpp</a>.</p>

</div>
</div>

### log() {#a9d343b8585f3d82a91ba629046390815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BinaryStreamError::log (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print an error message to an output stream.</p>

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamerror-cpp">BinaryStreamError.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Code {#adab632c28b234a60ce1e5658e20c8206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">stream_error_code llvm::BinaryStreamError::Code</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>.</p>

</div>
</div>

### ErrMsg {#afd6d94a1add52a7810e2a83ab5ca6b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::BinaryStreamError::ErrMsg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a52d955023ca0985818cb1b1f425c0567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char BinaryStreamError::ID = 0</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamerror-h">BinaryStreamError.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamerror-cpp">BinaryStreamError.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
