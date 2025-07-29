---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/elffile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFFile` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;class ELFT&gt;
class llvm::object::ELFFile&lt;ELFT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">llvm/Object/ELF.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aded5f2aa590cbcfe256b517b31aba812">WarningHandler</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp;Msg)&gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af7aa9ddd837c6041eb52bd45cae11289">RelsOrRelas</a> = std::pair&lt; std::vector&lt; Elf_Rel &gt;, std::vector&lt; Elf_Rela &gt; &gt;</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a54dee86341ca720bda5b7493841671b0">ELFFile</a> (StringRef Object)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6cf194b594fa748bf8cd72df35d6479">base</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8693389f2e062787589d31dbf6c304ee">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6e33078a7d937377faff3c10d2e1efaa">getBufSize</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Ehdr &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02cea47a954fd499a8dc8d80b75935ee">getHeader</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fe4eac160aa377a7f8e1edfcc4a17dd">getEntry</a> (uint32_t Section, uint32_t Entry) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a98e19eaf03c9744a18996776d77d0ee1">getEntry</a> (const Elf_Shdr &amp;Section, uint32_t Entry) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a20ac73b763595fb7dd3d76f6a221408c">getVersionDefinitions</a> (const Elf_Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/verdef">VerDef</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d7f36df9f1e78161aa1117443ec74e1">getVersionDependencies</a> (const Elf_Shdr &amp;Sec, WarningHandler WarnHandler=&amp;defaultWarningHandler) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/verneed">VerNeed</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a56343d577008471112adcb121718f1b2">getSymbolVersionByIndex</a> (uint32_t SymbolVersionIndex, bool &amp;IsDefault, SmallVector&lt; std::optional&lt; VersionEntry &gt;, 0 &gt; &amp;VersionMap, std::optional&lt; bool &gt; IsSymHidden) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add75d06af5256ffc8ac789721f09ef4e">getStringTable</a> (const Elf_Shdr &amp;Section, WarningHandler WarnHandler=&amp;defaultWarningHandler) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6a6612a17f1ed83c751bab1ed91ce355">getStringTableForSymtab</a> (const Elf_Shdr &amp;Section) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adfb3d16a4f2cb55b615809b97c5e6b13">getStringTableForSymtab</a> (const Elf_Shdr &amp;Section, Elf_Shdr_Range Sections) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0bbb4e885d31a6ae8eb4486532fb3108">getLinkAsStrtab</a> (const typename ELFT::Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26eb5a3830fae63f1263c58b0fb79621">getSHNDXTable</a> (const Elf_Shdr &amp;Section) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; Elf_Word &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b7e5aceb97b03a61eee57e8a2a4889c">getSHNDXTable</a> (const Elf_Shdr &amp;Section, Elf_Shdr_Range Sections) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; Elf_Word &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e0db63318e9923b354d95e0391c05db">getDynSymtabSize</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines the number of dynamic symbols. <a href="#a8e0db63318e9923b354d95e0391c05db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad45bb5df167eb8cac974b25d4c4ff5cd">getRelocationTypeName</a> (uint32_t Type) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6ff64d4cf042294e0aa84c193e5061f7">getRelocationTypeName</a> (uint32_t Type, SmallVectorImpl&lt; char &gt; &amp;Result) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a504594efdb5d22d6233ba933e550bc2a">getRelativeRelocationType</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26c25aaa2bbfe08a9e398cfa15769616">getDynamicTagAsString</a> (unsigned Arch, uint64_t Type) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8208b85e5ab2b28adf34fa92b116103">getDynamicTagAsString</a> (uint64_t Type) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a815105a2af24d7dffc158173b5324272">getRelocationSymbol</a> (const Elf_Rel &amp;Rel, const Elf_Shdr *SymTab) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Sym * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the symbol for a given relocation. <a href="#a815105a2af24d7dffc158173b5324272">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb221ffeffa3ec7eaaa8eecf37b0146d">loadVersionMap</a> (const Elf_Shdr *VerNeedSec, const Elf_Shdr *VerDefSec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/versionentry">VersionEntry</a> &gt;, 0 &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac9e50507b6d18dc2f18508ff067e140e">isLE</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9ee8e7123cfc8843e8558e604ad56b4">isMipsELF64</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#accd50e330d567f984dfff0557e49e044">isMips64EL</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab64e03f049c8588f24e0ec69a568aef9">sections</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; Elf_Shdr_Range &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa438ee4f7cc143674ffb81a41c01fcb2">dynamicEntries</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; Elf_Dyn_Range &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf0867b6082e1e0408b1b5d8301f27e2">toMappedAddr</a> (uint64_t VAddr, WarningHandler WarnHandler=&amp;defaultWarningHandler) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29639dfbcf056708f68f1cc4b2d8c237">symbols</a> (const Elf_Shdr *Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; Elf_Sym_Range &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63434f54fe78bfe55d1c3de263359e6f">relas</a> (const Elf_Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; Elf_Rela_Range &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed56eba38ac0877432634af5d02d282f">rels</a> (const Elf_Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; Elf_Rel_Range &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abfc0395a4aa4e229de6ff4f2c8c8f63c">relrs</a> (const Elf_Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; Elf_Relr_Range &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6fe298454e5320427d65c40da7981aa">decode_relrs</a> (Elf_Relr_Range relrs) const -&gt; std::vector&lt; Elf_Rel &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa1027abe2321f5eee653435e5305ddab">getCrelHeader</a> (ArrayRef&lt; uint8_t &gt; Content) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85a04b6f06b8f42bce6a666eee85d745">decodeCrel</a> (ArrayRef&lt; uint8_t &gt; Content) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#af7aa9ddd837c6041eb52bd45cae11289">RelsOrRelas</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae2039f20cc8322c8af90fb0dec7bb772">crels</a> (const Elf_Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#af7aa9ddd837c6041eb52bd45cae11289">RelsOrRelas</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0752ad646759ea4a034a218da571ab8b">android_relas</a> (const Elf_Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; Elf_Rela &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a685264b0f25cd162e8b4e85365aee004">program_headers</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; Elf_Phdr_Range &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterate over program header table. <a href="#a685264b0f25cd162e8b4e85365aee004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Elf_Note_Iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d91616c8a62b5988aa2570be36c7912">notes_begin</a> (const Elf_Phdr &amp;Phdr, Error &amp;Err) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator over notes in a program header. <a href="#a5d91616c8a62b5988aa2570be36c7912">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Elf_Note_Iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a472b2e829986b644129759fb3249df7c">notes_begin</a> (const Elf_Shdr &amp;Shdr, Error &amp;Err) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator over notes in a section. <a href="#a472b2e829986b644129759fb3249df7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Elf_Note_Iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acea5c9c723deca7b70c527a846819168">notes_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the end iterator for notes. <a href="#acea5c9c723deca7b70c527a846819168">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a54e0eb7b4c7bff44dd72334b6184a045">notes</a> (const Elf_Phdr &amp;Phdr, Error &amp;Err) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; Elf_Note_Iterator &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator range over notes of a program header. <a href="#a54e0eb7b4c7bff44dd72334b6184a045">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6be02fcc36d1f6e76eb877a09f5a225">notes</a> (const Elf_Shdr &amp;Shdr, Error &amp;Err) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; Elf_Note_Iterator &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator range over notes of a section. <a href="#ab6be02fcc36d1f6e76eb877a09f5a225">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88bd58d28de77251dc67fef8cf87e7a8">getSectionStringTable</a> (Elf_Shdr_Range Sections, WarningHandler WarnHandler=&amp;defaultWarningHandler) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe8f1b1f8599971e74d71887513cfd60">getSectionIndex</a> (const Elf_Sym &amp;Sym, Elf_Sym_Range Syms, DataRegion&lt; Elf_Word &gt; ShndxTable) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af1e96fd6674f65a3dcc5c4f46a4112b6">getSection</a> (const Elf_Sym &amp;Sym, const Elf_Shdr *SymTab, DataRegion&lt; Elf_Word &gt; ShndxTable) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a293b1243e72e557969d357e6e195e929">getSection</a> (const Elf_Sym &amp;Sym, Elf_Sym_Range Symtab, DataRegion&lt; Elf_Word &gt; ShndxTable) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14680087ccae0d9f57cda7380290b23d">getSection</a> (uint32_t Index) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d1adf40e179d829e92251f584b6f849">getSymbol</a> (const Elf_Shdr *Sec, uint32_t Index) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Sym * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1657b415560e76194871821263f1273">getSectionName</a> (const Elf_Shdr &amp;Section, WarningHandler WarnHandler=&amp;defaultWarningHandler) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b21b0b6b92569afb3b677c440ecb3b6">getSectionName</a> (const Elf_Shdr &amp;Section, StringRef DotShstrtab) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae1123dddef9e813facbc60595e9427f8">getSectionContentsAsArray</a> (const Elf_Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5fd489ea4559343125c546221251b743">getSectionContents</a> (const Elf_Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a464c7849464818cb8c8f45b84d375f8c">getSegmentContents</a> (const Elf_Phdr &amp;Phdr) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46e1bbe3fd829b216165917625cb142d">decodeBBAddrMap</a> (const Elf_Shdr &amp;Sec, const Elf_Shdr *RelaSec=nullptr, std::vector&lt; PGOAnalysisMap &gt; *PGOAnalyses=nullptr) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap">BBAddrMap</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a vector of <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap">BBAddrMap</a> structs corresponding to each function within the text section that the SHT_LLVM_BB_ADDR_MAP section <span class="doxyComputerOutput">Sec</span> is associated with. <a href="#a46e1bbe3fd829b216165917625cb142d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac224640f48ef4ce451d49bbb1b68e9ca">getSectionAndRelocations</a> (std::function&lt; Expected&lt; bool &gt;(const Elf_Shdr &amp;)&gt; IsMatch) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a map from every section matching <span class="doxyComputerOutput">IsMatch</span> to its relocation section, or <span class="doxyComputerOutput">nullptr</span> if it has no relocation section. <a href="#ac224640f48ef4ce451d49bbb1b68e9ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab0b3761016cb8d51d680debe57389b6">createFakeSections</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used by llvm-objdump -d (which needs sections for disassembly) to disassemble objects without a section header table (e.g. <a href="#aab0b3761016cb8d51d680debe57389b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a74a462dc40aa024b20303b88e898139d">Buf</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; Elf_Shdr &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a81b5e689ab29cf52ed4cee3b8895ba52">FakeSections</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 0 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2aa7a9df67f2874e46d37ea0cc0f2b85">FakeSectionStrings</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c43c56d0ce8c5e87d92506d7b567a5b">create</a> (StringRef Object) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a> &gt;</td>
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


<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### RelsOrRelas {#af7aa9ddd837c6041eb52bd45cae11289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::ELFFile&lt; ELFT &gt;::RelsOrRelas =  std::pair&lt;std::vector&lt;Elf_Rel&gt;, std::vector&lt;Elf_Rela&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

### WarningHandler {#aded5f2aa590cbcfe256b517b31aba812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::ELFFile&lt; ELFT &gt;::WarningHandler =  llvm::function_ref&lt;Error(const Twine &amp;Msg)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ELFFile() {#a54dee86341ca720bda5b7493841671b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::ELFFile&lt; ELFT &gt;::ELFFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Object)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### android\_relas() {#a0752ad646759ea4a034a218da571ab8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; typename ELFT::Rela &gt; &gt; ELFFile::android_relas (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a5fd489ea4559343125c546221251b743">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac9e50507b6d18dc2f18508ff067e140e">llvm::object::ELFFile&lt; ELFT &gt;::isLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a1fe366852b9d304301405e7d097a9f3aaea39a20846632fc74d5bd31904e7c7d3">llvm::ELF::RELOCATION_GROUP_HAS_ADDEND_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a1fe366852b9d304301405e7d097a9f3aae8d1bff7c4a8e67ecd69d60ff3ac7861">llvm::ELF::RELOCATION_GROUPED_BY_ADDEND_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a1fe366852b9d304301405e7d097a9f3aa52d7c6b548b48f57f1a662d30fa1054a">llvm::ELF::RELOCATION_GROUPED_BY_INFO_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a1fe366852b9d304301405e7d097a9f3aa4adde8f6d657bbe47c1694fa054638d7">llvm::ELF::RELOCATION_GROUPED_BY_OFFSET_DELTA_FLAG</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a3453d69f4b4b74c0cf69808bc7d1c8b0">llvm::DataExtractor::Cursor::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### base() {#ab6cf194b594fa748bf8cd72df35d6479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t * llvm::object::ELFFile&lt; ELFT &gt;::base ()</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>, <a href="#a8693389f2e062787589d31dbf6c304ee">llvm::object::ELFFile&lt; ELF32LE &gt;::end</a>, <a href="#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELF32LE &gt;::getHeader</a>, <a href="#ae1123dddef9e813facbc60595e9427f8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContentsAsArray</a>, <a href="#a464c7849464818cb8c8f45b84d375f8c">llvm::object::ELFFile&lt; ELFT &gt;::getSegmentContents</a>, <a href="#a5d91616c8a62b5988aa2570be36c7912">llvm::object::ELFFile&lt; ELF32LE &gt;::notes_begin</a>, <a href="#a472b2e829986b644129759fb3249df7c">llvm::object::ELFFile&lt; ELF32LE &gt;::notes_begin</a>, <a href="#a685264b0f25cd162e8b4e85365aee004">llvm::object::ELFFile&lt; ELF32LE &gt;::program_headers</a>, <a href="#ab64e03f049c8588f24e0ec69a568aef9">llvm::object::ELFFile&lt; ELFT &gt;::sections</a> and <a href="#abf0867b6082e1e0408b1b5d8301f27e2">llvm::object::ELFFile&lt; ELFT &gt;::toMappedAddr</a>.</p>

</div>
</div>

### createFakeSections() {#aab0b3761016cb8d51d680debe57389b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ELFFile&lt; ELFT &gt;::createFakeSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used by llvm-objdump -d (which needs sections for disassembly) to disassemble objects without a section header table (e.g.</p>


<p>ET_CORE objects analyzed by linux perf or ET_EXEC with llvm-strip –strip-sections).</p>


<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a434a5e99e2b676f037bae7c08955dbf7a8f0ef41a6f5cecd7908ad1d02d195697">llvm::ELF::PF_X</a>, <a href="#a685264b0f25cd162e8b4e85365aee004">llvm::object::ELFFile&lt; ELFT &gt;::program_headers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4c1b3bf29b3c86c8d11b6708ff244669a15ee14963e8cb0e95f10994bbd35a050">llvm::ELF::PT_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>.</p>

</div>
</div>

### crels() {#ae2039f20cc8322c8af90fb0dec7bb772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; typename ELFFile&lt; ELFT &gt;::RelsOrRelas &gt; ELFFile::crels (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab0f852d38471e3013e30ec9c1241edfe">llvm::object::decodeCrel</a>, <a href="#a5fd489ea4559343125c546221251b743">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContents</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### decode\_relrs() {#af6fe298454e5320427d65c40da7981aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; typename ELFT::Rel &gt; ELFFile::decode_relrs (Elf_Relr_Range relrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>Reference <a href="#abfc0395a4aa4e229de6ff4f2c8c8f63c">llvm::object::ELFFile&lt; ELFT &gt;::relrs</a>.</p>

</div>
</div>

### decodeBBAddrMap() {#a46e1bbe3fd829b216165917625cb142d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; BBAddrMap &gt; &gt; ELFFile::decodeBBAddrMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * RelaSec=nullptr, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/pgoanalysismap">PGOAnalysisMap</a> &gt; * PGOAnalyses=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a vector of <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap">BBAddrMap</a> structs corresponding to each function within the text section that the SHT_LLVM_BB_ADDR_MAP section <span class="doxyComputerOutput">Sec</span> is associated with.</p>


<p>If the current <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a> is relocatable, a corresponding <span class="doxyComputerOutput">RelaSec</span> must be passed in as an argument. Optional out variable to collect all PGO Analyses. New elements are only added if no error occurs. If not provided, the PGO Analyses are decoded then ignored.</p>


<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 932 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#a6264f8eee9db96846bfe5119e1ceb4ab">readBBAddrMapImpl</a>.</p>

</div>
</div>

### decodeCrel() {#a85a04b6f06b8f42bce6a666eee85d745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; typename ELFFile&lt; ELFT &gt;::RelsOrRelas &gt; ELFFile::decodeCrel (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Content)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab0f852d38471e3013e30ec9c1241edfe">llvm::object::decodeCrel</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### dynamicEntries() {#aa438ee4f7cc143674ffb81a41c01fcb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; typename ELFT::DynRange &gt; ELFFile::dynamicEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="#ab6cf194b594fa748bf8cd72df35d6479">llvm::object::ELFFile&lt; ELFT &gt;::base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#a8693389f2e062787589d31dbf6c304ee">llvm::object::ELFFile&lt; ELFT &gt;::end</a>, <a href="#ae1123dddef9e813facbc60595e9427f8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContentsAsArray</a>, <a href="#a685264b0f25cd162e8b4e85365aee004">llvm::object::ELFFile&lt; ELFT &gt;::program_headers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4c1b3bf29b3c86c8d11b6708ff244669a90c4af7485fa8c23cc0021edbcb81af4">llvm::ELF::PT_DYNAMIC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ad9bfff4f6c093ce614da964288d832c9">sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca8c63cb324623b483b1b1b1fb1b575447">llvm::ELF::SHT_DYNAMIC</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad4d4b1a08082a48e36079e1725005a2f">llvm::ifs::buildStub</a> and <a href="#a8e0db63318e9923b354d95e0391c05db">llvm::object::ELFFile&lt; ELFT &gt;::getDynSymtabSize</a>.</p>

</div>
</div>

### end() {#a8693389f2e062787589d31dbf6c304ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t * llvm::object::ELFFile&lt; ELFT &gt;::end ()</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>.</p>

</div>
</div>

### getBufSize() {#a6e33078a7d937377faff3c10d2e1efaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::object::ELFFile&lt; ELFT &gt;::getBufSize ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#a8693389f2e062787589d31dbf6c304ee">llvm::object::ELFFile&lt; ELF32LE &gt;::end</a>, <a href="#a685264b0f25cd162e8b4e85365aee004">llvm::object::ELFFile&lt; ELF32LE &gt;::program_headers</a> and <a href="#abf0867b6082e1e0408b1b5d8301f27e2">llvm::object::ELFFile&lt; ELFT &gt;::toMappedAddr</a>.</p>

</div>
</div>

### getCrelHeader() {#aa1027abe2321f5eee653435e5305ddab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; ELFFile::getCrelHeader (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Content)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#ac9e50507b6d18dc2f18508ff067e140e">llvm::object::ELFFile&lt; ELFT &gt;::isLE</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getDynamicTagAsString() {#a26c25aaa2bbfe08a9e398cfa15769616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ELFFile::getDynamicTagAsString (unsigned Arch, uint64_t Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>Referenced by <a href="#ac8208b85e5ab2b28adf34fa92b116103">llvm::object::ELFFile&lt; ELFT &gt;::getDynamicTagAsString</a>.</p>

</div>
</div>

### getDynamicTagAsString() {#ac8208b85e5ab2b28adf34fa92b116103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ELFFile::getDynamicTagAsString (uint64_t Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="#a26c25aaa2bbfe08a9e398cfa15769616">llvm::object::ELFFile&lt; ELFT &gt;::getDynamicTagAsString</a> and <a href="#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>.</p>

</div>
</div>

### getDynSymtabSize() {#a8e0db63318e9923b354d95e0391c05db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::object::ELFFile&lt; ELFT &gt;::getDynSymtabSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function determines the number of dynamic symbols.</p>


<p>It reads section headers first. If section headers are not available, the number of symbols will be inferred by parsing dynamic hash tables.</p>


<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25ba44ae8e92a80fde434e1ab19994cc">llvm::StringRef::bytes_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a29cbcbb2f84da38dfff44fc4704f3b66">llvm::object::getDynSymtabSizeFromGnuHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ad9bfff4f6c093ce614da964288d832c9">sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcadb5044a1bd05d2a84193fb0eb9b9df12">llvm::ELF::SHT_DYNSYM</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#abf0867b6082e1e0408b1b5d8301f27e2">llvm::object::ELFFile&lt; ELFT &gt;::toMappedAddr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad4d4b1a08082a48e36079e1725005a2f">llvm::ifs::buildStub</a>.</p>

</div>
</div>

### getEntry() {#a6fe4eac160aa377a7f8e1edfcc4a17dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const T * &gt; llvm::object::ELFFile&lt; ELFT &gt;::getEntry (uint32_t Section, uint32_t Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="#a6fe4eac160aa377a7f8e1edfcc4a17dd">llvm::object::ELFFile&lt; ELFT &gt;::getEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>.</p>


<p>Referenced by <a href="#a6fe4eac160aa377a7f8e1edfcc4a17dd">llvm::object::ELFFile&lt; ELFT &gt;::getEntry</a> and <a href="#a815105a2af24d7dffc158173b5324272">llvm::object::ELFFile&lt; ELFT &gt;::getRelocationSymbol</a>.</p>

</div>
</div>

### getEntry() {#a98e19eaf03c9744a18996776d77d0ee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const T * &gt; llvm::object::ELFFile&lt; ELFT &gt;::getEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Section, uint32_t Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="#ae1123dddef9e813facbc60595e9427f8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContentsAsArray</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

### getHeader() {#a02cea47a954fd499a8dc8d80b75935ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Elf_Ehdr &amp; llvm::object::ELFFile&lt; ELFT &gt;::getHeader ()</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad4d4b1a08082a48e36079e1725005a2f">llvm::ifs::buildStub</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a47b5436c5611f6605c7ea813253dac5a">llvm::object::describe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#a658b1211d163ef9492d062d29de98201">llvm::offloading::amdgpu::getAMDGPUMetaDataFromImage</a>, <a href="#ac8208b85e5ab2b28adf34fa92b116103">llvm::object::ELFFile&lt; ELFT &gt;::getDynamicTagAsString</a>, <a href="#a504594efdb5d22d6233ba933e550bc2a">llvm::object::ELFFile&lt; ELFT &gt;::getRelativeRelocationType</a>, <a href="#ad45bb5df167eb8cac974b25d4c4ff5cd">llvm::object::ELFFile&lt; ELFT &gt;::getRelocationTypeName</a>, <a href="#a88bd58d28de77251dc67fef8cf87e7a8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionStringTable</a>, <a href="#a1b7e5aceb97b03a61eee57e8a2a4889c">llvm::object::ELFFile&lt; ELFT &gt;::getSHNDXTable</a>, <a href="#add75d06af5256ffc8ac789721f09ef4e">llvm::object::ELFFile&lt; ELFT &gt;::getStringTable</a>, <a href="#ac9e50507b6d18dc2f18508ff067e140e">llvm::object::ELFFile&lt; ELF32LE &gt;::isLE</a>, <a href="#ab9ee8e7123cfc8843e8558e604ad56b4">llvm::object::ELFFile&lt; ELF32LE &gt;::isMipsELF64</a>, <a href="#a685264b0f25cd162e8b4e85365aee004">llvm::object::ELFFile&lt; ELF32LE &gt;::program_headers</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#a6264f8eee9db96846bfe5119e1ceb4ab">readBBAddrMapImpl</a> and <a href="#ab64e03f049c8588f24e0ec69a568aef9">llvm::object::ELFFile&lt; ELFT &gt;::sections</a>.</p>

</div>
</div>

### getLinkAsStrtab() {#a0bbb4e885d31a6ae8eb4486532fb3108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFFile&lt; ELFT &gt;::getLinkAsStrtab (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Shdr &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a47b5436c5611f6605c7ea813253dac5a">llvm::object::describe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="#add75d06af5256ffc8ac789721f09ef4e">llvm::object::ELFFile&lt; ELFT &gt;::getStringTable</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>


<p>Referenced by <a href="#a20ac73b763595fb7dd3d76f6a221408c">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDefinitions</a> and <a href="#a6d7f36df9f1e78161aa1117443ec74e1">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDependencies</a>.</p>

</div>
</div>

### getRelativeRelocationType() {#a504594efdb5d22d6233ba933e550bc2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::ELFFile&lt; ELFT &gt;::getRelativeRelocationType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a36f586048b3d4bb4f82bfd32f53a724a">llvm::object::getELFRelativeRelocationType</a> and <a href="#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>.</p>

</div>
</div>

### getRelocationSymbol() {#a815105a2af24d7dffc158173b5324272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const typename ELFT::Sym * &gt; llvm::object::ELFFile&lt; ELFT &gt;::getRelocationSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Rel &amp; Rel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * SymTab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the symbol for a given relocation.</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="#a6fe4eac160aa377a7f8e1edfcc4a17dd">llvm::object::ELFFile&lt; ELFT &gt;::getEntry</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp/#a69558ca9802bcb2fcbbd69e73baedc5d">isMips64EL</a>.</p>

</div>
</div>

### getRelocationTypeName() {#ad45bb5df167eb8cac974b25d4c4ff5cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::ELFFile&lt; ELFT &gt;::getRelocationTypeName (uint32_t Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a26dff1f08cc67aef943d43c26f6d635a">llvm::object::getELFRelocationTypeName</a> and <a href="#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>.</p>


<p>Referenced by <a href="#a6ff64d4cf042294e0aa84c193e5061f7">llvm::object::ELFFile&lt; ELFT &gt;::getRelocationTypeName</a>.</p>

</div>
</div>

### getRelocationTypeName() {#a6ff64d4cf042294e0aa84c193e5061f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ELFFile&lt; ELFT &gt;::getRelocationTypeName (uint32_t Type, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="#ad45bb5df167eb8cac974b25d4c4ff5cd">llvm::object::ELFFile&lt; ELFT &gt;::getRelocationTypeName</a> and <a href="#ab9ee8e7123cfc8843e8558e604ad56b4">llvm::object::ELFFile&lt; ELFT &gt;::isMipsELF64</a>.</p>

</div>
</div>

### getSection() {#af1e96fd6674f65a3dcc5c4f46a4112b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const typename ELFT::Shdr * &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Sym &amp; Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * SymTab, <a href="/web-llvm/docs/api/structs/llvm/object/dataregion">DataRegion</a>&lt; Elf_Word &gt; ShndxTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="#a29639dfbcf056708f68f1cc4b2d8c237">llvm::object::ELFFile&lt; ELFT &gt;::symbols</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#a6264f8eee9db96846bfe5119e1ceb4ab">readBBAddrMapImpl</a>.</p>

</div>
</div>

### getSection() {#a293b1243e72e557969d357e6e195e929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const typename ELFT::Shdr * &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Sym &amp; Sym, Elf_Sym_Range Symtab, <a href="/web-llvm/docs/api/structs/llvm/object/dataregion">DataRegion</a>&lt; Elf_Word &gt; ShndxTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="#afe8f1b1f8599971e74d71887513cfd60">llvm::object::ELFFile&lt; ELFT &gt;::getSectionIndex</a>.</p>

</div>
</div>

### getSection() {#a14680087ccae0d9f57cda7380290b23d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const typename ELFT::Shdr * &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSection (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ad9bfff4f6c093ce614da964288d832c9">sections</a>.</p>

</div>
</div>

### getSectionAndRelocations() {#ac224640f48ef4ce451d49bbb1b68e9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MapVector&lt; const typename ELFT::Shdr *, const typename ELFT::Shdr * &gt; &gt; ELFFile::getSectionAndRelocations (std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp;)&gt; IsMatch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a map from every section matching <span class="doxyComputerOutput">IsMatch</span> to its relocation section, or <span class="doxyComputerOutput">nullptr</span> if it has no relocation section.</p>


<p>This function returns an error if any of the <span class="doxyComputerOutput">IsMatch</span> calls fail or if it fails to retrieve the content section of any relocation section.</p>


<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a47b5436c5611f6605c7ea813253dac5a">llvm::object::describe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ad9bfff4f6c093ce614da964288d832c9">sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#a6264f8eee9db96846bfe5119e1ceb4ab">readBBAddrMapImpl</a>.</p>

</div>
</div>

### getSectionContents() {#a5fd489ea4559343125c546221251b743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSectionContents (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Reference <a href="#ae1123dddef9e813facbc60595e9427f8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContentsAsArray</a>.</p>


<p>Referenced by <a href="#a0752ad646759ea4a034a218da571ab8b">llvm::object::ELFFile&lt; ELFT &gt;::android_relas</a>, <a href="#ae2039f20cc8322c8af90fb0dec7bb772">llvm::object::ELFFile&lt; ELFT &gt;::crels</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="#a20ac73b763595fb7dd3d76f6a221408c">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDefinitions</a> and <a href="#a6d7f36df9f1e78161aa1117443ec74e1">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDependencies</a>.</p>

</div>
</div>

### getSectionContentsAsArray() {#ae1123dddef9e813facbc60595e9427f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; T &gt; &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSectionContentsAsArray (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ab6cf194b594fa748bf8cd72df35d6479">llvm::object::ELFFile&lt; ELFT &gt;::base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab1b8db806d8af1fbd1c7cbcd90166fed">llvm::object::getSecIndexForError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>, <a href="#a98e19eaf03c9744a18996776d77d0ee1">llvm::object::ELFFile&lt; ELFT &gt;::getEntry</a>, <a href="#a5fd489ea4559343125c546221251b743">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContents</a>, <a href="#a1b7e5aceb97b03a61eee57e8a2a4889c">llvm::object::ELFFile&lt; ELFT &gt;::getSHNDXTable</a>, <a href="#add75d06af5256ffc8ac789721f09ef4e">llvm::object::ELFFile&lt; ELFT &gt;::getStringTable</a>, <a href="#a63434f54fe78bfe55d1c3de263359e6f">llvm::object::ELFFile&lt; ELF32LE &gt;::relas</a>, <a href="#abfc0395a4aa4e229de6ff4f2c8c8f63c">llvm::object::ELFFile&lt; ELF32LE &gt;::relrs</a>, <a href="#aed56eba38ac0877432634af5d02d282f">llvm::object::ELFFile&lt; ELF32LE &gt;::rels</a> and <a href="#a29639dfbcf056708f68f1cc4b2d8c237">llvm::object::ELFFile&lt; ELF32LE &gt;::symbols</a>.</p>

</div>
</div>

### getSectionIndex() {#afe8f1b1f8599971e74d71887513cfd60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSectionIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Sym &amp; Sym, Elf_Sym_Range Syms, <a href="/web-llvm/docs/api/structs/llvm/object/dataregion">DataRegion</a>&lt; Elf_Word &gt; ShndxTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0123e359eccc453af98b12d2b5ce2516">llvm::object::getExtendedSymbolTableIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5ae3fe714923fc008de6b4078f07accaba">llvm::ELF::SHN_LORESERVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a18b158617442f1bf35e5b3d38135ee59">llvm::ELF::SHN_XINDEX</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a293b1243e72e557969d357e6e195e929">llvm::object::ELFFile&lt; ELFT &gt;::getSection</a>.</p>

</div>
</div>

### getSectionName() {#ad1657b415560e76194871821263f1273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSectionName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Section, <a href="#aded5f2aa590cbcfe256b517b31aba812">WarningHandler</a> WarnHandler=&amp;<a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f4bdf18fcce304e2e7bdaaf312b5744">defaultWarningHandler</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a2da32c7f0735e4bcb64c34222a79a6c1">llvm::dwarf_linker::getSectionName</a>, <a href="#a88bd58d28de77251dc67fef8cf87e7a8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionStringTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ad9bfff4f6c093ce614da964288d832c9">sections</a>.</p>

</div>
</div>

### getSectionName() {#a1b21b0b6b92569afb3b677c440ecb3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSectionName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Section, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DotShstrtab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab1b8db806d8af1fbd1c7cbcd90166fed">llvm::object::getSecIndexForError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

### getSectionStringTable() {#a88bd58d28de77251dc67fef8cf87e7a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSectionStringTable (Elf_Shdr_Range Sections, <a href="#aded5f2aa590cbcfe256b517b31aba812">WarningHandler</a> WarnHandler=&amp;<a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f4bdf18fcce304e2e7bdaaf312b5744">defaultWarningHandler</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>, <a href="#add75d06af5256ffc8ac789721f09ef4e">llvm::object::ELFFile&lt; ELFT &gt;::getStringTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a18b158617442f1bf35e5b3d38135ee59">llvm::ELF::SHN_XINDEX</a>.</p>


<p>Referenced by <a href="#ad1657b415560e76194871821263f1273">llvm::object::ELFFile&lt; ELFT &gt;::getSectionName</a>.</p>

</div>
</div>

### getSegmentContents() {#a464c7849464818cb8c8f45b84d375f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSegmentContents (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Phdr &amp; Phdr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ab6cf194b594fa748bf8cd72df35d6479">llvm::object::ELFFile&lt; ELFT &gt;::base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6093488a3671e60920d3ef11ccfd6118">llvm::object::getPhdrIndexForError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

### getSHNDXTable() {#a26eb5a3830fae63f1263c58b0fb79621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; typename ELFT::Word &gt; &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSHNDXTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="#a26eb5a3830fae63f1263c58b0fb79621">llvm::object::ELFFile&lt; ELFT &gt;::getSHNDXTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ad9bfff4f6c093ce614da964288d832c9">sections</a>.</p>


<p>Referenced by <a href="#a26eb5a3830fae63f1263c58b0fb79621">llvm::object::ELFFile&lt; ELFT &gt;::getSHNDXTable</a>.</p>

</div>
</div>

### getSHNDXTable() {#a1b7e5aceb97b03a61eee57e8a2a4889c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; typename ELFT::Word &gt; &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSHNDXTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Section, Elf_Shdr_Range Sections)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a506e41356e887f732b2edfb4bf0b4679">llvm::object::getELFSectionTypeName</a>, <a href="#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="#ae1123dddef9e813facbc60595e9427f8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContentsAsArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcadb5044a1bd05d2a84193fb0eb9b9df12">llvm::ELF::SHT_DYNSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca4f0cd819b71791cb5a1945952dbc9166">llvm::ELF::SHT_SYMTAB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca973f4a1893cca71a0ec69aa145189486">llvm::ELF::SHT_SYMTAB_SHNDX</a>.</p>

</div>
</div>

### getStringTable() {#add75d06af5256ffc8ac789721f09ef4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFFile&lt; ELFT &gt;::getStringTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Section, <a href="#aded5f2aa590cbcfe256b517b31aba812">WarningHandler</a> WarnHandler=&amp;<a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f4bdf18fcce304e2e7bdaaf312b5744">defaultWarningHandler</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a506e41356e887f732b2edfb4bf0b4679">llvm::object::getELFSectionTypeName</a>, <a href="#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab1b8db806d8af1fbd1c7cbcd90166fed">llvm::object::getSecIndexForError</a>, <a href="#ae1123dddef9e813facbc60595e9427f8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContentsAsArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca095782f71f1df92eff34130f8a6d15f5">llvm::ELF::SHT_STRTAB</a>.</p>


<p>Referenced by <a href="#a0bbb4e885d31a6ae8eb4486532fb3108">llvm::object::ELFFile&lt; ELFT &gt;::getLinkAsStrtab</a>, <a href="#a88bd58d28de77251dc67fef8cf87e7a8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionStringTable</a> and <a href="#adfb3d16a4f2cb55b615809b97c5e6b13">llvm::object::ELFFile&lt; ELFT &gt;::getStringTableForSymtab</a>.</p>

</div>
</div>

### getStringTableForSymtab() {#a6a6612a17f1ed83c751bab1ed91ce355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFFile&lt; ELFT &gt;::getStringTableForSymtab (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="#a6a6612a17f1ed83c751bab1ed91ce355">llvm::object::ELFFile&lt; ELFT &gt;::getStringTableForSymtab</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ad9bfff4f6c093ce614da964288d832c9">sections</a>.</p>


<p>Referenced by <a href="#a6a6612a17f1ed83c751bab1ed91ce355">llvm::object::ELFFile&lt; ELFT &gt;::getStringTableForSymtab</a>.</p>

</div>
</div>

### getStringTableForSymtab() {#adfb3d16a4f2cb55b615809b97c5e6b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFFile&lt; ELFT &gt;::getStringTableForSymtab (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Section, Elf_Shdr_Range Sections)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="#add75d06af5256ffc8ac789721f09ef4e">llvm::object::ELFFile&lt; ELFT &gt;::getStringTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcadb5044a1bd05d2a84193fb0eb9b9df12">llvm::ELF::SHT_DYNSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca4f0cd819b71791cb5a1945952dbc9166">llvm::ELF::SHT_SYMTAB</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbol() {#a1d1adf40e179d829e92251f584b6f849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const typename ELFT::Sym * &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * Sec, uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab1b8db806d8af1fbd1c7cbcd90166fed">llvm::object::getSecIndexForError</a> and <a href="#a29639dfbcf056708f68f1cc4b2d8c237">llvm::object::ELFFile&lt; ELFT &gt;::symbols</a>.</p>

</div>
</div>

### getSymbolVersionByIndex() {#a56343d577008471112adcb121718f1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFFile&lt; ELFT &gt;::getSymbolVersionByIndex (uint32_t SymbolVersionIndex, bool &amp; IsDefault, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/versionentry">VersionEntry</a> &gt;, 0 &gt; &amp; VersionMap, std::optional&lt; bool &gt; IsSymHidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#af6b1b4928e918ae4019d2fde4f9aa9e6a079135b139e10df32b8ca420dad080ad">llvm::ELF::VER_NDX_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#af6b1b4928e918ae4019d2fde4f9aa9e6a867f3fad795fe7d247ff071a1dbed95e">llvm::ELF::VER_NDX_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#af6b1b4928e918ae4019d2fde4f9aa9e6af5bf74dff96a0a21624938926f78d98b">llvm::ELF::VERSYM_HIDDEN</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#af6b1b4928e918ae4019d2fde4f9aa9e6a6c042b464251229feea450c81877b6e1">llvm::ELF::VERSYM_VERSION</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#afbf1738ff099ad1ac3079a05ae07ea35">readDynsymVersionsImpl</a>.</p>

</div>
</div>

### getVersionDefinitions() {#a20ac73b763595fb7dd3d76f6a221408c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; VerDef &gt; &gt; llvm::object::ELFFile&lt; ELFT &gt;::getVersionDefinitions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/verdef/#af7372065f32bd746ab12e55a5216162f">llvm::object::VerDef::AuxV</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verdef/#a0f805d96f6fe600a685be7e733347671">llvm::object::VerDef::Cnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a47b5436c5611f6605c7ea813253dac5a">llvm::object::describe</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verdef/#a5cbd270aaaff67b608b721a30671a2dc">llvm::object::VerDef::Flags</a>, <a href="#a0bbb4e885d31a6ae8eb4486532fb3108">llvm::object::ELFFile&lt; ELFT &gt;::getLinkAsStrtab</a>, <a href="#a5fd489ea4559343125c546221251b743">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContents</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verdef/#ac4b61a9488eba5b623679b14fbff251e">llvm::object::VerDef::Hash</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verdaux/#aafbd8e2ef9b1c236ad0135174a6efe13">llvm::object::VerdAux::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verdef/#aa533b7b2d7456b15a010cb755e2e3a6f">llvm::object::VerDef::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verdef/#a6e263eb70fba7daef521498c6f64a4a2">llvm::object::VerDef::Ndx</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verdaux/#a4186b02fe0547a25eac9864abcab8951">llvm::object::VerdAux::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verdef/#afe430230df0e56aa64e686432cb70c0e">llvm::object::VerDef::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verdef/#a43031ca1f6c370fda62624104d0a7aa3">llvm::object::VerDef::Version</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#aeb221ffeffa3ec7eaaa8eecf37b0146d">llvm::object::ELFFile&lt; ELFT &gt;::loadVersionMap</a>.</p>

</div>
</div>

### getVersionDependencies() {#a6d7f36df9f1e78161aa1117443ec74e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; VerNeed &gt; &gt; llvm::object::ELFFile&lt; ELFT &gt;::getVersionDependencies (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec, <a href="#aded5f2aa590cbcfe256b517b31aba812">WarningHandler</a> WarnHandler=&amp;<a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f4bdf18fcce304e2e7bdaaf312b5744">defaultWarningHandler</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/verneed/#aac1637ef258b8394baa30b181b7d8e37">llvm::object::VerNeed::AuxV</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verneed/#a1df691099257c6afb8798fb6f7b10bc8">llvm::object::VerNeed::Cnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a47b5436c5611f6605c7ea813253dac5a">llvm::object::describe</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verneed/#a4b2d0fcf63a2221c5716c4aa22fbdeb1">llvm::object::VerNeed::File</a>, <a href="/web-llvm/docs/api/structs/llvm/object/vernaux/#a70d346d05d2cc952fc7b0bfb9fb1f651">llvm::object::VernAux::Flags</a>, <a href="#a0bbb4e885d31a6ae8eb4486532fb3108">llvm::object::ELFFile&lt; ELFT &gt;::getLinkAsStrtab</a>, <a href="#a5fd489ea4559343125c546221251b743">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContents</a>, <a href="/web-llvm/docs/api/structs/llvm/object/vernaux/#a3d0bb624b8bb882c4e6ffa5dd4965435">llvm::object::VernAux::Hash</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/object/vernaux/#ad0e17c28356a0beb44ca177e2b1b7e12">llvm::object::VernAux::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/object/vernaux/#a5382944caaa0e5dd70614d616848dcf5">llvm::object::VernAux::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verneed/#ac8b5b5bad8332d27946b021c25636539">llvm::object::VerNeed::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/object/vernaux/#ae7c65a6d94db333a11020982016811f1">llvm::object::VernAux::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>, <a href="/web-llvm/docs/api/structs/llvm/object/verneed/#ad66e5401d34c72d9c6bb1cb2fae9c055">llvm::object::VerNeed::Version</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#aeb221ffeffa3ec7eaaa8eecf37b0146d">llvm::object::ELFFile&lt; ELFT &gt;::loadVersionMap</a>.</p>

</div>
</div>

### isLE() {#ac9e50507b6d18dc2f18508ff067e140e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFFile&lt; ELFT &gt;::isLE ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#a0752ad646759ea4a034a218da571ab8b">llvm::object::ELFFile&lt; ELFT &gt;::android_relas</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="#aa1027abe2321f5eee653435e5305ddab">llvm::object::ELFFile&lt; ELFT &gt;::getCrelHeader</a> and <a href="#accd50e330d567f984dfff0557e49e044">llvm::object::ELFFile&lt; ELF32LE &gt;::isMips64EL</a>.</p>

</div>
</div>

### isMips64EL() {#accd50e330d567f984dfff0557e49e044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFFile&lt; ELFT &gt;::isMips64EL ()</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

### isMipsELF64() {#ab9ee8e7123cfc8843e8558e604ad56b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFFile&lt; ELFT &gt;::isMipsELF64 ()</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#a6ff64d4cf042294e0aa84c193e5061f7">llvm::object::ELFFile&lt; ELFT &gt;::getRelocationTypeName</a> and <a href="#accd50e330d567f984dfff0557e49e044">llvm::object::ELFFile&lt; ELF32LE &gt;::isMips64EL</a>.</p>

</div>
</div>

### loadVersionMap() {#aeb221ffeffa3ec7eaaa8eecf37b0146d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SmallVector&lt; std::optional&lt; VersionEntry &gt;, 0 &gt; &gt; llvm::object::ELFFile&lt; ELFT &gt;::loadVersionMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * VerNeedSec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * VerDefSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="#a20ac73b763595fb7dd3d76f6a221408c">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDefinitions</a>, <a href="#a6d7f36df9f1e78161aa1117443ec74e1">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/llvm/object/vernaux/#ad0e17c28356a0beb44ca177e2b1b7e12">llvm::object::VernAux::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/object/vernaux/#ae7c65a6d94db333a11020982016811f1">llvm::object::VernAux::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#af6b1b4928e918ae4019d2fde4f9aa9e6a6c042b464251229feea450c81877b6e1">llvm::ELF::VERSYM_VERSION</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#afbf1738ff099ad1ac3079a05ae07ea35">readDynsymVersionsImpl</a>.</p>

</div>
</div>

### notes() {#a54e0eb7b4c7bff44dd72334b6184a045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; Elf_Note_Iterator &gt; llvm::object::ELFFile&lt; ELFT &gt;::notes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Phdr &amp; Phdr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
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

<p>Get an iterator range over notes of a program header.</p>


<p>The program header must be of type <span class="doxyComputerOutput">PT_NOTE</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Phdr</td>
<td class="doxyParamItemDescription"><p>the program header to iterate over.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Err</td>
<td class="doxyParamItemDescription"><p>[out] an error to support fallible iteration, which should be checked after iteration ends.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#a658b1211d163ef9492d062d29de98201">llvm::offloading::amdgpu::getAMDGPUMetaDataFromImage</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-buildid-cpp-/#a10d49947a1b089d5ee06458bf8252a37">anonymous{BuildID.cpp}::getBuildID</a>.</p>

</div>
</div>

### notes() {#ab6be02fcc36d1f6e76eb877a09f5a225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; Elf_Note_Iterator &gt; llvm::object::ELFFile&lt; ELFT &gt;::notes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Shdr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
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

<p>Get an iterator range over notes of a section.</p>


<p>The section must be of type <span class="doxyComputerOutput">SHT_NOTE</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Shdr</td>
<td class="doxyParamItemDescription"><p>the section to iterate over.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Err</td>
<td class="doxyParamItemDescription"><p>[out] an error to support fallible iteration, which should be checked after iteration ends.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

### notes\_begin() {#a5d91616c8a62b5988aa2570be36c7912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf_Note_Iterator llvm::object::ELFFile&lt; ELFT &gt;::notes_begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Phdr &amp; Phdr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
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

<p>Get an iterator over notes in a program header.</p>


<p>The program header must be of type <span class="doxyComputerOutput">PT_NOTE</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Phdr</td>
<td class="doxyParamItemDescription"><p>the program header to iterate over.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Err</td>
<td class="doxyParamItemDescription"><p>[out] an error to support fallible iteration, which should be checked after iteration ends.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#a54e0eb7b4c7bff44dd72334b6184a045">llvm::object::ELFFile&lt; ELF32LE &gt;::notes</a> and <a href="#ab6be02fcc36d1f6e76eb877a09f5a225">llvm::object::ELFFile&lt; ELF32LE &gt;::notes</a>.</p>

</div>
</div>

### notes\_begin() {#a472b2e829986b644129759fb3249df7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf_Note_Iterator llvm::object::ELFFile&lt; ELFT &gt;::notes_begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Shdr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
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

<p>Get an iterator over notes in a section.</p>


<p>The section must be of type <span class="doxyComputerOutput">SHT_NOTE</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Shdr</td>
<td class="doxyParamItemDescription"><p>the section to iterate over.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Err</td>
<td class="doxyParamItemDescription"><p>[out] an error to support fallible iteration, which should be checked after iteration ends.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

### notes\_end() {#acea5c9c723deca7b70c527a846819168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf_Note_Iterator llvm::object::ELFFile&lt; ELFT &gt;::notes_end ()</td>
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

<p>Get the end iterator for notes.</p>

<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#a54e0eb7b4c7bff44dd72334b6184a045">llvm::object::ELFFile&lt; ELF32LE &gt;::notes</a> and <a href="#ab6be02fcc36d1f6e76eb877a09f5a225">llvm::object::ELFFile&lt; ELF32LE &gt;::notes</a>.</p>

</div>
</div>

### program\_headers() {#a685264b0f25cd162e8b4e85365aee004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Elf_Phdr_Range &gt; llvm::object::ELFFile&lt; ELFT &gt;::program_headers ()</td>
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

<p>Iterate over program header table.</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#aab0b3761016cb8d51d680debe57389b6">llvm::object::ELFFile&lt; ELFT &gt;::createFakeSections</a>, <a href="#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-buildid-cpp-/#a10d49947a1b089d5ee06458bf8252a37">anonymous{BuildID.cpp}::getBuildID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6093488a3671e60920d3ef11ccfd6118">llvm::object::getPhdrIndexForError</a> and <a href="#abf0867b6082e1e0408b1b5d8301f27e2">llvm::object::ELFFile&lt; ELFT &gt;::toMappedAddr</a>.</p>

</div>
</div>

### relas() {#a63434f54fe78bfe55d1c3de263359e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Elf_Rela_Range &gt; llvm::object::ELFFile&lt; ELFT &gt;::relas (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec)</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>.</p>

</div>
</div>

### relrs() {#abfc0395a4aa4e229de6ff4f2c8c8f63c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Elf_Relr_Range &gt; llvm::object::ELFFile&lt; ELFT &gt;::relrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#af6fe298454e5320427d65c40da7981aa">llvm::object::ELFFile&lt; ELFT &gt;::decode_relrs</a>.</p>

</div>
</div>

### rels() {#aed56eba38ac0877432634af5d02d282f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Elf_Rel_Range &gt; llvm::object::ELFFile&lt; ELFT &gt;::rels (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr &amp; Sec)</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

### sections() {#ab64e03f049c8588f24e0ec69a568aef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; typename ELFT::ShdrRange &gt; llvm::object::ELFFile&lt; ELFT &gt;::sections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ab6cf194b594fa748bf8cd72df35d6479">llvm::object::ELFFile&lt; ELFT &gt;::base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#a47b5436c5611f6605c7ea813253dac5a">llvm::object::describe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#a658b1211d163ef9492d062d29de98201">llvm::offloading::amdgpu::getAMDGPUMetaDataFromImage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab1b8db806d8af1fbd1c7cbcd90166fed">llvm::object::getSecIndexForError</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#a6264f8eee9db96846bfe5119e1ceb4ab">readBBAddrMapImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#afbf1738ff099ad1ac3079a05ae07ea35">readDynsymVersionsImpl</a>.</p>

</div>
</div>

### symbols() {#a29639dfbcf056708f68f1cc4b2d8c237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Elf_Sym_Range &gt; llvm::object::ELFFile&lt; ELFT &gt;::symbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * Sec)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#af1e96fd6674f65a3dcc5c4f46a4112b6">llvm::object::ELFFile&lt; ELFT &gt;::getSection</a> and <a href="#a1d1adf40e179d829e92251f584b6f849">llvm::object::ELFFile&lt; ELFT &gt;::getSymbol</a>.</p>

</div>
</div>

### toMappedAddr() {#abf0867b6082e1e0408b1b5d8301f27e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const uint8_t * &gt; ELFFile::toMappedAddr (uint64_t VAddr, <a href="#aded5f2aa590cbcfe256b517b31aba812">WarningHandler</a> WarnHandler=&amp;<a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f4bdf18fcce304e2e7bdaaf312b5744">defaultWarningHandler</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>, definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ab6cf194b594fa748bf8cd72df35d6479">llvm::object::ELFFile&lt; ELFT &gt;::base</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="#a6e33078a7d937377faff3c10d2e1efaa">llvm::object::ELFFile&lt; ELFT &gt;::getBufSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a685264b0f25cd162e8b4e85365aee004">llvm::object::ELFFile&lt; ELFT &gt;::program_headers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4c1b3bf29b3c86c8d11b6708ff244669a15ee14963e8cb0e95f10994bbd35a050">llvm::ELF::PT_LOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b7d2ab11554bd10d15b6cb21b2c2787">llvm::upper_bound</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="#a8e0db63318e9923b354d95e0391c05db">llvm::object::ELFFile&lt; ELFT &gt;::getDynSymtabSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buf {#a74a462dc40aa024b20303b88e898139d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::ELFFile&lt; ELFT &gt;::Buf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

### FakeSections {#a81b5e689ab29cf52ed4cee3b8895ba52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Elf_Shdr&gt; llvm::object::ELFFile&lt; ELFT &gt;::FakeSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

### FakeSectionStrings {#a2aa7a9df67f2874e46d37ea0cc0f2b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;0&gt; llvm::object::ELFFile&lt; ELFT &gt;::FakeSectionStrings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a0c43c56d0ce8c5e87d92506d7b567a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ELFFile&lt; ELFT &gt; &gt; llvm::object::ELFFile&lt; ELFT &gt;::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Object)</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a65d9c3a1e8cb5fe3e06486957ea45fbb">llvm::object::ELFObjectFile&lt; ELFT &gt;::create</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">ELF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
