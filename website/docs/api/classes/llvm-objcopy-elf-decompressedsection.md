---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/elf/decompressedsection
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DecompressedSection` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::elf::DecompressedSection { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ObjCopy/ELF/ELFObject.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase">SectionBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa71155be2e4826ac2de050eb4f42756a">DecompressedSection</a> (const CompressedSection &amp;Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267b724d558bfbc8022ff8b42f669f9c">accept</a> (SectionVisitor &amp;Visitor) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7d087a23b0ebcd1963ce594a759762b">accept</a> (MutableSectionVisitor &amp;Visitor) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461b8c4c1b12aa28c900c5b6c2a2e69a">ChType</a></td>
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


<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DecompressedSection() {#aa71155be2e4826ac2de050eb4f42756a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::elf::DecompressedSection::DecompressedSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/compressedsection">CompressedSection</a> &amp; Sec)</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a964962447545ebfaaffa4deacfbf3940">llvm::objcopy::elf::SectionBase::Align</a>, <a href="#a461b8c4c1b12aa28c900c5b6c2a2e69a">ChType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#ac6aef8715c902e0061de80e3d18dd566ab61b2d6c6fa62903b882aaa53452c111">llvm::objcopy::ELF</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a68df71b92d4532e6ceabfb620f5ba02c">llvm::objcopy::elf::SectionBase::Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/compressedsection/#a8a492828f1abd98d02afebfa9da93172">llvm::objcopy::elf::CompressedSection::getDecompressedAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/compressedsection/#a4eea320678ea3ac07935006ac0c5c7d4">llvm::objcopy::elf::CompressedSection::getDecompressedSize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#aab7a7cefc3d8c0fac70539c18b84bfcd">llvm::objcopy::elf::SectionBase::OriginalFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#aa679879f673113d848d520be5db2cc2a">llvm::objcopy::elf::SectionBase::SectionBase</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6fefaf0cf6568001708fc6f9b862687a">llvm::objcopy::elf::SectionBase::Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accept() {#a267b724d558bfbc8022ff8b42f669f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DecompressedSection::accept (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionvisitor">SectionVisitor</a> &amp; Visitor)</td>
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



<p>Declaration at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionvisitor/#a1d8c208fbac3f796c3aa684de7f98a24">llvm::objcopy::elf::SectionVisitor::visit</a>.</p>

</div>
</div>

### accept() {#af7d087a23b0ebcd1963ce594a759762b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DecompressedSection::accept (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/mutablesectionvisitor">MutableSectionVisitor</a> &amp; Visitor)</td>
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



<p>Declaration at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/mutablesectionvisitor/#ad53fb5162bf876b8f1417b42ba8cf4aa">llvm::objcopy::elf::MutableSectionVisitor::visit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ChType {#a461b8c4c1b12aa28c900c5b6c2a2e69a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::objcopy::elf::DecompressedSection::ChType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="#aa71155be2e4826ac2de050eb4f42756a">DecompressedSection</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a9c48163b33da5da66af7a1e8f4deb637">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>.</p>

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
