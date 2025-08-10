---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/globpattern
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GlobPattern` Class

<p>This class implements a glob pattern matcher similar to the one found in bash, but with some key differences. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GlobPattern { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/globpattern-h">llvm/Support/GlobPattern.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bcd47fe233f29521e2d33adc1bf45e0">match</a> (StringRef S) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e2e456cd7f0e9ff0fd5798719b4d6fe">isTrivialMatchAll</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4951ff28ba8a00df54bd471c3cadc1a3">Prefix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; SubGlobPattern, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac04cf62bbbacedc4d102f459897f4f7a">SubGlobs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globpattern">GlobPattern</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad853cb6a2e5807ae5006c0f5ba1e7b49">create</a> (StringRef Pat, std::optional&lt; size_t &gt; MaxSubPatterns={})</td>
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

<p>This class implements a glob pattern matcher similar to the one found in bash, but with some key differences.</p>


<p>Namely, that <span class="doxyComputerOutput">"*"</span> matches all characters and does not exclude path separators.</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">"?"</span> matches a single character.</li>
<li><span class="doxyComputerOutput">"*"</span> matches zero or more characters.</li>
<li><span class="doxyComputerOutput">"[&lt;chars&gt;]"</span> matches one character in the bracket. Character ranges, e.g., <span class="doxyComputerOutput">"[a-z]"</span>, and negative sets via <span class="doxyComputerOutput">"[^ab]"</span> or <span class="doxyComputerOutput">"[!ab]"</span> are also supported.</li>
<li><span class="doxyComputerOutput">"{&lt;glob&gt;,...}"</span> matches one of the globs in the list. Nested brace expansions are not supported. If <span class="doxyComputerOutput">MaxSubPatterns</span> is empty then brace expansions are not supported and characters <span class="doxyComputerOutput">"{,}"</span> are treated as literals.</li>
<li><span class="doxyComputerOutput">"\\" (a single backslash) escapes the next character so it is treated
  as a literal.

Some known edge cases are:
* \p "</span>]" is allowed as the first character in a character class, i.e.,
  \p "[]]" is valid and matches the literal \p "]".
* The empty character class, i.e., \p "[]", is invalid.
* Empty or singleton brace expansions, e.g., \p "{}", \p "{a}", are invalid.
* \p "}" and \p "," that are not inside a brace expansion are taken as
  literals, e.g., \p ",}" is valid but \p "{" is not.

For example, \p "*[/\\]foo.{c,cpp}" (with two backslashes) will match
(unix or windows) paths to all files named \p "foo.c" or \p "foo.cpp".</li>
</ul>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/globpattern-h">GlobPattern.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### isTrivialMatchAll() {#a8e2e456cd7f0e9ff0fd5798719b4d6fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobPattern::isTrivialMatchAll ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/globpattern-h">GlobPattern.h</a>.</p>

</div>
</div>

### match() {#a7bcd47fe233f29521e2d33adc1bf45e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobPattern::match (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">true</span> if <span class="doxyComputerOutput">S</span> matches this glob pattern</p></dd>
</dl>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/globpattern-h">GlobPattern.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp">GlobPattern.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-internalize-cpp-/preserveapilist/#a369967c56c6438c8a3711f1dda61d9c0">anonymous{Internalize.cpp}::PreserveAPIList::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Prefix {#a4951ff28ba8a00df54bd471c3cadc1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::GlobPattern::Prefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/globpattern-h">GlobPattern.h</a>.</p>

</div>
</div>

### SubGlobs {#ac04cf62bbbacedc4d102f459897f4f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SubGlobPattern, 1&gt; llvm::GlobPattern::SubGlobs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/globpattern-h">GlobPattern.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#ad853cb6a2e5807ae5006c0f5ba1e7b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; GlobPattern &gt; GlobPattern::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pat, std::optional&lt; size_t &gt; MaxSubPatterns={})</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Pat</td>
<td class="doxyParamItemDescription"><p>the pattern to match against</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxSubPatterns</td>
<td class="doxyParamItemDescription"><p>if provided limit the number of allowed subpatterns created from expanding braces otherwise disable brace expansion</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/globpattern-h">GlobPattern.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp">GlobPattern.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a93b15a8c0022febbe39d17ab933737a8">llvm::StringRef::find_first_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a4f539d580f110fc7b26cd99ae4b09abe">parseBraceExpansions</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/nameorpattern/#ae26aada54fc59058d00a148699902f50">llvm::objcopy::NameOrPattern::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3d6148db61bf742f0e6a2c6a0f43fd9">llvm::ifs::filterIFSSyms</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/patternlist/#a61c5d0705d1f8b774e07fed8ab2add6e">anonymous{WholeProgramDevirt.cpp}::PatternList::init</a> and <a href="/web-llvm/docs/api/classes/llvm/specialcaselist/matcher/#aeddf3282ade6b3f5d5bd98297ae8300a">llvm::SpecialCaseList::Matcher::insert</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/globpattern-h">GlobPattern.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp">GlobPattern.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
