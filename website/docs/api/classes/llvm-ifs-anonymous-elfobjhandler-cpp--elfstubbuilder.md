---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfstubbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ELFStubBuilder` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;class ELFT&gt;
class llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt;ELFT&gt; { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a97f1e98e16fa0aa2e63d6007e32e621b">Elf_Ehdr</a> = typename ELFT::Ehdr</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a918e0bb0730e82fd6d8dc2428f2ff888">Elf_Shdr</a> = typename ELFT::Shdr</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abdfb461c7f9ef26ed7c93e39c342b9bb">Elf_Phdr</a> = typename ELFT::Phdr</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9573a5d90679d07ae450b2fff986047e">Elf_Sym</a> = typename ELFT::Sym</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a606278d4e3080fcf867637e035054779">Elf_Addr</a> = typename ELFT::Addr</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acfa7d6331b5a5a2a45691a755c813118">Elf_Dyn</a> = typename ELFT::Dyn</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4d6349fba03a4cba723fdb92da177e23">ELFStubBuilder</a> (const ELFStubBuilder &amp;)=delete</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0ad8cb2a0cd2ad9e58e814b8639b4695">ELFStubBuilder</a> (ELFStubBuilder &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a194076a5f7e07b8239271bf1d134c0b4">ELFStubBuilder</a> (const IFSStub &amp;Stub)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9e2aaf14f3cc9e2e9134aec542a07e54">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae94020185e3837a586b3ae6288d80044">write</a> (uint8_t *Data) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abaf797b8fb7a57492156e6a902c72b78">fillStrTabShdr</a> (ContentSection&lt; ELFStringTableBuilder, ELFT &gt; &amp;StrTab, uint32_t ShFlags=0) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aedbb3df29651b6a11275fbbbe441653f">fillSymTabShdr</a> (ContentSection&lt; ELFSymbolTableBuilder&lt; ELFT &gt;, ELFT &gt; &amp;SymTab, uint32_t ShType) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a94c3e45bb89a8da776d6a4df0ecfb253">fillDynTabShdr</a> (ContentSection&lt; ELFDynamicTableBuilder&lt; ELFT &gt;, ELFT &gt; &amp;DynTab) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04fd7a7917beb2c8826c5af0729355fb">shdrOffset</a> (const OutputSection&lt; ELFT &gt; &amp;Sec) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af56511bea5faa2c0d904981fb84ed4d8">writeShdr</a> (uint8_t *Data, const OutputSection&lt; ELFT &gt; &amp;Sec) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a97f1e98e16fa0aa2e63d6007e32e621b">Elf_Ehdr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f24f5d627a83472dd00e92a4218d0db">ElfHeader</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/contentsection">ContentSection</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfstringtablebuilder">ELFStringTableBuilder</a>, ELFT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4922b9775c2936234e6f3b1afe981ad3">DynStr</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/contentsection">ContentSection</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfstringtablebuilder">ELFStringTableBuilder</a>, ELFT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adbd3ead456f10f68500520b88eabd902">ShStrTab</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/contentsection">ContentSection</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfsymboltablebuilder">ELFSymbolTableBuilder</a>&lt; ELFT &gt;, ELFT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b753c0a37602373d5686d8622576994">DynSym</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/contentsection">ContentSection</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfdynamictablebuilder">ELFDynamicTableBuilder</a>&lt; ELFT &gt;, ELFT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abbc9571012102b3059f52181b980cd7b">DynTab</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a18ec0d2f09d58eada00048f277d17fd3">write</a> (uint8_t *Data, const T &amp;Value)</td>
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


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Elf\_Addr {#a606278d4e3080fcf867637e035054779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::Elf_Addr =  typename ELFT::Addr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### Elf\_Dyn {#acfa7d6331b5a5a2a45691a755c813118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::Elf_Dyn =  typename ELFT::Dyn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### Elf\_Ehdr {#a97f1e98e16fa0aa2e63d6007e32e621b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::Elf_Ehdr =  typename ELFT::Ehdr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### Elf\_Phdr {#abdfb461c7f9ef26ed7c93e39c342b9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::Elf_Phdr =  typename ELFT::Phdr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### Elf\_Shdr {#a918e0bb0730e82fd6d8dc2428f2ff888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::Elf_Shdr =  typename ELFT::Shdr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### Elf\_Sym {#a9573a5d90679d07ae450b2fff986047e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::Elf_Sym =  typename ELFT::Sym</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ELFStubBuilder() {#a4d6349fba03a4cba723fdb92da177e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::ELFStubBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfstubbuilder">ELFStubBuilder</a> &amp;)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>


<p>Reference <a href="#a4d6349fba03a4cba723fdb92da177e23">llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::ELFStubBuilder</a>.</p>


<p>Referenced by <a href="#a4d6349fba03a4cba723fdb92da177e23">llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::ELFStubBuilder</a> and <a href="#a0ad8cb2a0cd2ad9e58e814b8639b4695">llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::ELFStubBuilder</a>.</p>

</div>
</div>

### ELFStubBuilder() {#a0ad8cb2a0cd2ad9e58e814b8639b4695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::ELFStubBuilder (<a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfstubbuilder">ELFStubBuilder</a> &amp;&amp;)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>


<p>Reference <a href="#a4d6349fba03a4cba723fdb92da177e23">llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::ELFStubBuilder</a>.</p>

</div>
</div>

### ELFStubBuilder() {#a194076a5f7e07b8239271bf1d134c0b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::ELFStubBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/ifs/ifsstub">IFSStub</a> &amp; Stub)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/ifstarget/#af379bbc9af91abe4a488fb655778193c">llvm::ifs::IFSTarget::Arch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#aba771dce7043e25079c752870c254b85">llvm::ifs::convertIFSSymbolTypeToELF</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/outputsection/#a12ea06b90a0a78044f9a59cfe33a738f">llvm::ifs::anonymous{ELFObjHandler.cpp}::OutputSection&lt; ELFT &gt;::Index</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#af09bd2faf3988ebd053e331ead3bd55d">llvm::ifs::initELFHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/ifssymbol/#a7829f6a04e270a8d883ad63527d20fb2">llvm::ifs::IFSSymbol::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/ifsstub/#af56454051b29ead6e134477ed293e398">llvm::ifs::IFSStub::NeededLibs</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/outputsection/#a6a0f189619106eac58dc6265ffcd7c0f">llvm::ifs::anonymous{ELFObjHandler.cpp}::OutputSection&lt; ELFT &gt;::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcadb5044a1bd05d2a84193fb0eb9b9df12">llvm::ELF::SHT_DYNSYM</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/outputsection/#ab0f34431af795d93fb0571b3a2644864">llvm::ifs::anonymous{ELFObjHandler.cpp}::OutputSection&lt; ELFT &gt;::Size</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/ifssymbol/#aa86bfa354c2d5f829acfdc7299e44504">llvm::ifs::IFSSymbol::Size</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/ifsstub/#aecc734b33c3ef5d93a4d1a5b92ac6497">llvm::ifs::IFSStub::SoName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77afb3fa0269fc31b10834def07f16c1649">llvm::ELF::STB_WEAK</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/ifsstub/#a7042a2978ba2a5a9d8016bf066c6bc19">llvm::ifs::IFSStub::Symbols</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/ifsstub/#ae605540b36465d45ea9d68b803aab919">llvm::ifs::IFSStub::Target</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/ifssymbol/#a48ee2615146aa13d99d842fafbfd3b95">llvm::ifs::IFSSymbol::Type</a>, <a href="/web-llvm/docs/api/structs/llvm/ifs/ifssymbol/#a33a377541312be8ff8d1ecf7b2d523b1">llvm::ifs::IFSSymbol::Undefined</a> and <a href="/web-llvm/docs/api/structs/llvm/ifs/ifssymbol/#afe40967856915a99cf897560395d720f">llvm::ifs::IFSSymbol::Weak</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSize() {#a9e2aaf14f3cc9e2e9134aec542a07e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::getSize ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### write() {#ae94020185e3837a586b3ae6288d80044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::write (uint8_t * Data)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### fillDynTabShdr() {#a94c3e45bb89a8da776d6a4df0ecfb253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::fillDynTabShdr (<a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/contentsection">ContentSection</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfdynamictablebuilder">ELFDynamicTableBuilder</a>&lt; ELFT &gt;, ELFT &gt; &amp; DynTab)</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### fillStrTabShdr() {#abaf797b8fb7a57492156e6a902c72b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::fillStrTabShdr (<a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/contentsection">ContentSection</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfstringtablebuilder">ELFStringTableBuilder</a>, ELFT &gt; &amp; StrTab, uint32_t ShFlags=0)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### fillSymTabShdr() {#aedbb3df29651b6a11275fbbbe441653f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::fillSymTabShdr (<a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/contentsection">ContentSection</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfsymboltablebuilder">ELFSymbolTableBuilder</a>&lt; ELFT &gt;, ELFT &gt; &amp; SymTab, uint32_t ShType)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### shdrOffset() {#a04fd7a7917beb2c8826c5af0729355fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::shdrOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/outputsection">OutputSection</a>&lt; ELFT &gt; &amp; Sec)</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### writeShdr() {#af56511bea5faa2c0d904981fb84ed4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::writeShdr (uint8_t * Data, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/ifs/anonymous-elfobjhandler-cpp-/outputsection">OutputSection</a>&lt; ELFT &gt; &amp; Sec)</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DynStr {#a4922b9775c2936234e6f3b1afe981ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContentSection&lt;ELFStringTableBuilder, ELFT&gt; llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::DynStr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### DynSym {#a1b753c0a37602373d5686d8622576994}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContentSection&lt;ELFSymbolTableBuilder&lt;ELFT&gt;, ELFT&gt; llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::DynSym</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### DynTab {#abbc9571012102b3059f52181b980cd7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContentSection&lt;ELFDynamicTableBuilder&lt;ELFT&gt;, ELFT&gt; llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::DynTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### ElfHeader {#a0f24f5d627a83472dd00e92a4218d0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf_Ehdr llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::ElfHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

### ShStrTab {#adbd3ead456f10f68500520b88eabd902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContentSection&lt;ELFStringTableBuilder, ELFT&gt; llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::ShStrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### write() {#a18ec0d2f09d58eada00048f277d17fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStubBuilder&lt; ELFT &gt;::write (uint8_t * Data, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Value)</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/interfacestub/elfobjhandler-cpp">ELFObjHandler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
