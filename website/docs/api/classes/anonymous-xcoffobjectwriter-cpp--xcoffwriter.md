---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-xcoffobjectwriter-cpp-/xcoffwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XCOFFWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xcoffobjectwriter">XCOFFObjectWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a120cd2ed610d49b8b5549ca0868442c0">XCOFFWriter</a> (std::unique_ptr&lt; MCXCOFFObjectTargetWriter &gt; MOTW, raw_pwrite_stream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba20d7d48fbb17155fa17029e3475835">writeWord</a> (uint64_t Word)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef1741206324d286d02bd789ce323c2">addExceptionEntry</a> (const MCSymbol *Symbol, const MCSymbol *Trap, unsigned LanguageCode, unsigned ReasonCode, unsigned FunctionSize, bool hasDebug) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5652e69f3752a2629b5515fa76375b1f">addCInfoSymEntry</a> (StringRef Name, StringRef Metadata) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d54940f001df13dfb998f4fe5ae03b6">getCsectGroup</a> (const MCSectionXCOFF *MCSec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cad0ef5ee318537a1eb77063c051efa">reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lifetime management <a href="#a4cad0ef5ee318537a1eb77063c051efa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9982ecb527f13d39c465f2ee820b633">executePostLayoutBinding</a> (MCAssembler &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform any late binding of symbols (for example, to assign symbol indices for use when generating relocations). <a href="#af9982ecb527f13d39c465f2ee820b633">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63e780799b26c54712926c20e2c6d565">recordRelocation</a> (MCAssembler &amp;, const MCFragment *, const MCFixup &amp;, MCValue, uint64_t &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Record a relocation entry. <a href="#a63e780799b26c54712926c20e2c6d565">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a001f3e654c646a90e46986c7e8c0ce13">writeObject</a> (MCAssembler &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the object file and returns the number of bytes written. <a href="#a001f3e654c646a90e46986c7e8c0ce13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a58872976b74619b15a253e4ed9acb8">is64Bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f4f12691ecc5fba20b4892742766d2a">nameShouldBeInStringTable</a> (const StringRef &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af58d6b6392d8458bfd5db1e0c438315b">writeSymbolName</a> (const StringRef &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c9141698ea7031fb1c04a12324ff54">auxFileSymNameShouldBeInStringTable</a> (const StringRef &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca0534e7a7c0584999965c31b2b8147">writeAuxFileSymName</a> (const StringRef &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27c44b313a2b79c658add6b348e067c5">writeSymbolEntryForCsectMemberLabel</a> (const Symbol &amp;SymbolRef, const XCOFFSection &amp;CSectionRef, int16_t SectionIndex, uint64_t SymbolOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33aeb821ee2afaace483407b00ef941a">writeSymbolEntryForControlSection</a> (const XCOFFSection &amp;CSectionRef, int16_t SectionIndex, XCOFF::StorageClass StorageClass)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58f5ec62a51feaa8d9ac98f43664b7a5">writeSymbolEntryForDwarfSection</a> (const XCOFFSection &amp;DwarfSectionRef, int16_t SectionIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a466977499963eb28c37652ce46152aa4">writeFileHeader</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7c95f7a9e0f1d5309c615004334624">writeAuxFileHeader</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070daa3acebcca98920c50c6ae5bfe99">writeSectionHeader</a> (const SectionEntry *Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d3eeebb564573363f701154508ea806">writeSectionHeaderTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e9b3e3c35aec05553b7d830622a692">writeSections</a> (const MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba741c073c4ec7089b6bc81d87dd9401">writeSectionForControlSectionEntry</a> (const MCAssembler &amp;Asm, const CsectSectionEntry &amp;CsectEntry, uint64_t &amp;CurrentAddressLocation)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac424958fbdcf4c6cf0112d241afca55d">writeSectionForDwarfSectionEntry</a> (const MCAssembler &amp;Asm, const DwarfSectionEntry &amp;DwarfEntry, uint64_t &amp;CurrentAddressLocation)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf8e5af6597b4cb85c76aebc1818463c">writeSectionForExceptionSectionEntry</a> (const MCAssembler &amp;Asm, ExceptionSectionEntry &amp;ExceptionEntry, uint64_t &amp;CurrentAddressLocation)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299f3cd9ed509e879d5897e1facf5834">writeSectionForCInfoSymSectionEntry</a> (const MCAssembler &amp;Asm, CInfoSymSectionEntry &amp;CInfoSymEntry, uint64_t &amp;CurrentAddressLocation)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac95f621f154c423f6fc8bdbd118cabdf">writeSymbolTable</a> (MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a1483d9cb88695a3b693ecd6393383a">writeSymbolAuxFileEntry</a> (StringRef &amp;Name, uint8_t ftype)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb20a1006dec207971d212ddc539c5f">writeSymbolAuxDwarfEntry</a> (uint64_t LengthOfSectionPortion, uint64_t NumberOfRelocEnt=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abffbde31061aa9601a1d422e46e62944">writeSymbolAuxCsectEntry</a> (uint64_t SectionOrLength, uint8_t SymbolAlignmentAndType, uint8_t StorageMappingClass)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1f6d57b7c613fc1b11b78dd55d520d">writeSymbolAuxFunctionEntry</a> (uint32_t EntryOffset, uint32_t FunctionSize, uint64_t LineNumberPointer, uint32_t EndIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f9db8178f5a256f352e4302f86be43">writeSymbolAuxExceptionEntry</a> (uint64_t EntryOffset, uint32_t FunctionSize, uint32_t EndIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab690701b864eb6dc89d7b5c0a2cab759">writeSymbolEntry</a> (StringRef SymbolName, uint64_t Value, int16_t SectionNumber, uint16_t SymbolType, uint8_t StorageClass, uint8_t NumberOfAuxEntries=1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e22b162a5722e07dfe21d8ab833cf93">writeRelocations</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e667360b8243f558acaf86768d5a8f">writeRelocation</a> (XCOFFRelocation Reloc, const XCOFFSection &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eaad321245c9349d886961bdb86198d">assignAddressesAndIndices</a> (MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb88664b7c762fa9567ed8f819a63603">finalizeSectionInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af788dc716877eb45107407545716eee8">finalizeRelocationInfo</a> (SectionEntry *Sec, uint64_t RelCount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f65ed0971a36ed614108336203d40d6">calcOffsetToRelocations</a> (SectionEntry *Sec, uint64_t &amp;RawPointer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3110b3d35b81314dd3504a1be16af4bf">hasExceptionSection</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bf85546578562be979b26fcff4ce2bf">getExceptionSectionSize</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b927c2982210eb45213394ab730f299">getExceptionOffset</a> (const MCSymbol *Symbol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37bdd46ca54a597b1d838dd578144e74">auxiliaryHeaderSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b431fe46b9714316d6252d638cdf33a">SymbolTableEntryCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29739a335b6337fef2c387ee76d2d7d0">SymbolTableOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9026b81e877127be4d158cbdafb1896c">SectionCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6657b1e80312fbeea7c07511ddd5bc">PaddingsBeforeDwarf</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b89c0fc0140ffbe9b30a735529c9a4">HasVisibility</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/support/endian/writer">support::endian::Writer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe7d10fcfeb8b456fc4d8c2fcb9b4d05">W</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcxcoffobjecttargetwriter">MCXCOFFObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2753d8ea9fab658a18e99eec05380ac6">TargetObjectWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af8fed1fe4bd6fcb3e2d3a12bd8e05c">Strings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2bbdb7543200e967bb4f0345ec6edf">MaxRawDataSize</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff">MCSectionXCOFF</a> *, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/xcoffsection">XCOFFSection</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e33632be15fbf8ce9c5f7f47a4ae86a">SectionMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d95ec9fb2867cc3dcb6188e97fb2e6c">SymbolIndexMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9700f3d8d089ff7cf848d042028e2d3a">UndefinedCsects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641b3fba59bcb818501b7f35131009ff">ProgramCodeCsects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a950201a9c8b4b232081e7b3fc6188f6c">ReadOnlyCsects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae1b5421067011746e5f778c9b45d0ab">DataCsects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1628c16478883a86a1ea6c8d3686e8ef">FuncDSCsects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63ac8cf521ca645f3bdc7131051e5c63">TOCCsects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d5f8b0c1f7ccfb7243463f8418b1c0c">BSSCsects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a113c6135d45861ca36075b271663389f">TDataCsects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a03be9452a49d9a719156f9e422e4a89f">CsectGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b4dbf09568e7fac642ac15b19435e4">TBSSCsects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry">CsectSectionEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a211da4e8d1fb5d46f91219c490d545c9">Text</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry">CsectSectionEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20c91247b452eee9074d3a5f3b7fe7d">Data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry">CsectSectionEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90429efa6b4f8f0867b264c74c784974">BSS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry">CsectSectionEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94b08803e207ff6f97ae8231121e475c">TData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry">CsectSectionEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a1b957e1fc2a480d6a65ecd8f5ffc1">TBSS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry">CsectSectionEntry</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, 5 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa5d354a1731828ca77c31a981d736b">Sections</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry">DwarfSectionEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a013af887ca6ea291be9a528589834b8c">DwarfSections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry">SectionEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7354969e1e6de92e27f7d988e299df85">OverflowSections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptionsectionentry">ExceptionSectionEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39f8aca430fdbbea8dd08c820475bf6">ExceptionSection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosymsectionentry">CInfoSymSectionEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a859db181f591bcbe500b9a451b4b54ef">CInfoSymSection</a></td>
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


<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### XCOFFWriter() {#a120cd2ed610d49b8b5549ca0868442c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::XCOFFWriter (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcxcoffobjecttargetwriter">MCXCOFFObjectTargetWriter</a> &gt; MOTW, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeacb24e90dcfcba01d1c251bcf8b399ef2">llvm::XCOFF::STYP_BSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1e3f056d2214669889fba21e3d949ca3">llvm::XCOFF::STYP_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeabda15739c5c07c0ac38280faaa4a2306">llvm::XCOFF::STYP_EXCEPT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1f498f3fbb898ea8e37f18e59cf23e39">llvm::XCOFF::STYP_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeadcf57b5531bdb50652a3604cf820b71d">llvm::XCOFF::STYP_TBSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea233a82ca0336e9be851e053af95ecb5d">llvm::XCOFF::STYP_TDATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea625db7b5bb9b798cf7c4eac884e7722b">llvm::XCOFF::STYP_TEXT</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCInfoSymEntry() {#a5652e69f3752a2629b5515fa76375b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::addCInfoSymEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Metadata)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### addExceptionEntry() {#a0ef1741206324d286d02bd789ce323c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::addExceptionEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Trap, unsigned LanguageCode, unsigned ReasonCode, unsigned FunctionSize, bool hasDebug)</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptioninfo/#a7845cc15059a4da56d49cad9d61e9cdc">anonymous{XCOFFObjectWriter.cpp}::ExceptionInfo::Entries</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptioninfo/#a623a16b5510375c2e1b17c97a9b71974">anonymous{XCOFFObjectWriter.cpp}::ExceptionInfo::FunctionSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptioninfo/#aa50f4f4f26d4f4d774326752c6adbc67">anonymous{XCOFFObjectWriter.cpp}::ExceptionInfo::FunctionSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba178e499decd0c21272bc34e4b3056eab">Trap</a>.</p>

</div>
</div>

### writeWord() {#aba20d7d48fbb17155fa17029e3475835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeWord (uint64_t Word)</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assignAddressesAndIndices() {#a4eaad321245c9349d886961bdb86198d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::assignAddressesAndIndices (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### auxFileSymNameShouldBeInStringTable() {#aa1c9141698ea7031fb1c04a12324ff54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::auxFileSymNameShouldBeInStringTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; SymbolName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### auxiliaryHeaderSize() {#a37bdd46ca54a597b1d838dd578144e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::auxiliaryHeaderSize ()</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### calcOffsetToRelocations() {#a6f65ed0971a36ed614108336203d40d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::calcOffsetToRelocations (<a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry">SectionEntry</a> * Sec, uint64_t &amp; RawPointer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### executePostLayoutBinding() {#af9982ecb527f13d39c465f2ee820b633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::executePostLayoutBinding (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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

<p>Perform any late binding of symbols (for example, to assign symbol indices for use when generating relocations).</p>


<p>This routine is called by the assembler after layout and relaxation is complete.</p>


<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### finalizeRelocationInfo() {#af788dc716877eb45107407545716eee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::finalizeRelocationInfo (<a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry">SectionEntry</a> * Sec, uint64_t RelCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### finalizeSectionInfo() {#aeb88664b7c762fa9567ed8f819a63603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::finalizeSectionInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### getCsectGroup() {#a5d54940f001df13dfb998f4fe5ae03b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup &amp; anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::getCsectGroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff">MCSectionXCOFF</a> * MCSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### getExceptionOffset() {#a5b927c2982210eb45213394ab730f299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::getExceptionOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### getExceptionSectionSize() {#a6bf85546578562be979b26fcff4ce2bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::getExceptionSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### hasExceptionSection() {#a3110b3d35b81314dd3504a1be16af4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::hasExceptionSection ()</td>
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



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### is64Bit() {#a0a58872976b74619b15a253e4ed9acb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::is64Bit ()</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### nameShouldBeInStringTable() {#a8f4f12691ecc5fba20b4892742766d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::nameShouldBeInStringTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; SymbolName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### recordRelocation() {#a63e780799b26c54712926c20e2c6d565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::recordRelocation (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * Fragment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> Target, uint64_t &amp; FixedValue)</td>
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

<p>Record a relocation entry.</p>


<p>This routine is called by the assembler after layout and relaxation, and post layout binding. The implementation is responsible for storing information about the relocation so that it can be emitted during writeObject().</p>


<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### reset() {#a4cad0ef5ee318537a1eb77063c051efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::reset ()</td>
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

<p>lifetime management</p>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeAuxFileHeader() {#a2b7c95f7a9e0f1d5309c615004334624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeAuxFileHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeAuxFileSymName() {#a2ca0534e7a7c0584999965c31b2b8147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeAuxFileSymName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; SymbolName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeFileHeader() {#a466977499963eb28c37652ce46152aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeFileHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeObject() {#a001f3e654c646a90e46986c7e8c0ce13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeObject (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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

<p>Write the object file and returns the number of bytes written.</p>


<p>This routine is called by the assembler after layout and relaxation is complete, fixups have been evaluated and applied, and relocations generated.</p>


<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeRelocation() {#ac0e667360b8243f558acaf86768d5a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeRelocation (<a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/xcoffrelocation">XCOFFRelocation</a> Reloc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/xcoffsection">XCOFFSection</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeRelocations() {#a8e22b162a5722e07dfe21d8ab833cf93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeRelocations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSectionForCInfoSymSectionEntry() {#a299f3cd9ed509e879d5897e1facf5834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSectionForCInfoSymSectionEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosymsectionentry">CInfoSymSectionEntry</a> &amp; CInfoSymEntry, uint64_t &amp; CurrentAddressLocation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSectionForControlSectionEntry() {#aba741c073c4ec7089b6bc81d87dd9401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSectionForControlSectionEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry">CsectSectionEntry</a> &amp; CsectEntry, uint64_t &amp; CurrentAddressLocation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSectionForDwarfSectionEntry() {#ac424958fbdcf4c6cf0112d241afca55d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSectionForDwarfSectionEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry">DwarfSectionEntry</a> &amp; DwarfEntry, uint64_t &amp; CurrentAddressLocation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSectionForExceptionSectionEntry() {#adf8e5af6597b4cb85c76aebc1818463c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSectionForExceptionSectionEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptionsectionentry">ExceptionSectionEntry</a> &amp; ExceptionEntry, uint64_t &amp; CurrentAddressLocation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSectionHeader() {#a070daa3acebcca98920c50c6ae5bfe99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSectionHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry">SectionEntry</a> * Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSectionHeaderTable() {#a4d3eeebb564573363f701154508ea806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSectionHeaderTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSections() {#a60e9b3e3c35aec05553b7d830622a692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSections (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolAuxCsectEntry() {#abffbde31061aa9601a1d422e46e62944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolAuxCsectEntry (uint64_t SectionOrLength, uint8_t SymbolAlignmentAndType, uint8_t StorageMappingClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolAuxDwarfEntry() {#acdb20a1006dec207971d212ddc539c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolAuxDwarfEntry (uint64_t LengthOfSectionPortion, uint64_t NumberOfRelocEnt=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolAuxExceptionEntry() {#a47f9db8178f5a256f352e4302f86be43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolAuxExceptionEntry (uint64_t EntryOffset, uint32_t FunctionSize, uint32_t EndIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolAuxFileEntry() {#a7a1483d9cb88695a3b693ecd6393383a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolAuxFileEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name, uint8_t ftype)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolAuxFunctionEntry() {#a7e1f6d57b7c613fc1b11b78dd55d520d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolAuxFunctionEntry (uint32_t EntryOffset, uint32_t FunctionSize, uint64_t LineNumberPointer, uint32_t EndIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolEntry() {#ab690701b864eb6dc89d7b5c0a2cab759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName, uint64_t Value, int16_t SectionNumber, uint16_t SymbolType, uint8_t StorageClass, uint8_t NumberOfAuxEntries=1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolEntryForControlSection() {#a33aeb821ee2afaace483407b00ef941a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolEntryForControlSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/xcoffsection">XCOFFSection</a> &amp; CSectionRef, int16_t SectionIndex, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70">XCOFF::StorageClass</a> StorageClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolEntryForCsectMemberLabel() {#a27c44b313a2b79c658add6b348e067c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolEntryForCsectMemberLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/symbol">Symbol</a> &amp; SymbolRef, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/xcoffsection">XCOFFSection</a> &amp; CSectionRef, int16_t SectionIndex, uint64_t SymbolOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolEntryForDwarfSection() {#a58f5ec62a51feaa8d9ac98f43664b7a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolEntryForDwarfSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/xcoffsection">XCOFFSection</a> &amp; DwarfSectionRef, int16_t SectionIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolName() {#af58d6b6392d8458bfd5db1e0c438315b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; SymbolName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolTable() {#ac95f621f154c423f6fc8bdbd118cabdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeSymbolTable (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BSS {#a90429efa6b4f8f0867b264c74c784974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectSectionEntry anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::BSS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### BSSCsects {#a5d5f8b0c1f7ccfb7243463f8418b1c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::BSSCsects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### CInfoSymSection {#a859db181f591bcbe500b9a451b4b54ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CInfoSymSectionEntry anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::CInfoSymSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### Data {#ae20c91247b452eee9074d3a5f3b7fe7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectSectionEntry anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### DataCsects {#aae1b5421067011746e5f778c9b45d0ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::DataCsects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### DwarfSections {#a013af887ca6ea291be9a528589834b8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DwarfSectionEntry&gt; anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::DwarfSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### ExceptionSection {#ac39f8aca430fdbbea8dd08c820475bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExceptionSectionEntry anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::ExceptionSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### FuncDSCsects {#a1628c16478883a86a1ea6c8d3686e8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::FuncDSCsects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### HasVisibility {#a51b89c0fc0140ffbe9b30a735529c9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::HasVisibility = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### MaxRawDataSize {#aad2bbdb7543200e967bb4f0345ec6edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::MaxRawDataSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      TargetObjectWriter-&gt;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>() ? <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a> : UINT32_MAX
</div>
</dd>
</dl>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### OverflowSections {#a7354969e1e6de92e27f7d988e299df85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SectionEntry&gt; anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::OverflowSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### PaddingsBeforeDwarf {#a8b6657b1e80312fbeea7c07511ddd5bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::PaddingsBeforeDwarf = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### ProgramCodeCsects {#a641b3fba59bcb818501b7f35131009ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::ProgramCodeCsects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### ReadOnlyCsects {#a950201a9c8b4b232081e7b3fc6188f6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::ReadOnlyCsects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### SectionCount {#a9026b81e877127be4d158cbdafb1896c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::SectionCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### SectionMap {#a6e33632be15fbf8ce9c5f7f47a4ae86a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSectionXCOFF *, XCOFFSection *&gt; anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::SectionMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### Sections {#abfa5d354a1731828ca77c31a981d736b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;CsectSectionEntry *const, 5&gt; anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      {&amp;Text, &amp;Data, &amp;BSS, &amp;TData, &amp;TBSS}}
</div>
</dd>
</dl>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### Strings {#a3af8fed1fe4bd6fcb3e2d3a12bd8e05c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::Strings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### SymbolIndexMap {#a6d95ec9fb2867cc3dcb6188e97fb2e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSymbol *, uint32_t&gt; anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::SymbolIndexMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### SymbolTableEntryCount {#a1b431fe46b9714316d6252d638cdf33a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::SymbolTableEntryCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### SymbolTableOffset {#a29739a335b6337fef2c387ee76d2d7d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::SymbolTableOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### TargetObjectWriter {#a2753d8ea9fab658a18e99eec05380ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCXCOFFObjectTargetWriter&gt; anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::TargetObjectWriter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### TBSS {#a20a1b957e1fc2a480d6a65ecd8f5ffc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectSectionEntry anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::TBSS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### TBSSCsects {#a13b4dbf09568e7fac642ac15b19435e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::TBSSCsects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### TData {#a94b08803e207ff6f97ae8231121e475c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectSectionEntry anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::TData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### TDataCsects {#a113c6135d45861ca36075b271663389f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::TDataCsects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### Text {#a211da4e8d1fb5d46f91219c490d545c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectSectionEntry anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::Text</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### TOCCsects {#a63ac8cf521ca645f3bdc7131051e5c63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::TOCCsects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### UndefinedCsects {#a9700f3d8d089ff7cf848d042028e2d3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CsectGroup anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::UndefinedCsects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### W {#abe7d10fcfeb8b456fc4d8c2fcb9b4d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::endian::Writer anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::W</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
