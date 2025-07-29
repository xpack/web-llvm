---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DarwinAsmParser` Class

<p>Implementation of directive handling which is shared across all Darwin targets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{DarwinAsmParser.cpp}::DarwinAsmParser { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension">MCAsmParserExtension</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic interface for extending the <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a>, which is implemented by target and object file assembly parser implementations. <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a3d0d9893e790f145f4b0cf354bfaa">DarwinAsmParser</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60417cf07ab7af9a9d65ad7477c39214">Initialize</a> (MCAsmParser &amp;Parser) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the extension for parsing using the given <span class="doxyComputerOutput">Parser</span>. <a href="#a60417cf07ab7af9a9d65ad7477c39214">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a463a346d7da05840b0c7f4b92dd3caf6">parseDirectiveAltEntry</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveAltEntry ::= .alt_entry identifier <a href="#a463a346d7da05840b0c7f4b92dd3caf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3b0cb9ef7b3869b91009f946b1d560">parseDirectiveDesc</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveDesc ::= .desc identifier , expression <a href="#a7f3b0cb9ef7b3869b91009f946b1d560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb14af816964063e2e902f6d9586abcd">parseDirectiveIndirectSymbol</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIndirectSymbol ::= .indirect_symbol identifier <a href="#adb14af816964063e2e902f6d9586abcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6c0e51b6f9cf34090c9a86852d932a">parseDirectiveDumpOrLoad</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveDumpOrLoad ::= ( .dump | .load ) "filename" <a href="#aea6c0e51b6f9cf34090c9a86852d932a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022d1cc063e7491e1378663102c8a4b5">parseDirectiveLsym</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveLsym ::= .lsym identifier , expression <a href="#a022d1cc063e7491e1378663102c8a4b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac817c5437e692128f921c71df5da2fba">parseDirectiveLinkerOption</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveLinkerOption ::= .linker_option "string" ( , "string" )*. <a href="#ac817c5437e692128f921c71df5da2fba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757668838f5767cbf28d9a5b1201a646">parseDirectiveSection</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveSection: ::= .section identifier (',' identifier)* <a href="#a757668838f5767cbf28d9a5b1201a646">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67167ef6f5bc9b24749cc75966450eb0">parseDirectivePushSection</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectivePushSection: ::= .pushsection identifier (',' identifier)*. <a href="#a67167ef6f5bc9b24749cc75966450eb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adccb36665f54db568d0fda77df5a2c3f">parseDirectivePopSection</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectivePopSection: ::= .popsection. <a href="#adccb36665f54db568d0fda77df5a2c3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34717c40eba0454dd55a5f74d5dbb2e">parseDirectivePrevious</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectivePrevious: ::= .previous. <a href="#aa34717c40eba0454dd55a5f74d5dbb2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35c606c799d33998f19368dbd9fb5c3a">parseDirectiveSecureLogReset</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveSecureLogReset ::= .secure_log_reset. <a href="#a35c606c799d33998f19368dbd9fb5c3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3237e027b109101104739097a3e415da">parseDirectiveSecureLogUnique</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveSecureLogUnique ::= .secure_log_unique ... message ... <a href="#a3237e027b109101104739097a3e415da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48439c82acdd2f356bfbf9e120e3bb9">parseDirectiveSubsectionsViaSymbols</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveSubsectionsViaSymbols ::= .subsections_via_symbols <a href="#aa48439c82acdd2f356bfbf9e120e3bb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865b1c6f63f4309779f26c93bd7030bf">parseDirectiveTBSS</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveTBSS ::= .tbss identifier, size, align. <a href="#a865b1c6f63f4309779f26c93bd7030bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684c8f59f91c7a9a03ed144fef80ba6a">parseDirectiveZerofill</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveZerofill ::= .zerofill segname , sectname [, identifier , size_expression [ , align_expression ]]. <a href="#a684c8f59f91c7a9a03ed144fef80ba6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae246971cdc93908b9f10e7e7a829314c">parseDirectiveDataRegion</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveDataRegion ::= .data_region [ ( jt8 | jt16 | jt32 ) ]. <a href="#ae246971cdc93908b9f10e7e7a829314c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0111046854925fdf5c7a297f6751c2">parseDirectiveDataRegionEnd</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveDataRegionEnd ::= .end_data_region. <a href="#a6f0111046854925fdf5c7a297f6751c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae16160a652212b911866e872c2f87e4c">parseSectionDirectiveBss</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00cf798d4d43fdb77066c73d437ed65b">parseSectionDirectiveConst</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae05d3b52e52765e7ab7a3271bed3d475">parseSectionDirectiveStaticConst</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af53f317a5cfa75be1d48ad2ab9277104">parseSectionDirectiveCString</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772d7f38e4800882c7028d01ca29186a">parseSectionDirectiveLiteral4</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ea32416058437c8c635d20dacd27742">parseSectionDirectiveLiteral8</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd1ad69567e4ab4a7ad8256b5f85d255">parseSectionDirectiveLiteral16</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc9bbd0fd1133d18eced5801c718fddf">parseSectionDirectiveConstructor</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a574101e489a48e854781fcf266b29f31">parseSectionDirectiveDestructor</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad095aa38fe7e564a2ccacd3a3cb1dda9">parseSectionDirectiveFVMLibInit0</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1feeaffc04438e78d2e2be3a65245b6b">parseSectionDirectiveFVMLibInit1</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93fd2572a8e2654644b7ec8fdf2a1b55">parseSectionDirectiveSymbolStub</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a456a08446ef9b2f8d615a2ac65b0bc60">parseSectionDirectivePICSymbolStub</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e27d03cf1944ecaad8d3b1c9d1a5f2">parseSectionDirectiveData</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac63c84558e6b85ad8019834b52c358">parseSectionDirectiveStaticData</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15fce59624f758ed2432c9de1352ce7e">parseSectionDirectiveNonLazySymbolPointers</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ec93cf1c2f4fe004cbb77fa439e90b">parseSectionDirectiveLazySymbolPointers</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ce8995ef5213ea9854eff832ab3de0">parseSectionDirectiveThreadLocalVariablePointers</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820e7907d305bd5620af2a7718ab4ed6">parseSectionDirectiveDyld</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb451a4f4ad1a35df4ba27060f01ad7">parseSectionDirectiveModInitFunc</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401e65426d2f71742382c120b3c0cc55">parseSectionDirectiveModTermFunc</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c400f64256609d0d2ac2f1a51108be9">parseSectionDirectiveConstData</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac8af0e9c5c082ff419a20cdc42516b">parseSectionDirectiveObjCClass</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1424b4ba2bccbc7096fd14419746dc8d">parseSectionDirectiveObjCMetaClass</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed715e74d6b109f7c253fe3543e1f07e">parseSectionDirectiveObjCCatClsMeth</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e33dc3da93e7f1d805a0ed82f78a1ae">parseSectionDirectiveObjCCatInstMeth</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7dc05406fc68fa9e0a96c0d033b0c7">parseSectionDirectiveObjCProtocol</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90acdc4fe681273a7ee1be1aa334c872">parseSectionDirectiveObjCStringObject</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d591c077b4c616c93d77c1bf57e49f">parseSectionDirectiveObjCClsMeth</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0cf233d7dded51f051d2b9b7bea2e57">parseSectionDirectiveObjCInstMeth</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48bce75e438068cf105294149f68eb03">parseSectionDirectiveObjCClsRefs</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc47d1c5fad97ba5387c7925e029c2f8">parseSectionDirectiveObjCMessageRefs</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a419999eaa924169be7f24e8b2e79c5">parseSectionDirectiveObjCSymbols</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ee677b588304f17b5fbb282c7401d1">parseSectionDirectiveObjCCategory</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99fff813150a25b4e44d53d393d44f7">parseSectionDirectiveObjCClassVars</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4d34a196a5c54ebe98ea445b212ee4">parseSectionDirectiveObjCInstanceVars</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2837f85a93a5c4576eb6abee271c2057">parseSectionDirectiveObjCModuleInfo</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b6d17d5f6f1859a2621ab7197edf27">parseSectionDirectiveObjCClassNames</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c1fd940790f3a2bcd71a8823dc04ba">parseSectionDirectiveObjCMethVarTypes</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba18a8d6c9e8868212e298c4e1955b6">parseSectionDirectiveObjCMethVarNames</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe85c872285d4051252674641f19a178">parseSectionDirectiveObjCSelectorStrs</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80d1ffc772157a8086b9487ff7ad3af">parseSectionDirectiveTData</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070b2f2ad69f69969a7e29784e89ce1f">parseSectionDirectiveText</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac397f90fb6124675e37a3b5ad6c25ea3">parseSectionDirectiveTLV</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7692f02f029f7b374e86d144e2055d3c">parseSectionDirectiveIdent</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb3ea963f9194c1821e16911f8040c8">parseSectionDirectiveThreadInitFunc</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf15ff7e79d0b2b8282032b72a11323d">parseWatchOSVersionMin</a> (StringRef Directive, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc371dc374b982a002dbf368f986390">parseTvOSVersionMin</a> (StringRef Directive, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ed98b8d1e01ce06f29e69e9f5945e5">parseIOSVersionMin</a> (StringRef Directive, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1535d26083b8e2c2907f3df355ff1619">parseMacOSXVersionMin</a> (StringRef Directive, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a972ee6fe54b3bdbfbcf505162a75ea">parseBuildVersion</a> (StringRef Directive, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseBuildVersion ::= .build_version (macos|ios|tvos|watchos), parseVersion parseSDKVersion <a href="#a1a972ee6fe54b3bdbfbcf505162a75ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb30c8e8f9bd310eefdf38def39c408a">parseVersionMin</a> (StringRef Directive, SMLoc Loc, MCVersionMinType Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseVersionMin ::= .ios_version_min parseVersion parseSDKVersion | .macosx_version_min parseVersion parseSDKVersion | .tvos_version_min parseVersion parseSDKVersion | .watchos_version_min parseVersion parseSDKVersion <a href="#afb30c8e8f9bd310eefdf38def39c408a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada48b8f406d37c059696406dd6177d32">parseMajorMinorVersionComponent</a> (unsigned *Major, unsigned *Minor, const char *VersionName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseMajorMinorVersionComponent ::= major, minor <a href="#ada48b8f406d37c059696406dd6177d32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2097c2b524a1f2b8a81abdf82679654">parseOptionalTrailingVersionComponent</a> (unsigned *Component, const char *ComponentName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalTrailingVersionComponent ::= , version_number <a href="#ac2097c2b524a1f2b8a81abdf82679654">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a4d51524eaad36622be26b13c78256">parseVersion</a> (unsigned *Major, unsigned *Minor, unsigned *Update)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseVersion ::= parseMajorMinorVersionComponent parseOptionalTrailingVersionComponent <a href="#a11a4d51524eaad36622be26b13c78256">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e5f912459671a68d8fb7dcb06fb322d">parseSDKVersion</a> (VersionTuple &amp;SDKVersion)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a06fbb4615244e2f5e81529fd08a9d0">checkVersion</a> (StringRef Directive, StringRef Arg, SMLoc Loc, Triple::OSType ExpectedOS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d48081548f77ae318b303f7c7ae26b8">parseDirectiveCGProfile</a> (StringRef Directive, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCGProfile ::= .cg_profile from, to, count <a href="#a5d48081548f77ae318b303f7c7ae26b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool(DarwinAsmParser::*)(StringRef, SMLoc) HandlerMethod&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d3dce353e7eac73501c00ca0f5443ed">addDirectiveHandler</a> (StringRef Directive)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc76257731956ed13cb46b6dbef5ed31">parseSectionSwitch</a> (StringRef Segment, StringRef Section, unsigned TAA=0, unsigned ImplicitAlign=0, unsigned StubSize=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94b3d5458cf6b8ea0e4a3353416e4f46">LastVersionDirective</a></td>
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

<p>Implementation of directive handling which is shared across all Darwin targets.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DarwinAsmParser() {#ac7a3d0d9893e790f145f4b0cf354bfaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::DarwinAsmParser ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkVersion() {#a0a06fbb4615244e2f5e81529fd08a9d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DarwinAsmParser::checkVersion (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cd">Triple::OSType</a> ExpectedOS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a3b0649c72650c313a357338dcdfb64ec">llvm::Note</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>


<p>Referenced by <a href="#a1a972ee6fe54b3bdbfbcf505162a75ea">parseBuildVersion</a> and <a href="#afb30c8e8f9bd310eefdf38def39c408a">parseVersionMin</a>.</p>

</div>
</div>

### Initialize() {#a60417cf07ab7af9a9d65ad7477c39214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::Initialize (<a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; Parser)</td>
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

<p>Initialize the extension for parsing using the given <span class="doxyComputerOutput">Parser</span>.</p>


<p>The extension should use the AsmParser interfaces to register its parsing routines.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a77a335167c72ea8bc771501825f81696">llvm::MCAsmParserExtension::Initialize</a>, <a href="#a53ec93cf1c2f4fe004cbb77fa439e90b">parseSectionDirectiveLazySymbolPointers</a>, <a href="#a15fce59624f758ed2432c9de1352ce7e">parseSectionDirectiveNonLazySymbolPointers</a>, <a href="#acc4d34a196a5c54ebe98ea445b212ee4">parseSectionDirectiveObjCInstanceVars</a>, <a href="#adba18a8d6c9e8868212e298c4e1955b6">parseSectionDirectiveObjCMethVarNames</a>, <a href="#ab4c1fd940790f3a2bcd71a8823dc04ba">parseSectionDirectiveObjCMethVarTypes</a>, <a href="#afe85c872285d4051252674641f19a178">parseSectionDirectiveObjCSelectorStrs</a>, <a href="#a90acdc4fe681273a7ee1be1aa334c872">parseSectionDirectiveObjCStringObject</a> and <a href="#a74ce8995ef5213ea9854eff832ab3de0">parseSectionDirectiveThreadLocalVariablePointers</a>.</p>

</div>
</div>

### parseBuildVersion() {#a1a972ee6fe54b3bdbfbcf505162a75ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseBuildVersion (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseBuildVersion ::= .build_version (macos|ios|tvos|watchos), parseVersion parseSDKVersion</p>

<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a3fa87f63e16161bde91f88f7d4484c8a">llvm::MCAsmParserExtension::addErrorSuffix</a>, <a href="#a0a06fbb4615244e2f5e81529fd08a9d0">checkVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp/#ac4bb416185172ddb6e598d7fa48af2f9">getOSTypeFromPlatform</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a4235d087dc899291be41be9db4d811a9">llvm::MCAsmParserExtension::getTok</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp/#a21988b6120a3252f50bd655296f7903d">isSDKVersionToken</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a2c0ffc86a3d3e895b526e036cf1aa4d3">llvm::MCAsmParserExtension::parseEOL</a>, <a href="#a5e5f912459671a68d8fb7dcb06fb322d">parseSDKVersion</a>, <a href="#a11a4d51524eaad36622be26b13c78256">parseVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveAltEntry() {#a463a346d7da05840b0c7f4b92dd3caf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveAltEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveAltEntry ::= .alt_entry identifier</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2899e74730516967f04d81966bb4f881">llvm::MCSymbol::isDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a452eae0b6838f1340eb75102bdfabd47">llvm::MCSA_AltEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveCGProfile() {#a5d48081548f77ae318b303f7c7ae26b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveCGProfile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCGProfile ::= .cg_profile from, to, count</p>

<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#acb5fd683cbbfb19a2e0d78ee46bb283c">llvm::MCAsmParserExtension::parseDirectiveCGProfile</a>.</p>

</div>
</div>

### parseDirectiveDataRegion() {#ae246971cdc93908b9f10e7e7a829314c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveDataRegion (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveDataRegion ::= .data_region [ ( jt8 | jt16 | jt32 ) ].</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a05d6258eaccbe86ca4c18e36910fda79">llvm::MCDR_DataRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008adc2335b540bd652d82bf3bcbed5a87d4">llvm::MCDR_DataRegionJT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008ac0586422896e4472fa7aa7118d9a4ecb">llvm::MCDR_DataRegionJT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a1183f27779c00ba04ce7aec4344952d2">llvm::MCDR_DataRegionJT8</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveDataRegionEnd() {#a6f0111046854925fdf5c7a297f6751c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveDataRegionEnd (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveDataRegionEnd ::= .end_data_region.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a0178c9475f859cfd8a0f552b8e22f412">llvm::MCDR_DataRegionEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveDesc() {#a7f3b0cb9ef7b3869b91009f946b1d560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveDesc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveDesc ::= .desc identifier , expression</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveDumpOrLoad() {#aea6c0e51b6f9cf34090c9a86852d932a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveDumpOrLoad (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveDumpOrLoad ::= ( .dump | .load ) "filename"</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58">llvm::AsmToken::String</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

### parseDirectiveIndirectSymbol() {#adb14af816964063e2e902f6d9586abcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveIndirectSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIndirectSymbol ::= .indirect_symbol identifier</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a2f530d6116df447fdadb8ef67239cd4e">llvm::MCSectionMachO::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a9c4d91f21dab6846f0eb7cdd8608c16a">llvm::MCSA_IndirectSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a4735e4e9043352fd4e19057bf95ea28a">llvm::MachO::S_LAZY_SYMBOL_POINTERS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a93912b05b13268a5cbd717f4a5fab8c9">llvm::MachO::S_NON_LAZY_SYMBOL_POINTERS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409ae03f48f1f4c31faadeac53f15460c2d6">llvm::MachO::S_SYMBOL_STUBS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a0b4240e38bf4066a8378e3a0450555ef">llvm::MachO::S_THREAD_LOCAL_VARIABLE_POINTERS</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveLinkerOption() {#ac817c5437e692128f921c71df5da2fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveLinkerOption (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveLinkerOption ::= .linker_option "string" ( , "string" )*.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58">llvm::AsmToken::String</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveLsym() {#a022d1cc063e7491e1378663102c8a4b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveLsym (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveLsym ::= .lsym identifier , expression</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectivePopSection() {#adccb36665f54db568d0fda77df5a2c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectivePopSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectivePopSection: ::= .popsection.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectivePrevious() {#aa34717c40eba0454dd55a5f74d5dbb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectivePrevious (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DirName, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectivePrevious: ::= .previous.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectivePushSection() {#a67167ef6f5bc9b24749cc75966450eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectivePushSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectivePushSection: ::= .pushsection identifier (',' identifier)*.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a> and <a href="#a757668838f5767cbf28d9a5b1201a646">parseDirectiveSection</a>.</p>

</div>
</div>

### parseDirectiveSection() {#a757668838f5767cbf28d9a5b1201a646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveSection: ::= .section identifier (',' identifier)*</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ab34712e7b8a90ef1894fd6a3b483179f">llvm::MCAsmParserExtension::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a587678b6051996e25d2bd6ebce323c9c">llvm::SectionKind::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a36d55da4fb88dbef3b548a7e25c99dd7">llvm::SectionKind::getText</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a1ea0b527a25e96bb74c8217704b22a07">llvm::MCSectionMachO::ParseSectionSpecifier</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">llvm::Triple::ppc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>


<p>Referenced by <a href="#a67167ef6f5bc9b24749cc75966450eb0">parseDirectivePushSection</a>.</p>

</div>
</div>

### parseDirectiveSecureLogReset() {#a35c606c799d33998f19368dbd9fb5c3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveSecureLogReset (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveSecureLogReset ::= .secure_log_reset.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveSecureLogUnique() {#a3237e027b109101104739097a3e415da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveSecureLogUnique (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveSecureLogUnique ::= .secure_log_unique ... message ...</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a0401ba9b53470dbdefa8e78d8b344e5d">llvm::MCAsmParserExtension::getSourceManager</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ac999fafdcc991e61bbc2df56a4310083">llvm::sys::fs::OF_Append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ab505c2c79499fbe180989bffbf108a50">llvm::sys::fs::OF_TextWithCRLF</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveSubsectionsViaSymbols() {#aa48439c82acdd2f356bfbf9e120e3bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveSubsectionsViaSymbols (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveSubsectionsViaSymbols ::= .subsections_via_symbols</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1adeea37757529c5d5cfeb922221d0f6f0">llvm::MCAF_SubsectionsViaSymbols</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveTBSS() {#a865b1c6f63f4309779f26c93bd7030bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveTBSS (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveTBSS ::= .tbss identifier, size, align.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a9ca4fd7df1d9dc2cf7c4a1046d5b6957">llvm::SectionKind::getThreadBSS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa462dae167e31cac32e97bb0c77ab071">llvm::MCSymbol::isUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a30ad04b8f551f61de19b8756ab76eae2">llvm::MachO::S_THREAD_LOCAL_ZEROFILL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseDirectiveZerofill() {#a684c8f59f91c7a9a03ed144fef80ba6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseDirectiveZerofill (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveZerofill ::= .zerofill segname , sectname [, identifier , size_expression [ , align_expression ]].</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a97d95412f17878de8c47a9d13fd91871">llvm::SectionKind::getBSS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa462dae167e31cac32e97bb0c77ab071">llvm::MCSymbol::isUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a901e329f9c215482ab4877d7efec0768">llvm::MachO::S_ZEROFILL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### parseIOSVersionMin() {#a80ed98b8d1e01ce06f29e69e9f5945e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseIOSVersionMin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626ead9e407b6ec006c31f17818a1283f6d3f">llvm::MCVM_IOSVersionMin</a> and <a href="#afb30c8e8f9bd310eefdf38def39c408a">parseVersionMin</a>.</p>

</div>
</div>

### parseMacOSXVersionMin() {#a1535d26083b8e2c2907f3df355ff1619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseMacOSXVersionMin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626ea386d6f60bcd1993e7d17e07a0af6affb">llvm::MCVM_OSXVersionMin</a> and <a href="#afb30c8e8f9bd310eefdf38def39c408a">parseVersionMin</a>.</p>

</div>
</div>

### parseMajorMinorVersionComponent() {#ada48b8f406d37c059696406dd6177d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseMajorMinorVersionComponent (unsigned * Major, unsigned * Minor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * VersionName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseMajorMinorVersionComponent ::= major, minor</p>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>


<p>Referenced by <a href="#a5e5f912459671a68d8fb7dcb06fb322d">parseSDKVersion</a> and <a href="#a11a4d51524eaad36622be26b13c78256">parseVersion</a>.</p>

</div>
</div>

### parseOptionalTrailingVersionComponent() {#ac2097c2b524a1f2b8a81abdf82679654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseOptionalTrailingVersionComponent (unsigned * Component, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ComponentName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalTrailingVersionComponent ::= , version_number</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>


<p>Referenced by <a href="#a5e5f912459671a68d8fb7dcb06fb322d">parseSDKVersion</a> and <a href="#a11a4d51524eaad36622be26b13c78256">parseVersion</a>.</p>

</div>
</div>

### parseSDKVersion() {#a5e5f912459671a68d8fb7dcb06fb322d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseSDKVersion (<a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> &amp; SDKVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a4235d087dc899291be41be9db4d811a9">llvm::MCAsmParserExtension::getTok</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp/#a21988b6120a3252f50bd655296f7903d">isSDKVersionToken</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="#ada48b8f406d37c059696406dd6177d32">parseMajorMinorVersionComponent</a> and <a href="#ac2097c2b524a1f2b8a81abdf82679654">parseOptionalTrailingVersionComponent</a>.</p>


<p>Referenced by <a href="#a1a972ee6fe54b3bdbfbcf505162a75ea">parseBuildVersion</a> and <a href="#afb30c8e8f9bd310eefdf38def39c408a">parseVersionMin</a>.</p>

</div>
</div>

### parseSectionDirectiveBss() {#ae16160a652212b911866e872c2f87e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveBss (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveConst() {#a00cf798d4d43fdb77066c73d437ed65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveConst (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveConstData() {#a2c400f64256609d0d2ac2f1a51108be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveConstData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveConstructor() {#afc9bbd0fd1133d18eced5801c718fddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveConstructor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveCString() {#af53f317a5cfa75be1d48ad2ab9277104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveCString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a857886b2cccfd23c2445e9912addf150">llvm::MachO::S_CSTRING_LITERALS</a>.</p>

</div>
</div>

### parseSectionDirectiveData() {#ae7e27d03cf1944ecaad8d3b1c9d1a5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveDestructor() {#a574101e489a48e854781fcf266b29f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveDestructor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveDyld() {#a820e7907d305bd5620af2a7718ab4ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveDyld (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveFVMLibInit0() {#ad095aa38fe7e564a2ccacd3a3cb1dda9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveFVMLibInit0 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveFVMLibInit1() {#a1feeaffc04438e78d2e2be3a65245b6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveFVMLibInit1 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveIdent() {#a7692f02f029f7b374e86d144e2055d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveIdent (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>.</p>

</div>
</div>

### parseSectionDirectiveLazySymbolPointers() {#a53ec93cf1c2f4fe004cbb77fa439e90b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveLazySymbolPointers (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a4735e4e9043352fd4e19057bf95ea28a">llvm::MachO::S_LAZY_SYMBOL_POINTERS</a>.</p>


<p>Referenced by <a href="#a60417cf07ab7af9a9d65ad7477c39214">Initialize</a>.</p>

</div>
</div>

### parseSectionDirectiveLiteral16() {#acd1ad69567e4ab4a7ad8256b5f85d255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveLiteral16 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a22ad6417ce1c6d4ecad57a09abbc8e78">llvm::MachO::S_16BYTE_LITERALS</a>.</p>

</div>
</div>

### parseSectionDirectiveLiteral4() {#a772d7f38e4800882c7028d01ca29186a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveLiteral4 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a96a823d462214dfff581d9471ec646e2">llvm::MachO::S_4BYTE_LITERALS</a>.</p>

</div>
</div>

### parseSectionDirectiveLiteral8() {#a9ea32416058437c8c635d20dacd27742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveLiteral8 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409abf30d8c4dee516771947b057cde186c4">llvm::MachO::S_8BYTE_LITERALS</a>.</p>

</div>
</div>

### parseSectionDirectiveModInitFunc() {#a8cb451a4f4ad1a35df4ba27060f01ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveModInitFunc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a61e394fcd6d71346ac33aad0f551459b">llvm::MachO::S_MOD_INIT_FUNC_POINTERS</a>.</p>

</div>
</div>

### parseSectionDirectiveModTermFunc() {#a401e65426d2f71742382c120b3c0cc55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveModTermFunc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a5933976355da08874b6a186342dbadd1">llvm::MachO::S_MOD_TERM_FUNC_POINTERS</a>.</p>

</div>
</div>

### parseSectionDirectiveNonLazySymbolPointers() {#a15fce59624f758ed2432c9de1352ce7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveNonLazySymbolPointers (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a93912b05b13268a5cbd717f4a5fab8c9">llvm::MachO::S_NON_LAZY_SYMBOL_POINTERS</a>.</p>


<p>Referenced by <a href="#a60417cf07ab7af9a9d65ad7477c39214">Initialize</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCCatClsMeth() {#aed715e74d6b109f7c253fe3543e1f07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCCatClsMeth (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCCategory() {#a43ee677b588304f17b5fbb282c7401d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCCategory (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCCatInstMeth() {#a7e33dc3da93e7f1d805a0ed82f78a1ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCCatInstMeth (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCClass() {#a6ac8af0e9c5c082ff419a20cdc42516b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCClass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCClassNames() {#a29b6d17d5f6f1859a2621ab7197edf27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCClassNames (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a857886b2cccfd23c2445e9912addf150">llvm::MachO::S_CSTRING_LITERALS</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCClassVars() {#aa99fff813150a25b4e44d53d393d44f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCClassVars (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCClsMeth() {#ac2d591c077b4c616c93d77c1bf57e49f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCClsMeth (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCClsRefs() {#a48bce75e438068cf105294149f68eb03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCClsRefs (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409aa906bb55cd8e457ca1ffce51741d055e">llvm::MachO::S_LITERAL_POINTERS</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCInstanceVars() {#acc4d34a196a5c54ebe98ea445b212ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCInstanceVars (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>


<p>Referenced by <a href="#a60417cf07ab7af9a9d65ad7477c39214">Initialize</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCInstMeth() {#ae0cf233d7dded51f051d2b9b7bea2e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCInstMeth (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCMessageRefs() {#afc47d1c5fad97ba5387c7925e029c2f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCMessageRefs (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409aa906bb55cd8e457ca1ffce51741d055e">llvm::MachO::S_LITERAL_POINTERS</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCMetaClass() {#a1424b4ba2bccbc7096fd14419746dc8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCMetaClass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCMethVarNames() {#adba18a8d6c9e8868212e298c4e1955b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCMethVarNames (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a857886b2cccfd23c2445e9912addf150">llvm::MachO::S_CSTRING_LITERALS</a>.</p>


<p>Referenced by <a href="#a60417cf07ab7af9a9d65ad7477c39214">Initialize</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCMethVarTypes() {#ab4c1fd940790f3a2bcd71a8823dc04ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCMethVarTypes (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a857886b2cccfd23c2445e9912addf150">llvm::MachO::S_CSTRING_LITERALS</a>.</p>


<p>Referenced by <a href="#a60417cf07ab7af9a9d65ad7477c39214">Initialize</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCModuleInfo() {#a2837f85a93a5c4576eb6abee271c2057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCModuleInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCProtocol() {#aba7dc05406fc68fa9e0a96c0d033b0c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCProtocol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCSelectorStrs() {#afe85c872285d4051252674641f19a178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCSelectorStrs (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a857886b2cccfd23c2445e9912addf150">llvm::MachO::S_CSTRING_LITERALS</a>.</p>


<p>Referenced by <a href="#a60417cf07ab7af9a9d65ad7477c39214">Initialize</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCStringObject() {#a90acdc4fe681273a7ee1be1aa334c872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCStringObject (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>


<p>Referenced by <a href="#a60417cf07ab7af9a9d65ad7477c39214">Initialize</a>.</p>

</div>
</div>

### parseSectionDirectiveObjCSymbols() {#a7a419999eaa924169be7f24e8b2e79c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveObjCSymbols (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a219d3dc4a2d2ca1840c300a63956df44">llvm::MachO::S_ATTR_NO_DEAD_STRIP</a>.</p>

</div>
</div>

### parseSectionDirectivePICSymbolStub() {#a456a08446ef9b2f8d615a2ac65b0bc60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectivePICSymbolStub (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a96ef438f63eb95474a1bb24b8ef24e5b">llvm::MachO::S_ATTR_PURE_INSTRUCTIONS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409ae03f48f1f4c31faadeac53f15460c2d6">llvm::MachO::S_SYMBOL_STUBS</a>.</p>

</div>
</div>

### parseSectionDirectiveStaticConst() {#ae05d3b52e52765e7ab7a3271bed3d475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveStaticConst (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveStaticData() {#a7ac63c84558e6b85ad8019834b52c358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveStaticData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveSymbolStub() {#a93fd2572a8e2654644b7ec8fdf2a1b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveSymbolStub (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a96ef438f63eb95474a1bb24b8ef24e5b">llvm::MachO::S_ATTR_PURE_INSTRUCTIONS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409ae03f48f1f4c31faadeac53f15460c2d6">llvm::MachO::S_SYMBOL_STUBS</a>.</p>

</div>
</div>

### parseSectionDirectiveTData() {#ad80d1ffc772157a8086b9487ff7ad3af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveTData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a859e2b1570a6cbc56a0449589c4645ae">llvm::MachO::S_THREAD_LOCAL_REGULAR</a>.</p>

</div>
</div>

### parseSectionDirectiveText() {#a070b2f2ad69f69969a7e29784e89ce1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveText (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a96ef438f63eb95474a1bb24b8ef24e5b">llvm::MachO::S_ATTR_PURE_INSTRUCTIONS</a>.</p>

</div>
</div>

### parseSectionDirectiveThreadInitFunc() {#a8bb3ea963f9194c1821e16911f8040c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveThreadInitFunc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a279435a8b308da87e4d920ed3ef7b2d3">llvm::MachO::S_THREAD_LOCAL_INIT_FUNCTION_POINTERS</a>.</p>

</div>
</div>

### parseSectionDirectiveThreadLocalVariablePointers() {#a74ce8995ef5213ea9854eff832ab3de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveThreadLocalVariablePointers (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a0b4240e38bf4066a8378e3a0450555ef">llvm::MachO::S_THREAD_LOCAL_VARIABLE_POINTERS</a>.</p>


<p>Referenced by <a href="#a60417cf07ab7af9a9d65ad7477c39214">Initialize</a>.</p>

</div>
</div>

### parseSectionDirectiveTLV() {#ac397f90fb6124675e37a3b5ad6c25ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseSectionDirectiveTLV (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409ada9065a004d3bc6b6d7b4c7b721060fd">llvm::MachO::S_THREAD_LOCAL_VARIABLES</a>.</p>

</div>
</div>

### parseTvOSVersionMin() {#a5fc371dc374b982a002dbf368f986390}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseTvOSVersionMin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626eaa7ab690e482966c940af477dcf395dce">llvm::MCVM_TvOSVersionMin</a> and <a href="#afb30c8e8f9bd310eefdf38def39c408a">parseVersionMin</a>.</p>

</div>
</div>

### parseVersion() {#a11a4d51524eaad36622be26b13c78256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseVersion (unsigned * Major, unsigned * Minor, unsigned * Update)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseVersion ::= parseMajorMinorVersionComponent parseOptionalTrailingVersionComponent</p>

<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a4235d087dc899291be41be9db4d811a9">llvm::MCAsmParserExtension::getTok</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp/#a21988b6120a3252f50bd655296f7903d">isSDKVersionToken</a>, <a href="#ada48b8f406d37c059696406dd6177d32">parseMajorMinorVersionComponent</a>, <a href="#ac2097c2b524a1f2b8a81abdf82679654">parseOptionalTrailingVersionComponent</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>


<p>Referenced by <a href="#a1a972ee6fe54b3bdbfbcf505162a75ea">parseBuildVersion</a> and <a href="#afb30c8e8f9bd310eefdf38def39c408a">parseVersionMin</a>.</p>

</div>
</div>

### parseVersionMin() {#afb30c8e8f9bd310eefdf38def39c408a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseVersionMin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626e">MCVersionMinType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseVersionMin ::= .ios_version_min parseVersion parseSDKVersion | .macosx_version_min parseVersion parseSDKVersion | .tvos_version_min parseVersion parseSDKVersion | .watchos_version_min parseVersion parseSDKVersion</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a3fa87f63e16161bde91f88f7d4484c8a">llvm::MCAsmParserExtension::addErrorSuffix</a>, <a href="#a0a06fbb4615244e2f5e81529fd08a9d0">checkVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp/#aa4d2f023c0c7b2b0d1819481165af656">getOSTypeFromMCVM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a4235d087dc899291be41be9db4d811a9">llvm::MCAsmParserExtension::getTok</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp/#a21988b6120a3252f50bd655296f7903d">isSDKVersionToken</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a2c0ffc86a3d3e895b526e036cf1aa4d3">llvm::MCAsmParserExtension::parseEOL</a>, <a href="#a5e5f912459671a68d8fb7dcb06fb322d">parseSDKVersion</a> and <a href="#a11a4d51524eaad36622be26b13c78256">parseVersion</a>.</p>


<p>Referenced by <a href="#a80ed98b8d1e01ce06f29e69e9f5945e5">parseIOSVersionMin</a>, <a href="#a1535d26083b8e2c2907f3df355ff1619">parseMacOSXVersionMin</a>, <a href="#a5fc371dc374b982a002dbf368f986390">parseTvOSVersionMin</a> and <a href="#acf15ff7e79d0b2b8282032b72a11323d">parseWatchOSVersionMin</a>.</p>

</div>
</div>

### parseWatchOSVersionMin() {#acf15ff7e79d0b2b8282032b72a11323d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseWatchOSVersionMin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626ea183c1e03234356aae7e6f65d0b0931f4">llvm::MCVM_WatchOSVersionMin</a> and <a href="#afb30c8e8f9bd310eefdf38def39c408a">parseVersionMin</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDirectiveHandler() {#a8d3dce353e7eac73501c00ca0f5443ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool(DarwinAsmParser::*)(StringRef, SMLoc) HandlerMethod&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::addDirectiveHandler (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

### parseSectionSwitch() {#adc76257731956ed13cb46b6dbef5ed31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DarwinAsmParser::parseSectionSwitch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Segment, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, unsigned TAA=0, unsigned ImplicitAlign=0, unsigned StubSize=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LastVersionDirective {#a94b3d5458cf6b8ea0e4a3353416e4f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::LastVersionDirective</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp">DarwinAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
