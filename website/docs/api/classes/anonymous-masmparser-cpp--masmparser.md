---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-masmparser-cpp-/masmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MasmParser` Class

<p>The concrete assembly parser instance. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MasmParser.cpp}::MasmParser { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314e31f13f6e31ef75cced99a4e946c2">MasmParser</a> (SourceMgr &amp;SM, MCContext &amp;Ctx, MCStreamer &amp;Out, const MCAsmInfo &amp;MAI, struct tm TM, unsigned CB=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4080ce1e3aceb1e7904ff18196b96e4e">MasmParser</a> (const MasmParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b475bb30badf7d39f82d088bc7e45aa">~MasmParser</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser">MasmParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a132b6ee69da8751dc4b4ceaf501dbae9">operator=</a> (const MasmParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46449244c1f2d4e4b2022d1126e7c5ab">Run</a> (bool NoInitialTextSection, bool NoFinalize=false) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the parser on the input source buffer. <a href="#a46449244c1f2d4e4b2022d1126e7c5ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad89ebc499fe4187fb52f86729c44316d">addDirectiveHandler</a> (StringRef Directive, ExtensionDirectiveHandler Handler) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24dd12008c998554435cec558a45c26a">addAliasForDirective</a> (StringRef Directive, StringRef Alias) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmlexer">AsmLexer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae312499fb091ba834bb7ac58984d2252">Lexer</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafc7cbc8a836e22f9b20db715e7a5c6c">Ctx</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b1085973bc6d95bc373e654d24e695">Out</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad40faf72ff0e1c0931c4e84b787401">MAI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d742da6d24d493c57a9d8433b30745">SrcMgr</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b2a70e20323d3db5ac448367862344">SavedDiagHandler</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593150ae7466969b1ac7a520413ef831">SavedDiagContext</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa33fc10f385d7ed5bf28b8f83b8a064">PlatformParser</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9baef79719475d6634a1efc71cae3f">CurBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the current buffer index we're lexing from as managed by the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> object. <a href="#a4e9baef79719475d6634a1efc71cae3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf61e44dfe7a135550980e7a6d8e0d5">TM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>time of assembly <a href="#a4bf61e44dfe7a135550980e7a6d8e0d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31e3d26998e29fb46ad486c5ca6557f3">EndStatementAtEOFStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmcond">AsmCond</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bc42975e59400a499b33a677300d533">TheCondState</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca56e7d16ec7a99a7538cf91cf84ef2">TheCondStack</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6440c63a4d3fa3e8d1b8db6073ca7664">ExtensionDirectiveMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>maps directive names to handler methods in parser extensions. <a href="#a6440c63a4d3fa3e8d1b8db6073ca7664">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; Variable &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b4c398b4d0d686ff5bfc8f34b9e7ffa">Variables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674216c44ded1603cd0e52354305cb06">StructInProgress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stack of active struct definitions. <a href="#a674216c44ded1603cd0e52354305cb06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add885649802bf9142f72ea1466ba1ad7">Structs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps struct tags to struct definitions. <a href="#add885649802bf9142f72ea1466ba1ad7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/asmtypeinfo">AsmTypeInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a59d0f84bb6a1adf4baba583a78b35">KnownType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps data location names to types. <a href="#a32a59d0f84bb6a1adf4baba583a78b35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/macroinstantiation">MacroInstantiation</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45fbdac199a892556119e0021ad69351">ActiveMacros</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stack of active macro instantiations. <a href="#a45fbdac199a892556119e0021ad69351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aef886429821d411d7c3af4e9a0d6df">MacroLikeBodies</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of bodies of anonymous macros. <a href="#a5aef886429821d411d7c3af4e9a0d6df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec646d26913c5d68a9a8a5a9259f3339">NumOfMacroInstantiations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of how many .macro's have been instantiated. <a href="#aec646d26913c5d68a9a8a5a9259f3339">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">CppHashInfoTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65efdff1b8d27c1b87aef5624cf0cf47">CppHashInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb70ada1beb78b552ccb7b583b4827f2">FirstCppHashFilename</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The filename from the first cpp hash file line comment, if any. <a href="#aeb70ada1beb78b552ccb7b583b4827f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>, CppHashInfoTy, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac82ce61f243eb141399c086f0bb558e7">DirLabels</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of forward directional labels for diagnosis at the end. <a href="#ac82ce61f243eb141399c086f0bb558e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d17b5422777874a2816fb78e00df3d8">AssemblerDialect</a> = 1U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AssemblerDialect. <a href="#a0d17b5422777874a2816fb78e00df3d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04169434184405235c96db83dfd60bd6">IsDarwin</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>is Darwin compatibility enabled? <a href="#a04169434184405235c96db83dfd60bd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32079f2281b284adc179fd8f3b7003ed">ParsingMSInlineAsm</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are we parsing ms-style inline assembly? <a href="#a32079f2281b284adc179fd8f3b7003ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf488f11cfc90483a3d6b580a2efee7">ReportedInconsistentMD5</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Did we already inform the user about inconsistent <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> usage? <a href="#aecf488f11cfc90483a3d6b580a2efee7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0455ced2955f31767365077ab63bc8b">AngleBracketDepth</a> = 0U</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6826b5f51f429ae2fbf4c827586999ed">LocalCounter</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ExpandKind { <a href="#a9246043f1e0c2b0855ae7dd69b8308b2">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">IdentifierPositionKind { <a href="#af84638c0bc3a211840905bad257bf39e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an identifier or string (as a quoted identifier) and set <span class="doxyComputerOutput">Res</span> to the identifier contents. <a href="#af84638c0bc3a211840905bad257bf39e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DirectiveKind { <a href="#a0f7d9f989d988b78677af2e3f888f33a">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">CVDefRangeType { <a href="#ae3cede150e95aa800f01c276994eb1e5">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">BuiltinSymbol { <a href="#a064df5a0f44746675d5b115d7d103f59">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6618681ca8ba2eb0b506d682c9de5d1">DirectiveKindMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps directive name --&gt; DirectiveKind enum, for directives parsed by this class. <a href="#ac6618681ca8ba2eb0b506d682c9de5d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; CVDefRangeType &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64aceefe6cce901f701da140aef3f8e7">CVDefRangeTypeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps Codeview def_range types --&gt; CVDefRangeType enum, for Codeview def_range types parsed by this class. <a href="#a64aceefe6cce901f701da140aef3f8e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; BuiltinSymbol &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a338f6b11f7553687ac9a8e870842ed">BuiltinSymbolMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps builtin name --&gt; BuiltinSymbol enum, for builtins handled by this class. <a href="#a4a338f6b11f7553687ac9a8e870842ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3cad9372a815b281af642700fff1fbc">getSourceManager</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17ba7a1f3ebadc9d347d00f9d910c14">getLexer</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e18d4299230d21094f423f2fdc7fc72">getContext</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08041d421b04248dc8a9a193868fa850">getStreamer</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the output streamer for the assembler. <a href="#a08041d421b04248dc8a9a193868fa850">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeviewcontext">CodeViewContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4e1cb388f1118953752d11ea770dc1">getCVContext</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d473a254f569b1c1fdf6b1244cf8b38">getAssemblerDialect</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18ee9263e29f8eec6f6a01be947f3a60">setAssemblerDialect</a> (unsigned i) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9203278cccf22c7dafdfe75efa742ff4">Note</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a note at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#a9203278cccf22c7dafdfe75efa742ff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f88c883adc92a0b9eacbc5a4064d2b">Warning</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a warning at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#a08f88c883adc92a0b9eacbc5a4064d2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac54c7247683fdbcce5c47cf186227d00">printError</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an error at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#ac54c7247683fdbcce5c47cf186227d00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa801ffa70e7cd238829a01fa92d71c4">Lex</a> (ExpandKind ExpandNextToken)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3606169bb499457fe3acc26441161166">Lex</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next AsmToken in the stream, possibly handling file inclusion first. <a href="#a3606169bb499457fe3acc26441161166">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13733656a25cdd26131630f2ec1d1b5">setParsingMSInlineAsm</a> (bool V) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42c43698f83b23ab4f8ba2f5e350f38d">isParsingMSInlineAsm</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d49e00ff845f0165f228a3484de058e">isParsingMasm</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae39bffc615ea979f44a25c730094bbb4">defineMacro</a> (StringRef Name, StringRef Value) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d778f1ca3df360a0a0e09cef5930f1">lookUpField</a> (StringRef Name, AsmFieldInfo &amp;Info) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bb608aba526021fe280a23f84ee7754">lookUpField</a> (StringRef Base, StringRef Member, AsmFieldInfo &amp;Info) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2e029f6e72e5147a329b0a221f38fbf">lookUpType</a> (StringRef Name, AsmTypeInfo &amp;Info) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae48dce9460eac00f49a306f8d48fdf11">parseMSInlineAsm</a> (std::string &amp;AsmString, unsigned &amp;NumOutputs, unsigned &amp;NumInputs, SmallVectorImpl&lt; std::pair&lt; void *, bool &gt; &gt; &amp;OpDecls, SmallVectorImpl&lt; std::string &gt; &amp;Constraints, SmallVectorImpl&lt; std::string &gt; &amp;Clobbers, const MCInstrInfo *MII, MCInstPrinter *IP, MCAsmParserSemaCallback &amp;SI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse MS-style inline assembly. <a href="#ae48dce9460eac00f49a306f8d48fdf11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902a0a4bd0fb4232ebd3d92ad800aadf">parseExpression</a> (const MCExpr *&amp;Res)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46e587fd477a44bb0b3c9e3689ff2f92">parseExpression</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an expression and return it. <a href="#a46e587fd477a44bb0b3c9e3689ff2f92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc, AsmTypeInfo *TypeInfo) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a primary expression and return it. <a href="#a48e574342f9028f1077132c27267952b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1bf86c7b80900c21e8f6777aa1cd7d">parseParenExpression</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an arbitrary expression, assuming that an initial '(' has already been consumed. <a href="#aeb1bf86c7b80900c21e8f6777aa1cd7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61115ff1360e15d4f0eb3f12d757d7c1">parseParenExprOfDepth</a> (unsigned ParenDepth, const MCExpr *&amp;Res, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an arbitrary expression of a specified parenthesis depth, assuming that the initial '(' characters have already been consumed. <a href="#a61115ff1360e15d4f0eb3f12d757d7c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759ccd5c07709f9d7fd4e339af61f662">parseAbsoluteExpression</a> (int64_t &amp;Res) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an expression which must evaluate to an absolute value. <a href="#a759ccd5c07709f9d7fd4e339af61f662">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c3ac00eab4ed0328bc8c8942957c83b">parseRealValue</a> (const fltSemantics &amp;Semantics, APInt &amp;Res)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a floating point expression using the float <span class="doxyComputerOutput">Semantics</span> and set <span class="doxyComputerOutput">Res</span> to the value. <a href="#a1c3ac00eab4ed0328bc8c8942957c83b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6dea9845d70ac952115bdbe378dbea1">parseIdentifier</a> (StringRef &amp;Res, IdentifierPositionKind Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseIdentifier: ::= identifier ::= string <a href="#af6dea9845d70ac952115bdbe378dbea1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87c2b4cc4079362b8f826afacfd8231">parseIdentifier</a> (StringRef &amp;Res) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an identifier or string (as a quoted identifier) and set <span class="doxyComputerOutput">Res</span> to the identifier contents. <a href="#aa87c2b4cc4079362b8f826afacfd8231">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ecdddfce4d05cafad65fa385d17f77">eatToEndOfStatement</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Throw away the rest of the line for testing purposes. <a href="#a19ecdddfce4d05cafad65fa385d17f77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d982772a36fe8255164eced5dd71bf">checkForValidSection</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure that we have a valid section set in the streamer. <a href="#a10d982772a36fe8255164eced5dd71bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e3c75dc7536e385bf086a600d4e57d5">expandMacros</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a8e3c75dc7536e385bf086a600d4e57d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab42058a45d470b008f26fd29b4fb76c4">peekTok</a> (bool ShouldSkipSpace=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05bb73a9b1f718bee860d01bf0e4c688">parseStatement</a> (ParseStatementInfo &amp;Info, MCAsmParserSemaCallback *SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseStatement: ::= % statement ::= EndOfStatement ::= Label* <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> ...Operands... EndOfStatement ::= Label* Identifier OperandList* EndOfStatement. <a href="#a05bb73a9b1f718bee860d01bf0e4c688">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10428bc1ba22ce89ec6be75d6fc27556">parseCurlyBlockScope</a> (SmallVectorImpl&lt; AsmRewrite &gt; &amp;AsmStrRewrites)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a925aaa0f2255093e61ce634871122d27">parseCppHashLineFilenameComment</a> (SMLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCppHashLineFilenameComment as this: ::= # number "filename" <a href="#a925aaa0f2255093e61ce634871122d27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd24774a7e2d181182f7a0c628d6819">expandMacro</a> (raw_svector_ostream &amp;OS, StringRef Body, ArrayRef&lt; MCAsmMacroParameter &gt; Parameters, ArrayRef&lt; MCAsmMacroArgument &gt; A, const std::vector&lt; std::string &gt; &amp;Locals, SMLoc L)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048a484457069efc7be3f05e4b11fc5c">isInsideMacroInstantiation</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are we inside a macro instantiation? <a href="#a048a484457069efc7be3f05e4b11fc5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf77ddb2d4fb9faff2d6f6ca63b0e11f">handleMacroEntry</a> (const MCAsmMacro *M, SMLoc NameLoc, AsmToken::TokenKind ArgumentEndTok=AsmToken::EndOfStatement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle entry to macro instantiation. <a href="#abf77ddb2d4fb9faff2d6f6ca63b0e11f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33726a4abdbc936b0153374f444a178b">handleMacroInvocation</a> (const MCAsmMacro *M, SMLoc NameLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invocation of macro function. <a href="#a33726a4abdbc936b0153374f444a178b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9daa2795a23b297a36a0ada5fc5c2cde">handleMacroExit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle exit from macro instantiation. <a href="#a9daa2795a23b297a36a0ada5fc5c2cde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5a735ef2dd76b3e51a6001c24acf284">parseMacroArgument</a> (const MCAsmMacroParameter *MP, MCAsmMacroArgument &amp;MA, AsmToken::TokenKind EndTok=AsmToken::EndOfStatement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract AsmTokens for a macro argument. <a href="#aa5a735ef2dd76b3e51a6001c24acf284">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab474a00700753e0bc01b23733c107287">parseMacroArguments</a> (const MCAsmMacro *M, MCAsmMacroArguments &amp;A, AsmToken::TokenKind EndTok=AsmToken::EndOfStatement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse all macro arguments for a given macro. <a href="#ab474a00700753e0bc01b23733c107287">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf78c53490e61aa2107cd30ea0e450e">printMacroInstantiations</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ad449e41c042be65171cc3a012f4423">expandStatement</a> (SMLoc Loc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea65225f3507247f5495f456c1762471">printMessage</a> (SMLoc Loc, SourceMgr::DiagKind Kind, const Twine &amp;Msg, SMRange Range=std::nullopt) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2552264f41f57cff5738b24c57df1a5e">lookUpField</a> (const StructInfo &amp;Structure, StringRef Member, AsmFieldInfo &amp;Info) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3886ee69415d83cfc3284f1ec062ad">enabledGenDwarfForAssembly</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we emit DWARF describing this assembler source? <a href="#aea3886ee69415d83cfc3284f1ec062ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf69ee594e31d45c1c6065022b14ce8">enterIncludeFile</a> (const std::string &amp;Filename)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enter the specified file. This returns true on failure. <a href="#a5bf69ee594e31d45c1c6065022b14ce8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd9299725e5b485ba78a6e5e76963d1">jumpToLoc</a> (SMLoc Loc, unsigned InBuffer=0, bool EndStatementAtEOF=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the current lexer position to that given by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>. <a href="#aebd9299725e5b485ba78a6e5e76963d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4112e259651b721e27ea572fd874002">parseStringRefsTo</a> (AsmToken::TokenKind EndTok)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse up to a token of kind <span class="doxyComputerOutput">EndTok</span> and return the contents from the current token up to (but not including) this token; the current token on exit will be either this kind or EOF. <a href="#ab4112e259651b721e27ea572fd874002">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a708016f80fa4d2044f553d243e6e8822">parseStringTo</a> (AsmToken::TokenKind EndTok)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a727c06165a9106a3b0759fb344e14bb5">parseStringToEndOfStatement</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse up to the end of statement and return the contents from the current token until the end of the statement; the current token on exit will be either the EndOfStatement or EOF. <a href="#a727c06165a9106a3b0759fb344e14bb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2847168dd8053fd74bd6e75d0bb4c9d6">parseTextItem</a> (std::string &amp;Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>textItem ::= textLiteral | textMacroID | % constExpr <a href="#a2847168dd8053fd74bd6e75d0bb4c9d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f5f402526aefe4f34fa6e8989f597c">getBinOpPrecedence</a> (AsmToken::TokenKind K, MCBinaryExpr::Opcode &amp;Kind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebbcf249e68ad2885fc69da9bf4beb90">parseBinOpRHS</a> (unsigned Precedence, const MCExpr *&amp;Res, SMLoc &amp;EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse all binary operators with precedence &gt;= 'Precedence'. <a href="#aebbcf249e68ad2885fc69da9bf4beb90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42fb541c38140136796f19cbeec0d80">parseParenExpr</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a paren expression and return it. <a href="#aa42fb541c38140136796f19cbeec0d80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc79d750b0c936352fcc756e8fe9663">parseBracketExpr</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a bracket expression and return it. <a href="#a3cc79d750b0c936352fcc756e8fe9663">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a569156266365309580745e126914ad85">parseRegisterOrRegisterNumber</a> (int64_t &amp;Register, SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parse register name or number. <a href="#a569156266365309580745e126914ad85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35479af33a07bb5c70b2c145e1f2066a">parseCVFunctionId</a> (int64_t &amp;FunctionId, StringRef DirectiveName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33d8ef9973061b5588241c082f6371ec">parseCVFileId</a> (int64_t &amp;FileId, StringRef DirectiveName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada091238d012c874b91e6a24661a870d">isMacroLikeDirective</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e0ca571e4cbd2dd6301636d0ff1dc22">evaluateBuiltinValue</a> (BuiltinSymbol Symbol, SMLoc StartLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbed4057e4eb09fdadb8e65311a7a2f2">evaluateBuiltinTextMacro</a> (BuiltinSymbol Symbol, SMLoc StartLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a830a8ed7c24753368c31706e9bb289a6">parseDirectiveAscii</a> (StringRef IDVal, bool ZeroTerminated)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveAscii: ::= ( .ascii | .asciz | .string ) [ "string" ( , "string" )* ] <a href="#a830a8ed7c24753368c31706e9bb289a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201ae8a3351e3f6c1fc1a63345870349">emitIntValue</a> (const MCExpr *Value, unsigned Size)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68ea763319aebf69bc74848aeee0bce6">parseScalarInitializer</a> (unsigned Size, SmallVectorImpl&lt; const MCExpr * &gt; &amp;Values, unsigned StringPadLength=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b7094001fb9413bfca4774dd4940ed5">parseScalarInstList</a> (unsigned Size, SmallVectorImpl&lt; const MCExpr * &gt; &amp;Values, const AsmToken::TokenKind EndToken=AsmToken::EndOfStatement)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43da2b1b067e55727a163d3e4b7c3964">emitIntegralValues</a> (unsigned Size, unsigned *Count=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bb8a5cb4d24a709b401e2df99d9792d">addIntegralField</a> (StringRef Name, unsigned Size)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab43251a2501c33e5d7281aa005b44940">parseDirectiveValue</a> (StringRef IDVal, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveValue ::= (byte | word | ... ) [ expression (, expression)* ] <a href="#ab43251a2501c33e5d7281aa005b44940">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0161f03993da8a67125ac9ea31298d06">parseDirectiveNamedValue</a> (StringRef TypeName, unsigned Size, StringRef Name, SMLoc NameLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveNamedValue ::= name (byte | word | ... ) [ expression (, expression)* ] <a href="#a0161f03993da8a67125ac9ea31298d06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f99aa12f95ce46564f979d25a5a210">emitRealValues</a> (const fltSemantics &amp;Semantics, unsigned *Count=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c37a9325928495237a3050dfbe4f69">addRealField</a> (StringRef Name, const fltSemantics &amp;Semantics, size_t Size)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7465acb55dc7210ef172dfd3ee6a7e">parseDirectiveRealValue</a> (StringRef IDVal, const fltSemantics &amp;Semantics, size_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveRealValue ::= (real4 | real8 | real10) [ expression (, expression)* ] <a href="#ada7465acb55dc7210ef172dfd3ee6a7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02fde01466157a9db0ed84786e066d9">parseRealInstList</a> (const fltSemantics &amp;Semantics, SmallVectorImpl&lt; APInt &gt; &amp;Values, const AsmToken::TokenKind EndToken=AsmToken::EndOfStatement)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a49f76ed7dde17dd2651b924e24b289">parseDirectiveNamedRealValue</a> (StringRef TypeName, const fltSemantics &amp;Semantics, unsigned Size, StringRef Name, SMLoc NameLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveNamedRealValue ::= name (real4 | real8 | real10) [ expression (, expression)* ] <a href="#a6a49f76ed7dde17dd2651b924e24b289">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341c92469f1c16f767408ead3b9de6be">parseOptionalAngleBracketOpen</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2686cf8e123c05bc26de40f383f1983">parseAngleBracketClose</a> (const Twine &amp;Msg="expected '&gt;'")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9fd8885ddc478e31ea6c5e7b904154">parseFieldInitializer</a> (const FieldInfo &amp;Field, FieldInitializer &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ac15e7f820b9605fb9784994976d1f5">parseFieldInitializer</a> (const FieldInfo &amp;Field, const IntFieldInfo &amp;Contents, FieldInitializer &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d79a3e2a5080e4d93c9026ecdeaf32d">parseFieldInitializer</a> (const FieldInfo &amp;Field, const RealFieldInfo &amp;Contents, FieldInitializer &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47bb6e75f21fa5cfcd75d3eccf555fa2">parseFieldInitializer</a> (const FieldInfo &amp;Field, const StructFieldInfo &amp;Contents, FieldInitializer &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1690d007dc0459f89300ab353e4f5b8">parseStructInitializer</a> (const StructInfo &amp;Structure, StructInitializer &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad10016a91b3f44031b4e6043f95dbd2a">parseStructInstList</a> (const StructInfo &amp;Structure, std::vector&lt; StructInitializer &gt; &amp;Initializers, const AsmToken::TokenKind EndToken=AsmToken::EndOfStatement)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe01254479ec104363c6b7875595a1d5">emitFieldValue</a> (const FieldInfo &amp;Field)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6e423a6b2fb5ff04965d8f1e7cd99c5">emitFieldValue</a> (const FieldInfo &amp;Field, const IntFieldInfo &amp;Contents)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a94b43703065760acd377b38619c407">emitFieldValue</a> (const FieldInfo &amp;Field, const RealFieldInfo &amp;Contents)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acadbeed70ca66d303433e5a96a56d55a">emitFieldValue</a> (const FieldInfo &amp;Field, const StructFieldInfo &amp;Contents)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe614477db3d32d323b211ddce4c7fa">emitFieldInitializer</a> (const FieldInfo &amp;Field, const FieldInitializer &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b2ff638adff11ea9ecfb94809b11fb">emitFieldInitializer</a> (const FieldInfo &amp;Field, const IntFieldInfo &amp;Contents, const IntFieldInfo &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78f08b7db4701ad016b69373d835f19b">emitFieldInitializer</a> (const FieldInfo &amp;Field, const RealFieldInfo &amp;Contents, const RealFieldInfo &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391e5c63736c22fc48d24875bcadcce4">emitFieldInitializer</a> (const FieldInfo &amp;Field, const StructFieldInfo &amp;Contents, const StructFieldInfo &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b06167ffd8b67fb2ed0e4cd9d3f0904">emitStructInitializer</a> (const StructInfo &amp;Structure, const StructInitializer &amp;Initializer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59eac94c837bb806a445e9d87d25a549">emitStructValues</a> (const StructInfo &amp;Structure, unsigned *Count=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e0de4e9cabb3a6ad1223b6e8ef0a38">addStructField</a> (StringRef Name, const StructInfo &amp;Structure)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a827ed3b344fb3e2795de89307b162575">parseDirectiveStructValue</a> (const StructInfo &amp;Structure, StringRef Directive, SMLoc DirLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveStructValue ::= struct-id (&lt;struct-initializer&gt; | {struct-initializer}) [, (&lt;struct-initializer&gt; | {struct-initializer})]* <a href="#a827ed3b344fb3e2795de89307b162575">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767c999aed4edef34c07b50c8b4e56f3">parseDirectiveNamedStructValue</a> (const StructInfo &amp;Structure, StringRef Directive, SMLoc DirLoc, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveNamedValue ::= name (byte | word | ... ) [ expression (, expression)* ] <a href="#a767c999aed4edef34c07b50c8b4e56f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24801f84e5a228e61b56066615a4d220">parseDirectiveEquate</a> (StringRef IDVal, StringRef Name, DirectiveKind DirKind, SMLoc NameLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEquate: ::= name "=" expression | name "equ" expression (not redefinable) | name "equ" text-list | name "textequ" text-list (redefinability unspecified) <a href="#a24801f84e5a228e61b56066615a4d220">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5007f550384ecc62b05ffb7a2f20e982">parseDirectiveOrg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveOrg ::= org expression <a href="#a5007f550384ecc62b05ffb7a2f20e982">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac098d71d14c076b5568f86ea8d370137">emitAlignTo</a> (int64_t Alignment)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78f9b89a8fb433220ce2f5f13c5e7d7">parseDirectiveAlign</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveAlign ::= align expression <a href="#aa78f9b89a8fb433220ce2f5f13c5e7d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd0d03781403a84b3e65f14afb21ba00">parseDirectiveEven</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEven ::= even <a href="#abd0d03781403a84b3e65f14afb21ba00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19cbb77584cb25ac6d8b8d9b4f3a1af1">parseDirectiveFile</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveFile ::= .file filename ::= .file number [directory] filename [md5 checksum] [source source-text] <a href="#a19cbb77584cb25ac6d8b8d9b4f3a1af1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096010c2299914b7078e987c3d5570fe">parseDirectiveLine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveLine ::= .line [number] <a href="#a096010c2299914b7078e987c3d5570fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bb0dde0b0118b01e71bf551e3d131bc">parseDirectiveLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveLoc ::= .loc FileNumber [LineNumber] [ColumnPos] [basic_block] [prologue_end] [epilogue_begin] [is_stmt VALUE] [isa VALUE] The first number is a file number, must have been previously assigned with a .file directive, the second number is the line number and optionally the third number is a column position (zero if not specified). <a href="#a4bb0dde0b0118b01e71bf551e3d131bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c91af5a619958e573507255496c3b67">parseDirectiveStabs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveStabs ::= .stabs string, number, number, number <a href="#a0c91af5a619958e573507255496c3b67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6adf18bf0f4ece092f1e25f39d94b18">parseDirectiveCVFile</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFile ::= .cv_file number filename [checksum] [checksumkind] <a href="#ad6adf18bf0f4ece092f1e25f39d94b18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c714d9127f81a103b4c1c4f6977c2a0">parseDirectiveCVFuncId</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFuncId ::= .cv_func_id <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> <a href="#a5c714d9127f81a103b4c1c4f6977c2a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a064944aa8e0186dcaf0a6b800c5946d1">parseDirectiveCVInlineSiteId</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVInlineSiteId ::= .cv_inline_site_id <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> "within" IAFunc "inlined_at" IAFile IALine [IACol] <a href="#a064944aa8e0186dcaf0a6b800c5946d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd9b036eae8fe437b8434079c2492f3">parseDirectiveCVLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVLoc ::= .cv_loc <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> FileNumber [LineNumber] [ColumnPos] [prologue_end] [is_stmt VALUE] The first number is a file number, must have been previously assigned with a .file directive, the second number is the line number and optionally the third number is a column position (zero if not specified). <a href="#acdd9b036eae8fe437b8434079c2492f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b84c0ecf3aac96c6e71f2ea3ce6c84">parseDirectiveCVLinetable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVLinetable ::= .cv_linetable <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, FnStart, FnEnd <a href="#a81b84c0ecf3aac96c6e71f2ea3ce6c84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02c4e903becabe700baaefd619a93a4">parseDirectiveCVInlineLinetable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVInlineLinetable ::= .cv_inline_linetable PrimaryFunctionId FileId LineNum FnStart FnEnd <a href="#ab02c4e903becabe700baaefd619a93a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3783e047ff32598c6738e40f77f392b5">parseDirectiveCVDefRange</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVDefRange ::= .cv_def_range RangeStart RangeEnd (GapStart GapEnd)*, bytes* <a href="#a3783e047ff32598c6738e40f77f392b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad756697444d8f507c821c246910bc0b5">parseDirectiveCVString</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVString ::= .cv_stringtable "string" <a href="#ad756697444d8f507c821c246910bc0b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a007c14314414fa24f8e0aacdbcf41f3d">parseDirectiveCVStringTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVStringTable ::= .cv_stringtable <a href="#a007c14314414fa24f8e0aacdbcf41f3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8403caeb1dee73906761f4c4c85beb0e">parseDirectiveCVFileChecksums</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFileChecksums ::= .cv_filechecksums <a href="#a8403caeb1dee73906761f4c4c85beb0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e1837b50f1d07fc18bfdbe9543a500c">parseDirectiveCVFileChecksumOffset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFileChecksumOffset ::= .cv_filechecksumoffset fileno <a href="#a0e1837b50f1d07fc18bfdbe9543a500c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07f047a7ddb19577bd46d3771821ec3">parseDirectiveCVFPOData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCVFPOData ::= .cv_fpo_data procsym <a href="#ad07f047a7ddb19577bd46d3771821ec3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab894c8a5c3acb433249dee41e84b7180">parseDirectiveCFIRegister</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRegister ::= .cfi_register register, register <a href="#ab894c8a5c3acb433249dee41e84b7180">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383be10abc242ae9d7874575457628d8">parseDirectiveCFIWindowSave</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIWindowSave ::= .cfi_window_save <a href="#a383be10abc242ae9d7874575457628d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc3e09b70a01caecd0fe7fcaf6a4cf6">parseDirectiveCFISections</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFISections ::= .cfi_sections section [, section] <a href="#afbc3e09b70a01caecd0fe7fcaf6a4cf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a651df80c41f7b3a1c537bddf8f544">parseDirectiveCFIStartProc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIStartProc ::= .cfi_startproc [simple] <a href="#a69a651df80c41f7b3a1c537bddf8f544">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4c099f73b0affe8f8b082f19f4db34">parseDirectiveCFIEndProc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIEndProc ::= .cfi_endproc <a href="#afc4c099f73b0affe8f8b082f19f4db34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d04451cea48d74c39f47e629d8554a6">parseDirectiveCFIDefCfaOffset</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIDefCfaOffset ::= .cfi_def_cfa_offset offset <a href="#a2d04451cea48d74c39f47e629d8554a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b731a8bfdd35c6aa4b49725bee269a">parseDirectiveCFIDefCfa</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIDefCfa ::= .cfi_def_cfa register, offset <a href="#a55b731a8bfdd35c6aa4b49725bee269a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada127802f0af8e94518c70083c81218c">parseDirectiveCFIAdjustCfaOffset</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIAdjustCfaOffset ::= .cfi_adjust_cfa_offset adjustment <a href="#ada127802f0af8e94518c70083c81218c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb839747e1473fe8e6b0fd3c5bc6b885">parseDirectiveCFIDefCfaRegister</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIDefCfaRegister ::= .cfi_def_cfa_register register <a href="#afb839747e1473fe8e6b0fd3c5bc6b885">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c30d86fd71e5ce6c7cdf09d1e554587">parseDirectiveCFIOffset</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIOffset ::= .cfi_offset register, offset <a href="#a5c30d86fd71e5ce6c7cdf09d1e554587">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2acc087a4b4eedf420d1d679982f5f6e">parseDirectiveCFIRelOffset</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRelOffset ::= .cfi_rel_offset register, offset <a href="#a2acc087a4b4eedf420d1d679982f5f6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92debdcb1e6ba3e643933fbce81f712d">parseDirectiveCFIPersonalityOrLsda</a> (bool IsPersonality)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIPersonalityOrLsda IsPersonality true for cfi_personality, false for cfi_lsda ::= .cfi_personality encoding, [symbol_name] ::= .cfi_lsda encoding, [symbol_name] <a href="#a92debdcb1e6ba3e643933fbce81f712d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08beee4a4873fb3a77d1b946384354a8">parseDirectiveCFIRememberState</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRememberState ::= .cfi_remember_state <a href="#a08beee4a4873fb3a77d1b946384354a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a022fa4083ad1ab0244b650de5101ee">parseDirectiveCFIRestoreState</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRestoreState ::= .cfi_remember_state <a href="#a4a022fa4083ad1ab0244b650de5101ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46d3a2eb455369ec6743ed6e03682ea">parseDirectiveCFISameValue</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFISameValue ::= .cfi_same_value register <a href="#ab46d3a2eb455369ec6743ed6e03682ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e1528ddc895216b5b7e005020a140e">parseDirectiveCFIRestore</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIRestore ::= .cfi_restore register <a href="#a70e1528ddc895216b5b7e005020a140e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae0fa2705cc39e013220b63c587268f">parseDirectiveCFIEscape</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIEscape ::= .cfi_escape expression[,...] <a href="#a7ae0fa2705cc39e013220b63c587268f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a503ae2f1762b6601a960f58d6645efb7">parseDirectiveCFIReturnColumn</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIReturnColumn ::= .cfi_return_column register <a href="#a503ae2f1762b6601a960f58d6645efb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb89781f06dce5ce8507775cbb3722e">parseDirectiveCFISignalFrame</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFISignalFrame ::= .cfi_signal_frame <a href="#a3cb89781f06dce5ce8507775cbb3722e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3e390c66f767b208f3088a33c9575c">parseDirectiveCFIUndefined</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveCFIUndefined ::= .cfi_undefined register <a href="#a8b3e390c66f767b208f3088a33c9575c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cacecd0a66d343748f3ec1f60c0d758">parseDirectivePurgeMacro</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectivePurgeMacro ::= purge identifier ( , identifier )* <a href="#a3cacecd0a66d343748f3ec1f60c0d758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bde4078077c0482b51f4172735fef75">parseDirectiveExitMacro</a> (SMLoc DirectiveLoc, StringRef Directive, std::string &amp;Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveExitMacro ::= "exitm" [textitem] <a href="#a3bde4078077c0482b51f4172735fef75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bd68caeef836f3c1e0db6115478e1d">parseDirectiveEndMacro</a> (StringRef Directive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEndMacro ::= endm <a href="#ad1bd68caeef836f3c1e0db6115478e1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5cd62c89476e9983e7433f24d8a9e49">parseDirectiveMacro</a> (StringRef Name, SMLoc NameLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveMacro ::= name macro [parameters] ["LOCAL" identifiers] parameters ::= parameter [, parameter]* parameter ::= name ":" qualifier qualifier ::= "req" | "vararg" | "=" macro_argument <a href="#aa5cd62c89476e9983e7433f24d8a9e49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667a08aa29c20544687179ecb27cc2ad">parseDirectiveStruct</a> (StringRef Directive, DirectiveKind DirKind, StringRef Name, SMLoc NameLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveStruct ::= &lt;name&gt; (STRUC | STRUCT | UNION) [fieldAlign] [, NONUNIQUE] (dataDir | generalDir | offsetDir | nestedStruct)+ &lt;name&gt; ENDS <a href="#a667a08aa29c20544687179ecb27cc2ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49ca0b9d6385dd275d9d02da660ded59">parseDirectiveNestedStruct</a> (StringRef Directive, DirectiveKind DirKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveNestedStruct ::= (STRUC | STRUCT | UNION) [name] (dataDir | generalDir | offsetDir | nestedStruct)+ ENDS <a href="#a49ca0b9d6385dd275d9d02da660ded59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a01d10813755283e3bc39bb97303880">parseDirectiveEnds</a> (StringRef Name, SMLoc NameLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926b066e23651843f3f0f5cbfcf10437">parseDirectiveNestedEnds</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4f0be8c7a2cc5213b0a68e29e014b0">parseDirectiveExtern</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae85e6333889e3ef3ce494a6899422e1c">parseDirectiveSymbolAttribute</a> (MCSymbolAttr Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a directive like ".globl" which accepts a single symbol (which should be a label or an external). <a href="#ae85e6333889e3ef3ce494a6899422e1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7056ca175910e7e195d38b976b64f4a1">parseDirectiveComm</a> (bool IsLocal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveComm ::= ( .comm | .lcomm ) identifier , size_expression [ , align_expression ] <a href="#a7056ca175910e7e195d38b976b64f4a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c71ac3f332dec5a0e8dc467441844c9">parseDirectiveComment</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveComment ::= comment delimiter [[text]] [[text]] [[text]] delimiter [[text]] <a href="#a8c71ac3f332dec5a0e8dc467441844c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1623bc2bac9901c02009c9b07344c220">parseDirectiveInclude</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveInclude ::= include &lt;filename&gt; | include filename <a href="#a1623bc2bac9901c02009c9b07344c220">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af83dc9a4855dedcc92c3b5dc6bf719da">parseDirectiveIf</a> (SMLoc DirectiveLoc, DirectiveKind DirKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIf ::= .if{,eq,ge,gt,le,lt,ne} expression <a href="#af83dc9a4855dedcc92c3b5dc6bf719da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65a40b647df2bc364d0c8d8e83560f90">parseDirectiveIfb</a> (SMLoc DirectiveLoc, bool ExpectBlank)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIfb ::= .ifb textitem <a href="#a65a40b647df2bc364d0c8d8e83560f90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab910fa6af4676929a21f14329b6dcb1a">parseDirectiveIfidn</a> (SMLoc DirectiveLoc, bool ExpectEqual, bool CaseInsensitive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIfidn ::= ifidn textitem, textitem <a href="#ab910fa6af4676929a21f14329b6dcb1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab355ea45d6c554f67476f824ae724492">parseDirectiveIfdef</a> (SMLoc DirectiveLoc, bool expect_defined)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIfdef ::= ifdef symbol | ifdef variable <a href="#ab355ea45d6c554f67476f824ae724492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8271588212dcfc612f4b507af8428de">parseDirectiveElseIf</a> (SMLoc DirectiveLoc, DirectiveKind DirKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveElseIf ::= elseif expression <a href="#aa8271588212dcfc612f4b507af8428de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c93d6e3328b576857fec4229702f9a7">parseDirectiveElseIfb</a> (SMLoc DirectiveLoc, bool ExpectBlank)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveElseIfb ::= elseifb textitem <a href="#a2c93d6e3328b576857fec4229702f9a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2685e9100d6b29fc13f69238c8a8983f">parseDirectiveElseIfdef</a> (SMLoc DirectiveLoc, bool expect_defined)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveElseIfdef ::= elseifdef symbol | elseifdef variable <a href="#a2685e9100d6b29fc13f69238c8a8983f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac33f17498ead0b25237c44596d63d815">parseDirectiveElseIfidn</a> (SMLoc DirectiveLoc, bool ExpectEqual, bool CaseInsensitive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveElseIfidn ::= elseifidn textitem, textitem <a href="#ac33f17498ead0b25237c44596d63d815">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac319ee593ef6ae02e26496ccd6a36cd7">parseDirectiveElse</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveElse ::= else <a href="#ac319ee593ef6ae02e26496ccd6a36cd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2942c8abaa99183a21f596095c1f600c">parseDirectiveEndIf</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEndIf ::= .endif <a href="#a2942c8abaa99183a21f596095c1f600c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23756b1b8e93f17b4a152cb04a84b716">parseEscapedString</a> (std::string &amp;Data) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the current token as a string which may include escaped characters and return the string contents. <a href="#a23756b1b8e93f17b4a152cb04a84b716">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab072c67afc063ea45e6d55211ac97f56">parseAngleBracketString</a> (std::string &amp;Data) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an angle-bracket delimited string at the current position if one is present, returning the string contents. <a href="#ab072c67afc063ea45e6d55211ac97f56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41615a2a483ce292d16dc86b8910e644">parseMacroLikeBody</a> (SMLoc DirectiveLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8822b08540880a86a5e9cca7862d11">instantiateMacroLikeBody</a> (MCAsmMacro *M, SMLoc DirectiveLoc, raw_svector_ostream &amp;OS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8916a86c5e9048c9baface5478835aa">instantiateMacroLikeBody</a> (MCAsmMacro *M, SMLoc DirectiveLoc, SMLoc ExitLoc, raw_svector_ostream &amp;OS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d550c0301db14892995f3e8f8ff1d01">parseDirectiveRepeat</a> (SMLoc DirectiveLoc, StringRef Directive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveRepeat ::= ("repeat" | "rept") count body endm <a href="#a5d550c0301db14892995f3e8f8ff1d01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab901e6531ed5f9e00d9622f79803ebc7">parseDirectiveFor</a> (SMLoc DirectiveLoc, StringRef Directive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveFor ::= ("for" | "irp") symbol [":" qualifier], &lt;values&gt; body endm <a href="#ab901e6531ed5f9e00d9622f79803ebc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf58cbf0a69214103987f166f96bad6">parseDirectiveForc</a> (SMLoc DirectiveLoc, StringRef Directive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveForc ::= ("forc" | "irpc") symbol, &lt;string&gt; body endm <a href="#a2cf58cbf0a69214103987f166f96bad6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf468d32d374c005269c5b5d72ae676a">parseDirectiveWhile</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveWhile ::= "while" expression body endm <a href="#acf468d32d374c005269c5b5d72ae676a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc920ac21710bca7d83d26c04a1e027">parseDirectiveMSEmit</a> (SMLoc DirectiveLoc, ParseStatementInfo &amp;Info, size_t Len)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa315c4e442d0443978a371e9231274">parseDirectiveMSAlign</a> (SMLoc DirectiveLoc, ParseStatementInfo &amp;Info)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c8e970efdeea44f4c4977c9784f0953">parseDirectiveEnd</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEnd ::= end <a href="#a8c8e970efdeea44f4c4977c9784f0953">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41356ad52a35e6a661bc858fac9d219">parseDirectiveError</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveError ::= .err [message] <a href="#ac41356ad52a35e6a661bc858fac9d219">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d04ecf45fc102422863b10805a0971">parseDirectiveErrorIfb</a> (SMLoc DirectiveLoc, bool ExpectBlank)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveErrorIfb ::= .errb textitem[, message] <a href="#a52d04ecf45fc102422863b10805a0971">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc51ecbc19ae8a3292ac6c717d3e2de2">parseDirectiveErrorIfdef</a> (SMLoc DirectiveLoc, bool ExpectDefined)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveErrorIfdef ::= .errdef name[, message] <a href="#afc51ecbc19ae8a3292ac6c717d3e2de2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28ecc91775acfc249825eaff9918ac5e">parseDirectiveErrorIfidn</a> (SMLoc DirectiveLoc, bool ExpectEqual, bool CaseInsensitive)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveErrorIfidn ::= .erridn textitem, textitem[, message] <a href="#a28ecc91775acfc249825eaff9918ac5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf8ef76846ba233b94e79ef497b6693">parseDirectiveErrorIfe</a> (SMLoc DirectiveLoc, bool ExpectZero)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveErrorIfe ::= .erre expression[, message] <a href="#a8bf8ef76846ba233b94e79ef497b6693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ef8fbe18bdaaaf927a30392884b7ca">parseDirectiveRadix</a> (SMLoc DirectiveLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae666a8d08fd0382b779055fb4f07d2aa">parseDirectiveEcho</a> (SMLoc DirectiveLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEcho ::= "echo" message <a href="#ae666a8d08fd0382b779055fb4f07d2aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af419e9bd76aeb0900d99d58860ab04d8">initializeDirectiveKindMap</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67f70371a42135c0075b0a7e24def29e">initializeCVDefRangeTypeMap</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4596112d543cb1cb49780035adb21a8c">initializeBuiltinSymbolMap</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74eac762402bc8894cfdb9b4d0390fbc">DiagHandler</a> (const SMDiagnostic &amp;Diag, void *Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>will use the last parsed cpp hash line filename comment for the Filename and LineNo if any in the diagnostic. <a href="#a74eac762402bc8894cfdb9b4d0390fbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The concrete assembly parser instance.</p>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MasmParser() {#a314e31f13f6e31ef75cced99a4e946c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MasmParser::MasmParser (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, struct tm TM, unsigned CB=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afad5b9aac74030a159903f3cf64c481c">llvm::MCAsmParser::HadError</a>.</p>


<p>Referenced by <a href="#a4080ce1e3aceb1e7904ff18196b96e4e">MasmParser</a> and <a href="#a132b6ee69da8751dc4b4ceaf501dbae9">operator=</a>.</p>

</div>
</div>

### MasmParser() {#a4080ce1e3aceb1e7904ff18196b96e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MasmParser.cpp}::MasmParser::MasmParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser">MasmParser</a> &amp;)</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>Reference <a href="#a314e31f13f6e31ef75cced99a4e946c2">MasmParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MasmParser() {#a3b475bb30badf7d39f82d088bc7e45aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MasmParser::~MasmParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afad5b9aac74030a159903f3cf64c481c">llvm::MCAsmParser::HadError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a132b6ee69da8751dc4b4ceaf501dbae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MasmParser &amp; anonymous{MasmParser.cpp}::MasmParser::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser">MasmParser</a> &amp;)</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>Reference <a href="#a314e31f13f6e31ef75cced99a4e946c2">MasmParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAliasForDirective() {#a24dd12008c998554435cec558a45c26a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MasmParser.cpp}::MasmParser::addAliasForDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Alias)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### addDirectiveHandler() {#ad89ebc499fe4187fb52f86729c44316d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MasmParser.cpp}::MasmParser::addDirectiveHandler (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a9ce3532c090e7b66928ff9a42dae508c">ExtensionDirectiveHandler</a> Handler)</td>
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



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### Run() {#a46449244c1f2d4e4b2022d1126e7c5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::Run (bool NoInitialTextSection, bool NoFinalize=false)</td>
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

<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a589edc5876425761e8515d0d03ba9576">llvm::MCContext::addGenDwarfSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="#a19ecdddfce4d05cafad65fa385d17f77">eatToEndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86ef367bc55c7f607d673a9dd38189b3">llvm::MCTargetAsmParser::flushPendingInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="#a8e18d4299230d21094f423f2fdc7fc72">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a>, <a href="#ad17ba7a1f3ebadc9d347d00f9d910c14">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a844102db6a944e0b900e1dcb331cd8ba">llvm::MCContext::getMCDwarfLineTables</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="#a08041d421b04248dc8a9a193868fa850">getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afad5b9aac74030a159903f3cf64c481c">llvm::MCAsmParser::HadError</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a16be3cf71194a82a5cf1d124ebbdc433">llvm::MCContext::hadError</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a4947313871f8935468ae02f6621260c8">llvm::MCAsmParser::hasPendingError</a>, <a href="/web-llvm/docs/api/classes/llvm/asmcond/#ab86a4572bd9b87223e026101d390cb46">llvm::AsmCond::Ignore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2899e74730516967f04d81966bb4f881">llvm::MCSymbol::isDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="#a3606169bb499457fe3acc26441161166">Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a44a59dce1747781c994608fbeffd37c9">llvm::MCTargetAsmParser::onBeginOfFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a93d0e54ca0dae7b1e034284b33df3288">llvm::MCTargetAsmParser::onEndOfFile</a>, <a href="#ac54c7247683fdbcce5c47cf186227d00">printError</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a25158c234ca9e60f3976a36d7d6ef271">llvm::MCAsmParser::printPendingErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a61ee519481ec9d6b36a55212e44a34e6">llvm::MCSection::setBeginSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/asmcond/#ab5ad0559afdf12eaa55b0e4f3165d08b">llvm::AsmCond::TheCond</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ActiveMacros {#a45fbdac199a892556119e0021ad69351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MacroInstantiation*&gt; anonymous{MasmParser.cpp}::MasmParser::ActiveMacros</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stack of active macro instantiations.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### AngleBracketDepth {#af0455ced2955f31767365077ab63bc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MasmParser.cpp}::MasmParser::AngleBracketDepth = 0U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### AssemblerDialect {#a0d17b5422777874a2816fb78e00df3d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MasmParser.cpp}::MasmParser::AssemblerDialect = 1U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AssemblerDialect.</p>


<p>~OU means unset value and use value provided by MAI. Defaults to 1U, meaning Intel.</p>


<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### CppHashInfo {#a65efdff1b8d27c1b87aef5624cf0cf47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CppHashInfoTy anonymous{MasmParser.cpp}::MasmParser::CppHashInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### Ctx {#aafc7cbc8a836e22f9b20db715e7a5c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; anonymous{MasmParser.cpp}::MasmParser::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### CurBuffer {#a4e9baef79719475d6634a1efc71cae3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MasmParser.cpp}::MasmParser::CurBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the current buffer index we're lexing from as managed by the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> object.</p>

<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### DirLabels {#ac82ce61f243eb141399c086f0bb558e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::tuple&lt;SMLoc, CppHashInfoTy, MCSymbol *&gt;, 4&gt; anonymous{MasmParser.cpp}::MasmParser::DirLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of forward directional labels for diagnosis at the end.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### EndStatementAtEOFStack {#a31e3d26998e29fb46ad486c5ca6557f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{MasmParser.cpp}::MasmParser::EndStatementAtEOFStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### ExtensionDirectiveMap {#a6440c63a4d3fa3e8d1b8db6073ca7664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;ExtensionDirectiveHandler&gt; anonymous{MasmParser.cpp}::MasmParser::ExtensionDirectiveMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>maps directive names to handler methods in parser extensions.</p>


<p>Extensions register themselves in this map by calling addDirectiveHandler.</p>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### FirstCppHashFilename {#aeb70ada1beb78b552ccb7b583b4827f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MasmParser.cpp}::MasmParser::FirstCppHashFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The filename from the first cpp hash file line comment, if any.</p>

<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### IsDarwin {#a04169434184405235c96db83dfd60bd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MasmParser.cpp}::MasmParser::IsDarwin = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>is Darwin compatibility enabled?</p>

<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### KnownType {#a32a59d0f84bb6a1adf4baba583a78b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;AsmTypeInfo&gt; anonymous{MasmParser.cpp}::MasmParser::KnownType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps data location names to types.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### Lexer {#ae312499fb091ba834bb7ac58984d2252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmLexer anonymous{MasmParser.cpp}::MasmParser::Lexer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### LocalCounter {#a6826b5f51f429ae2fbf4c827586999ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t anonymous{MasmParser.cpp}::MasmParser::LocalCounter = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### MacroLikeBodies {#a5aef886429821d411d7c3af4e9a0d6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;MCAsmMacro&gt; anonymous{MasmParser.cpp}::MasmParser::MacroLikeBodies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of bodies of anonymous macros.</p>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### MAI {#acad40faf72ff0e1c0931c4e84b787401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo&amp; anonymous{MasmParser.cpp}::MasmParser::MAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### NumOfMacroInstantiations {#aec646d26913c5d68a9a8a5a9259f3339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MasmParser.cpp}::MasmParser::NumOfMacroInstantiations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of how many .macro's have been instantiated.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### Out {#aa4b1085973bc6d95bc373e654d24e695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer&amp; anonymous{MasmParser.cpp}::MasmParser::Out</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### ParsingMSInlineAsm {#a32079f2281b284adc179fd8f3b7003ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MasmParser.cpp}::MasmParser::ParsingMSInlineAsm = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Are we parsing ms-style inline assembly?</p>

<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### PlatformParser {#afa33fc10f385d7ed5bf28b8f83b8a064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCAsmParserExtension&gt; anonymous{MasmParser.cpp}::MasmParser::PlatformParser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### ReportedInconsistentMD5 {#aecf488f11cfc90483a3d6b580a2efee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MasmParser.cpp}::MasmParser::ReportedInconsistentMD5 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Did we already inform the user about inconsistent <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> usage?</p>

<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### SavedDiagContext {#a593150ae7466969b1ac7a520413ef831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* anonymous{MasmParser.cpp}::MasmParser::SavedDiagContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### SavedDiagHandler {#af7b2a70e20323d3db5ac448367862344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr::DiagHandlerTy anonymous{MasmParser.cpp}::MasmParser::SavedDiagHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### SrcMgr {#a63d742da6d24d493c57a9d8433b30745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr&amp; anonymous{MasmParser.cpp}::MasmParser::SrcMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### StructInProgress {#a674216c44ded1603cd0e52354305cb06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StructInfo, 1&gt; anonymous{MasmParser.cpp}::MasmParser::StructInProgress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stack of active struct definitions.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### Structs {#add885649802bf9142f72ea1466ba1ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;StructInfo&gt; anonymous{MasmParser.cpp}::MasmParser::Structs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps struct tags to struct definitions.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### TheCondStack {#abca56e7d16ec7a99a7538cf91cf84ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AsmCond&gt; anonymous{MasmParser.cpp}::MasmParser::TheCondStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### TheCondState {#a5bc42975e59400a499b33a677300d533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmCond anonymous{MasmParser.cpp}::MasmParser::TheCondState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### TM {#a4bf61e44dfe7a135550980e7a6d8e0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct tm anonymous{MasmParser.cpp}::MasmParser::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>time of assembly</p>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### Variables {#a5b4c398b4d0d686ff5bfc8f34b9e7ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;Variable&gt; anonymous{MasmParser.cpp}::MasmParser::Variables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## MCAsmParser Interface



<p>{</p>


### addIntegralField {#a4bb8a5cb4d24a709b401e2df99d9792d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::addIntegralField (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### addRealField {#ab3c37a9325928495237a3050dfbe4f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::addRealField (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### addStructField {#a30e0de4e9cabb3a6ad1223b6e8ef0a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::addStructField (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a> &amp; Structure)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### BuiltinSymbol {#a064df5a0f44746675d5b115d7d103f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MasmParser.cpp}::MasmParser::BuiltinSymbol </td>
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
<td class="doxyEnumItemName">BI_NO_SYMBOL<a id="a064df5a0f44746675d5b115d7d103f59a988b9d6ab38c7f1c00deaf2de1bd1709"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_DATE<a id="a064df5a0f44746675d5b115d7d103f59a9f982c51a77e6f8a3aa37a2b1809a034"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_TIME<a id="a064df5a0f44746675d5b115d7d103f59a5e1a4864966a5b7443fc7da65ce78fd7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_VERSION<a id="a064df5a0f44746675d5b115d7d103f59a9f16f8fb4ea0312e1a3c8daeb5c280b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_FILECUR<a id="a064df5a0f44746675d5b115d7d103f59ac37af7a9d106612ef04df6a24895fc25"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_FILENAME<a id="a064df5a0f44746675d5b115d7d103f59a8e425d6fea57ab0b682f8f1c0f6e752e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_LINE<a id="a064df5a0f44746675d5b115d7d103f59a2a551a90e402bbee649668e260c9541f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_CURSEG<a id="a064df5a0f44746675d5b115d7d103f59a4922920fb9af2dbdb7dee478d046c988"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_CPU<a id="a064df5a0f44746675d5b115d7d103f59ab6b69ce42d6f71b1072725857b065aa0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_INTERFACE<a id="a064df5a0f44746675d5b115d7d103f59a9ee70682096dcde880a632badbd2e4c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_CODE<a id="a064df5a0f44746675d5b115d7d103f59a221d12e1000f112e0e65befa730a3434"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_DATA<a id="a064df5a0f44746675d5b115d7d103f59aedc2e9971a89995bd6d3e040bd30cb6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_FARDATA<a id="a064df5a0f44746675d5b115d7d103f59ac0970270162b0205b23cf0b27fd3865b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_WORDSIZE<a id="a064df5a0f44746675d5b115d7d103f59a3b2b2d7f0a76519bbd2e70a0f5d39743"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_CODESIZE<a id="a064df5a0f44746675d5b115d7d103f59ae5baf68fbf6e06a834df90a64914a5f3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_DATASIZE<a id="a064df5a0f44746675d5b115d7d103f59a77e270c74182a567721d4ba922ad8838"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_MODEL<a id="a064df5a0f44746675d5b115d7d103f59a1be568dcafa75130b38726f42b5c8b49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BI_STACK<a id="a064df5a0f44746675d5b115d7d103f59a6a0f4116d21ae69a71db05a3b9de7a5b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### BuiltinSymbolMap {#a4a338f6b11f7553687ac9a8e870842ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;BuiltinSymbol&gt; anonymous{MasmParser.cpp}::MasmParser::BuiltinSymbolMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps builtin name --&gt; BuiltinSymbol enum, for builtins handled by this class.</p>

<p>Definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### checkForValidSection {#a10d982772a36fe8255164eced5dd71bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::checkForValidSection ()</td>
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


<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a08041d421b04248dc8a9a193868fa850">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>.</p>

</div>
</div>

### CVDefRangeType {#ae3cede150e95aa800f01c276994eb1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MasmParser.cpp}::MasmParser::CVDefRangeType </td>
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
<td class="doxyEnumItemName">CVDR_DEFRANGE<a id="ae3cede150e95aa800f01c276994eb1e5a485481628187e13f9523489164b3fbaa"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVDR_DEFRANGE_REGISTER<a id="ae3cede150e95aa800f01c276994eb1e5a0d0c30203afedf12cf56e80e0e97cfed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVDR_DEFRANGE_FRAMEPOINTER_REL<a id="ae3cede150e95aa800f01c276994eb1e5ad742d926a0a111aac0b70f9249e77ad9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVDR_DEFRANGE_SUBFIELD_REGISTER<a id="ae3cede150e95aa800f01c276994eb1e5a9275c5d0ca6788ca923f693347b93474"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVDR_DEFRANGE_REGISTER_REL<a id="ae3cede150e95aa800f01c276994eb1e5ab2c2d4af944031c4d59bbdc42a9a32ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### CVDefRangeTypeMap {#a64aceefe6cce901f701da140aef3f8e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;CVDefRangeType&gt; anonymous{MasmParser.cpp}::MasmParser::CVDefRangeTypeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps Codeview def_range types --&gt; CVDefRangeType enum, for Codeview def_range types parsed by this class.</p>

<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### defineMacro {#ae39bffc615ea979f44a25c730094bbb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::defineMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a> and <a href="#a08f88c883adc92a0b9eacbc5a4064d2b">Warning</a>.</p>

</div>
</div>

### DiagHandler {#a74eac762402bc8894cfdb9b4d0390fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::DiagHandler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Diag, void * Context)</td>
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

<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### DirectiveKind {#a0f7d9f989d988b78677af2e3f888f33a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MasmParser.cpp}::MasmParser::DirectiveKind </td>
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
<td class="doxyEnumItemName">DK_NO_DIRECTIVE<a id="a0f7d9f989d988b78677af2e3f888f33aa374af616694c26d6d0560baa2e997870"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_HANDLER_DIRECTIVE<a id="a0f7d9f989d988b78677af2e3f888f33aa6fc2d99fd4cc9cf5b083305b36cb825f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ASSIGN<a id="a0f7d9f989d988b78677af2e3f888f33aa94f56a8be98ee2f0b09bd7ebc0734c7f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_EQU<a id="a0f7d9f989d988b78677af2e3f888f33aaf10de7e5060282c52b4eba333eb35844"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_TEXTEQU<a id="a0f7d9f989d988b78677af2e3f888f33aaa1a8bb01949b74f0101205364186bb98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ASCII<a id="a0f7d9f989d988b78677af2e3f888f33aa43850dbe0f35369c68bd0d6a29e81def"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ASCIZ<a id="a0f7d9f989d988b78677af2e3f888f33aaa0f99bc1ed98e54930757a9a2cf7d23a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_STRING<a id="a0f7d9f989d988b78677af2e3f888f33aa0aee6b9e2e0569269f4129c228b1dbba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_BYTE<a id="a0f7d9f989d988b78677af2e3f888f33aa40c5d197a99abe1a448cafbd902b0f15"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SBYTE<a id="a0f7d9f989d988b78677af2e3f888f33aa3936ec2cbb4896812b61c55a9f3db4ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_WORD<a id="a0f7d9f989d988b78677af2e3f888f33aa448ff9a4613b4266e915db34c8c0123a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SWORD<a id="a0f7d9f989d988b78677af2e3f888f33aa1560148c77b8ea8598ffc6677e7363ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DWORD<a id="a0f7d9f989d988b78677af2e3f888f33aaab5af175d0fefa475a6110320542d105"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SDWORD<a id="a0f7d9f989d988b78677af2e3f888f33aa1c224c6bf79f91c8969601da1bb5f661"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_FWORD<a id="a0f7d9f989d988b78677af2e3f888f33aaf72005ac3dc2bdceb6f5f6c859bf05b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_QWORD<a id="a0f7d9f989d988b78677af2e3f888f33aa0874493a1d988afe4c562dbcc8aad872"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SQWORD<a id="a0f7d9f989d988b78677af2e3f888f33aa617bfa77f929ab1ea50de56013795a03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DB<a id="a0f7d9f989d988b78677af2e3f888f33aa84f2e09ae6c029ce128988956135fc31"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DD<a id="a0f7d9f989d988b78677af2e3f888f33aa7ff3e96c4e47cd2f86f74ddeb9d0be98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DF<a id="a0f7d9f989d988b78677af2e3f888f33aa130e1fbb6374a9a6acd08379003277cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DQ<a id="a0f7d9f989d988b78677af2e3f888f33aa97bf83383b2ea1374904dca593d57803"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_DW<a id="a0f7d9f989d988b78677af2e3f888f33aa2f01cc3ec0a1bfbbb4b716caf4716913"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_REAL4<a id="a0f7d9f989d988b78677af2e3f888f33aa6a01bedcef0e3eeda541b27370fe344d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_REAL8<a id="a0f7d9f989d988b78677af2e3f888f33aa6c195799186feab27c4ecc776e463a0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_REAL10<a id="a0f7d9f989d988b78677af2e3f888f33aa8c484633bfdf663d7ea209c3af17ed55"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ALIGN<a id="a0f7d9f989d988b78677af2e3f888f33aad24044b0bb9d2980331fde356c3eb731"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_EVEN<a id="a0f7d9f989d988b78677af2e3f888f33aa409c42601850ed857d439b3c03468759"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ORG<a id="a0f7d9f989d988b78677af2e3f888f33aaeedc4f893ce1b583dd68a4c13b588e24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ENDR<a id="a0f7d9f989d988b78677af2e3f888f33aa4a2478495a987bd2b0653cbceab9410e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_EXTERN<a id="a0f7d9f989d988b78677af2e3f888f33aa86c2abcb310e60569ac7002009a97ede"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_PUBLIC<a id="a0f7d9f989d988b78677af2e3f888f33aa1dd54e6e1b1b0428886dd83a22217f95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_COMM<a id="a0f7d9f989d988b78677af2e3f888f33aae8c81e5a59d56395f8ab2c78fd3baf30"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_COMMENT<a id="a0f7d9f989d988b78677af2e3f888f33aae62345e371de9a8963a75e872b1e716a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_INCLUDE<a id="a0f7d9f989d988b78677af2e3f888f33aa7af9494ea8ea0c4b5c3dcb4daef3030a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_REPEAT<a id="a0f7d9f989d988b78677af2e3f888f33aaed6b71c4eafaa02476d119bafae16dc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_WHILE<a id="a0f7d9f989d988b78677af2e3f888f33aaefc4bb1ad73fbc9c69e284b91d1f4df8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_FOR<a id="a0f7d9f989d988b78677af2e3f888f33aa093542b58400acbc30c531a24c7ff033"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_FORC<a id="a0f7d9f989d988b78677af2e3f888f33aafd67d48fd123c8176cd468768a3a3544"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IF<a id="a0f7d9f989d988b78677af2e3f888f33aaa3df3bd5d9ce70c11f39300b7efced54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFE<a id="a0f7d9f989d988b78677af2e3f888f33aadeff4ad10790c7e07bfc0c999f75e70e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFB<a id="a0f7d9f989d988b78677af2e3f888f33aa4838a173ab0d76efc1c5f1ee116b0434"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFNB<a id="a0f7d9f989d988b78677af2e3f888f33aa83deba791d4acf4f5c3832993f0b8bca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFDEF<a id="a0f7d9f989d988b78677af2e3f888f33aa56e8c298f93d5a1ed03786bfaccc33f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFNDEF<a id="a0f7d9f989d988b78677af2e3f888f33aacce5cab0b947f5d264d65cdee8a613a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFDIF<a id="a0f7d9f989d988b78677af2e3f888f33aad359b08c3e863bf7e47c2e20b14ce082"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFDIFI<a id="a0f7d9f989d988b78677af2e3f888f33aa6c70cececd8cfeb3627f2aa71c173865"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFIDN<a id="a0f7d9f989d988b78677af2e3f888f33aa2ebdc202eefc10ad3bbcde521d44f124"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_IFIDNI<a id="a0f7d9f989d988b78677af2e3f888f33aa022cc96e882e378d918091a3020befc7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIF<a id="a0f7d9f989d988b78677af2e3f888f33aa950d7ae84a6a280ae18a7a0da0549cb7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIFE<a id="a0f7d9f989d988b78677af2e3f888f33aa48f0b4676a0c4dee1d0090b4bbe71c27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIFB<a id="a0f7d9f989d988b78677af2e3f888f33aa3a447a8fbc3fa3274ddea091574ff51a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIFNB<a id="a0f7d9f989d988b78677af2e3f888f33aa6f19430e3410470da4c999f72107eb87"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIFDEF<a id="a0f7d9f989d988b78677af2e3f888f33aadd3f617b4d040358c69f5aa333072972"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIFNDEF<a id="a0f7d9f989d988b78677af2e3f888f33aac3e2728474da31d0d5bbe11623958d94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIFDIF<a id="a0f7d9f989d988b78677af2e3f888f33aa26ace1109a15ce86d92decf52b496d6b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIFDIFI<a id="a0f7d9f989d988b78677af2e3f888f33aae832a672b1e6c883a47f5814191b5cf2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIFIDN<a id="a0f7d9f989d988b78677af2e3f888f33aaaa466b3f36042301fd4ee39720388267"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSEIFIDNI<a id="a0f7d9f989d988b78677af2e3f888f33aad6f096d506352fff79364463a3d795fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ELSE<a id="a0f7d9f989d988b78677af2e3f888f33aa5e1f492299dde03f78bca543b6b481ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ENDIF<a id="a0f7d9f989d988b78677af2e3f888f33aa580e2edffee3372355667fe4976f8547"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_FILE<a id="a0f7d9f989d988b78677af2e3f888f33aad2d05b9f5d8953f7f655078230fd4349"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LINE<a id="a0f7d9f989d988b78677af2e3f888f33aa482140d09b7f29a85202d3a8e2df2eee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_LOC<a id="a0f7d9f989d988b78677af2e3f888f33aa62604a19957f48fa64be9b86258cd34c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_STABS<a id="a0f7d9f989d988b78677af2e3f888f33aa57c0316b1168ef6a288d6613bc1ea7f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FILE<a id="a0f7d9f989d988b78677af2e3f888f33aa5fcdc436ab26ecaf86022d5d85392625"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FUNC_ID<a id="a0f7d9f989d988b78677af2e3f888f33aac32203e71b17e90cdef1f55f300f8a4f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_INLINE_SITE_ID<a id="a0f7d9f989d988b78677af2e3f888f33aaf9f4b0eb31aa139e847ae5b1393851ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_LOC<a id="a0f7d9f989d988b78677af2e3f888f33aa547fb52bdb508758253ed66193f88574"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_LINETABLE<a id="a0f7d9f989d988b78677af2e3f888f33aa59ed13a1ac366746d5a6b2713b4ffbfc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_INLINE_LINETABLE<a id="a0f7d9f989d988b78677af2e3f888f33aae2eb60de16c7cc9e50435678b5ce6402"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_DEF_RANGE<a id="a0f7d9f989d988b78677af2e3f888f33aa0638fb44b5ab8e8e6f22f808fc3c496e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_STRINGTABLE<a id="a0f7d9f989d988b78677af2e3f888f33aa6ae0e8848b96123cae8325d3192fc3cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_STRING<a id="a0f7d9f989d988b78677af2e3f888f33aa47d7ba925c2edb9fb885ed3a74f401fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FILECHECKSUMS<a id="a0f7d9f989d988b78677af2e3f888f33aac5b6a1d7bfbe051fea9f8186c7b28d98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FILECHECKSUM_OFFSET<a id="a0f7d9f989d988b78677af2e3f888f33aa05f5d99e91ce29e16bd8053ea1e280a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CV_FPO_DATA<a id="a0f7d9f989d988b78677af2e3f888f33aac397c07031be85d4fb9def67f9e12a13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_SECTIONS<a id="a0f7d9f989d988b78677af2e3f888f33aab4b9fdac5a988779d7cd2ee71d397c49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_STARTPROC<a id="a0f7d9f989d988b78677af2e3f888f33aa416ac634ef260ab94be8c7adb2bc2303"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_ENDPROC<a id="a0f7d9f989d988b78677af2e3f888f33aab08951f8333c9cca48d70cea89dd0bf5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_DEF_CFA<a id="a0f7d9f989d988b78677af2e3f888f33aa1d9cab672ae7a3e105952b136d1ea458"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_DEF_CFA_OFFSET<a id="a0f7d9f989d988b78677af2e3f888f33aacf68e8e8b0643fcd883694ffeda7db82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_ADJUST_CFA_OFFSET<a id="a0f7d9f989d988b78677af2e3f888f33aadea52cc268d8b61d26af6020258c4c31"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_DEF_CFA_REGISTER<a id="a0f7d9f989d988b78677af2e3f888f33aa87a9e69725dea21ae3e73fbbdcbe9d00"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_OFFSET<a id="a0f7d9f989d988b78677af2e3f888f33aa3c153c7b6c6068be5322f392a7ca1bd1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_REL_OFFSET<a id="a0f7d9f989d988b78677af2e3f888f33aae054965ec20a020a2b7fd4d2e9040ea9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_PERSONALITY<a id="a0f7d9f989d988b78677af2e3f888f33aadba886fcc11d3eae71189b633265463b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_LSDA<a id="a0f7d9f989d988b78677af2e3f888f33aa33fa5f3b70a4fbe5de90ae812579325d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_REMEMBER_STATE<a id="a0f7d9f989d988b78677af2e3f888f33aa4c522f2bb10adedd3cee96de8e34323b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_RESTORE_STATE<a id="a0f7d9f989d988b78677af2e3f888f33aaa86fb9298a05ee76ae2ce0b89be5fbd2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_SAME_VALUE<a id="a0f7d9f989d988b78677af2e3f888f33aa064098158d898d032a62d37e1a91ccb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_RESTORE<a id="a0f7d9f989d988b78677af2e3f888f33aa6804551788c54e4b9f02883141f62404"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_ESCAPE<a id="a0f7d9f989d988b78677af2e3f888f33aad2ce7a5bf65a67b1d3dc4d2417f9797d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_RETURN_COLUMN<a id="a0f7d9f989d988b78677af2e3f888f33aa088764059b541052ca6f8f9a67339d7f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_SIGNAL_FRAME<a id="a0f7d9f989d988b78677af2e3f888f33aad6125bfa2dad0db5bfcc2f0327f836de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_UNDEFINED<a id="a0f7d9f989d988b78677af2e3f888f33aa0daf0e72f8514a52f6c46b52bd3cedf5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_REGISTER<a id="a0f7d9f989d988b78677af2e3f888f33aa349762e9fe5349eb00c039306f029df1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_WINDOW_SAVE<a id="a0f7d9f989d988b78677af2e3f888f33aac0fcbfb4ba8e1da6e4988dc39923c403"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_CFI_B_KEY_FRAME<a id="a0f7d9f989d988b78677af2e3f888f33aaa7f5fcb3fda380d859ac37a4f291b593"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_MACRO<a id="a0f7d9f989d988b78677af2e3f888f33aa4c20d91b2bbe8a048f88027460a17d41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_EXITM<a id="a0f7d9f989d988b78677af2e3f888f33aaeec11aaf5ea47bc99ce1b93f4a9832ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ENDM<a id="a0f7d9f989d988b78677af2e3f888f33aaa1d1f8ee24ef40ced6d27d56e37a0174"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_PURGE<a id="a0f7d9f989d988b78677af2e3f888f33aac60824310b4a9a8fa91529b5def4cedc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERR<a id="a0f7d9f989d988b78677af2e3f888f33aafffb95e889c5222fefffafefb1c3cd41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRB<a id="a0f7d9f989d988b78677af2e3f888f33aa87ec8dc5c398d2a3a0670bee71f1c680"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRNB<a id="a0f7d9f989d988b78677af2e3f888f33aa81741770ea95e812d44df14e4a9c8c74"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRDEF<a id="a0f7d9f989d988b78677af2e3f888f33aa2f05aacd6d4efdbd184e8b49761612e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRNDEF<a id="a0f7d9f989d988b78677af2e3f888f33aa488aff9ebc6a18f1ff339ffc3d6b1cfb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRDIF<a id="a0f7d9f989d988b78677af2e3f888f33aa47e5b12cd49d133e3c539a81f7219827"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRDIFI<a id="a0f7d9f989d988b78677af2e3f888f33aaa3b3767feb307dc70128786c322cb8da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRIDN<a id="a0f7d9f989d988b78677af2e3f888f33aadbf6e3342f1c1b4b36abc04e9b7e5b27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRIDNI<a id="a0f7d9f989d988b78677af2e3f888f33aa6b7b674d33aa095a405c9894f560477e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRE<a id="a0f7d9f989d988b78677af2e3f888f33aad9228485b39a6b110b6fd6439d3bd363"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ERRNZ<a id="a0f7d9f989d988b78677af2e3f888f33aa993017a09ee530e23a8c7cde0806cc9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ECHO<a id="a0f7d9f989d988b78677af2e3f888f33aa3d0b0e1e213e4c878aee3c8fbb360c95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_STRUCT<a id="a0f7d9f989d988b78677af2e3f888f33aa7e75b5b929398d37b6ad3a25e614113a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_UNION<a id="a0f7d9f989d988b78677af2e3f888f33aaf05144c6025accf41cff24baf24eed80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_ENDS<a id="a0f7d9f989d988b78677af2e3f888f33aae616c1284dbc221abe034496197fe5a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_END<a id="a0f7d9f989d988b78677af2e3f888f33aa88fe6e738248742248ffad4d0fc34bb0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_PUSHFRAME<a id="a0f7d9f989d988b78677af2e3f888f33aafce93f648e6f0fee14ef389273f0dd13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_PUSHREG<a id="a0f7d9f989d988b78677af2e3f888f33aa20a46a208c660189c79dfcb546546324"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SAVEREG<a id="a0f7d9f989d988b78677af2e3f888f33aa2c4c8f627f4bc63d6a3abdd5f0af1ac6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SAVEXMM128<a id="a0f7d9f989d988b78677af2e3f888f33aaa6fd07acb08ef56d20d06c9ecc480c88"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_SETFRAME<a id="a0f7d9f989d988b78677af2e3f888f33aa6ac5f0726b8a17edd58e5c90163d3310"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_RADIX<a id="a0f7d9f989d988b78677af2e3f888f33aa6802fa62c173ab62277ceaaaadccf1a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### DirectiveKindMap {#ac6618681ca8ba2eb0b506d682c9de5d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;DirectiveKind&gt; anonymous{MasmParser.cpp}::MasmParser::DirectiveKindMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps directive name --&gt; DirectiveKind enum, for directives parsed by this class.</p>

<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### eatToEndOfStatement {#a19ecdddfce4d05cafad65fa385d17f77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::eatToEndOfStatement ()</td>
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

<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>.</p>


<p>Referenced by <a href="#a46449244c1f2d4e4b2022d1126e7c5ab">Run</a>.</p>

</div>
</div>

### emitAlignTo {#ac098d71d14c076b5568f86ea8d370137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitAlignTo (int64_t Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitFieldInitializer {#a7fe614477db3d32d323b211ddce4c7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitFieldInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/fieldinitializer">FieldInitializer</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitFieldInitializer {#ac8b2ff638adff11ea9ecfb94809b11fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitFieldInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/intfieldinfo">IntFieldInfo</a> &amp; Contents, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/intfieldinfo">IntFieldInfo</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitFieldInitializer {#a78f08b7db4701ad016b69373d835f19b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitFieldInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/realfieldinfo">RealFieldInfo</a> &amp; Contents, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/realfieldinfo">RealFieldInfo</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitFieldInitializer {#a391e5c63736c22fc48d24875bcadcce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitFieldInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structfieldinfo">StructFieldInfo</a> &amp; Contents, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structfieldinfo">StructFieldInfo</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 914 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitFieldValue {#abe01254479ec104363c6b7875595a1d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitFieldValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitFieldValue {#ad6e423a6b2fb5ff04965d8f1e7cd99c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitFieldValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/intfieldinfo">IntFieldInfo</a> &amp; Contents)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitFieldValue {#a5a94b43703065760acd377b38619c407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitFieldValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/realfieldinfo">RealFieldInfo</a> &amp; Contents)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitFieldValue {#acadbeed70ca66d303433e5a96a56d55a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitFieldValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structfieldinfo">StructFieldInfo</a> &amp; Contents)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitIntegralValues {#a43da2b1b067e55727a163d3e4b7c3964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitIntegralValues (unsigned Size, unsigned * Count=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitIntValue {#a201ae8a3351e3f6c1fc1a63345870349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitIntValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitRealValues {#a71f99aa12f95ce46564f979d25a5a210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitRealValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, unsigned * Count=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitStructInitializer {#a6b06167ffd8b67fb2ed0e4cd9d3f0904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitStructInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a> &amp; Structure, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinitializer">StructInitializer</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### emitStructValues {#a59eac94c837bb806a445e9d87d25a549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::emitStructValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a> &amp; Structure, unsigned * Count=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### enabledGenDwarfForAssembly {#aea3886ee69415d83cfc3284f1ec062ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::enabledGenDwarfForAssembly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Should we emit DWARF describing this assembler source?</p>


<p>(Returns false if the source has .file directives, which means we don't want to generate info describing the assembler source itself.)</p>


<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### enterIncludeFile {#a5bf69ee594e31d45c1c6065022b14ce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::enterIncludeFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Filename)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enter the specified file. This returns true on failure.</p>

<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### evaluateBuiltinTextMacro {#abbed4057e4eb09fdadb8e65311a7a2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; MasmParser::evaluateBuiltinTextMacro (BuiltinSymbol Symbol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### evaluateBuiltinValue {#a8e0ca571e4cbd2dd6301636d0ff1dc22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * MasmParser::evaluateBuiltinValue (BuiltinSymbol Symbol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### ExpandKind {#a9246043f1e0c2b0855ae7dd69b8308b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MasmParser.cpp}::MasmParser::ExpandKind </td>
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
<td class="doxyEnumItemName">ExpandMacros<a id="a9246043f1e0c2b0855ae7dd69b8308b2aa0e124e667686746142702bfa146dbcd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DoNotExpandMacros<a id="a9246043f1e0c2b0855ae7dd69b8308b2a5135b67cd241bf52838ec3a37690ceae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### expandMacro {#aefd24774a7e2d181182f7a0c628d6819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::expandMacro (<a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Body, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcasmmacroparameter">MCAsmMacroParameter</a> &gt; Parameters, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-masmparser-cpp-/#a665b389ce45b43172e5f51bd693c67e6">MCAsmMacroArgument</a> &gt; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; Locals, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### expandMacros {#a8e3c75dc7536e385bf086a600d4e57d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::expandMacros ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>

<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### expandStatement {#a9ad449e41c042be65171cc3a012f4423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::expandStatement (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### getAssemblerDialect {#a2d473a254f569b1c1fdf6b1244cf8b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MasmParser.cpp}::MasmParser::getAssemblerDialect ()</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### getBinOpPrecedence {#a42f5f402526aefe4f34fa6e8989f597c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MasmParser::getBinOpPrecedence (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629">MCBinaryExpr::Opcode</a> &amp; Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### getContext {#a8e18d4299230d21094f423f2fdc7fc72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext &amp; anonymous{MasmParser.cpp}::MasmParser::getContext ()</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>Referenced by <a href="#a46e587fd477a44bb0b3c9e3689ff2f92">parseExpression</a>, <a href="#ae48dce9460eac00f49a306f8d48fdf11">parseMSInlineAsm</a>, <a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a> and <a href="#a46449244c1f2d4e4b2022d1126e7c5ab">Run</a>.</p>

</div>
</div>

### getCVContext {#abe4e1cb388f1118953752d11ea770dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewContext &amp; anonymous{MasmParser.cpp}::MasmParser::getCVContext ()</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### getLexer {#ad17ba7a1f3ebadc9d347d00f9d910c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmLexer &amp; anonymous{MasmParser.cpp}::MasmParser::getLexer ()</td>
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



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>Referenced by <a href="#af6dea9845d70ac952115bdbe378dbea1">parseIdentifier</a>, <a href="#ae48dce9460eac00f49a306f8d48fdf11">parseMSInlineAsm</a>, <a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a>, <a href="#a1c3ac00eab4ed0328bc8c8942957c83b">parseRealValue</a> and <a href="#a46449244c1f2d4e4b2022d1126e7c5ab">Run</a>.</p>

</div>
</div>

### getSourceManager {#af3cad9372a815b281af642700fff1fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr &amp; anonymous{MasmParser.cpp}::MasmParser::getSourceManager ()</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### getStreamer {#a08041d421b04248dc8a9a193868fa850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer &amp; anonymous{MasmParser.cpp}::MasmParser::getStreamer ()</td>
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

<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>Referenced by <a href="#a10d982772a36fe8255164eced5dd71bf">checkForValidSection</a>, <a href="#a759ccd5c07709f9d7fd4e339af61f662">parseAbsoluteExpression</a> and <a href="#a46449244c1f2d4e4b2022d1126e7c5ab">Run</a>.</p>

</div>
</div>

### handleMacroEntry {#abf77ddb2d4fb9faff2d6f6ca63b0e11f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::handleMacroEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> * M, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> ArgumentEndTok=AsmToken::EndOfStatement)</td>
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

<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### handleMacroExit {#a9daa2795a23b297a36a0ada5fc5c2cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::handleMacroExit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle exit from macro instantiation.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### handleMacroInvocation {#a33726a4abdbc936b0153374f444a178b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::handleMacroInvocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> * M, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle invocation of macro function.</p>


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
<td class="doxyParamItemDescription"><p>Invocation location.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### IdentifierPositionKind {#af84638c0bc3a211840905bad257bf39e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MasmParser.cpp}::MasmParser::IdentifierPositionKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse an identifier or string (as a quoted identifier) and set <span class="doxyComputerOutput">Res</span> to the identifier contents.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StandardPosition<a id="af84638c0bc3a211840905bad257bf39eaf7499916e89a58e101d932f0ff79b76e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StartOfStatement<a id="af84638c0bc3a211840905bad257bf39eaaf290adec620c872f4d4bbba77b66ce0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### initializeBuiltinSymbolMap {#a4596112d543cb1cb49780035adb21a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::initializeBuiltinSymbolMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1075 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### initializeCVDefRangeTypeMap {#a67f70371a42135c0075b0a7e24def29e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::initializeCVDefRangeTypeMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### initializeDirectiveKindMap {#af419e9bd76aeb0900d99d58860ab04d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::initializeDirectiveKindMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### instantiateMacroLikeBody {#aae8822b08540880a86a5e9cca7862d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::instantiateMacroLikeBody (<a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> * M, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### instantiateMacroLikeBody {#ae8916a86c5e9048c9baface5478835aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::instantiateMacroLikeBody (<a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> * M, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> ExitLoc, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### isInsideMacroInstantiation {#a048a484457069efc7be3f05e4b11fc5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MasmParser.cpp}::MasmParser::isInsideMacroInstantiation ()</td>
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

<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### isMacroLikeDirective {#ada091238d012c874b91e6a24661a870d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::isMacroLikeDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### isParsingMasm {#a9d49e00ff845f0165f228a3484de058e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MasmParser.cpp}::MasmParser::isParsingMasm ()</td>
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



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### isParsingMSInlineAsm {#a42c43698f83b23ab4f8ba2f5e350f38d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MasmParser.cpp}::MasmParser::isParsingMSInlineAsm ()</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### jumpToLoc {#aebd9299725e5b485ba78a6e5e76963d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::jumpToLoc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned InBuffer=0, bool EndStatementAtEOF=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset the current lexer position to that given by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>.</p>


<p>The current token is not set; clients should ensure <a href="#a3606169bb499457fe3acc26441161166">Lex()</a> is called subsequently.</p>


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

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### Lex {#afa801ffa70e7cd238829a01fa92d71c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AsmToken &amp; MasmParser::Lex (<a href="#a9246043f1e0c2b0855ae7dd69b8308b2">ExpandKind</a> ExpandNextToken)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a3690783ddbc5a9d0f0f3c94f48dcf052">llvm::AsmToken::BackSlash</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0765774402d06b304b3f4bee2e6231ed">llvm::AsmToken::Comment</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae46058c90a3c703357331a6501b32f1c">llvm::StringRef::equals_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a9246043f1e0c2b0855ae7dd69b8308b2aa0e124e667686746142702bfa146dbcd">ExpandMacros</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a3168618a19701d0fb78aefb4d4e664de">llvm::AsmToken::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a710e72de4b87af42e7605679d1fb2c24">llvm::AsmToken::is</a>, <a href="#a3606169bb499457fe3acc26441161166">Lex</a> and <a href="#af84638c0bc3a211840905bad257bf39eaaf290adec620c872f4d4bbba77b66ce0">StartOfStatement</a>.</p>

</div>
</div>

### Lex {#a3606169bb499457fe3acc26441161166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AsmToken &amp; anonymous{MasmParser.cpp}::MasmParser::Lex ()</td>
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

<p>Get the next AsmToken in the stream, possibly handling file inclusion first.</p>

<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="#a9246043f1e0c2b0855ae7dd69b8308b2aa0e124e667686746142702bfa146dbcd">ExpandMacros</a> and <a href="#a3606169bb499457fe3acc26441161166">Lex</a>.</p>


<p>Referenced by <a href="#a3606169bb499457fe3acc26441161166">Lex</a>, <a href="#afa801ffa70e7cd238829a01fa92d71c4">Lex</a>, <a href="#af6dea9845d70ac952115bdbe378dbea1">parseIdentifier</a>, <a href="#ae48dce9460eac00f49a306f8d48fdf11">parseMSInlineAsm</a>, <a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a>, <a href="#a1c3ac00eab4ed0328bc8c8942957c83b">parseRealValue</a> and <a href="#a46449244c1f2d4e4b2022d1126e7c5ab">Run</a>.</p>

</div>
</div>

### lookUpField {#a84d778f1ca3df360a0a0e09cef5930f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::lookUpField (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/structs/llvm/asmfieldinfo">AsmFieldInfo</a> &amp; Info)</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="#a84d778f1ca3df360a0a0e09cef5930f1">lookUpField</a>.</p>


<p>Referenced by <a href="#a6bb608aba526021fe280a23f84ee7754">lookUpField</a>, <a href="#a84d778f1ca3df360a0a0e09cef5930f1">lookUpField</a> and <a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a>.</p>

</div>
</div>

### lookUpField {#a6bb608aba526021fe280a23f84ee7754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::lookUpField (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Base, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Member, <a href="/web-llvm/docs/api/structs/llvm/asmfieldinfo">AsmFieldInfo</a> &amp; Info)</td>
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



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="#a84d778f1ca3df360a0a0e09cef5930f1">lookUpField</a>, <a href="/web-llvm/docs/api/structs/llvm/asmtypeinfo/#af70e0f6aae81a4509f63cdbde77b910e">llvm::AsmTypeInfo::Name</a> and <a href="/web-llvm/docs/api/structs/llvm/asmfieldinfo/#a7d8269d04262e8a300a30289d01c1a37">llvm::AsmFieldInfo::Type</a>.</p>

</div>
</div>

### lookUpField {#a2552264f41f57cff5738b24c57df1a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::lookUpField (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a> &amp; Structure, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Member, <a href="/web-llvm/docs/api/structs/llvm/asmfieldinfo">AsmFieldInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### lookUpType {#ae2e029f6e72e5147a329b0a221f38fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::lookUpType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/structs/llvm/asmtypeinfo">AsmTypeInfo</a> &amp; Info)</td>
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



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a36af5d2d51b08d83d76264dc33746e8d">llvm::StringSwitch&lt; T, R &gt;::CaseLower</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a4544df2c19074824906281761017ddfc">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### Note {#a9203278cccf22c7dafdfe75efa742ff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::Note (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
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

<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a25158c234ca9e60f3976a36d7d6ef271">llvm::MCAsmParser::printPendingErrors</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### parseAbsoluteExpression {#a759ccd5c07709f9d7fd4e339af61f662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseAbsoluteExpression (int64_t &amp; Res)</td>
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


<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a08041d421b04248dc8a9a193868fa850">getStreamer</a> and <a href="#a902a0a4bd0fb4232ebd3d92ad800aadf">parseExpression</a>.</p>

</div>
</div>

### parseAngleBracketClose {#ab2686cf8e123c05bc26de40f383f1983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseAngleBracketClose (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg="expected '&gt;'")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseAngleBracketString {#ab072c67afc063ea45e6d55211ac97f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseAngleBracketString (std::string &amp; Data)</td>
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

<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseBinOpRHS {#aebbcf249e68ad2885fc69da9bf4beb90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseBinOpRHS (unsigned Precedence, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse all binary operators with precedence &gt;= 'Precedence'.</p>


<p>Res contains the LHS of the expression on input.</p>


<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseBracketExpr {#a3cc79d750b0c936352fcc756e8fe9663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseBracketExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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


<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseCppHashLineFilenameComment {#a925aaa0f2255093e61ce634871122d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseCppHashLineFilenameComment (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCppHashLineFilenameComment as this: ::= # number "filename"</p>

<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseCurlyBlockScope {#a10428bc1ba22ce89ec6be75d6fc27556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseCurlyBlockScope (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/asmrewrite">AsmRewrite</a> &gt; &amp; AsmStrRewrites)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseCVFileId {#a33d8ef9973061b5588241c082f6371ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseCVFileId (int64_t &amp; FileId, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DirectiveName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseCVFunctionId {#a35479af33a07bb5c70b2c145e1f2066a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseCVFunctionId (int64_t &amp; FunctionId, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DirectiveName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAlign {#aa78f9b89a8fb433220ce2f5f13c5e7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveAlign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveAlign ::= align expression</p>

<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAscii {#a830a8ed7c24753368c31706e9bb289a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveAscii (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, bool ZeroTerminated)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveAscii: ::= ( .ascii | .asciz | .string ) [ "string" ( , "string" )* ]</p>

<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIAdjustCfaOffset {#ada127802f0af8e94518c70083c81218c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIAdjustCfaOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIAdjustCfaOffset ::= .cfi_adjust_cfa_offset adjustment</p>

<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIDefCfa {#a55b731a8bfdd35c6aa4b49725bee269a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIDefCfa (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIDefCfa ::= .cfi_def_cfa register, offset</p>

<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIDefCfaOffset {#a2d04451cea48d74c39f47e629d8554a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIDefCfaOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIDefCfaOffset ::= .cfi_def_cfa_offset offset</p>

<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIDefCfaRegister {#afb839747e1473fe8e6b0fd3c5bc6b885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIDefCfaRegister (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIDefCfaRegister ::= .cfi_def_cfa_register register</p>

<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIEndProc {#afc4c099f73b0affe8f8b082f19f4db34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIEndProc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIEndProc ::= .cfi_endproc</p>

<p>Definition at line 966 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIEscape {#a7ae0fa2705cc39e013220b63c587268f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIEscape (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIEscape ::= .cfi_escape expression[,...]</p>

<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIOffset {#a5c30d86fd71e5ce6c7cdf09d1e554587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIOffset ::= .cfi_offset register, offset</p>

<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIPersonalityOrLsda {#a92debdcb1e6ba3e643933fbce81f712d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIPersonalityOrLsda (bool IsPersonality)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIPersonalityOrLsda IsPersonality true for cfi_personality, false for cfi_lsda ::= .cfi_personality encoding, [symbol_name] ::= .cfi_lsda encoding, [symbol_name]</p>

<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRegister {#ab894c8a5c3acb433249dee41e84b7180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIRegister (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRegister ::= .cfi_register register, register</p>

<p>Definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRelOffset {#a2acc087a4b4eedf420d1d679982f5f6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIRelOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRelOffset ::= .cfi_rel_offset register, offset</p>

<p>Definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRememberState {#a08beee4a4873fb3a77d1b946384354a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIRememberState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRememberState ::= .cfi_remember_state</p>

<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRestore {#a70e1528ddc895216b5b7e005020a140e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIRestore (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRestore ::= .cfi_restore register</p>

<p>Definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIRestoreState {#a4a022fa4083ad1ab0244b650de5101ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIRestoreState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIRestoreState ::= .cfi_remember_state</p>

<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIReturnColumn {#a503ae2f1762b6601a960f58d6645efb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIReturnColumn (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIReturnColumn ::= .cfi_return_column register</p>

<p>Definition at line 979 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFISameValue {#ab46d3a2eb455369ec6743ed6e03682ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFISameValue (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFISameValue ::= .cfi_same_value register</p>

<p>Definition at line 976 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFISections {#afbc3e09b70a01caecd0fe7fcaf6a4cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFISections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFISections ::= .cfi_sections section [, section]</p>

<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFISignalFrame {#a3cb89781f06dce5ce8507775cbb3722e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFISignalFrame ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFISignalFrame ::= .cfi_signal_frame</p>

<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIStartProc {#a69a651df80c41f7b3a1c537bddf8f544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIStartProc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIStartProc ::= .cfi_startproc [simple]</p>

<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIUndefined {#a8b3e390c66f767b208f3088a33c9575c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIUndefined (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIUndefined ::= .cfi_undefined register</p>

<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCFIWindowSave {#a383be10abc242ae9d7874575457628d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCFIWindowSave (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCFIWindowSave ::= .cfi_window_save</p>

<p>Definition at line 963 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveComm {#a7056ca175910e7e195d38b976b64f4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveComm (bool IsLocal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveComm ::= ( .comm | .lcomm ) identifier , size_expression [ , align_expression ]</p>

<p>Definition at line 1002 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveComment {#a8c71ac3f332dec5a0e8dc467441844c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveComment (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveComment ::= comment delimiter [[text]] [[text]] [[text]] delimiter [[text]]</p>

<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVDefRange {#a3783e047ff32598c6738e40f77f392b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVDefRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVDefRange ::= .cv_def_range RangeStart RangeEnd (GapStart GapEnd)*, bytes*</p>

<p>Definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFile {#ad6adf18bf0f4ece092f1e25f39d94b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFile ::= .cv_file number filename [checksum] [checksumkind]</p>

<p>Definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFileChecksumOffset {#a0e1837b50f1d07fc18bfdbe9543a500c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVFileChecksumOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFileChecksumOffset ::= .cv_filechecksumoffset fileno</p>

<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFileChecksums {#a8403caeb1dee73906761f4c4c85beb0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVFileChecksums ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFileChecksums ::= .cv_filechecksums</p>

<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFPOData {#ad07f047a7ddb19577bd46d3771821ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVFPOData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFPOData ::= .cv_fpo_data procsym</p>

<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVFuncId {#a5c714d9127f81a103b4c1c4f6977c2a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVFuncId ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVFuncId ::= .cv_func_id <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a></p>


<p>Introduces a function <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> that can be used with .cv_loc.</p>


<p>Definition at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVInlineLinetable {#ab02c4e903becabe700baaefd619a93a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVInlineLinetable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVInlineLinetable ::= .cv_inline_linetable PrimaryFunctionId FileId LineNum FnStart FnEnd</p>

<p>Definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVInlineSiteId {#a064944aa8e0186dcaf0a6b800c5946d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVInlineSiteId ()</td>
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


<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVLinetable {#a81b84c0ecf3aac96c6e71f2ea3ce6c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVLinetable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVLinetable ::= .cv_linetable <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, FnStart, FnEnd</p>

<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVLoc {#acdd9b036eae8fe437b8434079c2492f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVLoc ::= .cv_loc <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> FileNumber [LineNumber] [ColumnPos] [prologue_end] [is_stmt VALUE] The first number is a file number, must have been previously assigned with a .file directive, the second number is the line number and optionally the third number is a column position (zero if not specified).</p>


<p>The remaining optional items are .loc sub-directives.</p>


<p>Definition at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVString {#ad756697444d8f507c821c246910bc0b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVString ::= .cv_stringtable "string"</p>

<p>Definition at line 955 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCVStringTable {#a007c14314414fa24f8e0aacdbcf41f3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveCVStringTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveCVStringTable ::= .cv_stringtable</p>

<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEcho {#ae666a8d08fd0382b779055fb4f07d2aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveEcho (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEcho ::= "echo" message</p>

<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveElse {#ac319ee593ef6ae02e26496ccd6a36cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveElse (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveElse ::= else</p>

<p>Definition at line 1028 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveElseIf {#aa8271588212dcfc612f4b507af8428de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveElseIf (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, DirectiveKind DirKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveElseIf ::= elseif expression</p>

<p>Definition at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveElseIfb {#a2c93d6e3328b576857fec4229702f9a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveElseIfb (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectBlank)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveElseIfb ::= elseifb textitem</p>

<p>Definition at line 1021 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveElseIfdef {#a2685e9100d6b29fc13f69238c8a8983f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveElseIfdef (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool expect_defined)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveElseIfdef ::= elseifdef symbol | elseifdef variable</p>

<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveElseIfidn {#ac33f17498ead0b25237c44596d63d815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveElseIfidn (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectEqual, bool CaseInsensitive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveElseIfidn ::= elseifidn textitem, textitem</p>

<p>Definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEnd {#a8c8e970efdeea44f4c4977c9784f0953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveEnd (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEnd ::= end</p>

<p>Definition at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEndIf {#a2942c8abaa99183a21f596095c1f600c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveEndIf (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEndIf ::= .endif</p>

<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEndMacro {#ad1bd68caeef836f3c1e0db6115478e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveEndMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEndMacro ::= endm</p>

<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEnds {#a3a01d10813755283e3bc39bb97303880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveEnds (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEquate {#a24801f84e5a228e61b56066615a4d220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveEquate (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DirectiveKind DirKind, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEquate: ::= name "=" expression | name "equ" expression (not redefinable) | name "equ" text-list | name "textequ" text-list (redefinability unspecified)</p>

<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveError {#ac41356ad52a35e6a661bc858fac9d219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveError ::= .err [message]</p>

<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveErrorIfb {#a52d04ecf45fc102422863b10805a0971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveErrorIfb (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectBlank)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveErrorIfb ::= .errb textitem[, message]</p>

<p>Definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveErrorIfdef {#afc51ecbc19ae8a3292ac6c717d3e2de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveErrorIfdef (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectDefined)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveErrorIfdef ::= .errdef name[, message]</p>

<p>Definition at line 1059 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveErrorIfe {#a8bf8ef76846ba233b94e79ef497b6693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveErrorIfe (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectZero)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveErrorIfe ::= .erre expression[, message]</p>

<p>Definition at line 1065 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveErrorIfidn {#a28ecc91775acfc249825eaff9918ac5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveErrorIfidn (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectEqual, bool CaseInsensitive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveErrorIfidn ::= .erridn textitem, textitem[, message]</p>

<p>Definition at line 1062 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEven {#abd0d03781403a84b3e65f14afb21ba00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveEven ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEven ::= even</p>

<p>Definition at line 938 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveExitMacro {#a3bde4078077c0482b51f4172735fef75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveExitMacro (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, std::string &amp; Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveExitMacro ::= "exitm" [textitem]</p>

<p>Definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveExtern {#a4c4f0be8c7a2cc5213b0a68e29e014b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveExtern ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 996 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFile {#a19cbb77584cb25ac6d8b8d9b4f3a1af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveFile (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveFile ::= .file filename ::= .file number [directory] filename [md5 checksum] [source source-text]</p>

<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFor {#ab901e6531ed5f9e00d9622f79803ebc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveFor (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveFor ::= ("for" | "irp") symbol [":" qualifier], &lt;values&gt; body endm</p>

<p>Definition at line 1040 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveForc {#a2cf58cbf0a69214103987f166f96bad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveForc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveForc ::= ("forc" | "irpc") symbol, &lt;string&gt; body endm</p>

<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIf {#af83dc9a4855dedcc92c3b5dc6bf719da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveIf (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, DirectiveKind DirKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIf ::= .if{,eq,ge,gt,le,lt,ne} expression</p>

<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIfb {#a65a40b647df2bc364d0c8d8e83560f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveIfb (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectBlank)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIfb ::= .ifb textitem</p>

<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIfdef {#ab355ea45d6c554f67476f824ae724492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveIfdef (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool expect_defined)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIfdef ::= ifdef symbol | ifdef variable</p>

<p>Definition at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIfidn {#ab910fa6af4676929a21f14329b6dcb1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveIfidn (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, bool ExpectEqual, bool CaseInsensitive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIfidn ::= ifidn textitem, textitem</p>

<p>Definition at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveInclude {#a1623bc2bac9901c02009c9b07344c220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveInclude ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveInclude ::= include &lt;filename&gt; | include filename</p>

<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveLine {#a096010c2299914b7078e987c3d5570fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveLine ::= .line [number]</p>

<p>Definition at line 942 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveLoc {#a4bb0dde0b0118b01e71bf551e3d131bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveLoc ::= .loc FileNumber [LineNumber] [ColumnPos] [basic_block] [prologue_end] [epilogue_begin] [is_stmt VALUE] [isa VALUE] The first number is a file number, must have been previously assigned with a .file directive, the second number is the line number and optionally the third number is a column position (zero if not specified).</p>


<p>The remaining optional items are .loc sub-directives.</p>


<p>Definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveMacro {#aa5cd62c89476e9983e7433f24d8a9e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveMacro ::= name macro [parameters] ["LOCAL" identifiers] parameters ::= parameter [, parameter]* parameter ::= name ":" qualifier qualifier ::= "req" | "vararg" | "=" macro_argument</p>

<p>Definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveMSAlign {#a0aa315c4e442d0443978a371e9231274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveMSAlign (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveMSEmit {#a4dc920ac21710bca7d83d26c04a1e027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveMSEmit (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info, size_t Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1045 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveNamedRealValue {#a6a49f76ed7dde17dd2651b924e24b289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveNamedRealValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveNamedRealValue ::= name (real4 | real8 | real10) [ expression (, expression)* ]</p>

<p>Definition at line 875 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveNamedStructValue {#a767c999aed4edef34c07b50c8b4e56f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveNamedStructValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a> &amp; Structure, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirLoc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveNamedValue ::= name (byte | word | ... ) [ expression (, expression)* ]</p>

<p>Definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveNamedValue {#a0161f03993da8a67125ac9ea31298d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveNamedValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeName, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveNamedValue ::= name (byte | word | ... ) [ expression (, expression)* ]</p>

<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveNestedEnds {#a926b066e23651843f3f0f5cbfcf10437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveNestedEnds ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveNestedStruct {#a49ca0b9d6385dd275d9d02da660ded59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveNestedStruct (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, DirectiveKind DirKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveNestedStruct ::= (STRUC | STRUCT | UNION) [name] (dataDir | generalDir | offsetDir | nestedStruct)+ ENDS</p>

<p>Definition at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveOrg {#a5007f550384ecc62b05ffb7a2f20e982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveOrg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveOrg ::= org expression</p>

<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectivePurgeMacro {#a3cacecd0a66d343748f3ec1f60c0d758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectivePurgeMacro (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectivePurgeMacro ::= purge identifier ( , identifier )*</p>

<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveRadix {#a27ef8fbe18bdaaaf927a30392884b7ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveRadix (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveRealValue {#ada7465acb55dc7210ef172dfd3ee6a7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveRealValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveRealValue ::= (real4 | real8 | real10) [ expression (, expression)* ]</p>

<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveRepeat {#a5d550c0301db14892995f3e8f8ff1d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveRepeat (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveRepeat ::= ("repeat" | "rept") count body endm</p>

<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveStabs {#a0c91af5a619958e573507255496c3b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveStabs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveStabs ::= .stabs string, number, number, number</p>

<p>Definition at line 944 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveStruct {#a667a08aa29c20544687179ecb27cc2ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveStruct (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, DirectiveKind DirKind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveStruct ::= &lt;name&gt; (STRUC | STRUCT | UNION) [fieldAlign] [, NONUNIQUE] (dataDir | generalDir | offsetDir | nestedStruct)+ &lt;name&gt; ENDS</p>

<p>Definition at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveStructValue {#a827ed3b344fb3e2795de89307b162575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveStructValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a> &amp; Structure, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveStructValue ::= struct-id (&lt;struct-initializer&gt; | {struct-initializer}) [, (&lt;struct-initializer&gt; | {struct-initializer})]*</p>

<p>Definition at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSymbolAttribute {#ae85e6333889e3ef3ce494a6899422e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveSymbolAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a directive like ".globl" which accepts a single symbol (which should be a label or an external).</p>


<p>parseDirectiveSymbolAttribute ::= { ".globl", ".weak", ... } [ identifier ( , identifier )* ]</p>


<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveValue {#ab43251a2501c33e5d7281aa005b44940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveValue ::= (byte | word | ... ) [ expression (, expression)* ]</p>

<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveWhile {#acf468d32d374c005269c5b5d72ae676a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseDirectiveWhile (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveWhile ::= "while" expression body endm</p>

<p>Definition at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseEscapedString {#a23756b1b8e93f17b4a152cb04a84b716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseEscapedString (std::string &amp; Data)</td>
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

<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseExpression {#a902a0a4bd0fb4232ebd3d92ad800aadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>Reference <a href="#a902a0a4bd0fb4232ebd3d92ad800aadf">parseExpression</a>.</p>


<p>Referenced by <a href="#a759ccd5c07709f9d7fd4e339af61f662">parseAbsoluteExpression</a>, <a href="#a902a0a4bd0fb4232ebd3d92ad800aadf">parseExpression</a> and <a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a>.</p>

</div>
</div>

### parseExpression {#a46e587fd477a44bb0b3c9e3689ff2f92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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


<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="#a8e18d4299230d21094f423f2fdc7fc72">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a> and <a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a>.</p>

</div>
</div>

### parseFieldInitializer {#ace9fd8885ddc478e31ea6c5e7b904154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseFieldInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/fieldinitializer">FieldInitializer</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseFieldInitializer {#a9ac15e7f820b9605fb9784994976d1f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseFieldInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/intfieldinfo">IntFieldInfo</a> &amp; Contents, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/fieldinitializer">FieldInitializer</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseFieldInitializer {#a3d79a3e2a5080e4d93c9026ecdeaf32d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseFieldInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/realfieldinfo">RealFieldInfo</a> &amp; Contents, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/fieldinitializer">FieldInitializer</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 888 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseFieldInitializer {#a47bb6e75f21fa5cfcd75d3eccf555fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseFieldInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/fieldinfo">FieldInfo</a> &amp; Field, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structfieldinfo">StructFieldInfo</a> &amp; Contents, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/fieldinitializer">FieldInitializer</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseIdentifier {#af6dea9845d70ac952115bdbe378dbea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseIdentifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Res, <a href="#af84638c0bc3a211840905bad257bf39e">IdentifierPositionKind</a> Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseIdentifier: ::= identifier ::= string</p>

<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4aeb4b633eccde6dcae9b02af09c8302">llvm::AsmToken::At</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aaf2a32c0f2738e57cac623b73b2c88aba79935518a3889663d8688b6b01fff051">Default</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aaf57ac1b90bbb375414e2fd3fc15bf4c">llvm::AsmToken::Dollar</a>, <a href="#a9246043f1e0c2b0855ae7dd69b8308b2a5135b67cd241bf52838ec3a37690ceae">DoNotExpandMacros</a>, <a href="#a9246043f1e0c2b0855ae7dd69b8308b2aa0e124e667686746142702bfa146dbcd">ExpandMacros</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#aefa517e84a358fccd59fb1815b87fa44">llvm::AsmToken::getIdentifier</a>, <a href="#ad17ba7a1f3ebadc9d347d00f9d910c14">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a54bfbf3752a7a79c026b8ffe73308cb6">llvm::MCAsmLexer::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a2f492d3c8c226803c571528284a95d36">llvm::AsmToken::isNot</a>, <a href="#a3606169bb499457fe3acc26441161166">Lex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="#af84638c0bc3a211840905bad257bf39eaaf290adec620c872f4d4bbba77b66ce0">StartOfStatement</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58">llvm::AsmToken::String</a>.</p>


<p>Referenced by <a href="#aa87c2b4cc4079362b8f826afacfd8231">parseIdentifier</a> and <a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a>.</p>

</div>
</div>

### parseIdentifier {#aa87c2b4cc4079362b8f826afacfd8231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MasmParser.cpp}::MasmParser::parseIdentifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Res)</td>
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

<p>Parse an identifier or string (as a quoted identifier) and set <span class="doxyComputerOutput">Res</span> to the identifier contents.</p>

<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="#af6dea9845d70ac952115bdbe378dbea1">parseIdentifier</a> and <a href="#af84638c0bc3a211840905bad257bf39eaf7499916e89a58e101d932f0ff79b76e">StandardPosition</a>.</p>

</div>
</div>

### parseMacroArgument {#aa5a735ef2dd76b3e51a6001c24acf284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseMacroArgument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcasmmacroparameter">MCAsmMacroParameter</a> * MP, <a href="/web-llvm/docs/api/namespaces/anonymous-masmparser-cpp-/#a665b389ce45b43172e5f51bd693c67e6">MCAsmMacroArgument</a> &amp; MA, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> EndTok=AsmToken::EndOfStatement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract AsmTokens for a macro argument.</p>

<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseMacroArguments {#ab474a00700753e0bc01b23733c107287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseMacroArguments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> * M, <a href="/web-llvm/docs/api/namespaces/anonymous-masmparser-cpp-/#aea86380f3c03a7edd9590be092b86655">MCAsmMacroArguments</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> EndTok=AsmToken::EndOfStatement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse all macro arguments for a given macro.</p>

<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseMacroLikeBody {#a41615a2a483ce292d16dc86b8910e644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmMacro * MasmParser::parseMacroLikeBody (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseMSInlineAsm {#ae48dce9460eac00f49a306f8d48fdf11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseMSInlineAsm (std::string &amp; AsmString, unsigned &amp; NumOutputs, unsigned &amp; NumInputs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; void *, bool &gt; &gt; &amp; OpDecls, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::string &gt; &amp; Constraints, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::string &gt; &amp; Clobbers, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> * MII, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * IP, <a href="/web-llvm/docs/api/classes/llvm/mcasmparsersemacallback">MCAsmParserSemaCallback</a> &amp; SI)</td>
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

<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfdae141b627ac649470f82d9c2eb37249fb">llvm::AOK_Align</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda990d2241c927f6ed413ae464f7796f00">llvm::AOK_CallInput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda79f10173e38b98986342a2ba9fb6b2a1">llvm::AOK_Emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda2273a4cd5bbad83c4f121c983185a8df">llvm::AOK_EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda0364c4ccb95b97b3cfe1a1c9a3014173">llvm::AOK_EVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfdaa86669a9cc5218a2b8ea4daafd9f195e">llvm::AOK_Input</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfdad2780c2bc4d0d36293a242d17c6b07a6">llvm::AOK_IntelExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda15b8af91c21aac1a862c9e92e8c2cbfb">llvm::AOK_Label</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda2fdf76d69064416f4ade1f4615561e41">llvm::AOK_Output</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda533ada35f0fe9e602da710cbcd6d9430">llvm::AOK_SizeDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda7abdec48f548b1a8b8ce59f17b52e5ec">llvm::AOK_Skip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#ae18bef1cef63d8cdb84adad1f9eea472">llvm::IntelExpr::BaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#aaeade81f238c8b2aed5f561358188196">llvm::AsmRewrite::Done</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a90c2a69257a8fb499590383bd6b41f41">llvm::IntelExpr::emitImm</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#ad38a8c360d26f17718aafe2c7c5fc470">llvm::MCParsedAsmOperand::getConstraint</a>, <a href="#a8e18d4299230d21094f423f2fdc7fc72">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="#ad17ba7a1f3ebadc9d347d00f9d910c14">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#ab7825dc94141647be2917e6e410d97d0">llvm::MCParsedAsmOperand::getMCOperandNum</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#afb1a8b2b0718fe4a475feeefe15da9e1">llvm::MCParsedAsmOperand::getOpDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a78471ca3b825294a4e6015500d7a6630">llvm::MCParsedAsmOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a95096f6ce0d0d6e4140c954962796332">llvm::MCParsedAsmOperand::getSymName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a86940ae2900e1fb1066f5e169c0af6a7">llvm::IntelExpr::hasBaseReg</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a0e6fd9c1065f3aa23de324392652aeca">llvm::IntelExpr::hasIndexReg</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a31fe9e50f9bd6de0c55bdd144d874e98">llvm::IntelExpr::hasOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a4947313871f8935468ae02f6621260c8">llvm::MCAsmParser::hasPendingError</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a21dbdc3fb6e0b3cd12289b4b0478c714">llvm::IntelExpr::hasRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a06c8486a2041e1affbca1d4477bf33c0">llvm::IntelExpr::Imm</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a6f3150175cdaf4e5d88abd55fb222327">llvm::IntelExpr::IndexReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a529587a34ba75058d5002465e08f6cf8">llvm::AsmRewrite::IntelExp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#ab4d869652f0c0d119d84f800cf49229b">llvm::MCParsedAsmOperand::isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a8608c30f9162510854ebd7ad920cb288">llvm::MCParsedAsmOperand::isOffsetOfLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a3212ab0fba4f46a46382c297dd7ee5f7">llvm::MCParsedAsmOperand::isReg</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#ae3a557482aa4e3ab1faa40279052aea6">llvm::IntelExpr::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a49376fe6e2f150528a01d6e04c6bbbf9">llvm::AsmRewrite::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#aa86261d4d5f182d5be6d229e947a83d7">llvm::AsmRewrite::Label</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a73fd5ec31aade399b31f6da4bd3de4f7">llvm::AsmRewrite::Len</a>, <a href="#a3606169bb499457fe3acc26441161166">Lex</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a801ff63a978f05ed7a17965654f4db42">llvm::AsmRewrite::Loc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a4546812b19a8dd8aaf85077500ad0625">llvm::MCParsedAsmOperand::needAddressOf</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#ad44afff5ca85c4a193e7a112594c4899">llvm::IntelExpr::NeedBracs</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a81b64c6a2f24767fb2f524a622898b9b">llvm::IntelExpr::OffsetName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a25158c234ca9e60f3976a36d7d6ef271">llvm::MCAsmParser::printPendingErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ad0ad5f0b1236badc25e0613d3b962997">llvm::MCInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#ac27a97bbb42a7f0481f803251c65c237">rewritesSort</a>, <a href="/web-llvm/docs/api/structs/llvm/intelexpr/#a7316b8a13ba48c8e8157f02cbdd51bd9">llvm::IntelExpr::Scale</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48f85da577c6ce7d9aed90437dc0d07c">llvm::unique</a> and <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#ac737e0ab2d8987b1ce89fa143dd255b2">llvm::AsmRewrite::Val</a>.</p>

</div>
</div>

### parseOptionalAngleBracketOpen {#a341c92469f1c16f767408ead3b9de6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseOptionalAngleBracketOpen ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseParenExpr {#aa42fb541c38140136796f19cbeec0d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseParenExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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


<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseParenExpression {#aeb1bf86c7b80900c21e8f6777aa1cd7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseParenExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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


<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseParenExprOfDepth {#a61115ff1360e15d4f0eb3f12d757d7c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseParenExprOfDepth (unsigned ParenDepth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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


<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a9e6496a765eb2a14512ca0d5f48185fa">llvm::AsmToken::getEndLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a709fe7ec3803940386b0588e9a1c6f02">llvm::MCAsmParser::parseRParen</a>.</p>

</div>
</div>

### parsePrimaryExpr {#a48e574342f9028f1077132c27267952b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parsePrimaryExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc, <a href="/web-llvm/docs/api/structs/llvm/asmtypeinfo">AsmTypeInfo</a> * TypeInfo)</td>
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


<p>primaryexpr ::= (parenexpr primaryexpr ::= symbol primaryexpr ::= number primaryexpr ::= '.' primaryexpr ::= ~,+,-,'not' primaryexpr primaryexpr ::= string (a string is interpreted as a 64-bit number in big-endian base-256)</p>


<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c">llvm::MCBinaryExpr::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4aeb4b633eccde6dcae9b02af09c8302">llvm::AsmToken::At</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8792e8ff663b631c3d0069d1655c7b45">llvm::AsmToken::BigNum</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#ac393df34745cae1433909c2049978bd4">llvm::MCBinaryExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a58195f308d23f783e2b52e968ff1fe46">llvm::MCUnaryExpr::createLNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#aff718d95a5738283e9049bc93fa9abe2">llvm::MCUnaryExpr::createMinus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#af8b9397b901280268465e71ed2fef286">llvm::MCUnaryExpr::createNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a8f9fe9e0790b764dc9ef925a83408f74">llvm::MCUnaryExpr::createPlus</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#abefd1a22d96014163fe12930da2364ec">llvm::MCTargetAsmParser::createTargetUnaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aaf57ac1b90bbb375414e2fd3fc15bf4c">llvm::AsmToken::Dollar</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae95926c6ea560f4332395213cc7519e9">llvm::AsmToken::Dot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039af475f82c0aa5e42ef5751dcdc3bee49f">llvm::AsmToken::Exclaim</a>, <a href="#a8e18d4299230d21094f423f2fdc7fc72">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#afb8a5e63fad89ccba5fee1f314d644b5">llvm::MCContext::getDirectionalLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a392412e22be62f31478cfca07d562055">llvm::MCContext::getInlineAsmLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a270e1171db01008f862ffbc34f8476fc">llvm::AsmToken::getIntVal</a>, <a href="#ad17ba7a1f3ebadc9d347d00f9d910c14">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a54bfbf3752a7a79c026b8ffe73308cb6">llvm::MCAsmLexer::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a433c1cd00305214e7d1d81d682c2346a">llvm::MCSymbolRefExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa462dae167e31cac32e97bb0c77ab071">llvm::MCSymbol::isUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d">llvm::AsmToken::LBrac</a>, <a href="#a3606169bb499457fe3acc26441161166">Lex</a>, <a href="#a84d778f1ca3df360a0a0e09cef5930f1">lookUpField</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="#a902a0a4bd0fb4232ebd3d92ad800aadf">parseExpression</a>, <a href="#af6dea9845d70ac952115bdbe378dbea1">parseIdentifier</a>, <a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a709fe7ec3803940386b0588e9a1c6f02">llvm::MCAsmParser::parseRParen</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a137818cb489ba17770a17ee9eb6f269e">llvm::MCAsmParser::parseToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a00c4e8d8fb246b6b7aeed5c7b53ee299">llvm::AsmToken::PercentCall16</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a707c1a6ff33be3833fa784e55c72d356">llvm::AsmToken::PercentCall_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a074f871580c44c082aa24aaafd8a238a">llvm::AsmToken::PercentCall_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a267b3c56c189ca7b2c22f3f5a29647fe">llvm::AsmToken::PercentDtprel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa8b764c71f0045677baab76623a52bcd">llvm::AsmToken::PercentDtprel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a00774b22629d30aaa48e1c2bd537028b">llvm::AsmToken::PercentGot</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039af1f8ea5e121b4bc15a5df42c055bd6d7">llvm::AsmToken::PercentGot_Disp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ab0762694eece06d0f7a3a2079a4a4fc8">llvm::AsmToken::PercentGot_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0c1d09e9bf3105cc4a9f0fdbd353573e">llvm::AsmToken::PercentGot_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad1e2f5b48c997464f7959fc57dffc5f8">llvm::AsmToken::PercentGot_Ofst</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a92f6b21bb33e8fed87795f60509087b9">llvm::AsmToken::PercentGot_Page</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0605e7b15189ad4dbaf2de310d8d71d6">llvm::AsmToken::PercentGottprel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aceac274aaa62864ab0b60654281e237a">llvm::AsmToken::PercentGp_Rel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a07aadc6194c34b01c1dbc32579382c1e">llvm::AsmToken::PercentHi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1889a8a107d7a02053f669a752290d2d">llvm::AsmToken::PercentHigher</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ab00380bcbfc11a24a06d6ff70619f9fa">llvm::AsmToken::PercentHighest</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad3c8fae162d44bb21f7f39c853e85eca">llvm::AsmToken::PercentLo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039afe3b827d1ceee6cf5aaf0bb61cc1e77f">llvm::AsmToken::PercentNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a28be2810a4857bb3b0aad6844d80176e">llvm::AsmToken::PercentPcrel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7aa2c1d1de0fe4ef4d1d2275632aa6a1">llvm::AsmToken::PercentPcrel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8f666b660d975090f718938ee00fe9fc">llvm::AsmToken::PercentTlsgd</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a91a7f91ec2b3a0618572a821556591cf">llvm::AsmToken::PercentTlsldm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8df6f192abb2cb6a173a7a2aa91bd8a2">llvm::AsmToken::PercentTprel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a63518ba1849d2eb240372e55b9a04436">llvm::AsmToken::PercentTprel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">llvm::AsmToken::Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad1efc309b8dfe9289db5493d71569f0b">llvm::AsmToken::Real</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58">llvm::AsmToken::String</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a151c8770a1290c7713e3a8490ee09471">llvm::AsmToken::Tilde</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#aca3b32b0f673fcda41b604540f49a4f9">llvm::MCAsmParser::TokError</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4f5bc5fd0f95b1eb6e5aedfac9993cc2">llvm::MCSymbolRefExpr::VK_Invalid</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="#a46e587fd477a44bb0b3c9e3689ff2f92">parseExpression</a> and <a href="#a48e574342f9028f1077132c27267952b">parsePrimaryExpr</a>.</p>

</div>
</div>

### parseRealInstList {#ae02fde01466157a9db0ed84786e066d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseRealInstList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &amp; Values, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> EndToken=AsmToken::EndOfStatement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseRealValue {#a1c3ac00eab4ed0328bc8c8942957c83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseRealValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a floating point expression using the float <span class="doxyComputerOutput">Semantics</span> and set <span class="doxyComputerOutput">Res</span> to the value.</p>

<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a14180977794bfc2a37dbffeef3ca20de">llvm::StringRef::consume_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae46058c90a3c703357331a6501b32f1c">llvm::StringRef::equals_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0596fb939ff753151c9c37ed2b671b4c">llvm::errorToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a>, <a href="#ad17ba7a1f3ebadc9d347d00f9d910c14">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a54bfbf3752a7a79c026b8ffe73308cb6">llvm::MCAsmLexer::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aeecd5fa66870de83d235933a683b5952">llvm::APFloat::getNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a3168618a19701d0fb78aefb4d4e664de">llvm::AsmToken::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#abb1e94b8fff61f549bcbd5a2780f6796">llvm::SMLoc::isValid</a>, <a href="#a3606169bb499457fe3acc26441161166">Lex</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">llvm::AsmToken::Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad1efc309b8dfe9289db5493d71569f0b">llvm::AsmToken::Real</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#aca3b32b0f673fcda41b604540f49a4f9">llvm::MCAsmParser::TokError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a066e2a31a13d6520e52ae1944f194662">llvm::Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

### parseRegisterOrRegisterNumber {#a569156266365309580745e126914ad85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseRegisterOrRegisterNumber (int64_t &amp; Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> DirectiveLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parse register name or number.</p>

<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseScalarInitializer {#a68ea763319aebf69bc74848aeee0bce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseScalarInitializer (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt; &amp; Values, unsigned StringPadLength=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseScalarInstList {#a1b7094001fb9413bfca4774dd4940ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseScalarInstList (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt; &amp; Values, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> EndToken=AsmToken::EndOfStatement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseStatement {#a05bb73a9b1f718bee860d01bf0e4c688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseStatement (<a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/mcasmparsersemacallback">MCAsmParserSemaCallback</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseStatement: ::= % statement ::= EndOfStatement ::= Label* <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> ...Operands... EndOfStatement ::= Label* Identifier OperandList* EndOfStatement.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseStringRefsTo {#ab4112e259651b721e27ea572fd874002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; StringRef, 1 &gt; MasmParser::parseStringRefsTo (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> EndTok)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse up to a token of kind <span class="doxyComputerOutput">EndTok</span> and return the contents from the current token up to (but not including) this token; the current token on exit will be either this kind or EOF.</p>


<p>Reads through instantiated macro functions and text macros.</p>


<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseStringTo {#a708016f80fa4d2044f553d243e6e8822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string MasmParser::parseStringTo (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> EndTok)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseStringToEndOfStatement {#a727c06165a9106a3b0759fb344e14bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MasmParser::parseStringToEndOfStatement ()</td>
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

<p>Parse up to the end of statement and return the contents from the current token until the end of the statement; the current token on exit will be either the EndOfStatement or EOF.</p>

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseStructInitializer {#aa1690d007dc0459f89300ab353e4f5b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseStructInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a> &amp; Structure, <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinitializer">StructInitializer</a> &amp; Initializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseStructInstList {#ad10016a91b3f44031b4e6043f95dbd2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseStructInstList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo">StructInfo</a> &amp; Structure, std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinitializer">StructInitializer</a> &gt; &amp; Initializers, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> EndToken=AsmToken::EndOfStatement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### parseTextItem {#a2847168dd8053fd74bd6e75d0bb4c9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::parseTextItem (std::string &amp; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>textItem ::= textLiteral | textMacroID | % constExpr</p>

<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### peekTok {#ab42058a45d470b008f26fd29b4fb76c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AsmToken MasmParser::peekTok (bool ShouldSkipSpace=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### printError {#ac54c7247683fdbcce5c47cf186227d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::printError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
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


<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afad5b9aac74030a159903f3cf64c481c">llvm::MCAsmParser::HadError</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="#a46449244c1f2d4e4b2022d1126e7c5ab">Run</a>.</p>

</div>
</div>

### printMacroInstantiations {#afbf78c53490e61aa2107cd30ea0e450e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MasmParser::printMacroInstantiations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### printMessage {#aea65225f3507247f5495f456c1762471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MasmParser.cpp}::MasmParser::printMessage (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777">SourceMgr::DiagKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
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



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### setAssemblerDialect {#a18ee9263e29f8eec6f6a01be947f3a60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MasmParser.cpp}::MasmParser::setAssemblerDialect (unsigned i)</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### setParsingMSInlineAsm {#ac13733656a25cdd26131630f2ec1d1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MasmParser.cpp}::MasmParser::setParsingMSInlineAsm (bool V)</td>
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



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>

</div>
</div>

### Warning {#a08f88c883adc92a0b9eacbc5a4064d2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MasmParser::Warning (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
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


<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777a6bcc8ac9374461ed0599334db63365d0">llvm::SourceMgr::DK_Warning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afc6c7d84cb78a0d8586215b53b7bee33">llvm::MCAsmParser::getTargetParser</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="#ae39bffc615ea979f44a25c730094bbb4">defineMacro</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp">MasmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
