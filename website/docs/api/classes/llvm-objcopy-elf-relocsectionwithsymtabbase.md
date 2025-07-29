---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/elf/relocsectionwithsymtabbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RelocSectionWithSymtabBase` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;class SymTabType&gt;
class llvm::objcopy::elf::RelocSectionWithSymtabBase&lt;SymTabType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ObjCopy/ELF/ELFObject.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocationsectionbase">RelocationSectionBase</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SymTabType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5b78c2632993f7bd9d22d132dd130e73">RelocSectionWithSymtabBase</a> ()=default</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SymTabType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a957eb6753673d0aa863ddb450a9fa424">initialize</a> (SectionTableRef SecTable) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SymTabType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1972f264beb7a4843a3106f822bcbf8d">finalize</a> () override</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SymTabType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a523345b3e7d69c1a6f7e1973a95f8bca">setSymTab</a> (SymTabType *SymTab)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SymTabType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SymTabType *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac01f7d0cc784c140da3c0e8afd188b88">Symbols</a> = nullptr</td>
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


<p>Definition at line 896 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### RelocSectionWithSymtabBase() {#a5b78c2632993f7bd9d22d132dd130e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SymTabType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::elf::RelocSectionWithSymtabBase&lt; SymTabType &gt;::RelocSectionWithSymtabBase ()</td>
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



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalize() {#a1972f264beb7a4843a3106f822bcbf8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SymTabType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RelocSectionWithSymtabBase::finalize ()</td>
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



<p>Declaration at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#aa8b758f52d7a2f72c6ac4c65b2aa2c41">llvm::objcopy::elf::SectionBase::Info</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6d76f000182407983c28aab811228fcf">llvm::objcopy::elf::SectionBase::Link</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocationsectionbase/#ab6fd94e8484dacd19eed5accacf577cc">llvm::objcopy::elf::RelocationSectionBase::SecToApplyRel</a> and <a href="#ac01f7d0cc784c140da3c0e8afd188b88">llvm::objcopy::elf::RelocSectionWithSymtabBase&lt; SymTabType &gt;::Symbols</a>.</p>

</div>
</div>

### initialize() {#a957eb6753673d0aa863ddb450a9fa424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SymTabType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RelocSectionWithSymtabBase::initialize (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectiontableref">SectionTableRef</a> SecTable)</td>
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



<p>Declaration at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectiontableref/#abda78d9dce5c182f24eb5a92cb29bbaa">llvm::objcopy::elf::SectionTableRef::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectiontableref/#a1ede3cfcdfaccefa28d52e3e0bb13bda">llvm::objcopy::elf::SectionTableRef::getSectionOfType</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#aa8b758f52d7a2f72c6ac4c65b2aa2c41">llvm::objcopy::elf::SectionBase::Info</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6d76f000182407983c28aab811228fcf">llvm::objcopy::elf::SectionBase::Link</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6ca324c9086862d837e0593199d1e58e">llvm::objcopy::elf::SectionBase::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocationsectionbase/#ae27165e6aaaf240b0c5c1ec0c22460b7">llvm::objcopy::elf::RelocationSectionBase::setSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setSymTab() {#a523345b3e7d69c1a6f7e1973a95f8bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SymTabType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::elf::RelocSectionWithSymtabBase&lt; SymTabType &gt;::setSymTab (SymTabType * SymTab)</td>
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



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Symbols {#ac01f7d0cc784c140da3c0e8afd188b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SymTabType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymTabType* llvm::objcopy::elf::RelocSectionWithSymtabBase&lt; SymTabType &gt;::Symbols = nullptr</td>
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



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="#a1972f264beb7a4843a3106f822bcbf8d">llvm::objcopy::elf::RelocSectionWithSymtabBase&lt; SymTabType &gt;::finalize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
