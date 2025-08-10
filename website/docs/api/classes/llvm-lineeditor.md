---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lineeditor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LineEditor` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LineEditor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">llvm/LineEditor/LineEditor.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850c7f0652c0d7273484a266093805dd">LineEditor</a> (StringRef ProgName, StringRef HistoryPath="", FILE *In=stdin, FILE *Out=stdout, FILE *Err=stderr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/lineeditor">LineEditor</a> object. <a href="#a850c7f0652c0d7273484a266093805dd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1ec5b901f227b48659f9b2360092b27">~LineEditor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b66a9787d9b423292d75fb5eedf082">readLine</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads a line. <a href="#ac1b66a9787d9b423292d75fb5eedf082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2b493477c839b5c9bac51b09db7610a">saveHistory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a638fd1b86995827b00f34fe47e4f385a">loadHistory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a001e6b9ba0f38e37645ab73117658e4d">setHistorySize</a> (int size)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac206d08836b1ecbc66b9bef758bbd5d3">setCompleter</a> (T Comp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the completer for this <a href="/web-llvm/docs/api/classes/llvm/lineeditor">LineEditor</a>. <a href="#ac206d08836b1ecbc66b9bef758bbd5d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af10d0940b86e6d4650dfe2c55c65f4bf">setListCompleter</a> (T Comp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the completer for this <a href="/web-llvm/docs/api/classes/llvm/lineeditor">LineEditor</a> to the given list completer. <a href="#af10d0940b86e6d4650dfe2c55c65f4bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lineeditor/completionaction">CompletionAction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c9715831437239c8b4aebeb3772ba7b">getCompletionAction</a> (StringRef Buffer, size_t Pos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the current completer to produce a <a href="/web-llvm/docs/api/structs/llvm/lineeditor/completionaction">CompletionAction</a> for the given completion request. <a href="#a2c9715831437239c8b4aebeb3772ba7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed1afe007404f4f8a7a5d2ee4c907862">getPrompt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f2e551d8bd00097a3a69837a6a9c86">setPrompt</a> (const std::string &amp;P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abafc9dce43cbbcf3b2b08001bb69afcb">Prompt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbedb3078dc39aa08f368814f72ed510">HistoryPath</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/lineeditor/internaldata">InternalData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df1fbc82e05831120604b07e7f27f43">Data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CompleterConcept &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7cf08d1fde7c90d605bda4394e5b4c2">Completer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cf24dc9e2a09abc839f199155753e53">getDefaultHistoryPath</a> (StringRef ProgName)</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LineEditor() {#a850c7f0652c0d7273484a266093805dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineEditor::LineEditor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ProgName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> HistoryPath="", FILE * In=stdin, FILE * Out=stdout, FILE * Err=stderr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/lineeditor">LineEditor</a> object.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ProgName</td>
<td class="doxyParamItemDescription"><p>The name of the current program. Used to form a default prompt.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HistoryPath</td>
<td class="doxyParamItemDescription"><p>Path to the file in which to store history data, if possible.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">In</td>
<td class="doxyParamItemDescription"><p>The input stream used by the editor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Out</td>
<td class="doxyParamItemDescription"><p>The output stream used by the editor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Err</td>
<td class="doxyParamItemDescription"><p>The error stream used by the editor.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp">LineEditor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp/#a5f0f341a627fd6d0eab706d597a5988c">DefaultHistorySize</a>, <a href="#a6cf24dc9e2a09abc839f199155753e53">getDefaultHistoryPath</a>, <a href="#a638fd1b86995827b00f34fe47e4f385a">loadHistory</a>, <a href="#a001e6b9ba0f38e37645ab73117658e4d">setHistorySize</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LineEditor() {#af1ec5b901f227b48659f9b2360092b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineEditor::~LineEditor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp">LineEditor.cpp</a>.</p>


<p>Reference <a href="#ac2b493477c839b5c9bac51b09db7610a">saveHistory</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCompletionAction() {#a2c9715831437239c8b4aebeb3772ba7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineEditor::CompletionAction LineEditor::getCompletionAction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, size_t Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the current completer to produce a <a href="/web-llvm/docs/api/structs/llvm/lineeditor/completionaction">CompletionAction</a> for the given completion request.</p>


<p>If the current completer is a list completer, this will return an AK_Insert <a href="/web-llvm/docs/api/structs/llvm/lineeditor/completionaction">CompletionAction</a> if each completion has a common prefix, or an AK_ShowCompletions <a href="/web-llvm/docs/api/structs/llvm/lineeditor/completionaction">CompletionAction</a> otherwise.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Buffer</td>
<td class="doxyParamItemDescription"><p>The string to complete</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Pos</td>
<td class="doxyParamItemDescription"><p>The zero-based cursor position in the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp">LineEditor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lineeditor/completionaction/#ac232b5a8e51db460ca00d6122f0db70ea44496236f3d5e0a77dc12f50d7d2d6cc">llvm::LineEditor::CompletionAction::AK_ShowCompletions</a> and <a href="/web-llvm/docs/api/structs/llvm/lineeditor/completionaction/#a5d8e514dd4b30f8f3d0a59b0f8b989b5">llvm::LineEditor::CompletionAction::Kind</a>.</p>

</div>
</div>

### getPrompt() {#aed1afe007404f4f8a7a5d2ee4c907862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::LineEditor::getPrompt ()</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>

</div>
</div>

### loadHistory() {#a638fd1b86995827b00f34fe47e4f385a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LineEditor::loadHistory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp">LineEditor.cpp</a>.</p>


<p>Referenced by <a href="#a850c7f0652c0d7273484a266093805dd">LineEditor</a>.</p>

</div>
</div>

### readLine() {#ac1b66a9787d9b423292d75fb5eedf082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; LineEditor::readLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reads a line.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The line, or std::optional&lt;std::string&gt;() on EOF.</p></dd>
</dl>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp">LineEditor.cpp</a>.</p>

</div>
</div>

### saveHistory() {#ac2b493477c839b5c9bac51b09db7610a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LineEditor::saveHistory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp">LineEditor.cpp</a>.</p>


<p>Referenced by <a href="#af1ec5b901f227b48659f9b2360092b27">~LineEditor</a>.</p>

</div>
</div>

### setCompleter() {#ac206d08836b1ecbc66b9bef758bbd5d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LineEditor::setCompleter (T Comp)</td>
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

<p>Set the completer for this <a href="/web-llvm/docs/api/classes/llvm/lineeditor">LineEditor</a>.</p>


<p>A completer is a function object which takes arguments of type <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> (the string to complete) and size_t (the zero-based cursor position in the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) and returns a <a href="/web-llvm/docs/api/structs/llvm/lineeditor/completionaction">CompletionAction</a>.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### setHistorySize() {#a001e6b9ba0f38e37645ab73117658e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LineEditor::setHistorySize (int size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp">LineEditor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="#a850c7f0652c0d7273484a266093805dd">LineEditor</a>.</p>

</div>
</div>

### setListCompleter() {#af10d0940b86e6d4650dfe2c55c65f4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LineEditor::setListCompleter (T Comp)</td>
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

<p>Set the completer for this <a href="/web-llvm/docs/api/classes/llvm/lineeditor">LineEditor</a> to the given list completer.</p>


<p>A list completer is a function object which takes arguments of type <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> (the string to complete) and size_t (the zero-based cursor position in the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) and returns a std::vector&lt;Completion&gt;.</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### setPrompt() {#a20f2e551d8bd00097a3a69837a6a9c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LineEditor::setPrompt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; P)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Completer {#ae7cf08d1fde7c90d605bda4394e5b4c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const CompleterConcept&gt; llvm::LineEditor::Completer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>

</div>
</div>

### Data {#a7df1fbc82e05831120604b07e7f27f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InternalData&gt; llvm::LineEditor::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>

</div>
</div>

### HistoryPath {#acbedb3078dc39aa08f368814f72ed510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LineEditor::HistoryPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>

</div>
</div>

### Prompt {#abafc9dce43cbbcf3b2b08001bb69afcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LineEditor::Prompt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDefaultHistoryPath() {#a6cf24dc9e2a09abc839f199155753e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LineEditor::getDefaultHistoryPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ProgName)</td>
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



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp">LineEditor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1286bcdea03c97a18eb1f41af524f3d3">llvm::sys::path::home_directory</a>.</p>


<p>Referenced by <a href="#a850c7f0652c0d7273484a266093805dd">LineEditor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/lineeditor/lineeditor-cpp">LineEditor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
