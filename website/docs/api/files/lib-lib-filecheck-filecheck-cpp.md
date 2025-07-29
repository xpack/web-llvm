---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/filecheck/filecheck-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `FileCheck.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">llvm/FileCheck/FileCheck.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">llvm/ADT/StringSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/checkedarithmetic-h">llvm/Support/CheckedArithmetic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include &lt;cstdint&gt;
#include &lt;list&gt;
#include &lt;set&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/prefixmatcher">PrefixMatcher</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1eb91b7a599d7ef03c2282a78e99466">nextAPIntBitWidth</a> (unsigned BitWidth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4d3bfb8f8f9526c1e2703ef25f43418">toSigned</a> (APInt AbsVal, bool Negative)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5618db29d0000023a813f4d00e3bf484">popFront</a> (StringRef &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa386d2cd704c6f1176a5aef1f0f178da">ProcessMatchResult</a> (FileCheckDiag::MatchType MatchTy, const SourceMgr &amp;SM, SMLoc Loc, Check::FileCheckType CheckTy, StringRef Buffer, size_t Pos, size_t Len, std::vector&lt; FileCheckDiag &gt; *Diags, bool AdjustPrevDiags=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4c09a15faad3470da62b81f0e2d111f">IsPartOfWord</a> (char c)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; Check::FileCheckType, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a> (const FileCheckRequest &amp;Req, StringRef Buffer, StringRef Prefix, bool &amp;Misspelled)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; Check::FileCheckType, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7417ac794aa39897b5e34fa331d29f4b">FindCheckType</a> (const FileCheckRequest &amp;Req, StringRef Buffer, StringRef Prefix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17ae1981d9821c8ea405bb2d9c785cd8">SkipWord</a> (StringRef Str, size_t Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4199779f05c32f4716378090f22472">addDefaultPrefixes</a> (FileCheckRequest &amp;Req)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a> (const FileCheckRequest &amp;Req, PrefixMatcher &amp;Matcher, StringRef &amp;Buffer, unsigned &amp;LineNumber, Check::FileCheckType &amp;CheckTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Searches the buffer for the first prefix in the prefix regular expression. <a href="#a02aebfa7014b1bf9a52445a58163adb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a> (bool ExpectedMatch, const SourceMgr &amp;SM, StringRef Prefix, SMLoc Loc, const Pattern &amp;Pat, int MatchedCount, StringRef Buffer, Pattern::MatchResult MatchResult, const FileCheckRequest &amp;Req, std::vector&lt; FileCheckDiag &gt; *Diags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns either (1) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorsuccess">ErrorSuccess</a></span> if there was no error or (2) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorreported">ErrorReported</a></span> if an error was reported, such as an unexpected match. <a href="#adadd7e41a96b9e407d8e07cb45a0d6e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d394830d4143542278afee43f527b48">printNoMatch</a> (bool ExpectedMatch, const SourceMgr &amp;SM, StringRef Prefix, SMLoc Loc, const Pattern &amp;Pat, int MatchedCount, StringRef Buffer, Error MatchError, bool VerboseVerbose, std::vector&lt; FileCheckDiag &gt; *Diags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns either (1) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorsuccess">ErrorSuccess</a></span> if there was no error, or (2) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorreported">ErrorReported</a></span> if an error was reported, such as an expected match not found. <a href="#a5d394830d4143542278afee43f527b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0cc4b5cb93bf2b53aa2c8d1b8f37b7">reportMatchResult</a> (bool ExpectedMatch, const SourceMgr &amp;SM, StringRef Prefix, SMLoc Loc, const Pattern &amp;Pat, int MatchedCount, StringRef Buffer, Pattern::MatchResult MatchResult, const FileCheckRequest &amp;Req, std::vector&lt; FileCheckDiag &gt; *Diags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns either (1) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorsuccess">ErrorSuccess</a></span> if there was no error, or (2) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorreported">ErrorReported</a></span> if an error was reported. <a href="#a5c0cc4b5cb93bf2b53aa2c8d1b8f37b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7ad483468c2163f77072757b399fa86">CountNumNewlinesBetween</a> (StringRef Range, const char *&amp;FirstNewLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Counts the number of newlines in the specified range. <a href="#ab7ad483468c2163f77072757b399fa86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1863db0091c416836ecbf151ea73c90">ValidatePrefixes</a> (StringRef Kind, StringSet&lt;&gt; &amp;UniquePrefixes, ArrayRef&lt; StringRef &gt; SuppliedPrefixes)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ec02135bf1d64543cc44379b40d59d">SpaceChars</a> = " \t"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87fef1fd90a9f814f1b62f4346895419">DefaultCheckPrefixes</a>[] = {"CHECK"}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c6721cddb52eb652ee858b650f696fc">DefaultCommentPrefixes</a>[] = {"COM", "RUN"}</td>
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


<div class="doxySectionDef">

## Functions

### addDefaultPrefixes() {#aed4199779f05c32f4716378090f22472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addDefaultPrefixes (<a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req)</td>
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



<p>Definition at line 1642 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#acda76c0767dd2148162859f90b48f8b5">llvm::FileCheckRequest::CheckPrefixes</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#ab3f63b76e1980996f6a99891c5b385f7">llvm::FileCheckRequest::CommentPrefixes</a>, <a href="#a87fef1fd90a9f814f1b62f4346895419">DefaultCheckPrefixes</a>, <a href="#a8c6721cddb52eb652ee858b650f696fc">DefaultCommentPrefixes</a> and <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#a1443b68a9d922cc473ae084aaa14654d">llvm::FileCheckRequest::IsDefaultCheckPrefix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>.</p>

</div>
</div>

### CountNumNewlinesBetween() {#ab7ad483468c2163f77072757b399fa86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CountNumNewlinesBetween (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Range, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *&amp; FirstNewLine)</td>
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

<p>Counts the number of newlines in the specified range.</p>

<p>Definition at line 2143 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a36305f86aafd6d41b0c449eac6476efd">llvm::FileCheckString::CheckNext</a> and <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a82944774d532e6adc41c92e29a00e2e9">llvm::FileCheckString::CheckSame</a>.</p>

</div>
</div>

### FindCheckType() {#a7a9dc76f6cda36296f3df309700937e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Check::FileCheckType, StringRef &gt; FindCheckType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, bool &amp; Misspelled)</td>
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



<p>Definition at line 1534 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccab74df0ffb39a8f2c0918324e23a899f2">llvm::Check::CheckBadCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca8b26e2b469fdd62f96446d3299b4189e">llvm::Check::CheckBadNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaf16a622382af4f7939c473b436c8f2ca">llvm::Check::CheckComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca6e00b905236376d8aec56ad3351a45b0">llvm::Check::CheckDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca80e33945f521f203f2a632bc0f2041e5">llvm::Check::CheckEmpty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccad88307ccd9067d72cfb0e62d19daa77d">llvm::Check::CheckLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca49f3a249a76b57b5659baae2c45dfb75">llvm::Check::CheckNext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca9852bebd673f9c43a584b08401e3197d">llvm::Check::CheckNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca4f9655da5198915aff91bd25115d22fa">llvm::Check::CheckNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca166f25ea09a5e0064149ae472c8d8f2e">llvm::Check::CheckPlain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaf738504ab1341813c0cda15fa68a6310">llvm::Check::CheckSame</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#ab3f63b76e1980996f6a99891c5b385f7">llvm::FileCheckRequest::CommentPrefixes</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8265efd805e4ce0c9d3c18e78194324c">llvm::StringRef::ltrim</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#a7417ac794aa39897b5e34fa331d29f4b">FindCheckType</a> and <a href="#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>.</p>

</div>
</div>

### FindCheckType() {#a7417ac794aa39897b5e34fa331d29f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Check::FileCheckType, StringRef &gt; FindCheckType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
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



<p>Definition at line 1624 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccabced3746e039f44b8e662be748fd4e17">llvm::Check::CheckMisspelled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca9852bebd673f9c43a584b08401e3197d">llvm::Check::CheckNone</a> and <a href="#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a>.</p>

</div>
</div>

### FindFirstMatchingPrefix() {#a02aebfa7014b1bf9a52445a58163adb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; StringRef, StringRef &gt; FindFirstMatchingPrefix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req, <a href="/web-llvm/docs/api/structs/prefixmatcher">PrefixMatcher</a> &amp; Matcher, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Buffer, unsigned &amp; LineNumber, Check::FileCheckType &amp; CheckTy)</td>
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

<p>Searches the buffer for the first prefix in the prefix regular expression.</p>


<p>This searches the buffer using the provided regular expression, however it enforces constraints beyond that: 1) The found prefix must not be a suffix of something that looks like a valid prefix. 2) The found prefix must be followed by a valid check type suffix using <span class="doxyComputerOutput">FindCheckType</span> above.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>a pair of StringRefs into the Buffer, which combines:</p>


<ul class="doxyList ">
<li>the first match of the regular expression to satisfy these two is returned, otherwise an empty <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> is returned to indicate failure.</li>
<li>buffer rewound to the location right after parsed suffix, for parsing to continue from</li>
</ul>
</dd>
</dl>


<p>If this routine returns a valid prefix, it will also shrink <span class="doxyComputerOutput">Buffer</span> to start at the beginning of the returned prefix, increment <span class="doxyComputerOutput">LineNumber</span> for each new line consumed from <span class="doxyComputerOutput">Buffer</span>, and set <span class="doxyComputerOutput">CheckTy</span> to the type of check found by examining the suffix.</p>


<p>If no valid prefix is found, the state of Buffer, LineNumber, and CheckTy is unspecified.</p>


<p>Definition at line 1717 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5b6faabb08339ea1dd11e9d37a668634">llvm::StringRef::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca9852bebd673f9c43a584b08401e3197d">llvm::Check::CheckNone</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ac2c31b7b3c778d12aa176f9253511f37">llvm::StringRef::count</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a>, <a href="#af4c09a15faad3470da62b81f0e2d111f">IsPartOfWord</a>, <a href="/web-llvm/docs/api/structs/prefixmatcher/#a06d7229c302f7f9a6e42ad1afdc957c9">PrefixMatcher::match</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="#a17ae1981d9821c8ea405bb2d9c785cd8">SkipWord</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>.</p>

</div>
</div>

### IsPartOfWord() {#af4c09a15faad3470da62b81f0e2d111f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsPartOfWord (char c)</td>
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



<p>Definition at line 1470 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Referenced by <a href="#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a> and <a href="#a17ae1981d9821c8ea405bb2d9c785cd8">SkipWord</a>.</p>

</div>
</div>

### nextAPIntBitWidth() {#af1eb91b7a599d7ef03c2282a78e99466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned nextAPIntBitWidth (unsigned BitWidth)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#aaf70a90533b469062634730e27f6577d">llvm::APInt::APINT_BITS_PER_WORD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/binaryoperation/#ae881b7ad9c843880674599dbe5d85dd9">llvm::BinaryOperation::eval</a> and <a href="#ac4d3bfb8f8f9526c1e2703ef25f43418">toSigned</a>.</p>

</div>
</div>

### popFront() {#a5618db29d0000023a813f4d00e3bf484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char popFront (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; S)</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>.</p>

</div>
</div>

### printMatch() {#adadd7e41a96b9e407d8e07cb45a0d6e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error printMatch (bool ExpectedMatch, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> &amp; Pat, int MatchedCount, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult">Pattern::MatchResult</a> MatchResult, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags)</td>
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

<p>Returns either (1) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorsuccess">ErrorSuccess</a></span> if there was no error or (2) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorreported">ErrorReported</a></span> if an error was reported, such as an unexpected match.</p>

<p>Definition at line 1975 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaba2d525032487e7def52c8154b19e29c">llvm::Check::CheckEOF</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ae5a15719ab746bdc7713c4784fc1c6ea">llvm::SourceMgr::DK_Remark</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ac112adffc4bcc18c146110a4c648b683">llvm::Pattern::getCheckTy</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#abc8c2d9a0d0a8809940c9627857135ca">llvm::Pattern::getCount</a>, <a href="/web-llvm/docs/api/classes/llvm/check/filechecktype/#a28c2d38b7ebdeb9e3046f013c8ffa8a4">llvm::Check::FileCheckType::getDescription</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0adcf3e4ffa0433fb40711377d53b4baf1">llvm::FileCheckDiag::MatchFoundAndExpected</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0a66b95270a54c88af1ba70b794aa836f8">llvm::FileCheckDiag::MatchFoundButExcluded</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3a4e8a88439506522a2a0f3850802d3f">llvm::Pattern::printSubstitutions</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a91f729b936911342abb6b606e0606cdc">llvm::Pattern::printVariableDefs</a>, <a href="#aa386d2cd704c6f1176a5aef1f0f178da">ProcessMatchResult</a>, <a href="/web-llvm/docs/api/classes/llvm/errorreported/#a0412a33f257fe2933d2425c36d985bd3">llvm::ErrorReported::reportedOrSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/smrange/#a95721f80bb5e9cfa8571695f8807881b">llvm::SMRange::Start</a>, <a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult/#a408b0dd15d83a00ea824e3c76fec291d">llvm::Pattern::MatchResult::TheError</a>, <a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult/#abd537aa1cccb03b25c0ea331081ae782">llvm::Pattern::MatchResult::TheMatch</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#aa17abc10f9ba381d31d7271db615ad16">llvm::FileCheckRequest::Verbose</a> and <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#a193992afe00c8b2c9753fb0fab1b9106">llvm::FileCheckRequest::VerboseVerbose</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ac71c43fb658be4df9989f55be8447e1d">llvm::FileCheckString::CheckDag</a> and <a href="#a5c0cc4b5cb93bf2b53aa2c8d1b8f37b7">reportMatchResult</a>.</p>

</div>
</div>

### printNoMatch() {#a5d394830d4143542278afee43f527b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error printNoMatch (bool ExpectedMatch, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> &amp; Pat, int MatchedCount, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> MatchError, bool VerboseVerbose, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags)</td>
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

<p>Returns either (1) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorsuccess">ErrorSuccess</a></span> if there was no error, or (2) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorreported">ErrorReported</a></span> if an error was reported, such as an expected match not found.</p>

<p>Definition at line 2045 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ae5a15719ab746bdc7713c4784fc1c6ea">llvm::SourceMgr::DK_Remark</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ac112adffc4bcc18c146110a4c648b683">llvm::Pattern::getCheckTy</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#abc8c2d9a0d0a8809940c9627857135ca">llvm::Pattern::getCount</a>, <a href="/web-llvm/docs/api/classes/llvm/check/filechecktype/#a28c2d38b7ebdeb9e3046f013c8ffa8a4">llvm::Check::FileCheckType::getDescription</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0a4a92716c994d8a58dc2e6b158e2b2f3f">llvm::FileCheckDiag::MatchNoneAndExcluded</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0afc543db8ad6f068fab3eea06297e0ebc">llvm::FileCheckDiag::MatchNoneButExpected</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0ad139fc8ba0eace914c3d91f8c51c35b1">llvm::FileCheckDiag::MatchNoneForInvalidPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3331028c9eef66f4022ac3efa310af7d">llvm::Pattern::printFuzzyMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3a4e8a88439506522a2a0f3850802d3f">llvm::Pattern::printSubstitutions</a>, <a href="#aa386d2cd704c6f1176a5aef1f0f178da">ProcessMatchResult</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/errorreported/#a0412a33f257fe2933d2425c36d985bd3">llvm::ErrorReported::reportedOrSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smrange/#a95721f80bb5e9cfa8571695f8807881b">llvm::SMRange::Start</a>.</p>


<p>Referenced by <a href="#a5c0cc4b5cb93bf2b53aa2c8d1b8f37b7">reportMatchResult</a>.</p>

</div>
</div>

### ProcessMatchResult() {#aa386d2cd704c6f1176a5aef1f0f178da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange ProcessMatchResult (<a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0">FileCheckDiag::MatchType</a> MatchTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, Check::FileCheckType CheckTy, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, size_t Pos, size_t Len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags, bool AdjustPrevDiags=false)</td>
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



<p>Definition at line 1292 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ae337924e2723d7d8255011f1ac5624cf">llvm::FileCheckString::Check</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3331028c9eef66f4022ac3efa310af7d">llvm::Pattern::printFuzzyMatch</a>, <a href="#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a> and <a href="#a5d394830d4143542278afee43f527b48">printNoMatch</a>.</p>

</div>
</div>

### reportMatchResult() {#a5c0cc4b5cb93bf2b53aa2c8d1b8f37b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error reportMatchResult (bool ExpectedMatch, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> &amp; Pat, int MatchedCount, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult">Pattern::MatchResult</a> MatchResult, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags)</td>
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

<p>Returns either (1) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorsuccess">ErrorSuccess</a></span> if there was no error, or (2) <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/errorreported">ErrorReported</a></span> if an error was reported.</p>

<p>Definition at line 2128 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a>, <a href="#a5d394830d4143542278afee43f527b48">printNoMatch</a>, <a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult/#a408b0dd15d83a00ea824e3c76fec291d">llvm::Pattern::MatchResult::TheError</a>, <a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult/#abd537aa1cccb03b25c0ea331081ae782">llvm::Pattern::MatchResult::TheMatch</a> and <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#a193992afe00c8b2c9753fb0fab1b9106">llvm::FileCheckRequest::VerboseVerbose</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ae337924e2723d7d8255011f1ac5624cf">llvm::FileCheckString::Check</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ac71c43fb658be4df9989f55be8447e1d">llvm::FileCheckString::CheckDag</a> and <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ae85a64defc7f9bea8408ca9e64e3fc45">llvm::FileCheckString::CheckNot</a>.</p>

</div>
</div>

### SkipWord() {#a17ae1981d9821c8ea405bb2d9c785cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t SkipWord (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, size_t Loc)</td>
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



<p>Definition at line 1633 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Reference <a href="#af4c09a15faad3470da62b81f0e2d111f">IsPartOfWord</a>.</p>


<p>Referenced by <a href="#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>.</p>

</div>
</div>

### toSigned() {#ac4d3bfb8f8f9526c1e2703ef25f43418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt toSigned (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> AbsVal, bool Negative)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ada19a89b7c62ce0bb713a7254b002445">llvm::APInt::isSignBitSet</a>, <a href="#af1eb91b7a599d7ef03c2282a78e99466">nextAPIntBitWidth</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a0637f71055413c64c6bf057ea581f535">llvm::ExpressionFormat::valueFromStringRepr</a>.</p>

</div>
</div>

### ValidatePrefixes() {#ae1863db0091c416836ecbf151ea73c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ValidatePrefixes (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a>&lt;&gt; &amp; UniquePrefixes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; SuppliedPrefixes)</td>
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



<p>Definition at line 2468 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/stringset/#add93efa62e06c599f1734f3b206232a0">llvm::StringSet&lt; AllocatorTy &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#ae787b71e8d775a2b662d04e913489d8d">llvm::Regex::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecheck/#adf5e24a0f2fd2cbea147c73975624359">llvm::FileCheck::ValidateCheckPrefixes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DefaultCheckPrefixes {#a87fef1fd90a9f814f1b62f4346895419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* DefaultCheckPrefixes[] = {"CHECK"}</td>
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



<p>Definition at line 1639 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Referenced by <a href="#aed4199779f05c32f4716378090f22472">addDefaultPrefixes</a> and <a href="/web-llvm/docs/api/classes/llvm/filecheck/#adf5e24a0f2fd2cbea147c73975624359">llvm::FileCheck::ValidateCheckPrefixes</a>.</p>

</div>
</div>

### DefaultCommentPrefixes {#a8c6721cddb52eb652ee858b650f696fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* DefaultCommentPrefixes[] = {"COM", "RUN"}</td>
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



<p>Definition at line 1640 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Referenced by <a href="#aed4199779f05c32f4716378090f22472">addDefaultPrefixes</a> and <a href="/web-llvm/docs/api/classes/llvm/filecheck/#adf5e24a0f2fd2cbea147c73975624359">llvm::FileCheck::ValidateCheckPrefixes</a>.</p>

</div>
</div>

### SpaceChars {#a56ec02135bf1d64543cc44379b40d59d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral SpaceChars = " \t"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
