---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/option/opttable-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `OptTable.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">llvm/Option/OptTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">llvm/Option/Arg.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">llvm/Option/ArgList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/optspecifier-h">llvm/Option/OptSpecifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">llvm/Option/Option.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optionstrcmp-h">llvm/Support/OptionStrCmp.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cctype&gt;
#include &lt;cstring&gt;
#include &lt;map&gt;
#include &lt;set&gt;
#include &lt;string&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-opttable-cpp-">anonymous{OptTable.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-opttable-cpp-/optnameless">OptNameLess</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-opttable-cpp-/optioninfo">OptionInfo</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af47bf37decca7e443848028fa880eb14">isInput</a> (const ArrayRef&lt; StringRef &gt; &amp;Prefixes, StringRef Arg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4483fb95f4751170fa6aa139f143f02d">matchOption</a> (const StringTable &amp;StrTable, ArrayRef&lt; StringTable::Offset &gt; PrefixesTable, const OptTable::Info *I, StringRef Str, bool IgnoreCase)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52718732068c64ac539d3d833cef25af">optionMatches</a> (const StringTable &amp;StrTable, ArrayRef&lt; StringTable::Offset &gt; PrefixesTable, const OptTable::Info &amp;In, StringRef Option)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a0cf2a79d837c8bedf8ec34f134eea">getOptionHelpName</a> (const OptTable &amp;Opts, OptSpecifier Id)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57814310114de54a058984c486a21a2">PrintHelpOptionList</a> (raw_ostream &amp;OS, StringRef Title, std::vector&lt; OptionInfo &gt; &amp;OptionHelp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3401de5fc1f5acce586fb1185b125b53">getOptionHelpGroup</a> (const OptTable &amp;Opts, OptSpecifier Id)</td>
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


<div class="doxySectionDef">

## Functions

### getOptionHelpGroup() {#a3401de5fc1f5acce586fb1185b125b53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getOptionHelpGroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> &amp; Opts, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id)</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a9aae5837deca80e30e622c3bb524859c">llvm::opt::OptTable::getOptionGroupID</a>, <a href="#a3401de5fc1f5acce586fb1185b125b53">getOptionHelpGroup</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a34271f265cc461ddb0e8f3e0e1b45fa7">llvm::opt::OptTable::getOptionHelpText</a>.</p>


<p>Referenced by <a href="#a3401de5fc1f5acce586fb1185b125b53">getOptionHelpGroup</a>.</p>

</div>
</div>

### getOptionHelpName() {#ad6a0cf2a79d837c8bedf8ec34f134eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getOptionHelpName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> &amp; Opts, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id)</td>
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



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba12db4284256b50d5b531680ae77ab8e6">llvm::opt::Option::CommaJoinedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba27b06b20590e7663bda7eaecf0c37a9c">llvm::opt::Option::FlagClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a2fad5655e536707e9af3286417f2e3c6">llvm::opt::OptTable::getOption</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a20488bdf75a8ad482e6fa40d38af6345">llvm::opt::OptTable::getOptionMetaVar</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba0f16fdf1d979a9ba138dc95d6717ceef">llvm::opt::Option::GroupClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba7024d387cb59117469f0c569582aa5f5">llvm::opt::Option::InputClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdbaa237a218eacb9074f730d871a7fa7489">llvm::opt::Option::JoinedAndSeparateClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba00b88f85db9274d8b0b201f43ee119aa">llvm::opt::Option::JoinedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba659e5c55e0d0fe0918c9a7f9a6baa337">llvm::opt::Option::JoinedOrSeparateClass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba6fcf25ba21f30298b3d3a78bd31a44ac">llvm::opt::Option::MultiArgClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba67c06d35b9ba366cd9bd137a72ea8a24">llvm::opt::Option::RemainingArgsClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdbaf04ccf92614d9d8e8cb585d71d1e31b4">llvm::opt::Option::RemainingArgsJoinedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba8cc1cc3ad33454d90a35df26268b75e4">llvm::opt::Option::SeparateClass</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdba71db01a325850d1a7b626f06e71a6504">llvm::opt::Option::UnknownClass</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a60071c133b78fca37ea728e2d1db6fdbaf6b275b7fac73f5fe312a2792767a14e">llvm::opt::Option::ValuesClass</a>.</p>

</div>
</div>

### isInput() {#af47bf37decca7e443848028fa880eb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isInput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Prefixes, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arg)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dependence/#aecb581fe2d522d3f1ab25c5e5c024928">llvm::Dependence::dump</a>.</p>

</div>
</div>

### matchOption() {#a4483fb95f4751170fa6aa139f143f02d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned matchOption (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringtable">StringTable</a> &amp; StrTable, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringtable/offset">StringTable::Offset</a> &gt; PrefixesTable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">OptTable::Info</a> * I, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, bool IgnoreCase)</td>
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
<dd><p>Matched size. 0 means no match.</p></dd>
</dl>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a343b6c58108519aca196bb54b1d1a6ef">llvm::StringRef::starts_with_insensitive</a>.</p>

</div>
</div>

### optionMatches() {#a52718732068c64ac539d3d833cef25af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool optionMatches (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringtable">StringTable</a> &amp; StrTable, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringtable/offset">StringTable::Offset</a> &gt; PrefixesTable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">OptTable::Info</a> &amp; In, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Option)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#aaddd5ed7dd146aad3e0c51691a90f22c">llvm::opt::OptTable::suggestValueCompletions</a>.</p>

</div>
</div>

### PrintHelpOptionList() {#af57814310114de54a058984c486a21a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintHelpOptionList (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Title, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; OptionInfo &gt; &amp; OptionHelp)</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
