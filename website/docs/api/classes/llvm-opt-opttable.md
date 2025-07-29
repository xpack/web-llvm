---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/opt/opttable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OptTable` Class

<p>Provide access to the <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> info table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::opt::OptTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">llvm/Option/OptTable.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/genericopttable">GenericOptTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialization of <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a>. <a href="/web-llvm/docs/api/classes/llvm/opt/genericopttable/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/precomputedopttable">PrecomputedOptTable</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c39b3831711b590024c338280aca72">OptTable</a> (const StringTable &amp;StrTable, ArrayRef&lt; StringTable::Offset &gt; PrefixesTable, ArrayRef&lt; Info &gt; OptionInfos, bool IgnoreCase=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> using Tablegen'ed OptionInfos. <a href="#a25c39b3831711b590024c338280aca72">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742b6167a3a5c0e8d5c28510bffcaa6b">~OptTable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringtable">StringTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d94127cb03aeac6867d147ff2ec2da">getStrTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the string table used for option names. <a href="#af0d94127cb03aeac6867d147ff2ec2da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringtable/offset">StringTable::Offset</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc863453abb95d4e2094b5bd1b671b7d">getPrefixesTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the prefixes table used for option names. <a href="#abc863453abb95d4e2094b5bd1b671b7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf26248c40fce6fe688d619686698f93">getNumOptions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the total number of option classes. <a href="#adf26248c40fce6fe688d619686698f93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fad5655e536707e9af3286417f2e3c6">getOption</a> (OptSpecifier Opt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the given Opt's <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> instance, lazily creating it if necessary. <a href="#a2fad5655e536707e9af3286417f2e3c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d7fc5898d931b9576f991e5069c3953">getOptionName</a> (OptSpecifier id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup the name of the given option. <a href="#a0d7fc5898d931b9576f991e5069c3953">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403d67b8ae68de27b868e352b9d213d3">getOptionPrefix</a> (OptSpecifier id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup the prefix of the given option. <a href="#a403d67b8ae68de27b868e352b9d213d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2670409179c8ee6ea9a21f4f57f3eb3">appendOptionPrefixes</a> (OptSpecifier id, SmallVectorImpl&lt; StringRef &gt; &amp;Prefixes) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba23caa0f0c4bb6ab71df6cdae32d5d5">getOptionPrefixedName</a> (OptSpecifier id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup the prefixed name of the given option. <a href="#aba23caa0f0c4bb6ab71df6cdae32d5d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a144e7c564652619e7426764852dc17ba">getOptionKind</a> (OptSpecifier id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the kind of the given option. <a href="#a144e7c564652619e7426764852dc17ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aae5837deca80e30e622c3bb524859c">getOptionGroupID</a> (OptSpecifier id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the group id for the given option. <a href="#a9aae5837deca80e30e622c3bb524859c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34271f265cc461ddb0e8f3e0e1b45fa7">getOptionHelpText</a> (OptSpecifier id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the help text to use to describe this option. <a href="#a34271f265cc461ddb0e8f3e0e1b45fa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e705312a9e6fa8f248f0e2e8c3339d4">getOptionHelpText</a> (OptSpecifier id, Visibility VisibilityMask) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20488bdf75a8ad482e6fa40d38af6345">getOptionMetaVar</a> (OptSpecifier id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the meta-variable name to use when describing this options values in the help text. <a href="#a20488bdf75a8ad482e6fa40d38af6345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52af886cfdde9fcdd2eb8f38b1a38a32">setInitialOptionsFromEnvironment</a> (const char *E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify the environment variable where initial options should be read. <a href="#a52af886cfdde9fcdd2eb8f38b1a38a32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8bcfe99a666b88771c15356cc778be">setGroupedShortOptions</a> (bool Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support grouped short options. e.g. -ab represents -a -b. <a href="#aff8bcfe99a666b88771c15356cc778be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9e54d5c7b20ab2e63f88267aafc592">setDashDashParsing</a> (bool Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether "--" stops option parsing and treats all subsequent arguments as positional. <a href="#a6e9e54d5c7b20ab2e63f88267aafc592">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaddd5ed7dd146aad3e0c51691a90f22c">suggestValueCompletions</a> (StringRef Option, StringRef Arg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find possible value for given flags. <a href="#aaddd5ed7dd146aad3e0c51691a90f22c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb9a5bb7299045f334f16d82f244ad0">findByPrefix</a> (StringRef Cur, Visibility VisibilityMask, unsigned int DisableFlags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find flags from <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> which starts with Cur. <a href="#aebb9a5bb7299045f334f16d82f244ad0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc0c8204694490e197301b24eb6c140">findNearest</a> (StringRef Option, std::string &amp;NearestString, Visibility VisibilityMask=Visibility(), unsigned MinimumLength=4, unsigned MaximumDistance=UINT_MAX) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> option that most closely matches the given string. <a href="#a2bc0c8204694490e197301b24eb6c140">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8119253a15642e1fe80d26ae7f7360">findNearest</a> (StringRef Option, std::string &amp;NearestString, unsigned FlagsToInclude, unsigned FlagsToExclude=0, unsigned MinimumLength=4, unsigned MaximumDistance=UINT_MAX) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6361e7d3a469c8e290dbee6bfcd2b17">findExact</a> (StringRef Option, std::string &amp;ExactString, Visibility VisibilityMask=Visibility()) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ef7ad54c15ad0b5363e411f58251d5">findExact</a> (StringRef Option, std::string &amp;ExactString, unsigned FlagsToInclude, unsigned FlagsToExclude=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a209267a94d47fc715aedcb7c0b836d36">ParseOneArg</a> (const ArgList &amp;Args, unsigned &amp;Index, Visibility VisibilityMask=Visibility()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a single argument; returning the new argument and updating Index. <a href="#a209267a94d47fc715aedcb7c0b836d36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a534b852fce32e3f367c7d79668439fe0">ParseOneArg</a> (const ArgList &amp;Args, unsigned &amp;Index, unsigned FlagsToInclude, unsigned FlagsToExclude) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae1e1c17454fb6433f039b5fb02c5c4d">ParseArgs</a> (ArrayRef&lt; const char * &gt; Args, unsigned &amp;MissingArgIndex, unsigned &amp;MissingArgCount, Visibility VisibilityMask=Visibility()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an list of arguments into an <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a>. <a href="#aae1e1c17454fb6433f039b5fb02c5c4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac095b04e69b50cc16e488b2cebd8ecc6">ParseArgs</a> (ArrayRef&lt; const char * &gt; Args, unsigned &amp;MissingArgIndex, unsigned &amp;MissingArgCount, unsigned FlagsToInclude, unsigned FlagsToExclude=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0446fb27e6a1ab9f59c283d0960e86">parseArgs</a> (int Argc, char *const *Argv, OptSpecifier Unknown, StringSaver &amp;Saver, std::function&lt; void(StringRef)&gt; ErrorFn) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A convenience helper which handles optional initial options populated from an environment variable, expands response files recursively and parses options. <a href="#a0f0446fb27e6a1ab9f59c283d0960e86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef4e8b65e20fbddebc0a43c5b61eeb4">printHelp</a> (raw_ostream &amp;OS, const char *Usage, const char *Title, bool ShowHidden=false, bool ShowAllAliases=false, Visibility VisibilityMask=Visibility()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Render the help text for an option table. <a href="#a1ef4e8b65e20fbddebc0a43c5b61eeb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667472bdd201aa8c1db898f31085eae7">printHelp</a> (raw_ostream &amp;OS, const char *Usage, const char *Title, unsigned FlagsToInclude, unsigned FlagsToExclude, bool ShowAllAliases) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01fdf8f5ab053f70c4c67fd8361b60d5">buildPrefixChars</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build (or rebuild) the PrefixChars member. <a href="#a01fdf8f5ab053f70c4c67fd8361b60d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">Info</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a555478c5ebdbb4122c84ab649f2a8fe8">getInfo</a> (OptSpecifier Opt) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36e218fffeabc289767459c9c7fedf7">parseOneArgGrouped</a> (InputArgList &amp;Args, unsigned &amp;Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd4a071276f3827bd8ce11c2a3a852a4">internalFindNearest</a> (StringRef Option, std::string &amp;NearestString, unsigned MinimumLength, unsigned MaximumDistance, std::function&lt; bool(const Info &amp;)&gt; ExcludeOption) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec051d989dd3791dfe72eb41526f93b">internalParseOneArg</a> (const ArgList &amp;Args, unsigned &amp;Index, std::function&lt; bool(const Option &amp;)&gt; ExcludeOption) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c6c3568b13ab756e0f65e88e0b876e1">internalParseArgs</a> (ArrayRef&lt; const char * &gt; Args, unsigned &amp;MissingArgIndex, unsigned &amp;MissingArgCount, std::function&lt; bool(const Option &amp;)&gt; ExcludeOption) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c55c91cd74de600f989b6f9f1be41c9">internalPrintHelp</a> (raw_ostream &amp;OS, const char *Usage, const char *Title, bool ShowHidden, bool ShowAllAliases, std::function&lt; bool(const Info &amp;)&gt; ExcludeOption, Visibility VisibilityMask) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c70cba1015342a5a66a5bf0e110f95">FirstSearchableIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the first option which can be parsed (i.e., is not a special option like 'input' or 'unknown', and is not an option group). <a href="#a17c70cba1015342a5a66a5bf0e110f95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f70e420cd97fc15e415b7e4c16c6deb">PrefixesUnion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The union of all option prefixes. <a href="#a2f70e420cd97fc15e415b7e4c16c6deb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1dc3d5ce73817f28b8925a1cf6a659b">PrefixChars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The union of the first element of all option prefixes. <a href="#ac1dc3d5ce73817f28b8925a1cf6a659b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringtable">StringTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb70a2616b6fa8f40dedce48ecc9fbf9">StrTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringtable/offset">StringTable::Offset</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a82453a532d106c75499a299823d01">PrefixesTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">Info</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1444dfbdbabd8878c00c25469032187f">OptionInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The option information table. <a href="#a1444dfbdbabd8878c00c25469032187f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b4474db51ca5818ad5b8580adfa66f">IgnoreCase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a155c407d9d4a2bf8edfc0c6cb19145">GroupedShortOptions</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4697e66204c03ecb0a5fc4f8241b5107">DashDashParsing</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c04914f1661720d1cd8cfb2ceaaf93">EnvVar</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a600332e173fe59a9b2430bb03ffb8115">InputOptionID</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185980792e5402b6d2e25e42500022c9">UnknownOptionID</a> = 0</td>
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

<p>Provide access to the <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> info table.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> class provides a layer of indirection which allows <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> instance to be created lazily. In the common case, only a few options will be needed at runtime; the <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> class maintains enough information to parse command lines without instantiating Options, while letting other parts of the driver still use <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> instances where convenient.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### OptTable() {#a25c39b3831711b590024c338280aca72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptTable::OptTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringtable">StringTable</a> &amp; StrTable, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringtable/offset">StringTable::Offset</a> &gt; PrefixesTable, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">Info</a> &gt; OptionInfos, bool IgnoreCase=false)</td>
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

<p>Initialize <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> using Tablegen'ed OptionInfos.</p>


<p>Child class must manually call <span class="doxyComputerOutput">buildPrefixChars</span> once they are fully constructed.</p>


<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a07df67e096ac6736534eeb740165d530">llvm::opt::Option::dump</a>, <a href="#a17c70cba1015342a5a66a5bf0e110f95">FirstSearchableIndex</a>, <a href="#adf26248c40fce6fe688d619686698f93">getNumOptions</a>, <a href="#a2fad5655e536707e9af3286417f2e3c6">getOption</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba0f16fdf1d979a9ba138dc95d6717ceef">llvm::opt::Option::GroupClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba7024d387cb59117469f0c569582aa5f5">llvm::opt::Option::InputClass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba71db01a325850d1a7b626f06e71a6504">llvm::opt::Option::UnknownClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/genericopttable/#ac3179665bf593185b092d08113399ae8">llvm::opt::GenericOptTable::GenericOptTable</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/precomputedopttable/#a7305670bef5cd628b213e3a84d2222a1">llvm::opt::PrecomputedOptTable::PrecomputedOptTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~OptTable() {#a742b6167a3a5c0e8d5c28510bffcaa6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptTable::~OptTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appendOptionPrefixes() {#ac2670409179c8ee6ea9a21f4f57f3eb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::OptTable::appendOptionPrefixes (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> id, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Prefixes)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### findByPrefix() {#aebb9a5bb7299045f334f16d82f244ad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::string &gt; OptTable::findByPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Cur, <a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a> VisibilityMask, unsigned int DisableFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find flags from <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> which starts with Cur.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Cur</td>
<td class="doxyParamItemDescription"><p>- String prefix that all returned flags need</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The vector of flags which start with Cur.</p></dd>
</dl>


<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="#a17c70cba1015342a5a66a5bf0e110f95">FirstSearchableIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h/#a5336c02c81ff675028496f2f2409d30a">starts_with</a>.</p>

</div>
</div>

### findExact() {#ae6361e7d3a469c8e290dbee6bfcd2b17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::OptTable::findExact (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Option, std::string &amp; ExactString, <a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a> VisibilityMask=<a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a>())</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Reference <a href="#a2bc0c8204694490e197301b24eb6c140">findNearest</a>.</p>

</div>
</div>

### findExact() {#a47ef7ad54c15ad0b5363e411f58251d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::OptTable::findExact (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Option, std::string &amp; ExactString, unsigned FlagsToInclude, unsigned FlagsToExclude=0)</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Reference <a href="#a2bc0c8204694490e197301b24eb6c140">findNearest</a>.</p>

</div>
</div>

### findNearest() {#a2bc0c8204694490e197301b24eb6c140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned OptTable::findNearest (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Option, std::string &amp; NearestString, <a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a> VisibilityMask=<a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a>(), unsigned MinimumLength=4, unsigned MaximumDistance=UINT_MAX)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> option that most closely matches the given string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/opt/option"&gt;Option&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- A string, such as "-stdlibs=l", that represents user input of an option that may not exist in the <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a>. Note that the string includes prefix dashes "-" as well as values "=l".</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] NearestString</td>
<td class="doxyParamItemDescription"><p>- The nearest option string found in the <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] VisibilityMask</td>
<td class="doxyParamItemDescription"><p>- Only include options with any of these visibility flags set.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MinimumLength</td>
<td class="doxyParamItemDescription"><p>- Don't find options shorter than this length. For example, a minimum length of 3 prevents "-x" from being considered near to "-S".</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MaximumDistance</td>
<td class="doxyParamItemDescription"><p>- Don't find options whose distance is greater than this value.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The edit distance of the nearest string found.</p></dd>
</dl>


<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#a5fd493d1cc2d1c57e01f2881dcdd00f9">llvm::opt::OptTable::Info::Visibility</a>.</p>


<p>Referenced by <a href="#a47ef7ad54c15ad0b5363e411f58251d5">findExact</a>, <a href="#ae6361e7d3a469c8e290dbee6bfcd2b17">findExact</a> and <a href="#a0f0446fb27e6a1ab9f59c283d0960e86">parseArgs</a>.</p>

</div>
</div>

### findNearest() {#a4d8119253a15642e1fe80d26ae7f7360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned OptTable::findNearest (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Option, std::string &amp; NearestString, unsigned FlagsToInclude, unsigned FlagsToExclude=0, unsigned MinimumLength=4, unsigned MaximumDistance=UINT_MAX)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#ab63d01bf15a9a15adfa21d47453596b9">llvm::opt::OptTable::Info::Flags</a>.</p>

</div>
</div>

### getNumOptions() {#adf26248c40fce6fe688d619686698f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::OptTable::getNumOptions ()</td>
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

<p>Return the total number of option classes.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Referenced by <a href="#a2fad5655e536707e9af3286417f2e3c6">getOption</a> and <a href="#a25c39b3831711b590024c338280aca72">OptTable</a>.</p>

</div>
</div>

### getOption() {#a2fad5655e536707e9af3286417f2e3c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Option OptTable::getOption (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Opt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the given Opt's <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> instance, lazily creating it if necessary.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The option, or null for the INVALID option id.</p></dd>
</dl>


<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier/#af3dfa747aaff5143476f4840de4df433">llvm::opt::OptSpecifier::getID</a> and <a href="#adf26248c40fce6fe688d619686698f93">getNumOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp/#ad6a0cf2a79d837c8bedf8ec34f134eea">getOptionHelpName</a> and <a href="#a25c39b3831711b590024c338280aca72">OptTable</a>.</p>

</div>
</div>

### getOptionGroupID() {#a9aae5837deca80e30e622c3bb524859c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::OptTable::getOptionGroupID (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> id)</td>
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

<p>Get the group id for the given option.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp/#a3401de5fc1f5acce586fb1185b125b53">getOptionHelpGroup</a>.</p>

</div>
</div>

### getOptionHelpText() {#a34271f265cc461ddb0e8f3e0e1b45fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::opt::OptTable::getOptionHelpText (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> id)</td>
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

<p>Get the help text to use to describe this option.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Reference <a href="#a34271f265cc461ddb0e8f3e0e1b45fa7">getOptionHelpText</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp/#a3401de5fc1f5acce586fb1185b125b53">getOptionHelpGroup</a> and <a href="#a34271f265cc461ddb0e8f3e0e1b45fa7">getOptionHelpText</a>.</p>

</div>
</div>

### getOptionHelpText() {#a0e705312a9e6fa8f248f0e2e8c3339d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::opt::OptTable::getOptionHelpText (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> id, <a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a> VisibilityMask)</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#ac567b0eb5a967854e3638d66c5d8a084">llvm::opt::OptTable::Info::HelpText</a> and <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#af47dd44efbefdfc695c54e3fd4a8c07d">llvm::opt::OptTable::Info::HelpTextsForVariants</a>.</p>

</div>
</div>

### getOptionKind() {#a144e7c564652619e7426764852dc17ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::OptTable::getOptionKind (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> id)</td>
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

<p>Get the kind of the given option.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### getOptionMetaVar() {#a20488bdf75a8ad482e6fa40d38af6345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::opt::OptTable::getOptionMetaVar (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> id)</td>
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

<p>Get the meta-variable name to use when describing this options values in the help text.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp/#ad6a0cf2a79d837c8bedf8ec34f134eea">getOptionHelpName</a>.</p>

</div>
</div>

### getOptionName() {#a0d7fc5898d931b9576f991e5069c3953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::OptTable::getOptionName (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> id)</td>
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

<p>Lookup the name of the given option.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### getOptionPrefix() {#a403d67b8ae68de27b868e352b9d213d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::OptTable::getOptionPrefix (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> id)</td>
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

<p>Lookup the prefix of the given option.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getOptionPrefixedName() {#aba23caa0f0c4bb6ab71df6cdae32d5d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::OptTable::getOptionPrefixedName (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> id)</td>
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

<p>Lookup the prefixed name of the given option.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### getPrefixesTable() {#abc863453abb95d4e2094b5bd1b671b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; StringTable::Offset &gt; llvm::opt::OptTable::getPrefixesTable ()</td>
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

<p>Return the prefixes table used for option names.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### getStrTable() {#af0d94127cb03aeac6867d147ff2ec2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringTable &amp; llvm::opt::OptTable::getStrTable ()</td>
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

<p>Return the string table used for option names.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### parseArgs() {#a0f0446fb27e6a1ab9f59c283d0960e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InputArgList OptTable::parseArgs (int Argc, char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Argv, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Unknown, <a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a> &amp; Saver, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; ErrorFn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A convenience helper which handles optional initial options populated from an environment variable, expands response files recursively and parses options.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ErrorFn</td>
<td class="doxyParamItemDescription"><p>- Called on a formatted error message for missing arguments or unknown options.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a>; on error this will contain all the options which could be parsed.</p></dd>
</dl>


<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a3a60629142da060688204fabc5b05469">llvm::cl::expandResponseFiles</a>, <a href="#a2bc0c8204694490e197301b24eb6c140">findNearest</a>, <a href="#aae1e1c17454fb6433f039b5fb02c5c4d">ParseArgs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>

</div>
</div>

### ParseArgs() {#aae1e1c17454fb6433f039b5fb02c5c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InputArgList OptTable::ParseArgs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; Args, unsigned &amp; MissingArgIndex, unsigned &amp; MissingArgCount, <a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a> VisibilityMask=<a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse an list of arguments into an <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a>.</p>


<p>The resulting <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a> will reference the strings in [<span class="doxyComputerOutput">ArgBegin</span>, <span class="doxyComputerOutput">ArgEnd</span>), and their lifetime should extend past that of the returned <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a>.</p>


<p>The only error that can occur in this routine is if an argument is missing values; in this case <span class="doxyComputerOutput">MissingArgCount</span> will be non-zero.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MissingArgIndex</td>
<td class="doxyParamItemDescription"><p>- On error, the index of the option which could not be parsed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MissingArgCount</td>
<td class="doxyParamItemDescription"><p>- On error, the number of missing options.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VisibilityMask</td>
<td class="doxyParamItemDescription"><p>- Only include options with any of these visibility flags set.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a>; on error this will contain all the options which could be parsed.</p></dd>
</dl>


<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a772f45a13c458f1ca87fe137724017bf">llvm::opt::Option::hasVisibilityFlag</a>.</p>


<p>Referenced by <a href="#a0f0446fb27e6a1ab9f59c283d0960e86">parseArgs</a>.</p>

</div>
</div>

### ParseArgs() {#ac095b04e69b50cc16e488b2cebd8ecc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InputArgList OptTable::ParseArgs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; Args, unsigned &amp; MissingArgIndex, unsigned &amp; MissingArgCount, unsigned FlagsToInclude, unsigned FlagsToExclude=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a5297d732b8f9e9447a4f86e9eda1780e">llvm::opt::Option::hasFlag</a>.</p>

</div>
</div>

### ParseOneArg() {#a209267a94d47fc715aedcb7c0b836d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Arg &gt; OptTable::ParseOneArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp; Args, unsigned &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a> VisibilityMask=<a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a single argument; returning the new argument and updating Index.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Index</td>
<td class="doxyParamItemDescription"><p>- The current parsing position in the argument string list; on return this will be the index of the next argument string to parse.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] VisibilityMask</td>
<td class="doxyParamItemDescription"><p>- Only include options with any of these visibility flags set.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The parsed argument, or 0 if the argument is missing values (in which case Index still points at the conceptual next argument string to parse).</p></dd>
</dl>


<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a772f45a13c458f1ca87fe137724017bf">llvm::opt::Option::hasVisibilityFlag</a>.</p>

</div>
</div>

### ParseOneArg() {#a534b852fce32e3f367c7d79668439fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Arg &gt; OptTable::ParseOneArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp; Args, unsigned &amp; Index, unsigned FlagsToInclude, unsigned FlagsToExclude)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a5297d732b8f9e9447a4f86e9eda1780e">llvm::opt::Option::hasFlag</a>.</p>

</div>
</div>

### printHelp() {#a1ef4e8b65e20fbddebc0a43c5b61eeb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OptTable::printHelp (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Usage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Title, bool ShowHidden=false, bool ShowAllAliases=false, <a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a> VisibilityMask=<a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Render the help text for an option table.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>- The stream to write the help text to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Usage</td>
<td class="doxyParamItemDescription"><p>- USAGE: Usage</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Title</td>
<td class="doxyParamItemDescription"><p>- OVERVIEW: Title</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VisibilityMask</td>
<td class="doxyParamItemDescription"><p>- Only in <a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a> VisibilityMask,clude options with any of these visibility flags set.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ShowHidden</td>
<td class="doxyParamItemDescription"><p>- If true, display options marked as HelpHidden</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ShowAllAliases</td>
<td class="doxyParamItemDescription"><p>- If true, display all options including aliases that don't have help texts. By default, we display only options that are not hidden and have help texts.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#a5fd493d1cc2d1c57e01f2881dcdd00f9">llvm::opt::OptTable::Info::Visibility</a>.</p>

</div>
</div>

### printHelp() {#a667472bdd201aa8c1db898f31085eae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OptTable::printHelp (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Usage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Title, unsigned FlagsToInclude, unsigned FlagsToExclude, bool ShowAllAliases)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#ab63d01bf15a9a15adfa21d47453596b9">llvm::opt::OptTable::Info::Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/opt/#a834f7f7c0030af7d8ca758ed0468c8dcaa570b9511c70ab9813c19f9efbc3a23c">llvm::opt::HelpHidden</a>.</p>

</div>
</div>

### setDashDashParsing() {#a6e9e54d5c7b20ab2e63f88267aafc592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::OptTable::setDashDashParsing (bool Value)</td>
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

<p>Set whether "--" stops option parsing and treats all subsequent arguments as positional.</p>


<p>E.g. – -a -b gives two positional inputs.</p>


<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### setGroupedShortOptions() {#aff8bcfe99a666b88771c15356cc778be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::OptTable::setGroupedShortOptions (bool Value)</td>
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

<p>Support grouped short options. e.g. -ab represents -a -b.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### setInitialOptionsFromEnvironment() {#a52af886cfdde9fcdd2eb8f38b1a38a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::OptTable::setInitialOptionsFromEnvironment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * E)</td>
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

<p>Specify the environment variable where initial options should be read.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>.</p>

</div>
</div>

### suggestValueCompletions() {#aaddd5ed7dd146aad3e0c51691a90f22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::string &gt; OptTable::suggestValueCompletions (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Option, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find possible value for given flags.</p>


<p>This is used for shell autocompletion.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/opt/option"&gt;Option&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- Key flag like "-stdlib=" when "-stdlib=l" was passed to clang.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/opt/arg"&gt;Arg&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> which we want to autocomplete like "l" when "-stdlib=l" was passed to clang.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The vector of possible values.</p></dd>
</dl>


<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="#a17c70cba1015342a5a66a5bf0e110f95">FirstSearchableIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp/#a52718732068c64ac539d3d833cef25af">optionMatches</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### buildPrefixChars() {#a01fdf8f5ab053f70c4c67fd8361b60d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OptTable::buildPrefixChars ()</td>
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

<p>Build (or rebuild) the PrefixChars member.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#ac1dc3d5ce73817f28b8925a1cf6a659b">PrefixChars</a> and <a href="#a2f70e420cd97fc15e415b7e4c16c6deb">PrefixesUnion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/genericopttable/#ac3179665bf593185b092d08113399ae8">llvm::opt::GenericOptTable::GenericOptTable</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/precomputedopttable/#a7305670bef5cd628b213e3a84d2222a1">llvm::opt::PrecomputedOptTable::PrecomputedOptTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getInfo() {#a555478c5ebdbb4122c84ab649f2a8fe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Info &amp; llvm::opt::OptTable::getInfo (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Opt)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### internalFindNearest() {#abd4a071276f3827bd8ce11c2a3a852a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned OptTable::internalFindNearest (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Option, std::string &amp; NearestString, unsigned MinimumLength, unsigned MaximumDistance, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">Info</a> &amp;)&gt; ExcludeOption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>

</div>
</div>

### internalParseArgs() {#a7c6c3568b13ab756e0f65e88e0b876e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InputArgList OptTable::internalParseArgs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; Args, unsigned &amp; MissingArgIndex, unsigned &amp; MissingArgCount, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> &amp;)&gt; ExcludeOption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>

</div>
</div>

### internalParseOneArg() {#aeec051d989dd3791dfe72eb41526f93b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Arg &gt; OptTable::internalParseOneArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp; Args, unsigned &amp; Index, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> &amp;)&gt; ExcludeOption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>

</div>
</div>

### internalPrintHelp() {#a3c55c91cd74de600f989b6f9f1be41c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OptTable::internalPrintHelp (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Usage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Title, bool ShowHidden, bool ShowAllAliases, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">Info</a> &amp;)&gt; ExcludeOption, <a href="/web-llvm/docs/api/classes/llvm/opt/visibility">Visibility</a> VisibilityMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>

</div>
</div>

### parseOneArgGrouped() {#af36e218fffeabc289767459c9c7fedf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Arg &gt; OptTable::parseOneArgGrouped (<a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a> &amp; Args, unsigned &amp; Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### FirstSearchableIndex {#a17c70cba1015342a5a66a5bf0e110f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::OptTable::FirstSearchableIndex = 0</td>
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

<p>The index of the first option which can be parsed (i.e., is not a special option like 'input' or 'unknown', and is not an option group).</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Referenced by <a href="#aebb9a5bb7299045f334f16d82f244ad0">findByPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/genericopttable/#ac3179665bf593185b092d08113399ae8">llvm::opt::GenericOptTable::GenericOptTable</a>, <a href="#a25c39b3831711b590024c338280aca72">OptTable</a> and <a href="#aaddd5ed7dd146aad3e0c51691a90f22c">suggestValueCompletions</a>.</p>

</div>
</div>

### PrefixChars {#ac1dc3d5ce73817f28b8925a1cf6a659b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;8&gt; llvm::opt::OptTable::PrefixChars</td>
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

<p>The union of the first element of all option prefixes.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Referenced by <a href="#a01fdf8f5ab053f70c4c67fd8361b60d5">buildPrefixChars</a>.</p>

</div>
</div>

### PrefixesUnion {#a2f70e420cd97fc15e415b7e4c16c6deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StringRef&gt; llvm::opt::OptTable::PrefixesUnion</td>
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

<p>The union of all option prefixes.</p>


<p>If an argument does not begin with one of these, it is an input.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<p>Referenced by <a href="#a01fdf8f5ab053f70c4c67fd8361b60d5">buildPrefixChars</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/genericopttable/#ac3179665bf593185b092d08113399ae8">llvm::opt::GenericOptTable::GenericOptTable</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/precomputedopttable/#a7305670bef5cd628b213e3a84d2222a1">llvm::opt::PrecomputedOptTable::PrecomputedOptTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DashDashParsing {#a4697e66204c03ecb0a5fc4f8241b5107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::OptTable::DashDashParsing = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### EnvVar {#ab2c04914f1661720d1cd8cfb2ceaaf93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::opt::OptTable::EnvVar = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### GroupedShortOptions {#a4a155c407d9d4a2bf8edfc0c6cb19145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::OptTable::GroupedShortOptions = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### IgnoreCase {#ad0b4474db51ca5818ad5b8580adfa66f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::OptTable::IgnoreCase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### InputOptionID {#a600332e173fe59a9b2430bb03ffb8115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::OptTable::InputOptionID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### OptionInfos {#a1444dfbdbabd8878c00c25469032187f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;Info&gt; llvm::opt::OptTable::OptionInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The option information table.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### PrefixesTable {#ae3a82453a532d106c75499a299823d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;StringTable::Offset&gt; llvm::opt::OptTable::PrefixesTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### StrTable {#abb70a2616b6fa8f40dedce48ecc9fbf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringTable* llvm::opt::OptTable::StrTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

### UnknownOptionID {#a185980792e5402b6d2e25e42500022c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::OptTable::UnknownOptionID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
