---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/unittest/templink
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TempLink` Class

<p>A RAII object that creates a link upon initialization and removes it upon destruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::unittest::TempLink { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">llvm/Testing/Support/SupportHelpers.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae165707752c948dd6cdbbf79de356739">TempLink</a> (StringRef Target, StringRef Link)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a managed link at path Link pointing to <a href="/web-llvm/docs/api/classes/llvm/target">Target</a>. <a href="#ae165707752c948dd6cdbbf79de356739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcbacc0cc2b75bf29863ab6ea1a74f7d">TempLink</a> (const TempLink &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4cefa6c78430bcc507b1e7ce5b072f9">TempLink</a> (TempLink &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d45a9d93660d257d1bfb4197ffd0e46">~TempLink</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unittest/templink">TempLink</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9bf99aa937253f361e7ea08c13cfad">operator=</a> (const TempLink &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unittest/templink">TempLink</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4028e608e603cc80f4823d3c29b18c4e">operator=</a> (TempLink &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e1df7567a7da9e0386860ecf4b5247c">path</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The path to the link. <a href="#a1e1df7567a7da9e0386860ecf4b5247c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbabd22826cccea7451789f2a34eca48">Path</a></td>
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

<p>A RAII object that creates a link upon initialization and removes it upon destruction.</p>


<p>The link may be a soft or a hard link, depending on the platform.</p>


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TempLink() {#ae165707752c948dd6cdbbf79de356739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::unittest::TempLink::TempLink (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Target, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Link)</td>
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

<p>Creates a managed link at path Link pointing to <a href="/web-llvm/docs/api/classes/llvm/target">Target</a>.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a104eea5a51402274ef2499a3ee6c64b8">llvm::sys::fs::create_link</a>.</p>


<p>Referenced by <a href="#a5b9bf99aa937253f361e7ea08c13cfad">operator=</a>, <a href="#a4028e608e603cc80f4823d3c29b18c4e">operator=</a>, <a href="#adcbacc0cc2b75bf29863ab6ea1a74f7d">TempLink</a> and <a href="#ac4cefa6c78430bcc507b1e7ce5b072f9">TempLink</a>.</p>

</div>
</div>

### TempLink() {#adcbacc0cc2b75bf29863ab6ea1a74f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::unittest::TempLink::TempLink (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unittest/templink">TempLink</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<p>Reference <a href="#ae165707752c948dd6cdbbf79de356739">TempLink</a>.</p>

</div>
</div>

### TempLink() {#ac4cefa6c78430bcc507b1e7ce5b072f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::unittest::TempLink::TempLink (<a href="/web-llvm/docs/api/classes/llvm/unittest/templink">TempLink</a> &amp;&amp;)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<p>Reference <a href="#ae165707752c948dd6cdbbf79de356739">TempLink</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TempLink() {#a8d45a9d93660d257d1bfb4197ffd0e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::unittest::TempLink::~TempLink ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a5b9bf99aa937253f361e7ea08c13cfad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempLink &amp; llvm::unittest::TempLink::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unittest/templink">TempLink</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<p>Reference <a href="#ae165707752c948dd6cdbbf79de356739">TempLink</a>.</p>

</div>
</div>

### operator=() {#a4028e608e603cc80f4823d3c29b18c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempLink &amp; llvm::unittest::TempLink::operator= (<a href="/web-llvm/docs/api/classes/llvm/unittest/templink">TempLink</a> &amp;&amp;)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<p>Reference <a href="#ae165707752c948dd6cdbbf79de356739">TempLink</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### path() {#a1e1df7567a7da9e0386860ecf4b5247c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::unittest::TempLink::path ()</td>
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

<p>The path to the link.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Path {#abbabd22826cccea7451789f2a34eca48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;128&gt; llvm::unittest::TempLink::Path</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
