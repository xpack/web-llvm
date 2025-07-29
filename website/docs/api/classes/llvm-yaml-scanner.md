---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/yaml/scanner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Scanner` Class

<p>Scans YAML tokens from a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::yaml::Scanner { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f99d5aea0fe6bec1878f86a445f02db">SkipWhileFunc</a> = <a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a>(Scanner::*)(<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09031fd950bad51b931a2549417ad3f3">Scanner</a> (StringRef Input, SourceMgr &amp;SM, bool ShowColors=true, std::error_code *EC=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd342945825d1781793fed768a8a0fc1">Scanner</a> (MemoryBufferRef Buffer, SourceMgr &amp;SM_, bool ShowColors=true, std::error_code *EC=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/token">Token</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06b97628ff8ed484aac9ebc5306c010">peekNext</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the next token and return it without popping it. <a href="#ab06b97628ff8ed484aac9ebc5306c010">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5876373ad6798a36388fb54b9996bdf0">getNext</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the next token and pop it from the queue. <a href="#a5876373ad6798a36388fb54b9996bdf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa507f4be7455b212d8040c83bcc94841">printError</a> (SMLoc Loc, SourceMgr::DiagKind Kind, const Twine &amp;Message, ArrayRef&lt; SMRange &gt; Ranges={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4406ec44082e06c99c2b7463dbf77b1c">setError</a> (const Twine &amp;Message, StringRef::iterator Position)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80fc2acfaccf19dc765ccfd19094b706">failed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if an error occurred while parsing. <a href="#a80fc2acfaccf19dc765ccfd19094b706">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36412e93e294231f363398ee6ae05be6">init</a> (MemoryBufferRef Buffer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae23493f3c154b65cb6ff573786a99c6d">currentInput</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a312eeacf9361f1c1516dbafdec94e500">UTF8Decoded</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c8464739c3be84e6445d7eb53e453a">decodeUTF8</a> (StringRef::iterator Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode a UTF-8 minimal well-formed code unit subsequence starting at <em>Position</em>. <a href="#ab4c8464739c3be84e6445d7eb53e453a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d41cf86d00f27ddbcd3725dc2cb252">skip_nb_char</a> (StringRef::iterator Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip a single nb-char[27] starting at Position. <a href="#ad9d41cf86d00f27ddbcd3725dc2cb252">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47814db56f7bc825c1adaeb042e57a7">skip_b_break</a> (StringRef::iterator Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip a single b-break[28] starting at Position. <a href="#ad47814db56f7bc825c1adaeb042e57a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d23b3ff8aff35d5582dbf450840da8">skip_s_space</a> (StringRef::iterator Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip a single s-space[31] starting at Position. <a href="#ac9d23b3ff8aff35d5582dbf450840da8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af773459cf8d562cca498097e9dcac974">skip_s_white</a> (StringRef::iterator Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip a single s-white[33] starting at Position. <a href="#af773459cf8d562cca498097e9dcac974">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7e4fcbc7260d434466a43e5a230dd65">skip_ns_char</a> (StringRef::iterator Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip a single ns-char[34] starting at Position. <a href="#aa7e4fcbc7260d434466a43e5a230dd65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46985700e81f8c5af1b95ca80ca1a410">skip_while</a> (SkipWhileFunc Func, StringRef::iterator Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip minimal well-formed code unit subsequences until Func returns its input. <a href="#a46985700e81f8c5af1b95ca80ca1a410">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e1a8134fc8c2fe7ecb75d9754e0387">advanceWhile</a> (SkipWhileFunc Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip minimal well-formed code unit subsequences until Func returns its input. <a href="#a65e1a8134fc8c2fe7ecb75d9754e0387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6240089d197410f111b6d22c1130ed92">scan_ns_uri_char</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan ns-uri-char[39]s starting at Cur. <a href="#a6240089d197410f111b6d22c1130ed92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc2ae42328475f24b90df6098183412">consume</a> (uint32_t Expected)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Consume a minimal well-formed code unit subsequence starting at <em>Cur</em>. <a href="#a5fc2ae42328475f24b90df6098183412">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad11ebb973a2ee46b5fde5aa1061546fa">skip</a> (uint32_t Distance)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip <em>Distance</em> UTF-8 code units. Updates <em>Cur</em> and <em>Column</em>. <a href="#ad11ebb973a2ee46b5fde5aa1061546fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae040c97bdd0d4d786e9fca25069211e8">isBlankOrBreak</a> (StringRef::iterator Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the minimal well-formed code unit subsequence at Pos is whitespace or a new line. <a href="#ae040c97bdd0d4d786e9fca25069211e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a580bd063d9d7f0da581b2199337d99b0">isPlainSafeNonBlank</a> (StringRef::iterator Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the minimal well-formed code unit subsequence at Pos is considered a "safe" character for plain scalars. <a href="#a580bd063d9d7f0da581b2199337d99b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3362adeb38c4e0d3f0048bbeae03b3af">isLineEmpty</a> (StringRef Line)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the line is a line break, false otherwise. <a href="#a3362adeb38c4e0d3f0048bbeae03b3af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6caf929abcb783eae1b40c9ebff2454e">consumeLineBreakIfPresent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Consume a single b-break[28] if it's present at the current position. <a href="#a6caf929abcb783eae1b40c9ebff2454e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3f7d524d3a61476f60a6909dfddb77">saveSimpleKeyCandidate</a> (TokenQueueT::iterator Tok, unsigned AtColumn, bool IsRequired)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If IsSimpleKeyAllowed, create and push_back a new SimpleKey. <a href="#a1b3f7d524d3a61476f60a6909dfddb77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1269183d8256cf9fbe1b4dcf0fd64739">removeStaleSimpleKeyCandidates</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove simple keys that can no longer be valid simple keys. <a href="#a1269183d8256cf9fbe1b4dcf0fd64739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee11cad4b757fe6b93a2b500295e216c">removeSimpleKeyCandidatesOnFlowLevel</a> (unsigned Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all simple keys on FlowLevel <em>Level</em>. <a href="#aee11cad4b757fe6b93a2b500295e216c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88ec6c05717f313fc521050a81be7c54">unrollIndent</a> (int ToColumn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unroll indentation in <em>Indents</em> back to <em>Col</em>. <a href="#a88ec6c05717f313fc521050a81be7c54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e01eff3695e304464415c7d4b4a877a">rollIndent</a> (int ToColumn, Token::TokenKind Kind, TokenQueueT::iterator InsertPoint)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Increase indent to <em>Col</em>. <a href="#a2e01eff3695e304464415c7d4b4a877a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124dfda3bacd940f3c4022d852f01811">skipComment</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip a single-line comment when the comment starts at the current position of the scanner. <a href="#a124dfda3bacd940f3c4022d852f01811">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ba6d9601cc54ba644f60ac873744bb">scanToNextToken</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip whitespace and comments until the start of the next token. <a href="#a67ba6d9601cc54ba644f60ac873744bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a055f1903ad9d69514f9be6570f4a2293">scanStreamStart</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Must be the first token generated. <a href="#a055f1903ad9d69514f9be6570f4a2293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c2a82f35954e4d516c65d0105ec2d5">scanStreamEnd</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate tokens needed to close out the stream. <a href="#a94c2a82f35954e4d516c65d0105ec2d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30b1ba20663711480d93dcc80534b299">scanDirective</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a BLAH directive. <a href="#a30b1ba20663711480d93dcc80534b299">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a654d287edcf47d5616108e4a39f6f3b0">scanDocumentIndicator</a> (bool IsStart)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a ... or —. <a href="#a654d287edcf47d5616108e4a39f6f3b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669ce6d50bc25387f8d672a7bbd90f71">scanFlowCollectionStart</a> (bool IsSequence)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a [ or { and generate the proper flow collection start token. <a href="#a669ce6d50bc25387f8d672a7bbd90f71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6009b9b0b14e67877b2f4caeb8b963ae">scanFlowCollectionEnd</a> (bool IsSequence)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a ] or } and generate the proper flow collection end token. <a href="#a6009b9b0b14e67877b2f4caeb8b963ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e011c0b365ebf56bc047142eddf7a27">scanFlowEntry</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan the , that separates entries in a flow collection. <a href="#a0e011c0b365ebf56bc047142eddf7a27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05461b59884ae5a34b64ac484d784534">scanBlockEntry</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan the - that starts block sequence entries. <a href="#a05461b59884ae5a34b64ac484d784534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af65312d874fe36fc179f4986662aa613">scanKey</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan an explicit ? indicating a key. <a href="#af65312d874fe36fc179f4986662aa613">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11e4d1b0dcacb0fac2cf9bce802a167f">scanValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan an explicit : indicating a value. <a href="#a11e4d1b0dcacb0fac2cf9bce802a167f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c71a5914d035f0652aaa6761382981">scanFlowScalar</a> (bool IsDoubleQuoted)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a quoted scalar. <a href="#a36c71a5914d035f0652aaa6761382981">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acebe1124c2879b25c3ee0300fcf8bb02">scanPlainScalar</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan an unquoted scalar. <a href="#acebe1124c2879b25c3ee0300fcf8bb02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bcb28cf0239d9c97bc011f4e84b4d19">scanAliasOrAnchor</a> (bool IsAlias)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan an Alias or Anchor starting with * or &amp;. <a href="#a7bcb28cf0239d9c97bc011f4e84b4d19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac766784f0dca94d3aeab5ca5f90b4a30">scanBlockScalar</a> (bool IsLiteral)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a block scalar starting with | or &gt;. <a href="#ac766784f0dca94d3aeab5ca5f90b4a30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6143ae4cc2889bc805b47f42f360e5d">scanBlockScalarIndicators</a> (char &amp;StyleIndicator, char &amp;ChompingIndicator, unsigned &amp;IndentIndicator, bool &amp;IsDone)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a block scalar style indicator and header. <a href="#ac6143ae4cc2889bc805b47f42f360e5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d643a9bc7664a5a5796c820b245614">scanBlockStyleIndicator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a style indicator in a block scalar header. <a href="#aa5d643a9bc7664a5a5796c820b245614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059b5098e3b4b2284006b50f9593ac07">scanBlockChompingIndicator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a chomping indicator in a block scalar header. <a href="#a059b5098e3b4b2284006b50f9593ac07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c824ec7ff4e9a7b08f160610496770">scanBlockIndentationIndicator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan an indentation indicator in a block scalar header. <a href="#a15c824ec7ff4e9a7b08f160610496770">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc0163434aded3d4ae3eaeed32e5a6ec">scanBlockScalarHeader</a> (char &amp;ChompingIndicator, unsigned &amp;IndentIndicator, bool &amp;IsDone)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a block scalar header. <a href="#abc0163434aded3d4ae3eaeed32e5a6ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce4a46167b7980663fcb828587915c2">findBlockScalarIndent</a> (unsigned &amp;BlockIndent, unsigned BlockExitIndent, unsigned &amp;LineBreaks, bool &amp;IsDone)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for the indentation level of a block scalar. <a href="#a8ce4a46167b7980663fcb828587915c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84afe41c0be23e82f07667c57930f1c4">scanBlockScalarIndent</a> (unsigned BlockIndent, unsigned BlockExitIndent, bool &amp;IsDone)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan the indentation of a text line in a block scalar. <a href="#a84afe41c0be23e82f07667c57930f1c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23038a39c7e7c48cf3d8b270da494eb4">scanTag</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan a tag of the form !stuff. <a href="#a23038a39c7e7c48cf3d8b270da494eb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a6a3995d2a2499a2925fb3cce43e0b">fetchMoreTokens</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispatch to the next scanning function based on <em>*Cur</em>. <a href="#a82a6a3995d2a2499a2925fb3cce43e0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab085ea94efdac4ff2766cba8f8a28cdd">SM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> used for diagnostics and buffer management. <a href="#ab085ea94efdac4ff2766cba8f8a28cdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af43a72c3c27355908afd24174b5ea0ef">InputBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The original input. <a href="#af43a72c3c27355908afd24174b5ea0ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c308b3af89a4eb128d361990506ab6f">Current</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current position of the scanner. <a href="#a1c308b3af89a4eb128d361990506ab6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8542f381f5906a949c8d86f99b7dabae">End</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The end of the input (one past the last character). <a href="#a8542f381f5906a949c8d86f99b7dabae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1abe827783eb489d9f01fa5b69ec2276">Indent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current YAML indentation level in spaces. <a href="#a1abe827783eb489d9f01fa5b69ec2276">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a299dc30ebc42e765ef4eaf12e353d6">Column</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current column number in Unicode code points. <a href="#a0a299dc30ebc42e765ef4eaf12e353d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c7690a48828885761d85d226207b4a">Line</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current line number. <a href="#a63c7690a48828885761d85d226207b4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c70383b5e34aa33cdfe3e0a3d503d99">FlowLevel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How deep we are in flow style containers. 0 Means at block level. <a href="#a4c70383b5e34aa33cdfe3e0a3d503d99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfeedfd15ada95a61cfca3d52a6257d4">IsStartOfStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are we at the start of the stream? <a href="#acfeedfd15ada95a61cfca3d52a6257d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69ae8f54742f6800ab87f1fa795128b">IsSimpleKeyAllowed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can the next token be the start of a simple key? <a href="#af69ae8f54742f6800ab87f1fa795128b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae42285fe15501ac90691aaf239806532">IsAdjacentValueAllowedInFlow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can the next token be a value indicator even if it does not have a trailing space? <a href="#ae42285fe15501ac90691aaf239806532">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1b043ba45198d363a07b528b92903e">Failed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if an error has occurred. <a href="#a9a1b043ba45198d363a07b528b92903e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d8ddfb95a787acf0ff82a95b1c90e0">ShowColors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should colors be used when printing out the diagnostic messages? <a href="#a12d8ddfb95a787acf0ff82a95b1c90e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#ae4fd0b9d6e0e9f3892b611f8e82a1f90">TokenQueueT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac897d9fa20cb8c75266aa76a11aa5164">TokenQueue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Queue of tokens. <a href="#ac897d9fa20cb8c75266aa76a11aa5164">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6fae4d2314dfc2d775c043288c7f06">Indents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indentation levels. <a href="#add6fae4d2314dfc2d775c043288c7f06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; SimpleKey, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af01384842d66ef57c768d676501053da">SimpleKeys</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Potential simple keys. <a href="#af01384842d66ef57c768d676501053da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9dcbd7bd91062ffc564cf2e5a30a4e">EC</a></td>
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

<p>Scans YAML tokens from a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### SkipWhileFunc {#a1f99d5aea0fe6bec1878f86a445f02db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::yaml::Scanner::SkipWhileFunc =  StringRef::iterator (Scanner::*)(StringRef::iterator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Scanner() {#a09031fd950bad51b931a2549417ad3f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scanner::Scanner (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Input, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, bool ShowColors=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, std::error_code * EC=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### Scanner() {#acd342945825d1781793fed768a8a0fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scanner::Scanner (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM_, bool ShowColors=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, std::error_code * EC=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### failed() {#a80fc2acfaccf19dc765ccfd19094b706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::Scanner::failed ()</td>
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

<p>Returns true if an error occurred while parsing.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### getNext() {#a5876373ad6798a36388fb54b9996bdf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token Scanner::getNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the next token and pop it from the queue.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Reference <a href="#ab06b97628ff8ed484aac9ebc5306c010">peekNext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a0cd0bee5524ca6391139da12d74c2632">llvm::yaml::dumpTokens</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a5ce7fd9c11f22cd3e9c74d9def608457">llvm::yaml::scanTokens</a>.</p>

</div>
</div>

### peekNext() {#ab06b97628ff8ed484aac9ebc5306c010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token &amp; Scanner::peekNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the next token and return it without popping it.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#a5876373ad6798a36388fb54b9996bdf0">getNext</a>.</p>

</div>
</div>

### printError() {#aa507f4be7455b212d8040c83bcc94841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::Scanner::printError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777">SourceMgr::DiagKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &gt; Ranges={})</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Referenced by <a href="#a4406ec44082e06c99c2b7463dbf77b1c">setError</a>.</p>

</div>
</div>

### setError() {#a4406ec44082e06c99c2b7463dbf77b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::Scanner::setError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a> and <a href="#aa507f4be7455b212d8040c83bcc94841">printError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### advanceWhile() {#a65e1a8134fc8c2fe7ecb75d9754e0387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Scanner::advanceWhile (SkipWhileFunc Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip minimal well-formed code unit subsequences until Func returns its input.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### consume() {#a5fc2ae42328475f24b90df6098183412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::consume (uint32_t Expected)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Consume a minimal well-formed code unit subsequence starting at <em>Cur</em>.</p>


<p>Return false if it is not the same Unicode scalar value as <em><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a></em>. This updates <em>Column</em>.</p>


<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### consumeLineBreakIfPresent() {#a6caf929abcb783eae1b40c9ebff2454e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::consumeLineBreakIfPresent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Consume a single b-break[28] if it's present at the current position.</p>


<p>Return false if the code unit at the current position isn't a line break.</p>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### currentInput() {#ae23493f3c154b65cb6ff573786a99c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::Scanner::currentInput ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### decodeUTF8() {#ab4c8464739c3be84e6445d7eb53e453a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UTF8Decoded llvm::yaml::Scanner::decodeUTF8 (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
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

<p>Decode a UTF-8 minimal well-formed code unit subsequence starting at <em>Position</em>.</p>


<p>If the UTF-8 code units starting at Position do not form a well-formed code unit subsequence, then the Unicode scalar value is 0, and the length is 0.</p>


<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### fetchMoreTokens() {#a82a6a3995d2a2499a2925fb3cce43e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::fetchMoreTokens ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dispatch to the next scanning function based on <em>*Cur</em>.</p>

<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### findBlockScalarIndent() {#a8ce4a46167b7980663fcb828587915c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::findBlockScalarIndent (unsigned &amp; BlockIndent, unsigned BlockExitIndent, unsigned &amp; LineBreaks, bool &amp; IsDone)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for the indentation level of a block scalar.</p>


<p>Return false if an error occurred.</p>


<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### init() {#a36412e93e294231f363398ee6ae05be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Scanner::init (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### isBlankOrBreak() {#ae040c97bdd0d4d786e9fca25069211e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::isBlankOrBreak (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the minimal well-formed code unit subsequence at Pos is whitespace or a new line.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### isLineEmpty() {#a3362adeb38c4e0d3f0048bbeae03b3af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::isLineEmpty (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the line is a line break, false otherwise.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### isPlainSafeNonBlank() {#a580bd063d9d7f0da581b2199337d99b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::isPlainSafeNonBlank (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the minimal well-formed code unit subsequence at Pos is considered a "safe" character for plain scalars.</p>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### removeSimpleKeyCandidatesOnFlowLevel() {#aee11cad4b757fe6b93a2b500295e216c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Scanner::removeSimpleKeyCandidatesOnFlowLevel (unsigned Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all simple keys on FlowLevel <em>Level</em>.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### removeStaleSimpleKeyCandidates() {#a1269183d8256cf9fbe1b4dcf0fd64739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Scanner::removeStaleSimpleKeyCandidates ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove simple keys that can no longer be valid simple keys.</p>


<p>Invalid simple keys are not on the current line or are further than 1024 columns back.</p>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### rollIndent() {#a2e01eff3695e304464415c7d4b4a877a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::rollIndent (int ToColumn, <a href="/web-llvm/docs/api/structs/llvm/yaml/token/#a160e10c0839740601f1138548ddb0531">Token::TokenKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/allocatorlist/#a8cf6516b2732f1ba16dc5694bf3194d0">TokenQueueT::iterator</a> InsertPoint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Increase indent to <em>Col</em>.</p>


<p>Creates <em>Kind</em> token at <em><a href="/web-llvm/docs/api/classes/llvm/irbuilder">InsertPoint</a></em> if needed.</p>


<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### saveSimpleKeyCandidate() {#a1b3f7d524d3a61476f60a6909dfddb77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Scanner::saveSimpleKeyCandidate (<a href="/web-llvm/docs/api/classes/llvm/allocatorlist/#a8cf6516b2732f1ba16dc5694bf3194d0">TokenQueueT::iterator</a> Tok, unsigned AtColumn, bool IsRequired)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If IsSimpleKeyAllowed, create and push_back a new SimpleKey.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scan\_ns\_uri\_char() {#a6240089d197410f111b6d22c1130ed92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Scanner::scan_ns_uri_char ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan ns-uri-char[39]s starting at Cur.</p>


<p>This updates Cur and Column while scanning.</p>


<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanAliasOrAnchor() {#a7bcb28cf0239d9c97bc011f4e84b4d19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanAliasOrAnchor (bool IsAlias)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan an Alias or Anchor starting with * or &amp;.</p>

<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanBlockChompingIndicator() {#a059b5098e3b4b2284006b50f9593ac07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char Scanner::scanBlockChompingIndicator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a chomping indicator in a block scalar header.</p>

<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanBlockEntry() {#a05461b59884ae5a34b64ac484d784534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanBlockEntry ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan the - that starts block sequence entries.</p>

<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanBlockIndentationIndicator() {#a15c824ec7ff4e9a7b08f160610496770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Scanner::scanBlockIndentationIndicator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan an indentation indicator in a block scalar header.</p>

<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanBlockScalar() {#ac766784f0dca94d3aeab5ca5f90b4a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanBlockScalar (bool IsLiteral)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a block scalar starting with | or &gt;.</p>

<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanBlockScalarHeader() {#abc0163434aded3d4ae3eaeed32e5a6ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanBlockScalarHeader (char &amp; ChompingIndicator, unsigned &amp; IndentIndicator, bool &amp; IsDone)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a block scalar header.</p>


<p>Return false if an error occurred.</p>


<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanBlockScalarIndent() {#a84afe41c0be23e82f07667c57930f1c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanBlockScalarIndent (unsigned BlockIndent, unsigned BlockExitIndent, bool &amp; IsDone)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan the indentation of a text line in a block scalar.</p>


<p>Return false if an error occurred.</p>


<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanBlockScalarIndicators() {#ac6143ae4cc2889bc805b47f42f360e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanBlockScalarIndicators (char &amp; StyleIndicator, char &amp; ChompingIndicator, unsigned &amp; IndentIndicator, bool &amp; IsDone)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a block scalar style indicator and header.</p>


<p>Note: This is distinct from scanBlockScalarHeader to mirror the fact that YAML does not consider the style indicator to be a part of the header.</p>


<p>Return false if an error occurred.</p>


<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanBlockStyleIndicator() {#aa5d643a9bc7664a5a5796c820b245614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char Scanner::scanBlockStyleIndicator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a style indicator in a block scalar header.</p>

<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanDirective() {#a30b1ba20663711480d93dcc80534b299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a BLAH directive.</p>

<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanDocumentIndicator() {#a654d287edcf47d5616108e4a39f6f3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanDocumentIndicator (bool IsStart)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a ... or —.</p>

<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanFlowCollectionEnd() {#a6009b9b0b14e67877b2f4caeb8b963ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanFlowCollectionEnd (bool IsSequence)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a ] or } and generate the proper flow collection end token.</p>

<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanFlowCollectionStart() {#a669ce6d50bc25387f8d672a7bbd90f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanFlowCollectionStart (bool IsSequence)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a [ or { and generate the proper flow collection start token.</p>

<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanFlowEntry() {#a0e011c0b365ebf56bc047142eddf7a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanFlowEntry ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan the , that separates entries in a flow collection.</p>

<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanFlowScalar() {#a36c71a5914d035f0652aaa6761382981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanFlowScalar (bool IsDoubleQuoted)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a quoted scalar.</p>

<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanKey() {#af65312d874fe36fc179f4986662aa613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanKey ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan an explicit ? indicating a key.</p>

<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanPlainScalar() {#acebe1124c2879b25c3ee0300fcf8bb02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanPlainScalar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan an unquoted scalar.</p>

<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanStreamEnd() {#a94c2a82f35954e4d516c65d0105ec2d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanStreamEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate tokens needed to close out the stream.</p>

<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanStreamStart() {#a055f1903ad9d69514f9be6570f4a2293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanStreamStart ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Must be the first token generated.</p>

<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanTag() {#a23038a39c7e7c48cf3d8b270da494eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanTag ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan a tag of the form !stuff.</p>

<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanToNextToken() {#a67ba6d9601cc54ba644f60ac873744bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Scanner::scanToNextToken ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip whitespace and comments until the start of the next token.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### scanValue() {#a11e4d1b0dcacb0fac2cf9bce802a167f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::scanValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan an explicit : indicating a value.</p>

<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### skip() {#ad11ebb973a2ee46b5fde5aa1061546fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Scanner::skip (uint32_t Distance)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip <em>Distance</em> UTF-8 code units. Updates <em>Cur</em> and <em>Column</em>.</p>

<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### skip\_b\_break() {#ad47814db56f7bc825c1adaeb042e57a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator Scanner::skip_b_break (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip a single b-break[28] starting at Position.</p>


<p>A b-break is 0xD 0xA | 0xD | 0xA</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The code unit after the b-break, or Position if it's not a b-break.</p></dd>
</dl>


<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### skip\_nb\_char() {#ad9d41cf86d00f27ddbcd3725dc2cb252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator Scanner::skip_nb_char (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip a single nb-char[27] starting at Position.</p>


<p>A nb-char is 0x9 | [0x20-0x7E] | 0x85 | [0xA0-0xD7FF] | [0xE000-0xFEFE] | [0xFF00-0xFFFD] | [0x10000-0x10FFFF]</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The code unit after the nb-char, or Position if it's not an nb-char.</p></dd>
</dl>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### skip\_ns\_char() {#aa7e4fcbc7260d434466a43e5a230dd65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator Scanner::skip_ns_char (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip a single ns-char[34] starting at Position.</p>


<p>A ns-char is nb-char - s-white</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The code unit after the ns-char, or Position if it's not a ns-char.</p></dd>
</dl>


<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### skip\_s\_space() {#ac9d23b3ff8aff35d5582dbf450840da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator Scanner::skip_s_space (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip a single s-space[31] starting at Position.</p>


<p>An s-space is 0x20</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The code unit after the s-space, or Position if it's not a s-space.</p></dd>
</dl>


<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### skip\_s\_white() {#af773459cf8d562cca498097e9dcac974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator Scanner::skip_s_white (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip a single s-white[33] starting at Position.</p>


<p>A s-white is 0x20 | 0x9</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The code unit after the s-white, or Position if it's not a s-white.</p></dd>
</dl>


<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### skip\_while() {#a46985700e81f8c5af1b95ca80ca1a410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator Scanner::skip_while (SkipWhileFunc Func, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip minimal well-formed code unit subsequences until Func returns its input.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The code unit after the last minimal well-formed code unit subsequence that Func accepted.</p></dd>
</dl>


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### skipComment() {#a124dfda3bacd940f3c4022d852f01811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Scanner::skipComment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip a single-line comment when the comment starts at the current position of the scanner.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### unrollIndent() {#a88ec6c05717f313fc521050a81be7c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Scanner::unrollIndent (int ToColumn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unroll indentation in <em>Indents</em> back to <em>Col</em>.</p>


<p>Creates BlockEnd tokens if needed.</p>


<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Column {#a0a299dc30ebc42e765ef4eaf12e353d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::Scanner::Column</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current column number in Unicode code points.</p>

<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### Current {#a1c308b3af89a4eb128d361990506ab6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator llvm::yaml::Scanner::Current</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current position of the scanner.</p>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### EC {#a4b9dcbd7bd91062ffc564cf2e5a30a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code* llvm::yaml::Scanner::EC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### End {#a8542f381f5906a949c8d86f99b7dabae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator llvm::yaml::Scanner::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The end of the input (one past the last character).</p>

<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### Failed {#a9a1b043ba45198d363a07b528b92903e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::Scanner::Failed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if an error has occurred.</p>

<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### FlowLevel {#a4c70383b5e34aa33cdfe3e0a3d503d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::Scanner::FlowLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How deep we are in flow style containers. 0 Means at block level.</p>

<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### Indent {#a1abe827783eb489d9f01fa5b69ec2276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::yaml::Scanner::Indent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current YAML indentation level in spaces.</p>

<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### Indents {#add6fae4d2314dfc2d775c043288c7f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int, 4&gt; llvm::yaml::Scanner::Indents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indentation levels.</p>

<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### InputBuffer {#af43a72c3c27355908afd24174b5ea0ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBufferRef llvm::yaml::Scanner::InputBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The original input.</p>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### IsAdjacentValueAllowedInFlow {#ae42285fe15501ac90691aaf239806532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::Scanner::IsAdjacentValueAllowedInFlow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Can the next token be a value indicator even if it does not have a trailing space?</p>

<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### IsSimpleKeyAllowed {#af69ae8f54742f6800ab87f1fa795128b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::Scanner::IsSimpleKeyAllowed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Can the next token be the start of a simple key?</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### IsStartOfStream {#acfeedfd15ada95a61cfca3d52a6257d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::Scanner::IsStartOfStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Are we at the start of the stream?</p>

<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### Line {#a63c7690a48828885761d85d226207b4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::Scanner::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current line number.</p>

<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### ShowColors {#a12d8ddfb95a787acf0ff82a95b1c90e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::Scanner::ShowColors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Should colors be used when printing out the diagnostic messages?</p>

<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### SimpleKeys {#af01384842d66ef57c768d676501053da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SimpleKey, 4&gt; llvm::yaml::Scanner::SimpleKeys</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Potential simple keys.</p>

<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### SM {#ab085ea94efdac4ff2766cba8f8a28cdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr&amp; llvm::yaml::Scanner::SM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> used for diagnostics and buffer management.</p>

<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### TokenQueue {#ac897d9fa20cb8c75266aa76a11aa5164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenQueueT llvm::yaml::Scanner::TokenQueue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Queue of tokens.</p>


<p>This is required to queue up tokens while looking for the end of a simple key. And for cases where a single character can produce multiple tokens (e.g. BlockEnd).</p>


<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
