---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cl/subcommand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SubCommand` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::cl::SubCommand { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ccde6e696fc67347f3b0b41c8b598d3">SubCommand</a> (StringRef Name, StringRef Description="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a097cf28c3f8aac5fdf608ce40a4e73db">SubCommand</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec3f60533c02f25c929a5396e354eb4c">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b787c26145d642aae6f83d6a5a9135">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0573f9685ec31cc8ad70d8012f603881">getName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8cce7c38c8dabfb0f9e566350d61e12">getDescription</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe714a766051424993c5909def2d3e8">registerSubCommand</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a500bcef097029745e7391cadc1c7a87b">unregisterSubCommand</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade889ec01b2473e079cc890fdf8b52dd">PositionalOpts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc7d77ecd6cac278e5ea613e751b9ca">SinkOpts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb5d9ee3f51b3b92d53e71a44bece099">OptionsMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb1a5fe3e6498c2517d70c5576ba51b">ConsumeAfterOpt</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02da86e3f69568a29d633e1adff59e6">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a442be1cd4390e2ee4f2282be165814b2">Description</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3faf2de70f129bd4fc2eeff949d81806">getTopLevel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b56989e390102900666b2aec0b3504">getAll</a> ()</td>
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


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SubCommand() {#a1ccde6e696fc67347f3b0b41c8b598d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::cl::SubCommand::SubCommand (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Description="")</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>


<p>Reference <a href="#acbe714a766051424993c5909def2d3e8">registerSubCommand</a>.</p>


<p>Referenced by <a href="#a76b56989e390102900666b2aec0b3504">getAll</a>, <a href="#a3faf2de70f129bd4fc2eeff949d81806">getTopLevel</a> and <a href="#a097cf28c3f8aac5fdf608ce40a4e73db">SubCommand</a>.</p>

</div>
</div>

### SubCommand() {#a097cf28c3f8aac5fdf608ce40a4e73db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::cl::SubCommand::SubCommand ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>


<p>Reference <a href="#a1ccde6e696fc67347f3b0b41c8b598d3">SubCommand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#aec3f60533c02f25c929a5396e354eb4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubCommand::operator bool ()</td>
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



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>, definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a391287ed187d72f0c6b3ebe84178bda9">GlobalParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDescription() {#af8cce7c38c8dabfb0f9e566350d61e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::cl::SubCommand::getDescription ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a>.</p>

</div>
</div>

### getName() {#a0573f9685ec31cc8ad70d8012f603881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::cl::SubCommand::getName ()</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a> and <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#aa094a47b69ddfc374ff59a112e6dc32a">anonymous{CommandLine.cpp}::CommandLineParser::registerSubCommand</a>.</p>

</div>
</div>

### reset() {#a87b787c26145d642aae6f83d6a5a9135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SubCommand::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>, definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#acdb1a5fe3e6498c2517d70c5576ba51b">ConsumeAfterOpt</a>, <a href="#aeb5d9ee3f51b3b92d53e71a44bece099">OptionsMap</a>, <a href="#ade889ec01b2473e079cc890fdf8b52dd">PositionalOpts</a> and <a href="#a1fc7d77ecd6cac278e5ea613e751b9ca">SinkOpts</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ac615ebedc16556276f615ea06109f9b4">anonymous{CommandLine.cpp}::CommandLineParser::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### registerSubCommand() {#acbe714a766051424993c5909def2d3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SubCommand::registerSubCommand ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a391287ed187d72f0c6b3ebe84178bda9">GlobalParser</a>.</p>


<p>Referenced by <a href="#a1ccde6e696fc67347f3b0b41c8b598d3">SubCommand</a>.</p>

</div>
</div>

### unregisterSubCommand() {#a500bcef097029745e7391cadc1c7a87b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SubCommand::unregisterSubCommand ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>, definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a391287ed187d72f0c6b3ebe84178bda9">GlobalParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ConsumeAfterOpt {#acdb1a5fe3e6498c2517d70c5576ba51b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Option* llvm::cl::SubCommand::ConsumeAfterOpt = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#abd610bc0b0d15cdc72ab8d32205bf2a4">anonymous{CommandLine.cpp}::CommandLineParser::hasOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ab28699e21ef7b0aa06794bee56959a32">anonymous{CommandLine.cpp}::CommandLineParser::removeOption</a> and <a href="#a87b787c26145d642aae6f83d6a5a9135">reset</a>.</p>

</div>
</div>

### OptionsMap {#aeb5d9ee3f51b3b92d53e71a44bece099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;Option *&gt; llvm::cl::SubCommand::OptionsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a6d52a42303dabd7949d77a3da9d1ee6a">llvm::cl::getRegisteredOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#abd610bc0b0d15cdc72ab8d32205bf2a4">anonymous{CommandLine.cpp}::CommandLineParser::hasOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a22aba70ff931d97f2ae7de13b16c54fa">llvm::cl::HideUnrelatedOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aeb4508557302c61518095f4325c8b80b">llvm::cl::HideUnrelatedOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ab28699e21ef7b0aa06794bee56959a32">anonymous{CommandLine.cpp}::CommandLineParser::removeOption</a>, <a href="#a87b787c26145d642aae6f83d6a5a9135">reset</a> and <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#abf94691c7b08e508a00a3c2ed1d77003">anonymous{CommandLine.cpp}::CommandLineParser::updateArgStr</a>.</p>

</div>
</div>

### PositionalOpts {#ade889ec01b2473e079cc890fdf8b52dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Option *, 4&gt; llvm::cl::SubCommand::PositionalOpts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#abd610bc0b0d15cdc72ab8d32205bf2a4">anonymous{CommandLine.cpp}::CommandLineParser::hasOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ab28699e21ef7b0aa06794bee56959a32">anonymous{CommandLine.cpp}::CommandLineParser::removeOption</a> and <a href="#a87b787c26145d642aae6f83d6a5a9135">reset</a>.</p>

</div>
</div>

### SinkOpts {#a1fc7d77ecd6cac278e5ea613e751b9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Option *, 4&gt; llvm::cl::SubCommand::SinkOpts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ab28699e21ef7b0aa06794bee56959a32">anonymous{CommandLine.cpp}::CommandLineParser::removeOption</a> and <a href="#a87b787c26145d642aae6f83d6a5a9135">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Description {#a442be1cd4390e2ee4f2282be165814b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::cl::SubCommand::Description</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>

</div>
</div>

### Name {#af02da86e3f69568a29d633e1adff59e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::cl::SubCommand::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getAll() {#a76b56989e390102900666b2aec0b3504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubCommand &amp; SubCommand::getAll ()</td>
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



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a210deb1402e4e9a128d05dd20ffee841">AllSubCommands</a> and <a href="#a1ccde6e696fc67347f3b0b41c8b598d3">SubCommand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a1fcebda716de8f7953afb2d71049e205">anonymous{CommandLine.cpp}::CommandLineParser::forEachSubCommand</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#aa094a47b69ddfc374ff59a112e6dc32a">anonymous{CommandLine.cpp}::CommandLineParser::registerSubCommand</a> and <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ac615ebedc16556276f615ea06109f9b4">anonymous{CommandLine.cpp}::CommandLineParser::reset</a>.</p>

</div>
</div>

### getTopLevel() {#a3faf2de70f129bd4fc2eeff949d81806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubCommand &amp; SubCommand::getTopLevel ()</td>
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



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a>, definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a1ccde6e696fc67347f3b0b41c8b598d3">SubCommand</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#ab2f76f2b92b75733ac63b96c4e56202c">TopLevelSubCommand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#aaf7734e332f693209e45dccad133ffba">anonymous{CommandLine.cpp}::CommandLineParser::CommandLineParser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a3a60629142da060688204fabc5b05469">llvm::cl::expandResponseFiles</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a1fcebda716de8f7953afb2d71049e205">anonymous{CommandLine.cpp}::CommandLineParser::forEachSubCommand</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a> and <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ac615ebedc16556276f615ea06109f9b4">anonymous{CommandLine.cpp}::CommandLineParser::reset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">CommandLine.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
