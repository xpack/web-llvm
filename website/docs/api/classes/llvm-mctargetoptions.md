---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mctargetoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCTargetOptions` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCTargetOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AsmInstrumentation { <a href="#ab3e07439105776ddfef6ac036a71b2e9">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DwarfDirectory { <a href="#a465c716319177c7bd66f91856de9b950">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe45569eb1fc361fe06c7eaa6eb560d2">getABIName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getABIName - If this returns a non-empty string this represents the textual name of the ABI that we want the backend to use, e.g. <a href="#abe45569eb1fc361fe06c7eaa6eb560d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c0d5c2bbef51e1321b085fea8ac151">getAssemblyLanguage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAssemblyLanguage - If this returns a non-empty string this represents the textual name of the assembly language that we will use for this target, e.g. <a href="#a99c0d5c2bbef51e1321b085fea8ac151">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3544137759e331c4e642b503446ae37">MCRelaxAll</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8e1262e292540ca8d5d018595e6321e">MCNoExecStack</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f6d1d4964cb277768b52c4e35eb528a">MCFatalWarnings</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc259c9de184410d907dc5ceaaca66c">MCNoWarn</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd255769b72684d7f95a51543d7b482b">MCNoDeprecatedWarn</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27b0881b107fd89bb8a0f9ed80c86f8">MCNoTypeCheck</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10e48ae7fceb4c0cf4472c6540dc3167">MCSaveTempLabels</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab77c97fec0d6362479ced908a5323a39">MCIncrementalLinkerCompatible</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9704f25f7a07b19cfc3aa8e880abb180">FDPIC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e87b5414c2d2fc8156ad1dfb7fed2d">ShowMCEncoding</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290c2759caa16dd5c9e5cc00d1f6eb97">ShowMCInst</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192e9c2a63352ff1000ebe757e5b1f12">AsmVerbose</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125c3ac3a9e34b7e0d51305aaaad1e84">PreserveAsmComments</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Preserve Comments in Assembly. <a href="#a125c3ac3a9e34b7e0d51305aaaad1e84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa51c36e502e100769e3e546dba091e4e">Dwarf64</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c88d87144f11ed223126c42717b91c3">Crel</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e9b008c809aa499263cff181c10248">ImplicitMapSyms</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a106ade7efd6ef5456719c4213759416c">X86RelaxRelocations</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb3b119d58305767b270fce6bca9c79">X86Sse2Avx</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa5631019db32a47ffc833696038b6e">OutputAsmVariant</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a86a87fba6a15227ff4f33edd538e6d0f">EmitDwarfUnwindType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59bbe0608c986366f813fb874a5bb1ad">EmitDwarfUnwind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927fc8de228c8bd3d98ebbd8a3b9ac4c">DwarfVersion</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a465c716319177c7bd66f91856de9b950">DwarfDirectory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ebf0d418b7b9e095f2fea195ca3647e">MCUseDwarfDirectory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00">DebugCompressionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fcf2c30f6f52244ed3a3ab649aa058c">CompressDebugSections</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00a6adf97f83acf6453d4a6a4b1070f3754">DebugCompressionType::None</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ad049c9ea46724ff90d40440cebf6a">ABIName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aead1aa5df244dc5d1211264eb7a6a1ec">AssemblyLanguage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acefd0594d6d756c7157223199d2865b0">SplitDwarfFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13df3bc8f64c9fed490adab0443ad510">AsSecureLogFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d1e967f0d6a1e5be0fb8b0cc1a2bc4">Argv0</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e18a122d4011a01584fae89234f8160">CommandlineArgs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b23a839cd13469d3ca05db20f45aeb">IASSearchPaths</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Additional paths to search for <span class="doxyComputerOutput">.include</span> directives when using the integrated assembler. <a href="#a95b23a839cd13469d3ca05db20f45aeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b2bb92f0f16cc71abb01992c3e2ff2">EmitCompactUnwindNonCanonical</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd640a184aedbe8bd30e2051c6e9301">PPCUseFullRegisterNames</a></td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AsmInstrumentation {#ab3e07439105776ddfef6ac036a71b2e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCTargetOptions::AsmInstrumentation </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AsmInstrumentationNone<a id="ab3e07439105776ddfef6ac036a71b2e9a8b8b2c37f69cfac2d00742bff926d81c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AsmInstrumentationAddress<a id="ab3e07439105776ddfef6ac036a71b2e9afcba2f371a23cbc282781fb3889a9888"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

### DwarfDirectory {#a465c716319177c7bd66f91856de9b950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCTargetOptions::DwarfDirectory </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DisableDwarfDirectory<a id="a465c716319177c7bd66f91856de9b950ad2087ee63cfdfb4d320b2fed6ccd93a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EnableDwarfDirectory<a id="a465c716319177c7bd66f91856de9b950a0ad3dcce4e7f9e1fa609ed0c529aba6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DefaultDwarfDirectory<a id="a465c716319177c7bd66f91856de9b950a58188af3953f4687fd6806e933e23fff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCTargetOptions() {#ae66d32a696f11369da4e9a7c2bbd41e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetOptions::MCTargetOptions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mctargetoptions-cpp">MCTargetOptions.cpp</a>.</p>


<p>References <a href="#a192e9c2a63352ff1000ebe757e5b1f12">AsmVerbose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="#a465c716319177c7bd66f91856de9b950a58188af3953f4687fd6806e933e23fff">DefaultDwarfDirectory</a>, <a href="#aa51c36e502e100769e3e546dba091e4e">Dwarf64</a>, <a href="#a57b2bb92f0f16cc71abb01992c3e2ff2">EmitCompactUnwindNonCanonical</a>, <a href="#a59bbe0608c986366f813fb874a5bb1ad">EmitDwarfUnwind</a>, <a href="#a9704f25f7a07b19cfc3aa8e880abb180">FDPIC</a>, <a href="#a2f6d1d4964cb277768b52c4e35eb528a">MCFatalWarnings</a>, <a href="#ab77c97fec0d6362479ced908a5323a39">MCIncrementalLinkerCompatible</a>, <a href="#afd255769b72684d7f95a51543d7b482b">MCNoDeprecatedWarn</a>, <a href="#aa8e1262e292540ca8d5d018595e6321e">MCNoExecStack</a>, <a href="#ac27b0881b107fd89bb8a0f9ed80c86f8">MCNoTypeCheck</a>, <a href="#a9bc259c9de184410d907dc5ceaaca66c">MCNoWarn</a>, <a href="#ad3544137759e331c4e642b503446ae37">MCRelaxAll</a>, <a href="#a10e48ae7fceb4c0cf4472c6540dc3167">MCSaveTempLabels</a>, <a href="#a2ebf0d418b7b9e095f2fea195ca3647e">MCUseDwarfDirectory</a>, <a href="#a5cd640a184aedbe8bd30e2051c6e9301">PPCUseFullRegisterNames</a>, <a href="#a125c3ac3a9e34b7e0d51305aaaad1e84">PreserveAsmComments</a>, <a href="#a28e87b5414c2d2fc8156ad1dfb7fed2d">ShowMCEncoding</a>, <a href="#a290c2759caa16dd5c9e5cc00d1f6eb97">ShowMCInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getABIName() {#abe45569eb1fc361fe06c7eaa6eb560d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MCTargetOptions::getABIName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getABIName - If this returns a non-empty string this represents the textual name of the ABI that we want the backend to use, e.g.</p>


<p>o32, or aapcs-linux.</p>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mctargetoptions-cpp">MCTargetOptions.cpp</a>.</p>


<p>Reference <a href="#ad8ad049c9ea46724ff90d40440cebf6a">ABIName</a>.</p>

</div>
</div>

### getAssemblyLanguage() {#a99c0d5c2bbef51e1321b085fea8ac151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MCTargetOptions::getAssemblyLanguage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAssemblyLanguage - If this returns a non-empty string this represents the textual name of the assembly language that we will use for this target, e.g.</p>


<p>masm.</p>


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mctargetoptions-cpp">MCTargetOptions.cpp</a>.</p>


<p>Reference <a href="#aead1aa5df244dc5d1211264eb7a6a1ec">AssemblyLanguage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ABIName {#ad8ad049c9ea46724ff90d40440cebf6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCTargetOptions::ABIName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#abe45569eb1fc361fe06c7eaa6eb560d2">getABIName</a> and <a href="/web-llvm/docs/api/groups/llvmctarget/#gad5c3bf4cc627842e1987abae68f676de">LLVMCreateTargetMachineWithOptions</a>.</p>

</div>
</div>

### Argv0 {#a75d1e967f0d6a1e5be0fb8b0cc1a2bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCTargetOptions::Argv0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

### AsmVerbose {#a192e9c2a63352ff1000ebe757e5b1f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::AsmVerbose</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a> and <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### AsSecureLogFile {#a13df3bc8f64c9fed490adab0443ad510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCTargetOptions::AsSecureLogFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

### AssemblyLanguage {#aead1aa5df244dc5d1211264eb7a6a1ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCTargetOptions::AssemblyLanguage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#a99c0d5c2bbef51e1321b085fea8ac151">getAssemblyLanguage</a>.</p>

</div>
</div>

### CommandlineArgs {#a5e18a122d4011a01584fae89234f8160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCTargetOptions::CommandlineArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

### CompressDebugSections {#a8fcf2c30f6f52244ed3a3ab649aa058c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugCompressionType llvm::MCTargetOptions::CompressDebugSections = <a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00a6adf97f83acf6453d4a6a4b1070f3754">DebugCompressionType::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

### Crel {#a3c88d87144f11ed223126c42717b91c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::Crel = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a01e8d5b5fce0c5c0440880ba3af1e2ca">anonymous{ELFObjectWriter.cpp}::ELFWriter::createRelocationSection</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#af1d4d772f1ae1ed6488491408a1244a4">llvm::ELFObjectWriter::usesRela</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aa07832cc5201fc524e000dcc171a70e7">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeRelocations</a>.</p>

</div>
</div>

### Dwarf64 {#aa51c36e502e100769e3e546dba091e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::Dwarf64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### DwarfVersion {#a927fc8de228c8bd3d98ebbd8a3b9ac4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MCTargetOptions::DwarfVersion = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

### EmitCompactUnwindNonCanonical {#a57b2bb92f0f16cc71abb01992c3e2ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::EmitCompactUnwindNonCanonical</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### EmitDwarfUnwind {#a59bbe0608c986366f813fb874a5bb1ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmitDwarfUnwindType llvm::MCTargetOptions::EmitDwarfUnwind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### FDPIC {#a9704f25f7a07b19cfc3aa8e880abb180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::FDPIC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### IASSearchPaths {#a95b23a839cd13469d3ca05db20f45aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::MCTargetOptions::IASSearchPaths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Additional paths to search for <span class="doxyComputerOutput">.include</span> directives when using the integrated assembler.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

### ImplicitMapSyms {#a00e9b008c809aa499263cff181c10248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::ImplicitMapSyms = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfstreamer-cpp-/aarch64elfstreamer/#ab3c1d7ab672f0bd15bc00752eb7f8c4d">anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::AArch64ELFStreamer</a>.</p>

</div>
</div>

### MCFatalWarnings {#a2f6d1d4964cb277768b52c4e35eb528a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::MCFatalWarnings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### MCIncrementalLinkerCompatible {#ab77c97fec0d6362479ced908a5323a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::MCIncrementalLinkerCompatible</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### MCNoDeprecatedWarn {#afd255769b72684d7f95a51543d7b482b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::MCNoDeprecatedWarn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### MCNoExecStack {#aa8e1262e292540ca8d5d018595e6321e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::MCNoExecStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### MCNoTypeCheck {#ac27b0881b107fd89bb8a0f9ed80c86f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::MCNoTypeCheck</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### MCNoWarn {#a9bc259c9de184410d907dc5ceaaca66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::MCNoWarn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### MCRelaxAll {#ad3544137759e331c4e642b503446ae37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::MCRelaxAll</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### MCSaveTempLabels {#a10e48ae7fceb4c0cf4472c6540dc3167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::MCSaveTempLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### MCUseDwarfDirectory {#a2ebf0d418b7b9e095f2fea195ca3647e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfDirectory llvm::MCTargetOptions::MCUseDwarfDirectory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a> and <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### OutputAsmVariant {#a8aa5631019db32a47ffc833696038b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::MCTargetOptions::OutputAsmVariant</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

### PPCUseFullRegisterNames {#a5cd640a184aedbe8bd30e2051c6e9301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::PPCUseFullRegisterNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### PreserveAsmComments {#a125c3ac3a9e34b7e0d51305aaaad1e84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::PreserveAsmComments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Preserve Comments in Assembly.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### ShowMCEncoding {#a28e87b5414c2d2fc8156ad1dfb7fed2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::ShowMCEncoding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### ShowMCInst {#a290c2759caa16dd5c9e5cc00d1f6eb97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::ShowMCInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="#ae66d32a696f11369da4e9a7c2bbd41e5">MCTargetOptions</a>.</p>

</div>
</div>

### SplitDwarfFile {#acefd0594d6d756c7157223199d2865b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCTargetOptions::SplitDwarfFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

### X86RelaxRelocations {#a106ade7efd6ef5456719c4213759416c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::X86RelaxRelocations = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>.</p>

</div>
</div>

### X86Sse2Avx {#afdb3b119d58305767b270fce6bca9c79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCTargetOptions::X86Sse2Avx = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">MCTargetOptions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mctargetoptions-cpp">MCTargetOptions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
