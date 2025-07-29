---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-asmparser-cpp-/asmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AsmParser` Class

<p>The concrete assembly parser instance. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{AsmParser.cpp}::AsmParser { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic assembler parser interface, for use by target specific assembly parsers. <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/hlasmasmparser">HLASMAsmParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d1a7fb69c6ee8e272ede2e29448a50">AsmParser</a> (SourceMgr &amp;SM, MCContext &amp;Ctx, MCStreamer &amp;Out, const MCAsmInfo &amp;MAI, unsigned CB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab037ee439331dc5b5a03626ada94cc7f">AsmParser</a> (const AsmParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ed0042b8e6c36abcf883ba9efb975d">~AsmParser</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser">AsmParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52700f1434ad3c2b676029a89630e526">operator=</a> (const AsmParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">Run</a> (bool NoInitialTextSection, bool NoFinalize=false) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the parser on the input source buffer. <a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4abe3da9de4f2f7293fec78bebf6e93">addDirectiveHandler</a> (StringRef Directive, ExtensionDirectiveHandler Handler) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b3a355413b120f5a101863780e3c44a">addAliasForDirective</a> (StringRef Directive, StringRef Alias) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a> (ParseStatementInfo &amp;Info, MCAsmParserSemaCallback *SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseStatement: ::= EndOfStatement ::= Label* <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> ...Operands... EndOfStatement ::= Label* Identifier OperandList* EndOfStatement. <a href="#a034b546ea133319ab2244f9bfa28ecae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaaaf7da6379fe3994da86bf71024ddc">parseAndMatchAndEmitTargetInstruction</a> (ParseStatementInfo &amp;Info, StringRef IDVal, AsmToken ID, SMLoc IDLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This routine uses the target specific ParseInstruction function to parse an instruction into Operands, and then call the target specific MatchAndEmit function to match and emit the instruction. <a href="#afaaaf7da6379fe3994da86bf71024ddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdbd82da864ad373a4e42c0ed3b2230">enabledGenDwarfForAssembly</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we emit DWARF describing this assembler source? <a href="#abfdbd82da864ad373a4e42c0ed3b2230">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmlexer">AsmLexer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c1c92d783d95b33bdede842ee01148">Lexer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5980113b36fe57c60cb729d8987ffb0">Ctx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc92beaaef3e326b21b008b49faa6732">Out</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e4fa8972015729a4c21cad5506708b">MAI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6b4499584c3db46e263719ee1ea0417">SrcMgr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acf78be89ec851a45f37a776a5a58bfe8">SourceMgr::DiagHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d0e1bbc98b27af9a70270c4941c462f">SavedDiagHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6cd807d4fafcef1df97e56f6b1e4e8f">SavedDiagContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension">MCAsmParserExtension</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c7d2f4a235c08dfc2393cf7b2a43b91">PlatformParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1435a18a3fb9665b2ac299753961717c">StartTokLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec8ccc73a96b1a571880e0add4d204aa">CFIStartProcLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb36083ed0bc97755173a4155daacb44">CurBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the current buffer index we're lexing from as managed by the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> object. <a href="#aeb36083ed0bc97755173a4155daacb44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmcond">AsmCond</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ab15e76eb3d7894202fdfd7a2f3340">TheCondState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/asmcond">AsmCond</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa84f8597aad6eb28a8ff6e67d385925">TheCondStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a9ce3532c090e7b66928ff9a42dae508c">ExtensionDirectiveHandler</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65fc7cfe2af91012f038f58cb9fec3a6">ExtensionDirectiveMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>maps directive names to handler methods in parser extensions. <a href="#a65fc7cfe2af91012f038f58cb9fec3a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/macroinstantiation">MacroInstantiation</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5cd24b539bb880e941a1794482e815a">ActiveMacros</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stack of active macro instantiations. <a href="#ac5cd24b539bb880e941a1794482e815a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc0f3599fe175f964d6e01bf62284ce">MacroLikeBodies</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of bodies of anonymous macros. <a href="#a7dc0f3599fe175f964d6e01bf62284ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9af3c6ee49f8b4055af6300c913fdf13">MacrosEnabledFlag</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> tracking whether macro substitution is enabled. <a href="#a9af3c6ee49f8b4055af6300c913fdf13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f60e19b7dc5b4f176bb4d6c2226f46">NumOfMacroInstantiations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of how many .macro's have been instantiated. <a href="#a48f60e19b7dc5b4f176bb4d6c2226f46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">CppHashInfoTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9df8ad225acfabf969e380d4c352cc">CppHashInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdebdc851185cf639050a820185bef80">HadCppHashFilename</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Have we seen any file line comment. <a href="#afdebdc851185cf639050a820185bef80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>, CppHashInfoTy, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70068f55a290367b773ba215ad0092b6">DirLabels</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of forward directional labels for diagnosis at the end. <a href="#a70068f55a290367b773ba215ad0092b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73501b5e5d2e2f570d3c1f8917e73418">LTODiscardSymbols</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4b506d0c4c6c99b2e969ff366ee30f">AssemblerDialect</a> = ~0U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AssemblerDialect. ~OU means unset value and use value provided by MAI. <a href="#a6f4b506d0c4c6c99b2e969ff366ee30f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f703fa0050256c4589e49ae5ab6545">IsDarwin</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>is Darwin compatibility enabled? <a href="#a95f703fa0050256c4589e49ae5ab6545">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a430bb91a030761c6a2e6b5c6f95ebca1">ParsingMSInlineAsm</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are we parsing ms-style inline assembly? <a href="#a430bb91a030761c6a2e6b5c6f95ebca1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab079468ed8e2225653583323822ab1c7">ReportedInconsistentMD5</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Did we already inform the user about inconsistent <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> usage? <a href="#ab079468ed8e2225653583323822ab1c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde08bfa9aa81411b204fbea9e73bffc">AltMacroMode</a> = false</td>
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

## MCAsmParser Interface Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AssignmentKind { <a href="#a1bbf8ed2a7170a885f4f5162736abc0c">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DirectiveKind { <a href="#a922449c7444d6a657e8ffd7b7ad88879">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">CVDefRangeType { <a href="#a8960eaf69d8b105ba62fab667264622b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; DirectiveKind &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb6dff5b397561a040817ad73e0f744">DirectiveKindMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps directive name --&gt; DirectiveKind enum, for directives parsed by this class. <a href="#aaeb6dff5b397561a040817ad73e0f744">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; CVDefRangeType &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeda338b84c3a92845277019323a4f517">CVDefRangeTypeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps Codeview def_range types --&gt; CVDefRangeType enum, for Codeview def_range types parsed by this class. <a href="#aeda338b84c3a92845277019323a4f517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeeb1b807d25ed0a194d15135330796f">getSourceManager</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmlexer">MCAsmLexer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ddf50b4cf84a930050c2e3affa6190">getLexer</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a054e4ac93e14d4f4c594f1b58a7c8e0a">getContext</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af0d74b30ef9c0a4e4d1c07300c26d6">getStreamer</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the output streamer for the assembler. <a href="#a3af0d74b30ef9c0a4e4d1c07300c26d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeviewcontext">CodeViewContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95abe1c2105d82b41baaa16d9a405be8">getCVContext</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4126089fcd9bbd3b8721c69567f847">getAssemblerDialect</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c016ce9ac36c99065a1c51b817c8cad">setAssemblerDialect</a> (unsigned i) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8b63a81cb9bf1891795b81d34b6972">Note</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a note at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#afd8b63a81cb9bf1891795b81d34b6972">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a5adf3db1aba1fc30809f73fc05c08">Warning</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a warning at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#a57a5adf3db1aba1fc30809f73fc05c08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a307a44ebfb83c5c16d6a0af1861547c1">printError</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an error at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#a307a44ebfb83c5c16d6a0af1861547c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next AsmToken in the stream, possibly handling file inclusion first. <a href="#af3d4af20be9f94cbdad904d45cafbefa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ef0d658df455dcf1c37cce90712788">setParsingMSInlineAsm</a> (bool V) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca8544a6b02c09c6fadee9c549fd0ec">isParsingMSInlineAsm</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfd6ef18b9ebd50358b7d4c3ddfa2f9e">discardLTOSymbol</a> (StringRef Name) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6779c29e343b8e71d97734686a3eabd2">parseMSInlineAsm</a> (std::string &amp;AsmString, unsigned &amp;NumOutputs, unsigned &amp;NumInputs, SmallVectorImpl&lt; std::pair&lt; void *, bool &gt; &gt; &amp;OpDecls, SmallVectorImpl&lt; std::string &gt; &amp;Constraints, SmallVectorImpl&lt; std::string &gt; &amp;Clobbers, const MCInstrInfo *MII, MCInstPrinter *IP, MCAsmParserSemaCallback &amp;SI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse MS-style inline assembly. <a href="#a6779c29e343b8e71d97734686a3eabd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc1050c60fea592a8902be95251705a">parseExpression</a> (const MCExpr *&amp;Res)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7fc5af218d2f17280c5b443dbe20838">parseExpression</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an expression and return it. <a href="#ac7fc5af218d2f17280c5b443dbe20838">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02bbdeea1375089f06a52747e919b4dc">parsePrimaryExpr</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc, AsmTypeInfo *TypeInfo) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a primary expression and return it. <a href="#a02bbdeea1375089f06a52747e919b4dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35423377e62d2d83bec01c6cf269b9f3">parseParenExpression</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an arbitrary expression, assuming that an initial '(' has already been consumed. <a href="#a35423377e62d2d83bec01c6cf269b9f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8f1c479ef06f41b1f2010afd80b43a">parseParenExprOfDepth</a> (unsigned ParenDepth, const MCExpr *&amp;Res, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an arbitrary expression of a specified parenthesis depth, assuming that the initial '(' characters have already been consumed. <a href="#a1c8f1c479ef06f41b1f2010afd80b43a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec28069dca3f6f64e1e5e13477d62688">parseAbsoluteExpression</a> (int64_t &amp;Res) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an expression which must evaluate to an absolute value. <a href="#aec28069dca3f6f64e1e5e13477d62688">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdaa8ae9b3e01099946066f89a8e10ad">parseRealValue</a> (const fltSemantics &amp;Semantics, APInt &amp;Res)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a floating point expression using the float <span class="doxyComputerOutput">Semantics</span> and set <span class="doxyComputerOutput">Res</span> to the value. <a href="#abdaa8ae9b3e01099946066f89a8e10ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91d3c1b093e3561b948794724961f4b">parseIdentifier</a> (StringRef &amp;Res) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an identifier or string (as a quoted identifier) and set <span class="doxyComputerOutput">Res</span> to the identifier contents. <a href="#aa91d3c1b093e3561b948794724961f4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a464d658f065637fc039e0645a94d87">eatToEndOfStatement</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Throw away the rest of the line for testing purposes. <a href="#a1a464d658f065637fc039e0645a94d87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a252ed0bb8924351d3e4a6a6cd6dd938f">checkForValidSection</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure that we have a valid section set in the streamer. <a href="#a252ed0bb8924351d3e4a6a6cd6dd938f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a12cece10f328b150b341acf27a9b2">parseCurlyBlockScope</a> (SmallVectorImpl&lt; AsmRewrite &gt; &amp;AsmStrRewrites)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#ac2a12cece10f328b150b341acf27a9b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6109f652dada46ce6418c67f2b79b710">parseCppHashLineFilenameComment</a> (SMLoc L, bool SaveLocInfo=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCppHashLineFilenameComment as this: ::= # number "filename" <a href="#a6109f652dada46ce6418c67f2b79b710">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83fee714b61cad4771b4b6c6fefacea">checkForBadMacro</a> (SMLoc DirectiveLoc, StringRef Name, StringRef Body, ArrayRef&lt; MCAsmMacroParameter &gt; Parameters)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkForBadMacro <a href="#aa83fee714b61cad4771b4b6c6fefacea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a939c2b49e45af39faaf482f0752d89ae">expandMacro</a> (raw_svector_ostream &amp;OS, MCAsmMacro &amp;Macro, ArrayRef&lt; MCAsmMacroParameter &gt; Parameters, ArrayRef&lt; MCAsmMacroArgument &gt; A, bool EnableAtPseudoVariable)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac7be96c8ee178a08cd86bbca2948431">areMacrosEnabled</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are macros enabled in the parser? <a href="#aac7be96c8ee178a08cd86bbca2948431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f1e4937edebd3aa3b2d3b85f66223dd">setMacrosEnabled</a> (bool Flag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Control a flag in the parser that enables or disables macros. <a href="#a9f1e4937edebd3aa3b2d3b85f66223dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e662ae1a842470452847a0c671d78cf">isInsideMacroInstantiation</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are we inside a macro instantiation? <a href="#a6e662ae1a842470452847a0c671d78cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa07796c3a7f0e6314119e7e6478a411f">handleMacroEntry</a> (MCAsmMacro *M, SMLoc NameLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle entry to macro instantiation. <a href="#aa07796c3a7f0e6314119e7e6478a411f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0c8eae34a387bfc736daff86361d56">handleMacroExit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle exit from macro instantiation. <a href="#a6b0c8eae34a387bfc736daff86361d56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776b90cc1bda03e592f370c9da56b63d">parseMacroArgument</a> (MCAsmMacroArgument &amp;MA, bool Vararg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract AsmTokens for a macro argument. <a href="#a776b90cc1bda03e592f370c9da56b63d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468af0d1c59a41301937bd9f3fb5ded6">parseMacroArguments</a> (const MCAsmMacro *M, MCAsmMacroArguments &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse all macro arguments for a given macro. <a href="#a468af0d1c59a41301937bd9f3fb5ded6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36a6362c5cb970cc8ddf02eac7a3414">printMacroInstantiations</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f3933720a830d7a60f62e43879d3b6">printMessage</a> (SMLoc Loc, SourceMgr::DiagKind Kind, const Twine &amp;Msg, SMRange Range=std::nullopt) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf4b7c99bb6159d9eeb01cd68346952">enterIncludeFile</a> (const std::string &amp;Filename)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enter the specified file. This returns true on failure. <a href="#adaf4b7c99bb6159d9eeb01cd68346952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac49ab77dcc55f1798c55872c96a92ea">processIncbinFile</a> (const std::string &amp;Filename, int64_t Skip=0, const MCExpr *Count=nullptr, SMLoc Loc=SMLoc())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the specified file for the .incbin directive. <a href="#aac49ab77dcc55f1798c55872c96a92ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab945e73bf2bf14615ae16f4bd24b7856">jumpToLoc</a> (SMLoc Loc, unsigned InBuffer=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the current lexer position to that given by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>. <a href="#ab945e73bf2bf14615ae16f4bd24b7856">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af927a042550c3a9220514a11b79b187d">parseStringToEndOfStatement</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse up to the end of statement and a return the contents from the current token until the end of the statement; the current token on exit will be either the EndOfStatement or EOF. <a href="#af927a042550c3a9220514a11b79b187d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7505aa908c01f185d61fac457c6f7a06">parseStringToComma</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse until the end of a statement or a comma is encountered, return the contents from the current token up to the end or comma. <a href="#a7505aa908c01f185d61fac457c6f7a06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22fb9ac9c913da9317de5dd47e922ab9">parseAssignment</a> (StringRef Name, AssignmentKind Kind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b05b4557ece0c3856d8f8cdc3cf02b">getBinOpPrecedence</a> (AsmToken::TokenKind K, MCBinaryExpr::Opcode &amp;Kind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8cd84f16db451a5e1f5a0686d1f6a51">parseBinOpRHS</a> (unsigned Precedence, const MCExpr *&amp;Res, SMLoc &amp;EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse all binary operators with precedence &gt;= 'Precedence'. <a href="#ab8cd84f16db451a5e1f5a0686d1f6a51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbee37ebbde2698746d5483f8374a1cb">parseParenExpr</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a paren expression and return it. <a href="#abbee37ebbde2698746d5483f8374a1cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa928ab3b2b141ead9902eb52f84eace3">parseBracketExpr</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a bracket expression and return it. <a href="#aa928ab3b2b141ead9902eb52f84eace3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26abcaa93dd78ecd18e762e40fbca90c">parseRegisterOrRegisterNumber</a> (int64_t &amp;Register, SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parse register name or number. <a href="#a26abcaa93dd78ecd18e762e40fbca90c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8526b37563ca2bdb20e8b8499bde194a">parseCVFunctionId</a> (int64_t &amp;FunctionId, StringRef DirectiveName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5013ebb4832779da0bd927c076fb526c">parseCVFileId</a> (int64_t &amp;FileId, StringRef DirectiveName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ece22de12907abcd359a5b633880910">parseDirectiveAscii</a> (StringRef IDVal, bool ZeroTerminated)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveAscii: <a href="#a1ece22de12907abcd359a5b633880910">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac624a83f61b5480aab4df0044320d348">parseDirectiveReloc</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveReloc ::= .reloc expression , identifier [ , expression ] <a href="#ac624a83f61b5480aab4df0044320d348">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe12d97b02636f4f593892a253fc9aed">parseDirectiveValue</a> (StringRef IDVal, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveValue ::= (.byte | .short | ... ) [ expression (, expression)* ] <a href="#afe12d97b02636f4f593892a253fc9aed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48cf8e2ed16948a3aa755bebfa0651be">parseDirectiveOctaValue</a> (StringRef IDVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveOctaValue ::= .octa [ hexconstant (, hexconstant)* ]. <a href="#a48cf8e2ed16948a3aa755bebfa0651be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c184b0044a4d9df31236d660da26303">parseDirectiveRealValue</a> (StringRef IDVal, const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveRealValue ::= (.single | .double) [ expression (, expression)* ] <a href="#a5c184b0044a4d9df31236d660da26303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb235ab04af23f15565e2a40ca38d233">parseDirectiveFill</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveFill ::= .fill expression [ , expression [ , expression ] ] <a href="#acb235ab04af23f15565e2a40ca38d233">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ccff216c84a0242f3146de9830f7614">parseDirectiveZero</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveZero ::= .zero expression <a href="#a9ccff216c84a0242f3146de9830f7614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9ee8a4f74f25632bd9c48d912b6b15">parseDirectiveSet</a> (StringRef IDVal, AssignmentKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveSet: ::= .equ identifier ',' expression ::= .equiv identifier ',' expression ::= .set identifier ',' expression ::= .lto_set_conditional identifier ',' expression <a href="#a4b9ee8a4f74f25632bd9c48d912b6b15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af26d818234b097f560c009daacc8f60e">parseDirectiveOrg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveOrg ::= .org expression [ , expression ] <a href="#af26d818234b097f560c009daacc8f60e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1f52851a21b14d9e075871bc59c8cd">parseDirectiveAlign</a> (bool IsPow2, unsigned ValueSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveAlign ::= {.align, ...} expression [ , expression [ , expression ]] <a href="#afd1f52851a21b14d9e075871bc59c8cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a123aff093d2907628798d82a960046ac">parseDirectiveFile</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveFile ::= .file filename ::= .file number [directory] filename [md5 checksum] [source source-text] <a href="#a123aff093d2907628798d82a960046ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc30b95c1824494b1deb4d70583aa680">parseDirectiveLine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveLine ::= .line [number] <a href="#acc30b95c1824494b1deb4d70583aa680">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a424c5458e89bd957a0b8de7c0cb3b">parseDirectiveLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveLoc ::= .loc FileNumber [LineNumber] [ColumnPos] [basic_block] [prologue_end] [epilogue_begin] [is_stmt VALUE] [isa VALUE] The first number is a file number, must have been previously assigned with a .file directive, the second number is the line number and optionally the third number is a column position (zero if not specified). <a href="#ad0a424c5458e89bd957a0b8de7c0cb3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3052e120496be89628041c77f2e4d26">parseDirectiveLocLabel</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveLoc ::= .loc_label label <a href="#af3052e120496be89628041c77f2e4d26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a550efe84411b279196e9db5341f33e09">parseDirectiveStabs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveStabs ::= .stabs string, number, number, number <a href="#a550efe84411b279196e9db5341f33e09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af785b1f5367c1ec9f3b1f9f9bd988560">parseDirectiveCVFile</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFile ::= .cv_file number filename [checksum] [checksumkind] <a href="#af785b1f5367c1ec9f3b1f9f9bd988560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cc20b416686fb4a25168442a56f027">parseDirectiveCVFuncId</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFuncId ::= .cv_func_id <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> <a href="#a07cc20b416686fb4a25168442a56f027">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7521709812209fb96bb00f99fc11225f">parseDirectiveCVInlineSiteId</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVInlineSiteId ::= .cv_inline_site_id <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> "within" IAFunc "inlined_at" IAFile IALine [IACol] <a href="#a7521709812209fb96bb00f99fc11225f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124ceb1405fa9ae2fd3d02606fc6c759">parseDirectiveCVLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVLoc ::= .cv_loc <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> FileNumber [LineNumber] [ColumnPos] [prologue_end] [is_stmt VALUE] The first number is a file number, must have been previously assigned with a .file directive, the second number is the line number and optionally the third number is a column position (zero if not specified). <a href="#a124ceb1405fa9ae2fd3d02606fc6c759">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39230a71860983f5a63a7cad11e02790">parseDirectiveCVLinetable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVLinetable ::= .cv_linetable <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, FnStart, FnEnd <a href="#a39230a71860983f5a63a7cad11e02790">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d4efd17a8e033e8d83f919085adc4ab">parseDirectiveCVInlineLinetable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVInlineLinetable ::= .cv_inline_linetable PrimaryFunctionId FileId LineNum FnStart FnEnd <a href="#a7d4efd17a8e033e8d83f919085adc4ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe637dc8ab41d86549b2262644e3cd9c">parseDirectiveCVDefRange</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVDefRange ::= .cv_def_range RangeStart RangeEnd (GapStart GapEnd)*, bytes* <a href="#abe637dc8ab41d86549b2262644e3cd9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a56f664dbb3c7706eaa2ec9cde5a6a">parseDirectiveCVString</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVString ::= .cv_stringtable "string" <a href="#a63a56f664dbb3c7706eaa2ec9cde5a6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7956bb61161dc983f0d93694d9ccd17">parseDirectiveCVStringTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVStringTable ::= .cv_stringtable <a href="#aa7956bb61161dc983f0d93694d9ccd17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b94185bbc2ddc7fe6e0d6de3ce43e6d">parseDirectiveCVFileChecksums</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFileChecksums ::= .cv_filechecksums <a href="#a8b94185bbc2ddc7fe6e0d6de3ce43e6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a600634b0fc1faf866a73ed973b941c94">parseDirectiveCVFileChecksumOffset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFileChecksumOffset ::= .cv_filechecksumoffset fileno <a href="#a600634b0fc1faf866a73ed973b941c94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a405f058ac862afe9541364a94472aa41">parseDirectiveCVFPOData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFPOData ::= .cv_fpo_data procsym <a href="#a405f058ac862afe9541364a94472aa41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a595f7c32bf4fe17d9248e89cdf6e4ac3">parseDirectiveCFIRegister</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRegister ::= .cfi_register register, register <a href="#a595f7c32bf4fe17d9248e89cdf6e4ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace82bd69be3c5ef608dd4c1e28195a90">parseDirectiveCFIWindowSave</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIWindowSave ::= .cfi_window_save <a href="#ace82bd69be3c5ef608dd4c1e28195a90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4999659eac834c3b41ee684347352c3c">parseDirectiveCFISections</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFISections ::= .cfi_sections section [, section] <a href="#a4999659eac834c3b41ee684347352c3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa817dc6a589a3f23be34caa217b8e8">parseDirectiveCFIStartProc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIStartProc ::= .cfi_startproc [simple] <a href="#a3aa817dc6a589a3f23be34caa217b8e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3365349f4aaefa17d38417599a78c4ec">parseDirectiveCFIEndProc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIEndProc ::= .cfi_endproc <a href="#a3365349f4aaefa17d38417599a78c4ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4a6e0cb0a8d46ad70750f5baa46151c">parseDirectiveCFIDefCfaOffset</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIDefCfaOffset ::= .cfi_def_cfa_offset offset <a href="#ab4a6e0cb0a8d46ad70750f5baa46151c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbda2cc95d38deca294d9bd2d24f07e3">parseDirectiveCFIDefCfa</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIDefCfa ::= .cfi_def_cfa register, offset <a href="#afbda2cc95d38deca294d9bd2d24f07e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be05dc230fa01a6aa6b129f503776d8">parseDirectiveCFIAdjustCfaOffset</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIAdjustCfaOffset ::= .cfi_adjust_cfa_offset adjustment <a href="#a2be05dc230fa01a6aa6b129f503776d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15fbc799680c561d5871957b9b8c939b">parseDirectiveCFIDefCfaRegister</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIDefCfaRegister ::= .cfi_def_cfa_register register <a href="#a15fbc799680c561d5871957b9b8c939b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cbf06a4de966d8889c62228a5f65d6b">parseDirectiveCFILLVMDefAspaceCfa</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFILLVMDefAspaceCfa ::= .cfi_llvm_def_aspace_cfa register, offset, address_space <a href="#a0cbf06a4de966d8889c62228a5f65d6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef75aa07050d01f3147d53694b6b4053">parseDirectiveCFIOffset</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIOffset ::= .cfi_offset register, offset <a href="#aef75aa07050d01f3147d53694b6b4053">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a5d1574c30795b26a50e60232861d11">parseDirectiveCFIRelOffset</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRelOffset ::= .cfi_rel_offset register, offset <a href="#a0a5d1574c30795b26a50e60232861d11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5887c9fa578d7628328e753c5909062a">parseDirectiveCFIPersonalityOrLsda</a> (bool IsPersonality)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIPersonalityOrLsda IsPersonality true for cfi_personality, false for cfi_lsda ::= .cfi_personality encoding, [symbol_name] ::= .cfi_lsda encoding, [symbol_name] <a href="#a5887c9fa578d7628328e753c5909062a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf32e6935922d5b75e81cdd5a65fdedf">parseDirectiveCFIRememberState</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRememberState ::= .cfi_remember_state <a href="#abf32e6935922d5b75e81cdd5a65fdedf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30fd3ed5521a615bee0285f5bfe64c6">parseDirectiveCFIRestoreState</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRestoreState ::= .cfi_remember_state <a href="#af30fd3ed5521a615bee0285f5bfe64c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4758997f0fe5366d5379d135ce65a4b">parseDirectiveCFISameValue</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFISameValue ::= .cfi_same_value register <a href="#ae4758997f0fe5366d5379d135ce65a4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2076847a2dab837e71d11aadd197a846">parseDirectiveCFIRestore</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRestore ::= .cfi_restore register <a href="#a2076847a2dab837e71d11aadd197a846">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0121136aefec723cad78c5e7beefae58">parseDirectiveCFIEscape</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIEscape ::= .cfi_escape expression[,...] <a href="#a0121136aefec723cad78c5e7beefae58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bcf05a8b320a5b571112c19d998c4f2">parseDirectiveCFIReturnColumn</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIReturnColumn ::= .cfi_return_column register <a href="#a8bcf05a8b320a5b571112c19d998c4f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335551445044983ae7c686c0b1a517e4">parseDirectiveCFISignalFrame</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFISignalFrame ::= .cfi_signal_frame <a href="#a335551445044983ae7c686c0b1a517e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceceeebca04a53fe6c5b5988be3a1950">parseDirectiveCFIUndefined</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIUndefined ::= .cfi_undefined register <a href="#aceceeebca04a53fe6c5b5988be3a1950">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9be73769c013d28ebe568fad1f455e">parseDirectiveCFILabel</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFILabel ::= .cfi_label label <a href="#adc9be73769c013d28ebe568fad1f455e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5d2e0e9342af988eab3bfa8325c44f">parseDirectiveCFIValOffset</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIValOffset ::= .cfi_val_offset register, offset <a href="#afc5d2e0e9342af988eab3bfa8325c44f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83880918c6668279f10dbae1fcb65081">parseDirectivePurgeMacro</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectivePurgeMacro ::= .purgem name <a href="#a83880918c6668279f10dbae1fcb65081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe72200661b3480e8456d7536b287e8b">parseDirectiveExitMacro</a> (StringRef Directive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveExitMacro ::= .exitm <a href="#afe72200661b3480e8456d7536b287e8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6df8a7b1240daf2ac4d7ee5c097760e">parseDirectiveEndMacro</a> (StringRef Directive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEndMacro ::= .endm ::= .endmacro <a href="#ab6df8a7b1240daf2ac4d7ee5c097760e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ddd2e5e3ad51820af135af61f8f72ec">parseDirectiveMacro</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveMacro ::= .macro name[,] [parameters] <a href="#a6ddd2e5e3ad51820af135af61f8f72ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a446748c012d8185f6f3366aaff97e">parseDirectiveMacrosOnOff</a> (StringRef Directive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveMacrosOnOff ::= .macros_on ::= .macros_off <a href="#a13a446748c012d8185f6f3366aaff97e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7567a0e2f43f88cf86e97f08789750e4">parseDirectiveAltmacro</a> (StringRef Directive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveAltmacro ::= .altmacro ::= .noaltmacro <a href="#a7567a0e2f43f88cf86e97f08789750e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6217914a481325450cb1b97a5a3b0a4f">parseDirectiveBundleAlignMode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveBundleAlignMode ::= {.bundle_align_mode} expression <a href="#a6217914a481325450cb1b97a5a3b0a4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c30a61328f44a83fbefb9b052a77978">parseDirectiveBundleLock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveBundleLock ::= {.bundle_lock} [align_to_end] <a href="#a0c30a61328f44a83fbefb9b052a77978">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4486f5598719d38a26d8477f2b53a5e0">parseDirectiveBundleUnlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveBundleLock ::= {.bundle_lock} <a href="#a4486f5598719d38a26d8477f2b53a5e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704dab055eff3732a67501c22a4926f3">parseDirectiveSpace</a> (StringRef IDVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveSpace ::= (.skip | .space) expression [ , expression ] <a href="#a704dab055eff3732a67501c22a4926f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e1f5c5dfa66aa72ab22f7b47b66bd7c">parseDirectiveDCB</a> (StringRef IDVal, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveDCB ::= .dcb. <a href="#a4e1f5c5dfa66aa72ab22f7b47b66bd7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43a7983cf873a8abbcd916c59694134f">parseDirectiveRealDCB</a> (StringRef IDVal, const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveRealDCB ::= .dcb. <a href="#a43a7983cf873a8abbcd916c59694134f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c3cddea3f74c3037f29f1cc4657f11">parseDirectiveDS</a> (StringRef IDVal, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveDS ::= .ds. <a href="#ab5c3cddea3f74c3037f29f1cc4657f11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af530a3132791044e662df1ce7ee7b06c">parseDirectiveLEB128</a> (bool Signed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveLEB128 ::= (.sleb128 | .uleb128) [ expression (, expression)* ] <a href="#af530a3132791044e662df1ce7ee7b06c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac716972afcc4947830d5d875229e3a3b">parseDirectiveSymbolAttribute</a> (MCSymbolAttr Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a directive like ".globl" which accepts a single symbol (which should be a label or an external). <a href="#ac716972afcc4947830d5d875229e3a3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac94039bfeec5c12c046737dfed26b30">parseDirectiveComm</a> (bool IsLocal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveComm ::= ( .comm | .lcomm ) identifier , size_expression [ , align_expression ] <a href="#aac94039bfeec5c12c046737dfed26b30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3a5e0c7c12c4f136a88bebb14d35108">parseDirectiveAbort</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveAbort ::= .abort [... message ...] <a href="#ab3a5e0c7c12c4f136a88bebb14d35108">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9989e87a059afc476e1c2f3deff42b9b">parseDirectiveInclude</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveInclude ::= .include "filename" <a href="#a9989e87a059afc476e1c2f3deff42b9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78af659d55c1755007b7c663518298f0">parseDirectiveIncbin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIncbin ::= .incbin "filename" [ , skip [ , count ] ] <a href="#a78af659d55c1755007b7c663518298f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7409e8b3993389e9a9087fc65d41ea19">parseDirectiveIf</a> (SMLoc DirectiveLoc, DirectiveKind DirKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIf ::= .if{,eq,ge,gt,le,lt,ne} expression <a href="#a7409e8b3993389e9a9087fc65d41ea19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e929743a74a7cbbe1f513c3bf91e33f">parseDirectiveIfb</a> (SMLoc DirectiveLoc, bool ExpectBlank)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIfb ::= .ifb string <a href="#a5e929743a74a7cbbe1f513c3bf91e33f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b9a1d7a44563361666c64ac6ba5ad60">parseDirectiveIfc</a> (SMLoc DirectiveLoc, bool ExpectEqual)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIfc ::= .ifc string1, string2 ::= .ifnc string1, string2 <a href="#a8b9a1d7a44563361666c64ac6ba5ad60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596b03dd3ec0f8eaa3d9e1e98cb717fd">parseDirectiveIfeqs</a> (SMLoc DirectiveLoc, bool ExpectEqual)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIfeqs ::= .ifeqs string1, string2 <a href="#a596b03dd3ec0f8eaa3d9e1e98cb717fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbac3caafc704d63811301dc318f7215">parseDirectiveIfdef</a> (SMLoc DirectiveLoc, bool expect_defined)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIfdef ::= .ifdef symbol <a href="#abbac3caafc704d63811301dc318f7215">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2f1a27158cef67c735a5c7df1b9674">parseDirectiveElseIf</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveElseIf ::= .elseif expression <a href="#a5d2f1a27158cef67c735a5c7df1b9674">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ec65d1967503cabbe22330b4357a75">parseDirectiveElse</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveElse ::= .else <a href="#a57ec65d1967503cabbe22330b4357a75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8059f3965fd6f3b06013767dcdd7c078">parseDirectiveEndIf</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEndIf ::= .endif <a href="#a8059f3965fd6f3b06013767dcdd7c078">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515e58918a1422275c98640a07a93fb7">parseEscapedString</a> (std::string &amp;Data) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the current token as a string which may include escaped characters and return the string contents. <a href="#a515e58918a1422275c98640a07a93fb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5347cc04614e8c6adca091ab5a919b2d">parseAngleBracketString</a> (std::string &amp;Data) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an angle-bracket delimited string at the current position if one is present, returning the string contents. <a href="#a5347cc04614e8c6adca091ab5a919b2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a81c9a201f832df3372f7df9f07ca1">applyModifierToExpr</a> (const MCExpr *E, MCSymbolRefExpr::VariantKind Variant)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b222a667ed694008b2978f3b541b195">parseMacroLikeBody</a> (SMLoc DirectiveLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3f1ee438bb4c31b48c16aa7e08a71f">instantiateMacroLikeBody</a> (MCAsmMacro *M, SMLoc DirectiveLoc, raw_svector_ostream &amp;OS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58557537569318a67a4f21d1502d12e9">parseDirectiveRept</a> (SMLoc DirectiveLoc, StringRef Directive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveRept ::= .rep | .rept count <a href="#a58557537569318a67a4f21d1502d12e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54bac06b53c01858f47205e06042a6aa">parseDirectiveIrp</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIrp ::= .irp symbol,values <a href="#a54bac06b53c01858f47205e06042a6aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbee8f14c04b792d9d09bc360c900c93">parseDirectiveIrpc</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIrpc ::= .irpc symbol,values <a href="#adbee8f14c04b792d9d09bc360c900c93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac40728d0704ebda01857b48cf03573f0">parseDirectiveEndr</a> (SMLoc DirectiveLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a1ed829401bc36221800de4886fe3d">parseDirectiveMSEmit</a> (SMLoc DirectiveLoc, ParseStatementInfo &amp;Info, size_t Len)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32dd51b666f1141190f91427b03b81f">parseDirectiveMSAlign</a> (SMLoc DirectiveLoc, ParseStatementInfo &amp;Info)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a716ac7a9569174af267208e3dbee63e8">parseDirectiveEnd</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEnd ::= .end <a href="#a716ac7a9569174af267208e3dbee63e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df4da36647ecd1f47cc9731e7b6d914">parseDirectiveError</a> (SMLoc DirectiveLoc, bool WithMessage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveError ::= .err ::= .error [string] <a href="#a2df4da36647ecd1f47cc9731e7b6d914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99313ccd7ba92c6d14e6ad8731e419aa">parseDirectiveWarning</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveWarning ::= .warning [string] <a href="#a99313ccd7ba92c6d14e6ad8731e419aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b0180cab11041e3524cefb3c0921a0">parseDirectivePrint</a> (SMLoc DirectiveLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe882fae8feb54f0c5fa6b12266eacd8">parseDirectivePseudoProbe</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe82e3f106d4bd4e99d73399b7849e6f">parseDirectiveLTODiscard</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveLTODiscard ::= ".lto_discard" [ identifier ( , identifier )* ] The LTO library emits this directive to discard non-prevailing symbols. <a href="#afe82e3f106d4bd4e99d73399b7849e6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad83158f1697319c10231d0d8ad959266">parseDirectiveAddrsig</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae2a2344e38f377639d7d364ced086f">parseDirectiveAddrsigSym</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ea41a1a200ef098cf9440a53a1c434d">initializeDirectiveKindMap</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b371c6d68d602f6b2de4fa04cd736d0">initializeCVDefRangeTypeMap</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975aad462fee630e7001108d3c84ff35">DiagHandler</a> (const SMDiagnostic &amp;Diag, void *Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>will use the last parsed cpp hash line filename comment for the Filename and LineNo if any in the diagnostic. <a href="#a975aad462fee630e7001108d3c84ff35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The concrete assembly parser instance.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AsmParser() {#a66d1a7fb69c6ee8e272ede2e29448a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmParser::AsmParser (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, unsigned CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afad5b9aac74030a159903f3cf64c481c">llvm::MCAsmParser::HadError</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#ab037ee439331dc5b5a03626ada94cc7f">AsmParser</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/hlasmasmparser/#a123082543e8e0043abcbb49a723e78fa">anonymous{AsmParser.cpp}::HLASMAsmParser::HLASMAsmParser</a> and <a href="#a52700f1434ad3c2b676029a89630e526">operator=</a>.</p>

</div>
</div>

### AsmParser() {#ab037ee439331dc5b5a03626ada94cc7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AsmParser.cpp}::AsmParser::AsmParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser">AsmParser</a> &amp;)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Reference <a href="#a66d1a7fb69c6ee8e272ede2e29448a50">AsmParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AsmParser() {#a47ed0042b8e6c36abcf883ba9efb975d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmParser::~AsmParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afad5b9aac74030a159903f3cf64c481c">llvm::MCAsmParser::HadError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a52700f1434ad3c2b676029a89630e526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmParser &amp; anonymous{AsmParser.cpp}::AsmParser::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser">AsmParser</a> &amp;)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="#a66d1a7fb69c6ee8e272ede2e29448a50">AsmParser</a> and <a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">Run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAliasForDirective() {#a9b3a355413b120f5a101863780e3c44a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmParser.cpp}::AsmParser::addAliasForDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Alias)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#abb1344e353958db14e66ec7ab574001a">llvm::StringRef::lower</a>.</p>

</div>
</div>

### addDirectiveHandler() {#ac4abe3da9de4f2f7293fec78bebf6e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmParser.cpp}::AsmParser::addDirectiveHandler (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a9ce3532c090e7b66928ff9a42dae508c">ExtensionDirectiveHandler</a> Handler)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### Run() {#a1f9777a39f525bf9f8a85ce9d52cccd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::Run (bool NoInitialTextSection, bool NoFinalize=false)</td>
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

<p>Run the parser on the input source buffer.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a589edc5876425761e8515d0d03ba9576">llvm::MCContext::addGenDwarfSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="#a1a464d658f065637fc039e0645a94d87">eatToEndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86ef367bc55c7f607d673a9dd38189b3">llvm::MCTargetAsmParser::flushPendingInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="#a054e4ac93e14d4f4c594f1b58a7c8e0a">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a>, <a href="#a33ddf50b4cf84a930050c2e3affa6190">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a844102db6a944e0b900e1dcb331cd8ba">llvm::MCContext::getMCDwarfLineTables</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="#a3af0d74b30ef9c0a4e4d1c07300c26d6">getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afad5b9aac74030a159903f3cf64c481c">llvm::MCAsmParser::HadError</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a16be3cf71194a82a5cf1d124ebbdc433">llvm::MCContext::hadError</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a4947313871f8935468ae02f6621260c8">llvm::MCAsmParser::hasPendingError</a>, <a href="/web-llvm/docs/api/classes/llvm/asmcond/#ab86a4572bd9b87223e026101d390cb46">llvm::AsmCond::Ignore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2899e74730516967f04d81966bb4f881">llvm::MCSymbol::isDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a44a59dce1747781c994608fbeffd37c9">llvm::MCTargetAsmParser::onBeginOfFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a93d0e54ca0dae7b1e034284b33df3288">llvm::MCTargetAsmParser::onEndOfFile</a>, <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>, <a href="#a307a44ebfb83c5c16d6a0af1861547c1">printError</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a25158c234ca9e60f3976a36d7d6ef271">llvm::MCAsmParser::printPendingErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a61ee519481ec9d6b36a55212e44a34e6">llvm::MCSection::setBeginSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/asmcond/#ab5ad0559afdf12eaa55b0e4f3165d08b">llvm::AsmCond::TheCond</a>.</p>


<p>Referenced by <a href="#a52700f1434ad3c2b676029a89630e526">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### enabledGenDwarfForAssembly() {#abfdbd82da864ad373a4e42c0ed3b2230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::enabledGenDwarfForAssembly ()</td>
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

<p>Should we emit DWARF describing this assembler source?</p>


<p>(Returns false if the source has .file directives, which means we don't want to generate info describing the assembler source itself.)</p>


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile/#a07c9bf0537b9f094eb0b52b12116ecc6">llvm::MCDwarfFile::Checksum</a>, <a href="#a054e4ac93e14d4f4c594f1b58a7c8e0a">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a62f7e21c9dac9e7acb4fdd713e712d20">llvm::MCContext::getMCDwarfLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a65fb41d3f061e9004436525117bf6f8b">llvm::MCDwarfLineTable::getRootFile</a>, <a href="#a3af0d74b30ef9c0a4e4d1c07300c26d6">getStreamer</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile/#a14ad1cb6e8857b9f234f15e73434f508">llvm::MCDwarfFile::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#acfed6f3916764b6062de06e25e4a6603">llvm::MCContext::setGenDwarfFileNumber</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile/#a26f94642740ae0843e6043d876bdd740">llvm::MCDwarfFile::Source</a>.</p>


<p>Referenced by <a href="#afaaaf7da6379fe3994da86bf71024ddc">parseAndMatchAndEmitTargetInstruction</a> and <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>.</p>

</div>
</div>

### parseAndMatchAndEmitTargetInstruction() {#afaaaf7da6379fe3994da86bf71024ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseAndMatchAndEmitTargetInstruction (<a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> ID, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc)</td>
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

<p>This routine uses the target specific ParseInstruction function to parse an instruction into Operands, and then call the target specific MatchAndEmit function to match and emit the instruction.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#a377ba69923635f8154cad5784be89ff6">DWARF2_FLAG_IS_STMT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#abc3534e4318dd6126f55a94635209c93">DWARF2_LINE_DEFAULT_IS_STMT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4a16115d4363f1c16af9cfcb425ce0d5">llvm::MCStreamer::emitDwarfFileDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a43c1c961a6b54da9fccacdf1cf5fc38f">llvm::MCStreamer::emitDwarfLocDirective</a>, <a href="#abfdbd82da864ad373a4e42c0ed3b2230">enabledGenDwarfForAssembly</a>, <a href="#a054e4ac93e14d4f4c594f1b58a7c8e0a">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a6e4af5e4d650f5bec85b99dfe0fc4d04">llvm::MCAsmParser::getShowParsedOperands</a>, <a href="#a3af0d74b30ef9c0a4e4d1c07300c26d6">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a4947313871f8935468ae02f6621260c8">llvm::MCAsmParser::hasPendingError</a>, <a href="#aaca8544a6b02c09c6fadee9c549fd0ec">isParsingMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#abb1344e353958db14e66ec7ab574001a">llvm::StringRef::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a058facd817d442129355ef40eb9a1140">llvm::MCTargetAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#acfed6f3916764b6062de06e25e4a6603">llvm::MCContext::setGenDwarfFileNumber</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>


<p>Referenced by <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>.</p>

</div>
</div>

### parseStatement() {#a034b546ea133319ab2244f9bfa28ecae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseStatement (<a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/mcasmparsersemacallback">MCAsmParserSemaCallback</a> * SI)</td>
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

<p>ParseStatement: ::= EndOfStatement ::= Label* <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> ...Operands... EndOfStatement ::= Label* Identifier OperandList* EndOfStatement.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda0364c4ccb95b97b3cfe1a1c9a3014173">llvm::AOK_EVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda15b8af91c21aac1a862c9e92e8c2cbfb">llvm::AOK_Label</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a252ed0bb8924351d3e4a6a6cd6dd938f">checkForValidSection</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="#abfd6ef18b9ebd50358b7d4c3ddfa2f9e">discardLTOSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa40a8eedcddfcb1d10768fe2021bfa91">llvm::MCTargetAsmParser::doBeforeLabelEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae95926c6ea560f4332395213cc7519e9">llvm::AsmToken::Dot</a>, <a href="#a1a464d658f065637fc039e0645a94d87">eatToEndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#abfdbd82da864ad373a4e42c0ed3b2230">enabledGenDwarfForAssembly</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aaf27951b9eea060afd2ae6a01e8a8e0e">llvm::AsmToken::Equal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86ef367bc55c7f607d673a9dd38189b3">llvm::MCTargetAsmParser::flushPendingInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac0385a239e90b266f49755f28c5e3c9b">llvm::MCAsmInfo::getAlignmentIsInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="#a054e4ac93e14d4f4c594f1b58a7c8e0a">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a270e1171db01008f862ffbc34f8476fc">llvm::AsmToken::getIntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="#aeeeb1b807d25ed0a194d15135330796f">getSourceManager</a>, <a href="#a3af0d74b30ef9c0a4e4d1c07300c26d6">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a3168618a19701d0fb78aefb4d4e664de">llvm::AsmToken::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8008076fe2821cf033daf56965fd748b">llvm::AsmToken::Hash</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a5ed906a629ca3518e4b230146dff4c7a">llvm::AsmToken::HashDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a4947313871f8935468ae02f6621260c8">llvm::MCAsmParser::hasPendingError</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ada159ab0506b0f377aaa17516506f65a">llvm::MCSymbol::isExternal</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a01a3be3f469c6f0a26bf9a5180b7b322">llvm::ParseStatus::isFailure</a>, <a href="#aaca8544a6b02c09c6fadee9c549fd0ec">isParsingMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a940bbb142e7bb0990d40889426def99c">llvm::AsmToken::LCurly</a>, <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#abb1344e353958db14e66ec7ab574001a">llvm::StringRef::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry/#a741d0c6e829f284182bd9bbef0362e2d">llvm::MCGenDwarfLabelEntry::Make</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ab79bc663bb12acbf83bd10cdcfdd037e">llvm::MCSA_Cold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa1e94c23156e37812e4d6e078af1d728">llvm::MCSA_Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a6f8590ba0f71b1b8b0e937695e303208">llvm::MCSA_LazyReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a17067e9f600d7ededa1cd3a6f236d5a7">llvm::MCSA_Memtag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243afb34d5700d536c3f8f8a5004985d1f57">llvm::MCSA_NoDeadStrip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a39ad38d82f889bf4c82e539beb859d05">llvm::MCSA_PrivateExtern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a80891606fbdc946b4085496f58aafd62">llvm::MCSA_Reference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83196df34bcdda178fae802a4a06a6dc">llvm::MCSA_SymbolResolver</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a0506d51c6914f1b55fec60c97d4d8cc9">llvm::MCSA_WeakDefAutoPrivate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a9cd0febd9a535eb96c33815707bab481">llvm::MCSA_WeakDefinition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a42ec27e2fd185b27d0fbf1aaf0bfd214">llvm::MCSA_WeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a0534c8b9bfd14060aacc472e8d64ebd4">llvm::MCTargetAsmParser::onLabelParsed</a>, <a href="#afaaaf7da6379fe3994da86bf71024ddc">parseAndMatchAndEmitTargetInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a0478394229fb5470e1489709c8711643">llvm::MCTargetAsmParser::parseDirective</a>, <a href="#aa91d3c1b093e3561b948794724961f4b">parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a5530d71c3414b44f2205d3a3b3026d82">llvm::MCAsmParser::parseStringToEndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a3847b0adce89a393ecf0b359d8ff8646">llvm::AsmToken::RCurly</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1ff20331fe667c9bf3a49cc28516155e">llvm::AsmToken::Space</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a871b85a46f471e616995b722df807211">llvm::AsmToken::Star</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#aca3b32b0f673fcda41b604540f49a4f9">llvm::MCAsmParser::TokError</a>.</p>


<p>Referenced by <a href="#a6779c29e343b8e71d97734686a3eabd2">parseMSInlineAsm</a> and <a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">Run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ActiveMacros {#ac5cd24b539bb880e941a1794482e815a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MacroInstantiation*&gt; anonymous{AsmParser.cpp}::AsmParser::ActiveMacros</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stack of active macro instantiations.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### AltMacroMode {#afde08bfa9aa81411b204fbea9e73bffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmParser.cpp}::AsmParser::AltMacroMode = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### AssemblerDialect {#a6f4b506d0c4c6c99b2e969ff366ee30f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AsmParser.cpp}::AsmParser::AssemblerDialect = ~0U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AssemblerDialect. ~OU means unset value and use value provided by MAI.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### CFIStartProcLoc {#aec8ccc73a96b1a571880e0add4d204aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;SMLoc&gt; anonymous{AsmParser.cpp}::AsmParser::CFIStartProcLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### CppHashInfo {#a6e9df8ad225acfabf969e380d4c352cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CppHashInfoTy anonymous{AsmParser.cpp}::AsmParser::CppHashInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### Ctx {#ad5980113b36fe57c60cb729d8987ffb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; anonymous{AsmParser.cpp}::AsmParser::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### CurBuffer {#aeb36083ed0bc97755173a4155daacb44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AsmParser.cpp}::AsmParser::CurBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the current buffer index we're lexing from as managed by the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> object.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### DirLabels {#a70068f55a290367b773ba215ad0092b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::tuple&lt;SMLoc, CppHashInfoTy, MCSymbol *&gt;, 4&gt; anonymous{AsmParser.cpp}::AsmParser::DirLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of forward directional labels for diagnosis at the end.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### ExtensionDirectiveMap {#a65fc7cfe2af91012f038f58cb9fec3a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;ExtensionDirectiveHandler&gt; anonymous{AsmParser.cpp}::AsmParser::ExtensionDirectiveMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>maps directive names to handler methods in parser extensions.</p>


<p>Extensions register themselves in this map by calling addDirectiveHandler.</p>


<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### HadCppHashFilename {#afdebdc851185cf639050a820185bef80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmParser.cpp}::AsmParser::HadCppHashFilename = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Have we seen any file line comment.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### IsDarwin {#a95f703fa0050256c4589e49ae5ab6545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmParser.cpp}::AsmParser::IsDarwin = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>is Darwin compatibility enabled?</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### Lexer {#a38c1c92d783d95b33bdede842ee01148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmLexer anonymous{AsmParser.cpp}::AsmParser::Lexer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### LTODiscardSymbols {#a73501b5e5d2e2f570d3c1f8917e73418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;StringRef, 2&gt; anonymous{AsmParser.cpp}::AsmParser::LTODiscardSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### MacroLikeBodies {#a7dc0f3599fe175f964d6e01bf62284ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;MCAsmMacro&gt; anonymous{AsmParser.cpp}::AsmParser::MacroLikeBodies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of bodies of anonymous macros.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### MacrosEnabledFlag {#a9af3c6ee49f8b4055af6300c913fdf13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AsmParser.cpp}::AsmParser::MacrosEnabledFlag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> tracking whether macro substitution is enabled.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### MAI {#a72e4fa8972015729a4c21cad5506708b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo&amp; anonymous{AsmParser.cpp}::AsmParser::MAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### NumOfMacroInstantiations {#a48f60e19b7dc5b4f176bb4d6c2226f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AsmParser.cpp}::AsmParser::NumOfMacroInstantiations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of how many .macro's have been instantiated.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### Out {#afc92beaaef3e326b21b008b49faa6732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer&amp; anonymous{AsmParser.cpp}::AsmParser::Out</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### ParsingMSInlineAsm {#a430bb91a030761c6a2e6b5c6f95ebca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmParser.cpp}::AsmParser::ParsingMSInlineAsm = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Are we parsing ms-style inline assembly?</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### PlatformParser {#a0c7d2f4a235c08dfc2393cf7b2a43b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCAsmParserExtension&gt; anonymous{AsmParser.cpp}::AsmParser::PlatformParser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### ReportedInconsistentMD5 {#ab079468ed8e2225653583323822ab1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmParser.cpp}::AsmParser::ReportedInconsistentMD5 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Did we already inform the user about inconsistent <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> usage?</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### SavedDiagContext {#ae6cd807d4fafcef1df97e56f6b1e4e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* anonymous{AsmParser.cpp}::AsmParser::SavedDiagContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### SavedDiagHandler {#a5d0e1bbc98b27af9a70270c4941c462f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr::DiagHandlerTy anonymous{AsmParser.cpp}::AsmParser::SavedDiagHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### SrcMgr {#af6b4499584c3db46e263719ee1ea0417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr&amp; anonymous{AsmParser.cpp}::AsmParser::SrcMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### StartTokLoc {#a1435a18a3fb9665b2ac299753961717c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{AsmParser.cpp}::AsmParser::StartTokLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### TheCondStack {#afa84f8597aad6eb28a8ff6e67d385925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AsmCond&gt; anonymous{AsmParser.cpp}::AsmParser::TheCondStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### TheCondState {#a37ab15e76eb3d7894202fdfd7a2f3340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmCond anonymous{AsmParser.cpp}::AsmParser::TheCondState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## MCAsmParser Interface



<p>{</p>


### applyModifierToExpr {#a81a81c9a201f832df3372f7df9f07ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * AsmParser::applyModifierToExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a> Variant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### areMacrosEnabled {#aac7be96c8ee178a08cd86bbca2948431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmParser.cpp}::AsmParser::areMacrosEnabled ()</td>
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

<p>Are macros enabled in the parser?</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### AssignmentKind {#a1bbf8ed2a7170a885f4f5162736abc0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{AsmParser.cpp}::AsmParser::AssignmentKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Set<a id="a1bbf8ed2a7170a885f4f5162736abc0ca5d5b78699e57104f2fa03bbdf7b9197b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Equiv<a id="a1bbf8ed2a7170a885f4f5162736abc0ca405b480b56dd17b4829251e904d51417"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Equal<a id="a1bbf8ed2a7170a885f4f5162736abc0caf5f286e73bda105e538310b3190f75c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTOSetConditional<a id="a1bbf8ed2a7170a885f4f5162736abc0ca02e403338b70a2a83a2981a15d4ba0cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### checkForBadMacro {#aa83fee714b61cad4771b4b6c6fefacea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::checkForBadMacro (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Body, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcasmmacroparameter">MCAsmMacroParameter</a> &gt; Parameters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>checkForBadMacro</p>


<p>With the support added for named parameters there may be code out there that is transitioning from positional parameters. In versions of gas that did not support named parameters they would be ignored on the macro definition. But to support both styles of parameters this is not possible so if a macro definition has named parameters but does not use them and has what appears to be positional parameters, strings like $1, $2, ... and $n, then issue a warning that the positional parameter found in body which have no effect. Hoping the developer will either remove the named parameters from the macro definition so the positional parameters get used if that was what was intended or change the macro to use the named parameters. It is possible this warning will trigger when the none of the named parameters are used and the strings like $1 are infact to simply to be passed trough unchanged.</p>


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### checkForValidSection {#a252ed0bb8924351d3e4a6a6cd6dd938f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::checkForValidSection ()</td>
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

<p>Ensure that we have a valid section set in the streamer.</p>


<p>Otherwise, report an error and switch to .text.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a3af0d74b30ef9c0a4e4d1c07300c26d6">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>.</p>


<p>Referenced by <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>.</p>

</div>
</div>

### CVDefRangeType {#a8960eaf69d8b105ba62fab667264622b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AsmParser.cpp}::AsmParser::CVDefRangeType </td>
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
<td class="doxyEnumItemName">CVDR_DEFRANGE<a id="a8960eaf69d8b105ba62fab667264622ba9fa544941e1c5e60155be4729b122e96"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVDR_DEFRANGE_REGISTER<a id="a8960eaf69d8b105ba62fab667264622ba4004d197384d7cfdb0a8122bbe5ddaa8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVDR_DEFRANGE_FRAMEPOINTER_REL<a id="a8960eaf69d8b105ba62fab667264622ba8e33b7ac62e5e58367b51e6dcca8998d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVDR_DEFRANGE_SUBFIELD_REGISTER<a id="a8960eaf69d8b105ba62fab667264622bab189e68bee25d035c51f1e6c4802c8e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVDR_DEFRANGE_REGISTER_REL<a id="a8960eaf69d8b105ba62fab667264622ba102ba8e36bec527a0068eedfa51f4422"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### CVDefRangeTypeMap {#aeda338b84c3a92845277019323a4f517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;CVDefRangeType&gt; anonymous{AsmParser.cpp}::AsmParser::CVDefRangeTypeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps Codeview def_range types --&gt; CVDefRangeType enum, for Codeview def_range types parsed by this class.</p>

<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### DiagHandler {#a975aad462fee630e7001108d3c84ff35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::DiagHandler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Diag, void * Context)</td>
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

<p>will use the last parsed cpp hash line filename comment for the Filename and LineNo if any in the diagnostic.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### DirectiveKind {#a922449c7444d6a657e8ffd7b7ad88879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AsmParser.cpp}::AsmParser::DirectiveKind </td>
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
<td class="doxyEnumItemName">DK_NO_DIRECTIVE<a id="a922449c7444d6a657e8ffd7b7ad88879aa8de00ac2fe4efdba8f04a125719edac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SET<a id="a922449c7444d6a657e8ffd7b7ad88879a53560aa5706ff9f729919c26c8df3306"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_EQU<a id="a922449c7444d6a657e8ffd7b7ad88879af48ce9929d09e2007b3c216480c5be78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_EQUIV<a id="a922449c7444d6a657e8ffd7b7ad88879af76e15fbfbe36307e303d07c826b54e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ASCII<a id="a922449c7444d6a657e8ffd7b7ad88879aa0b99264f90a4db5f89003d520a8e28a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ASCIZ<a id="a922449c7444d6a657e8ffd7b7ad88879a2dcb7cbc10fa2ff470a6f53b7c7633e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_STRING<a id="a922449c7444d6a657e8ffd7b7ad88879ad7736c896d7e7839eb2eb9a236358e21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_BYTE<a id="a922449c7444d6a657e8ffd7b7ad88879a430c63904e36ff8e8e7a18840678d47c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SHORT<a id="a922449c7444d6a657e8ffd7b7ad88879a91115474031e9c3a8b0e3bc94beda0f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_RELOC<a id="a922449c7444d6a657e8ffd7b7ad88879ae61e201a8fdc4418d8535a2d46b89d99"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_VALUE<a id="a922449c7444d6a657e8ffd7b7ad88879a8c7058549b4afa107f6b090dcf77ccfc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_2BYTE<a id="a922449c7444d6a657e8ffd7b7ad88879a55cbb2833d849e4e5e3c87036febd0e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LONG<a id="a922449c7444d6a657e8ffd7b7ad88879a6a7e6a2d013b966b2fe5ec1363a90ea3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_INT<a id="a922449c7444d6a657e8ffd7b7ad88879a1ac78dd53edb7f53853e6d1e03dfb679"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_4BYTE<a id="a922449c7444d6a657e8ffd7b7ad88879af98f6df403468cff70e15c56f77b0697"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_QUAD<a id="a922449c7444d6a657e8ffd7b7ad88879a68e4ab8a2f8b484ff956222de8223b63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_8BYTE<a id="a922449c7444d6a657e8ffd7b7ad88879a95351bee16600bd8bec6c80dfa7c9a3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_OCTA<a id="a922449c7444d6a657e8ffd7b7ad88879af5d657c6732fb28096ca44fcfc956052"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DC<a id="a922449c7444d6a657e8ffd7b7ad88879a19dbff9226a60a22b68e703eba06ea72"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DC_A<a id="a922449c7444d6a657e8ffd7b7ad88879aaa044d39c26ed8796c673bb58dd66085"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DC_B<a id="a922449c7444d6a657e8ffd7b7ad88879ae2411e9a0c93db477a25f958637384b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DC_D<a id="a922449c7444d6a657e8ffd7b7ad88879a1e6f0e54dd56a5cefb20475764b0307c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DC_L<a id="a922449c7444d6a657e8ffd7b7ad88879a21e08b73d7385b74ee83307ff1a8f2f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DC_S<a id="a922449c7444d6a657e8ffd7b7ad88879abf17f5443d9a953378d31014c88fc1db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DC_W<a id="a922449c7444d6a657e8ffd7b7ad88879a54cf621431933f0af990b57cd9ce6d28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DC_X<a id="a922449c7444d6a657e8ffd7b7ad88879a2a5f6c31de5404978105652f8cf3cc40"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DCB<a id="a922449c7444d6a657e8ffd7b7ad88879a20810a99d2b8f3e95b8d8f59a03dc00a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DCB_B<a id="a922449c7444d6a657e8ffd7b7ad88879a671413e84daa52d11ee9c33437809ccc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DCB_D<a id="a922449c7444d6a657e8ffd7b7ad88879a262ec9f93c9e3f411c02ea7d658929ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DCB_L<a id="a922449c7444d6a657e8ffd7b7ad88879a5cfe102837e97fd86405aa694d90dbb3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DCB_S<a id="a922449c7444d6a657e8ffd7b7ad88879a48954d9bed72867c5a09d6c2d97b7cda"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DCB_W<a id="a922449c7444d6a657e8ffd7b7ad88879a95cb8bafc0e972a34abe71aa60f312d0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DCB_X<a id="a922449c7444d6a657e8ffd7b7ad88879a1b25e893e65496136c4baedc2eb28c83"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DS<a id="a922449c7444d6a657e8ffd7b7ad88879a2e1f5040381fe9ead252f2976e3bd519"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DS_B<a id="a922449c7444d6a657e8ffd7b7ad88879abc8547c8ffb846a86911455ec568c3c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DS_D<a id="a922449c7444d6a657e8ffd7b7ad88879aeabd27227540248b2b28ed42807d6c0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DS_L<a id="a922449c7444d6a657e8ffd7b7ad88879a258a9f415c57ce82ff92cd7e81a5a05e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DS_P<a id="a922449c7444d6a657e8ffd7b7ad88879a22e9677b5c83b7144475fb15964c2e64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DS_S<a id="a922449c7444d6a657e8ffd7b7ad88879adbce18a05d33ffb081a88b3bc496f0ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DS_W<a id="a922449c7444d6a657e8ffd7b7ad88879ae8da36464ef1fd30f8d8460f8d43edab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DS_X<a id="a922449c7444d6a657e8ffd7b7ad88879af3fd11269ec8500339fe55f677cf150a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SINGLE<a id="a922449c7444d6a657e8ffd7b7ad88879abff463d4fc0265f04f42f31a2372a8f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_FLOAT<a id="a922449c7444d6a657e8ffd7b7ad88879a5343757e58a2b20baa935bd11854e7f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DOUBLE<a id="a922449c7444d6a657e8ffd7b7ad88879ac9dc892c6676c98c8ac0700fe2be8700"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ALIGN<a id="a922449c7444d6a657e8ffd7b7ad88879a7bfb79fb004514ebc1f257624f7ad59b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ALIGN32<a id="a922449c7444d6a657e8ffd7b7ad88879a99cf63bc25e987b7f2d0fb77acb5f833"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_BALIGN<a id="a922449c7444d6a657e8ffd7b7ad88879a0369ab891e6f4c509d3143cc23f38fcf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_BALIGNW<a id="a922449c7444d6a657e8ffd7b7ad88879a0f6cf7babd798230696e0598732771f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_BALIGNL<a id="a922449c7444d6a657e8ffd7b7ad88879aa4c21f49734fe91de6f4af53d506c42d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_P2ALIGN<a id="a922449c7444d6a657e8ffd7b7ad88879a4debccf08cc4ddb071563bbc85459e63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_P2ALIGNW<a id="a922449c7444d6a657e8ffd7b7ad88879a291cd4b8d1471a675739311d08e71e64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_P2ALIGNL<a id="a922449c7444d6a657e8ffd7b7ad88879a2e110990958c4862faeef1a1d35b1ece"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ORG<a id="a922449c7444d6a657e8ffd7b7ad88879a5f4f7f800db1ccc3963854962a972259"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_FILL<a id="a922449c7444d6a657e8ffd7b7ad88879a0769ba9b9f77c53b4743649eb72f7b32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ENDR<a id="a922449c7444d6a657e8ffd7b7ad88879a67a6cc0b4cd4e388b1e6dac17386a770"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_BUNDLE_ALIGN_MODE<a id="a922449c7444d6a657e8ffd7b7ad88879a7e34818112fef66612bdd4939cd0ed7b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_BUNDLE_LOCK<a id="a922449c7444d6a657e8ffd7b7ad88879a9a979b9e29a548cb85e064c3a707d1d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_BUNDLE_UNLOCK<a id="a922449c7444d6a657e8ffd7b7ad88879ab34645d1c664cc82127ab5d4a484047d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ZERO<a id="a922449c7444d6a657e8ffd7b7ad88879a4612295f2528022dd42d44612ad14300"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_EXTERN<a id="a922449c7444d6a657e8ffd7b7ad88879a2cb3900200571026f77038ebc17b9164"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_GLOBL<a id="a922449c7444d6a657e8ffd7b7ad88879a96d7975206d0455cedc06f8ee0729e57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_GLOBAL<a id="a922449c7444d6a657e8ffd7b7ad88879ae58bb63456f370951b468d9a4c60b034"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LAZY_REFERENCE<a id="a922449c7444d6a657e8ffd7b7ad88879a5a2856b8d84bbd3bce48463e1d2675fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_NO_DEAD_STRIP<a id="a922449c7444d6a657e8ffd7b7ad88879a192a225311f576860f8e72d46610ffd3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SYMBOL_RESOLVER<a id="a922449c7444d6a657e8ffd7b7ad88879aaf92a6241bb460f894f3211a5960e142"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_PRIVATE_EXTERN<a id="a922449c7444d6a657e8ffd7b7ad88879a35858cd510ab7bd7ba043e59fb23d4ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_REFERENCE<a id="a922449c7444d6a657e8ffd7b7ad88879a24a145b8b70e8b3719ab6bef33c4b880"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_WEAK_DEFINITION<a id="a922449c7444d6a657e8ffd7b7ad88879a4250d17936cbf360cf5617b3d871a862"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_WEAK_REFERENCE<a id="a922449c7444d6a657e8ffd7b7ad88879ad97c8b6077b4e17b1a2839de32b7db48"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_WEAK_DEF_CAN_BE_HIDDEN<a id="a922449c7444d6a657e8ffd7b7ad88879aa9798656c5ee94e62bf72df89ef785f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_COLD<a id="a922449c7444d6a657e8ffd7b7ad88879a4a965d4cc1a0413eb9b1cfe357810071"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_COMM<a id="a922449c7444d6a657e8ffd7b7ad88879a953ffc1d16a8adc05b160c89fe8b0189"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_COMMON<a id="a922449c7444d6a657e8ffd7b7ad88879a30cadf35fd38e80bb193ed3d7f10b404"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LCOMM<a id="a922449c7444d6a657e8ffd7b7ad88879aab32d2c909b411c4746ed34907b3648a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ABORT<a id="a922449c7444d6a657e8ffd7b7ad88879a2901b05191644f80e87b5d5134018b24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_INCLUDE<a id="a922449c7444d6a657e8ffd7b7ad88879a7d9ab9e03d800d4e5521be174cc894fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_INCBIN<a id="a922449c7444d6a657e8ffd7b7ad88879a80718ec63e16092bb6b88838942a144b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CODE16<a id="a922449c7444d6a657e8ffd7b7ad88879aab935909a086864a8327919f91a918c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CODE16GCC<a id="a922449c7444d6a657e8ffd7b7ad88879a7aa118b80c83138db4c3743c36ea5acb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_REPT<a id="a922449c7444d6a657e8ffd7b7ad88879ade623436ed5a4211b2d4905f4d6e29b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IRP<a id="a922449c7444d6a657e8ffd7b7ad88879afa154c7f60567c9bf487daa84ba51e12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IRPC<a id="a922449c7444d6a657e8ffd7b7ad88879a40c46e91059d8cfc8fc2de7465dabd53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IF<a id="a922449c7444d6a657e8ffd7b7ad88879a641c52d698ed578fb4aea259a96751b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFEQ<a id="a922449c7444d6a657e8ffd7b7ad88879a0fd4eea56bb966cb3aef32c353851322"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFGE<a id="a922449c7444d6a657e8ffd7b7ad88879ab01e1573fba1fbfc4a25025f5eb4c8a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFGT<a id="a922449c7444d6a657e8ffd7b7ad88879a97c9fa4d9bae54301d264c0d42496ea3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFLE<a id="a922449c7444d6a657e8ffd7b7ad88879ad2d1627804846cdd4dfcb50b50b789c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFLT<a id="a922449c7444d6a657e8ffd7b7ad88879acffc6abce6bdd16bafaaea3d7583f2e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFNE<a id="a922449c7444d6a657e8ffd7b7ad88879a9ecf160cb7ce41da88cfce24b33a55ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFB<a id="a922449c7444d6a657e8ffd7b7ad88879a601a08d392e70d3882472596e666de99"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFNB<a id="a922449c7444d6a657e8ffd7b7ad88879ab301f8fa5ab5523a18d8c247d9474dbf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFC<a id="a922449c7444d6a657e8ffd7b7ad88879ae8c989f997e1a9183064785192fcb514"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFEQS<a id="a922449c7444d6a657e8ffd7b7ad88879ad8432845e0ba2680d53fccc93bb9ee91"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFNC<a id="a922449c7444d6a657e8ffd7b7ad88879aec546ba7d524bbd09c8a326713e453e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFNES<a id="a922449c7444d6a657e8ffd7b7ad88879a73bee9b8de17cbf07c0a3a0cd7be96a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFDEF<a id="a922449c7444d6a657e8ffd7b7ad88879a17a196b403468af5aa394092d87b09f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFNDEF<a id="a922449c7444d6a657e8ffd7b7ad88879a91319e546b91bcb5bd0a0c3023c31153"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFNOTDEF<a id="a922449c7444d6a657e8ffd7b7ad88879a1502eec82040d925c254ff41c4bc7cc8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIF<a id="a922449c7444d6a657e8ffd7b7ad88879ac180cacafb98b2e5dfdf82d0f084931b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSE<a id="a922449c7444d6a657e8ffd7b7ad88879a4918c3bb7e90b66807bd7f4c2a786255"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ENDIF<a id="a922449c7444d6a657e8ffd7b7ad88879ad0bc24238992b0d074ebf0dea8e042c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SPACE<a id="a922449c7444d6a657e8ffd7b7ad88879a98a752617bf56710448a0e9877181dce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SKIP<a id="a922449c7444d6a657e8ffd7b7ad88879ac4d12b2498f5c19720cb3b4fe81b41e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_FILE<a id="a922449c7444d6a657e8ffd7b7ad88879ac6b7998fa9b24768ba8a05606ae3b9d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LINE<a id="a922449c7444d6a657e8ffd7b7ad88879a591aa53b33d052338bc90ce50c231686"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LOC<a id="a922449c7444d6a657e8ffd7b7ad88879ac1bdcb04b316ea0179a986bca5796212"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LOC_LABEL<a id="a922449c7444d6a657e8ffd7b7ad88879a4ece5cd0bf87f88514818e232e26067e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_STABS<a id="a922449c7444d6a657e8ffd7b7ad88879a05e2315455aec4c39656eb0e0feb5ecc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FILE<a id="a922449c7444d6a657e8ffd7b7ad88879ac84f7442f5d819f649c1ec14c1cd98e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FUNC_ID<a id="a922449c7444d6a657e8ffd7b7ad88879ab280a72413586aa6bf05de827cb9f434"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_INLINE_SITE_ID<a id="a922449c7444d6a657e8ffd7b7ad88879a95114f18e0d1bf3efce09a6fe2f31523"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_LOC<a id="a922449c7444d6a657e8ffd7b7ad88879a05681b4b094460c1e3fb8fec6159553e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_LINETABLE<a id="a922449c7444d6a657e8ffd7b7ad88879ad20fe6188a9207cf7a93bbd908bbfa11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_INLINE_LINETABLE<a id="a922449c7444d6a657e8ffd7b7ad88879aa181be47e6a549f156cb7fe0915669fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_DEF_RANGE<a id="a922449c7444d6a657e8ffd7b7ad88879ab63627cd6460247b192d2a9dda72cdea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_STRINGTABLE<a id="a922449c7444d6a657e8ffd7b7ad88879a95ff4ae1e8b0cfc340179371061c2503"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_STRING<a id="a922449c7444d6a657e8ffd7b7ad88879a8d91fc91a8456e70be9dd323c56cc7bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FILECHECKSUMS<a id="a922449c7444d6a657e8ffd7b7ad88879a2637cf017c6119e13c951496df6d43da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FILECHECKSUM_OFFSET<a id="a922449c7444d6a657e8ffd7b7ad88879a7c4c0e2e61e93364ee623f2719f1c80d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FPO_DATA<a id="a922449c7444d6a657e8ffd7b7ad88879ab53e1e7ee39057f239e1957204858369"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_SECTIONS<a id="a922449c7444d6a657e8ffd7b7ad88879a48fc9537914fd1a67f54ad62ec844d32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_STARTPROC<a id="a922449c7444d6a657e8ffd7b7ad88879a7b9091330561d161e60bc0b47d74cd78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_ENDPROC<a id="a922449c7444d6a657e8ffd7b7ad88879a73b4ad8ed1fe70e8f2a802bd2c5abcd7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_DEF_CFA<a id="a922449c7444d6a657e8ffd7b7ad88879a6b22829ceb5ac50aebd50bc40f006bbb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_DEF_CFA_OFFSET<a id="a922449c7444d6a657e8ffd7b7ad88879a69dc0ff613e99fc2749f255b576be112"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_ADJUST_CFA_OFFSET<a id="a922449c7444d6a657e8ffd7b7ad88879ab1d4b5a684fe8a63e537426d097ddb1f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_DEF_CFA_REGISTER<a id="a922449c7444d6a657e8ffd7b7ad88879a07cad0bcede5ca1dc2b3392a240be0fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_LLVM_DEF_ASPACE_CFA<a id="a922449c7444d6a657e8ffd7b7ad88879adf6542a9d0e351d8e0d86af071ae2be7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_OFFSET<a id="a922449c7444d6a657e8ffd7b7ad88879a1922bd1af827cd5831bf506ced61ea90"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_REL_OFFSET<a id="a922449c7444d6a657e8ffd7b7ad88879adb73937fdde01931d41d949b6684211d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_PERSONALITY<a id="a922449c7444d6a657e8ffd7b7ad88879ab860a2cd5cdf6e88a28c03f58f30d137"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_LSDA<a id="a922449c7444d6a657e8ffd7b7ad88879aeb37191898c61d90e46d830a4ec245fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_REMEMBER_STATE<a id="a922449c7444d6a657e8ffd7b7ad88879aa4b71c8fc19c86e259b2891216de870e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_RESTORE_STATE<a id="a922449c7444d6a657e8ffd7b7ad88879a138c52bece9c23f73257e93d628f28ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_SAME_VALUE<a id="a922449c7444d6a657e8ffd7b7ad88879aeb16d0fd0f7ac1ec3a3a55725dd08132"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_RESTORE<a id="a922449c7444d6a657e8ffd7b7ad88879ac29b10472068c66c7614d5c153e881f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_ESCAPE<a id="a922449c7444d6a657e8ffd7b7ad88879aaa941237981627e55de1a29d6b126df3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_RETURN_COLUMN<a id="a922449c7444d6a657e8ffd7b7ad88879a8c98c4dbfcc0caae36dc5b479869256b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_SIGNAL_FRAME<a id="a922449c7444d6a657e8ffd7b7ad88879a47c523490268f789a3c654e4af2c4cdb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_UNDEFINED<a id="a922449c7444d6a657e8ffd7b7ad88879ac09d728be07486fd835f24b71fad5b6f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_REGISTER<a id="a922449c7444d6a657e8ffd7b7ad88879a974b37a5fc4ea073362e25373fc83e35"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_WINDOW_SAVE<a id="a922449c7444d6a657e8ffd7b7ad88879a3485e14f91a0ba7e88729a6f08f44ade"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_LABEL<a id="a922449c7444d6a657e8ffd7b7ad88879ae455df5cea0691744e78ee57c18ec9f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_B_KEY_FRAME<a id="a922449c7444d6a657e8ffd7b7ad88879ae436e1d03450f7116b201b9e12fdbbed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_VAL_OFFSET<a id="a922449c7444d6a657e8ffd7b7ad88879a5b71d5edf1e6b9757362414251edd7fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_MACROS_ON<a id="a922449c7444d6a657e8ffd7b7ad88879af516b4fb7e044f1e4af2c97231e2c81e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_MACROS_OFF<a id="a922449c7444d6a657e8ffd7b7ad88879a8d1ef621a5ec6a66abd2f4b3e99de87f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ALTMACRO<a id="a922449c7444d6a657e8ffd7b7ad88879a196a8b493ded9d2aad0b49b25caac355"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_NOALTMACRO<a id="a922449c7444d6a657e8ffd7b7ad88879abf45d58933bd8e1a017496ea249d3a78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_MACRO<a id="a922449c7444d6a657e8ffd7b7ad88879a4a647c287b58718e548ac0bfc9d452d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_EXITM<a id="a922449c7444d6a657e8ffd7b7ad88879a4e813dc50b274c00d5163997f37706a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ENDM<a id="a922449c7444d6a657e8ffd7b7ad88879a4a9797dfeb5a4f6ec008facd3ec2c64f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ENDMACRO<a id="a922449c7444d6a657e8ffd7b7ad88879abc22541b9c6273ff609183303b2e6143"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_PURGEM<a id="a922449c7444d6a657e8ffd7b7ad88879a6f307c0d29037cd9a7dde51d042297fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SLEB128<a id="a922449c7444d6a657e8ffd7b7ad88879a651bb8e4eb4e95c28aee6ca90e6ba911"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ULEB128<a id="a922449c7444d6a657e8ffd7b7ad88879a39217bd2f6146f93f90135b546410ac2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERR<a id="a922449c7444d6a657e8ffd7b7ad88879ad71e3371b46cd2f26571f0eeae0ae971"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERROR<a id="a922449c7444d6a657e8ffd7b7ad88879a671febc6b19a825238cb76719cc739df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_WARNING<a id="a922449c7444d6a657e8ffd7b7ad88879aa6ada4aaa2cac2c97ddd62516dcf506f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_PRINT<a id="a922449c7444d6a657e8ffd7b7ad88879a225d0be96f2b6fa720851f39b4813530"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ADDRSIG<a id="a922449c7444d6a657e8ffd7b7ad88879a7ec92753e9a5482f8f86dfb5d6c109b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ADDRSIG_SYM<a id="a922449c7444d6a657e8ffd7b7ad88879ace46b8fb40388a2458084e18e4d67e7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_PSEUDO_PROBE<a id="a922449c7444d6a657e8ffd7b7ad88879a6b88356fc0517b26fa5ab3faceb3ff15"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LTO_DISCARD<a id="a922449c7444d6a657e8ffd7b7ad88879a51f8602632e34995f5f6c0195cd46a44"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LTO_SET_CONDITIONAL<a id="a922449c7444d6a657e8ffd7b7ad88879a9d7c1deb6168c932bfe5383925d7fc76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_MTE_TAGGED_FRAME<a id="a922449c7444d6a657e8ffd7b7ad88879aaa6454602a0fa26bb834dbb067d7ffa5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_MEMTAG<a id="a922449c7444d6a657e8ffd7b7ad88879ac9950916ad7d07bf09a88b59d185c626"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_END<a id="a922449c7444d6a657e8ffd7b7ad88879a0dc76d306b4e85cee77862142a50d118"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### DirectiveKindMap {#aaeb6dff5b397561a040817ad73e0f744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;DirectiveKind&gt; anonymous{AsmParser.cpp}::AsmParser::DirectiveKindMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps directive name --&gt; DirectiveKind enum, for directives parsed by this class.</p>

<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### discardLTOSymbol {#abfd6ef18b9ebd50358b7d4c3ddfa2f9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmParser.cpp}::AsmParser::discardLTOSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>.</p>

</div>
</div>

### eatToEndOfStatement {#a1a464d658f065637fc039e0645a94d87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::eatToEndOfStatement ()</td>
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

<p>Throw away the rest of the line for testing purposes.</p>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>.</p>


<p>Referenced by <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/hlasmasmparser/#a7ab8a603879e4abd860791912451799c">anonymous{AsmParser.cpp}::HLASMAsmParser::parseStatement</a> and <a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">Run</a>.</p>

</div>
</div>

### enterIncludeFile {#adaf4b7c99bb6159d9eeb01cd68346952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::enterIncludeFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Filename)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enter the specified file. This returns true on failure.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### expandMacro {#a939c2b49e45af39faaf482f0752d89ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::expandMacro (<a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> &amp; Macro, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcasmmacroparameter">MCAsmMacroParameter</a> &gt; Parameters, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-asmparser-cpp-/#ac0478524b98a3f10477cb9006480f9e5">MCAsmMacroArgument</a> &gt; A, bool EnableAtPseudoVariable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### getAssemblerDialect {#a1f4126089fcd9bbd3b8721c69567f847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AsmParser.cpp}::AsmParser::getAssemblerDialect ()</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### getBinOpPrecedence {#a91b05b4557ece0c3856d8f8cdc3cf02b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AsmParser::getBinOpPrecedence (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629">MCBinaryExpr::Opcode</a> &amp; Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### getContext {#a054e4ac93e14d4f4c594f1b58a7c8e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext &amp; anonymous{AsmParser.cpp}::AsmParser::getContext ()</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#abfdbd82da864ad373a4e42c0ed3b2230">enabledGenDwarfForAssembly</a>, <a href="#afaaaf7da6379fe3994da86bf71024ddc">parseAndMatchAndEmitTargetInstruction</a>, <a href="#ac7fc5af218d2f17280c5b443dbe20838">parseExpression</a>, <a href="#a6779c29e343b8e71d97734686a3eabd2">parseMSInlineAsm</a>, <a href="#a02bbdeea1375089f06a52747e919b4dc">parsePrimaryExpr</a>, <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a> and <a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">Run</a>.</p>

</div>
</div>

### getCVContext {#a95abe1c2105d82b41baaa16d9a405be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewContext &amp; anonymous{AsmParser.cpp}::AsmParser::getCVContext ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### getLexer {#a33ddf50b4cf84a930050c2e3affa6190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmLexer &amp; anonymous{AsmParser.cpp}::AsmParser::getLexer ()</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/hlasmasmparser/#a123082543e8e0043abcbb49a723e78fa">anonymous{AsmParser.cpp}::HLASMAsmParser::HLASMAsmParser</a>, <a href="#aa91d3c1b093e3561b948794724961f4b">parseIdentifier</a>, <a href="#a6779c29e343b8e71d97734686a3eabd2">parseMSInlineAsm</a>, <a href="#a02bbdeea1375089f06a52747e919b4dc">parsePrimaryExpr</a>, <a href="#abdaa8ae9b3e01099946066f89a8e10ad">parseRealValue</a> and <a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">Run</a>.</p>

</div>
</div>

### getSourceManager {#aeeeb1b807d25ed0a194d15135330796f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr &amp; anonymous{AsmParser.cpp}::AsmParser::getSourceManager ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>.</p>

</div>
</div>

### getStreamer {#a3af0d74b30ef9c0a4e4d1c07300c26d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer &amp; anonymous{AsmParser.cpp}::AsmParser::getStreamer ()</td>
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

<p>Return the output streamer for the assembler.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a252ed0bb8924351d3e4a6a6cd6dd938f">checkForValidSection</a>, <a href="#abfdbd82da864ad373a4e42c0ed3b2230">enabledGenDwarfForAssembly</a>, <a href="#aec28069dca3f6f64e1e5e13477d62688">parseAbsoluteExpression</a>, <a href="#afaaaf7da6379fe3994da86bf71024ddc">parseAndMatchAndEmitTargetInstruction</a>, <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a> and <a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">Run</a>.</p>

</div>
</div>

### handleMacroEntry {#aa07796c3a7f0e6314119e7e6478a411f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::handleMacroEntry (<a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> * M, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle entry to macro instantiation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>The macro.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLoc</td>
<td class="doxyParamItemDescription"><p>Instantiation location.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### handleMacroExit {#a6b0c8eae34a387bfc736daff86361d56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::handleMacroExit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle exit from macro instantiation.</p>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### initializeCVDefRangeTypeMap {#a0b371c6d68d602f6b2de4fa04cd736d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::initializeCVDefRangeTypeMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### initializeDirectiveKindMap {#a7ea41a1a200ef098cf9440a53a1c434d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::initializeDirectiveKindMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### instantiateMacroLikeBody {#a1e3f1ee438bb4c31b48c16aa7e08a71f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::instantiateMacroLikeBody (<a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> * M, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### isInsideMacroInstantiation {#a6e662ae1a842470452847a0c671d78cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmParser.cpp}::AsmParser::isInsideMacroInstantiation ()</td>
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

<p>Are we inside a macro instantiation?</p>

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### isParsingMSInlineAsm {#aaca8544a6b02c09c6fadee9c549fd0ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmParser.cpp}::AsmParser::isParsingMSInlineAsm ()</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#afaaaf7da6379fe3994da86bf71024ddc">parseAndMatchAndEmitTargetInstruction</a> and <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>.</p>

</div>
</div>

### jumpToLoc {#ab945e73bf2bf14615ae16f4bd24b7856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::jumpToLoc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned InBuffer=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset the current lexer position to that given by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>.</p>


<p>The current token is not set; clients should ensure <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex()</a> is called subsequently.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InBuffer</td>
<td class="doxyParamItemDescription"><p>If not 0, should be the known buffer id that contains the location.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### Lex {#af3d4af20be9f94cbdad904d45cafbefa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AsmToken &amp; AsmParser::Lex ()</td>
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

<p>Get the next AsmToken in the stream, possibly handling file inclusion first.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0765774402d06b304b3f4bee2e6231ed">llvm::AsmToken::Comment</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a3168618a19701d0fb78aefb4d4e664de">llvm::AsmToken::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a710e72de4b87af42e7605679d1fb2c24">llvm::AsmToken::is</a> and <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a>.</p>


<p>Referenced by <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a>, <a href="#ac7fc5af218d2f17280c5b443dbe20838">parseExpression</a>, <a href="#aa91d3c1b093e3561b948794724961f4b">parseIdentifier</a>, <a href="#a6779c29e343b8e71d97734686a3eabd2">parseMSInlineAsm</a>, <a href="#a02bbdeea1375089f06a52747e919b4dc">parsePrimaryExpr</a>, <a href="#abdaa8ae9b3e01099946066f89a8e10ad">parseRealValue</a>, <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/hlasmasmparser/#a7ab8a603879e4abd860791912451799c">anonymous{AsmParser.cpp}::HLASMAsmParser::parseStatement</a> and <a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">Run</a>.</p>

</div>
</div>

### Note {#afd8b63a81cb9bf1891795b81d34b6972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::Note (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
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

<p>Emit a note at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a25158c234ca9e60f3976a36d7d6ef271">llvm::MCAsmParser::printPendingErrors</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### parseAbsoluteExpression {#aec28069dca3f6f64e1e5e13477d62688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseAbsoluteExpression (int64_t &amp; Res)</td>
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

<p>Parse an expression which must evaluate to an absolute value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The value of the absolute expression. The result is undefined on error.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a3af0d74b30ef9c0a4e4d1c07300c26d6">getStreamer</a> and <a href="#a8fc1050c60fea592a8902be95251705a">parseExpression</a>.</p>

</div>
</div>

### parseAngleBracketString {#a5347cc04614e8c6adca091ab5a919b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseAngleBracketString (std::string &amp; Data)</td>
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

<p>Parse an angle-bracket delimited string at the current position if one is present, returning the string contents.</p>

<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseAssignment {#a22fb9ac9c913da9317de5dd47e922ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseAssignment (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, AssignmentKind Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseBinOpRHS {#ab8cd84f16db451a5e1f5a0686d1f6a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseBinOpRHS (unsigned Precedence, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse all binary operators with precedence &gt;= 'Precedence'.</p>


<p>Res contains the LHS of the expression on input.</p>


<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseBracketExpr {#aa928ab3b2b141ead9902eb52f84eace3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseBracketExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a bracket expression and return it.</p>


<p>NOTE: This assumes the leading '[' has already been consumed.</p>


<p>bracketexpr ::= expr]</p>


<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseCppHashLineFilenameComment {#a6109f652dada46ce6418c67f2b79b710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseCppHashLineFilenameComment (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, bool SaveLocInfo=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCppHashLineFilenameComment as this: ::= # number "filename"</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseCurlyBlockScope {#ac2a12cece10f328b150b341acf27a9b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseCurlyBlockScope (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/asmrewrite">AsmRewrite</a> &gt; &amp; AsmStrRewrites)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseCVFileId {#a5013ebb4832779da0bd927c076fb526c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseCVFileId (int64_t &amp; FileId, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DirectiveName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseCVFunctionId {#a8526b37563ca2bdb20e8b8499bde194a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseCVFunctionId (int64_t &amp; FunctionId, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DirectiveName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAbort {#ab3a5e0c7c12c4f136a88bebb14d35108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveAbort (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveAbort ::= .abort [... message ...]</p>

<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAddrsig {#ad83158f1697319c10231d0d8ad959266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveAddrsig ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAddrsigSym {#a2ae2a2344e38f377639d7d364ced086f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveAddrsigSym ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAlign {#afd1f52851a21b14d9e075871bc59c8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveAlign (bool IsPow2, unsigned ValueSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveAlign ::= {.align, ...} expression [ , expression [ , expression ]]</p>

<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAltmacro {#a7567a0e2f43f88cf86e97f08789750e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveAltmacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveAltmacro ::= .altmacro ::= .noaltmacro</p>

<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAscii {#a1ece22de12907abcd359a5b633880910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveAscii (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, bool ZeroTerminated)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveAscii:</p>


<p>::= ( .asciz | .string ) [ "string" ( , "string" )* ]</p>


<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveBundleAlignMode {#a6217914a481325450cb1b97a5a3b0a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveBundleAlignMode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveBundleAlignMode ::= {.bundle_align_mode} expression</p>

<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveBundleLock {#a0c30a61328f44a83fbefb9b052a77978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveBundleLock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveBundleLock ::= {.bundle_lock} [align_to_end]</p>

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveBundleUnlock {#a4486f5598719d38a26d8477f2b53a5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveBundleUnlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveBundleLock ::= {.bundle_lock}</p>

<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIAdjustCfaOffset {#a2be05dc230fa01a6aa6b129f503776d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIAdjustCfaOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIAdjustCfaOffset ::= .cfi_adjust_cfa_offset adjustment</p>

<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIDefCfa {#afbda2cc95d38deca294d9bd2d24f07e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIDefCfa (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIDefCfa ::= .cfi_def_cfa register, offset</p>

<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIDefCfaOffset {#ab4a6e0cb0a8d46ad70750f5baa46151c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIDefCfaOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIDefCfaOffset ::= .cfi_def_cfa_offset offset</p>

<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIDefCfaRegister {#a15fbc799680c561d5871957b9b8c939b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIDefCfaRegister (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIDefCfaRegister ::= .cfi_def_cfa_register register</p>

<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIEndProc {#a3365349f4aaefa17d38417599a78c4ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIEndProc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIEndProc ::= .cfi_endproc</p>

<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIEscape {#a0121136aefec723cad78c5e7beefae58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIEscape (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIEscape ::= .cfi_escape expression[,...]</p>

<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFILabel {#adc9be73769c013d28ebe568fad1f455e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFILabel (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFILabel ::= .cfi_label label</p>

<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFILLVMDefAspaceCfa {#a0cbf06a4de966d8889c62228a5f65d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFILLVMDefAspaceCfa (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFILLVMDefAspaceCfa ::= .cfi_llvm_def_aspace_cfa register, offset, address_space</p>

<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIOffset {#aef75aa07050d01f3147d53694b6b4053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIOffset ::= .cfi_offset register, offset</p>

<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIPersonalityOrLsda {#a5887c9fa578d7628328e753c5909062a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIPersonalityOrLsda (bool IsPersonality)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIPersonalityOrLsda IsPersonality true for cfi_personality, false for cfi_lsda ::= .cfi_personality encoding, [symbol_name] ::= .cfi_lsda encoding, [symbol_name]</p>

<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRegister {#a595f7c32bf4fe17d9248e89cdf6e4ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIRegister (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRegister ::= .cfi_register register, register</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRelOffset {#a0a5d1574c30795b26a50e60232861d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIRelOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRelOffset ::= .cfi_rel_offset register, offset</p>

<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRememberState {#abf32e6935922d5b75e81cdd5a65fdedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIRememberState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRememberState ::= .cfi_remember_state</p>

<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRestore {#a2076847a2dab837e71d11aadd197a846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIRestore (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRestore ::= .cfi_restore register</p>

<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRestoreState {#af30fd3ed5521a615bee0285f5bfe64c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIRestoreState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRestoreState ::= .cfi_remember_state</p>

<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIReturnColumn {#a8bcf05a8b320a5b571112c19d998c4f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIReturnColumn (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIReturnColumn ::= .cfi_return_column register</p>

<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFISameValue {#ae4758997f0fe5366d5379d135ce65a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFISameValue (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFISameValue ::= .cfi_same_value register</p>

<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFISections {#a4999659eac834c3b41ee684347352c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFISections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFISections ::= .cfi_sections section [, section]</p>

<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFISignalFrame {#a335551445044983ae7c686c0b1a517e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFISignalFrame (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFISignalFrame ::= .cfi_signal_frame</p>

<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIStartProc {#a3aa817dc6a589a3f23be34caa217b8e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIStartProc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIStartProc ::= .cfi_startproc [simple]</p>

<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIUndefined {#aceceeebca04a53fe6c5b5988be3a1950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIUndefined (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIUndefined ::= .cfi_undefined register</p>

<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIValOffset {#afc5d2e0e9342af988eab3bfa8325c44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIValOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIValOffset ::= .cfi_val_offset register, offset</p>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIWindowSave {#ace82bd69be3c5ef608dd4c1e28195a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCFIWindowSave (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIWindowSave ::= .cfi_window_save</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveComm {#aac94039bfeec5c12c046737dfed26b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveComm (bool IsLocal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveComm ::= ( .comm | .lcomm ) identifier , size_expression [ , align_expression ]</p>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVDefRange {#abe637dc8ab41d86549b2262644e3cd9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVDefRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVDefRange ::= .cv_def_range RangeStart RangeEnd (GapStart GapEnd)*, bytes*</p>

<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFile {#af785b1f5367c1ec9f3b1f9f9bd988560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFile ::= .cv_file number filename [checksum] [checksumkind]</p>

<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFileChecksumOffset {#a600634b0fc1faf866a73ed973b941c94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVFileChecksumOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFileChecksumOffset ::= .cv_filechecksumoffset fileno</p>

<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFileChecksums {#a8b94185bbc2ddc7fe6e0d6de3ce43e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVFileChecksums ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFileChecksums ::= .cv_filechecksums</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFPOData {#a405f058ac862afe9541364a94472aa41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVFPOData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFPOData ::= .cv_fpo_data procsym</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFuncId {#a07cc20b416686fb4a25168442a56f027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVFuncId ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFuncId ::= .cv_func_id <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a></p>


<p>Introduces a function <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> that can be used with .cv_loc.</p>


<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVInlineLinetable {#a7d4efd17a8e033e8d83f919085adc4ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVInlineLinetable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVInlineLinetable ::= .cv_inline_linetable PrimaryFunctionId FileId LineNum FnStart FnEnd</p>

<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVInlineSiteId {#a7521709812209fb96bb00f99fc11225f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVInlineSiteId ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVInlineSiteId ::= .cv_inline_site_id <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> "within" IAFunc "inlined_at" IAFile IALine [IACol]</p>


<p>Introduces a function <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> that can be used with .cv_loc. Includes "inlined
at" source location information for use in the line table of the caller, whether the caller is a real function or another inlined call site.</p>


<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVLinetable {#a39230a71860983f5a63a7cad11e02790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVLinetable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVLinetable ::= .cv_linetable <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, FnStart, FnEnd</p>

<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVLoc {#a124ceb1405fa9ae2fd3d02606fc6c759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVLoc ::= .cv_loc <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> FileNumber [LineNumber] [ColumnPos] [prologue_end] [is_stmt VALUE] The first number is a file number, must have been previously assigned with a .file directive, the second number is the line number and optionally the third number is a column position (zero if not specified).</p>


<p>The remaining optional items are .loc sub-directives.</p>


<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVString {#a63a56f664dbb3c7706eaa2ec9cde5a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVString ::= .cv_stringtable "string"</p>

<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVStringTable {#aa7956bb61161dc983f0d93694d9ccd17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveCVStringTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVStringTable ::= .cv_stringtable</p>

<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveDCB {#a4e1f5c5dfa66aa72ab22f7b47b66bd7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveDCB (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveDCB ::= .dcb.</p>


<p>{b, l, w} expression, expression</p>


<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveDS {#ab5c3cddea3f74c3037f29f1cc4657f11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveDS (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveDS ::= .ds.</p>


<p>{b, d, l, p, s, w, x} expression</p>


<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveElse {#a57ec65d1967503cabbe22330b4357a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveElse (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveElse ::= .else</p>

<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveElseIf {#a5d2f1a27158cef67c735a5c7df1b9674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveElseIf (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveElseIf ::= .elseif expression</p>

<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEnd {#a716ac7a9569174af267208e3dbee63e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveEnd (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEnd ::= .end</p>

<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEndIf {#a8059f3965fd6f3b06013767dcdd7c078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveEndIf (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEndIf ::= .endif</p>

<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEndMacro {#ab6df8a7b1240daf2ac4d7ee5c097760e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveEndMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEndMacro ::= .endm ::= .endmacro</p>

<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEndr {#ac40728d0704ebda01857b48cf03573f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveEndr (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveError {#a2df4da36647ecd1f47cc9731e7b6d914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool WithMessage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveError ::= .err ::= .error [string]</p>

<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveExitMacro {#afe72200661b3480e8456d7536b287e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveExitMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveExitMacro ::= .exitm</p>

<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFile {#a123aff093d2907628798d82a960046ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveFile (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveFile ::= .file filename ::= .file number [directory] filename [md5 checksum] [source source-text]</p>

<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFill {#acb235ab04af23f15565e2a40ca38d233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveFill ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveFill ::= .fill expression [ , expression [ , expression ] ]</p>

<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIf {#a7409e8b3993389e9a9087fc65d41ea19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveIf (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, DirectiveKind DirKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIf ::= .if{,eq,ge,gt,le,lt,ne} expression</p>

<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIfb {#a5e929743a74a7cbbe1f513c3bf91e33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveIfb (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectBlank)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIfb ::= .ifb string</p>

<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIfc {#a8b9a1d7a44563361666c64ac6ba5ad60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveIfc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectEqual)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIfc ::= .ifc string1, string2 ::= .ifnc string1, string2</p>

<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIfdef {#abbac3caafc704d63811301dc318f7215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveIfdef (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool expect_defined)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIfdef ::= .ifdef symbol</p>

<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIfeqs {#a596b03dd3ec0f8eaa3d9e1e98cb717fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveIfeqs (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectEqual)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIfeqs ::= .ifeqs string1, string2</p>

<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIncbin {#a78af659d55c1755007b7c663518298f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveIncbin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIncbin ::= .incbin "filename" [ , skip [ , count ] ]</p>

<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveInclude {#a9989e87a059afc476e1c2f3deff42b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveInclude ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveInclude ::= .include "filename"</p>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIrp {#a54bac06b53c01858f47205e06042a6aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveIrp (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIrp ::= .irp symbol,values</p>

<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIrpc {#adbee8f14c04b792d9d09bc360c900c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveIrpc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIrpc ::= .irpc symbol,values</p>

<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveLEB128 {#af530a3132791044e662df1ce7ee7b06c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveLEB128 (bool Signed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveLEB128 ::= (.sleb128 | .uleb128) [ expression (, expression)* ]</p>

<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveLine {#acc30b95c1824494b1deb4d70583aa680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveLine ::= .line [number]</p>

<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveLoc {#ad0a424c5458e89bd957a0b8de7c0cb3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveLoc ::= .loc FileNumber [LineNumber] [ColumnPos] [basic_block] [prologue_end] [epilogue_begin] [is_stmt VALUE] [isa VALUE] The first number is a file number, must have been previously assigned with a .file directive, the second number is the line number and optionally the third number is a column position (zero if not specified).</p>


<p>The remaining optional items are .loc sub-directives.</p>


<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveLocLabel {#af3052e120496be89628041c77f2e4d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveLocLabel (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveLoc ::= .loc_label label</p>

<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveLTODiscard {#afe82e3f106d4bd4e99d73399b7849e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveLTODiscard ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveLTODiscard ::= ".lto_discard" [ identifier ( , identifier )* ] The LTO library emits this directive to discard non-prevailing symbols.</p>


<p>We ignore symbol assignments and attribute changes for the specified symbols.</p>


<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveMacro {#a6ddd2e5e3ad51820af135af61f8f72ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveMacro (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveMacro ::= .macro name[,] [parameters]</p>

<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveMacrosOnOff {#a13a446748c012d8185f6f3366aaff97e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveMacrosOnOff (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveMacrosOnOff ::= .macros_on ::= .macros_off</p>

<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveMSAlign {#ab32dd51b666f1141190f91427b03b81f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveMSAlign (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveMSEmit {#a32a1ed829401bc36221800de4886fe3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveMSEmit (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info, size_t Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveOctaValue {#a48cf8e2ed16948a3aa755bebfa0651be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveOctaValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveOctaValue ::= .octa [ hexconstant (, hexconstant)* ].</p>

<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveOrg {#af26d818234b097f560c009daacc8f60e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveOrg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveOrg ::= .org expression [ , expression ]</p>

<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectivePrint {#a31b0180cab11041e3524cefb3c0921a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectivePrint (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectivePseudoProbe {#abe882fae8feb54f0c5fa6b12266eacd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectivePseudoProbe ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectivePurgeMacro {#a83880918c6668279f10dbae1fcb65081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectivePurgeMacro (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectivePurgeMacro ::= .purgem name</p>

<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveRealDCB {#a43a7983cf873a8abbcd916c59694134f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveRealDCB (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveRealDCB ::= .dcb.</p>


<p>{d, s} expression, expression</p>


<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveRealValue {#a5c184b0044a4d9df31236d660da26303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveRealValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveRealValue ::= (.single | .double) [ expression (, expression)* ]</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveReloc {#ac624a83f61b5480aab4df0044320d348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveReloc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveReloc ::= .reloc expression , identifier [ , expression ]</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveRept {#a58557537569318a67a4f21d1502d12e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveRept (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveRept ::= .rep | .rept count</p>

<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSet {#a4b9ee8a4f74f25632bd9c48d912b6b15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveSet (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, AssignmentKind Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveSet: ::= .equ identifier ',' expression ::= .equiv identifier ',' expression ::= .set identifier ',' expression ::= .lto_set_conditional identifier ',' expression</p>

<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSpace {#a704dab055eff3732a67501c22a4926f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveSpace (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveSpace ::= (.skip | .space) expression [ , expression ]</p>

<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveStabs {#a550efe84411b279196e9db5341f33e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveStabs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveStabs ::= .stabs string, number, number, number</p>

<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSymbolAttribute {#ac716972afcc4947830d5d875229e3a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveSymbolAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a directive like ".globl" which accepts a single symbol (which should be a label or an external).</p>


<p>parseDirectiveSymbolAttribute ::= { ".globl", ".weak", ... } [ identifier ( , identifier )* ]</p>


<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveValue {#afe12d97b02636f4f593892a253fc9aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveValue ::= (.byte | .short | ... ) [ expression (, expression)* ]</p>

<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveWarning {#a99313ccd7ba92c6d14e6ad8731e419aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveWarning (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveWarning ::= .warning [string]</p>

<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveZero {#a9ccff216c84a0242f3146de9830f7614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseDirectiveZero ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveZero ::= .zero expression</p>

<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseEscapedString {#a515e58918a1422275c98640a07a93fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseEscapedString (std::string &amp; Data)</td>
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

<p>Parse the current token as a string which may include escaped characters and return the string contents.</p>

<p>Definition at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseExpression {#a8fc1050c60fea592a8902be95251705a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Reference <a href="#a8fc1050c60fea592a8902be95251705a">parseExpression</a>.</p>


<p>Referenced by <a href="#aec28069dca3f6f64e1e5e13477d62688">parseAbsoluteExpression</a>, <a href="#a8fc1050c60fea592a8902be95251705a">parseExpression</a> and <a href="#a02bbdeea1375089f06a52747e919b4dc">parsePrimaryExpr</a>.</p>

</div>
</div>

### parseExpression {#ac7fc5af218d2f17280c5b443dbe20838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>Parse an expression and return it.</p>


<p>expr ::= expr &amp;&amp;,|| expr -&gt; lowest. expr ::= expr |,^,&amp;,! expr expr ::= expr ==,!=,&lt;&gt;,&lt;,&lt;=,&gt;,&gt;= expr expr ::= expr &lt;&lt;,&gt;&gt; expr expr ::= expr +,- expr expr ::= expr *,/,% expr -&gt; highest. expr ::= primaryexpr</p>


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4aeb4b633eccde6dcae9b02af09c8302">llvm::AsmToken::At</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="#a054e4ac93e14d4f4c594f1b58a7c8e0a">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a433c1cd00305214e7d1d81d682c2346a">llvm::MCSymbolRefExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a7fe5bbdb7d87187478d77f3a1d5a2a93">llvm::MCAsmParser::parseOptionalToken</a>, <a href="#a02bbdeea1375089f06a52747e919b4dc">parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#aca3b32b0f673fcda41b604540f49a4f9">llvm::MCAsmParser::TokError</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4f5bc5fd0f95b1eb6e5aedfac9993cc2">llvm::MCSymbolRefExpr::VK_Invalid</a>.</p>

</div>
</div>

### parseIdentifier {#aa91d3c1b093e3561b948794724961f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseIdentifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Res)</td>
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

<p>Parse an identifier or string (as a quoted identifier) and set <span class="doxyComputerOutput">Res</span> to the identifier contents.</p>


<p>parseIdentifier: ::= identifier ::= string</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4aeb4b633eccde6dcae9b02af09c8302">llvm::AsmToken::At</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aaf57ac1b90bbb375414e2fd3fc15bf4c">llvm::AsmToken::Dollar</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#aefa517e84a358fccd59fb1815b87fa44">llvm::AsmToken::getIdentifier</a>, <a href="#a33ddf50b4cf84a930050c2e3affa6190">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a54bfbf3752a7a79c026b8ffe73308cb6">llvm::MCAsmLexer::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58">llvm::AsmToken::String</a>.</p>


<p>Referenced by <a href="#a02bbdeea1375089f06a52747e919b4dc">parsePrimaryExpr</a> and <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>.</p>

</div>
</div>

### parseMacroArgument {#a776b90cc1bda03e592f370c9da56b63d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseMacroArgument (<a href="/web-llvm/docs/api/namespaces/anonymous-asmparser-cpp-/#ac0478524b98a3f10477cb9006480f9e5">MCAsmMacroArgument</a> &amp; MA, bool Vararg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract AsmTokens for a macro argument.</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseMacroArguments {#a468af0d1c59a41301937bd9f3fb5ded6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseMacroArguments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> * M, <a href="/web-llvm/docs/api/namespaces/anonymous-asmparser-cpp-/#a17d4229190ca69c32766cbc745ab6411">MCAsmMacroArguments</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse all macro arguments for a given macro.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseMacroLikeBody {#a8b222a667ed694008b2978f3b541b195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmMacro * AsmParser::parseMacroLikeBody (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseMSInlineAsm {#a6779c29e343b8e71d97734686a3eabd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseMSInlineAsm (std::string &amp; AsmString, unsigned &amp; NumOutputs, unsigned &amp; NumInputs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; void *, bool &gt; &gt; &amp; OpDecls, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::string &gt; &amp; Constraints, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::string &gt; &amp; Clobbers, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> * MII, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * IP, <a href="/web-llvm/docs/api/classes/llvm/mcasmparsersemacallback">MCAsmParserSemaCallback</a> &amp; SI)</td>
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

<p>Parse MS-style inline assembly.</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfdae141b627ac649470f82d9c2eb37249fb">llvm::AOK_Align</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda990d2241c927f6ed413ae464f7796f00">llvm::AOK_CallInput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda79f10173e38b98986342a2ba9fb6b2a1">llvm::AOK_Emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda2273a4cd5bbad83c4f121c983185a8df">llvm::AOK_EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda0364c4ccb95b97b3cfe1a1c9a3014173">llvm::AOK_EVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfdaa86669a9cc5218a2b8ea4daafd9f195e">llvm::AOK_Input</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfdad2780c2bc4d0d36293a242d17c6b07a6">llvm::AOK_IntelExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda15b8af91c21aac1a862c9e92e8c2cbfb">llvm::AOK_Label</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda2fdf76d69064416f4ade1f4615561e41">llvm::AOK_Output</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda533ada35f0fe9e602da710cbcd6d9430">llvm::AOK_SizeDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda7abdec48f548b1a8b8ce59f17b52e5ec">llvm::AOK_Skip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#ae18bef1cef63d8cdb84adad1f9eea472">llvm::IntelExpr::BaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#aaeade81f238c8b2aed5f561358188196">llvm::AsmRewrite::Done</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a90c2a69257a8fb499590383bd6b41f41">llvm::IntelExpr::emitImm</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#ad38a8c360d26f17718aafe2c7c5fc470">llvm::MCParsedAsmOperand::getConstraint</a>, <a href="#a054e4ac93e14d4f4c594f1b58a7c8e0a">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="#a33ddf50b4cf84a930050c2e3affa6190">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#ab7825dc94141647be2917e6e410d97d0">llvm::MCParsedAsmOperand::getMCOperandNum</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#afb1a8b2b0718fe4a475feeefe15da9e1">llvm::MCParsedAsmOperand::getOpDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a78471ca3b825294a4e6015500d7a6630">llvm::MCParsedAsmOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a95096f6ce0d0d6e4140c954962796332">llvm::MCParsedAsmOperand::getSymName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a86940ae2900e1fb1066f5e169c0af6a7">llvm::IntelExpr::hasBaseReg</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a0e6fd9c1065f3aa23de324392652aeca">llvm::IntelExpr::hasIndexReg</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a31fe9e50f9bd6de0c55bdd144d874e98">llvm::IntelExpr::hasOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a4947313871f8935468ae02f6621260c8">llvm::MCAsmParser::hasPendingError</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a21dbdc3fb6e0b3cd12289b4b0478c714">llvm::IntelExpr::hasRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a06c8486a2041e1affbca1d4477bf33c0">llvm::IntelExpr::Imm</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a6f3150175cdaf4e5d88abd55fb222327">llvm::IntelExpr::IndexReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a529587a34ba75058d5002465e08f6cf8">llvm::AsmRewrite::IntelExp</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a20853111e3553d57fac94e803c52649c">llvm::AsmRewrite::IntelExpRestricted</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#ab4d869652f0c0d119d84f800cf49229b">llvm::MCParsedAsmOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a00dfaa7a4c4ab65f8f0b572fd7f04e68">llvm::MCParsedAsmOperand::isMemUseUpRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a8608c30f9162510854ebd7ad920cb288">llvm::MCParsedAsmOperand::isOffsetOfLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a3212ab0fba4f46a46382c297dd7ee5f7">llvm::MCParsedAsmOperand::isReg</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#ae3a557482aa4e3ab1faa40279052aea6">llvm::IntelExpr::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a49376fe6e2f150528a01d6e04c6bbbf9">llvm::AsmRewrite::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#aa86261d4d5f182d5be6d229e947a83d7">llvm::AsmRewrite::Label</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a73fd5ec31aade399b31f6da4bd3de4f7">llvm::AsmRewrite::Len</a>, <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a801ff63a978f05ed7a17965654f4db42">llvm::AsmRewrite::Loc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a4546812b19a8dd8aaf85077500ad0625">llvm::MCParsedAsmOperand::needAddressOf</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#ad44afff5ca85c4a193e7a112594c4899">llvm::IntelExpr::NeedBracs</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a81b64c6a2f24767fb2f524a622898b9b">llvm::IntelExpr::OffsetName</a>, <a href="#a034b546ea133319ab2244f9bfa28ecae">parseStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a25158c234ca9e60f3976a36d7d6ef271">llvm::MCAsmParser::printPendingErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ad0ad5f0b1236badc25e0613d3b962997">llvm::MCInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#ac27a97bbb42a7f0481f803251c65c237">rewritesSort</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a7316b8a13ba48c8e8157f02cbdd51bd9">llvm::IntelExpr::Scale</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48f85da577c6ce7d9aed90437dc0d07c">llvm::unique</a> and <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#ac737e0ab2d8987b1ce89fa143dd255b2">llvm::AsmRewrite::Val</a>.</p>

</div>
</div>

### parseParenExpr {#abbee37ebbde2698746d5483f8374a1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseParenExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a paren expression and return it.</p>


<p>NOTE: This assumes the leading '(' has already been consumed.</p>


<p>parenexpr ::= expr)</p>


<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseParenExpression {#a35423377e62d2d83bec01c6cf269b9f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseParenExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>Parse an arbitrary expression, assuming that an initial '(' has already been consumed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The value of the expression. The result is undefined on error.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseParenExprOfDepth {#a1c8f1c479ef06f41b1f2010afd80b43a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseParenExprOfDepth (unsigned ParenDepth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>Parse an arbitrary expression of a specified parenthesis depth, assuming that the initial '(' characters have already been consumed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParenDepth</td>
<td class="doxyParamItemDescription"><p>- Specifies how many trailing expressions outside the current parentheses we have to parse.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The value of the expression. The result is undefined on error.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a9e6496a765eb2a14512ca0d5f48185fa">llvm::AsmToken::getEndLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a709fe7ec3803940386b0588e9a1c6f02">llvm::MCAsmParser::parseRParen</a>.</p>

</div>
</div>

### parsePrimaryExpr {#a02bbdeea1375089f06a52747e919b4dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parsePrimaryExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc, <a href="/web-llvm/docs/api/structs/llvm/asmtypeinfo">AsmTypeInfo</a> * TypeInfo)</td>
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

<p>Parse a primary expression and return it.</p>


<p>primaryexpr ::= (parenexpr primaryexpr ::= symbol primaryexpr ::= number primaryexpr ::= '.' primaryexpr ::= ~,+,- primaryexpr</p>


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4aeb4b633eccde6dcae9b02af09c8302">llvm::AsmToken::At</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8792e8ff663b631c3d0069d1655c7b45">llvm::AsmToken::BigNum</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a58195f308d23f783e2b52e968ff1fe46">llvm::MCUnaryExpr::createLNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#aff718d95a5738283e9049bc93fa9abe2">llvm::MCUnaryExpr::createMinus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#af8b9397b901280268465e71ed2fef286">llvm::MCUnaryExpr::createNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a8f9fe9e0790b764dc9ef925a83408f74">llvm::MCUnaryExpr::createPlus</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#abefd1a22d96014163fe12930da2364ec">llvm::MCTargetAsmParser::createTargetUnaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aaf57ac1b90bbb375414e2fd3fc15bf4c">llvm::AsmToken::Dollar</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae95926c6ea560f4332395213cc7519e9">llvm::AsmToken::Dot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039af475f82c0aa5e42ef5751dcdc3bee49f">llvm::AsmToken::Exclaim</a>, <a href="#a054e4ac93e14d4f4c594f1b58a7c8e0a">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a392412e22be62f31478cfca07d562055">llvm::MCContext::getInlineAsmLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a270e1171db01008f862ffbc34f8476fc">llvm::AsmToken::getIntVal</a>, <a href="#a33ddf50b4cf84a930050c2e3affa6190">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a54bfbf3752a7a79c026b8ffe73308cb6">llvm::MCAsmLexer::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a3168618a19701d0fb78aefb4d4e664de">llvm::AsmToken::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a433c1cd00305214e7d1d81d682c2346a">llvm::MCSymbolRefExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9c71bbbb6e41ab4d9b6a95620f4266a9">llvm::MCTargetAsmParser::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa462dae167e31cac32e97bb0c77ab071">llvm::MCSymbol::isUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d">llvm::AsmToken::LBrac</a>, <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="#a8fc1050c60fea592a8902be95251705a">parseExpression</a>, <a href="#aa91d3c1b093e3561b948794724961f4b">parseIdentifier</a>, <a href="#a02bbdeea1375089f06a52747e919b4dc">parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a709fe7ec3803940386b0588e9a1c6f02">llvm::MCAsmParser::parseRParen</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a00c4e8d8fb246b6b7aeed5c7b53ee299">llvm::AsmToken::PercentCall16</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a707c1a6ff33be3833fa784e55c72d356">llvm::AsmToken::PercentCall_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a074f871580c44c082aa24aaafd8a238a">llvm::AsmToken::PercentCall_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a267b3c56c189ca7b2c22f3f5a29647fe">llvm::AsmToken::PercentDtprel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa8b764c71f0045677baab76623a52bcd">llvm::AsmToken::PercentDtprel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a00774b22629d30aaa48e1c2bd537028b">llvm::AsmToken::PercentGot</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039af1f8ea5e121b4bc15a5df42c055bd6d7">llvm::AsmToken::PercentGot_Disp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ab0762694eece06d0f7a3a2079a4a4fc8">llvm::AsmToken::PercentGot_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0c1d09e9bf3105cc4a9f0fdbd353573e">llvm::AsmToken::PercentGot_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad1e2f5b48c997464f7959fc57dffc5f8">llvm::AsmToken::PercentGot_Ofst</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a92f6b21bb33e8fed87795f60509087b9">llvm::AsmToken::PercentGot_Page</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0605e7b15189ad4dbaf2de310d8d71d6">llvm::AsmToken::PercentGottprel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aceac274aaa62864ab0b60654281e237a">llvm::AsmToken::PercentGp_Rel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a07aadc6194c34b01c1dbc32579382c1e">llvm::AsmToken::PercentHi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1889a8a107d7a02053f669a752290d2d">llvm::AsmToken::PercentHigher</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ab00380bcbfc11a24a06d6ff70619f9fa">llvm::AsmToken::PercentHighest</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad3c8fae162d44bb21f7f39c853e85eca">llvm::AsmToken::PercentLo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039afe3b827d1ceee6cf5aaf0bb61cc1e77f">llvm::AsmToken::PercentNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a28be2810a4857bb3b0aad6844d80176e">llvm::AsmToken::PercentPcrel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7aa2c1d1de0fe4ef4d1d2275632aa6a1">llvm::AsmToken::PercentPcrel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8f666b660d975090f718938ee00fe9fc">llvm::AsmToken::PercentTlsgd</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a91a7f91ec2b3a0618572a821556591cf">llvm::AsmToken::PercentTlsldm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8df6f192abb2cb6a173a7a2aa91bd8a2">llvm::AsmToken::PercentTprel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a63518ba1849d2eb240372e55b9a04436">llvm::AsmToken::PercentTprel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">llvm::AsmToken::Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad1efc309b8dfe9289db5493d71569f0b">llvm::AsmToken::Real</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a871b85a46f471e616995b722df807211">llvm::AsmToken::Star</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58">llvm::AsmToken::String</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a151c8770a1290c7713e3a8490ee09471">llvm::AsmToken::Tilde</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#aca3b32b0f673fcda41b604540f49a4f9">llvm::MCAsmParser::TokError</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4f5bc5fd0f95b1eb6e5aedfac9993cc2">llvm::MCSymbolRefExpr::VK_Invalid</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="#ac7fc5af218d2f17280c5b443dbe20838">parseExpression</a> and <a href="#a02bbdeea1375089f06a52747e919b4dc">parsePrimaryExpr</a>.</p>

</div>
</div>

### parseRealValue {#abdaa8ae9b3e01099946066f89a8e10ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseRealValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a floating point expression using the float <span class="doxyComputerOutput">Semantics</span> and set <span class="doxyComputerOutput">Res</span> to the value.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae9c79bda245d64ef5df420f94ec4bbd1">llvm::StringRef::compare_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0596fb939ff753151c9c37ed2b671b4c">llvm::errorToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a>, <a href="#a33ddf50b4cf84a930050c2e3affa6190">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aeecd5fa66870de83d235933a683b5952">llvm::APFloat::getNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a3168618a19701d0fb78aefb4d4e664de">llvm::AsmToken::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="#af3d4af20be9f94cbdad904d45cafbefa">Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">llvm::AsmToken::Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad1efc309b8dfe9289db5493d71569f0b">llvm::AsmToken::Real</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#aca3b32b0f673fcda41b604540f49a4f9">llvm::MCAsmParser::TokError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a066e2a31a13d6520e52ae1944f194662">llvm::Value</a>.</p>

</div>
</div>

### parseRegisterOrRegisterNumber {#a26abcaa93dd78ecd18e762e40fbca90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::parseRegisterOrRegisterNumber (int64_t &amp; Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parse register name or number.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseStringToComma {#a7505aa908c01f185d61fac457c6f7a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AsmParser::parseStringToComma ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse until the end of a statement or a comma is encountered, return the contents from the current token up to the end or comma.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseStringToEndOfStatement {#af927a042550c3a9220514a11b79b187d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AsmParser::parseStringToEndOfStatement ()</td>
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

<p>Parse up to the end of statement and a return the contents from the current token until the end of the statement; the current token on exit will be either the EndOfStatement or EOF.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### printError {#a307a44ebfb83c5c16d6a0af1861547c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::printError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
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

<p>Emit an error at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The return value is always true, as an idiomatic convenience to clients.</p></dd>
</dl>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afad5b9aac74030a159903f3cf64c481c">llvm::MCAsmParser::HadError</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="#a1f9777a39f525bf9f8a85ce9d52cccd9">Run</a>.</p>

</div>
</div>

### printMacroInstantiations {#af36a6362c5cb970cc8ddf02eac7a3414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmParser::printMacroInstantiations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### printMessage {#a22f3933720a830d7a60f62e43879d3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmParser.cpp}::AsmParser::printMessage (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777">SourceMgr::DiagKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### processIncbinFile {#aac49ab77dcc55f1798c55872c96a92ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::processIncbinFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Filename, int64_t Skip=0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Count=nullptr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the specified file for the .incbin directive.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the specified .incbin file by searching for it in the include paths then just emitting the byte contents of the file to the streamer.</p>


<p>This returns true on failure.</p>


<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### setAssemblerDialect {#a1c016ce9ac36c99065a1c51b817c8cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmParser.cpp}::AsmParser::setAssemblerDialect (unsigned i)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### setMacrosEnabled {#a9f1e4937edebd3aa3b2d3b85f66223dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmParser.cpp}::AsmParser::setMacrosEnabled (bool Flag)</td>
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

<p>Control a flag in the parser that enables or disables macros.</p>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### setParsingMSInlineAsm {#a59ef0d658df455dcf1c37cce90712788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmParser.cpp}::AsmParser::setParsingMSInlineAsm (bool V)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### Warning {#a57a5adf3db1aba1fc30809f73fc05c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmParser::Warning (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
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

<p>Emit a warning at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The return value is true, if warnings are fatal.</p></dd>
</dl>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777a6bcc8ac9374461ed0599334db63365d0">llvm::SourceMgr::DK_Warning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
