---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-commandline-cpp-/commandlineparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CommandLineParser` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{CommandLine.cpp}::CommandLineParser { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf7734e332f693209e45dccad133ffba">CommandLineParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed9675f845196eb805498480d36229f">ResetAllOptionOccurrences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset all options at least once, so that we can parse different options. <a href="#a8ed9675f845196eb805498480d36229f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff4dbfdf39c7f753e0258704d834879">ParseCommandLineOptions</a> (int argc, const char *const *argv, StringRef Overview, raw_ostream *Errs=nullptr, bool LongOptionsUseDoubleDash=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fcebda716de8f7953afb2d71049e205">forEachSubCommand</a> (Option &amp;Opt, function_ref&lt; void(SubCommand &amp;)&gt; Action)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60309e6fcb8d94bc5b62a03b4325645b">addLiteralOption</a> (Option &amp;Opt, SubCommand *SC, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad68a75d9205c0e19f3c5a39b0a55e180">addLiteralOption</a> (Option &amp;Opt, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f0804a7ab6d4b7a5ecbae2c628fdf7">addOption</a> (Option *O, SubCommand *SC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c5265c696a843db84b9f1b3ac53902">addOption</a> (Option *O, bool ProcessDefaultOption=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab28699e21ef7b0aa06794bee56959a32">removeOption</a> (Option *O, SubCommand *SC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38890649035c621bf6b12a8a0f2ff020">removeOption</a> (Option *O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd610bc0b0d15cdc72ab8d32205bf2a4">hasOptions</a> (const SubCommand &amp;Sub) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca3078bdaaf6b88a01f5dc2db56bc098">hasOptions</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad7464ca9688fab3603acd7c61e96fa">hasNamedSubCommands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e1bc80d79d0fc528a9c9971b672eda">getActiveSubCommand</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf94691c7b08e508a00a3c2ed1d77003">updateArgStr</a> (Option *O, StringRef NewName, SubCommand *SC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab579bdcee98dd531d062bdf95af5443b">updateArgStr</a> (Option *O, StringRef NewName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a936ffbef3dd147515d76ff3ad15ba22c">printOptionValues</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dd765680258b4790c6aa2472651f851">registerCategory</a> (OptionCategory *cat)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa094a47b69ddfc374ff59a112e6dc32a">registerSubCommand</a> (SubCommand *sub)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b59b9eaa08ea0a03e11e0bcc2f8bd3">unregisterSubCommand</a> (SubCommand *sub)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; typename <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> *, 4 &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e0b298d91027a9b8e4e3c572f4c2021">getRegisteredSubcommands</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac615ebedc16556276f615ea06109f9b4">reset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba48bdb75d749e5db9f48ce00a9b7bbe">LookupOption</a> (SubCommand &amp;Sub, StringRef &amp;Arg, StringRef &amp;Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LookupOption - Lookup the option specified by the specified option on the command line. <a href="#aba48bdb75d749e5db9f48ce00a9b7bbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b95bc381823165cf5f3ce1475eaeb2e">LookupLongOption</a> (SubCommand &amp;Sub, StringRef &amp;Arg, StringRef &amp;Value, bool LongOptionsUseDoubleDash, bool HaveDoubleDash)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a5ce323c000fc3fc10e1920ea855336">LookupSubCommand</a> (StringRef Name, std::string &amp;NearestString)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecbc8776f53584443cc2f740be62452b">ProgramName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a5d31589d952e3fa42e13e3b4fc2fc">ProgramOverview</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a108d65b2d565b8b09d026a5b8d394a50">MoreHelp</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091648a1cd4cf084ddbbaa5a77dc6205">DefaultOptions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/optioncategory">OptionCategory</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7af9371b6c5694d39f19dadb5cd5d73">RegisteredOptionCategories</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae6da3624f3252e234290e88ba8739f">RegisteredSubCommands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c50306a189c65d98a85197e532b78b8">ActiveSubCommand</a> = nullptr</td>
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


<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CommandLineParser() {#aaf7734e332f693209e45dccad133ffba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CommandLine.cpp}::CommandLineParser::CommandLineParser ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a3faf2de70f129bd4fc2eeff949d81806">llvm::cl::SubCommand::getTopLevel</a> and <a href="#aa094a47b69ddfc374ff59a112e6dc32a">registerSubCommand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLiteralOption() {#a60309e6fcb8d94bc5b62a03b4325645b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::addLiteralOption (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> &amp; Opt, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * SC, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a92a906892bbe1daf247b22ba6d8d6f7a">llvm::cl::Option::hasArgStr</a>, <a href="#aecbc8776f53584443cc2f740be62452b">ProgramName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#ad68a75d9205c0e19f3c5a39b0a55e180">addLiteralOption</a> and <a href="#aa094a47b69ddfc374ff59a112e6dc32a">registerSubCommand</a>.</p>

</div>
</div>

### addLiteralOption() {#ad68a75d9205c0e19f3c5a39b0a55e180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::addLiteralOption (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> &amp; Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a60309e6fcb8d94bc5b62a03b4325645b">addLiteralOption</a> and <a href="#a1fcebda716de8f7953afb2d71049e205">forEachSubCommand</a>.</p>

</div>
</div>

### addOption() {#a19f0804a7ab6d4b7a5ecbae2c628fdf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::addOption (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * SC)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a492234b10e0c5918d72a3a15a6f0fa6ea5dfae4543d7900fab74a9b213df0d1d8">llvm::cl::ConsumeAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa38ff96248cd0dc3e25aea3f5baf710ca">llvm::cl::Positional</a>, <a href="#aecbc8776f53584443cc2f740be62452b">ProgramName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ac96f30ba8b117dbd380b88ab8a03732ba1e82b710efc2f25cc275e53b3833e6fa">llvm::cl::Sink</a>.</p>


<p>Referenced by <a href="#ac9c5265c696a843db84b9f1b3ac53902">addOption</a>, <a href="#a8ff4dbfdf39c7f753e0258704d834879">ParseCommandLineOptions</a> and <a href="#aa094a47b69ddfc374ff59a112e6dc32a">registerSubCommand</a>.</p>

</div>
</div>

### addOption() {#ac9c5265c696a843db84b9f1b3ac53902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::addOption (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O, bool ProcessDefaultOption=false)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a19f0804a7ab6d4b7a5ecbae2c628fdf7">addOption</a>, <a href="#a091648a1cd4cf084ddbbaa5a77dc6205">DefaultOptions</a> and <a href="#a1fcebda716de8f7953afb2d71049e205">forEachSubCommand</a>.</p>

</div>
</div>

### forEachSubCommand() {#a1fcebda716de8f7953afb2d71049e205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::forEachSubCommand (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> &amp; Opt, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> &amp;)&gt; Action)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a76b56989e390102900666b2aec0b3504">llvm::cl::SubCommand::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a3faf2de70f129bd4fc2eeff949d81806">llvm::cl::SubCommand::getTopLevel</a>, <a href="#a7ae6da3624f3252e234290e88ba8739f">RegisteredSubCommands</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a256acf8ef8ff67c9b07bde8e65c06913">llvm::cl::Option::Subs</a>.</p>


<p>Referenced by <a href="#ad68a75d9205c0e19f3c5a39b0a55e180">addLiteralOption</a>, <a href="#ac9c5265c696a843db84b9f1b3ac53902">addOption</a>, <a href="#a38890649035c621bf6b12a8a0f2ff020">removeOption</a> and <a href="#ab579bdcee98dd531d062bdf95af5443b">updateArgStr</a>.</p>

</div>
</div>

### getActiveSubCommand() {#af3e1bc80d79d0fc528a9c9971b672eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubCommand * anonymous{CommandLine.cpp}::CommandLineParser::getActiveSubCommand ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

### getRegisteredSubcommands() {#a3e0b298d91027a9b8e4e3c572f4c2021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; typename SmallPtrSet&lt; SubCommand *, 4 &gt;::iterator &gt; anonymous{CommandLine.cpp}::CommandLineParser::getRegisteredSubcommands ()</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a7ae6da3624f3252e234290e88ba8739f">RegisteredSubCommands</a>.</p>

</div>
</div>

### hasNamedSubCommands() {#a3ad7464ca9688fab3603acd7c61e96fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CommandLine.cpp}::CommandLineParser::hasNamedSubCommands ()</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="#a7ae6da3624f3252e234290e88ba8739f">RegisteredSubCommands</a>.</p>


<p>Referenced by <a href="#a8ff4dbfdf39c7f753e0258704d834879">ParseCommandLineOptions</a>.</p>

</div>
</div>

### hasOptions() {#abd610bc0b0d15cdc72ab8d32205bf2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CommandLine.cpp}::CommandLineParser::hasOptions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> &amp; Sub)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#acdb1a5fe3e6498c2517d70c5576ba51b">llvm::cl::SubCommand::ConsumeAfterOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#aeb5d9ee3f51b3b92d53e71a44bece099">llvm::cl::SubCommand::OptionsMap</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#ade889ec01b2473e079cc890fdf8b52dd">llvm::cl::SubCommand::PositionalOpts</a>.</p>


<p>Referenced by <a href="#aca3078bdaaf6b88a01f5dc2db56bc098">hasOptions</a> and <a href="#a8ff4dbfdf39c7f753e0258704d834879">ParseCommandLineOptions</a>.</p>

</div>
</div>

### hasOptions() {#aca3078bdaaf6b88a01f5dc2db56bc098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CommandLine.cpp}::CommandLineParser::hasOptions ()</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#abd610bc0b0d15cdc72ab8d32205bf2a4">hasOptions</a> and <a href="#a7ae6da3624f3252e234290e88ba8739f">RegisteredSubCommands</a>.</p>

</div>
</div>

### ParseCommandLineOptions() {#a8ff4dbfdf39c7f753e0258704d834879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CommandLineParser::ParseCommandLineOptions (int argc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * argv, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Overview, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * Errs=nullptr, bool LongOptionsUseDoubleDash=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a19f0804a7ab6d4b7a5ecbae2c628fdf7">addOption</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a29fc50efce4c1ac670e638f1049a9d9f">llvm::cl::Option::ArgStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#acdb1a5fe3e6498c2517d70c5576ba51b">llvm::cl::SubCommand::ConsumeAfterOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a091648a1cd4cf084ddbbaa5a77dc6205">DefaultOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#ae5338ad16d90987a4431af6701844f8e">EatsUnboundedNumberOfValues</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a8be5b89e05ade5c6e5a08c6351b9821a">llvm::cl::Option::error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a56457123d8727edb2035dd014f284a21">llvm::cl::Option::getFormattingFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#aaa1c8565b0bb78da114f0d7f628e9d79">llvm::cl::Option::getMiscFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a2dc75fafb68e7669e776e19da7857cdf">llvm::cl::Option::getNumOccurrences</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a5efd7899e465adb76e098c727f4f0831">llvm::cl::Option::getNumOccurrencesFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a3faf2de70f129bd4fc2eeff949d81806">llvm::cl::SubCommand::getTopLevel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a391287ed187d72f0c6b3ebe84178bda9">GlobalParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a21de2c5fb30965f2300f1e49f791c915">HandlePrefixedOrGroupedOption</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a92a906892bbe1daf247b22ba6d8d6f7a">llvm::cl::Option::hasArgStr</a>, <a href="#a3ad7464ca9688fab3603acd7c61e96fa">hasNamedSubCommands</a>, <a href="#abd610bc0b0d15cdc72ab8d32205bf2a4">hasOptions</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#ae015be66fae811e0fe4cc32ce868f373">LookupNearestOption</a>, <a href="#a108d65b2d565b8b09d026a5b8d394a50">MoreHelp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a492234b10e0c5918d72a3a15a6f0fa6eafa11e887576398ca8a5fd74979a5a4c6">llvm::cl::OneOrMore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a492234b10e0c5918d72a3a15a6f0fa6eaee3d7c816c2a04f9f49c4aa194ef25b0">llvm::cl::Optional</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#aeb5d9ee3f51b3b92d53e71a44bece099">llvm::cl::SubCommand::OptionsMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa38ff96248cd0dc3e25aea3f5baf710ca">llvm::cl::Positional</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ac96f30ba8b117dbd380b88ab8a03732baf5893a59f7ee527848937d65719ef4b2">llvm::cl::PositionalEatsArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#ade889ec01b2473e079cc890fdf8b52dd">llvm::cl::SubCommand::PositionalOpts</a>, <a href="#aecbc8776f53584443cc2f740be62452b">ProgramName</a>, <a href="#ac4a5d31589d952e3fa42e13e3b4fc2fc">ProgramOverview</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a80082128b2626dbac74c382b28062330">ProvideOption</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aba3d2a652f73ed425dbbea55f4e7208c">llvm::cl::ProvidePositionalOption</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a492234b10e0c5918d72a3a15a6f0fa6eafb49e6d343a4ce63c7048a222586cc9e">llvm::cl::Required</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a0be046f5ecc4c5eedd4dfe7b2310a87a">RequiresValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a1fc7d77ecd6cac278e5ea613e751b9ca">llvm::cl::SubCommand::SinkOpts</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aff28c3d477d3a7870ec643381f186ed4">llvm::cl::TokenizeGNUCommandLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a3b42fd69f84c0ceef44857e925613ee4">llvm::cl::TokenizeWindowsCommandLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a492234b10e0c5918d72a3a15a6f0fa6ea61d3cb794533763159788c493ad266d9">llvm::cl::ZeroOrMore</a>.</p>

</div>
</div>

### printOptionValues() {#a936ffbef3dd147515d76ff3ad15ba22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CommandLineParser::printOptionValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a8ac44c2bdda9ce0b3da929e15237389b">CommonOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#afa436b61ad2191b0937d9d9240c37013">sortOpts</a>.</p>

</div>
</div>

### registerCategory() {#a0dd765680258b4790c6aa2472651f851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::registerCategory (<a href="/web-llvm/docs/api/classes/llvm/cl/optioncategory">OptionCategory</a> * cat)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/optioncategory/#adb804bdac6a31186775bc384bd2f0d8a">llvm::cl::OptionCategory::getName</a> and <a href="#af7af9371b6c5694d39f19dadb5cd5d73">RegisteredOptionCategories</a>.</p>

</div>
</div>

### registerSubCommand() {#aa094a47b69ddfc374ff59a112e6dc32a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::registerSubCommand (<a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * sub)</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a60309e6fcb8d94bc5b62a03b4325645b">addLiteralOption</a>, <a href="#a19f0804a7ab6d4b7a5ecbae2c628fdf7">addOption</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a76b56989e390102900666b2aec0b3504">llvm::cl::SubCommand::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a0573f9685ec31cc8ad70d8012f603881">llvm::cl::SubCommand::getName</a> and <a href="#a7ae6da3624f3252e234290e88ba8739f">RegisteredSubCommands</a>.</p>


<p>Referenced by <a href="#aaf7734e332f693209e45dccad133ffba">CommandLineParser</a> and <a href="#ac615ebedc16556276f615ea06109f9b4">reset</a>.</p>

</div>
</div>

### removeOption() {#ab28699e21ef7b0aa06794bee56959a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::removeOption (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * SC)</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#acdb1a5fe3e6498c2517d70c5576ba51b">llvm::cl::SubCommand::ConsumeAfterOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#aeb5d9ee3f51b3b92d53e71a44bece099">llvm::cl::SubCommand::OptionsMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa38ff96248cd0dc3e25aea3f5baf710ca">llvm::cl::Positional</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#ade889ec01b2473e079cc890fdf8b52dd">llvm::cl::SubCommand::PositionalOpts</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ac96f30ba8b117dbd380b88ab8a03732ba1e82b710efc2f25cc275e53b3833e6fa">llvm::cl::Sink</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a1fc7d77ecd6cac278e5ea613e751b9ca">llvm::cl::SubCommand::SinkOpts</a>.</p>


<p>Referenced by <a href="#a38890649035c621bf6b12a8a0f2ff020">removeOption</a>.</p>

</div>
</div>

### removeOption() {#a38890649035c621bf6b12a8a0f2ff020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::removeOption (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O)</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a1fcebda716de8f7953afb2d71049e205">forEachSubCommand</a> and <a href="#ab28699e21ef7b0aa06794bee56959a32">removeOption</a>.</p>

</div>
</div>

### reset() {#ac615ebedc16556276f615ea06109f9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::reset ()</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a091648a1cd4cf084ddbbaa5a77dc6205">DefaultOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a76b56989e390102900666b2aec0b3504">llvm::cl::SubCommand::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a3faf2de70f129bd4fc2eeff949d81806">llvm::cl::SubCommand::getTopLevel</a>, <a href="#a108d65b2d565b8b09d026a5b8d394a50">MoreHelp</a>, <a href="#aecbc8776f53584443cc2f740be62452b">ProgramName</a>, <a href="#ac4a5d31589d952e3fa42e13e3b4fc2fc">ProgramOverview</a>, <a href="#af7af9371b6c5694d39f19dadb5cd5d73">RegisteredOptionCategories</a>, <a href="#a7ae6da3624f3252e234290e88ba8739f">RegisteredSubCommands</a>, <a href="#aa094a47b69ddfc374ff59a112e6dc32a">registerSubCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a87b787c26145d642aae6f83d6a5a9135">llvm::cl::SubCommand::reset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a5db1a221190b0a9136749cbea271082c">llvm::cl::ResetAllOptionOccurrences</a>.</p>

</div>
</div>

### ResetAllOptionOccurrences() {#a8ed9675f845196eb805498480d36229f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CommandLineParser::ResetAllOptionOccurrences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset all options at least once, so that we can parse different options.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="#a7ae6da3624f3252e234290e88ba8739f">RegisteredSubCommands</a>.</p>

</div>
</div>

### unregisterSubCommand() {#a00b59b9eaa08ea0a03e11e0bcc2f8bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::unregisterSubCommand (<a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * sub)</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="#a7ae6da3624f3252e234290e88ba8739f">RegisteredSubCommands</a>.</p>

</div>
</div>

### updateArgStr() {#abf94691c7b08e508a00a3c2ed1d77003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::updateArgStr (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NewName, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * SC)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#aeb5d9ee3f51b3b92d53e71a44bece099">llvm::cl::SubCommand::OptionsMap</a>, <a href="#aecbc8776f53584443cc2f740be62452b">ProgramName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#ab579bdcee98dd531d062bdf95af5443b">updateArgStr</a>.</p>

</div>
</div>

### updateArgStr() {#ab579bdcee98dd531d062bdf95af5443b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CommandLine.cpp}::CommandLineParser::updateArgStr (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NewName)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a1fcebda716de8f7953afb2d71049e205">forEachSubCommand</a> and <a href="#abf94691c7b08e508a00a3c2ed1d77003">updateArgStr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### LookupLongOption() {#a6b95bc381823165cf5f3ce1475eaeb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Option * anonymous{CommandLine.cpp}::CommandLineParser::LookupLongOption (<a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> &amp; Sub, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Arg, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Value, bool LongOptionsUseDoubleDash, bool HaveDoubleDash)</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

### LookupOption() {#aba48bdb75d749e5db9f48ce00a9b7bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Option * CommandLineParser::LookupOption (<a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> &amp; Sub, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Arg, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LookupOption - Lookup the option specified by the specified option on the command line.</p>


<p>If there is a value specified (after an equal sign) return that as well. This assumes that leading dashes have already been stripped.</p>


<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

### LookupSubCommand() {#a5a5ce323c000fc3fc10e1920ea855336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubCommand * CommandLineParser::LookupSubCommand (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, std::string &amp; NearestString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DefaultOptions {#a091648a1cd4cf084ddbbaa5a77dc6205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Option*, 4&gt; anonymous{CommandLine.cpp}::CommandLineParser::DefaultOptions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#ac9c5265c696a843db84b9f1b3ac53902">addOption</a>, <a href="#a8ff4dbfdf39c7f753e0258704d834879">ParseCommandLineOptions</a> and <a href="#ac615ebedc16556276f615ea06109f9b4">reset</a>.</p>

</div>
</div>

### MoreHelp {#a108d65b2d565b8b09d026a5b8d394a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StringRef&gt; anonymous{CommandLine.cpp}::CommandLineParser::MoreHelp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a8ff4dbfdf39c7f753e0258704d834879">ParseCommandLineOptions</a> and <a href="#ac615ebedc16556276f615ea06109f9b4">reset</a>.</p>

</div>
</div>

### ProgramName {#aecbc8776f53584443cc2f740be62452b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{CommandLine.cpp}::CommandLineParser::ProgramName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a60309e6fcb8d94bc5b62a03b4325645b">addLiteralOption</a>, <a href="#a19f0804a7ab6d4b7a5ecbae2c628fdf7">addOption</a>, <a href="#a8ff4dbfdf39c7f753e0258704d834879">ParseCommandLineOptions</a>, <a href="#ac615ebedc16556276f615ea06109f9b4">reset</a> and <a href="#abf94691c7b08e508a00a3c2ed1d77003">updateArgStr</a>.</p>

</div>
</div>

### ProgramOverview {#ac4a5d31589d952e3fa42e13e3b4fc2fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{CommandLine.cpp}::CommandLineParser::ProgramOverview</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a8ff4dbfdf39c7f753e0258704d834879">ParseCommandLineOptions</a> and <a href="#ac615ebedc16556276f615ea06109f9b4">reset</a>.</p>

</div>
</div>

### RegisteredOptionCategories {#af7af9371b6c5694d39f19dadb5cd5d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;OptionCategory *, 16&gt; anonymous{CommandLine.cpp}::CommandLineParser::RegisteredOptionCategories</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a0dd765680258b4790c6aa2472651f851">registerCategory</a> and <a href="#ac615ebedc16556276f615ea06109f9b4">reset</a>.</p>

</div>
</div>

### RegisteredSubCommands {#a7ae6da3624f3252e234290e88ba8739f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;SubCommand *, 4&gt; anonymous{CommandLine.cpp}::CommandLineParser::RegisteredSubCommands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a1fcebda716de8f7953afb2d71049e205">forEachSubCommand</a>, <a href="#a3e0b298d91027a9b8e4e3c572f4c2021">getRegisteredSubcommands</a>, <a href="#a3ad7464ca9688fab3603acd7c61e96fa">hasNamedSubCommands</a>, <a href="#aca3078bdaaf6b88a01f5dc2db56bc098">hasOptions</a>, <a href="#aa094a47b69ddfc374ff59a112e6dc32a">registerSubCommand</a>, <a href="#ac615ebedc16556276f615ea06109f9b4">reset</a>, <a href="#a8ed9675f845196eb805498480d36229f">ResetAllOptionOccurrences</a> and <a href="#a00b59b9eaa08ea0a03e11e0bcc2f8bd3">unregisterSubCommand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ActiveSubCommand {#a4c50306a189c65d98a85197e532b78b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubCommand* anonymous{CommandLine.cpp}::CommandLineParser::ActiveSubCommand = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
