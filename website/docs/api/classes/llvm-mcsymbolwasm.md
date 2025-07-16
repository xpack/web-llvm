---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsymbolwasm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCSymbolWasm` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCSymbolWasm { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">llvm/MC/MCSymbolWasm.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> - Instances of this class represent a symbol name in the MC file, and MCSymbols are created and uniqued by the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> class. <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b1a4d377afcb0e8b74c7b1da059ed45">MCSymbolWasm</a> (const MCSymbolTableEntry *Name, bool isTemporary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4be99a3a42bbf0d95ef6ae77e3739696">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af330152133430b4db138c108eeda9afa">setSize</a> (const MCExpr *SS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af29669e65379f28f1a8a33c9669d10c9">isFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae44253a72e870a7e69f9b7ce14a20ae6">isData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021e36df6773457087c3395d22ad76f2">isGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ab563f7a291d954ed63612309b8161">isTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b7daf6c01b225f2a0b4e232c8b7a50">isSection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56e445b93e9f0caadc3de0b4b77aab7">isTag</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529">wasm::WasmSymbolType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3dcaf743b04a6ee2c241b2259959b4a">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817a67945b1632513e9b43ca0da9aacd">setType</a> (wasm::WasmSymbolType type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b84295e51434ac5b2b268a2fa7c130c">isExported</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab601ca3b61286b47c425b061856e876f">setExported</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a903f25fc3d903840c154d513b80942da">isNoStrip</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c1c155ac78b299701444d7a31046e5">setNoStrip</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0aaed75ab9d50975313452d033616e5">isTLS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d60a95bc4f401939956b7328ee70d9">setTLS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa960aaf1389b277d2b4698848e5a0d">isWeak</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5b64abdda5a509f48743e420f4acb5">setWeak</a> (bool isWeak)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ebc3c728aa91b31e6d827d02e55fdc6">isHidden</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d89991eadd01d39609d0b9a569bee71">setHidden</a> (bool isHidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdc1ecc9ad5f0c1a3259bd47e8ff95f9">isComdat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b2eeed02c99b34cc1252ad86bb34b69">setComdat</a> (bool isComdat)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab08ba322a351661960566b5625495569">omitFromLinkingSection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b68f461b38d0ad3f9ff58f93e248de1">setOmitFromLinkingSection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d3dc9fc9281d6a21ea16e11edbcf30d">hasImportModule</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6529ceff66d509880f4e30e50fe2f9">getImportModule</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c65364364450057e78a85f0ab10838">setImportModule</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af056be7de240107505a77a16ec790ac0">hasImportName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36fdd6258a57e9924a00446921669046">getImportName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca6349278b2b3a0ba49fdff66c61bba">setImportName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf5765465e6dd1fc6877d8e5782ac624">hasExportName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac63af1ba89b469d68d373e6bb8ee43e2">getExportName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa9eb84018c0d87097bb8d30b9623ed">setExportName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a2f276f396875ef912e9b13ba292663">isFunctionTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d32c6868ad27b8c94d4d0e7134af2a">setFunctionTable</a> (bool is64)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56ab9b089a323046170c255a54ed9c5">setUsedInGOT</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2426e377a83ffde5eac50cbdb45a67ca">isUsedInGOT</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc80c8bee21a7624569d9f3f8275165">setUsedInInitArray</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf11978111e10d3d704afde069ce518">isUsedInInitArray</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31dc0afa892465aaef33221d049d16f1">getSignature</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f3dcb387e1f3450b1833e03a133f7e">setSignature</a> (wasm::WasmSignature *Sig)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmglobaltype">wasm::WasmGlobalType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec92aa6c545424605c7be276e633608">getGlobalType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b778bb98433efd9a6630bb45b4bd64f">setGlobalType</a> (wasm::WasmGlobalType GT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b4268f73b473ca305a50118d3684c45">hasTableType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtabletype">wasm::WasmTableType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d51e7d9f9147057c66d10f913a82a4">getTableType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a044b57ea7f09bf315fe429350de59d25">setTableType</a> (wasm::WasmTableType TT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bc6315a3c5c2b726c8831fdaff12054">setTableType</a> (wasm::ValType VT, uint8_t flags=wasm::WASM_LIMITS_FLAG_NONE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529">wasm::WasmSymbolType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6a79ccc2616f73cda563134b1b04ab">Type</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace330776df449048e2a4ae210d28f50b">IsWeak</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed33b970b7e0c4a4d2f50fad5258bd47">IsHidden</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0cae83a292a1fb7b1184108470eacb">IsComdat</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e158a5c27b78c9fb34a5031936c45f">OmitFromLinkingSection</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98533ca0b360847da91430a84ca369b4">IsUsedInInitArray</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461072e11ffab67dcc5dbb27d4214c49">IsUsedInGOT</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e0040f6cee396ce5b70543bb563cc1">ImportModule</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0282eaf4cc3d946120354c379b69e6d6">ImportName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd6836251a804c989546755a0979b46d">ExportName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80201e3fae96d9144c0b978e2c04e464">Signature</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmglobaltype">wasm::WasmGlobalType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a24c6af2f8fc2be957b975d5ba5096c">GlobalType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtabletype">wasm::WasmTableType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0324d33a610f6f6edebf2250cb1b526c">TableType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bdd5d33f788a7ca17d557bcb904a8e">SymbolSize</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An expression describing how to calculate the size of a symbol. <a href="#ad1bdd5d33f788a7ca17d557bcb904a8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b060951fe2c68b6071614499e1d8ab">classof</a> (const MCSymbol *S)</td>
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


<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCSymbolWasm() {#a3b1a4d377afcb0e8b74c7b1da059ed45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSymbolWasm::MCSymbolWasm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> * Name, bool isTemporary)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab8dab642726ffad2a75d9fb7e4ec4291aba489d15d843572410f5bbf9dcba0934">llvm::MCSymbol::SymbolKindWasm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getExportName() {#ac63af1ba89b469d68d373e6bb8ee43e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSymbolWasm::getExportName ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### getGlobalType() {#abec92aa6c545424605c7be276e633608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmGlobalType &amp; llvm::MCSymbolWasm::getGlobalType ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#aa2841293de9505ceb9ef958d38fa1526">llvm::WebAssemblyTargetAsmStreamer::emitGlobalType</a>.</p>

</div>
</div>

### getImportModule() {#a2b6529ceff66d509880f4e30e50fe2f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSymbolWasm::getImportModule ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### getImportName() {#a36fdd6258a57e9924a00446921669046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSymbolWasm::getImportName ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>.</p>

</div>
</div>

### getSignature() {#a31dc0afa892465aaef33221d049d16f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmSignature * llvm::MCSymbolWasm::getSignature ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#a3d00e1ac3848f4af6f98182dca6f5045">llvm::WebAssemblyTargetAsmStreamer::emitFunctionType</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#ad431095019a0f5c940ea308e3bcfadbf">llvm::WebAssemblyTargetAsmStreamer::emitTagType</a>.</p>

</div>
</div>

### getSize() {#a4be99a3a42bbf0d95ef6ae77e3739696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::MCSymbolWasm::getSize ()</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4003ba7a2726fde2214660963213cc31">llvm::MCSymbol::MCExpr</a>.</p>

</div>
</div>

### getTableType() {#a20d51e7d9f9147057c66d10f913a82a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmTableType &amp; llvm::MCSymbolWasm::getTableType ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5b4268f73b473ca305a50118d3684c45">hasTableType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#ab1be13e43fafccdcb3c7fb6ff5b316e5">llvm::WebAssemblyTargetAsmStreamer::emitTableType</a> and <a href="#a5a2f276f396875ef912e9b13ba292663">isFunctionTable</a>.</p>

</div>
</div>

### getType() {#af3dcaf743b04a6ee2c241b2259959b4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; wasm::WasmSymbolType &gt; llvm::MCSymbolWasm::getType ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a4d155a589e83947673539f155aa88172">llvm::WebAssemblyAsmPrinter::emitSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aec55174841f8aa80f2d1c3f56c4165af">llvm::MCContext::getWasmSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a711350a8af2fb95f4f1ca8cb7fa79374">llvm::WebAssembly::wasmSymbolSetType</a>.</p>

</div>
</div>

### hasExportName() {#aaf5765465e6dd1fc6877d8e5782ac624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::hasExportName ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### hasImportModule() {#a4d3dc9fc9281d6a21ea16e11edbcf30d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::hasImportModule ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### hasImportName() {#af056be7de240107505a77a16ec790ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::hasImportName ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### hasTableType() {#a5b4268f73b473ca305a50118d3684c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::hasTableType ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="#a20d51e7d9f9147057c66d10f913a82a4">getTableType</a> and <a href="#a5a2f276f396875ef912e9b13ba292663">isFunctionTable</a>.</p>

</div>
</div>

### isComdat() {#acdc1ecc9ad5f0c1a3259bd47e8ff95f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isComdat ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#acfd6b837b0a2c4f3fbf36102a70cc5b9">isInSymtab</a> and <a href="#a1b2eeed02c99b34cc1252ad86bb34b69">setComdat</a>.</p>

</div>
</div>

### isData() {#ae44253a72e870a7e69f9b7ce14a20ae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isData ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a3bf8c7186acf1ffbf50c1f7c915554bb">llvm::wasm::WASM_SYMBOL_TYPE_DATA</a>.</p>

</div>
</div>

### isExported() {#a2b84295e51434ac5b2b268a2fa7c130c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isExported ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8030ced805cc560d06af7948a8f6bb6f">llvm::wasm::WASM_SYMBOL_EXPORTED</a>.</p>

</div>
</div>

### isFunction() {#af29669e65379f28f1a8a33c9669d10c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isFunction ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ae2d3246e8f9451c96b200707078c83d9">llvm::wasm::WASM_SYMBOL_TYPE_FUNCTION</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#a3d00e1ac3848f4af6f98182dca6f5045">llvm::WebAssemblyTargetAsmStreamer::emitFunctionType</a>.</p>

</div>
</div>

### isFunctionTable() {#a5a2f276f396875ef912e9b13ba292663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isFunctionTable ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtabletype/#a9e6205df9696b4d237496b86b95389b7">llvm::wasm::WasmTableType::ElemType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a56830bd472296f98c7672a39085926ae">llvm::wasm::FUNCREF</a>, <a href="#a20d51e7d9f9147057c66d10f913a82a4">getTableType</a>, <a href="#a5b4268f73b473ca305a50118d3684c45">hasTableType</a> and <a href="#ab9ab563f7a291d954ed63612309b8161">isTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a7258bffac41959b91226f473086e93a2">llvm::WebAssembly::getOrCreateFuncrefCallTableSymbol</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyasmparser-cpp-/#a97776aecc75fa260afa954c88a1bfed6">anonymous{WebAssemblyAsmParser.cpp}::getOrCreateFunctionTableSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a33df8ca13cb8bb9e37d1f43b202aef7f">llvm::WebAssembly::getOrCreateFunctionTableSymbol</a>.</p>

</div>
</div>

### isGlobal() {#a021e36df6773457087c3395d22ad76f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isGlobal ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a36f3d68b8025222c9f73a586aee5932f">llvm::wasm::WASM_SYMBOL_TYPE_GLOBAL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#aa2841293de9505ceb9ef958d38fa1526">llvm::WebAssemblyTargetAsmStreamer::emitGlobalType</a>.</p>

</div>
</div>

### isHidden() {#a9ebc3c728aa91b31e6d827d02e55fdc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isHidden ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="#a8d89991eadd01d39609d0b9a569bee71">setHidden</a>.</p>

</div>
</div>

### isNoStrip() {#a903f25fc3d903840c154d513b80942da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isNoStrip ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ebe6b8e2293d161eef6e6ccfb89397c">llvm::wasm::WASM_SYMBOL_NO_STRIP</a>.</p>

</div>
</div>

### isSection() {#aa0b7daf6c01b225f2a0b4e232c8b7a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isSection ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ad7d988e101231ece62ebfe7d06884a1f">llvm::wasm::WASM_SYMBOL_TYPE_SECTION</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#acfd6b837b0a2c4f3fbf36102a70cc5b9">isInSymtab</a>.</p>

</div>
</div>

### isTable() {#ab9ab563f7a291d954ed63612309b8161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isTable ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a7e6d4cfa5233363b413a1b9997c98d7c">llvm::wasm::WASM_SYMBOL_TYPE_TABLE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#ab1be13e43fafccdcb3c7fb6ff5b316e5">llvm::WebAssemblyTargetAsmStreamer::emitTableType</a> and <a href="#a5a2f276f396875ef912e9b13ba292663">isFunctionTable</a>.</p>

</div>
</div>

### isTag() {#ae56e445b93e9f0caadc3de0b4b77aab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isTag ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a47169d0c34c301e7580280da4dc576a6">llvm::wasm::WASM_SYMBOL_TYPE_TAG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#ad431095019a0f5c940ea308e3bcfadbf">llvm::WebAssemblyTargetAsmStreamer::emitTagType</a>.</p>

</div>
</div>

### isTLS() {#af0aaed75ab9d50975313452d033616e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isTLS ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a712cacf1731d527651876ac16e90cad0">llvm::MCSymbol::getFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a406d59a61d7b0d3345136e6a0f442b6e">llvm::wasm::WASM_SYMBOL_TLS</a>.</p>

</div>
</div>

### isUsedInGOT() {#a2426e377a83ffde5eac50cbdb45a67ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isUsedInGOT ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### isUsedInInitArray() {#aebf11978111e10d3d704afde069ce518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isUsedInInitArray ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#acfd6b837b0a2c4f3fbf36102a70cc5b9">isInSymtab</a>.</p>

</div>
</div>

### isWeak() {#afaa960aaf1389b277d2b4698848e5a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::isWeak ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="#a7e5b64abdda5a509f48743e420f4acb5">setWeak</a>.</p>

</div>
</div>

### omitFromLinkingSection() {#ab08ba322a351661960566b5625495569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::omitFromLinkingSection ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#acfd6b837b0a2c4f3fbf36102a70cc5b9">isInSymtab</a>.</p>

</div>
</div>

### setComdat() {#a1b2eeed02c99b34cc1252ad86bb34b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setComdat (bool isComdat)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="#acdc1ecc9ad5f0c1a3259bd47e8ff95f9">isComdat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aec55174841f8aa80f2d1c3f56c4165af">llvm::MCContext::getWasmSection</a>.</p>

</div>
</div>

### setExported() {#ab601ca3b61286b47c425b061856e876f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setExported ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8030ced805cc560d06af7948a8f6bb6f">llvm::wasm::WASM_SYMBOL_EXPORTED</a>.</p>

</div>
</div>

### setExportName() {#a8aa9eb84018c0d87097bb8d30b9623ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setExportName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### setFunctionTable() {#a54d32c6868ad27b8c94d4d0e7134af2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setFunctionTable (bool is64)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a56830bd472296f98c7672a39085926ae">llvm::wasm::FUNCREF</a>, <a href="#a044b57ea7f09bf315fe429350de59d25">setTableType</a>, <a href="#a817a67945b1632513e9b43ca0da9aacd">setType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a59b99a8ddca474dff358ee96d7a5b9ada5c31f95862dbfe9c083dbf74bb602292">llvm::wasm::WASM_LIMITS_FLAG_IS_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a59b99a8ddca474dff358ee96d7a5b9ada6b795ffd15b7b08b9a936f6fd6d0c6a7">llvm::wasm::WASM_LIMITS_FLAG_NONE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a7e6d4cfa5233363b413a1b9997c98d7c">llvm::wasm::WASM_SYMBOL_TYPE_TABLE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyasmparser-cpp-/#a97776aecc75fa260afa954c88a1bfed6">anonymous{WebAssemblyAsmParser.cpp}::getOrCreateFunctionTableSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a33df8ca13cb8bb9e37d1f43b202aef7f">llvm::WebAssembly::getOrCreateFunctionTableSymbol</a>.</p>

</div>
</div>

### setGlobalType() {#a8b778bb98433efd9a6630bb45b4bd64f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setGlobalType (<a href="/web-llvm/docs/api/structs/llvm/wasm/wasmglobaltype">wasm::WasmGlobalType</a> GT)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a711350a8af2fb95f4f1ca8cb7fa79374">llvm::WebAssembly::wasmSymbolSetType</a>.</p>

</div>
</div>

### setHidden() {#a8d89991eadd01d39609d0b9a569bee71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setHidden (bool isHidden)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="#a9ebc3c728aa91b31e6d827d02e55fdc6">isHidden</a>.</p>

</div>
</div>

### setImportModule() {#a22c65364364450057e78a85f0ab10838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setImportModule (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### setImportName() {#a6ca6349278b2b3a0ba49fdff66c61bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setImportName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### setNoStrip() {#a67c1c155ac78b299701444d7a31046e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setNoStrip ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ebe6b8e2293d161eef6e6ccfb89397c">llvm::wasm::WASM_SYMBOL_NO_STRIP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>.</p>

</div>
</div>

### setOmitFromLinkingSection() {#a9b68f461b38d0ad3f9ff58f93e248de1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setOmitFromLinkingSection ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a7258bffac41959b91226f473086e93a2">llvm::WebAssembly::getOrCreateFuncrefCallTableSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a33df8ca13cb8bb9e37d1f43b202aef7f">llvm::WebAssembly::getOrCreateFunctionTableSymbol</a>.</p>

</div>
</div>

### setSignature() {#a51f3dcb387e1f3450b1833e03a133f7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setSignature (<a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> * Sig)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### setSize() {#af330152133430b4db138c108eeda9afa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * SS)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4003ba7a2726fde2214660963213cc31">llvm::MCSymbol::MCExpr</a>.</p>

</div>
</div>

### setTableType() {#a044b57ea7f09bf315fe429350de59d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setTableType (<a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtabletype">wasm::WasmTableType</a> TT)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a7258bffac41959b91226f473086e93a2">llvm::WebAssembly::getOrCreateFuncrefCallTableSymbol</a>, <a href="#a54d32c6868ad27b8c94d4d0e7134af2a">setFunctionTable</a>, <a href="#a5bc6315a3c5c2b726c8831fdaff12054">setTableType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a711350a8af2fb95f4f1ca8cb7fa79374">llvm::WebAssembly::wasmSymbolSetType</a>.</p>

</div>
</div>

### setTableType() {#a5bc6315a3c5c2b726c8831fdaff12054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setTableType (<a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a> VT, uint8_t flags=<a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a59b99a8ddca474dff358ee96d7a5b9ada6b795ffd15b7b08b9a936f6fd6d0c6a7">wasm::WASM_LIMITS_FLAG_NONE</a>)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="#a044b57ea7f09bf315fe429350de59d25">setTableType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a59b99a8ddca474dff358ee96d7a5b9ada6b795ffd15b7b08b9a936f6fd6d0c6a7">llvm::wasm::WASM_LIMITS_FLAG_NONE</a>.</p>

</div>
</div>

### setTLS() {#af9d60a95bc4f401939956b7328ee70d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setTLS ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4f740178324a11d838ee335b2986d6eb">llvm::MCSymbol::modifyFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a406d59a61d7b0d3345136e6a0f442b6e">llvm::wasm::WASM_SYMBOL_TLS</a>.</p>

</div>
</div>

### setType() {#a817a67945b1632513e9b43ca0da9aacd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setType (<a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529">wasm::WasmSymbolType</a> type)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a7258bffac41959b91226f473086e93a2">llvm::WebAssembly::getOrCreateFuncrefCallTableSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aec55174841f8aa80f2d1c3f56c4165af">llvm::MCContext::getWasmSection</a>, <a href="#a54d32c6868ad27b8c94d4d0e7134af2a">setFunctionTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a711350a8af2fb95f4f1ca8cb7fa79374">llvm::WebAssembly::wasmSymbolSetType</a>.</p>

</div>
</div>

### setUsedInGOT() {#ae56ab9b089a323046170c255a54ed9c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setUsedInGOT ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### setUsedInInitArray() {#a9dc80c8bee21a7624569d9f3f8275165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setUsedInInitArray ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### setWeak() {#a7e5b64abdda5a509f48743e420f4acb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSymbolWasm::setWeak (bool isWeak)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>Reference <a href="#afaa960aaf1389b277d2b4698848e5a0d">isWeak</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a7258bffac41959b91226f473086e93a2">llvm::WebAssembly::getOrCreateFuncrefCallTableSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ExportName {#acd6836251a804c989546755a0979b46d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringRef&gt; llvm::MCSymbolWasm::ExportName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### GlobalType {#a0a24c6af2f8fc2be957b975d5ba5096c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;wasm::WasmGlobalType&gt; llvm::MCSymbolWasm::GlobalType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### ImportModule {#a68e0040f6cee396ce5b70543bb563cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringRef&gt; llvm::MCSymbolWasm::ImportModule</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### ImportName {#a0282eaf4cc3d946120354c379b69e6d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringRef&gt; llvm::MCSymbolWasm::ImportName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### IsComdat {#a0b0cae83a292a1fb7b1184108470eacb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::IsComdat = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### IsHidden {#aed33b970b7e0c4a4d2f50fad5258bd47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::IsHidden = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### IsUsedInGOT {#a461072e11ffab67dcc5dbb27d4214c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::IsUsedInGOT = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### IsUsedInInitArray {#a98533ca0b360847da91430a84ca369b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::IsUsedInInitArray = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### IsWeak {#ace330776df449048e2a4ae210d28f50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::IsWeak = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### OmitFromLinkingSection {#ac3e158a5c27b78c9fb34a5031936c45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::OmitFromLinkingSection = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### Signature {#a80201e3fae96d9144c0b978e2c04e464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmSignature* llvm::MCSymbolWasm::Signature = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### SymbolSize {#ad1bdd5d33f788a7ca17d557bcb904a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::MCSymbolWasm::SymbolSize = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An expression describing how to calculate the size of a symbol.</p>


<p>If a symbol has no size this field will be NULL.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### TableType {#a0324d33a610f6f6edebf2250cb1b526c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;wasm::WasmTableType&gt; llvm::MCSymbolWasm::TableType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

### Type {#acb6a79ccc2616f73cda563134b1b04ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;wasm::WasmSymbolType&gt; llvm::MCSymbolWasm::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a18b060951fe2c68b6071614499e1d8ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolWasm::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * S)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a063e60f6284c95d6447e7afbfb4e8ace">llvm::MCSymbol::isWasm</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a66a74a9d90f80bcf982d70ab2446862e">llvm::MCSymbol::MCSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolwasm-h">MCSymbolWasm.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
