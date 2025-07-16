---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/specialcaselist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SpecialCaseList` Class Reference

<p>This is a utility class used to parse user-provided text files with "special case lists" for code sanitizers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SpecialCaseList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">llvm/Support/SpecialCaseList.h</a>"
</div>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecbe1059ebccc9ee4b8e8b43e6d026a8">SectionEntries</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/specialcaselist/matcher">Matcher</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b799c5b8a9865e51dfb44b0c8498a1">SpecialCaseList</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a141eb963d759c382bdf7b359489648e0">SpecialCaseList</a> (SpecialCaseList const &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a973602c10952d42c1862f2e745280ec8">~SpecialCaseList</a> ()</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a8c1a7772379f7ef89625ba236a177">operator=</a> (SpecialCaseList const &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af394caf58f7cb160c839f71cdf6697ca">inSection</a> (StringRef Section, StringRef Prefix, StringRef Query, StringRef Category=StringRef()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true, if special case list contains a line. <a href="#af394caf58f7cb160c839f71cdf6697ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2861cf6102d164cff830ba0b31e9e38">inSectionBlame</a> (StringRef Section, StringRef Prefix, StringRef Query, StringRef Category=StringRef()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the line number corresponding to the special case list entry if the special case list contains a line. <a href="#ab2861cf6102d164cff830ba0b31e9e38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e125454a7bbe1568bddd90a3045bade">createInternal</a> (const std::vector&lt; std::string &gt; &amp;Paths, vfs::FileSystem &amp;VFS, std::string &amp;Error)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb50180bcc2a385ee38e2f7400c1c983">createInternal</a> (const MemoryBuffer *MB, std::string &amp;Error)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/specialcaselist/section">Section</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acddee90812e74127ce6b0d59780166f0">addSection</a> (StringRef SectionStr, unsigned LineNo, bool UseGlobs=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd812a66cf342fb3cd2e392ec9c7a0b0">parse</a> (const MemoryBuffer *MB, std::string &amp;Error)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses just-constructed <a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> entries from a memory buffer. <a href="#afd812a66cf342fb3cd2e392ec9c7a0b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e1e1d8f6e061aee93a507c395ac2c9f">inSectionBlame</a> (const SectionEntries &amp;Entries, StringRef Prefix, StringRef Query, StringRef Category) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/specialcaselist/section">Section</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a37a162a6f093f0ba2fed20f7c6a04">Sections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86af60e718692f43fa3a22b94bbbc4a8">create</a> (const std::vector&lt; std::string &gt; &amp;Paths, llvm::vfs::FileSystem &amp;FS, std::string &amp;Error)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses the special case list entries from files. <a href="#a86af60e718692f43fa3a22b94bbbc4a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ab77fdd72977bc4b930a7e6c5570e8">create</a> (const MemoryBuffer *MB, std::string &amp;Error)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses the special case list from a memory buffer. <a href="#a81ab77fdd72977bc4b930a7e6c5570e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c0343ae2b29d3a9882c0cfc4bee8c03">createOrDie</a> (const std::vector&lt; std::string &gt; &amp;Paths, llvm::vfs::FileSystem &amp;FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses the special case list entries from files. <a href="#a6c0343ae2b29d3a9882c0cfc4bee8c03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is a utility class used to parse user-provided text files with "special case lists" for code sanitizers.</p>


<p>Such files are used to define an "ABI list" for DataFlowSanitizer and allow/exclusion lists for sanitizers like AddressSanitizer or UndefinedBehaviorSanitizer.</p>


<p>Empty lines and lines starting with "#" are ignored. Sections are defined using a '[section_name]' header and can be used to specify sanitizers the entries below it apply to. <a href="/web-llvm/docs/api/structs/llvm/specialcaselist/section">Section</a> names are globs, and entries without a section header match all sections (e.g. an '[*]' header is assumed.) The remaining lines should have the form: prefix:glob_pattern[=category] If category is not specified, it is assumed to be empty string. Definitions of "prefix" and "category" are sanitizer-specific. For example, sanitizer exclusion support prefixes "src", "mainfile", "fun" and "global". "glob_pattern" defines source files, main files, functions or globals which shouldn't be instrumented. Examples of categories: "functional": used in DFSan to list functions with pure functional semantics. "init": used in ASan exclusion list to disable initialization-order bugs detection for certain globals or source files.</p>



### Full special case list file example: {#autotoc_md54}


<p>[address]</p>


## Excluded items: {#autotoc_md55}


<p>fun:<em>_ZN4base6subtle</em> global:<em>global_with_bad_access_or_initialization</em> global:<em>global_with_initialization_issues</em>=init type:<em>Namespace::ClassName</em>=init src:file_with_tricky_code.cc src:ignore-global-initializers-issues.cc=init mainfile:main_file.cc</p>


<p>[dataflow]</p>


## Functions with pure functional semantics: {#autotoc_md56}


<p>fun:cos=functional</p>


### fun:sin=functional {#autotoc_md57}


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### SectionEntries {#aecbe1059ebccc9ee4b8e8b43e6d026a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SpecialCaseList::SectionEntries =  StringMap&lt;StringMap&lt;Matcher&gt;&gt;</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### SpecialCaseList() {#a96b799c5b8a9865e51dfb44b0c8498a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SpecialCaseList::SpecialCaseList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>


<p>Referenced by <a href="#a81ab77fdd72977bc4b930a7e6c5570e8">create</a>, <a href="#a86af60e718692f43fa3a22b94bbbc4a8">create</a>, <a href="#a08a8c1a7772379f7ef89625ba236a177">operator=</a> and <a href="#a141eb963d759c382bdf7b359489648e0">SpecialCaseList</a>.</p>

</div>
</div>

### SpecialCaseList() {#a141eb963d759c382bdf7b359489648e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SpecialCaseList::SpecialCaseList (<a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>


<p>Reference <a href="#a96b799c5b8a9865e51dfb44b0c8498a1">SpecialCaseList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SpecialCaseList() {#a973602c10952d42c1862f2e745280ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SpecialCaseList::~SpecialCaseList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a08a8c1a7772379f7ef89625ba236a177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecialCaseList &amp; llvm::SpecialCaseList::operator= (<a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>


<p>Reference <a href="#a96b799c5b8a9865e51dfb44b0c8498a1">SpecialCaseList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### inSection() {#af394caf58f7cb160c839f71cdf6697ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SpecialCaseList::inSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Query, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Category=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true, if special case list contains a line.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">@<a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa7861ef1db44eac8ea7a373cd7c53a7c5">Prefix</a>:&lt;<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>&gt;=@Category</span></span></div>

</div>


<p>where @Query satisfies the glob &lt;E&gt; in a given @Section.</p>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>Reference <a href="#ab2861cf6102d164cff830ba0b31e9e38">inSectionBlame</a>.</p>

</div>
</div>

### inSectionBlame() {#ab2861cf6102d164cff830ba0b31e9e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SpecialCaseList::inSectionBlame (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Query, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Category=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the line number corresponding to the special case list entry if the special case list contains a line.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">@<a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa7861ef1db44eac8ea7a373cd7c53a7c5">Prefix</a>:&lt;<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>&gt;=@Category</span></span></div>

</div>


<p>where @Query satisfies the glob &lt;E&gt; in a given @Section. Returns zero if there is no exclusion entry corresponding to this expression.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>References <a href="#ab2861cf6102d164cff830ba0b31e9e38">inSectionBlame</a> and <a href="#a87a37a162a6f093f0ba2fed20f7c6a04">Sections</a>.</p>


<p>Referenced by <a href="#af394caf58f7cb160c839f71cdf6697ca">inSection</a> and <a href="#ab2861cf6102d164cff830ba0b31e9e38">inSectionBlame</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addSection() {#acddee90812e74127ce6b0d59780166f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SpecialCaseList::Section * &gt; llvm::SpecialCaseList::addSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionStr, unsigned LineNo, bool UseGlobs=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/specialcaselist/section/#a91cff40f296053ff15e49819d7675df6">llvm::SpecialCaseList::Section::SectionMatcher</a>, <a href="#a87a37a162a6f093f0ba2fed20f7c6a04">Sections</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>


<p>Referenced by <a href="#afd812a66cf342fb3cd2e392ec9c7a0b0">parse</a>.</p>

</div>
</div>

### createInternal() {#a5e125454a7bbe1568bddd90a3045bade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SpecialCaseList::createInternal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; Paths, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &amp; VFS, std::string &amp; Error)</td>
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



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/erroror/#a7903f14c3b4fb5b4f9f9fa8b4ee0b4eb">llvm::ErrorOr&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#ac2998b305007e6726aead7b5bdd8346d">llvm::vfs::FileSystem::getBufferForFile</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a> and <a href="#afd812a66cf342fb3cd2e392ec9c7a0b0">parse</a>.</p>

</div>
</div>

### createInternal() {#acb50180bcc2a385ee38e2f7400c1c983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SpecialCaseList::createInternal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> * MB, std::string &amp; Error)</td>
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



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>Reference <a href="#afd812a66cf342fb3cd2e392ec9c7a0b0">parse</a>.</p>

</div>
</div>

### inSectionBlame() {#a9e1e1d8f6e061aee93a507c395ac2c9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SpecialCaseList::inSectionBlame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aecbe1059ebccc9ee4b8e8b43e6d026a8">SectionEntries</a> &amp; Entries, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Query, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Category)</td>
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



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a16e5eaf2df56249e87019be23ee07695">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a49e68e4c86fe0b96c633adea0c366d74">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### parse() {#afd812a66cf342fb3cd2e392ec9c7a0b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SpecialCaseList::parse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> * MB, std::string &amp; Error)</td>
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

<p>Parses just-constructed <a href="/web-llvm/docs/api/classes/llvm/specialcaselist">SpecialCaseList</a> entries from a memory buffer.</p>

<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>References <a href="#acddee90812e74127ce6b0d59780166f0">addSection</a>, <a href="/web-llvm/docs/api/structs/llvm/specialcaselist/section/#a873ad17053480f9b05bb351a90cfeef5">llvm::SpecialCaseList::Section::Entries</a>, <a href="/web-llvm/docs/api/classes/llvm/line-iterator/#a617941704a472090ba3304c9daf1c37f">llvm::line_iterator::is_at_eof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>


<p>Referenced by <a href="#acb50180bcc2a385ee38e2f7400c1c983">createInternal</a> and <a href="#a5e125454a7bbe1568bddd90a3045bade">createInternal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Sections {#a87a37a162a6f093f0ba2fed20f7c6a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;Section&gt; llvm::SpecialCaseList::Sections</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>


<p>Referenced by <a href="#acddee90812e74127ce6b0d59780166f0">addSection</a> and <a href="#ab2861cf6102d164cff830ba0b31e9e38">inSectionBlame</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a86af60e718692f43fa3a22b94bbbc4a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SpecialCaseList &gt; llvm::SpecialCaseList::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; Paths, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">llvm::vfs::FileSystem</a> &amp; FS, std::string &amp; Error)</td>
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

<p>Parses the special case list entries from files.</p>


<p>On failure, returns 0 and writes an error message to string.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>Reference <a href="#a96b799c5b8a9865e51dfb44b0c8498a1">SpecialCaseList</a>.</p>


<p>Referenced by <a href="#a6c0343ae2b29d3a9882c0cfc4bee8c03">createOrDie</a>.</p>

</div>
</div>

### create() {#a81ab77fdd72977bc4b930a7e6c5570e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SpecialCaseList &gt; llvm::SpecialCaseList::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> * MB, std::string &amp; Error)</td>
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

<p>Parses the special case list from a memory buffer.</p>


<p>On failure, returns 0 and writes an error message to string.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>Reference <a href="#a96b799c5b8a9865e51dfb44b0c8498a1">SpecialCaseList</a>.</p>

</div>
</div>

### createOrDie() {#a6c0343ae2b29d3a9882c0cfc4bee8c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SpecialCaseList &gt; llvm::SpecialCaseList::createOrDie (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; Paths, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">llvm::vfs::FileSystem</a> &amp; FS)</td>
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

<p>Parses the special case list entries from files.</p>


<p>On failure, reports a fatal error.</p>


<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>References <a href="#a86af60e718692f43fa3a22b94bbbc4a8">create</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#a991cf3988b07a606932e1d69f8f8507f">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DataFlowSanitizer</a>, <a href="/web-llvm/docs/api/classes/llvm/sanitizerbinarymetadatapass/#a4c4b3aea1ab9cc4a61033672c29e3c69">llvm::SanitizerBinaryMetadataPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/sanitizercoveragepass/#a4bda9a7c3b3d5d112826474bc35081e0">llvm::SanitizerCoveragePass::SanitizerCoveragePass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
