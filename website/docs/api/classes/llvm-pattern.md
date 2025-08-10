---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pattern
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Pattern` Class



## Declaration

<div class="doxyDeclaration">
class llvm::Pattern { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheck/FileCheckImpl.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AllowedOperand { <a href="#a66f908b43f1abb512fe86d06c38ce330">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca22b7cb255f175dc6918f3d2171834">Pattern</a> (Check::FileCheckType Ty, FileCheckPatternContext *Context, std::optional&lt; size_t &gt; Line=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695dab5368e4f50fb49e8849c144b5d3">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4c59c2efdda38066089fa98dd6134a">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae173fad50624dec05877e86be7b7e429">parsePattern</a> (StringRef PatternStr, StringRef Prefix, SourceMgr &amp;SM, const FileCheckRequest &amp;Req)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses the pattern in <span class="doxyComputerOutput">PatternStr</span> and initializes this <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> instance accordingly. <a href="#ae173fad50624dec05877e86be7b7e429">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/pattern/matchresult">MatchResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23cdde8b9bdd40fd4a93d3635ca77dc6">match</a> (StringRef Buffer, const SourceMgr &amp;SM) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Matches the pattern string against the input buffer <span class="doxyComputerOutput">Buffer</span>. <a href="#a23cdde8b9bdd40fd4a93d3635ca77dc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a4e8a88439506522a2a0f3850802d3f">printSubstitutions</a> (const SourceMgr &amp;SM, StringRef Buffer, SMRange MatchRange, FileCheckDiag::MatchType MatchTy, std::vector&lt; FileCheckDiag &gt; *Diags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prints the value of successful substitutions. <a href="#a3a4e8a88439506522a2a0f3850802d3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3331028c9eef66f4022ac3efa310af7d">printFuzzyMatch</a> (const SourceMgr &amp;SM, StringRef Buffer, std::vector&lt; FileCheckDiag &gt; *Diags) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403b8b5edaa8e13e36a81cf6c6ea43a5">hasVariable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f729b936911342abb6b606e0606cdc">printVariableDefs</a> (const SourceMgr &amp;SM, FileCheckDiag::MatchType MatchTy, std::vector&lt; FileCheckDiag &gt; *Diags) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">Check::FileCheckType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac112adffc4bcc18c146110a4c648b683">getCheckTy</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc8c2d9a0d0a8809940c9627857135ca">getCount</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8656ba59f7446d275fb24a26ed1234e1">AddRegExToRegEx</a> (StringRef RS, unsigned &amp;CurParen, SourceMgr &amp;SM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec79a1e3297409ba8ccbd546c6692ecc">AddBackrefToRegEx</a> (unsigned BackrefNum)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d257b67b3a8cc172b127a83f7dc9497">computeMatchDistance</a> (StringRef Buffer) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes an arbitrary estimate for the quality of matching this pattern at the start of <span class="doxyComputerOutput">Buffer</span>; a distance of zero should correspond to a perfect match. <a href="#a7d257b67b3a8cc172b127a83f7dc9497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b44d4483629dac9c74e91c90820521">PatternLoc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8274e7720d93acf9904b90005d67e377">FixedStr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A fixed string to match as the pattern or empty if this pattern requires a regex match. <a href="#a8274e7720d93acf9904b90005d67e377">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63cf4dbaca95beea07b39b1c9859be7f">RegExStr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A regex string to match as the pattern or empty if this pattern requires a fixed string to match. <a href="#a63cf4dbaca95beea07b39b1c9859be7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/substitution">Substitution</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff56304525c840e6174b955002dfac1f">Substitutions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Entries in this vector represent a substitution of a string variable or an expression in the RegExStr regex at match time. <a href="#aff56304525c840e6174b955002dfac1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc704521498407c55d187400bcfba6e">VariableDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps names of string variables defined in a pattern to the number of their parenthesis group in RegExStr capturing their last definition. <a href="#a8dc704521498407c55d187400bcfba6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; NumericVariableMatch &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd0167c30287e0d447043bd7d9f25cc">NumericVariableDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the number of the parenthesis group in RegExStr and pointer to the corresponding <a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> class instance of all numeric variable definitions. <a href="#acfd0167c30287e0d447043bd7d9f25cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ca0f2165075c5cc9b914a985c59181">Context</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to a class instance holding the global state shared by all patterns: <a href="#a92ca0f2165075c5cc9b914a985c59181">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">Check::FileCheckType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5f81ce94c4a9ae6f92b4d750fc447c">CheckTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72caffe6ede6d89a559dd833157ea5bd">LineNumber</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Line number for this CHECK pattern or std::nullopt if it is an implicit pattern. <a href="#a72caffe6ede6d89a559dd833157ea5bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a716c6ef466cab85e024e5154118b83ca">IgnoreCase</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ignore case while matching if set to true. <a href="#a716c6ef466cab85e024e5154118b83ca">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0710447b6816c22e98d213c789f30ca">isValidVarNameStart</a> (char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/pattern/variableproperties">VariableProperties</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21cf4e03d53e49c96bf3f26cafdf7e82">parseVariable</a> (StringRef &amp;Str, const SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses the string at the start of <span class="doxyComputerOutput">Str</span> for a variable name. <a href="#a21cf4e03d53e49c96bf3f26cafdf7e82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d176c2f7da2816d871ca9dbecd13b7e">parseNumericSubstitutionBlock</a> (StringRef Expr, std::optional&lt; NumericVariable * &gt; &amp;DefinedNumericVariable, bool IsLegacyLineExpr, std::optional&lt; size_t &gt; LineNumber, FileCheckPatternContext *Context, const SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses <span class="doxyComputerOutput">Expr</span> for a numeric substitution block at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None. <a href="#a7d176c2f7da2816d871ca9dbecd13b7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8022ee24be560fa6a1b83ba4f8878ba6">FindRegexVarEnd</a> (StringRef Str, SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the closing sequence of a regex variable usage or definition. <a href="#a8022ee24be560fa6a1b83ba4f8878ba6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c71e3cb43c704c48b90007ed8622d63">parseNumericVariableDefinition</a> (StringRef &amp;Expr, FileCheckPatternContext *Context, std::optional&lt; size_t &gt; LineNumber, ExpressionFormat ImplicitFormat, const SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses <span class="doxyComputerOutput">Expr</span> for the name of a numeric variable to be defined at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None. <a href="#a8c71e3cb43c704c48b90007ed8622d63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/numericvariableuse">NumericVariableUse</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29ea8cd6af5b2f6250d41c9d8e74004">parseNumericVariableUse</a> (StringRef Name, bool IsPseudo, std::optional&lt; size_t &gt; LineNumber, FileCheckPatternContext *Context, const SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses <span class="doxyComputerOutput">Name</span> as a (pseudo if <span class="doxyComputerOutput">IsPseudo</span> is true) numeric variable use at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None. <a href="#ac29ea8cd6af5b2f6250d41c9d8e74004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a380ed99e91e488eea79aab11d6343cfa">parseNumericOperand</a> (StringRef &amp;Expr, AllowedOperand AO, bool ConstraintParsed, std::optional&lt; size_t &gt; LineNumber, FileCheckPatternContext *Context, const SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses <span class="doxyComputerOutput">Expr</span> for use of a numeric operand at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None. <a href="#a380ed99e91e488eea79aab11d6343cfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8d9c4cfdb07e05d629156a84f94098">parseBinop</a> (StringRef Expr, StringRef &amp;RemainingExpr, std::unique_ptr&lt; ExpressionAST &gt; LeftOp, bool IsLegacyLineExpr, std::optional&lt; size_t &gt; LineNumber, FileCheckPatternContext *Context, const SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses and updates <span class="doxyComputerOutput">RemainingExpr</span> for a binary operation at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None. <a href="#aac8d9c4cfdb07e05d629156a84f94098">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f6d1ca14d1012b74a1a0a6f87d8ab1">parseParenExpr</a> (StringRef &amp;Expr, std::optional&lt; size_t &gt; LineNumber, FileCheckPatternContext *Context, const SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a parenthesized expression inside <span class="doxyComputerOutput">Expr</span> at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None. <a href="#a17f6d1ca14d1012b74a1a0a6f87d8ab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a3500d003443bb0561c4b38770d44a3">parseCallExpr</a> (StringRef &amp;Expr, StringRef FuncName, std::optional&lt; size_t &gt; LineNumber, FileCheckPatternContext *Context, const SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses <span class="doxyComputerOutput">Expr</span> for an argument list belonging to a call to function <span class="doxyComputerOutput">FuncName</span> at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None. <a href="#a4a3500d003443bb0561c4b38770d44a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AllowedOperand {#a66f908b43f1abb512fe86d06c38ce330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::Pattern::AllowedOperand </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">LineVar<a id="a66f908b43f1abb512fe86d06c38ce330a06246d2d0759469d1a9293b638f5b12d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LegacyLiteral<a id="a66f908b43f1abb512fe86d06c38ce330a51d29b58d058d936eae9ae149ea54314"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Any<a id="a66f908b43f1abb512fe86d06c38ce330aed36a1ef76a59ee3f15180e0441188ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Pattern() {#a8ca22b7cb255f175dc6918f3d2171834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Pattern::Pattern (<a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">Check::FileCheckType</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> * Context, std::optional&lt; size_t &gt; Line=std::nullopt)</td>
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



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCheckTy() {#ac112adffc4bcc18c146110a4c648b683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Check::FileCheckType llvm::Pattern::getCheckTy ()</td>
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



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a95a7a7f317661b984c86d196fa44dff9">llvm::FileCheck::checkInput</a>, <a href="#a3331028c9eef66f4022ac3efa310af7d">printFuzzyMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a> and <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5d394830d4143542278afee43f527b48">printNoMatch</a>.</p>

</div>
</div>

### getContext() {#a6b4c59c2efdda38066089fa98dd6134a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCheckPatternContext * llvm::Pattern::getContext ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the pointer to the global state for all patterns in this <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> instance.</p></dd>
</dl>


<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### getCount() {#abc8c2d9a0d0a8809940c9627857135ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::Pattern::getCount ()</td>
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



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a> and <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5d394830d4143542278afee43f527b48">printNoMatch</a>.</p>

</div>
</div>

### getLoc() {#a695dab5368e4f50fb49e8849c144b5d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::Pattern::getLoc ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the location in source code.</p></dd>
</dl>


<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Referenced by <a href="#a3331028c9eef66f4022ac3efa310af7d">printFuzzyMatch</a>, <a href="#a3a4e8a88439506522a2a0f3850802d3f">printSubstitutions</a> and <a href="#a91f729b936911342abb6b606e0606cdc">printVariableDefs</a>.</p>

</div>
</div>

### hasVariable() {#a403b8b5edaa8e13e36a81cf6c6ea43a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Pattern::hasVariable ()</td>
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



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### match() {#a23cdde8b9bdd40fd4a93d3635ca77dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pattern::MatchResult Pattern::match (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Matches the pattern string against the input buffer <span class="doxyComputerOutput">Buffer</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>either (1) an error resulting in no match or (2) a match possibly with an error encountered while processing the match.</p></dd>
</dl>


<p>The GlobalVariableTable <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> in the <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> class instance provides the current values of <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> string variables and is updated if this match defines new values. Likewise, the GlobalNumericVariableTable <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> in the same class provides the current values of <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> numeric variables and is updated if this match defines new numeric values.</p>


<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1077 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca80e33945f521f203f2a632bc0f2041e5">llvm::Check::CheckEmpty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaba2d525032487e7def52c8154b19e29c">llvm::Check::CheckEOF</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#abc37e42bcf44968ae55ddc8c69748150">llvm::StringRef::find_insensitive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>, <a href="/web-llvm/docs/api/classes/llvm/numericvariable/#a307e40ec1e902bd8fa29819520ff33a9">llvm::NumericVariable::getImplicitFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/substitution/#a4cb8271788f45323ee85e99c0621e189">llvm::Substitution::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/substitution/#ad78740e164cb18ead36b8353f45e829f">llvm::Substitution::getResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3285d0c2736154c3ea72dbecaa446eec">llvm::handleErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a1cc1c3ad43ad382ef8d864fe9c16e25ca5f9b72100ddf65c55baa3cd82e778c4b">llvm::Regex::IgnoreCase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/structs/llvm/pattern/match/#a026da53ebcf239c0c67deee806165d38">llvm::Pattern::Match::Len</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a23cdde8b9bdd40fd4a93d3635ca77dc6">match</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a1cc1c3ad43ad382ef8d864fe9c16e25ca58612c80b543a7e989edd919e009b25b">llvm::Regex::Newline</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/structs/llvm/pattern/match/#ac72cc457a7bb55b7ea1030ebbd600e72">llvm::Pattern::Match::Pos</a>, <a href="/web-llvm/docs/api/classes/llvm/numericvariable/#a2a13f0b809c580616bb241ffda9c31d6">llvm::NumericVariable::setValue</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3d6148db61bf742f0e6a2c6a0f43fd9">llvm::ifs::filterIFSSyms</a> and <a href="#a23cdde8b9bdd40fd4a93d3635ca77dc6">match</a>.</p>

</div>
</div>

### parsePattern() {#ae173fad50624dec05877e86be7b7e429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Pattern::parsePattern (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PatternStr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest">FileCheckRequest</a> &amp; Req)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses the pattern in <span class="doxyComputerOutput">PatternStr</span> and initializes this <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> instance accordingly.</p>


<p><span class="doxyComputerOutput">Prefix</span> provides which prefix is being matched, <span class="doxyComputerOutput">Req</span> describes the global options that influence the parsing such as whitespace canonicalization, <span class="doxyComputerOutput">SM</span> provides the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> used for error reports.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true in case of an error, false otherwise.</p></dd>
</dl>


<p>Declaration at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca80e33945f521f203f2a632bc0f2041e5">llvm::Check::CheckEmpty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca4f9655da5198915aff91bd25115d22fa">llvm::Check::CheckNot</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a83a294111af6d4412163b209725ca556">llvm::StringRef::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a2f9ca9cf19b3d8803cfb233c2cb32af4">llvm::Regex::escape</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a93b15a8c0022febbe39d17ab933737a8">llvm::StringRef::find_first_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#ae884000984dd09d1cfbb3628ea820ed2">llvm::FileCheckRequest::IgnoreCase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#aa028a0ee1d4971af329f05d81c9b2bfd">llvm::FileCheckRequest::MatchFullLines</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckrequest/#a568ab5f904650e1b022c8ec1d4c0fe06">llvm::FileCheckRequest::NoCanonicalizeWhiteSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="#a7d176c2f7da2816d871ca9dbecd13b7e">parseNumericSubstitutionBlock</a>, <a href="#a21cf4e03d53e49c96bf3f26cafdf7e82">parseVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9b52404a8d2877d3b32ebb5d1f5c72ff">llvm::StringRef::rtrim</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### printFuzzyMatch() {#a3331028c9eef66f4022ac3efa310af7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pattern::printFuzzyMatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1313 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="#ac112adffc4bcc18c146110a4c648b683">getCheckTy</a>, <a href="#a695dab5368e4f50fb49e8849c144b5d3">getLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0a6c8cff7a0ac871bde6a0e4e33a8e90d2">llvm::FileCheckDiag::MatchFuzzy</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#aa386d2cd704c6f1176a5aef1f0f178da">ProcessMatchResult</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smrange/#a95721f80bb5e9cfa8571695f8807881b">llvm::SMRange::Start</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5d394830d4143542278afee43f527b48">printNoMatch</a>.</p>

</div>
</div>

### printSubstitutions() {#a3a4e8a88439506522a2a0f3850802d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pattern::printSubstitutions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> MatchRange, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0">FileCheckDiag::MatchType</a> MatchTy, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prints the value of successful substitutions.</p>

<p>Declaration at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/substitution/#a255f149343d5a52972fcd99b782c2db6">llvm::Substitution::getFromString</a>, <a href="#a695dab5368e4f50fb49e8849c144b5d3">getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/substitution/#ad78740e164cb18ead36b8353f45e829f">llvm::Substitution::getResult</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a5ba2ece4b959bae02752c34b784ba087">llvm::raw_ostream::write_escaped</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a> and <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5d394830d4143542278afee43f527b48">printNoMatch</a>.</p>

</div>
</div>

### printVariableDefs() {#a91f729b936911342abb6b606e0606cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pattern::printVariableDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#ab33e9e639814daad35bb1a9dc84190c0">FileCheckDiag::MatchType</a> MatchTy, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag">FileCheckDiag</a> &gt; * Diags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="#a695dab5368e4f50fb49e8849c144b5d3">getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a5fb499d84f3af1286e8d508a760aa396">llvm::SourceMgr::PrintMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AddBackrefToRegEx() {#aec79a1e3297409ba8ccbd546c6692ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pattern::AddBackrefToRegEx (unsigned BackrefNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### AddRegExToRegEx() {#a8656ba59f7446d275fb24a26ed1234e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Pattern::AddRegExToRegEx (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RS, unsigned &amp; CurParen, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### computeMatchDistance() {#a7d257b67b3a8cc172b127a83f7dc9497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Pattern::computeMatchDistance (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes an arbitrary estimate for the quality of matching this pattern at the start of <span class="doxyComputerOutput">Buffer</span>; a distance of zero should correspond to a perfect match.</p>

<p>Declaration at line 732 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CheckTy {#a7a5f81ce94c4a9ae6f92b4d750fc447c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Check::FileCheckType llvm::Pattern::CheckTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### Context {#a92ca0f2165075c5cc9b914a985c59181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCheckPatternContext* llvm::Pattern::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to a class instance holding the global state shared by all patterns:</p>


<ul class="doxyList ">
<li>separate tables with the values of live string and numeric variables respectively at the start of any given CHECK line;</li>
<li>table holding whether a string variable has been defined at any given point during the parsing phase.</li>
</ul>

<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### FixedStr {#a8274e7720d93acf9904b90005d67e377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Pattern::FixedStr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A fixed string to match as the pattern or empty if this pattern requires a regex match.</p>

<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### IgnoreCase {#a716c6ef466cab85e024e5154118b83ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Pattern::IgnoreCase = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ignore case while matching if set to true.</p>

<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### LineNumber {#a72caffe6ede6d89a559dd833157ea5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;size_t&gt; llvm::Pattern::LineNumber</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Line number for this CHECK pattern or std::nullopt if it is an implicit pattern.</p>


<p>Used to determine whether a variable definition is made on an earlier line to the one with this CHECK.</p>


<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### NumericVariableDefs {#acfd0167c30287e0d447043bd7d9f25cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;NumericVariableMatch&gt; llvm::Pattern::NumericVariableDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the number of the parenthesis group in RegExStr and pointer to the corresponding <a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> class instance of all numeric variable definitions.</p>


<p>Used to set the matched value of all those variables.</p>


<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### PatternLoc {#ad0b44d4483629dac9c74e91c90820521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::Pattern::PatternLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### RegExStr {#a63cf4dbaca95beea07b39b1c9859be7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Pattern::RegExStr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A regex string to match as the pattern or empty if this pattern requires a fixed string to match.</p>

<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### Substitutions {#aff56304525c840e6174b955002dfac1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Substitution *&gt; llvm::Pattern::Substitutions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Entries in this vector represent a substitution of a string variable or an expression in the RegExStr regex at match time.</p>


<p>For example, in the case of a CHECK directive with the pattern "foo[[bar]]baz[[#N+1]]", RegExStr will contain "foobaz" and we'll get two entries in this vector that tells us to insert the value of string variable "bar" at offset 3 and the value of expression "N+1" at offset 6.</p>


<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### VariableDefs {#a8dc704521498407c55d187400bcfba6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;StringRef, unsigned&gt; llvm::Pattern::VariableDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps names of string variables defined in a pattern to the number of their parenthesis group in RegExStr capturing their last definition.</p>


<p>E.g. for the pattern "foo[[bar:.*]]baz([[bar]][[QUUX]][[bar:.*]])", RegExStr will be "foo(.*)baz(\1&lt;quux value&gt;(.*))" where &lt;quux value&gt; is the value captured for QUUX on the earlier line where it was defined, and VariableDefs will map "bar" to the third parenthesis group which captures the second definition of "bar".</p>


<p>Note: uses std::map rather than <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> to be able to get the key when iterating over values.</p>


<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isValidVarNameStart() {#aa0710447b6816c22e98d213c789f30ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Pattern::isValidVarNameStart (char C)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>whether <span class="doxyComputerOutput">C</span> is a valid first character for a variable name.</p></dd>
</dl>


<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a21cf4e03d53e49c96bf3f26cafdf7e82">parseVariable</a>.</p>

</div>
</div>

### parseNumericSubstitutionBlock() {#a7d176c2f7da2816d871ca9dbecd13b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Expression &gt; &gt; Pattern::parseNumericSubstitutionBlock (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Expr, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> * &gt; &amp; DefinedNumericVariable, bool IsLegacyLineExpr, std::optional&lt; size_t &gt; LineNumber, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> * Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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

<p>Parses <span class="doxyComputerOutput">Expr</span> for a numeric substitution block at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None.</p>


<p>Parameter <span class="doxyComputerOutput">IsLegacyLineExpr</span> indicates whether <span class="doxyComputerOutput">Expr</span> should be a legacy @LINE expression and <span class="doxyComputerOutput">Context</span> points to the class instance holding the live string and numeric variables.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a pointer to the class instance representing the expression whose value must be substitued, or an error holding a diagnostic against <span class="doxyComputerOutput">SM</span> if parsing fails. If substitution was successful, sets <span class="doxyComputerOutput">DefinedNumericVariable</span> to point to the class representing the numeric variable defined in this numeric substitution block, or std::nullopt if this block does not define any variable.</p></dd>
</dl>


<p>Declaration at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>, <a href="/web-llvm/docs/api/classes/llvm/errordiagnostic/#afd2d10db0e8822de9860636d612a13af">llvm::ErrorDiagnostic::get</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a8aa1badb3ecc62f86172f9f85928fb61a64aea1932b88d7985edd8a140425a3a3">llvm::ExpressionFormat::HexLower</a>, <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a8aa1badb3ecc62f86172f9f85928fb61a71c7fabc0d41ad9cf4ddf4857b98615b">llvm::ExpressionFormat::HexUpper</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8265efd805e4ce0c9d3c18e78194324c">llvm::StringRef::ltrim</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5618db29d0000023a813f4d00e3bf484">popFront</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9b52404a8d2877d3b32ebb5d1f5c72ff">llvm::StringRef::rtrim</a>, <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a8aa1badb3ecc62f86172f9f85928fb61a71fed0c3428bf1a2e19af257c4bac379">llvm::ExpressionFormat::Signed</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a56ec02135bf1d64543cc44379b40d59d">SpaceChars</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa28286a33491b5d9a936fb6ae853baee">llvm::StringRef::take_front</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ab9990397f97b40d5d8564e000d00174a">llvm::StringRef::trim</a> and <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a8aa1badb3ecc62f86172f9f85928fb61aa1a914735b205424ba6c40b85528d78a">llvm::ExpressionFormat::Unsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a> and <a href="#ae173fad50624dec05877e86be7b7e429">parsePattern</a>.</p>

</div>
</div>

### parseVariable() {#a21cf4e03d53e49c96bf3f26cafdf7e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Pattern::VariableProperties &gt; Pattern::parseVariable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Str, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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

<p>Parses the string at the start of <span class="doxyComputerOutput">Str</span> for a variable name.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/structs/llvm/pattern/variableproperties">VariableProperties</a> structure holding the variable name and whether it is the name of a pseudo variable, or an error holding a diagnostic against <span class="doxyComputerOutput">SM</span> if parsing fail. If parsing was successful, also strips <span class="doxyComputerOutput">Str</span> from the variable name.</p></dd>
</dl>


<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/errordiagnostic/#afd2d10db0e8822de9860636d612a13af">llvm::ErrorDiagnostic::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aa0710447b6816c22e98d213c789f30ca">isValidVarNameStart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a> and <a href="#ae173fad50624dec05877e86be7b7e429">parsePattern</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### FindRegexVarEnd() {#a8022ee24be560fa6a1b83ba4f8878ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Pattern::FindRegexVarEnd (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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

<p>Finds the closing sequence of a regex variable usage or definition.</p>


<p><span class="doxyComputerOutput">Str</span> has to point in the beginning of the definition (right after the opening sequence). <span class="doxyComputerOutput">SM</span> holds the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> used for error reporting.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the offset of the closing sequence within Str, or npos if it was not found.</p></dd>
</dl>


<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1390 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### parseBinop() {#aac8d9c4cfdb07e05d629156a84f94098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ExpressionAST &gt; &gt; Pattern::parseBinop (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Expr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; RemainingExpr, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a> &gt; LeftOp, bool IsLegacyLineExpr, std::optional&lt; size_t &gt; LineNumber, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> * Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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

<p>Parses and updates <span class="doxyComputerOutput">RemainingExpr</span> for a binary operation at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None.</p>


<p>The left operand of this binary operation is given in <span class="doxyComputerOutput">LeftOp</span> and <span class="doxyComputerOutput">Expr</span> holds the string for the full expression, including the left operand. Parameter <span class="doxyComputerOutput">IsLegacyLineExpr</span> indicates whether we are parsing a legacy @LINE expression. Parameter <span class="doxyComputerOutput">Context</span> points to the class instance holding the live string and numeric variables.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the class representing the binary operation in the AST of the expression, or an error holding a diagnostic against <span class="doxyComputerOutput">SM</span> otherwise.</p></dd>
</dl>


<p>Declaration at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### parseCallExpr() {#a4a3500d003443bb0561c4b38770d44a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ExpressionAST &gt; &gt; Pattern::parseCallExpr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Expr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, std::optional&lt; size_t &gt; LineNumber, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> * Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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

<p>Parses <span class="doxyComputerOutput">Expr</span> for an argument list belonging to a call to function <span class="doxyComputerOutput">FuncName</span> at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None.</p>


<p>Parameter <span class="doxyComputerOutput">FuncLoc</span> is the source location used for diagnostics. Parameter <span class="doxyComputerOutput">Context</span> points to the class instance holding the live string and numeric variables.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the class representing that call in the AST of the expression or an error holding a diagnostic against <span class="doxyComputerOutput">SM</span> otherwise.</p></dd>
</dl>


<p>Declaration at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### parseNumericOperand() {#a380ed99e91e488eea79aab11d6343cfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ExpressionAST &gt; &gt; Pattern::parseNumericOperand (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Expr, AllowedOperand AO, bool ConstraintParsed, std::optional&lt; size_t &gt; LineNumber, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> * Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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

<p>Parses <span class="doxyComputerOutput">Expr</span> for use of a numeric operand at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None.</p>


<p>Accepts literal values, numeric variables and function calls, depending on the value of <span class="doxyComputerOutput">AO</span>. <span class="doxyComputerOutput">MaybeInvalidConstraint</span> indicates whether the text being parsed could be an invalid constraint. <span class="doxyComputerOutput">Context</span> points to the class instance holding the live string and numeric variables.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the class representing that operand in the AST of the expression or an error holding a diagnostic against <span class="doxyComputerOutput">SM</span> otherwise. If <span class="doxyComputerOutput">Expr</span> starts with a "(" this function will attempt to parse a parenthesized expression.</p></dd>
</dl>


<p>Declaration at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### parseNumericVariableDefinition() {#a8c71e3cb43c704c48b90007ed8622d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; NumericVariable * &gt; Pattern::parseNumericVariableDefinition (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Expr, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> * Context, std::optional&lt; size_t &gt; LineNumber, <a href="/web-llvm/docs/api/structs/llvm/expressionformat">ExpressionFormat</a> ImplicitFormat, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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

<p>Parses <span class="doxyComputerOutput">Expr</span> for the name of a numeric variable to be defined at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a pointer to the class instance representing that variable, creating it if needed, or an error holding a diagnostic against <span class="doxyComputerOutput">SM</span> should defining such a variable be invalid.</p></dd>
</dl>


<p>Declaration at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### parseNumericVariableUse() {#ac29ea8cd6af5b2f6250d41c9d8e74004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; NumericVariableUse &gt; &gt; Pattern::parseNumericVariableUse (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool IsPseudo, std::optional&lt; size_t &gt; LineNumber, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> * Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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

<p>Parses <span class="doxyComputerOutput">Name</span> as a (pseudo if <span class="doxyComputerOutput">IsPseudo</span> is true) numeric variable use at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None.</p>


<p>Parameter <span class="doxyComputerOutput">Context</span> points to the class instance holding the live string and numeric variables.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the pointer to the class instance representing that variable if successful, or an error holding a diagnostic against <span class="doxyComputerOutput">SM</span> otherwise.</p></dd>
</dl>


<p>Declaration at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### parseParenExpr() {#a17f6d1ca14d1012b74a1a0a6f87d8ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ExpressionAST &gt; &gt; Pattern::parseParenExpr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Expr, std::optional&lt; size_t &gt; LineNumber, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext">FileCheckPatternContext</a> * Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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

<p>Parses a parenthesized expression inside <span class="doxyComputerOutput">Expr</span> at line <span class="doxyComputerOutput">LineNumber</span>, or before input is parsed if <span class="doxyComputerOutput">LineNumber</span> is None.</p>


<p><span class="doxyComputerOutput">Expr</span> must start with a '('. Accepts both literal values and numeric variables. Parameter <span class="doxyComputerOutput">Context</span> points to the class instance holding the live string and numeric variables.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the class representing that operand in the AST of the expression or an error holding a diagnostic against <span class="doxyComputerOutput">SM</span> otherwise.</p></dd>
</dl>


<p>Declaration at line 795 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
