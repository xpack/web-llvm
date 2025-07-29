---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regex
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Regex` Class



## Declaration

<div class="doxyDeclaration">
class llvm::Regex { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">llvm/Support/Regex.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RegexFlags : unsigned { <a href="#a1cc1c3ad43ad382ef8d864fe9c16e25c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac844880235ca7d00251aca1cc406c45">Regex</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80318325208303662f9f20af3a28b1d7">Regex</a> (StringRef Regex, RegexFlags Flags=NoFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compiles the given regular expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a></span>. <a href="#a80318325208303662f9f20af3a28b1d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79cfea7f92fa267424ad0466eff0fe4c">Regex</a> (StringRef Regex, unsigned Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15b84e06bac43b7de4e3277c37da0136">Regex</a> (const Regex &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c76bd33fa9d47ce2ed57c301e0c919">Regex</a> (Regex &amp;&amp;regex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b32acda8c0843ee5a68ebccba4ad993">~Regex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f2e58ac16f0e4fd48eae5fa118a7201">operator=</a> (Regex regex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ec0a13edce115b90710387e246519f">isValid</a> (std::string &amp;Error) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isValid - returns the error encountered during regex compilation, if any. <a href="#ab0ec0a13edce115b90710387e246519f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d488b5389a26ae3684748722f98306a">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d348cc6c3aa2942d9ebeadef92863f">getNumMatches</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNumMatches - In a valid regex, return the number of parenthesized matches it contains. <a href="#ad5d348cc6c3aa2942d9ebeadef92863f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae787b71e8d775a2b662d04e913489d8d">match</a> (StringRef String, SmallVectorImpl&lt; StringRef &gt; *Matches=nullptr, std::string *Error=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>matches - Match the regex against a given <span class="doxyComputerOutput">String</span>. <a href="#ae787b71e8d775a2b662d04e913489d8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603517a82c194cc3daa912831dff244a">sub</a> (StringRef Repl, StringRef String, std::string *Error=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>sub - Return the result of replacing the first match of the regex in <span class="doxyComputerOutput">String</span> with the <span class="doxyComputerOutput">Repl</span> string. <a href="#a603517a82c194cc3daa912831dff244a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab15b33499a9fa00ca2e4eea4b940a210">preg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ddcdc7213ac21310d29024ffe43ea77">error</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa821cfa27ddeb5cc419a88fa79804b2">isLiteralERE</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this function returns true, ^Str$ is an extended regular expression that matches Str and only Str. <a href="#aaa821cfa27ddeb5cc419a88fa79804b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9ca9cf19b3d8803cfb233c2cb32af4">escape</a> (StringRef String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn String into a regex by escaping its special characters. <a href="#a2f9ca9cf19b3d8803cfb233c2cb32af4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### RegexFlags {#a1cc1c3ad43ad382ef8d864fe9c16e25c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Regex::RegexFlags : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoFlags<a id="a1cc1c3ad43ad382ef8d864fe9c16e25ca79b1bd6f86856fd29672454892153e85"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IgnoreCase<a id="a1cc1c3ad43ad382ef8d864fe9c16e25ca5f9b72100ddf65c55baa3cd82e778c4b"></a></td>
<td class="doxyEnumItemDescription">Compile for matching that ignores upper/lower case distinctions (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Newline<a id="a1cc1c3ad43ad382ef8d864fe9c16e25ca58612c80b543a7e989edd919e009b25b"></a></td>
<td class="doxyEnumItemDescription">Compile for newline-sensitive matching (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BasicRegex<a id="a1cc1c3ad43ad382ef8d864fe9c16e25cae62480697e924b5793194a07ac798df4"></a></td>
<td class="doxyEnumItemDescription">By default, the POSIX extended regular expression (ERE) syntax is assumed (= 4)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Regex() {#aac844880235ca7d00251aca1cc406c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Regex::Regex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad7e13616a54be821d6b686d8b2587401">REG_BADPAT</a>.</p>


<p>Referenced by <a href="#a4f2e58ac16f0e4fd48eae5fa118a7201">operator=</a>, <a href="#a15b84e06bac43b7de4e3277c37da0136">Regex</a>, <a href="#a79c76bd33fa9d47ce2ed57c301e0c919">Regex</a> and <a href="#a79cfea7f92fa267424ad0466eff0fe4c">Regex</a>.</p>

</div>
</div>

### Regex() {#a80318325208303662f9f20af3a28b1d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Regex::Regex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Regex, <a href="#a1cc1c3ad43ad382ef8d864fe9c16e25c">RegexFlags</a> Flags=<a href="#a1cc1c3ad43ad382ef8d864fe9c16e25ca79b1bd6f86856fd29672454892153e85">NoFlags</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compiles the given regular expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a></span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/regex"&gt;Regex&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- referenced string is no longer needed after this constructor does finish. Only its compiled form is kept stored.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>References <a href="#a1cc1c3ad43ad382ef8d864fe9c16e25cae62480697e924b5793194a07ac798df4">BasicRegex</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="#a1cc1c3ad43ad382ef8d864fe9c16e25ca5f9b72100ddf65c55baa3cd82e778c4b">IgnoreCase</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="#a1cc1c3ad43ad382ef8d864fe9c16e25ca58612c80b543a7e989edd919e009b25b">Newline</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5fc31e6da9b77e09ea62b4544ac4767f">REG_EXTENDED</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a0c3e7b1d5bc9c2d278a544fe9b61b67a">REG_ICASE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ab678ef3b27bf7de2fb82c79cb2cd9d8a">REG_NEWLINE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a95142205890c3ac8dc12e5850cb0e946">REG_PEND</a>.</p>

</div>
</div>

### Regex() {#a79cfea7f92fa267424ad0466eff0fe4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Regex::Regex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Regex, unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>Reference <a href="#aac844880235ca7d00251aca1cc406c45">Regex</a>.</p>

</div>
</div>

### Regex() {#a15b84e06bac43b7de4e3277c37da0136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Regex::Regex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a> &amp;)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>.</p>


<p>Reference <a href="#aac844880235ca7d00251aca1cc406c45">Regex</a>.</p>

</div>
</div>

### Regex() {#a79c76bd33fa9d47ce2ed57c301e0c919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Regex::Regex (<a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a> &amp;&amp; regex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad7e13616a54be821d6b686d8b2587401">REG_BADPAT</a> and <a href="#aac844880235ca7d00251aca1cc406c45">Regex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Regex() {#a4b32acda8c0843ee5a68ebccba4ad993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Regex::~Regex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5b067957e932003b295ff3a8bbffe882">llvm_regfree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a4f2e58ac16f0e4fd48eae5fa118a7201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Regex &amp; llvm::Regex::operator= (<a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a> regex)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>.</p>


<p>References <a href="#aac844880235ca7d00251aca1cc406c45">Regex</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNumMatches() {#ad5d348cc6c3aa2942d9ebeadef92863f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Regex::getNumMatches ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getNumMatches - In a valid regex, return the number of parenthesized matches it contains.</p>


<p>The number filled in by match will include this many entries plus one for the whole regex (as element 0).</p>


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>

</div>
</div>

### isValid() {#ab0ec0a13edce115b90710387e246519f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Regex::isValid (std::string &amp; Error)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isValid - returns the error encountered during regex compilation, if any.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/nameorpattern/#ae26aada54fc59058d00a148699902f50">llvm::objcopy::NameOrPattern::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9ec3732ab208437ca6ee8e13438bd0e8">llvm::MachO::createRegexFromGlob</a> and <a href="/web-llvm/docs/api/classes/llvm/specialcaselist/matcher/#aeddf3282ade6b3f5d5bd98297ae8300a">llvm::SpecialCaseList::Matcher::insert</a>.</p>

</div>
</div>

### isValid() {#a5d488b5389a26ae3684748722f98306a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Regex::isValid ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>.</p>


<p>Referenced by <a href="#ae787b71e8d775a2b662d04e913489d8d">match</a>.</p>

</div>
</div>

### match() {#ae787b71e8d775a2b662d04e913489d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Regex::match (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; * Matches=nullptr, std::string * Error=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>matches - Match the regex against a given <span class="doxyComputerOutput">String</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Matches</td>
<td class="doxyParamItemDescription"><p>- If given, on a successful match this will be filled in with references to the matched group expressions (inside <span class="doxyComputerOutput">String</span>), the first group is always the entire pattern.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/error"&gt;Error&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- If non-null, any errors in the matching will be recorded as a non-empty string. If there is no error, it will be an empty string.</p></td>
</tr>
</table>
</dd>
</dl>

<p>This returns true on a successful match.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="#a5d488b5389a26ae3684748722f98306a">isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a2e1b5bd9424a1d1082d4bd670b1a0be6">rc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a183aab34192b1bdc18a56e84759aa210">REG_NOMATCH</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a343ef97b721e94f5cb1a8d2e742132b1">REG_STARTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a61053e705b1b4e91859a6c2ed7a60b64">llvm::M68kInstrInfo::isPCRelRegisterOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/specialcaselist/matcher/#a95c112003d4b27780538553f72b0d7c0">llvm::SpecialCaseList::Matcher::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64sysreg/#aa3c0c0cf3eb5c07094ada472569bc196">llvm::AArch64SysReg::parseGenericRegister</a>, <a href="#a603517a82c194cc3daa912831dff244a">sub</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#ae1863db0091c416836ecbf151ea73c90">ValidatePrefixes</a>.</p>

</div>
</div>

### sub() {#a603517a82c194cc3daa912831dff244a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Regex::sub (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Repl, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String, std::string * Error=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>sub - Return the result of replacing the first match of the regex in <span class="doxyComputerOutput">String</span> with the <span class="doxyComputerOutput">Repl</span> string.</p>


<p>Backreferences like "\0" and "\g&lt;1&gt;" in the replacement string are replaced with the appropriate match substring.</p>


<p>Note that the replacement string has backslash escaping performed on it. Invalid backreferences are ignored (replaced by empty strings).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/error"&gt;Error&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>If non-null, any errors in the substitution (invalid backreferences, trailing backslashes) will be recorded as a non-empty string. If there is no error, it will be an empty string.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae851887270f35d2a2670a79b9833d45b">llvm::StringRef::find_first_not_of</a>, <a href="#ae787b71e8d775a2b662d04e913489d8d">match</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/patternrewritedescriptor/#a634757052a33e4bba359e83b8b33199a">anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; DT, ValueType, Get, Iterator &gt;::performOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### error {#a9ddcdc7213ac21310d29024ffe43ea77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::Regex::error</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>.</p>

</div>
</div>

### preg {#ab15b33499a9fa00ca2e4eea4b940a210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm_regex* llvm::Regex::preg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### escape() {#a2f9ca9cf19b3d8803cfb233c2cb32af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Regex::escape (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
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

<p>Turn String into a regex by escaping its special characters.</p>

<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp/#a5dfb80ef07f86b668f26998d4d444097">RegexMetachars</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stringsubstitution/#a5586c71b9d5f3470c0f260453969e5ca">llvm::StringSubstitution::getResult</a> and <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>.</p>

</div>
</div>

### isLiteralERE() {#aaa821cfa27ddeb5cc419a88fa79804b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Regex::isLiteralERE (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>If this function returns true, ^Str$ is an extended regular expression that matches Str and only Str.</p>

<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp/#a5dfb80ef07f86b668f26998d4d444097">RegexMetachars</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/regex-h">Regex.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/regex-cpp">Regex.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
