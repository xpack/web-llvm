---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-commandline-cpp-/helpprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HelpPrinter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{CommandLine.cpp}::HelpPrinter { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/categorizedhelpprinter">CategorizedHelpPrinter</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * &gt;, 128 &gt; <a href="#a03c77bd2120dfb6572649319341d38f7">StrOptionPairVector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * &gt;, 128 &gt; <a href="#a839fc5a474344a27b89ee22f4a575b07">StrSubCommandPairVector</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ccf397b425e3b2b0cf54435ba6de9c">HelpPrinter</a> (bool showHidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999d76516bd2722a3748ef1f47988aa2">~HelpPrinter</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91d3a23357338c4df7eeea6f0fca9178">operator=</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1007dc3842414831c7641e4b5824e4a0">printHelp</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f5b0f29c0bc09d86c10acc086657c21">printOptions</a> (StrOptionPairVector &amp;Opts, size_t MaxArgLen)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3edd58dd488ae30a1cfa617a24168e">printSubCommands</a> (StrSubCommandPairVector &amp;Subs, size_t MaxSubLen)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a20dc4b7e987465da1bcb34f982665">ShowHidden</a></td>
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


<p>Definition at line 2306 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### StrOptionPairVector {#a03c77bd2120dfb6572649319341d38f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVector&lt;std::pair&lt;const char *, Option *&gt;, 128&gt; anonymous{CommandLine.cpp}::HelpPrinter::StrOptionPairVector</td>
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



<p>Definition at line 2310 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

### StrSubCommandPairVector {#a839fc5a474344a27b89ee22f4a575b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVector&lt;std::pair&lt;const char *, SubCommand *&gt;, 128&gt; anonymous{CommandLine.cpp}::HelpPrinter::StrSubCommandPairVector</td>
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



<p>Definition at line 2312 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HelpPrinter() {#a43ccf397b425e3b2b0cf54435ba6de9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CommandLine.cpp}::HelpPrinter::HelpPrinter (bool showHidden)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2331 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="#aa8a20dc4b7e987465da1bcb34f982665">ShowHidden</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/categorizedhelpprinter/#aa661198a483500b5ae435be0ef8d5389">anonymous{CommandLine.cpp}::CategorizedHelpPrinter::CategorizedHelpPrinter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~HelpPrinter() {#a999d76516bd2722a3748ef1f47988aa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{CommandLine.cpp}::HelpPrinter::~HelpPrinter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2332 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a91d3a23357338c4df7eeea6f0fca9178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::HelpPrinter::operator= (bool Value)</td>
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



<p>Definition at line 2335 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="#a1007dc3842414831c7641e4b5824e4a0">printHelp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printHelp() {#a1007dc3842414831c7641e4b5824e4a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::HelpPrinter::printHelp ()</td>
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



<p>Definition at line 2344 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a29fc50efce4c1ac670e638f1049a9d9f">llvm::cl::Option::ArgStr</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#acdb1a5fe3e6498c2517d70c5576ba51b">llvm::cl::SubCommand::ConsumeAfterOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#af8cce7c38c8dabfb0f9e566350d61e12">llvm::cl::SubCommand::getDescription</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a0573f9685ec31cc8ad70d8012f603881">llvm::cl::SubCommand::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a3faf2de70f129bd4fc2eeff949d81806">llvm::cl::SubCommand::getTopLevel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a391287ed187d72f0c6b3ebe84178bda9">GlobalParser</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a92a906892bbe1daf247b22ba6d8d6f7a">llvm::cl::Option::hasArgStr</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#afbbf21de1a4bcce74821735914bdedcf">llvm::cl::Option::HelpStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#aeb5d9ee3f51b3b92d53e71a44bece099">llvm::cl::SubCommand::OptionsMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#ade889ec01b2473e079cc890fdf8b52dd">llvm::cl::SubCommand::PositionalOpts</a>, <a href="#a2f5b0f29c0bc09d86c10acc086657c21">printOptions</a>, <a href="#a7f3edd58dd488ae30a1cfa617a24168e">printSubCommands</a>, <a href="#aa8a20dc4b7e987465da1bcb34f982665">ShowHidden</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#afa436b61ad2191b0937d9d9240c37013">sortOpts</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#aceec35695771c1b589aec748d34e9e4b">sortSubCommands</a>.</p>


<p>Referenced by <a href="#a91d3a23357338c4df7eeea6f0fca9178">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### printOptions() {#a2f5b0f29c0bc09d86c10acc086657c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{CommandLine.cpp}::HelpPrinter::printOptions (<a href="#a03c77bd2120dfb6572649319341d38f7">StrOptionPairVector</a> &amp; Opts, size_t MaxArgLen)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2314 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a1007dc3842414831c7641e4b5824e4a0">printHelp</a>.</p>

</div>
</div>

### printSubCommands() {#a7f3edd58dd488ae30a1cfa617a24168e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::HelpPrinter::printSubCommands (<a href="#a839fc5a474344a27b89ee22f4a575b07">StrSubCommandPairVector</a> &amp; Subs, size_t MaxSubLen)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2319 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>.</p>


<p>Referenced by <a href="#a1007dc3842414831c7641e4b5824e4a0">printHelp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ShowHidden {#aa8a20dc4b7e987465da1bcb34f982665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{CommandLine.cpp}::HelpPrinter::ShowHidden</td>
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



<p>Definition at line 2308 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a43ccf397b425e3b2b0cf54435ba6de9c">HelpPrinter</a> and <a href="#a1007dc3842414831c7641e4b5824e4a0">printHelp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
