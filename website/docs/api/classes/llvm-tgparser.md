---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/tgparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TGParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::TGParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TableGen/TGParser.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa5867e82549e21c22ec1e622f9da66">SubstStack</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * &gt;, 8 &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8468db4f5ce9ce5baace61c48723396">ArgValueHandler</a> = std::function&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *)&gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IDParseMode { <a href="#aa3955833ae4b6607c50af4c2a66fae9d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb79a047abfe9f327a7595d58d04b61">TGParser</a> (SourceMgr &amp;SM, ArrayRef&lt; std::string &gt; Macros, RecordKeeper &amp;records, const bool NoWarnOnUnusedTemplateArgs=false, const bool TrackReferenceLocs=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2220b1390559e48081eb1187622748">ParseFile</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseFile - Main entrypoint for parsing a tblgen file. <a href="#adf2220b1390559e48081eb1187622748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88a8d625cb0f5b05c02959e439f9a3b6">Error</a> (SMLoc L, const Twine &amp;Msg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5db391a5f2cba3c4a78e69e1ddb3fd2">TokError</a> (const Twine &amp;Msg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/tglexer/#afaf6bde3c87f4217358a4b4b89df79e2">TGLexer::DependenciesSetTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58685cdd792796ad7d316a781ebd7089">getDependencies</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c749c975468baeb15fb9757c58a48d">PushScope</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3100229bcd453690b137edb3871ee7d">PushScope</a> (Record *Rec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a899a19e6bae243782e1ba66bee2c8994">PushScope</a> (ForeachLoop *Loop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e316b3eecce4817b10beaaf482151d">PushScope</a> (MultiClass *Multiclass)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a050e3ccb0e5c0b55cb30615217398b52">PopScope</a> (TGVarScope *ExpectedStackTop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fd5cc67aa5c3839e40638ad75d739c">AddValue</a> (Record *TheRec, SMLoc Loc, const RecordVal &amp;RV)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a456129bcd80efa5e0d91ab03dcf06f1b">SetValue</a> (Record *TheRec, SMLoc Loc, const Init *ValName, ArrayRef&lt; unsigned &gt; BitList, const Init *V, bool AllowSelfAssignment=false, bool OverrideDefLoc=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the value of a <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> within the given record. <a href="#a456129bcd80efa5e0d91ab03dcf06f1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1448223f3ed5019a9c551b6d4d116b57">AddSubClass</a> (Record *Rec, SubClassReference &amp;SubClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddSubClass - Add SubClass as a subclass to CurRec, resolving its template args as SubClass's template arguments. <a href="#a1448223f3ed5019a9c551b6d4d116b57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef1eef57f74abd5a24099f4021acaa0">AddSubClass</a> (RecordsEntry &amp;Entry, SubClassReference &amp;SubClass)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe998559bb299a9ff0887369405e2ab6">AddSubMultiClass</a> (MultiClass *CurMC, SubMultiClassReference &amp;SubMultiClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddSubMultiClass - Add SubMultiClass as a subclass to CurMC, resolving its template args as SubMultiClass's template arguments. <a href="#afe998559bb299a9ff0887369405e2ab6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22264cec4b430a2c159717a9f566eb0c">addEntry</a> (RecordsEntry E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a record, foreach loop, or assertion to the current context. <a href="#a22264cec4b430a2c159717a9f566eb0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6546bcd069ab87b015f188b0d148b9ef">resolve</a> (const ForeachLoop &amp;Loop, SubstStack &amp;Stack, bool Final, std::vector&lt; RecordsEntry &gt; *Dest, SMLoc *Loc=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve the entries in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a></span>, going over inner loops recursively and making the given subsitutions of (name, value) pairs. <a href="#a6546bcd069ab87b015f188b0d148b9ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3663ff20a8d2fe19503b42a580861767">resolve</a> (const std::vector&lt; RecordsEntry &gt; &amp;Source, SubstStack &amp;Substs, bool Final, std::vector&lt; RecordsEntry &gt; *Dest, SMLoc *Loc=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve the entries in <span class="doxyComputerOutput">Source</span>, going over loops recursively and making the given substitutions of (name, value) pairs. <a href="#a3663ff20a8d2fe19503b42a580861767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09891ad31b97c85a8874755b9e592c5">addDefOne</a> (std::unique_ptr&lt; Record &gt; Rec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve the record fully and add it to the record keeper. <a href="#ad09891ad31b97c85a8874755b9e592c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b47b953c0ccc2b12e8ab77d5fcca5d1">resolveArguments</a> (const Record *Rec, ArrayRef&lt; const ArgumentInit * &gt; ArgValues, SMLoc Loc, ArgValueHandler ArgValueHandler=[](const Init *, const Init *) {})</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a972a3d6c67e123384dc7c4e5d3bb32ae">resolveArgumentsOfClass</a> (MapResolver &amp;R, const Record *Rec, ArrayRef&lt; const ArgumentInit * &gt; ArgValues, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve the arguments of class and set them to <a href="/web-llvm/docs/api/classes/llvm/mapresolver">MapResolver</a>. <a href="#a972a3d6c67e123384dc7c4e5d3bb32ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8b587d5eeb43e576b218aa7fca8a2a">resolveArgumentsOfMultiClass</a> (SubstStack &amp;Substs, MultiClass *MC, ArrayRef&lt; const ArgumentInit * &gt; ArgValues, const Init *DefmName, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve the arguments of multiclass and store them into SubstStack. <a href="#a0e8b587d5eeb43e576b218aa7fca8a2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c0430438b38081597a768d5452de35">consume</a> (tgtok::TokKind K)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a568150af076e5d2e698a96f19a72226b">ParseObjectList</a> (MultiClass *MC=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseObjectList ObjectList :== Object*. <a href="#a568150af076e5d2e698a96f19a72226b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b717f35699aded00ea02bf21cb6a50a">ParseObject</a> (MultiClass *MC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseObject Object ::= ClassInst Object ::= DefInst Object ::= MultiClassInst Object ::= DefMInst Object ::= LETCommand '{' ObjectList '}' Object ::= LETCommand Object Object ::= Defset Object ::= Deftype Object ::= Defvar Object ::= Assert Object ::= Dump. <a href="#a9b717f35699aded00ea02bf21cb6a50a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3894b83a9e85605f909a21cfb54bae09">ParseClass</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseClass - Parse a tblgen class definition. <a href="#a3894b83a9e85605f909a21cfb54bae09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33db554af03479d5863f9d23ac839853">ParseMultiClass</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseMultiClass - Parse a multiclass definition. <a href="#a33db554af03479d5863f9d23ac839853">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a816a1546393b89a4cf7b132a4373ae79">ParseDefm</a> (MultiClass *CurMultiClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDefm - Parse the instantiation of a multiclass. <a href="#a816a1546393b89a4cf7b132a4373ae79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad226db4ed50e913b4829e3583fd17e2d">ParseDef</a> (MultiClass *CurMultiClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDef - Parse and return a top level or multiclass record definition. <a href="#ad226db4ed50e913b4829e3583fd17e2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dea9c175324f04154f7cbaa09ff2e4e">ParseDefset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDefset - Parse a defset statement. <a href="#a3dea9c175324f04154f7cbaa09ff2e4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecbb529e8adfe38a61c3e69826fb1297">ParseDeftype</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDeftype - Parse a defvar statement. <a href="#aecbb529e8adfe38a61c3e69826fb1297">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1248ddc95c5697be7a81fe2958afee3b">ParseDefvar</a> (Record *CurRec=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDefvar - Parse a defvar statement. <a href="#a1248ddc95c5697be7a81fe2958afee3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e07706cd397714199f0c52836be824a">ParseDump</a> (MultiClass *CurMultiClass, Record *CurRec=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca24eab98dd4587c68b6c2f7db1852d8">ParseForeach</a> (MultiClass *CurMultiClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseForeach - Parse a for statement. <a href="#aca24eab98dd4587c68b6c2f7db1852d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b2ac83afb70de9ec74c747209e34d2e">ParseIf</a> (MultiClass *CurMultiClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseIf - Parse an if statement. <a href="#a8b2ac83afb70de9ec74c747209e34d2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad207395a6a8d34598a8b9a6e9cdc7adc">ParseIfBody</a> (MultiClass *CurMultiClass, StringRef Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseIfBody - Parse the then-clause or else-clause of an if statement. <a href="#ad207395a6a8d34598a8b9a6e9cdc7adc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3a7dfeaf4a840a37b0ce604735a97fb">ParseAssert</a> (MultiClass *CurMultiClass, Record *CurRec=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseAssert - Parse an assert statement. <a href="#ac3a7dfeaf4a840a37b0ce604735a97fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab31750a4a9193f24692af53e7ea845e6">ParseTopLevelLet</a> (MultiClass *CurMultiClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseTopLevelLet - Parse a 'let' at top level. <a href="#ab31750a4a9193f24692af53e7ea845e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a574184346dbce246238e1c01069c08cc">ParseLetList</a> (SmallVectorImpl&lt; LetRecord &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseLetList - Parse a non-empty list of assignment expressions into a list of LetRecords. <a href="#a574184346dbce246238e1c01069c08cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf98e35dec734091521872790473753c">ParseObjectBody</a> (Record *CurRec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseObjectBody - Parse the body of a def or class. <a href="#aaf98e35dec734091521872790473753c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d37ad634be013e9358c05ebf3cd28d7">ParseBody</a> (Record *CurRec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseBody - Read the body of a class or def. <a href="#a2d37ad634be013e9358c05ebf3cd28d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8a4bf2d2bdf87c69a04e7e0dbfa9ce">ParseBodyItem</a> (Record *CurRec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseBodyItem - Parse a single item within the body of a def or class. <a href="#aaf8a4bf2d2bdf87c69a04e7e0dbfa9ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cfd6ea7690c0fd4b573519c0d6a0716">ParseTemplateArgList</a> (Record *CurRec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseTemplateArgList - Read a template argument list, which is a non-empty sequence of template-declarations in &lt;&gt;'s. <a href="#a5cfd6ea7690c0fd4b573519c0d6a0716">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e6e0ba477c95c6f61d5487d7481b791">ParseDeclaration</a> (Record *CurRec, bool ParsingTemplateArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDeclaration - Read a declaration, returning the name of field <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, or an empty string on error. <a href="#a3e6e0ba477c95c6f61d5487d7481b791">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/varinit">VarInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b6c82cafcfc76dcd8a2a7106820574c">ParseForeachDeclaration</a> (const Init *&amp;ForeachListValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseForeachDeclaration - Read a foreach declaration, returning the name of the declared object or a NULL <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> on error. <a href="#a6b6c82cafcfc76dcd8a2a7106820574c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/subclassreference">SubClassReference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f8b1496893ebbe3a0f18f450cbd33f">ParseSubClassReference</a> (Record *CurRec, bool isDefm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSubClassReference - Parse a reference to a subclass or a multiclass. <a href="#a24f8b1496893ebbe3a0f18f450cbd33f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/submulticlassreference">SubMultiClassReference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4f5b479ebd3fe98f052bfa71231c5db">ParseSubMultiClassReference</a> (MultiClass *CurMC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSubMultiClassReference - Parse a reference to a subclass or to a templated submulticlass. <a href="#ad4f5b479ebd3fe98f052bfa71231c5db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a27e94136c592062c52d9eb192e5b9">ParseIDValue</a> (Record *CurRec, const StringInit *Name, SMRange NameLoc, IDParseMode Mode=ParseValueMode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseIDValue. <a href="#a32a27e94136c592062c52d9eb192e5b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e98cf0cae28a494bb33ebc83e9c7235">ParseSimpleValue</a> (Record *CurRec, const RecTy *ItemType=nullptr, IDParseMode Mode=ParseValueMode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSimpleValue - Parse a tblgen value. <a href="#a1e98cf0cae28a494bb33ebc83e9c7235">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d5a448d985bdcee64ad98c890989ca4">ParseValue</a> (Record *CurRec, const RecTy *ItemType=nullptr, IDParseMode Mode=ParseValueMode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseValue - Parse a <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> value. <a href="#a1d5a448d985bdcee64ad98c890989ca4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997b5c8dc94a1d6a514032a2b31851cc">ParseValueList</a> (SmallVectorImpl&lt; const Init * &gt; &amp;Result, Record *CurRec, const RecTy *ItemType=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseValueList - Parse a comma separated list of values, returning them in a vector. <a href="#a997b5c8dc94a1d6a514032a2b31851cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6fdf045c211fe0a7195521bf1b8d5e1">ParseTemplateArgValueList</a> (SmallVectorImpl&lt; const ArgumentInit * &gt; &amp;Result, SmallVectorImpl&lt; SMLoc &gt; &amp;ArgLocs, Record *CurRec, const Record *ArgsRec)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d49e0617f1c5c41e68fcab6553c5c47">ParseDagArgList</a> (SmallVectorImpl&lt; std::pair&lt; const Init *, const StringInit * &gt; &gt; &amp;Result, Record *CurRec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDagArgList - Parse the argument list for a dag literal expression. <a href="#a1d49e0617f1c5c41e68fcab6553c5c47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05be8fbcdce3652a0acf26b10a11e898">ParseOptionalRangeList</a> (SmallVectorImpl&lt; unsigned &gt; &amp;Ranges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseOptionalRangeList - Parse either a range list in &lt;&gt;'s or nothing. <a href="#a05be8fbcdce3652a0acf26b10a11e898">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89432356ae298c4cf16ed7cfaf873aa3">ParseOptionalBitList</a> (SmallVectorImpl&lt; unsigned &gt; &amp;Ranges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseOptionalBitList - Parse either a bit list in {}'s or nothing. <a href="#a89432356ae298c4cf16ed7cfaf873aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typedinit">TypedInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81fb74c8c6762039d467d4c4bad545d7">ParseSliceElement</a> (Record *CurRec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSliceElement - Parse subscript or range. <a href="#a81fb74c8c6762039d467d4c4bad545d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typedinit">TypedInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7a8743b7a8e4826958d4174f078e405">ParseSliceElements</a> (Record *CurRec, bool Single=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSliceElements - Parse subscripts in square brackets. <a href="#ab7a8743b7a8e4826958d4174f078e405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35d067a4c56fc746a3e3cd27f1071ea2">ParseRangeList</a> (SmallVectorImpl&lt; unsigned &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseRangeList - Parse a list of scalars and ranges into scalar values. <a href="#a35d067a4c56fc746a3e3cd27f1071ea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e943773b15626c21acd8bf74d8ff01">ParseRangePiece</a> (SmallVectorImpl&lt; unsigned &gt; &amp;Ranges, const TypedInit *FirstItem=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseRangePiece - Parse a bit/value range. <a href="#ac4e943773b15626c21acd8bf74d8ff01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e9585b6815b422bad1e16466979130">ParseType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseType - Parse and return a tblgen type. <a href="#a41e9585b6815b422bad1e16466979130">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67d2b5babe1381cedd82163ee56f18c6">ParseOperation</a> (Record *CurRec, const RecTy *ItemType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseOperation - Parse an operator. <a href="#a67d2b5babe1381cedd82163ee56f18c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25113a91699d31ffd8b0e7bf4e7f1435">ParseOperationSubstr</a> (Record *CurRec, const RecTy *ItemType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the !substr operation. <a href="#a25113a91699d31ffd8b0e7bf4e7f1435">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f7628b19468c6bb3c05095927a53b4b">ParseOperationFind</a> (Record *CurRec, const RecTy *ItemType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the !find operation. <a href="#a7f7628b19468c6bb3c05095927a53b4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad882e62920391e22bc688fecbc266b29">ParseOperationForEachFilter</a> (Record *CurRec, const RecTy *ItemType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the !foreach and !filter operations. <a href="#ad882e62920391e22bc688fecbc266b29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a789830d566836e8fd06c2903852e1c84">ParseOperationCond</a> (Record *CurRec, const RecTy *ItemType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e2a4bcea2de05519d668e65c1df816">ParseOperatorType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseOperatorType - Parse a type for an operator. <a href="#a57e2a4bcea2de05519d668e65c1df816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6684e3d0842870094f569b2d29bb8a">ParseObjectName</a> (MultiClass *CurMultiClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseObjectName - If a valid object name is specified, return it. <a href="#ace6684e3d0842870094f569b2d29bb8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a988bf9b6a4fcd2ee27bb9a2d2db1102f">ParseClassID</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseClassID - Parse and resolve a reference to a class name. <a href="#a988bf9b6a4fcd2ee27bb9a2d2db1102f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d97963ed3c3db3bb9d6b362c6a9af43">ParseMultiClassID</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseMultiClassID - Parse and resolve a reference to a multiclass name. <a href="#a4d97963ed3c3db3bb9d6b362c6a9af43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1955a971f39df77d3c263e878e5177c8">ApplyLetStack</a> (Record *CurRec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the current let bindings to <em>CurRec</em>. <a href="#a1955a971f39df77d3c263e878e5177c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1077c51a265e32dcb9663aa1c8c8bbca">ApplyLetStack</a> (RecordsEntry &amp;Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the current let bindings to the <a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a>. <a href="#a1077c51a265e32dcb9663aa1c8c8bbca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799a00ae9c67002d49fe0ed5eaac64d0">CheckTemplateArgValues</a> (SmallVectorImpl&lt; const ArgumentInit * &gt; &amp;Values, ArrayRef&lt; SMLoc &gt; ValuesLocs, const Record *ArgsRec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tglexer">TGLexer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51e7fc0e5fb61cfed1a0565740036dc0">Lex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/letrecord">LetRecord</a>, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58450cbc341985da347babf2104d04e">LetStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23dbce3fc1ab53434e85c7549619a8b1">MultiClasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a368f995443a8cea7a7c7dffb3ae5a0da">TypeAliases</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77d7f20345688bbe8ef048f553a75bad">Loops</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loops - Keep track of any foreach loops we are within. <a href="#a77d7f20345688bbe8ef048f553a75bad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/defsetrecord">DefsetRecord</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4248da5d3d42838489af48e85fb0be3">Defsets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc7d11ae304700336326c9d4af6dc6a7">CurMultiClass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CurMultiClass - If we are parsing a 'multiclass' definition, this is the current value. <a href="#abc7d11ae304700336326c9d4af6dc6a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad4db3e3d37d65f4dfa63fd02f9fd24f">CurScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CurScope - Innermost of the current nested scopes for 'defvar' variables. <a href="#aad4db3e3d37d65f4dfa63fd02f9fd24f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa19b5bd44a5c9bdcdcfd4833a3137ae2">Records</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3acf859137eb0befaf381debc9c994c2">NoWarnOnUnusedTemplateArgs</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e7d06bf91f49f61b9617bca898de04">TrackReferenceLocs</a> = false</td>
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


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ArgValueHandler {#ac8468db4f5ce9ce5baace61c48723396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TGParser::ArgValueHandler =  std::function&lt;void(const Init *, const Init *)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### SubstStack {#abfa5867e82549e21c22ec1e622f9da66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TGParser::SubstStack =  SmallVector&lt;std::pair&lt;const Init *, const Init *&gt;, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### IDParseMode {#aa3955833ae4b6607c50af4c2a66fae9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TGParser::IDParseMode </td>
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
<td class="doxyEnumItemName">ParseValueMode<a id="aa3955833ae4b6607c50af4c2a66fae9daeaeb9c2dbb58948a215e65798ddc947d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ParseNameMode<a id="aa3955833ae4b6607c50af4c2a66fae9da6afe37124596590c5edaa02486b1e4cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TGParser() {#accb79a047abfe9f327a7595d58d04b61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TGParser::TGParser (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; Macros, <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; records, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool NoWarnOnUnusedTemplateArgs=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool TrackReferenceLocs=false)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Error() {#a88a8d625cb0f5b05c02959e439f9a3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TGParser::Error (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a37310d4cb640733ed81281942c314d05">llvm::PrintError</a>.</p>

</div>
</div>

### getDependencies() {#a58685cdd792796ad7d316a781ebd7089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TGLexer::DependenciesSetTy &amp; llvm::TGParser::getDependencies ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp/#a5cdb223afb9f4268a3716aaac56826bd">createDependencyFile</a>.</p>

</div>
</div>

### ParseFile() {#adf2220b1390559e48081eb1187622748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseFile - Main entrypoint for parsing a tblgen file.</p>


<p>These parser routines return true on error, or false on success.</p>


<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4405 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5ad5504ffda0efa1de5ca3294f5ea86bbf">llvm::tgtok::Eof</a>, <a href="#a050e3ccb0e5c0b55cb30615217398b52">PopScope</a>, <a href="#af0c749c975468baeb15fb9757c58a48d">PushScope</a> and <a href="#ab5db391a5f2cba3c4a78e69e1ddb3fd2">TokError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### PopScope() {#a050e3ccb0e5c0b55cb30615217398b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TGParser::PopScope (<a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> * ExpectedStackTop)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#adf2220b1390559e48081eb1187622748">ParseFile</a>.</p>

</div>
</div>

### PushScope() {#af0c749c975468baeb15fb9757c58a48d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TGVarScope * llvm::TGParser::PushScope ()</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="#adf2220b1390559e48081eb1187622748">ParseFile</a>.</p>

</div>
</div>

### PushScope() {#ab3100229bcd453690b137edb3871ee7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TGVarScope * llvm::TGParser::PushScope (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * Rec)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### PushScope() {#a899a19e6bae243782e1ba66bee2c8994}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TGVarScope * llvm::TGParser::PushScope (<a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> * Loop)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### PushScope() {#ad8e316b3eecce4817b10beaaf482151d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TGVarScope * llvm::TGParser::PushScope (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * Multiclass)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### TokError() {#ab5db391a5f2cba3c4a78e69e1ddb3fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TGParser::TokError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>.</p>


<p>Referenced by <a href="#adf2220b1390559e48081eb1187622748">ParseFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDefOne() {#ad09891ad31b97c85a8874755b9e592c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::addDefOne (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> &gt; Rec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve the record fully and add it to the record keeper.</p>

<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### addEntry() {#a22264cec4b430a2c159717a9f566eb0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::addEntry (<a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a> E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a record, foreach loop, or assertion to the current context.</p>

<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### AddSubClass() {#a1448223f3ed5019a9c551b6d4d116b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::AddSubClass (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * Rec, <a href="/web-llvm/docs/api/structs/llvm/subclassreference">SubClassReference</a> &amp; SubClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddSubClass - Add SubClass as a subclass to CurRec, resolving its template args as SubClass's template arguments.</p>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### AddSubClass() {#a0ef1eef57f74abd5a24099f4021acaa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::AddSubClass (<a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a> &amp; Entry, <a href="/web-llvm/docs/api/structs/llvm/subclassreference">SubClassReference</a> &amp; SubClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### AddSubMultiClass() {#afe998559bb299a9ff0887369405e2ab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::AddSubMultiClass (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMC, <a href="/web-llvm/docs/api/structs/llvm/submulticlassreference">SubMultiClassReference</a> &amp; SubMultiClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddSubMultiClass - Add SubMultiClass as a subclass to CurMC, resolving its template args as SubMultiClass's template arguments.</p>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### AddValue() {#ae1fd5cc67aa5c3839e40638ad75d739c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::AddValue (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * TheRec, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> &amp; RV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ApplyLetStack() {#a1955a971f39df77d3c263e878e5177c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ApplyLetStack (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply the current let bindings to <em>CurRec</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true on error, false otherwise.</p></dd>
</dl>


<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3570 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ApplyLetStack() {#a1077c51a265e32dcb9663aa1c8c8bbca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ApplyLetStack (<a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a> &amp; Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply the current let bindings to the <a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a>.</p>

<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3579 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### CheckTemplateArgValues() {#a799a00ae9c67002d49fe0ed5eaac64d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::CheckTemplateArgValues (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argumentinit">ArgumentInit</a> * &gt; &amp; Values, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt; ValuesLocs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * ArgsRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4423 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### consume() {#a25c0430438b38081597a768d5452de35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::consume (<a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseAssert() {#ac3a7dfeaf4a840a37b0ce604735a97fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseAssert (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMultiClass, <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseAssert - Parse an assert statement.</p>


<p>Assert ::= ASSERT condition , message ;</p>


<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3963 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseBody() {#a2d37ad634be013e9358c05ebf3cd28d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseBody (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseBody - Read the body of a class or def.</p>


<p>Return true on error, false on success.</p>


<p>Body ::= ';' Body ::= '{' BodyList '}' BodyList BodyItem*</p>


<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3543 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseBodyItem() {#aaf8a4bf2d2bdf87c69a04e7e0dbfa9ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseBodyItem (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseBodyItem - Parse a single item within the body of a def or class.</p>


<p>BodyItem ::= Declaration ';' BodyItem ::= LET <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> OptionalBitList '=' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ';' BodyItem ::= Defvar BodyItem ::= Dump BodyItem ::= Assert</p>


<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3481 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseClass() {#a3894b83a9e85605f909a21cfb54bae09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseClass - Parse a tblgen class definition.</p>


<p>ClassInst ::= CLASS <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> TemplateArgList? ObjectBody</p>


<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3996 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseClassID() {#a988bf9b6a4fcd2ee27bb9a2d2db1102f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Record * TGParser::ParseClassID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseClassID - Parse and resolve a reference to a class name.</p>


<p>This returns null on error.</p>


<p>ClassID ::= <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></p>


<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseDagArgList() {#a1d49e0617f1c5c41e68fcab6553c5c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TGParser::ParseDagArgList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a> * &gt; &gt; &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDagArgList - Parse the argument list for a dag literal expression.</p>


<p>DagArg ::= <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> (':' VARNAME)? DagArg ::= VARNAME DagArgList ::= DagArg DagArgList ::= DagArgList ',' DagArg</p>


<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3136 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseDeclaration() {#a3e6e0ba477c95c6f61d5487d7481b791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseDeclaration (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, bool ParsingTemplateArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDeclaration - Read a declaration, returning the name of field <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, or an empty string on error.</p>


<p>This can happen in a number of different contexts, including within a def or in the template args for a class (in which case CurRec will be non-null) and within the template args for a multiclass (in which case CurRec will be null, but CurMultiClass will be set). This can also happen within a def that is within a multiclass, which will set both CurRec and CurMultiClass.</p>


<p>Declaration ::= FIELD? <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> ('=' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)?</p>


<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3286 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseDef() {#ad226db4ed50e913b4829e3583fd17e2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseDef (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMultiClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDef - Parse and return a top level or multiclass record definition.</p>


<p>Return false if okay, true if error.</p>


<p>DefInst ::= DEF ObjectName ObjectBody</p>


<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3643 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseDefm() {#a816a1546393b89a4cf7b132a4373ae79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseDefm (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMultiClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDefm - Parse the instantiation of a multiclass.</p>


<p>DefMInst ::= DEFM <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> ':' DefmSubClassRef ';'</p>


<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4247 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseDefset() {#a3dea9c175324f04154f7cbaa09ff2e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseDefset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDefset - Parse a defset statement.</p>


<p>Defset ::= DEFSET <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Id '=' '{' ObjectList '}'</p>


<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3676 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseDeftype() {#aecbb529e8adfe38a61c3e69826fb1297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseDeftype ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDeftype - Parse a defvar statement.</p>


<p>Deftype ::= DEFTYPE Id '=' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ';'</p>


<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3722 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseDefvar() {#a1248ddc95c5697be7a81fe2958afee3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseDefvar (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDefvar - Parse a defvar statement.</p>


<p>Defvar ::= DEFVAR Id '=' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ';'</p>


<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3758 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseDump() {#a8e07706cd397714199f0c52836be824a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseDump (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMultiClass, <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4490 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseForeach() {#aca24eab98dd4587c68b6c2f7db1852d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseForeach (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMultiClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseForeach - Parse a for statement.</p>


<p>Return the record corresponding to it. This returns true on error.</p>


<p>Foreach ::= FOREACH Declaration IN '{ ObjectList '}' Foreach ::= FOREACH Declaration IN Object</p>


<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3805 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseForeachDeclaration() {#a6b6c82cafcfc76dcd8a2a7106820574c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VarInit * TGParser::ParseForeachDeclaration (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *&amp; ForeachListValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseForeachDeclaration - Read a foreach declaration, returning the name of the declared object or a NULL <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> on error.</p>


<p>Return the name of the parsed initializer list through ForeachListName.</p>


<p>ForeachDeclaration ::= <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> '=' '{' RangeList '}' ForeachDeclaration ::= <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> '=' RangePiece ForeachDeclaration ::= <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> '=' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></p>


<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3361 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseIDValue() {#a32a27e94136c592062c52d9eb192e5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseIDValue (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> NameLoc, IDParseMode Mode=ParseValueMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseIDValue.</p>

<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseIf() {#a8b2ac83afb70de9ec74c747209e34d2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseIf (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMultiClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseIf - Parse an if statement.</p>


<p>If ::= IF <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> THEN IfBody If ::= IF <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> THEN IfBody ELSE IfBody</p>


<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3859 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseIfBody() {#ad207395a6a8d34598a8b9a6e9cdc7adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseIfBody (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMultiClass, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseIfBody - Parse the then-clause or else-clause of an if statement.</p>


<p>IfBody ::= Object IfBody ::= '{' ObjectList '}'</p>


<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3933 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseLetList() {#a574184346dbce246238e1c01069c08cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TGParser::ParseLetList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/letrecord">LetRecord</a> &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseLetList - Parse a non-empty list of assignment expressions into a list of LetRecords.</p>


<p>LetList ::= LetItem (',' LetItem)* LetItem ::= <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> OptionalRangeList '=' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></p>


<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4050 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseMultiClass() {#a33db554af03479d5863f9d23ac839853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseMultiClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseMultiClass - Parse a multiclass definition.</p>


<p>MultiClassInst ::= MULTICLASS <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> TemplateArgList? ':' BaseMultiClassList '{' MultiClassObject+ '}' MultiClassObject ::= Assert MultiClassObject ::= DefInst MultiClassObject ::= DefMInst MultiClassObject ::= Defvar MultiClassObject ::= Foreach MultiClassObject ::= If MultiClassObject ::= LETCommand '{' ObjectList '}' MultiClassObject ::= LETCommand Object</p>


<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4149 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseMultiClassID() {#a4d97963ed3c3db3bb9d6b362c6a9af43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MultiClass * TGParser::ParseMultiClassID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseMultiClassID - Parse and resolve a reference to a multiclass name.</p>


<p>This returns null on error.</p>


<p>MultiClassID ::= <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></p>


<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseObject() {#a9b717f35699aded00ea02bf21cb6a50a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseObject (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * MC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseObject Object ::= ClassInst Object ::= DefInst Object ::= MultiClassInst Object ::= DefMInst Object ::= LETCommand '{' ObjectList '}' Object ::= LETCommand Object Object ::= Defset Object ::= Deftype Object ::= Defvar Object ::= Assert Object ::= Dump.</p>

<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4362 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseObjectBody() {#aaf98e35dec734091521872790473753c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseObjectBody (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseObjectBody - Parse the body of a def or class.</p>


<p>This consists of an optional ClassList followed by a Body. CurRec is the current def or class that is being parsed.</p>


<p>ObjectBody ::= BaseClassList Body BaseClassList ::= /*empty*‍/ BaseClassList ::= ':' BaseClassListNE BaseClassListNE ::= SubClassRef (',' SubClassRef)*</p>


<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3608 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseObjectList() {#a568150af076e5d2e698a96f19a72226b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseObjectList (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * MC=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseObjectList ObjectList :== Object*.</p>

<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4397 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseObjectName() {#ace6684e3d0842870094f569b2d29bb8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseObjectName (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMultiClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseObjectName - If a valid object name is specified, return it.</p>


<p>If no name is specified, return the unset initializer. Return nullptr on parse error. ObjectName ::= <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> [ '#' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ]* ObjectName ::= /*empty*‍/</p>


<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseOperation() {#a67d2b5babe1381cedd82163ee56f18c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseOperation (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * ItemType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseOperation - Parse an operator.</p>


<p>This returns null on error.</p>


<p>Operation ::= XOperator ['&lt;' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> '&gt;'] '(' Args ')'</p>


<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseOperationCond() {#a789830d566836e8fd06c2903852e1c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseOperationCond (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * ItemType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 2549 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseOperationFind() {#a7f7628b19468c6bb3c05095927a53b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseOperationFind (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * ItemType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the !find operation.</p>


<p>Return null on error.</p>


<p>Substr ::= !find(string, string [, start-int]) =&gt; int</p>


<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 2334 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseOperationForEachFilter() {#ad882e62920391e22bc688fecbc266b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseOperationForEachFilter (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * ItemType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the !foreach and !filter operations.</p>


<p>Return null on error.</p>


<p>ForEach ::= !foreach(<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, list-or-dag, expr) =&gt; list&lt;expr type&gt; Filter ::= !foreach(<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, list, predicate) ==&gt; list&lt;list type&gt;</p>


<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 2424 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseOperationSubstr() {#a25113a91699d31ffd8b0e7bf4e7f1435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseOperationSubstr (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * ItemType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the !substr operation.</p>


<p>Return null on error.</p>


<p>Substr ::= !substr(string, start-int [, length-int]) =&gt; string</p>


<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 2245 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseOperatorType() {#a57e2a4bcea2de05519d668e65c1df816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RecTy * TGParser::ParseOperatorType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseOperatorType - Parse a type for an operator.</p>


<p>This returns null on error.</p>


<p>OperatorType ::= '&lt;' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> '&gt;'</p>


<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 2216 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseOptionalBitList() {#a89432356ae298c4cf16ed7cfaf873aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseOptionalBitList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Ranges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseOptionalBitList - Parse either a bit list in {}'s or nothing.</p>


<p>OptionalBitList ::= '{' RangeList '}' OptionalBitList ::= /*empty*‍/</p>


<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseOptionalRangeList() {#a05be8fbcdce3652a0acf26b10a11e898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseOptionalRangeList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Ranges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseOptionalRangeList - Parse either a range list in &lt;&gt;'s or nothing.</p>


<p>OptionalRangeList ::= '&lt;' RangeList '&gt;' OptionalRangeList ::= /*empty*‍/</p>


<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseRangeList() {#a35d067a4c56fc746a3e3cd27f1071ea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TGParser::ParseRangeList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseRangeList - Parse a list of scalars and ranges into scalar values.</p>


<p>RangeList ::= RangePiece (',' RangePiece)*</p>


<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseRangePiece() {#ac4e943773b15626c21acd8bf74d8ff01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseRangePiece (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Ranges, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typedinit">TypedInit</a> * FirstItem=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseRangePiece - Parse a bit/value range.</p>


<p>RangePiece ::= INTVAL RangePiece ::= INTVAL '...' INTVAL RangePiece ::= INTVAL '-' INTVAL RangePiece ::= INTVAL INTVAL</p>


<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 978 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseSimpleValue() {#a1e98cf0cae28a494bb33ebc83e9c7235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseSimpleValue (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * ItemType=nullptr, IDParseMode Mode=ParseValueMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSimpleValue - Parse a tblgen value.</p>


<p>This returns null on error.</p>


<p>SimpleValue ::= IDValue SimpleValue ::= INTVAL SimpleValue ::= STRVAL+ SimpleValue ::= CODEFRAGMENT SimpleValue ::= '?' SimpleValue ::= '{' ValueList '}' SimpleValue ::= <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> '&lt;' ValueListNE '&gt;' SimpleValue ::= '[' ValueList ']' SimpleValue ::= '(' IDValue DagArgList ')' SimpleValue ::= CONCATTOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= ADDTOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= DIVTOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= SUBTOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= SHLTOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= SRATOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= SRLTOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= LISTCONCATTOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= LISTSPLATTOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= LISTREMOVETOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= RANGE '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= RANGE '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= RANGE '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= STRCONCATTOK '(' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ')' SimpleValue ::= COND '(' [<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ':' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>,]+ ')'</p>


<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 2655 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseSliceElement() {#a81fb74c8c6762039d467d4c4bad545d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TypedInit * TGParser::ParseSliceElement (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSliceElement - Parse subscript or range.</p>


<p>SliceElement ::= <a href="/web-llvm/docs/api/classes/llvm/value">Value&lt;list&lt;int&gt;&gt;</a> SliceElement ::= <a href="/web-llvm/docs/api/classes/llvm/value">Value&lt;int&gt;</a> SliceElement ::= <a href="/web-llvm/docs/api/classes/llvm/value">Value&lt;int&gt;</a> '...' <a href="/web-llvm/docs/api/classes/llvm/value">Value&lt;int&gt;</a> SliceElement ::= <a href="/web-llvm/docs/api/classes/llvm/value">Value&lt;int&gt;</a> '-' <a href="/web-llvm/docs/api/classes/llvm/value">Value&lt;int&gt;</a> (deprecated) SliceElement ::= <a href="/web-llvm/docs/api/classes/llvm/value">Value&lt;int&gt;</a> INTVAL(Negative; deprecated)</p>


<p>SliceElement is either <a href="/web-llvm/docs/api/classes/llvm/intrecty">IntRecTy</a>, <a href="/web-llvm/docs/api/classes/llvm/listrecty">ListRecTy</a>, or nullptr</p>


<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseSliceElements() {#ab7a8743b7a8e4826958d4174f078e405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TypedInit * TGParser::ParseSliceElements (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, bool Single=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSliceElements - Parse subscripts in square brackets.</p>


<p>SliceElements ::= ( SliceElement ',' )* SliceElement ','?</p>


<p>SliceElement is either <a href="/web-llvm/docs/api/classes/llvm/intrecty">IntRecTy</a>, <a href="/web-llvm/docs/api/classes/llvm/listrecty">ListRecTy</a>, or nullptr</p>


<p>Returns <a href="/web-llvm/docs/api/classes/llvm/listrecty">ListRecTy</a> by defaut. Returns <a href="/web-llvm/docs/api/classes/llvm/intrecty">IntRecTy</a> if;</p>


<ul class="doxyList ">
<li>Single=true</li>
<li>SliceElements is <a href="/web-llvm/docs/api/classes/llvm/value">Value&lt;int&gt;</a> w/o trailing comma</li>
</ul>

<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseSubClassReference() {#a24f8b1496893ebbe3a0f18f450cbd33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubClassReference TGParser::ParseSubClassReference (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, bool isDefm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSubClassReference - Parse a reference to a subclass or a multiclass.</p>


<p>This returns a SubClassRefTy with a null Record* on error.</p>


<p>SubClassRef ::= ClassID SubClassRef ::= ClassID '&lt;' ArgValueList '&gt;'</p>


<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseSubMultiClassReference() {#ad4f5b479ebd3fe98f052bfa71231c5db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubMultiClassReference TGParser::ParseSubMultiClassReference (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSubMultiClassReference - Parse a reference to a subclass or to a templated submulticlass.</p>


<p>This returns a SubMultiClassRefTy with a null Record* on error.</p>


<p>SubMultiClassRef ::= MultiClassID SubMultiClassRef ::= MultiClassID '&lt;' ArgValueList '&gt;'</p>


<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseTemplateArgList() {#a5cfd6ea7690c0fd4b573519c0d6a0716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseTemplateArgList (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseTemplateArgList - Read a template argument list, which is a non-empty sequence of template-declarations in &lt;&gt;'s.</p>


<p>If CurRec is non-null, these are template args for a class. If null, these are the template args for a multiclass.</p>


<p>TemplateArgList ::= '&lt;' Declaration (',' Declaration)* '&gt;'</p>


<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3441 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseTemplateArgValueList() {#ac6fdf045c211fe0a7195521bf1b8d5e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseTemplateArgValueList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argumentinit">ArgumentInit</a> * &gt; &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt; &amp; ArgLocs, <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * ArgsRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3208 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseTopLevelLet() {#ab31750a4a9193f24692af53e7ea845e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::ParseTopLevelLet (<a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * CurMultiClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseTopLevelLet - Parse a 'let' at top level.</p>


<p>This can be a couple of different related productions. This works inside multiclasses too.</p>


<p>Object ::= LET LetList IN '{' ObjectList '}' Object ::= LET LetList IN Object</p>


<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4093 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseType() {#a41e9585b6815b422bad1e16466979130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RecTy * TGParser::ParseType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseType - Parse and return a tblgen type.</p>


<p>This returns null on error.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ::= STRING // string type <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ::= CODE // code type <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ::= BIT // bit type <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ::= BITS '&lt;' INTVAL '&gt;' // bits&lt;x&gt; type <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ::= INT // int type <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ::= LIST '&lt;' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> '&gt;' // list&lt;x&gt; type <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ::= DAG // dag type <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ::= ClassID // <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a></p>


<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseValue() {#a1d5a448d985bdcee64ad98c890989ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGParser::ParseValue (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * ItemType=nullptr, IDParseMode Mode=ParseValueMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseValue - Parse a <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> value.</p>


<p>This returns null on error.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ::= SimpleValue ValueSuffix* ValueSuffix ::= '{' BitList '}' ValueSuffix ::= '[' SliceElements ']' ValueSuffix ::= '.' <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></p>


<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 2934 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### ParseValueList() {#a997b5c8dc94a1d6a514032a2b31851cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TGParser::ParseValueList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * &gt; &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * ItemType=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseValueList - Parse a comma separated list of values, returning them in a vector.</p>


<p>Note that this always expects to be able to parse at least one value. It returns an empty list if this is not possible.</p>


<p>ValueList ::= <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> (',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</p>


<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 3180 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### resolve() {#a6546bcd069ab87b015f188b0d148b9ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::resolve (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> &amp; Loop, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SubstStack</a> &amp; Substs, bool Final, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a> &gt; * Dest, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> * Loc=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve the entries in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a></span>, going over inner loops recursively and making the given subsitutions of (name, value) pairs.</p>


<p>The resulting records are stored in <span class="doxyComputerOutput">Dest</span> if non-null. Otherwise, they are added to the global record keeper.</p>


<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### resolve() {#a3663ff20a8d2fe19503b42a580861767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::resolve (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a> &gt; &amp; Source, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SubstStack</a> &amp; Substs, bool Final, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a> &gt; * Dest, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> * Loc=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve the entries in <span class="doxyComputerOutput">Source</span>, going over loops recursively and making the given substitutions of (name, value) pairs.</p>


<p>The resulting records are stored in <span class="doxyComputerOutput">Dest</span> if non-null. Otherwise, they are added to the global record keeper.</p>


<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### resolveArguments() {#a5b47b953c0ccc2b12e8ab77d5fcca5d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::resolveArguments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * Rec, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argumentinit">ArgumentInit</a> * &gt; ArgValues, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, ArgValueHandler ArgValueHandler=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *) {})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### resolveArgumentsOfClass() {#a972a3d6c67e123384dc7c4e5d3bb32ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::resolveArgumentsOfClass (<a href="/web-llvm/docs/api/classes/llvm/mapresolver">MapResolver</a> &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * Rec, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argumentinit">ArgumentInit</a> * &gt; ArgValues, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve the arguments of class and set them to <a href="/web-llvm/docs/api/classes/llvm/mapresolver">MapResolver</a>.</p>


<p>Returns true if failed.</p>


<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### resolveArgumentsOfMultiClass() {#a0e8b587d5eeb43e576b218aa7fca8a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::resolveArgumentsOfMultiClass (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SubstStack</a> &amp; Substs, <a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * MC, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argumentinit">ArgumentInit</a> * &gt; ArgValues, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * DefmName, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve the arguments of multiclass and store them into SubstStack.</p>


<p>Returns true if failed.</p>


<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

### SetValue() {#a456129bcd80efa5e0d91ab03dcf06f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGParser::SetValue (<a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * TheRec, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * ValName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; BitList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * V, bool AllowSelfAssignment=false, bool OverrideDefLoc=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the value of a <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a> within the given record.</p>


<p>SetValue - Return true on error, false on success.</p>


<p>If <span class="doxyComputerOutput">OverrideDefLoc</span> is set, the provided location overrides any existing location of the <a href="/web-llvm/docs/api/classes/llvm/recordval">RecordVal</a>.</p>


<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurMultiClass {#abc7d11ae304700336326c9d4af6dc6a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MultiClass* llvm::TGParser::CurMultiClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CurMultiClass - If we are parsing a 'multiclass' definition, this is the current value.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### CurScope {#aad4db3e3d37d65f4dfa63fd02f9fd24f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TGVarScope&gt; llvm::TGParser::CurScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CurScope - Innermost of the current nested scopes for 'defvar' variables.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### Defsets {#ab4248da5d3d42838489af48e85fb0be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DefsetRecord *, 2&gt; llvm::TGParser::Defsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### LetStack {#aa58450cbc341985da347babf2104d04e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SmallVector&lt;LetRecord, 4&gt; &gt; llvm::TGParser::LetStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### Lex {#a51e7fc0e5fb61cfed1a0565740036dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TGLexer llvm::TGParser::Lex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### Loops {#a77d7f20345688bbe8ef048f553a75bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;ForeachLoop&gt; &gt; llvm::TGParser::Loops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loops - Keep track of any foreach loops we are within.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### MultiClasses {#a23dbce3fc1ab53434e85c7549619a8b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, std::unique_ptr&lt;MultiClass&gt; &gt; llvm::TGParser::MultiClasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### NoWarnOnUnusedTemplateArgs {#a3acf859137eb0befaf381debc9c994c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TGParser::NoWarnOnUnusedTemplateArgs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### Records {#aa19b5bd44a5c9bdcdcfd4833a3137ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordKeeper&amp; llvm::TGParser::Records</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### TrackReferenceLocs {#a25e7d06bf91f49f61b9617bca898de04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TGParser::TrackReferenceLocs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### TypeAliases {#a368f995443a8cea7a7c7dffb3ae5a0da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, const RecTy *&gt; llvm::TGParser::TypeAliases</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
