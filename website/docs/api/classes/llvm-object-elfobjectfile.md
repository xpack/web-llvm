---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/elfobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ELFObjectFile` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;class ELFT&gt;
class llvm::object::ELFObjectFile&lt;ELFT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">llvm/Object/ELFObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase">ELFObjectFileBase</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-runtimedyldelf-cpp-/dyldelfobject">DyldELFObject&lt;ELFT&gt;</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3ef3a0df77100e5a640653d0c2336df7">ELFObjectFile</a> (ELFObjectFile&lt; ELFT &gt; &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a049aa0eb7315f0b23cfec93dba79ff42">ELFObjectFile</a> (MemoryBufferRef Object, ELFFile&lt; ELFT &gt; EF, const Elf_Shdr *DotDynSymSec, const Elf_Shdr *DotSymtabSec, const Elf_Shdr *DotSymtabShndxSec)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26a8b66384eac1604e4ce7bd35bb6878">toSectionRef</a> (const Elf_Shdr *Sec) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref">ELFSymbolRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5247b35d5fcc7e4087e2db32a4210c66">toSymbolRef</a> (const Elf_Shdr *SymTable, unsigned SymbolNum) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2bb517f0216737e6058b65d64516664e">IsContentValid</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Rel *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d0ec360affeb52e9ce16d7f03b8bd0f">getRel</a> (DataRefImpl Rel) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Rela *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a601dda6211feb315c7ee08b7b18cdcc1">getRela</a> (DataRefImpl Rela) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Elf_Crel</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e46698fa736bb80c17d882d025b6d5e">getCrel</a> (DataRefImpl Crel) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a380007d3421e3ea8b92b2a99d3503914">getSymbol</a> (DataRefImpl Sym) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Sym * &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91e58df62039bd1c5efc1f2ec5d403a6">getRelSection</a> (DataRefImpl Rel) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the relocation section that contains <em>Rel</em>. <a href="#a91e58df62039bd1c5efc1f2ec5d403a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad3948dea124f86f2acec9ac741d0a003">getSection</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4df4dd9bdd97616b9710ac0464fa183d">symbol_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abefb1aceb82f15c250ab09c759d97273">symbol_end</a> () const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c3e3311e7ad7f04e507ff2c861d2a0b">is64Bit</a> () const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elf-symbol-iterator">elf_symbol_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada77010d9c8ebda8b2f14e155c56ac3e">dynamic_symbol_begin</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elf-symbol-iterator">elf_symbol_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adc6d540d187c8250f636159fb7f2b59f">dynamic_symbol_end</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae648cd200193e29acb9f122298373715">section_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88783da09d7c0838a1f8d70545dde91b">section_end</a> () const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9344d22023aca51c38f99bf5b35c811f">getRelocationAddend</a> (DataRefImpl Rel) const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int64_t &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0baff9952a1ab0ba1c04c142ee5aeee">getBytesInAddress</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes used to represent an address in this object file format. <a href="#af0baff9952a1ab0ba1c04c142ee5aeee">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f800705ddfcafe90204f53339ceb01a">getFileFormatName</a> () const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a01300e2d307f9b0804e765f3c7be7e">getArch</a> () const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cd">Triple::OSType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1fac5e29bf02a04dd08ec4f3c62e2b92">getOS</a> () const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af591167c2c7ca37b052f6e9b225e4c3c">getStartAddress</a> () const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa711ab9b1fbabfc024aa526a54e2056">getPlatformFlags</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns platform-specific object flags, if any. <a href="#aaa711ab9b1fbabfc024aa526a54e2056">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a048e38d71ccf2bac0bc8176f16ffc910">getELFFile</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a>&lt; ELFT &gt; &amp;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a436b47ff384ed39d09f4e2120a7b99a2">isDyldType</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#acfa80c2a44dbec7ba7718d1be22fc9e3">elf_symbol_iterator_range</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a33e28ab84959ee02f29b56cd1025034c">getDynamicSymbolIterators</a> () const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a852d31a92a4f2e97ad2d64360758d5ec">isRelocatableObject</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is a relocatable object (.o/.obj). <a href="#a852d31a92a4f2e97ad2d64360758d5ec">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a366992059c86a298944c825122d3ec8f">createFakeSections</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afff19aa09cf22aea52fde5f561aa0690">getCrelDecodeProblem</a> (DataRefImpl Sec) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abda9cbfc7a332979538e75a0d52f7fdc">initContent</a> () override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85fb90e445dc6273e7820231a50a981b">moveSymbolNext</a> (DataRefImpl &amp;Symb) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab82d11942ddc1cd6df695e3ec80ad39b">getSymbolName</a> (DataRefImpl Symb) const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4f47a108418b742c0419cc238a0cdebb">getSymbolAddress</a> (DataRefImpl Symb) const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b197578436993f9a0a9753d214822b4">getSymbolValueImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a784f287bf4c93da1cc4c455e4c41fd94">getSymbolAlignment</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a74cdab4ba5f0146a2444c6c4d29b2d">getCommonSymbolSizeImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d7040098bbc2f04e4191b9991a769e3">getSymbolFlags</a> (DataRefImpl Symb) const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1c87c93f81427748d963d87ba65b21a">getSymbolBinding</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8794e158de6bc5ebb588198cdf868418">getSymbolOther</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a19c92b8d9a2449d3b8c4b3de8b5db326">getSymbolELFType</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad38d33d56845066a2063cc3896329d03">getSymbolType</a> (DataRefImpl Symb) const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04">SymbolRef::Type</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a42018f438c55d2c9c83355e3a8c3cb94">getSymbolSection</a> (const Elf_Sym *Symb, const Elf_Shdr *SymTab) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3859965ea1c713b4c1187bdafba6fa60">getSymbolSection</a> (DataRefImpl Symb) const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa24b98f2423948931bb4fb8b50ca9cf4">moveSectionNext</a> (DataRefImpl &amp;Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a051bc7c48ec863294318a92b616739b3">getSectionName</a> (DataRefImpl Sec) const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a691f9ee3cc6ab7a16a223d713dbc46eb">getSectionAddress</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c1a5fe426bd8ab30f4a7d5fe83e4ab7">getSectionIndex</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7dc02eb7ee0d57e4f38a1e5c68113057">getSectionSize</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6aa9147fe46df8a395d32bfcfb7585bd">getSectionContents</a> (DataRefImpl Sec) const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1a1351e82d9cbc15e5b1df7bc88fc8dd">getSectionAlignment</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae831a9c23d4063e07c13f8f03cd1f1f5">isSectionCompressed</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16c5ac6875015c495c671b56e3ecd0bc">isSectionText</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73870a9eff6636a746979c4f968a1ab5">isSectionData</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa270392082b5912cf2adaec08da203c8">isSectionBSS</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1fa4ba92d78835f1fa8d4d7fa2eab0a6">isSectionVirtual</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb51b7c07d49924799bbf0a7f8f8d265">isBerkeleyText</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ef4e220ea14cc91dcfa99884aa627e4">isBerkeleyData</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae62484c71e9b9ab034fe9a10717fa718">isDebugSection</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4f09c74a59f0465db07fe6b95233878">section_rel_begin</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aca0c5ead089272fe21045ffd6895b298">section_rel_end</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1300a4c221076a37306ccd4eb96b2e2a">dynamic_relocation_sections</a> () const override -&gt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9cb66c2081706fafa8bb7804d9c8b0b3">getRelocatedSection</a> (DataRefImpl Sec) const override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaff3a188e4b250ad59461b8687ca3354">moveRelocationNext</a> (DataRefImpl &amp;Rel) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9452290037eaad9ae3c05b7a5ed6133c">getRelocationOffset</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbol-iterator">symbol_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a319cac7161084045e98652fa736ed8e3">getRelocationSymbol</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15cfaa14709e529b7ea5c52d1cd9bb80">getRelocationType</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6bf6040a258d1e795595c91c82d4635a">getRelocationTypeName</a> (DataRefImpl Rel, SmallVectorImpl&lt; char &gt; &amp;Result) const override</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2be82e45724555e77b4c06e56a65bb4d">getSectionType</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaab62140bd37d2d31eab0d8e84148883">getSectionFlags</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac85e557d61ba57ac514dfb6c4482056c">getSectionOffset</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3bbfa07784d5a4f7f0217ee54514ac21">getRelocationTypeName</a> (uint32_t Type) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae00fd66498ddb379c96552de1ee04062">toDRI</a> (const Elf_Shdr *SymTable, unsigned SymbolNum) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a790f65b9fc4ad4683fdb5498a2252cdf">toELFShdrIter</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad912f79fa206416af9b82b3532b8e5e7">toDRI</a> (const Elf_Shdr *Sec) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1cddf7fbb62a4bd40c06942b513b2e52">toDRI</a> (const Elf_Dyn *Dyn) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a67de91533b4746c8c320bea8e517de4a">isExportedToOtherDSO</a> (const Elf_Sym *ESym) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad4f1deb260cb6fd64575135be5a3d25f">getBuildAttributes</a> (ELFAttributeParser &amp;Attributes) const override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#addc7322bab6b111283196697a10fe0d7">getEMachine</a> () const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a136b0cad5fd4a02ae821f2f1bfc436f4">getEType</a> () const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c07fc16d5dd80c0312dacd9c3a1b7b7">getEIdentABIVersion</a> () const override</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af506559607adac6ce0063e2717f6e3fb">getSymbolSize</a> (DataRefImpl Sym) const override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a>&lt; ELFT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">EF</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a771c752c0df8994c1fd0ab9c300bb5cf">DotDynSymSec</a> = nullptr</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a74cc6208555d0a46056d7bf1a2888537">DotSymtabSec</a> = nullptr</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adc31179fa21b266172586d580f9e51b0">DotSymtabShndxSec</a> = nullptr</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; Elf_Crel, 0 &gt;, 0 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae97c27d726114928e38aff51e6113ee9">Crels</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::string, 0 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d68484baaee7cdf4d1d2157c72c9b8c">CrelDecodeProblems</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21a7e8753647ddac0219c5c6423184a6">isDyldELFObject</a> = false</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd7ae170d26c1b6a7397a13ed124b40c">ContentValid</a> = false</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a65d9c3a1e8cb5fe3e06486957ea45fbb">create</a> (MemoryBufferRef Object, bool InitContent=true) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile">ELFObjectFile</a>&lt; ELFT &gt; &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a01e1316c81b78deca5cf4ebbc2d0c0c5">classof</a> (const Binary *v)</td>
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


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ELFObjectFile() {#a3ef3a0df77100e5a640653d0c2336df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::ELFObjectFile&lt; ELFT &gt;::ELFObjectFile (<a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile">ELFObjectFile</a>&lt; ELFT &gt; &amp;&amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="#a771c752c0df8994c1fd0ab9c300bb5cf">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotDynSymSec</a>, <a href="#a74cc6208555d0a46056d7bf1a2888537">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabSec</a>, <a href="#adc31179fa21b266172586d580f9e51b0">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabShndxSec</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ELFObjectFile() {#a049aa0eb7315f0b23cfec93dba79ff42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::ELFObjectFile&lt; ELFT &gt;::ELFObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a>&lt; ELFT &gt; EF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * DotDynSymSec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * DotSymtabSec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * DotSymtabShndxSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createFakeSections() {#a366992059c86a298944c825122d3ec8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ELFObjectFile&lt; ELFT &gt;::createFakeSections ()</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### dynamic\_symbol\_begin() {#ada77010d9c8ebda8b2f14e155c56ac3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">elf_symbol_iterator llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a771c752c0df8994c1fd0ab9c300bb5cf">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotDynSymSec</a> and <a href="#ae00fd66498ddb379c96552de1ee04062">llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI</a>.</p>


<p>Referenced by <a href="#adc6d540d187c8250f636159fb7f2b59f">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_end</a> and <a href="#a33e28ab84959ee02f29b56cd1025034c">llvm::object::ELFObjectFile&lt; ELFT &gt;::getDynamicSymbolIterators</a>.</p>

</div>
</div>

### dynamic\_symbol\_end() {#adc6d540d187c8250f636159fb7f2b59f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">elf_symbol_iterator llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a771c752c0df8994c1fd0ab9c300bb5cf">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotDynSymSec</a>, <a href="#ada77010d9c8ebda8b2f14e155c56ac3e">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_begin</a> and <a href="#ae00fd66498ddb379c96552de1ee04062">llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI</a>.</p>


<p>Referenced by <a href="#a33e28ab84959ee02f29b56cd1025034c">llvm::object::ELFObjectFile&lt; ELFT &gt;::getDynamicSymbolIterators</a>.</p>

</div>
</div>

### getArch() {#a7a01300e2d307f9b0804e765f3c7be7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType llvm::object::ELFObjectFile&lt; ELFT &gt;::getArch ()</td>
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



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">llvm::Triple::avr</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">llvm::Triple::bpfeb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">llvm::Triple::bpfel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">llvm::Triple::csky</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbab242034f8c02a1c57ded2c9a4b5296c4">llvm::ELF::EF_AMDGPU_MACH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba65b305c18a5c2ecc15a83f13da3dc302">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_FIRST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba2d0b0e4a96200f91f82a58eaa4fd1c98">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_LAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbad491a7f8c6c55e05147310f46237b52e">llvm::ELF::EF_AMDGPU_MACH_R600_FIRST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba55769f2bd33f4e5a78d9cef1da7e5727">llvm::ELF::EF_AMDGPU_MACH_R600_LAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4848e3ad29a6f6a8216e031204f636e9ac8ef31dee034e9fa40e690a4cdd360de">llvm::ELF::EI_CLASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5ac700ff9a9a24f46587997e131502702c">llvm::ELF::ELFCLASS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5a54b4da97cdda07031363b240c26c9794">llvm::ELF::ELFCLASS64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da6a266f492c600d97849933aad5356be4">llvm::ELF::EM_386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da68081d3eeeb60e9c28bfd47ded6af8cf">llvm::ELF::EM_68K</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dace9c7753eed878839a8fb04768d1436c">llvm::ELF::EM_AARCH64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dafb457612e3f91aca5d93ee2f1de6d4be">llvm::ELF::EM_AMDGPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dae70d9dc0883af67df7d3a1b521031c21">llvm::ELF::EM_ARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daff31d8bd81c175ccbcb24b80abe83f45">llvm::ELF::EM_AVR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da886091c305600f2e4056e5a4bec406f1">llvm::ELF::EM_BPF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da398ae44d88b5e271262866dcaeb64008">llvm::ELF::EM_CSKY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da7374b3df052ab46b2d79b52907c5d5ba">llvm::ELF::EM_CUDA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daa4bdb6dee5d86bb842354637ef53e14c">llvm::ELF::EM_HEXAGON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daf94f3540cf7f0fac3c8cf0cdde4e7b46">llvm::ELF::EM_IAMCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daa545d9417959747a17ee926b27a8d36f">llvm::ELF::EM_LANAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da7e72d41153159cd60700a91fa59f6e77">llvm::ELF::EM_LOONGARCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daaf29cd80fceba94e4f48b143fcf354c6">llvm::ELF::EM_MIPS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da0070e5fa94c73580a60f1cc71552f5d1">llvm::ELF::EM_MSP430</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da8a2160f2f630e0ebf2618fbec29150ea">llvm::ELF::EM_PPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da1da82f3b7f3ee5823ee15f4df8ce3d06">llvm::ELF::EM_PPC64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dad426ff446687588ec3a40dee3f6b3598">llvm::ELF::EM_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da0c6bd206dc080750ac4752f6c159e2a5">llvm::ELF::EM_S390</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da2c7a7ca60ce63d4bac4516de29c56145">llvm::ELF::EM_SPARC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da5125c70f3e4d8fc7f4b46aad1358e647">llvm::ELF::EM_SPARC32PLUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dac695bdf043012ff5b3d6ef4287b2639d">llvm::ELF::EM_SPARCV9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daed6f91343936a96682f2ea8f99a7930e">llvm::ELF::EM_VE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daa298f18ed198890cf54b635b54eafee3">llvm::ELF::EM_X86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dad0452e45f1fcaf19e2be8a02f67384a9">llvm::ELF::EM_XTENSA</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">llvm::Triple::hexagon</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">llvm::Triple::lanai</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">llvm::Triple::loongarch32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">llvm::Triple::loongarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">llvm::Triple::m68k</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">llvm::Triple::mips</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">llvm::Triple::mips64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">llvm::Triple::mips64el</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">llvm::Triple::mipsel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">llvm::Triple::msp430</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">llvm::Triple::nvptx</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">llvm::Triple::nvptx64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">llvm::Triple::ppc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">llvm::Triple::ppcle</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">llvm::Triple::r600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">llvm::Triple::riscv32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">llvm::Triple::riscv64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">llvm::Triple::sparc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">llvm::Triple::sparcel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">llvm::Triple::sparcv9</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">llvm::Triple::systemz</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">llvm::Triple::ve</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">llvm::Triple::xtensa</a>.</p>

</div>
</div>

### getBytesInAddress() {#af0baff9952a1ab0ba1c04c142ee5aeee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getBytesInAddress ()</td>
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

<p>The number of bytes used to represent an address in this object file format.</p>

<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a1c3e3311e7ad7f04e507ff2c861d2a0b">llvm::object::ELFObjectFile&lt; ELF32LE &gt;::is64Bit</a>.</p>

</div>
</div>

### getCrel() {#a3e46698fa736bb80c17d882d025b6d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFObjectFile&lt; ELFT &gt;::Elf_Crel llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrel (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Crel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="#ae97c27d726114928e38aff51e6113ee9">llvm::object::ELFObjectFile&lt; ELFT &gt;::Crels</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a91e58df62039bd1c5efc1f2ec5d403a6">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a>.</p>


<p>Referenced by <a href="#a9344d22023aca51c38f99bf5b35c811f">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationAddend</a>, <a href="#a9452290037eaad9ae3c05b7a5ed6133c">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationOffset</a>, <a href="#a319cac7161084045e98652fa736ed8e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationSymbol</a> and <a href="#a15cfaa14709e529b7ea5c52d1cd9bb80">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationType</a>.</p>

</div>
</div>

### getCrelDecodeProblem() {#afff19aa09cf22aea52fde5f561aa0690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrelDecodeProblem (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="#a5d68484baaee7cdf4d1d2157c72c9b8c">llvm::object::ELFObjectFile&lt; ELFT &gt;::CrelDecodeProblems</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>

</div>
</div>

### getDynamicSymbolIterators() {#a33e28ab84959ee02f29b56cd1025034c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFObjectFileBase::elf_symbol_iterator_range llvm::object::ELFObjectFile&lt; ELFT &gt;::getDynamicSymbolIterators ()</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#ada77010d9c8ebda8b2f14e155c56ac3e">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_begin</a>, <a href="#adc6d540d187c8250f636159fb7f2b59f">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### getELFFile() {#a048e38d71ccf2bac0bc8176f16ffc910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ELFFile&lt; ELFT &gt; &amp; llvm::object::ELFObjectFile&lt; ELFT &gt;::getELFFile ()</td>
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



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad4d4b1a08082a48e36079e1725005a2f">llvm::ifs::buildStub</a>.</p>

</div>
</div>

### getFileFormatName() {#a7f800705ddfcafe90204f53339ceb01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::ELFObjectFile&lt; ELFT &gt;::getFileFormatName ()</td>
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



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4848e3ad29a6f6a8216e031204f636e9ac8ef31dee034e9fa40e690a4cdd360de">llvm::ELF::EI_CLASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5ac700ff9a9a24f46587997e131502702c">llvm::ELF::ELFCLASS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5a54b4da97cdda07031363b240c26c9794">llvm::ELF::ELFCLASS64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da6a266f492c600d97849933aad5356be4">llvm::ELF::EM_386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da68081d3eeeb60e9c28bfd47ded6af8cf">llvm::ELF::EM_68K</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dace9c7753eed878839a8fb04768d1436c">llvm::ELF::EM_AARCH64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dafb457612e3f91aca5d93ee2f1de6d4be">llvm::ELF::EM_AMDGPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dae70d9dc0883af67df7d3a1b521031c21">llvm::ELF::EM_ARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daff31d8bd81c175ccbcb24b80abe83f45">llvm::ELF::EM_AVR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da886091c305600f2e4056e5a4bec406f1">llvm::ELF::EM_BPF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da398ae44d88b5e271262866dcaeb64008">llvm::ELF::EM_CSKY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daa4bdb6dee5d86bb842354637ef53e14c">llvm::ELF::EM_HEXAGON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daf94f3540cf7f0fac3c8cf0cdde4e7b46">llvm::ELF::EM_IAMCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daa545d9417959747a17ee926b27a8d36f">llvm::ELF::EM_LANAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da7e72d41153159cd60700a91fa59f6e77">llvm::ELF::EM_LOONGARCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daaf29cd80fceba94e4f48b143fcf354c6">llvm::ELF::EM_MIPS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da0070e5fa94c73580a60f1cc71552f5d1">llvm::ELF::EM_MSP430</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da8a2160f2f630e0ebf2618fbec29150ea">llvm::ELF::EM_PPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da1da82f3b7f3ee5823ee15f4df8ce3d06">llvm::ELF::EM_PPC64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dad426ff446687588ec3a40dee3f6b3598">llvm::ELF::EM_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da0c6bd206dc080750ac4752f6c159e2a5">llvm::ELF::EM_S390</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da2c7a7ca60ce63d4bac4516de29c56145">llvm::ELF::EM_SPARC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da5125c70f3e4d8fc7f4b46aad1358e647">llvm::ELF::EM_SPARC32PLUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dac695bdf043012ff5b3d6ef4287b2639d">llvm::ELF::EM_SPARCV9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daed6f91343936a96682f2ea8f99a7930e">llvm::ELF::EM_VE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daa298f18ed198890cf54b635b54eafee3">llvm::ELF::EM_X86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dad0452e45f1fcaf19e2be8a02f67384a9">llvm::ELF::EM_XTENSA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getOS() {#a1fac5e29bf02a04dd08ec4f3c62e2b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::OSType llvm::object::ELFObjectFile&lt; ELFT &gt;::getOS ()</td>
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



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda55c9e8cff2a0eab89d1b234d419ee93f">llvm::Triple::AIX</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0a0dddcf03f8f66f7c13558b3c81d845">llvm::Triple::AMDHSA</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda7d8eb2c700c876375f588d68dc692f15">llvm::Triple::AMDPAL</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdac81124e2bdd6fb0d7b3fc4bd30233928">llvm::Triple::CUDA</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4848e3ad29a6f6a8216e031204f636e9ad43f8c1b4c159b3097c2004a8efea579">llvm::ELF::EI_OSABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4aaa31a212520f8873c798f07969d51d86">llvm::ELF::ELFOSABI_AIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4a71077267b2389d1de69fe5e5c12dff78">llvm::ELF::ELFOSABI_AMDGPU_HSA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4ad1406c0a44be20c0782bd2d548fe0373">llvm::ELF::ELFOSABI_AMDGPU_MESA3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4afd51206ff16b4be5928dff614b58405e">llvm::ELF::ELFOSABI_AMDGPU_PAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4a47fbf6020f26321c90af2abd86189ce4">llvm::ELF::ELFOSABI_CUDA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4a78245924e20856d9317e537709083772">llvm::ELF::ELFOSABI_FREEBSD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4a19daae637859d1a2a9becaca5b29bc9c">llvm::ELF::ELFOSABI_HURD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4a8101be7aded4969c509bec5335c9c0f1">llvm::ELF::ELFOSABI_LINUX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4a64607c7f2ba8d19ce36fdd4d31ef6e74">llvm::ELF::ELFOSABI_NETBSD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4a484746e3feeafb95b272953d9039db0c">llvm::ELF::ELFOSABI_OPENBSD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4a751e4191f9a44197287300f33a71f320">llvm::ELF::ELFOSABI_SOLARIS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda64fc6929b84f845ced55d3313ebcf423">llvm::Triple::FreeBSD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdaf17d175b40b8e7ceedc92aea3929eb27">llvm::Triple::Hurd</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda76d4dd8dc67e3a11d975743f6d63a9df">llvm::Triple::Linux</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda81cc47a265b37fea8b5b3575b67ea6ed">llvm::Triple::Mesa3D</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdad10d236fcf52bdbf36bd6b401ca9e427">llvm::Triple::NetBSD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda13c01bda5d01cb2264a0cebe7b411c54">llvm::Triple::OpenBSD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdac44628c2fbd9505dc608a330838fccce">llvm::Triple::Solaris</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda4b110a50637320a1a0db33999b809ddd">llvm::Triple::UnknownOS</a>.</p>

</div>
</div>

### getPlatformFlags() {#aaa711ab9b1fbabfc024aa526a54e2056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::object::ELFObjectFile&lt; ELFT &gt;::getPlatformFlags ()</td>
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

<p>Returns platform-specific object flags, if any.</p>

<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### getRel() {#a3d0ec360affeb52e9ce16d7f03b8bd0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ELFObjectFile&lt; ELFT &gt;::Elf_Rel * llvm::object::ELFObjectFile&lt; ELFT &gt;::getRel (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed898e74c946513975b0d7aad4d65e40">llvm::errorToErrorCode</a>, <a href="#a91e58df62039bd1c5efc1f2ec5d403a6">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a>.</p>


<p>Referenced by <a href="#a9452290037eaad9ae3c05b7a5ed6133c">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationOffset</a>, <a href="#a319cac7161084045e98652fa736ed8e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationSymbol</a> and <a href="#a15cfaa14709e529b7ea5c52d1cd9bb80">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationType</a>.</p>

</div>
</div>

### getRela() {#a601dda6211feb315c7ee08b7b18cdcc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ELFObjectFile&lt; ELFT &gt;::Elf_Rela * llvm::object::ELFObjectFile&lt; ELFT &gt;::getRela (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rela)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed898e74c946513975b0d7aad4d65e40">llvm::errorToErrorCode</a>, <a href="#a91e58df62039bd1c5efc1f2ec5d403a6">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a>.</p>


<p>Referenced by <a href="#a9344d22023aca51c38f99bf5b35c811f">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationAddend</a>, <a href="#a9452290037eaad9ae3c05b7a5ed6133c">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationOffset</a>, <a href="#a319cac7161084045e98652fa736ed8e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationSymbol</a> and <a href="#a15cfaa14709e529b7ea5c52d1cd9bb80">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationType</a>.</p>

</div>
</div>

### getRelocationAddend() {#a9344d22023aca51c38f99bf5b35c811f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int64_t &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationAddend (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="#a3e46698fa736bb80c17d882d025b6d5e">llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrel</a>, <a href="#a601dda6211feb315c7ee08b7b18cdcc1">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRela</a>, <a href="#a91e58df62039bd1c5efc1f2ec5d403a6">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a>.</p>

</div>
</div>

### getRelSection() {#a91e58df62039bd1c5efc1f2ec5d403a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Elf_Shdr * llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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

<p>Get the relocation section that contains <em>Rel</em>.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a3e46698fa736bb80c17d882d025b6d5e">llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrel</a>, <a href="#a3d0ec360affeb52e9ce16d7f03b8bd0f">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRel</a>, <a href="#a601dda6211feb315c7ee08b7b18cdcc1">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRela</a>, <a href="#a9344d22023aca51c38f99bf5b35c811f">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationAddend</a>, <a href="#a9452290037eaad9ae3c05b7a5ed6133c">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationOffset</a>, <a href="#a319cac7161084045e98652fa736ed8e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationSymbol</a>, <a href="#a15cfaa14709e529b7ea5c52d1cd9bb80">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationType</a> and <a href="#aca0c5ead089272fe21045ffd6895b298">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_end</a>.</p>

</div>
</div>

### getSection() {#ad3948dea124f86f2acec9ac741d0a003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Elf_Shdr * llvm::object::ELFObjectFile&lt; ELFT &gt;::getSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### getStartAddress() {#af591167c2c7ca37b052f6e9b225e4c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getStartAddress ()</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Reference <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>.</p>

</div>
</div>

### getSymbol() {#a380007d3421e3ea8b92b2a99d3503914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const Elf_Sym * &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sym)</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a4f47a108418b742c0419cc238a0cdebb">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolAddress</a>, <a href="#a784f287bf4c93da1cc4c455e4c41fd94">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolAlignment</a>, <a href="#ac1c87c93f81427748d963d87ba65b21a">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolBinding</a>, <a href="#a19c92b8d9a2449d3b8c4b3de8b5db326">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolELFType</a>, <a href="#a6d7040098bbc2f04e4191b9991a769e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolFlags</a>, <a href="#ab82d11942ddc1cd6df695e3ec80ad39b">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolName</a>, <a href="#a8794e158de6bc5ebb588198cdf868418">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolOther</a>, <a href="#a3859965ea1c713b4c1187bdafba6fa60">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a>, <a href="#ad38d33d56845066a2063cc3896329d03">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolType</a> and <a href="#a4b197578436993f9a0a9753d214822b4">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolValueImpl</a>.</p>

</div>
</div>

### is64Bit() {#a1c3e3311e7ad7f04e507ff2c861d2a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::is64Bit ()</td>
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



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### IsContentValid() {#a2bb517f0216737e6058b65d64516664e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::IsContentValid ()</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### isDyldType() {#a436b47ff384ed39d09f4e2120a7b99a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isDyldType ()</td>
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



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### isRelocatableObject() {#a852d31a92a4f2e97ad2d64360758d5ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isRelocatableObject ()</td>
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

<p>True if this is a relocatable object (.o/.obj).</p>

<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aadbc5ef54c920f724d4e267f41d2c00aaba0cdd056685bc8fe4fab01da806afdc">llvm::ELF::ET_REL</a>.</p>

</div>
</div>

### section\_begin() {#ae648cd200193e29acb9f122298373715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator llvm::object::ELFObjectFile&lt; ELFT &gt;::section_begin ()</td>
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



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a> and <a href="#ae00fd66498ddb379c96552de1ee04062">llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI</a>.</p>

</div>
</div>

### section\_end() {#a88783da09d7c0838a1f8d70545dde91b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator llvm::object::ELFObjectFile&lt; ELFT &gt;::section_end ()</td>
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



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a> and <a href="#ae00fd66498ddb379c96552de1ee04062">llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI</a>.</p>


<p>Referenced by <a href="#a9cb66c2081706fafa8bb7804d9c8b0b3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocatedSection</a> and <a href="#a42018f438c55d2c9c83355e3a8c3cb94">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a>.</p>

</div>
</div>

### symbol\_begin() {#a4df4dd9bdd97616b9710ac0464fa183d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator llvm::object::ELFObjectFile&lt; ELFT &gt;::symbol_begin ()</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a74cc6208555d0a46056d7bf1a2888537">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabSec</a> and <a href="#ae00fd66498ddb379c96552de1ee04062">llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI</a>.</p>


<p>Referenced by <a href="#abefb1aceb82f15c250ab09c759d97273">llvm::object::ELFObjectFile&lt; ELFT &gt;::symbol_end</a>.</p>

</div>
</div>

### symbol\_end() {#abefb1aceb82f15c250ab09c759d97273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator llvm::object::ELFObjectFile&lt; ELFT &gt;::symbol_end ()</td>
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



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a74cc6208555d0a46056d7bf1a2888537">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabSec</a>, <a href="#a4df4dd9bdd97616b9710ac0464fa183d">llvm::object::ELFObjectFile&lt; ELFT &gt;::symbol_begin</a> and <a href="#ae00fd66498ddb379c96552de1ee04062">llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI</a>.</p>


<p>Referenced by <a href="#a319cac7161084045e98652fa736ed8e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationSymbol</a>.</p>

</div>
</div>

### toSectionRef() {#a26a8b66384eac1604e4ce7bd35bb6878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionRef llvm::object::ELFObjectFile&lt; ELFT &gt;::toSectionRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * Sec)</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### toSymbolRef() {#a5247b35d5fcc7e4087e2db32a4210c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFSymbolRef llvm::object::ELFObjectFile&lt; ELFT &gt;::toSymbolRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * SymTable, unsigned SymbolNum)</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### dynamic\_relocation\_sections() {#a1300a4c221076a37306ccd4eb96b2e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; SectionRef &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_relocation_sections ()</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca971fd8cc345d8bd9f92e9f7d88fdf20c">llvm::Dynamic</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca8c63cb324623b483b1b1b1fb1b575447">llvm::ELF::SHT_DYNAMIC</a> and <a href="#ae00fd66498ddb379c96552de1ee04062">llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI</a>.</p>

</div>
</div>

### getBuildAttributes() {#ad4f1deb260cb6fd64575135be5a3d25f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::ELFObjectFile&lt; ELFT &gt;::getBuildAttributes (<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser">ELFAttributeParser</a> &amp; Attributes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### getCommonSymbolSizeImpl() {#a7a74cdab4ba5f0146a2444c6c4d29b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getCommonSymbolSizeImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### getRelocatedSection() {#a9cb66c2081706fafa8bb7804d9c8b0b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocatedSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="#a88783da09d7c0838a1f8d70545dde91b">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#ae00fd66498ddb379c96552de1ee04062">llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI</a>.</p>

</div>
</div>

### getRelocationOffset() {#a9452290037eaad9ae3c05b7a5ed6133c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationOffset (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a3e46698fa736bb80c17d882d025b6d5e">llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrel</a>, <a href="#a3d0ec360affeb52e9ce16d7f03b8bd0f">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRel</a>, <a href="#a601dda6211feb315c7ee08b7b18cdcc1">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRela</a>, <a href="#a91e58df62039bd1c5efc1f2ec5d403a6">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a>.</p>

</div>
</div>

### getRelocationSymbol() {#a319cac7161084045e98652fa736ed8e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_iterator llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationSymbol (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="#a3e46698fa736bb80c17d882d025b6d5e">llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrel</a>, <a href="#a3d0ec360affeb52e9ce16d7f03b8bd0f">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRel</a>, <a href="#a601dda6211feb315c7ee08b7b18cdcc1">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRela</a>, <a href="#a91e58df62039bd1c5efc1f2ec5d403a6">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a> and <a href="#abefb1aceb82f15c250ab09c759d97273">llvm::object::ELFObjectFile&lt; ELFT &gt;::symbol_end</a>.</p>

</div>
</div>

### getRelocationType() {#a15cfaa14709e529b7ea5c52d1cd9bb80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="#a3e46698fa736bb80c17d882d025b6d5e">llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrel</a>, <a href="#a3d0ec360affeb52e9ce16d7f03b8bd0f">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRel</a>, <a href="#a601dda6211feb315c7ee08b7b18cdcc1">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRela</a>, <a href="#a91e58df62039bd1c5efc1f2ec5d403a6">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a>.</p>


<p>Referenced by <a href="#a6bf6040a258d1e795595c91c82d4635a">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationTypeName</a>.</p>

</div>
</div>

### getRelocationTypeName() {#a6bf6040a258d1e795595c91c82d4635a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationTypeName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Result)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a> and <a href="#a15cfaa14709e529b7ea5c52d1cd9bb80">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationType</a>.</p>

</div>
</div>

### getRelocationTypeName() {#a3bbfa07784d5a4f7f0217ee54514ac21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationTypeName (uint32_t Type)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a26dff1f08cc67aef943d43c26f6d635a">llvm::object::getELFRelocationTypeName</a>.</p>

</div>
</div>

### getSectionAddress() {#a691f9ee3cc6ab7a16a223d713dbc46eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>.</p>

</div>
</div>

### getSectionAlignment() {#a1a1351e82d9cbc15e5b1df7bc88fc8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>.</p>

</div>
</div>

### getSectionContents() {#a6aa9147fe46df8a395d32bfcfb7585bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionContents (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#afc55f34d54c38dcea2d603b5dd7c902f">llvm::object::Binary::checkOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac0322f1809be8f6f88af125c1956c9a1">llvm::object::Binary::getMemoryBufferRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>.</p>


<p>Referenced by <a href="#ab4f09c74a59f0465db07fe6b95233878">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_begin</a>.</p>

</div>
</div>

### getSectionFlags() {#aaab62140bd37d2d31eab0d8e84148883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>.</p>

</div>
</div>

### getSectionIndex() {#a6c1a5fe426bd8ab30f4a7d5fe83e4ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionIndex (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>.</p>

</div>
</div>

### getSectionName() {#a051bc7c48ec863294318a92b616739b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>.</p>

</div>
</div>

### getSectionOffset() {#ac85e557d61ba57ac514dfb6c4482056c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionOffset (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>.</p>

</div>
</div>

### getSectionSize() {#a7dc02eb7ee0d57e4f38a1e5c68113057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionSize (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>.</p>

</div>
</div>

### getSectionType() {#a2be82e45724555e77b4c06e56a65bb4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>.</p>

</div>
</div>

### getSymbolAddress() {#a4f47a108418b742c0419cc238a0cdebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#adc31179fa21b266172586d580f9e51b0">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabShndxSec</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aadbc5ef54c920f724d4e267f41d2c00aaba0cdd056685bc8fe4fab01da806afdc">llvm::ELF::ET_REL</a>, <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a2ffc6774a44004d9673c9fc04fcd01af">getSymbolValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a319b64bc6b9c38e948eda8bfafff58b5">llvm::ELF::SHN_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a39083466eebf0993a765922244288d20">llvm::ELF::SHN_COMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolAlignment() {#a784f287bf4c93da1cc4c455e4c41fd94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a39083466eebf0993a765922244288d20">llvm::ELF::SHN_COMMON</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolBinding() {#ac1c87c93f81427748d963d87ba65b21a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolBinding (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolELFType() {#a19c92b8d9a2449d3b8c4b3de8b5db326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolELFType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolFlags() {#a6d7040098bbc2f04e4191b9991a769e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#a771c752c0df8994c1fd0ab9c300bb5cf">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotDynSymSec</a>, <a href="#a74cc6208555d0a46056d7bf1a2888537">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabSec</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dace9c7753eed878839a8fb04768d1436c">llvm::ELF::EM_AARCH64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dae70d9dc0883af67df7d3a1b521031c21">llvm::ELF::EM_ARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da398ae44d88b5e271262866dcaeb64008">llvm::ELF::EM_CSKY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dad426ff446687588ec3a40dee3f6b3598">llvm::ELF::EM_RISCV</a>, <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#a28913db87cd89255cef33ba3133945b8">getSymbolName</a>, <a href="#a67de91533b4746c8c320bea8e517de4a">llvm::object::ELFObjectFile&lt; ELFT &gt;::isExportedToOtherDSO</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431acc6eb3e8d6f0fb38a6f3eb9ddef198af">llvm::object::BasicSymbolRef::SF_Absolute</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a3936e16c4ba4b109e74006ad9bdc06f8">llvm::object::BasicSymbolRef::SF_Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac0848bf2e216fe6f4664820d93ab7265">llvm::object::BasicSymbolRef::SF_FormatSpecific</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a204140e5ce85b4dc444bf37cb0d8e402">llvm::object::BasicSymbolRef::SF_Hidden</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a9660b615b36c70668b966e987719d9d6">llvm::object::BasicSymbolRef::SF_Indirect</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1cfe0c449b3dd82ae0eaeff1da6f766">llvm::object::BasicSymbolRef::SF_None</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a586a24e61bc504778e4c89c8bb929e90">llvm::object::BasicSymbolRef::SF_Thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a319b64bc6b9c38e948eda8bfafff58b5">llvm::ELF::SHN_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a39083466eebf0993a765922244288d20">llvm::ELF::SHN_COMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77afb3fa0269fc31b10834def07f16c1649">llvm::ELF::STB_WEAK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a6fb5d8136ffc8cfccf0425682fae235f">llvm::ELF::STT_COMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a58921cad23ba8bdf0c8077b7a2923127">llvm::ELF::STT_FILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a7269ceaea4bf3dbd15caa427598cbcb9">llvm::ELF::STT_GNU_IFUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5ab38517de2fd6c124c49e40bc25c25c0c">llvm::ELF::STV_HIDDEN</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolName() {#ab82d11942ddc1cd6df695e3ec80ad39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="#a42018f438c55d2c9c83355e3a8c3cb94">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolOther() {#a8794e158de6bc5ebb588198cdf868418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolOther (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolSection() {#a42018f438c55d2c9c83355e3a8c3cb94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Sym * Symb, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * SymTab)</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#adc31179fa21b266172586d580f9e51b0">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabShndxSec</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="#a88783da09d7c0838a1f8d70545dde91b">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_end</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#ab82d11942ddc1cd6df695e3ec80ad39b">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolName</a> and <a href="#a3859965ea1c713b4c1187bdafba6fa60">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a>.</p>

</div>
</div>

### getSymbolSection() {#a3859965ea1c713b4c1187bdafba6fa60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="#a42018f438c55d2c9c83355e3a8c3cb94">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolType() {#ad38d33d56845066a2063cc3896329d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolRef::Type &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a8a501fedaaa3e562541580b8f1db3975">llvm::object::SymbolRef::ST_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04afe6722fa933ffee4c116ee60c2de5049">llvm::object::SymbolRef::ST_Debug</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a771f3523463fc179b4e89f60841a23b8">llvm::object::SymbolRef::ST_File</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a076f193658db35c0f4d60f9e0a3e329f">llvm::object::SymbolRef::ST_Other</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2d334a713a4916963744a0cc31ab9552">llvm::object::SymbolRef::ST_Unknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a6fb5d8136ffc8cfccf0425682fae235f">llvm::ELF::STT_COMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a58921cad23ba8bdf0c8077b7a2923127">llvm::ELF::STT_FILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a2addd3222711e927ec6604bc65bccb2c">llvm::ELF::STT_NOTYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a9803bad2cfdce7601000ee3f6b979d9b">llvm::ELF::STT_OBJECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179ab453d9dfef54b0c7fd0cbaf82b4ba9d6">llvm::ELF::STT_TLS</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolValueImpl() {#a4b197578436993f9a0a9753d214822b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolValueImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dae70d9dc0883af67df7d3a1b521031c21">llvm::ELF::EM_ARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daaf29cd80fceba94e4f48b143fcf354c6">llvm::ELF::EM_MIPS</a>, <a href="#a380007d3421e3ea8b92b2a99d3503914">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a319b64bc6b9c38e948eda8bfafff58b5">llvm::ELF::SHN_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### initContent() {#abda9cbfc7a332979538e75a0d52f7fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::ELFObjectFile&lt; ELFT &gt;::initContent ()</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a771c752c0df8994c1fd0ab9c300bb5cf">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotDynSymSec</a>, <a href="#a74cc6208555d0a46056d7bf1a2888537">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabSec</a>, <a href="#adc31179fa21b266172586d580f9e51b0">llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabShndxSec</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcadb5044a1bd05d2a84193fb0eb9b9df12">llvm::ELF::SHT_DYNSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca4f0cd819b71791cb5a1945952dbc9166">llvm::ELF::SHT_SYMTAB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca973f4a1893cca71a0ec69aa145189486">llvm::ELF::SHT_SYMTAB_SHNDX</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a65d9c3a1e8cb5fe3e06486957ea45fbb">llvm::object::ELFObjectFile&lt; ELFT &gt;::create</a>.</p>

</div>
</div>

### isBerkeleyData() {#a7ef4e220ea14cc91dcfa99884aa627e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isBerkeleyData (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="#aeb51b7c07d49924799bbf0a7f8f8d265">llvm::object::ELFObjectFile&lt; ELFT &gt;::isBerkeleyText</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>.</p>

</div>
</div>

### isBerkeleyText() {#aeb51b7c07d49924799bbf0a7f8f8d265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isBerkeleyText (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>.</p>


<p>Referenced by <a href="#a7ef4e220ea14cc91dcfa99884aa627e4">llvm::object::ELFObjectFile&lt; ELFT &gt;::isBerkeleyData</a>.</p>

</div>
</div>

### isDebugSection() {#ae62484c71e9b9ab034fe9a10717fa718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isDebugSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a2da32c7f0735e4bcb64c34222a79a6c1">llvm::dwarf_linker::getSectionName</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### isExportedToOtherDSO() {#a67de91533b4746c8c320bea8e517de4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isExportedToOtherDSO (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Sym * ESym)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a6d7040098bbc2f04e4191b9991a769e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolFlags</a>.</p>

</div>
</div>

### isSectionBSS() {#aa270392082b5912cf2adaec08da203c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isSectionBSS (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>.</p>

</div>
</div>

### isSectionCompressed() {#ae831a9c23d4063e07c13f8f03cd1f1f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isSectionCompressed (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015abf799091c82aff654ed25824e734ffcc">llvm::ELF::SHF_COMPRESSED</a>.</p>

</div>
</div>

### isSectionData() {#a73870a9eff6636a746979c4f968a1ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isSectionData (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>.</p>

</div>
</div>

### isSectionText() {#a16c5ac6875015c495c671b56e3ecd0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isSectionText (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a>.</p>

</div>
</div>

### isSectionVirtual() {#a1fa4ba92d78835f1fa8d4d7fa2eab0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isSectionVirtual (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>.</p>

</div>
</div>

### moveRelocationNext() {#aaff3a188e4b250ad59461b8687ca3354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ELFObjectFile&lt; ELFT &gt;::moveRelocationNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Rel)</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### moveSectionNext() {#aa24b98f2423948931bb4fb8b50ca9cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ELFObjectFile&lt; ELFT &gt;::moveSectionNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Sec)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="#ae00fd66498ddb379c96552de1ee04062">llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI</a>.</p>

</div>
</div>

### moveSymbolNext() {#a85fb90e445dc6273e7820231a50a981b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::ELFObjectFile&lt; ELFT &gt;::moveSymbolNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Symb)</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### section\_rel\_begin() {#ab4f09c74a59f0465db07fe6b95233878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_begin (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a5d68484baaee7cdf4d1d2157c72c9b8c">llvm::object::ELFObjectFile&lt; ELFT &gt;::CrelDecodeProblems</a>, <a href="#ae97c27d726114928e38aff51e6113ee9">llvm::object::ELFObjectFile&lt; ELFT &gt;::Crels</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab0f852d38471e3013e30ec9c1241edfe">llvm::object::decodeCrel</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="#a6aa9147fe46df8a395d32bfcfb7585bd">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a>.</p>


<p>Referenced by <a href="#aca0c5ead089272fe21045ffd6895b298">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_end</a>.</p>

</div>
</div>

### section\_rel\_end() {#aca0c5ead089272fe21045ffd6895b298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_end (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="#ae97c27d726114928e38aff51e6113ee9">llvm::object::ELFObjectFile&lt; ELFT &gt;::Crels</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a2a5b26201d2bc89a8bb7c89ff02f4866">llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed898e74c946513975b0d7aad4d65e40">llvm::errorToErrorCode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#acd93a9353f94b029cdfa295b88874b38">llvm::object::RelocationRef::getRawDataRefImpl</a>, <a href="#a91e58df62039bd1c5efc1f2ec5d403a6">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelSection</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#ab4f09c74a59f0465db07fe6b95233878">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a>.</p>

</div>
</div>

### toDRI() {#ae00fd66498ddb379c96552de1ee04062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * SymTable, unsigned SymbolNum)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a1300a4c221076a37306ccd4eb96b2e2a">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_relocation_sections</a>, <a href="#ada77010d9c8ebda8b2f14e155c56ac3e">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_begin</a>, <a href="#adc6d540d187c8250f636159fb7f2b59f">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_end</a>, <a href="#a9cb66c2081706fafa8bb7804d9c8b0b3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocatedSection</a>, <a href="#aa24b98f2423948931bb4fb8b50ca9cf4">llvm::object::ELFObjectFile&lt; ELFT &gt;::moveSectionNext</a>, <a href="#ae648cd200193e29acb9f122298373715">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_begin</a>, <a href="#a88783da09d7c0838a1f8d70545dde91b">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_end</a>, <a href="#a4df4dd9bdd97616b9710ac0464fa183d">llvm::object::ELFObjectFile&lt; ELFT &gt;::symbol_begin</a>, <a href="#abefb1aceb82f15c250ab09c759d97273">llvm::object::ELFObjectFile&lt; ELFT &gt;::symbol_end</a>, <a href="#a26a8b66384eac1604e4ce7bd35bb6878">llvm::object::ELFObjectFile&lt; ELF32LE &gt;::toSectionRef</a> and <a href="#a5247b35d5fcc7e4087e2db32a4210c66">llvm::object::ELFObjectFile&lt; ELF32LE &gt;::toSymbolRef</a>.</p>

</div>
</div>

### toDRI() {#ad912f79fa206416af9b82b3532b8e5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Shdr * Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### toDRI() {#a1cddf7fbb62a4bd40c06942b513b2e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::ELFObjectFile&lt; ELFT &gt;::toDRI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Elf_Dyn * Dyn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### toELFShdrIter() {#a790f65b9fc4ad4683fdb5498a2252cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Elf_Shdr * llvm::object::ELFObjectFile&lt; ELFT &gt;::toELFShdrIter (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getEIdentABIVersion() {#a7c07fc16d5dd80c0312dacd9c3a1b7b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getEIdentABIVersion ()</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### getEMachine() {#addc7322bab6b111283196697a10fe0d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getEMachine ()</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### getEType() {#a136b0cad5fd4a02ae821f2f1bfc436f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getEType ()</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### getSymbolSize() {#af506559607adac6ce0063e2717f6e3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSize (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sym)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CrelDecodeProblems {#a5d68484baaee7cdf4d1d2157c72c9b8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::string, 0&gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::CrelDecodeProblems</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#afff19aa09cf22aea52fde5f561aa0690">llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrelDecodeProblem</a> and <a href="#ab4f09c74a59f0465db07fe6b95233878">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_begin</a>.</p>

</div>
</div>

### Crels {#ae97c27d726114928e38aff51e6113ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SmallVector&lt;Elf_Crel, 0&gt;, 0&gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::Crels</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a3e46698fa736bb80c17d882d025b6d5e">llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrel</a>, <a href="#ab4f09c74a59f0465db07fe6b95233878">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_begin</a> and <a href="#aca0c5ead089272fe21045ffd6895b298">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_end</a>.</p>

</div>
</div>

### DotDynSymSec {#a771c752c0df8994c1fd0ab9c300bb5cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Elf_Shdr* llvm::object::ELFObjectFile&lt; ELFT &gt;::DotDynSymSec = nullptr</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#ada77010d9c8ebda8b2f14e155c56ac3e">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_begin</a>, <a href="#adc6d540d187c8250f636159fb7f2b59f">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_symbol_end</a>, <a href="#a3ef3a0df77100e5a640653d0c2336df7">llvm::object::ELFObjectFile&lt; ELFT &gt;::ELFObjectFile</a>, <a href="#a6d7040098bbc2f04e4191b9991a769e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolFlags</a> and <a href="#abda9cbfc7a332979538e75a0d52f7fdc">llvm::object::ELFObjectFile&lt; ELFT &gt;::initContent</a>.</p>

</div>
</div>

### DotSymtabSec {#a74cc6208555d0a46056d7bf1a2888537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Elf_Shdr* llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabSec = nullptr</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a3ef3a0df77100e5a640653d0c2336df7">llvm::object::ELFObjectFile&lt; ELFT &gt;::ELFObjectFile</a>, <a href="#a6d7040098bbc2f04e4191b9991a769e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolFlags</a>, <a href="#abda9cbfc7a332979538e75a0d52f7fdc">llvm::object::ELFObjectFile&lt; ELFT &gt;::initContent</a>, <a href="#a4df4dd9bdd97616b9710ac0464fa183d">llvm::object::ELFObjectFile&lt; ELFT &gt;::symbol_begin</a> and <a href="#abefb1aceb82f15c250ab09c759d97273">llvm::object::ELFObjectFile&lt; ELFT &gt;::symbol_end</a>.</p>

</div>
</div>

### DotSymtabShndxSec {#adc31179fa21b266172586d580f9e51b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Elf_Shdr* llvm::object::ELFObjectFile&lt; ELFT &gt;::DotSymtabShndxSec = nullptr</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a3ef3a0df77100e5a640653d0c2336df7">llvm::object::ELFObjectFile&lt; ELFT &gt;::ELFObjectFile</a>, <a href="#a4f47a108418b742c0419cc238a0cdebb">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolAddress</a>, <a href="#a42018f438c55d2c9c83355e3a8c3cb94">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a> and <a href="#abda9cbfc7a332979538e75a0d52f7fdc">llvm::object::ELFObjectFile&lt; ELFT &gt;::initContent</a>.</p>

</div>
</div>

### EF {#a2a5b26201d2bc89a8bb7c89ff02f4866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFFile&lt;ELFT&gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::EF</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a1300a4c221076a37306ccd4eb96b2e2a">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_relocation_sections</a>, <a href="#a3ef3a0df77100e5a640653d0c2336df7">llvm::object::ELFObjectFile&lt; ELFT &gt;::ELFObjectFile</a>, <a href="#a7a01300e2d307f9b0804e765f3c7be7e">llvm::object::ELFObjectFile&lt; ELFT &gt;::getArch</a>, <a href="#afff19aa09cf22aea52fde5f561aa0690">llvm::object::ELFObjectFile&lt; ELFT &gt;::getCrelDecodeProblem</a>, <a href="#a7f800705ddfcafe90204f53339ceb01a">llvm::object::ELFObjectFile&lt; ELFT &gt;::getFileFormatName</a>, <a href="#a1fac5e29bf02a04dd08ec4f3c62e2b92">llvm::object::ELFObjectFile&lt; ELFT &gt;::getOS</a>, <a href="#a3d0ec360affeb52e9ce16d7f03b8bd0f">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRel</a>, <a href="#a601dda6211feb315c7ee08b7b18cdcc1">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRela</a>, <a href="#a9cb66c2081706fafa8bb7804d9c8b0b3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocatedSection</a>, <a href="#a319cac7161084045e98652fa736ed8e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationSymbol</a>, <a href="#a15cfaa14709e529b7ea5c52d1cd9bb80">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationType</a>, <a href="#a6bf6040a258d1e795595c91c82d4635a">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationTypeName</a>, <a href="#a3bbfa07784d5a4f7f0217ee54514ac21">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocationTypeName</a>, <a href="#a6c1a5fe426bd8ab30f4a7d5fe83e4ab7">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionIndex</a>, <a href="#a051bc7c48ec863294318a92b616739b3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionName</a>, <a href="#af591167c2c7ca37b052f6e9b225e4c3c">llvm::object::ELFObjectFile&lt; ELFT &gt;::getStartAddress</a>, <a href="#a4f47a108418b742c0419cc238a0cdebb">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolAddress</a>, <a href="#a6d7040098bbc2f04e4191b9991a769e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolFlags</a>, <a href="#ab82d11942ddc1cd6df695e3ec80ad39b">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolName</a>, <a href="#a42018f438c55d2c9c83355e3a8c3cb94">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a>, <a href="#a3859965ea1c713b4c1187bdafba6fa60">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a>, <a href="#a4b197578436993f9a0a9753d214822b4">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolValueImpl</a>, <a href="#abda9cbfc7a332979538e75a0d52f7fdc">llvm::object::ELFObjectFile&lt; ELFT &gt;::initContent</a>, <a href="#a852d31a92a4f2e97ad2d64360758d5ec">llvm::object::ELFObjectFile&lt; ELFT &gt;::isRelocatableObject</a>, <a href="#ae648cd200193e29acb9f122298373715">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_begin</a>, <a href="#a88783da09d7c0838a1f8d70545dde91b">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_end</a>, <a href="#ab4f09c74a59f0465db07fe6b95233878">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_begin</a> and <a href="#aca0c5ead089272fe21045ffd6895b298">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_end</a>.</p>

</div>
</div>

### isDyldELFObject {#a21a7e8753647ddac0219c5c6423184a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::isDyldELFObject = false</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ContentValid {#afd7ae170d26c1b6a7397a13ed124b40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::ContentValid = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a01e1316c81b78deca5cf4ebbc2d0c0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ELFObjectFile&lt; ELFT &gt;::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>

</div>
</div>

### create() {#a65d9c3a1e8cb5fe3e06486957ea45fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ELFObjectFile&lt; ELFT &gt; &gt; llvm::object::ELFObjectFile&lt; ELFT &gt;::create (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, bool InitContent=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a0c43c56d0ce8c5e87d92506d7b567a5b">llvm::object::ELFFile&lt; ELFT &gt;::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="#abda9cbfc7a332979538e75a0d52f7fdc">llvm::object::ELFObjectFile&lt; ELFT &gt;::initContent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#a595f1eb44be7dd8b0cad008384c9d721">createPtr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
