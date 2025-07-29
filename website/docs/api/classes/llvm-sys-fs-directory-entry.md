---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sys/fs/directory-entry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `directory_entry` Class

<p><a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry">directory_entry</a> - A single entry in a directory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sys::fs::directory_entry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e7e41835f4f1b7568589acf598b83db">directory_entry</a> (const Twine &amp;Path, bool FollowSymlinks=true, file_type Type=file_type::type_unknown, basic_file_status Status=basic_file_status())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb9603e09037e57d4d3b29940a6f6127">directory_entry</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa754367ae705131fe3241d9277c4c066">operator==</a> (const directory_entry &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1ffb915d1f52b2bf8b5a4c0cd2ad323">operator!=</a> (const directory_entry &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8466ac4ae9cdc3c2e37da97871e0d84c">operator&lt;</a> (const directory_entry &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9133f1eee689b57948f6189e4fa04df7">operator&lt;=</a> (const directory_entry &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad557570393a2b4a1aba13b988672ce9a">operator&gt;</a> (const directory_entry &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48eec0fc62bd66bb40748eb491a9efad">operator&gt;=</a> (const directory_entry &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74c609b9d0a0eba4ea8f416dc2b0f19">replace_filename</a> (const Twine &amp;Filename, file_type Type, basic_file_status Status=basic_file_status())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add34311bc00580d44ed637f7435464e7">path</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status">basic_file_status</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f998fbb7795181d540a5fabf31e03d">status</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">file_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3488d637fb3f5bbb811b9377d7bb686">type</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69e9cae34a4eb1c533a6f5c19fb5a652">Path</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">file_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c8a06752c39810dc964d17b055932b">Type</a> = <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca415c07e20d98e11ce0d5e52a2ce2572f">file_type::type_unknown</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f85d88f26b2ce64917a96f4e482ff9">FollowSymlinks</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status">basic_file_status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a029d3c1be119bf4432832a0361584a26">Status</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry">directory_entry</a> - A single entry in a directory.</p>

<p>Definition at line 1347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### directory\_entry() {#a0e7e41835f4f1b7568589acf598b83db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::directory_entry::directory_entry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, bool FollowSymlinks=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">file_type</a> Type=<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca415c07e20d98e11ce0d5e52a2ce2572f">file_type::type_unknown</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status">basic_file_status</a> Status=<a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status">basic_file_status</a>())</td>
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



<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca415c07e20d98e11ce0d5e52a2ce2572f">llvm::sys::fs::type_unknown</a>.</p>


<p>Referenced by <a href="#ac1ffb915d1f52b2bf8b5a4c0cd2ad323">operator!=</a>, <a href="#a8466ac4ae9cdc3c2e37da97871e0d84c">operator&lt;</a>, <a href="#a9133f1eee689b57948f6189e4fa04df7">operator&lt;=</a>, <a href="#aa754367ae705131fe3241d9277c4c066">operator==</a>, <a href="#ad557570393a2b4a1aba13b988672ce9a">operator&gt;</a> and <a href="#a48eec0fc62bd66bb40748eb491a9efad">operator&gt;=</a>.</p>

</div>
</div>

### directory\_entry() {#aeb9603e09037e57d4d3b29940a6f6127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::directory_entry::directory_entry ()</td>
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



<p>Definition at line 1365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ac1ffb915d1f52b2bf8b5a4c0cd2ad323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::fs::directory_entry::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry">directory_entry</a> &amp; RHS)</td>
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



<p>Definition at line 1386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>References <a href="#a0e7e41835f4f1b7568589acf598b83db">directory_entry</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#a8466ac4ae9cdc3c2e37da97871e0d84c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::fs::directory_entry::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry">directory_entry</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>References <a href="#a0e7e41835f4f1b7568589acf598b83db">directory_entry</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;=() {#a9133f1eee689b57948f6189e4fa04df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::fs::directory_entry::operator&lt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry">directory_entry</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>References <a href="#a0e7e41835f4f1b7568589acf598b83db">directory_entry</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#aa754367ae705131fe3241d9277c4c066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::fs::directory_entry::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry">directory_entry</a> &amp; RHS)</td>
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



<p>Definition at line 1385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>References <a href="#a0e7e41835f4f1b7568589acf598b83db">directory_entry</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;() {#ad557570393a2b4a1aba13b988672ce9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::fs::directory_entry::operator&gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry">directory_entry</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>References <a href="#a0e7e41835f4f1b7568589acf598b83db">directory_entry</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;=() {#a48eec0fc62bd66bb40748eb491a9efad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::fs::directory_entry::operator&gt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry">directory_entry</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>References <a href="#a0e7e41835f4f1b7568589acf598b83db">directory_entry</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### path() {#add34311bc00580d44ed637f7435464e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::sys::fs::directory_entry::path ()</td>
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



<p>Definition at line 1370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-iterator/#a3542b9b7f9744755a6331cf2aa5f6c33">llvm::sys::fs::directory_iterator::directory_iterator</a>.</p>

</div>
</div>

### replace\_filename() {#af74c609b9d0a0eba4ea8f416dc2b0f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::fs::directory_entry::replace_filename (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">file_type</a> Type, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status">basic_file_status</a> Status=<a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status">basic_file_status</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a>.</p>

</div>
</div>

### status() {#a30f998fbb7795181d540a5fabf31e03d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; basic_file_status &gt; llvm::sys::fs::directory_entry::status ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#ad3488d637fb3f5bbb811b9377d7bb686">type</a>.</p>

</div>
</div>

### type() {#ad3488d637fb3f5bbb811b9377d7bb686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">file_type llvm::sys::fs::directory_entry::type ()</td>
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



<p>Definition at line 1378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>References <a href="#a30f998fbb7795181d540a5fabf31e03d">status</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca415c07e20d98e11ce0d5e52a2ce2572f">llvm::sys::fs::type_unknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FollowSymlinks {#aa7f85d88f26b2ce64917a96f4e482ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::fs::directory_entry::FollowSymlinks = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### Path {#a69e9cae34a4eb1c533a6f5c19fb5a652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::sys::fs::directory_entry::Path</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### Status {#a029d3c1be119bf4432832a0361584a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_file_status llvm::sys::fs::directory_entry::Status</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### Type {#a86c8a06752c39810dc964d17b055932b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">file_type llvm::sys::fs::directory_entry::Type = <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca415c07e20d98e11ce0d5e52a2ce2572f">file_type::type_unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
