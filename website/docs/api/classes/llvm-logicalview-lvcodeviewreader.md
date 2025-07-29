---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvcodeviewreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LVCodeViewReader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVCodeViewReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">llvm/DebugInfo/LogicalView/Readers/LVCodeViewReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader">LVBinaryReader</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6bb9fa720ff3c75b80d6f1f7f15cfa">LVModules</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff16e3a62f8e78112d81a200793e63b">RelocMapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">llvm::object::coff_section</a> *, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">llvm::object::RelocationRef</a> &gt; &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a709b10becad709f13dc39cc2ce45770a">LVTypeVisitor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdc853f3c302ada78aac525c62bca387">LVSymbolVisitor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c0f7389f62dde9b3a06576fb47b5f6">LVSymbolVisitorDelegate</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23b37c97171aa3bea064f4f767121f75">LVCodeViewReader</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1bd6b089058360736e027da1171157">LVCodeViewReader</a> (StringRef Filename, StringRef FileFormatName, llvm::object::COFFObjectFile &amp;Obj, ScopedPrinter &amp;W, StringRef ExePath)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7919065cf881851a0edff7ae9fbeb1">LVCodeViewReader</a> (StringRef Filename, StringRef FileFormatName, llvm::pdb::PDBFile &amp;Pdb, ScopedPrinter &amp;W, StringRef ExePath)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3081b57af6055cf3552eaf91e56f81f">LVCodeViewReader</a> (const LVCodeViewReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25277cd4314887f2570b999c12fcc2b">~LVCodeViewReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader">LVCodeViewReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f57c7bb333e1c34b8c452ab1ba316c9">operator=</a> (const LVCodeViewReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13963603763a7de1b2dedf831e687a26">getLinkageName</a> (const llvm::object::coff_section *CoffSection, uint32_t RelocOffset, uint32_t Offset, StringRef *RelocSym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094df7fcba77b7546390a66bc8ebfcbe">addModule</a> (LVScope *Scope)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa497117ee37def0eecd4737872ba9cd5">getScopeForModule</a> (uint32_t Modi)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c7683b6e84562ebcc173bd25a76deb">getRegisterName</a> (LVSmall Opcode, ArrayRef&lt; uint64_t &gt; Operands) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af383e0dc7e81bbf2e0583590dd9a4066">isSystemEntry</a> (LVElement *Element, StringRef Name) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a233a5f5615d011f6fe8856c96ff9d66e">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a11dbf5d82a23a68332b1e320d5470">printRecords</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f0f7c6aa119cd6028907469fc3053d">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b600452f45c702aaffaaeb6c4182c0">createScopes</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff98f67d98b64c4ea5b3ed912838e83b">sortScopes</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa82db852793b65b7419ee5c1462c3367">loadTargetInfo</a> (const object::ObjectFile &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd701397a22c12836d8fd608534f0b5f">loadTargetInfo</a> (const llvm::pdb::PDBFile &amp;Pdb)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44a082996bf7f1d98ed4caa4e5d0a285">mapRangeAddress</a> (const object::ObjectFile &amp;Obj, const object::SectionRef &amp;Section, bool IsComdat) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">llvm::object::COFFObjectFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a933ea4c4d8737ac457284944ae8d98f6">getObj</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">llvm::pdb::PDBFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf55c2c8666a0be124f595e20782c584">getPdb</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad976c1aee5e1658392f0d9ce2ec6680c">isObj</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a231bf73a0aa83b126392f7b38f370dfd">isPdb</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a419aa5914a8a1318385857ba23451b">getFileName</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897ad665cac45af31c5f7382197647f6">types</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5bd227fd91d520cd3a0cf3679e08f27">ids</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c911603d9ac4fb4003e7d0b59c9bdeb">getFileNameForFileOffset</a> (uint32_t FileOffset, const llvm::pdb::SymbolGroup *SG=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4c7e960f703a610ecfb037afbc0aab">printRelocatedField</a> (StringRef Label, const llvm::object::coff_section *CoffSection, uint32_t RelocOffset, uint32_t Offset, StringRef *RelocSym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03523aa1800197516c201b4f5a2de22b">printFileNameForOffset</a> (StringRef Label, uint32_t FileOffset, const llvm::pdb::SymbolGroup *SG=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d033f8a53d4d459493eba3a351957fd">loadPrecompiledObject</a> (PrecompRecord &amp;Precomp, CVTypeArray &amp;CVTypesObj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f2b2b66eeddb2f4e687aa5f400da09">loadTypeServer</a> (TypeServer2Record &amp;TS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ab24d3ecb706e260004cec407d8b67">traverseTypes</a> (llvm::pdb::PDBFile &amp;Pdb, LazyRandomTypeCollection &amp;Types, LazyRandomTypeCollection &amp;Ids)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a94c2e51a4c7707a2b07c728f8e386">collectInlineeInfo</a> (DebugInlineeLinesSubsectionRef &amp;Lines, const llvm::pdb::SymbolGroup *SG=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d40e73546e3852daed633aca6fbae81">cacheRelocations</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c7778a8e48ff9a5e21604d8f399ed0e">resolveSymbol</a> (const llvm::object::coff_section *CoffSection, uint64_t Offset, llvm::object::SymbolRef &amp;Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af766df5e3aa175064376c64c989ad346">resolveSymbolName</a> (const llvm::object::coff_section *CoffSection, uint64_t Offset, StringRef &amp;Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae158a2bc4d598adde455ce09c68042de">traverseTypeSection</a> (StringRef SectionName, const llvm::object::SectionRef &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318db524d19f816784729366eed89935">traverseSymbolSection</a> (StringRef SectionName, const llvm::object::SectionRef &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e411179090f9d9ca8157b2042db4d21">traverseInlineeLines</a> (StringRef Subsection)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3129076b216a299c015c7bb62bc72461">traverseSymbolsSubsection</a> (StringRef Subsection, const llvm::object::SectionRef &amp;Section, StringRef SectionContents)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab53fd45725f6a28844a1bb29ce1027e8">initializeFileAndStringTables</a> (BinaryStreamReader &amp;Reader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a .debug$S section, find the string table and file checksum table. <a href="#ab53fd45725f6a28844a1bb29ce1027e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87eda77d871aa23649cdda42632b03b8">createLines</a> (const FixedStreamArray&lt; LineNumberEntry &gt; &amp;LineNumbers, LVAddress Addendum, uint32_t Segment, uint32_t Begin, uint32_t Size, uint32_t NameIndex, const llvm::pdb::SymbolGroup *SG=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a583a2b510eafeb8943c671463d536d">createScopes</a> (llvm::object::COFFObjectFile &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8366dd3848efc18ce8fe482ae6bdc58">createScopes</a> (llvm::pdb::PDBFile &amp;Pdb)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf16968a2770ac02f9059563040c8b26">processModule</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LVModules</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa5babbf0c0cd37a1b319bc089f26489">Modules</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile">llvm::pdb::InputFile</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247e2d36ff60d2d1083612e7f0f4b1e3">Input</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile">llvm::pdb::InputFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae65c2aa3b4660dd86339a2cd0280d93">TypeServer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa941cf07d6ec8952271bb31126adc9ee">PrecompHeader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0defd0a1f69c343b058781b429638904">BuffOrErr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0623277ebc8f5f3c6f11abb619ae8523">MemBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsession">llvm::pdb::IPDBSession</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af33ef479dd0e396ff6d08bb5d34041">Session</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">llvm::pdb::NativeSession</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab062b2776fab0fea2f88e154ceada709">PdbSession</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8807e861ba8bbe7ae0310c08cb0e0e2e">BuilderAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/appendingtypetablebuilder">AppendingTypeTableBuilder</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d1359b676cfed9f53d3292741d35b5">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/binaryitemstream">BinaryItemStream</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae83463aa297fa33ea8cb0a4550da7651">ItemStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3462b2fbb098a1aa37575508d04dd8f1">ReaderPrecomp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a916fb75a6227d85a0a5ba60eed2c617c">TypeArray</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af531ed0ba1c612856aac7fde7784d58c">TypeStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a499d003b91763eb066c8f17fb7fe20bc">CVTypesPrecomp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4fb8094cdbc7de92809f96fc3c2bca">BinaryBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/binary">llvm::object::Binary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1295432123b8585d6c4b4f6592b0eb4">BinaryExecutable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f1b7bb5fe936b71f8eafeacbe96879">ExePath</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b53bb9faad5c73a478c50721a5236f7">CurrentOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa93f74c1d3c676033f1599d99864b8cc">CurrentModule</a> = -1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">RelocMapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8cbd286ffd759d71f8242f8c98ff511">RelocMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor">LVLogicalVisitor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21385957272f12adb3e4eb7a3b51ef8b">LogicalVisitor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsectionref">DebugChecksumsSubsectionRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e47795ee6424250dfa1536d64e2ae45">CVFileChecksumTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref">DebugStringTableSubsectionRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa155da513fd7245f5e71067afa7f7c94">CVStringTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9157acbaccd4abe39c0aa7c46e9b496">getSymbolKindName</a> (SymbolKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d3f3ac649e5dd9f636db1777b5778af">formatRegisterId</a> (RegisterId Register, CPUType CPU)</td>
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


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LVModules {#acb6bb9fa720ff3c75b80d6f1f7f15cfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVCodeViewReader::LVModules =  std::vector&lt;LVScope *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### RelocMapTy {#aeff16e3a62f8e78112d81a200793e63b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVCodeViewReader::RelocMapTy =  DenseMap&lt;const llvm::object::coff_section *,
                              std::vector&lt;llvm::object::RelocationRef&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LVSymbolVisitor {#abdc853f3c302ada78aac525c62bca387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor">LVSymbolVisitor</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>Reference <a href="#abdc853f3c302ada78aac525c62bca387">LVSymbolVisitor</a>.</p>


<p>Referenced by <a href="#abdc853f3c302ada78aac525c62bca387">LVSymbolVisitor</a>.</p>

</div>
</div>

### LVSymbolVisitorDelegate {#ae1c0f7389f62dde9b3a06576fb47b5f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitordelegate">LVSymbolVisitorDelegate</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>References <a href="#ae1c0f7389f62dde9b3a06576fb47b5f6">LVSymbolVisitorDelegate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6ab693cea68a050d89a00c376652df1c5e">llvm::codeview::Pdb</a>.</p>


<p>Referenced by <a href="#ae1c0f7389f62dde9b3a06576fb47b5f6">LVSymbolVisitorDelegate</a>.</p>

</div>
</div>

### LVTypeVisitor {#a709b10becad709f13dc39cc2ce45770a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor">LVTypeVisitor</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>Reference <a href="#a709b10becad709f13dc39cc2ce45770a">LVTypeVisitor</a>.</p>


<p>Referenced by <a href="#a709b10becad709f13dc39cc2ce45770a">LVTypeVisitor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LVCodeViewReader() {#a23b37c97171aa3bea064f4f767121f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVCodeViewReader::LVCodeViewReader ()</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>Referenced by <a href="#ad3081b57af6055cf3552eaf91e56f81f">LVCodeViewReader</a> and <a href="#a8f57c7bb333e1c34b8c452ab1ba316c9">operator=</a>.</p>

</div>
</div>

### LVCodeViewReader() {#a5a1bd6b089058360736e027da1171157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVCodeViewReader::LVCodeViewReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileFormatName, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">llvm::object::COFFObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExePath)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833ca4fa2ac5353638195d4ce3bc48a5a9db7">llvm::logicalview::COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a30c36ab397c2a31a605e88a0a476ee9c">llvm::logicalview::LVReader::FileFormatName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa1351017ac6423911223bc19a8cb7c653">llvm::logicalview::Filename</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a77d562b41fb3c6d478f38b73cfa44ab3">llvm::logicalview::LVBinaryReader::LVBinaryReader</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a05c1edcb51769b9ed74087532906b12e">llvm::logicalview::LVReader::W</a>.</p>

</div>
</div>

### LVCodeViewReader() {#aca7919065cf881851a0edff7ae9fbeb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVCodeViewReader::LVCodeViewReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileFormatName, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">llvm::pdb::PDBFile</a> &amp; Pdb, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExePath)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833ca4fa2ac5353638195d4ce3bc48a5a9db7">llvm::logicalview::COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a30c36ab397c2a31a605e88a0a476ee9c">llvm::logicalview::LVReader::FileFormatName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa1351017ac6423911223bc19a8cb7c653">llvm::logicalview::Filename</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a77d562b41fb3c6d478f38b73cfa44ab3">llvm::logicalview::LVBinaryReader::LVBinaryReader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6ab693cea68a050d89a00c376652df1c5e">llvm::codeview::Pdb</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a05c1edcb51769b9ed74087532906b12e">llvm::logicalview::LVReader::W</a>.</p>

</div>
</div>

### LVCodeViewReader() {#ad3081b57af6055cf3552eaf91e56f81f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVCodeViewReader::LVCodeViewReader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader">LVCodeViewReader</a> &amp;)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>Reference <a href="#a23b37c97171aa3bea064f4f767121f75">LVCodeViewReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LVCodeViewReader() {#ae25277cd4314887f2570b999c12fcc2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVCodeViewReader::~LVCodeViewReader ()</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefadfd0a82c4bf37b1e90b690a22a20692e">llvm::logicalview::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a8f57c7bb333e1c34b8c452ab1ba316c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVCodeViewReader &amp; llvm::logicalview::LVCodeViewReader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader">LVCodeViewReader</a> &amp;)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>Reference <a href="#a23b37c97171aa3bea064f4f767121f75">LVCodeViewReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addModule() {#a094df7fcba77b7546390a66bc8ebfcbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVCodeViewReader::addModule (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### dump() {#a03f0f7c6aa119cd6028907469fc3053d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVCodeViewReader::dump ()</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a233a5f5615d011f6fe8856c96ff9d66e">print</a>.</p>

</div>
</div>

### getLinkageName() {#a13963603763a7de1b2dedf831e687a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVCodeViewReader::getLinkageName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">llvm::object::coff_section</a> * CoffSection, uint32_t RelocOffset, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> * RelocSym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefadfd0a82c4bf37b1e90b690a22a20692e">llvm::logicalview::Offset</a>.</p>

</div>
</div>

### getRegisterName() {#a50c7683b6e84562ebcc173bd25a76deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LVCodeViewReader::getRegisterName (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ab9502425858a198bcbe9227a823f8aea">LVSmall</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Operands)</td>
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



<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>


<p>References <a href="#a2d3f3ac649e5dd9f636db1777b5778af">formatRegisterId</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a4dd83f4a260a18452465d5b20bde0f5e">llvm::logicalview::LVReader::getCompileUnitCPUType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa0ba7583639a274c434bbe6ef797115a4">llvm::logicalview::Register</a>.</p>

</div>
</div>

### getScopeForModule() {#aa497117ee37def0eecd4737872ba9cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScope * llvm::logicalview::LVCodeViewReader::getScopeForModule (uint32_t Modi)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### isSystemEntry() {#af383e0dc7e81bbf2e0583590dd9a4066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LVCodeViewReader::isSystemEntry (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a08e140d603b53c440c54cffc85131c8f">Find</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>

</div>
</div>

### print() {#a233a5f5615d011f6fe8856c96ff9d66e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVCodeViewReader::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ae3b66787d42fd33ae1c2fe2c5fd7225c">llvm::logicalview::LVReader::OS</a>.</p>


<p>Referenced by <a href="#a03f0f7c6aa119cd6028907469fc3053d">dump</a>.</p>

</div>
</div>

### printRecords() {#a24a11dbf5d82a23a68332b1e320d5470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVCodeViewReader::printRecords (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ae3b66787d42fd33ae1c2fe2c5fd7225c">llvm::logicalview::LVReader::OS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createScopes() {#ab2b600452f45c702aaffaaeb6c4182c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::createScopes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>


<p>References <a href="#ab2b600452f45c702aaffaaeb6c4182c0">createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#af75cb2856d2563990ed489c38b63a5c3">llvm::logicalview::LVReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a30c36ab397c2a31a605e88a0a476ee9c">llvm::logicalview::LVReader::FileFormatName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aca8db53bfaede35c8940fceb72b495aa">llvm::logicalview::LVReader::Root</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a05c1edcb51769b9ed74087532906b12e">llvm::logicalview::LVReader::W</a>.</p>


<p>Referenced by <a href="#ab2b600452f45c702aaffaaeb6c4182c0">createScopes</a>.</p>

</div>
</div>

### sortScopes() {#aff98f67d98b64c4ea5b3ed912838e83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVCodeViewReader::sortScopes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aca8db53bfaede35c8940fceb72b495aa">llvm::logicalview::LVReader::Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cacheRelocations() {#a5d40e73546e3852daed633aca6fbae81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVCodeViewReader::cacheRelocations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### collectInlineeInfo() {#a00a94c2e51a4c7707a2b07c728f8e386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::collectInlineeInfo (<a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsectionref">DebugInlineeLinesSubsectionRef</a> &amp; Lines, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolgroup">llvm::pdb::SymbolGroup</a> * SG=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### createLines() {#a87eda77d871aa23649cdda42632b03b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::createLines (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/linenumberentry">LineNumberEntry</a> &gt; &amp; LineNumbers, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a> Addendum, uint32_t Segment, uint32_t Begin, uint32_t Size, uint32_t NameIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolgroup">llvm::pdb::SymbolGroup</a> * SG=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### createScopes() {#a8a583a2b510eafeb8943c671463d536d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::createScopes (<a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">llvm::object::COFFObjectFile</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### createScopes() {#ab8366dd3848efc18ce8fe482ae6bdc58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::createScopes (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">llvm::pdb::PDBFile</a> &amp; Pdb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 894 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### getFileName() {#a7a419aa5914a8a1318385857ba23451b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::logicalview::LVCodeViewReader::getFileName ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### getFileNameForFileOffset() {#a8c911603d9ac4fb4003e7d0b59c9bdeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; LVCodeViewReader::getFileNameForFileOffset (uint32_t FileOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolgroup">llvm::pdb::SymbolGroup</a> * SG=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### getObj() {#a933ea4c4d8737ac457284944ae8d98f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::COFFObjectFile &amp; llvm::logicalview::LVCodeViewReader::getObj ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### getPdb() {#abf55c2c8666a0be124f595e20782c584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::pdb::PDBFile &amp; llvm::logicalview::LVCodeViewReader::getPdb ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### ids() {#ae5bd227fd91d520cd3a0cf3679e08f27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection &amp; llvm::logicalview::LVCodeViewReader::ids ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### initializeFileAndStringTables() {#ab53fd45725f6a28844a1bb29ce1027e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::initializeFileAndStringTables (<a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; Reader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a .debug$S section, find the string table and file checksum table.</p>


<p>This function taken from (COFFDumper.cpp). TODO: It can be moved to the <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> library.</p>


<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### isObj() {#ad976c1aee5e1658392f0d9ce2ec6680c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVCodeViewReader::isObj ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### isPdb() {#a231bf73a0aa83b126392f7b38f370dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVCodeViewReader::isPdb ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### loadPrecompiledObject() {#a8d033f8a53d4d459493eba3a351957fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::loadPrecompiledObject (<a href="/web-llvm/docs/api/classes/llvm/codeview/precomprecord">PrecompRecord</a> &amp; Precomp, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; CVTypesObj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### loadTargetInfo() {#aa82db852793b65b7419ee5c1462c3367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::loadTargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 1178 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### loadTargetInfo() {#abd701397a22c12836d8fd608534f0b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::loadTargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">llvm::pdb::PDBFile</a> &amp; Pdb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### loadTypeServer() {#a16f2b2b66eeddb2f4e687aa5f400da09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::loadTypeServer (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeserver2record">TypeServer2Record</a> &amp; TS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### mapRangeAddress() {#a44a082996bf7f1d98ed4caa4e5d0a285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVCodeViewReader::mapRangeAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">object::SectionRef</a> &amp; Section, bool IsComdat)</td>
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



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### printFileNameForOffset() {#a03523aa1800197516c201b4f5a2de22b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::printFileNameForOffset (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Label, uint32_t FileOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolgroup">llvm::pdb::SymbolGroup</a> * SG=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### printRelocatedField() {#aed4c7e960f703a610ecfb037afbc0aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVCodeViewReader::printRelocatedField (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Label, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">llvm::object::coff_section</a> * CoffSection, uint32_t RelocOffset, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> * RelocSym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### processModule() {#acf16968a2770ac02f9059563040c8b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::processModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 1114 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### resolveSymbol() {#a0c7778a8e48ff9a5e21604d8f399ed0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::resolveSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">llvm::object::coff_section</a> * CoffSection, uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">llvm::object::SymbolRef</a> &amp; Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### resolveSymbolName() {#af766df5e3aa175064376c64c989ad346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::resolveSymbolName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">llvm::object::coff_section</a> * CoffSection, uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### traverseInlineeLines() {#a2e411179090f9d9ca8157b2042db4d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::traverseInlineeLines (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Subsection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### traverseSymbolSection() {#a318db524d19f816784729366eed89935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::traverseSymbolSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">llvm::object::SectionRef</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### traverseSymbolsSubsection() {#a3129076b216a299c015c7bb62bc72461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::traverseSymbolsSubsection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Subsection, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">llvm::object::SectionRef</a> &amp; Section, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionContents)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### traverseTypes() {#a65ab24d3ecb706e260004cec407d8b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::traverseTypes (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">llvm::pdb::PDBFile</a> &amp; Pdb, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &amp; Types, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &amp; Ids)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### traverseTypeSection() {#ae158a2bc4d598adde455ce09c68042de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVCodeViewReader::traverseTypeSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">llvm::object::SectionRef</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>

</div>
</div>

### types() {#a897ad665cac45af31c5f7382197647f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection &amp; llvm::logicalview::LVCodeViewReader::types ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BinaryBuffer {#aae4fb8094cdbc7de92809f96fc3c2bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::logicalview::LVCodeViewReader::BinaryBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### BinaryExecutable {#af1295432123b8585d6c4b4f6592b0eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;llvm::object::Binary&gt; llvm::logicalview::LVCodeViewReader::BinaryExecutable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### BuffOrErr {#a0defd0a1f69c343b058781b429638904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt;std::unique_ptr&lt;MemoryBuffer&gt; &gt; llvm::logicalview::LVCodeViewReader::BuffOrErr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### Builder {#aa0d1359b676cfed9f53d3292741d35b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AppendingTypeTableBuilder&gt; llvm::logicalview::LVCodeViewReader::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### BuilderAllocator {#a8807e861ba8bbe7ae0310c08cb0e0e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::logicalview::LVCodeViewReader::BuilderAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### CurrentModule {#aa93f74c1d3c676033f1599d99864b8cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::logicalview::LVCodeViewReader::CurrentModule = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### CurrentOffset {#a4b53bb9faad5c73a478c50721a5236f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVOffset llvm::logicalview::LVCodeViewReader::CurrentOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### CVFileChecksumTable {#a7e47795ee6424250dfa1536d64e2ae45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugChecksumsSubsectionRef llvm::logicalview::LVCodeViewReader::CVFileChecksumTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### CVStringTable {#aa155da513fd7245f5e71067afa7f7c94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugStringTableSubsectionRef llvm::logicalview::LVCodeViewReader::CVStringTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### CVTypesPrecomp {#a499d003b91763eb066c8f17fb7fe20bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVTypeArray llvm::logicalview::LVCodeViewReader::CVTypesPrecomp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### ExePath {#a74f1b7bb5fe936b71f8eafeacbe96879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::logicalview::LVCodeViewReader::ExePath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### Input {#a247e2d36ff60d2d1083612e7f0f4b1e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::pdb::InputFile llvm::logicalview::LVCodeViewReader::Input</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### ItemStream {#ae83463aa297fa33ea8cb0a4550da7651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BinaryItemStream&lt;CVType&gt; &gt; llvm::logicalview::LVCodeViewReader::ItemStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### LogicalVisitor {#a21385957272f12adb3e4eb7a3b51ef8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVLogicalVisitor llvm::logicalview::LVCodeViewReader::LogicalVisitor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### MemBuffer {#a0623277ebc8f5f3c6f11abb619ae8523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::logicalview::LVCodeViewReader::MemBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### Modules {#afa5babbf0c0cd37a1b319bc089f26489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVModules llvm::logicalview::LVCodeViewReader::Modules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### PdbSession {#ab062b2776fab0fea2f88e154ceada709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;llvm::pdb::NativeSession&gt; llvm::logicalview::LVCodeViewReader::PdbSession</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### PrecompHeader {#aa941cf07d6ec8952271bb31126adc9ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;LazyRandomTypeCollection&gt; llvm::logicalview::LVCodeViewReader::PrecompHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### ReaderPrecomp {#a3462b2fbb098a1aa37575508d04dd8f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BinaryStreamReader&gt; llvm::logicalview::LVCodeViewReader::ReaderPrecomp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### RelocMap {#ac8cbd286ffd759d71f8242f8c98ff511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RelocMapTy llvm::logicalview::LVCodeViewReader::RelocMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### Session {#a7af33ef479dd0e396ff6d08bb5d34041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;llvm::pdb::IPDBSession&gt; llvm::logicalview::LVCodeViewReader::Session</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### TypeArray {#a916fb75a6227d85a0a5ba60eed2c617c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CVType&gt; llvm::logicalview::LVCodeViewReader::TypeArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### TypeServer {#aae65c2aa3b4660dd86339a2cd0280d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;llvm::pdb::InputFile&gt; llvm::logicalview::LVCodeViewReader::TypeServer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

### TypeStream {#af531ed0ba1c612856aac7fde7784d58c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVTypeArray llvm::logicalview::LVCodeViewReader::TypeStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### formatRegisterId() {#a2d3f3ac649e5dd9f636db1777b5778af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LVCodeViewReader::formatRegisterId (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a18efaabef8a962bb9f48589ec97b5be9">RegisterId</a> Register, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3a314f44c015362563c5333db978173d">CPUType</a> CPU)</td>
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



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3a314f44c015362563c5333db978173dab9b55c80d095761ac7757ced0fedadc4">llvm::codeview::ARM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3a314f44c015362563c5333db978173da28664eae29238b4cf66b337bcef6845e">llvm::codeview::ARMNT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa0ba7583639a274c434bbe6ef797115a4">llvm::logicalview::Register</a>.</p>


<p>Referenced by <a href="#a50c7683b6e84562ebcc173bd25a76deb">getRegisterName</a>.</p>

</div>
</div>

### getSymbolKindName() {#ab9157acbaccd4abe39c0aa7c46e9b496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef LVCodeViewReader::getSymbolKindName (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">SymbolKind</a> Kind)</td>
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



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a03d93ef611f1c51f7fa6da9281d2845a">llvm::logicalview::LVLogicalVisitor::printRecords</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewreader-h">LVCodeViewReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewreader-cpp">LVCodeViewReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
