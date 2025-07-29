---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/filecheckpatterncontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FileCheckPatternContext` Class

<p>Class holding the <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> global state, shared by all patterns: tables holding values of variables and whether they are defined or not at any given time in the matching process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FileCheckPatternContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheck/FileCheckImpl.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80446dbfe53d7e6af7d8f8a997d5a6c">Pattern</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e6d86d9107ad1af9fff63748f0161b5">getPatternVarValue</a> (StringRef VarName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7137a381bae270178ff79807b1d096d3">defineCmdlineVariables</a> (ArrayRef&lt; StringRef &gt; CmdlineDefines, SourceMgr &amp;SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defines string and numeric variables from definitions given on the command line, passed as a vector of [#]VAR=VAL strings in <span class="doxyComputerOutput">CmdlineDefines</span>. <a href="#a7137a381bae270178ff79807b1d096d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f53ad01f0965d1ab2c7acbbdee1c464">createLineVariable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create @LINE pseudo variable. <a href="#a7f53ad01f0965d1ab2c7acbbdee1c464">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75c8e4486e2725285e4f149cc025ef5">clearLocalVars</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Undefines local variables (variables whose name does not start with a '$' sign), i.e. <a href="#ad75c8e4486e2725285e4f149cc025ef5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Types&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afcf614b5fe22b5afa7a9f4846ce6e0c9">makeNumericVariable</a> (Types... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Makes a new numeric variable and registers it for destruction when the context is destroyed. <a href="#afcf614b5fe22b5afa7a9f4846ce6e0c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/substitution">Substitution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c48f8d17e8fb837101a29d8682cb725">makeStringSubstitution</a> (StringRef VarName, size_t InsertIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Makes a new string substitution and registers it for destruction when the context is destroyed. <a href="#a7c48f8d17e8fb837101a29d8682cb725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/substitution">Substitution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f3314d4017ac5e5e3d883a3bac5f98">makeNumericSubstitution</a> (StringRef ExpressionStr, std::unique_ptr&lt; Expression &gt; Expression, size_t InsertIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Makes a new numeric substitution and registers it for destruction when the context is destroyed. <a href="#a81f3314d4017ac5e5e3d883a3bac5f98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca6c885493d8ff07956599ea6e03d5b">GlobalVariableTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When matching a given pattern, this holds the value of all the string variables defined in previous patterns. <a href="#abca6c885493d8ff07956599ea6e03d5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2642f682c01156c2ebfffc6babcd937">DefinedVariableTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of all string variables defined so far. <a href="#ac2642f682c01156c2ebfffc6babcd937">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb6739e79457fbfd5aa5e35e69069da1">GlobalNumericVariableTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When matching a given pattern, this holds the pointers to the classes representing the numeric variables defined in previous patterns. <a href="#abb6739e79457fbfd5aa5e35e69069da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67b7981931cb3bea149a5cd1ac9fd088">LineVariable</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the class instance representing the @LINE pseudo variable for easily updating its value. <a href="#a67b7981931cb3bea149a5cd1ac9fd088">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c63bc0d590a460e345e6014c91db774">NumericVariables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector holding pointers to all parsed numeric variables. <a href="#a6c63bc0d590a460e345e6014c91db774">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b2eadf462fb486c69640bd98087e03">Expressions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector holding pointers to all parsed expressions. <a href="#a65b2eadf462fb486c69640bd98087e03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/substitution">Substitution</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad518b14df93964f562b661f4a1a031e4">Substitutions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector holding pointers to all substitutions. <a href="#ad518b14df93964f562b661f4a1a031e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class holding the <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> global state, shared by all patterns: tables holding values of variables and whether they are defined or not at any given time in the matching process.</p>

<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Pattern {#ac80446dbfe53d7e6af7d8f8a997d5a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a> and <a href="#ac80446dbfe53d7e6af7d8f8a997d5a6c">Pattern</a>.</p>


<p>Referenced by <a href="#ac80446dbfe53d7e6af7d8f8a997d5a6c">Pattern</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearLocalVars() {#ad75c8e4486e2725285e4f149cc025ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileCheckPatternContext::clearLocalVars ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Undefines local variables (variables whose name does not start with a '$' sign), i.e.</p>


<p>removes them from GlobalVariableTable and from GlobalNumericVariableTable and also clears the value of numeric variables.</p>


<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 2650 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### createLineVariable() {#a7f53ad01f0965d1ab2c7acbbdee1c464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileCheckPatternContext::createLineVariable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create @LINE pseudo variable.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is set when pattern are being matched.</p>


<p>Declaration at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1760 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a8aa1badb3ecc62f86172f9f85928fb61aa1a914735b205424ba6c40b85528d78a">llvm::ExpressionFormat::Unsigned</a>.</p>

</div>
</div>

### defineCmdlineVariables() {#a7137a381bae270178ff79807b1d096d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error FileCheckPatternContext::defineCmdlineVariables (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; CmdlineDefines, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Defines string and numeric variables from definitions given on the command line, passed as a vector of [#]VAR=VAL strings in <span class="doxyComputerOutput">CmdlineDefines</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error list containing diagnostics against <span class="doxyComputerOutput">SM</span> for all definition parsing failures, if any, or Success otherwise.</p></dd>
</dl>


<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 2512 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#afe70aa1105a855036bdeb6426cac27db">llvm::SourceMgr::AddNewSourceBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/expressionast/#a655a886757d7044f264994f7cd162684">llvm::ExpressionAST::eval</a>, <a href="/web-llvm/docs/api/classes/llvm/errordiagnostic/#afd2d10db0e8822de9860636d612a13af">llvm::ErrorDiagnostic::get</a>, <a href="/web-llvm/docs/api/classes/llvm/expression/#a5028400a021ac3b1af180f508dc67f3a">llvm::Expression::getAST</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a21cf4e03d53e49c96bf3f26cafdf7e82">llvm::Pattern::parseVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getPatternVarValue() {#a8e6d86d9107ad1af9fff63748f0161b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; FileCheckPatternContext::getPatternVarValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VarName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the value of string variable <span class="doxyComputerOutput">VarName</span> or an error if no such variable has been defined.</p></dd>
</dl>


<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1360 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### makeNumericSubstitution() {#a81f3314d4017ac5e5e3d883a3bac5f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Substitution * FileCheckPatternContext::makeNumericSubstitution (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExpressionStr, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a> &gt; Expression, size_t InsertIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Makes a new numeric substitution and registers it for destruction when the context is destroyed.</p>

<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1382 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### makeNumericVariable() {#afcf614b5fe22b5afa7a9f4846ce6e0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Types&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NumericVariable * FileCheckPatternContext::makeNumericVariable (Types... args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Makes a new numeric variable and registers it for destruction when the context is destroyed.</p>

<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1369 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

### makeStringSubstitution() {#a7c48f8d17e8fb837101a29d8682cb725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Substitution * FileCheckPatternContext::makeStringSubstitution (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VarName, size_t InsertIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Makes a new string substitution and registers it for destruction when the context is destroyed.</p>

<p>Declaration at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 1375 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DefinedVariableTable {#ac2642f682c01156c2ebfffc6babcd937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;bool&gt; llvm::FileCheckPatternContext::DefinedVariableTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of all string variables defined so far.</p>


<p>Used at parse time to detect a name conflict between a numeric variable and a string variable when the former is defined on a later line than the latter.</p>


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### Expressions {#a65b2eadf462fb486c69640bd98087e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;Expression&gt; &gt; llvm::FileCheckPatternContext::Expressions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector holding pointers to all parsed expressions.</p>


<p>Used to automatically free the expressions once they are guaranteed to no longer be used.</p>


<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### GlobalNumericVariableTable {#abb6739e79457fbfd5aa5e35e69069da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;NumericVariable *&gt; llvm::FileCheckPatternContext::GlobalNumericVariableTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When matching a given pattern, this holds the pointers to the classes representing the numeric variables defined in previous patterns.</p>


<p>When matching a pattern all definitions for that pattern are recorded in the NumericVariableDefs table in the <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> instance of that pattern.</p>


<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### GlobalVariableTable {#abca6c885493d8ff07956599ea6e03d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;StringRef&gt; llvm::FileCheckPatternContext::GlobalVariableTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When matching a given pattern, this holds the value of all the string variables defined in previous patterns.</p>


<p>In a pattern, only the last definition for a given variable is recorded in this table. Back-references are used for uses after any the other definition.</p>


<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### LineVariable {#a67b7981931cb3bea149a5cd1ac9fd088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NumericVariable* llvm::FileCheckPatternContext::LineVariable = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the class instance representing the @LINE pseudo variable for easily updating its value.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### NumericVariables {#a6c63bc0d590a460e345e6014c91db774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;NumericVariable&gt; &gt; llvm::FileCheckPatternContext::NumericVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector holding pointers to all parsed numeric variables.</p>


<p>Used to automatically free them once they are guaranteed to no longer be used.</p>


<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### Substitutions {#ad518b14df93964f562b661f4a1a031e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;Substitution&gt; &gt; llvm::FileCheckPatternContext::Substitutions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector holding pointers to all substitutions.</p>


<p>Used to automatically free them once they are guaranteed to no longer be used.</p>


<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
