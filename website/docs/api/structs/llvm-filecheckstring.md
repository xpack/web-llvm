---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/filecheckstring
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FileCheckString` Struct Reference

<p>A check that we found in the input file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::FileCheckString { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheck/FileCheckImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac104527c24fbf4fc739aa5bc1e62b107">FileCheckString</a> (Pattern &amp;&amp;P, StringRef S, SMLoc L, std::vector&lt; DagNotPrefixInfo &gt; &amp;&amp;D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae337924e2723d7d8255011f1ac5624cf">Check</a> (const SourceMgr &amp;SM, StringRef Buffer, bool IsLabelScanMode, size_t &amp;MatchLen, FileCheckRequest &amp;Req, std::vector&lt; FileCheckDiag &gt; *Diags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Matches check string and its "not strings" and/or "dag strings". <a href="#ae337924e2723d7d8255011f1ac5624cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36305f86aafd6d41b0c449eac6476efd">CheckNext</a> (const SourceMgr &amp;SM, StringRef Buffer) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies that there is a single line in the given <span class="doxyComputerOutput">Buffer</span>. <a href="#a36305f86aafd6d41b0c449eac6476efd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82944774d532e6adc41c92e29a00e2e9">CheckSame</a> (const SourceMgr &amp;SM, StringRef Buffer) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies that there is no newline in the given <span class="doxyComputerOutput">Buffer</span>. <a href="#a82944774d532e6adc41c92e29a00e2e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae85a64defc7f9bea8408ca9e64e3fc45">CheckNot</a> (const SourceMgr &amp;SM, StringRef Buffer, const std::vector&lt; const DagNotPrefixInfo * &gt; &amp;NotStrings, const FileCheckRequest &amp;Req, std::vector&lt; FileCheckDiag &gt; *Diags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies that none of the strings in <span class="doxyComputerOutput">NotStrings</span> are found in the given <span class="doxyComputerOutput">Buffer</span>. <a href="#ae85a64defc7f9bea8408ca9e64e3fc45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71c43fb658be4df9989f55be8447e1d">CheckDag</a> (const SourceMgr &amp;SM, StringRef Buffer, std::vector&lt; const DagNotPrefixInfo * &gt; &amp;NotStrings, const FileCheckRequest &amp;Req, std::vector&lt; FileCheckDiag &gt; *Diags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Matches "dag strings" and their mixed "not strings". <a href="#ac71c43fb658be4df9989f55be8447e1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b71a36a299b4598e79edc8cd2fce259">Pat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pattern to match. <a href="#a3b71a36a299b4598e79edc8cd2fce259">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2948212a235a5bfc923b3af70bb590">Prefix</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Which prefix name this check matched. <a href="#abb2948212a235a5bfc923b3af70bb590">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae9b54f909a74427af4aa78f6bedcf05">Loc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The location in the match file that the check string was specified. <a href="#aae9b54f909a74427af4aa78f6bedcf05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/dagnotprefixinfo">DagNotPrefixInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76be9b0b55136af940f598eb91664e5">DagNotStrings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold the DAG/NOT strings occurring in the input file. <a href="#aa76be9b0b55136af940f598eb91664e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A check that we found in the input file.</p>

<p>Definition at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FileCheckString() {#ac104527c24fbf4fc739aa5bc1e62b107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FileCheckString::FileCheckString (<a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> &amp;&amp; P, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/dagnotprefixinfo">DagNotPrefixInfo</a> &gt; &amp;&amp; D)</td>
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



<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#aa76be9b0b55136af940f598eb91664e5">DagNotStrings</a>, <a href="#aae9b54f909a74427af4aa78f6bedcf05">Loc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a3b71a36a299b4598e79edc8cd2fce259">Pat</a> and <a href="#abb2948212a235a5bfc923b3af70bb590">Prefix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Check() {#ae337924e2723d7d8255011f1ac5624cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t FileCheckString::Check (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, bool IsLabelScanMode, size_t &amp; MatchLen, <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Matches check string and its "not strings" and/or "dag strings".</p>

<p>Declaration at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 2165 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="#ac71c43fb658be4df9989f55be8447e1d">CheckDag</a>, <a href="#a36305f86aafd6d41b0c449eac6476efd">CheckNext</a>, <a href="#ae85a64defc7f9bea8408ca9e64e3fc45">CheckNot</a>, <a href="#a82944774d532e6adc41c92e29a00e2e9">CheckSame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3285d0c2736154c3ea72dbecaa446eec">llvm::handleErrors</a>, <a href="#aae9b54f909a74427af4aa78f6bedcf05">Loc</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0a3f5c9c6115db2361e358de0c62d43bed">llvm::FileCheckDiag::MatchFoundButWrongLine</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="#a3b71a36a299b4598e79edc8cd2fce259">Pat</a>, <a href="#abb2948212a235a5bfc923b3af70bb590">Prefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#aa386d2cd704c6f1176a5aef1f0f178da">ProcessMatchResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5c0cc4b5cb93bf2b53aa2c8d1b8f37b7">reportMatchResult</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult/#abd537aa1cccb03b25c0ea331081ae782">llvm::Pattern::MatchResult::TheMatch</a> and <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#aa17abc10f9ba381d31d7271db615ad16">llvm::FileCheckRequest::Verbose</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a95a7a7f317661b984c86d196fa44dff9">llvm::FileCheck::checkInput</a>.</p>

</div>
</div>

### CheckDag() {#ac71c43fb658be4df9989f55be8447e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t FileCheckString::CheckDag (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/dagnotprefixinfo">DagNotPrefixInfo</a> * &gt; &amp; NotStrings, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Matches "dag strings" and their mixed "not strings".</p>

<p>Declaration at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 2329 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#ae3392d2d27cadfad4a5a7f68c44fb7ba">llvm::FileCheckRequest::AllowDeprecatedDagOverlap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca6e00b905236376d8aec56ad3351a45b0">llvm::Check::CheckDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca4f9655da5198915aff91bd25115d22fa">llvm::Check::CheckNot</a>, <a href="#ae85a64defc7f9bea8408ca9e64e3fc45">CheckNot</a>, <a href="#aa76be9b0b55136af940f598eb91664e5">DagNotStrings</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3285d0c2736154c3ea72dbecaa446eec">llvm::handleErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0abf168517cbdcc053154c47b20986837b">llvm::FileCheckDiag::MatchFoundButDiscarded</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="#a3b71a36a299b4598e79edc8cd2fce259">Pat</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5c0cc4b5cb93bf2b53aa2c8d1b8f37b7">reportMatchResult</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult/#a408b0dd15d83a00ea824e3c76fec291d">llvm::Pattern::MatchResult::TheError</a>, <a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult/#abd537aa1cccb03b25c0ea331081ae782">llvm::Pattern::MatchResult::TheMatch</a> and <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#a193992afe00c8b2c9753fb0fab1b9106">llvm::FileCheckRequest::VerboseVerbose</a>.</p>


<p>Referenced by <a href="#ae337924e2723d7d8255011f1ac5624cf">Check</a>.</p>

</div>
</div>

### CheckNext() {#a36305f86aafd6d41b0c449eac6476efd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FileCheckString::CheckNext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies that there is a single line in the given <span class="doxyComputerOutput">Buffer</span>.</p>


<p>Errors are reported against <span class="doxyComputerOutput">SM</span>.</p>


<p>Declaration at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 2246 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca80e33945f521f203f2a632bc0f2041e5">llvm::Check::CheckEmpty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca49f3a249a76b57b5659baae2c45dfb75">llvm::Check::CheckNext</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#ab7ad483468c2163f77072757b399fa86">CountNumNewlinesBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="#aae9b54f909a74427af4aa78f6bedcf05">Loc</a>, <a href="#a3b71a36a299b4598e79edc8cd2fce259">Pat</a>, <a href="#abb2948212a235a5bfc923b3af70bb590">Prefix</a> and <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>.</p>


<p>Referenced by <a href="#ae337924e2723d7d8255011f1ac5624cf">Check</a>.</p>

</div>
</div>

### CheckNot() {#ae85a64defc7f9bea8408ca9e64e3fc45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FileCheckString::CheckNot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/dagnotprefixinfo">DagNotPrefixInfo</a> * &gt; &amp; NotStrings, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies that none of the strings in <span class="doxyComputerOutput">NotStrings</span> are found in the given <span class="doxyComputerOutput">Buffer</span>.</p>


<p>Errors are reported against <span class="doxyComputerOutput">SM</span> and diagnostics recorded in <span class="doxyComputerOutput">Diags</span> according to the verbosity level set in <span class="doxyComputerOutput">Req</span>.</p>


<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 2307 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca4f9655da5198915aff91bd25115d22fa">llvm::Check::CheckNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3285d0c2736154c3ea72dbecaa446eec">llvm::handleErrors</a> and <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5c0cc4b5cb93bf2b53aa2c8d1b8f37b7">reportMatchResult</a>.</p>


<p>Referenced by <a href="#ae337924e2723d7d8255011f1ac5624cf">Check</a> and <a href="#ac71c43fb658be4df9989f55be8447e1d">CheckDag</a>.</p>

</div>
</div>

### CheckSame() {#a82944774d532e6adc41c92e29a00e2e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FileCheckString::CheckSame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies that there is no newline in the given <span class="doxyComputerOutput">Buffer</span>.</p>


<p>Errors are reported against <span class="doxyComputerOutput">SM</span>.</p>


<p>Declaration at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 2285 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaf738504ab1341813c0cda15fa68a6310">llvm::Check::CheckSame</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#ab7ad483468c2163f77072757b399fa86">CountNumNewlinesBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="#aae9b54f909a74427af4aa78f6bedcf05">Loc</a>, <a href="#a3b71a36a299b4598e79edc8cd2fce259">Pat</a>, <a href="#abb2948212a235a5bfc923b3af70bb590">Prefix</a> and <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>.</p>


<p>Referenced by <a href="#ae337924e2723d7d8255011f1ac5624cf">Check</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DagNotStrings {#aa76be9b0b55136af940f598eb91664e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DagNotPrefixInfo&gt; llvm::FileCheckString::DagNotStrings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hold the DAG/NOT strings occurring in the input file.</p>

<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Referenced by <a href="#ac71c43fb658be4df9989f55be8447e1d">CheckDag</a> and <a href="#ac104527c24fbf4fc739aa5bc1e62b107">FileCheckString</a>.</p>

</div>
</div>

### Loc {#aae9b54f909a74427af4aa78f6bedcf05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::FileCheckString::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The location in the match file that the check string was specified.</p>

<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Referenced by <a href="#ae337924e2723d7d8255011f1ac5624cf">Check</a>, <a href="#a36305f86aafd6d41b0c449eac6476efd">CheckNext</a>, <a href="#a82944774d532e6adc41c92e29a00e2e9">CheckSame</a> and <a href="#ac104527c24fbf4fc739aa5bc1e62b107">FileCheckString</a>.</p>

</div>
</div>

### Pat {#a3b71a36a299b4598e79edc8cd2fce259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pattern llvm::FileCheckString::Pat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The pattern to match.</p>

<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Referenced by <a href="#ae337924e2723d7d8255011f1ac5624cf">Check</a>, <a href="#ac71c43fb658be4df9989f55be8447e1d">CheckDag</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a95a7a7f317661b984c86d196fa44dff9">llvm::FileCheck::checkInput</a>, <a href="#a36305f86aafd6d41b0c449eac6476efd">CheckNext</a>, <a href="#a82944774d532e6adc41c92e29a00e2e9">CheckSame</a> and <a href="#ac104527c24fbf4fc739aa5bc1e62b107">FileCheckString</a>.</p>

</div>
</div>

### Prefix {#abb2948212a235a5bfc923b3af70bb590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::FileCheckString::Prefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Which prefix name this check matched.</p>

<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Referenced by <a href="#ae337924e2723d7d8255011f1ac5624cf">Check</a>, <a href="#a36305f86aafd6d41b0c449eac6476efd">CheckNext</a>, <a href="#a82944774d532e6adc41c92e29a00e2e9">CheckSame</a> and <a href="#ac104527c24fbf4fc739aa5bc1e62b107">FileCheckString</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
