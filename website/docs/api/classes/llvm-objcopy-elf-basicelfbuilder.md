---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/elf/basicelfbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BasicELFBuilder` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::elf::BasicELFBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ObjCopy/ELF/ELFObject.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binaryelfbuilder">BinaryELFBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexelfbuilder">IHexELFBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d133a84d7e7fda64f90b76c9caceda">BasicELFBuilder</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53156fa08af05b511e0e9c0f476c1545">initFileHeader</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5598313252548691a55e2e29dbe69e8c">initHeaderSegment</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/stringtablesection">StringTableSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46bf4a5a8c7c2180cc146f232e4f7f6d">addStrTab</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection">SymbolTableSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62e4794b651253df24ca9cd5fe61340a">addSymTab</a> (StringTableSection *StrTab)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac573c6c02b8dea91c6c3831eac21b0ea">initSections</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74927e6bf86dae4692a942b02375e7d9">Obj</a></td>
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


<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BasicELFBuilder() {#ae3d133a84d7e7fda64f90b76c9caceda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::elf::BasicELFBuilder::BasicELFBuilder ()</td>
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



<p>Definition at line 1062 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Reference <a href="#a74927e6bf86dae4692a942b02375e7d9">Obj</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addStrTab() {#a46bf4a5a8c7c2180cc146f232e4f7f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableSection * BasicELFBuilder::addStrTab ()</td>
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



<p>Declaration at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 1281 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6ca324c9086862d837e0593199d1e58e">llvm::objcopy::elf::SectionBase::Name</a> and <a href="#a74927e6bf86dae4692a942b02375e7d9">Obj</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binaryelfbuilder/#a4fbb2863fa824a058d66949d4431e0e2">llvm::objcopy::elf::BinaryELFBuilder::build</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexelfbuilder/#abd1fb9c0a732defd1d594da8794d32a7">llvm::objcopy::elf::IHexELFBuilder::build</a>.</p>

</div>
</div>

### addSymTab() {#a62e4794b651253df24ca9cd5fe61340a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolTableSection * BasicELFBuilder::addSymTab (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/stringtablesection">StringTableSection</a> * StrTab)</td>
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



<p>Declaration at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 1289 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#adb56e51395271bed841ca39f9f997f3e">llvm::objcopy::elf::SectionBase::Index</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6ca324c9086862d837e0593199d1e58e">llvm::objcopy::elf::SectionBase::Name</a> and <a href="#a74927e6bf86dae4692a942b02375e7d9">Obj</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binaryelfbuilder/#a4fbb2863fa824a058d66949d4431e0e2">llvm::objcopy::elf::BinaryELFBuilder::build</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexelfbuilder/#abd1fb9c0a732defd1d594da8794d32a7">llvm::objcopy::elf::IHexELFBuilder::build</a>.</p>

</div>
</div>

### initFileHeader() {#a53156fa08af05b511e0e9c0f476c1545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicELFBuilder::initFileHeader ()</td>
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



<p>Declaration at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4afc97566f2e931d4d0e88c4425e88b56b">llvm::ELF::ELFOSABI_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da5d026a070d8ca9bff483536f60b88124">llvm::ELF::EM_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aadbc5ef54c920f724d4e267f41d2c00aaba0cdd056685bc8fe4fab01da806afdc">llvm::ELF::ET_REL</a> and <a href="#a74927e6bf86dae4692a942b02375e7d9">Obj</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binaryelfbuilder/#a4fbb2863fa824a058d66949d4431e0e2">llvm::objcopy::elf::BinaryELFBuilder::build</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexelfbuilder/#abd1fb9c0a732defd1d594da8794d32a7">llvm::objcopy::elf::IHexELFBuilder::build</a>.</p>

</div>
</div>

### initHeaderSegment() {#a5598313252548691a55e2e29dbe69e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicELFBuilder::initHeaderSegment ()</td>
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



<p>Declaration at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 1279 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>Reference <a href="#a74927e6bf86dae4692a942b02375e7d9">Obj</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binaryelfbuilder/#a4fbb2863fa824a058d66949d4431e0e2">llvm::objcopy::elf::BinaryELFBuilder::build</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexelfbuilder/#abd1fb9c0a732defd1d594da8794d32a7">llvm::objcopy::elf::IHexELFBuilder::build</a>.</p>

</div>
</div>

### initSections() {#ac573c6c02b8dea91c6c3831eac21b0ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BasicELFBuilder::initSections ()</td>
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



<p>Declaration at line 1059 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/section/#a3995c394cc393dfab7483f6a52f760ef">llvm::objcopy::elf::Section::initialize</a>, <a href="#a74927e6bf86dae4692a942b02375e7d9">Obj</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binaryelfbuilder/#a4fbb2863fa824a058d66949d4431e0e2">llvm::objcopy::elf::BinaryELFBuilder::build</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexelfbuilder/#abd1fb9c0a732defd1d594da8794d32a7">llvm::objcopy::elf::IHexELFBuilder::build</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Obj {#a74927e6bf86dae4692a942b02375e7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Object&gt; llvm::objcopy::elf::BasicELFBuilder::Obj</td>
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



<p>Definition at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="#a46bf4a5a8c7c2180cc146f232e4f7f6d">addStrTab</a>, <a href="#a62e4794b651253df24ca9cd5fe61340a">addSymTab</a>, <a href="#ae3d133a84d7e7fda64f90b76c9caceda">BasicELFBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binaryelfbuilder/#a4fbb2863fa824a058d66949d4431e0e2">llvm::objcopy::elf::BinaryELFBuilder::build</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexelfbuilder/#abd1fb9c0a732defd1d594da8794d32a7">llvm::objcopy::elf::IHexELFBuilder::build</a>, <a href="#a53156fa08af05b511e0e9c0f476c1545">initFileHeader</a>, <a href="#a5598313252548691a55e2e29dbe69e8c">initHeaderSegment</a> and <a href="#ac573c6c02b8dea91c6c3831eac21b0ea">initSections</a>.</p>

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
