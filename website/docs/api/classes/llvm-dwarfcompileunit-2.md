---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfcompileunit-2
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DwarfCompileUnit` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DwarfCompileUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">CodeGen/AsmPrinter/DwarfCompileUnit.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunit-2">DwarfUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This dwarf writer support class manages information associated with a source file. <a href="/web-llvm/docs/api/classes/llvm/dwarfunit-2/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69fd5b726df2fcc159fd50bc201f77a1">InlinedEntity</a> = <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#ad623a98e1212d4fb4d655e67828066be">DbgValueHistoryMap::InlinedEntity</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find abstract variable associated with Var. <a href="#a69fd5b726df2fcc159fd50bc201f77a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae379fa3c76d74051b87ccefe01c77b77">MDNodeSetVector</a> = <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, 4 &gt;, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad52017f371f28817067fc0ea956886e7">DwarfCompileUnit</a> (unsigned UID, const DICompileUnit *Node, AsmPrinter *A, DwarfDebug *DW, DwarfFile *DWU, UnitKind Kind=UnitKind::Full)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8db94fb6e067c46abe4207d31b8cb34">hasRangeLists</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d8fd9011312799cf4f440538b8cb79c">getSkeleton</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19052e5d06c02fdb8e572529d0acb8f6">includeMinimalInlineScopes</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaee698ea69682436f2ad91d3212fe55">emitFuncLineTableOffsets</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf6adcaa4ad6740a1a7544e827a5231">initStmtList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a780e3087cd40ac6f03e93e1722993cc2">applyStmtList</a> (DIE &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the DW_AT_stmt_list from this compile unit to the specified <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a780e3087cd40ac6f03e93e1722993cc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac84a303b99d4ac7659f9db66b3da8ef0">getLineTableStartSym</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get line table start symbol for this unit. <a href="#ac84a303b99d4ac7659f9db66b3da8ef0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd19f659a2944b4440bafe9f78a0809">getOrCreateGlobalVariableDIE</a> (const DIGlobalVariable *GV, ArrayRef&lt; GlobalExpr &gt; GlobalExprs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or create global variable <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a9bd19f659a2944b4440bafe9f78a0809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53bba044b64b7a894e30aeb52a247515">getOrCreateCommonBlock</a> (const DICommonBlock *CB, ArrayRef&lt; GlobalExpr &gt; GlobalExprs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6d364a5079f4f7a166cbaa1ba24ebb">addLocationAttribute</a> (DIE *ToDIE, const DIGlobalVariable *GV, ArrayRef&lt; GlobalExpr &gt; GlobalExprs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f8bac4a8c515d95110494a2ed662e5">addLabelAddress</a> (DIE &amp;Die, dwarf::Attribute Attribute, const MCSymbol *Label)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addLabelAddress - Add a dwarf label attribute data and value using either DW_FORM_addr or DW_FORM_GNU_addr_index. <a href="#ae7f8bac4a8c515d95110494a2ed662e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2ec97478e68f7a1d1570b6b058853b4">addLocalLabelAddress</a> (DIE &amp;Die, dwarf::Attribute Attribute, const MCSymbol *Label)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addLocalLabelAddress - Add a dwarf label attribute data and value using DW_FORM_addr only. <a href="#ac2ec97478e68f7a1d1570b6b058853b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45230644d6fe9517cbb489bb2f5b83e">getCU</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd839ab10698d2e52b0021818e8d9625">getOrCreateSourceID</a> (const DIFile *File) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the source <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the given file. <a href="#acd839ab10698d2e52b0021818e8d9625">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39cb0b18cc6f463c1d383db1ee6c6226">addRange</a> (RangeSpan Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addRange - Add an address range to the list of ranges for this unit. <a href="#a39cb0b18cc6f463c1d383db1ee6c6226">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b3f89703fa8ecd73c1b43a7ac656402">attachLowHighPC</a> (DIE &amp;D, const MCSymbol *Begin, const MCSymbol *End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a3a1f0710cf8260033c8eb18800175">updateSubprogramScopeDIE</a> (const DISubprogram *SP, MCSymbol *LineTableSym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given subprogram and attach appropriate DW_AT_low_pc, DW_AT_high_pc and DW_AT_LLVM_stmt_sequence attributes. <a href="#a11a3a1f0710cf8260033c8eb18800175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf65d0311d21263e1470c9c5f2ad57d8">constructScopeDIE</a> (LexicalScope *Scope, DIE &amp;ParentScopeDIE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e4e697039d4692563c2ccc3608864d1">addScopeRangeList</a> (DIE &amp;ScopeDIE, SmallVector&lt; RangeSpan, 2 &gt; Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function to construct a <a href="/web-llvm/docs/api/structs/llvm/rangespanlist">RangeSpanList</a> for a given lexical scope. <a href="#a4e4e697039d4692563c2ccc3608864d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8875ff9c8633acdeb1e970471f37f57">attachRangesOrLowHighPC</a> (DIE &amp;D, SmallVector&lt; RangeSpan, 2 &gt; Ranges)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d00bd782a8ae88d11495124673cd53">attachRangesOrLowHighPC</a> (DIE &amp;D, const SmallVectorImpl&lt; InsnRange &gt; &amp;Ranges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47e64bee9baa8d3436add9ec49d1c880">constructInlinedScopeDIE</a> (LexicalScope *Scope, DIE &amp;ParentScopeDIE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This scope represents an inlined body of a function. <a href="#a47e64bee9baa8d3436add9ec49d1c880">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac43078e4f82c8dea48b4a483de6f434a">constructLexicalScopeDIE</a> (LexicalScope *Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct new DW_TAG_lexical_block for this scope and attach DW_AT_low_pc/DW_AT_high_pc labels. <a href="#ac43078e4f82c8dea48b4a483de6f434a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a731f3ca3bc29b3acc59ef49fdb067f41">getLexicalBlockDIE</a> (const DILexicalBlock *LB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a>. <a href="#a731f3ca3bc29b3acc59ef49fdb067f41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e6b90f1ecca9999a225bac737d2fdc">constructVariableDIE</a> (DbgVariable &amp;DV, bool Abstract=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a>. <a href="#a90e6b90f1ecca9999a225bac737d2fdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a09bbbcfe5fb24876e63ca5b05f45a8">constructVariableDIE</a> (DbgVariable &amp;DV, const LexicalScope &amp;Scope, DIE *&amp;ObjectPointer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience overload which writes the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer into an out variable ObjectPointer in addition to returning it. <a href="#a4a09bbbcfe5fb24876e63ca5b05f45a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6d394e7617fdbb955ce7db1fc9aaff7">constructLabelDIE</a> (DbgLabel &amp;DL, const LexicalScope &amp;Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given <a href="/web-llvm/docs/api/classes/llvm/dbglabel">DbgLabel</a>. <a href="#ad6d394e7617fdbb955ce7db1fc9aaff7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c89d112b2f04f66826428c19d11301b">createBaseTypeDIEs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6f34c53b2dbad48a28b675922003e1">getOrCreateContextDIE</a> (const DIScope *Ty) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for a given scope. <a href="#a7b6f34c53b2dbad48a28b675922003e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cbe3dd2e5c24c363d750bd49f46838a">constructSubprogramScopeDIE</a> (const DISubprogram *Sub, LexicalScope *Scope, MCSymbol *LineTableSym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for this subprogram scope. <a href="#a8cbe3dd2e5c24c363d750bd49f46838a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a> (LexicalScope *Scope, DIE &amp;ScopeDIE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a150001a8f1d0061691188b80802e0365">constructAbstractSubprogramScopeDIE</a> (LexicalScope *Scope)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021658afc8b95fca777f7f6ebc36aa8c">useGNUAnalogForDwarf5Feature</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to use the GNU analog for a DWARF5 tag, attribute, or location atom. <a href="#a021658afc8b95fca777f7f6ebc36aa8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff931a71f37552aeef5c2ef16e950c3">getDwarf5OrGNUTag</a> (dwarf::Tag Tag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This takes a DWARF 5 tag and returns it or a GNU analog. <a href="#a0ff931a71f37552aeef5c2ef16e950c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5146bedc026123984b5193c0a6e94af">getDwarf5OrGNUAttr</a> (dwarf::Attribute Attr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This takes a DWARF 5 attribute and returns it or a GNU analog. <a href="#ab5146bedc026123984b5193c0a6e94af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0c">dwarf::LocationAtom</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9374110f110bab23d52438a26f629216">getDwarf5OrGNULocationAtom</a> (dwarf::LocationAtom Loc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This takes a DWARF 5 location atom and either returns it or a GNU analog. <a href="#a9374110f110bab23d52438a26f629216">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f002d26ef8a98b14c82c510d49e26b2">constructCallSiteEntryDIE</a> (DIE &amp;ScopeDIE, const DISubprogram *CalleeSP, bool IsTail, const MCSymbol *PCAddr, const MCSymbol *CallAddr, unsigned CallReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a call site entry <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> describing a call within <span class="doxyComputerOutput">Scope</span> to a callee described by <span class="doxyComputerOutput">CalleeSP</span>. <a href="#a3f002d26ef8a98b14c82c510d49e26b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0284131decd7881e49a1dc2b82e4ac58">constructCallSiteParmEntryDIEs</a> (DIE &amp;CallSiteDIE, SmallVector&lt; DbgCallSiteParam, 4 &gt; &amp;Params)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct call site parameter DIEs for the <span class="doxyComputerOutput">CallSiteDIE</span>. <a href="#a0284131decd7881e49a1dc2b82e4ac58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b6f98e91ce662c3a7a89705a00ef67f">getOrCreateImportedEntityDIE</a> (const DIImportedEntity *IE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for an imported entity. <a href="#a1b6f98e91ce662c3a7a89705a00ef67f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af154345e2837458e53079bc2eaf50ee2">constructImportedEntityDIE</a> (const DIImportedEntity *IE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5821362beb37693123202b5e35d15a">finishSubprogramDefinition</a> (const DISubprogram *SP)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3554b83e3e334e00da341d9aba81a47e">finishEntityDefinition</a> (const DbgEntity *Entity)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9c9bcc6b272753369d8b7d322c879c8">getExistingAbstractEntity</a> (const DINode *Node)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77347a4881397840dcd27b24ce537976">createAbstractEntity</a> (const DINode *Node, LexicalScope *Scope)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa31a57991dc2dd622d2a4f911fbe05d5">setSkeleton</a> (DwarfCompileUnit &amp;Skel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the skeleton unit associated with this unit. <a href="#aa31a57991dc2dd622d2a4f911fbe05d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e5a7772e91857ecf8d244dd25a1baf1">getHeaderSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the size of a header for this unit, not including the initial length field. <a href="#a0e5a7772e91857ecf8d244dd25a1baf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d4481aea40e318a364df01ae10d308">getLength</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c18db764d4e597a32d9ae44e2953cd3">emitHeader</a> (bool UseOffsets) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the header for this unit, not including the initial length field. <a href="#a0c18db764d4e597a32d9ae44e2953cd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3abb9664e1a14148cc2ad7f330009b20">addAddrTableBase</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the DW_AT_addr_base attribute to the unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a3abb9664e1a14148cc2ad7f330009b20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408063a00dcf4cf82daa52612bdb726a">getMacroLabelBegin</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742e325bd655dc33c538065902d73a9e">addGlobalName</a> (StringRef Name, const DIE &amp;Die, const DIScope *Context) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new global name to the compile unit. <a href="#a742e325bd655dc33c538065902d73a9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3365d623c06b679b5852addcbe4214c6">addGlobalNameForTypeUnit</a> (StringRef Name, const DIScope *Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new global name present in a type unit to this compile unit. <a href="#a3365d623c06b679b5852addcbe4214c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac514ce80941fff1bd81f371317a2f8b8">addGlobalTypeImpl</a> (const DIType *Ty, const DIE &amp;Die, const DIScope *Context) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new global type to the compile unit. <a href="#ac514ce80941fff1bd81f371317a2f8b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad94baae1a66e6173dc2f9ee860fc7d8d">addGlobalTypeUnitType</a> (const DIType *Ty, const DIScope *Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new global type present in a type unit to this compile unit. <a href="#ad94baae1a66e6173dc2f9ee860fc7d8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65e0a2dfe95734e2049e6602fc65f83">getGlobalNames</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adde26643b9a29b6fbca26a7d2aa1693b">getGlobalTypes</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56065e436441774c9323601217eff992">addVariableAddress</a> (const DbgVariable &amp;DV, DIE &amp;Die, MachineLocation Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add DW_AT_location attribute for a <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> based on provided <a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a>. <a href="#a56065e436441774c9323601217eff992">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab71e26dc84728f514a94593242e6d931">addAddress</a> (DIE &amp;Die, dwarf::Attribute Attribute, const MachineLocation &amp;Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an address attribute to a die based on the location provided. <a href="#ab71e26dc84728f514a94593242e6d931">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef8395275fb33cea31395023a1df1d54">addComplexAddress</a> (const DIExpression *DIExpr, DIE &amp;Die, dwarf::Attribute Attribute, const MachineLocation &amp;Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start with the address based on the location provided, and generate the DWARF information necessary to find the actual variable (navigating the extra location information encoded in the type) based on the starting location. <a href="#aef8395275fb33cea31395023a1df1d54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8e1f64509dc4e7c6a0ee7ea1592cdf3">addLocationList</a> (DIE &amp;Die, dwarf::Attribute Attribute, unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a Dwarf loclistptr attribute data and value. <a href="#ae8e1f64509dc4e7c6a0ee7ea1592cdf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f1c08f4c14daab9f9b9bd3502b0b384">applyCommonDbgVariableAttributes</a> (const DbgVariable &amp;Var, DIE &amp;VariableDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add attributes to <span class="doxyComputerOutput">Var</span> which reflect the common attributes of <span class="doxyComputerOutput">VariableDie</span>, namely those which are not dependant on the active variant. <a href="#a7f1c08f4c14daab9f9b9bd3502b0b384">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a8483dca80b0435c63148629476aaf">addExpr</a> (DIELoc &amp;Die, dwarf::Form Form, const MCExpr *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a Dwarf expression attribute data and value. <a href="#ab1a8483dca80b0435c63148629476aaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e16a00186a0cb4e8265515d9bbebb93">applySubprogramAttributesToDefinition</a> (const DISubprogram *SP, DIE &amp;SPDie)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab848ab31ed9686e47adbc3cd56c7a1f1">applyLabelAttributes</a> (const DbgLabel &amp;Label, DIE &amp;LabelDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rangespan">RangeSpan</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca21dd57a82d69c505bacff94e79f74">getRanges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRanges - Get the list of ranges for this unit. <a href="#acca21dd57a82d69c505bacff94e79f74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rangespan">RangeSpan</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dac2039805bd7eef2e24c4f8bab19be">takeRanges</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3b1932132a240e60eb9a336f16685f">setBaseAddress</a> (const MCSymbol *Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b0fd581ce4e48abe3900bad5eb8a1b">getBaseAddress</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5304aa2b4acf341571b67df6ba125efa">getDWOId</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc18cc6156ebe4a69d0e9e6f5073081d">setDWOId</a> (uint64_t DwoId)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade4388f12ad1757626e62ed0e1da6cf8">hasDwarfPubSections</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a255424b02147849a3f013d1dc7d8b544">addBaseTypeRef</a> (DIEValueList &amp;Die, int64_t Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">MDNodeSetVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6faa304af988d1f525a9e5139412ca">getDeferredLocalDecls</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5521057959001396fa26a2e8c5aab93f">isDwoUnit</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d990804dfc693370a2adabc2b408e3">getAbstractScopeDIEs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a> &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7960c18c7eb6f13b6d89e90f77839e1b">getAbstractEntities</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9189d91e2ad4fdcafa2bcabb2416d0c4">finishNonUnitTypeDIE</a> (DIE &amp;D, const DICompositeType *CTy) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f0e82cc10b33ad64eb683bad3c8c31">addWasmRelocBaseGlobal</a> (DIELoc *Loc, StringRef GlobalName, uint64_t GlobalIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add info for Wasm-global-based relocation. <a href="#a95f0e82cc10b33ad64eb683bad3c8c31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfcompileunit/basetyperef">BaseTypeRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415b620309aed1e1be14fbb29ae5adaa">ExprRefedBaseTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf4085b668a609bf97761b8538ab028">HasRangeLists</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a826dbe696bfe80107b079c2037b339">LineTableStartSym</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The start of the unit line section, this is also reused in appyStmtList. <a href="#a8a826dbe696bfe80107b079c2037b339">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a4892d7e6a08612fcfa2e1cfde588f7">Skeleton</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skeleton unit associated with this unit. <a href="#a1a4892d7e6a08612fcfa2e1cfde588f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223cf2d20aae5ba92dbf79b9149d2d25">MacroLabelBegin</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The start of the unit macro info within macro section. <a href="#a223cf2d20aae5ba92dbf79b9149d2d25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac55c33958e5b3386a0becd839e317e30">GlobalNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalNames - A map of globally visible named entities for this unit. <a href="#ac55c33958e5b3386a0becd839e317e30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d55b538fcc1945a9f868c8fe757a107">GlobalTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalTypes - A map of globally visible types for this unit. <a href="#a8d55b538fcc1945a9f868c8fe757a107">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rangespan">RangeSpan</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f62c2ed3a0fbc376894cca24787229">CURanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3884246dd85237f280b8af97cbd7b14d">BaseAddress</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">MDNodeSetVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18d134ad06b80e5cf536760156d8fed6">DeferredLocalDecls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f283be56c8ad8ff81ee1997bf40b97">LexicalBlockDIEs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78967a5c9a9ac873d176d8340e427ff">AbstractLocalScopeDIEs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe46f94798b06918c1a1c57ae3d474fa">AbstractEntities</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa255852116b6b8b8c7d0e5b4f46ab51">DWOId</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DWO <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for correlating skeleton and split units. <a href="#afa255852116b6b8b8c7d0e5b4f46ab51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fed3b73876ece0036312baf6a6d148b">LastFile</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98fee2ba144a6109171c5d4153488416">LastFileID</a></td>
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

## applyConcreteDbgVariableAttribute Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44176145a8a847b3392dbce8e9d2ae8">applyConcreteDbgVariableAttributes</a> (const Loc::Single &amp;Single, const DbgVariable &amp;DV, DIE &amp;VariableDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See applyConcreteDbgVariableAttribute. <a href="#ad44176145a8a847b3392dbce8e9d2ae8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a79f7c9cce95a6fbd98fef45808fa45">applyConcreteDbgVariableAttributes</a> (const Loc::Multi &amp;Multi, const DbgVariable &amp;DV, DIE &amp;VariableDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See applyConcreteDbgVariableAttribute. <a href="#a9a79f7c9cce95a6fbd98fef45808fa45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726573af3e68dbcb5b752229d03f8744">applyConcreteDbgVariableAttributes</a> (const Loc::MMI &amp;MMI, const DbgVariable &amp;DV, DIE &amp;VariableDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See applyConcreteDbgVariableAttribute. <a href="#a726573af3e68dbcb5b752229d03f8744">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b4ab6cab8964c9f60de8e0e0772324f">applyConcreteDbgVariableAttributes</a> (const Loc::EntryValue &amp;EntryValue, const DbgVariable &amp;DV, DIE &amp;VariableDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See applyConcreteDbgVariableAttribute. <a href="#a4b4ab6cab8964c9f60de8e0e0772324f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9add5611cac542241e428a88ecde04c9">applyConcreteDbgVariableAttributes</a> (const std::monostate &amp;, const DbgVariable &amp;DV, DIE &amp;VariableDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See applyConcreteDbgVariableAttribute. <a href="#a9add5611cac542241e428a88ecde04c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### InlinedEntity {#a69fd5b726df2fcc159fd50bc201f77a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DwarfCompileUnit::InlinedEntity =  DbgValueHistoryMap::InlinedEntity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find abstract variable associated with Var.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### MDNodeSetVector {#ae379fa3c76d74051b87ccefe01c77b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DwarfCompileUnit::MDNodeSetVector = 
      SetVector&lt;const MDNode *, SmallVector&lt;const MDNode *, 4&gt;,
                SmallPtrSet&lt;const MDNode *, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DwarfCompileUnit() {#ad52017f371f28817067fc0ea956886e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCompileUnit::DwarfCompileUnit (unsigned UID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> * DW, <a href="/web-llvm/docs/api/classes/llvm/dwarffile">DwarfFile</a> * DWU, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5b7ced2aa529c892b2219cd29b08760">UnitKind</a> Kind=<a href="/web-llvm/docs/api/namespaces/llvm/#ad5b7ced2aa529c892b2219cd29b08760abbd47109890259c0127154db1af26c75">UnitKind::Full</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa741c84d13418c47473a9c3a05eb1e54">llvm::DwarfUnit::DwarfUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#ad1a794474d8b6577eeeac7c922590641">GetCompileUnitType</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a517c4fddcafa9e846541f027a1364fcb">llvm::DwarfUnit::insertDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">constructAbstractSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af45230644d6fe9517cbb489bb2f5b83e">getCU</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9d8fd9011312799cf4f440538b8cb79c">getSkeleton</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa31a57991dc2dd622d2a4f911fbe05d5">setSkeleton</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAddress() {#ab71e26dc84728f514a94593242e6d931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addAddress (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a> &amp; Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an address attribute to a die based on the location provided.</p>

<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">llvm::DwarfUnit::addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ac2e0ff8d944ddd6ebf0ab7f7ab7b9775">llvm::DwarfExpression::addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">llvm::DwarfExpression::addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/diedwarfexpression/#a24b5a14abc09026d9bf5b13f6fe0b2fa">llvm::DIEDwarfExpression::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a509852c6998b529c06357c2bba7aeabb">llvm::DwarfExpression::setMemoryLocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a5f932b026f333235fb286cb5206fc208">llvm::DwarfExpression::TagOffset</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a56065e436441774c9323601217eff992">addVariableAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">constructCallSiteEntryDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">constructCallSiteParmEntryDIEs</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### addAddrTableBase() {#a3abb9664e1a14148cc2ad7f330009b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addAddrTableBase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the DW_AT_addr_base attribute to the unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1712 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">llvm::DwarfUnit::addSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a7dd91b8042158479671aa8f357fd5f62">llvm::MCObjectFileInfo::getDwarfAddrSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>.</p>

</div>
</div>

### addBaseTypeRef() {#a255424b02147849a3f013d1dc7d8b544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addBaseTypeRef (<a href="/web-llvm/docs/api/classes/llvm/dievaluelist">DIEValueList</a> &amp; Die, int64_t Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">llvm::DwarfUnit::addAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>.</p>

</div>
</div>

### addComplexAddress() {#aef8395275fb33cea31395023a1df1d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addComplexAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * DIExpr, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a> &amp; Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Start with the address based on the location provided, and generate the DWARF information necessary to find the actual variable (navigating the extra location information encoded in the type) based on the starting location.</p>


<p>Start with the address based on the location provided, and generate the DWARF information necessary to find the actual variable given the extra address information encoded in the <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a>, starting from the starting location.</p>


<p>Add the DWARF information to the die.</p>


<p>Declaration at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1618 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">llvm::DwarfUnit::addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ac2e0ff8d944ddd6ebf0ab7f7ab7b9775">llvm::DwarfExpression::addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2fdab5e48a4c62a742df876d4e55940f">llvm::DwarfExpression::addFragmentOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">llvm::DwarfExpression::addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af496d6e3f88f3b85e879bfdfe19b0b40">llvm::DwarfExpression::beginEntryValueExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/diedwarfexpression/#a24b5a14abc09026d9bf5b13f6fe0b2fa">llvm::DIEDwarfExpression::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a012168d44e49d5120cf8919cd096fd3b">llvm::DIExpression::isEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a082b9984a203d2a2ba3dd4b5986d4706">llvm::DwarfExpression::setLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a5f932b026f333235fb286cb5206fc208">llvm::DwarfExpression::TagOffset</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a56065e436441774c9323601217eff992">addVariableAddress</a>.</p>

</div>
</div>

### addExpr() {#ab1a8483dca80b0435c63148629476aaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addExpr (<a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a Dwarf expression attribute data and value.</p>

<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1682 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">llvm::DwarfUnit::addAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">addLocationAttribute</a>.</p>

</div>
</div>

### addGlobalName() {#a742e325bd655dc33c538065902d73a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addGlobalName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
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

<p>Add a new global name to the compile unit.</p>


<p>addGlobalName - Add a new global name to the compile unit.</p>


<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1542 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aace6bf1aa397a8c6f9b832c8a39b8b6c">llvm::DwarfUnit::getParentContextString</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ade4388f12ad1757626e62ed0e1da6cf8">hasDwarfPubSections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9e16a00186a0cb4e8265515d9bbebb93">applySubprogramAttributesToDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">getOrCreateCommonBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">getOrCreateGlobalVariableDIE</a>.</p>

</div>
</div>

### addGlobalNameForTypeUnit() {#a3365d623c06b679b5852addcbe4214c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addGlobalNameForTypeUnit (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new global name present in a type unit to this compile unit.</p>

<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1550 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aace6bf1aa397a8c6f9b832c8a39b8b6c">llvm::DwarfUnit::getParentContextString</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ade4388f12ad1757626e62ed0e1da6cf8">hasDwarfPubSections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#adb789fb653900fb7fcec59e8efb5caa3">llvm::DwarfTypeUnit::addGlobalName</a>.</p>

</div>
</div>

### addGlobalTypeImpl() {#ac514ce80941fff1bd81f371317a2f8b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addGlobalTypeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
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

<p>Add a new global type to the compile unit.</p>


<p>Add a new global type to the unit.</p>


<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1563 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aace6bf1aa397a8c6f9b832c8a39b8b6c">llvm::DwarfUnit::getParentContextString</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ade4388f12ad1757626e62ed0e1da6cf8">hasDwarfPubSections</a>.</p>

</div>
</div>

### addGlobalTypeUnitType() {#ad94baae1a66e6173dc2f9ee860fc7d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addGlobalTypeUnitType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new global type present in a type unit to this compile unit.</p>

<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1571 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aace6bf1aa397a8c6f9b832c8a39b8b6c">llvm::DwarfUnit::getParentContextString</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ade4388f12ad1757626e62ed0e1da6cf8">hasDwarfPubSections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a43330b5158516ba431669d48c2f91835">llvm::DwarfTypeUnit::addGlobalTypeImpl</a>.</p>

</div>
</div>

### addLabelAddress() {#ae7f8bac4a8c515d95110494a2ed662e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addLabelAddress (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addLabelAddress - Add a dwarf label attribute data and value using either DW_FORM_addr or DW_FORM_GNU_addr_index.</p>


<p>addLabelAddress - Add a dwarf label attribute data and value using DW_FORM_addr or DW_FORM_GNU_addr_index.</p>


<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">llvm::DwarfUnit::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">llvm::DwarfUnit::addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ac2ec97478e68f7a1d1570b6b058853b4">addLocalLabelAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad6ef869ce359f62362cd8ab0b372f6df">llvm::DwarfUnit::addPoolOpAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0b3f89703fa8ecd73c1b43a7ac656402">attachLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">constructCallSiteEntryDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3554b83e3e334e00da341d9aba81a47e">finishEntityDefinition</a>.</p>

</div>
</div>

### addLocalLabelAddress() {#ac2ec97478e68f7a1d1570b6b058853b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addLocalLabelAddress (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addLocalLabelAddress - Add a dwarf label attribute data and value using DW_FORM_addr only.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">llvm::DwarfUnit::addAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae7f8bac4a8c515d95110494a2ed662e5">addLabelAddress</a>.</p>

</div>
</div>

### addLocationAttribute() {#a9c6d364a5079f4f7a166cbaa1ba24ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addLocationAttribute (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * ToDIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> * GV, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfcompileunit/globalexpr">GlobalExpr</a> &gt; GlobalExprs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">llvm::DwarfUnit::addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a47ccb514c025257d1c6d106dae4c0689">llvm::DwarfUnit::addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab1a8483dca80b0435c63148629476aaf">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa849a65237107c0118e25e93a42ab2bd">llvm::DwarfUnit::addLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a7c0e3436e571693ed818b4985cf133">llvm::DwarfUnit::addOpAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa6bd295826d6eda8304af6da84feac34">llvm::DwarfUnit::addSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">llvm::DwarfUnit::CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#af0a91f5f2e148fabfcc21454c7768b40">llvm::DIExpression::extractAddressClass</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#aaa07b8d87479ec84346886b96ef5912a">llvm::DIExpression::getElement</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable/#ab0edecc1c9327e9d85e320b8480ec60c">llvm::DIGlobalVariable::getLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#af44724cae4bcd562972facee1cf035a5">llvm::DIVariable::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bfa4cc6684df7b4a92b1dec6fce3264fac8">llvm::Global</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#acabd4da8227159965c0baf81f9643d39">llvm::DIExpression::isConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">llvm::Reloc::PIC_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a593b80c5ddf9a5f0c06860e6711955d5">llvm::Reloc::ROPI_RWPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a33108d181242a6b5c92f1bdb81d38128">llvm::Reloc::RWPI</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a5307ea3a541fa8d6d713f305541c0782a96e79d1e0a81cdd5e68865fbe9132f2e">llvm::DIExpression::UnsignedConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">getOrCreateCommonBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">getOrCreateGlobalVariableDIE</a>.</p>

</div>
</div>

### addLocationList() {#ae8e1f64509dc4e7c6a0ee7ea1592cdf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addLocationList (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a Dwarf loclistptr attribute data and value.</p>

<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1645 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">llvm::DwarfUnit::addAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>.</p>

</div>
</div>

### addRange() {#a39cb0b18cc6f463c1d383db1ee6c6226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addRange (<a href="/web-llvm/docs/api/structs/llvm/rangespan">RangeSpan</a> Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addRange - Add an address range to the list of ranges for this unit.</p>

<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>.</p>

</div>
</div>

### addScopeRangeList() {#a4e4e697039d4692563c2ccc3608864d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addScopeRangeList (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; ScopeDIE, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rangespan">RangeSpan</a>, 2 &gt; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function to construct a <a href="/web-llvm/docs/api/structs/llvm/rangespanlist">RangeSpanList</a> for a given lexical scope.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5f6e3a70db3c30dc6999e3cd70ed8818">llvm::DwarfUnit::addSectionDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">llvm::DwarfUnit::addSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">llvm::DwarfUnit::DU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a31df4edd580fc4f6e43318cd9c5ed5bc">llvm::MCObjectFileInfo::getDwarfRangesSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af8875ff9c8633acdeb1e970471f37f57">attachRangesOrLowHighPC</a>.</p>

</div>
</div>

### addVariableAddress() {#a56065e436441774c9323601217eff992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addVariableAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> &amp; DV, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a> Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add DW_AT_location attribute for a <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> based on provided <a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a>.</p>

<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1583 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">addAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">addComplexAddress</a>.</p>

</div>
</div>

### applyCommonDbgVariableAttributes() {#a7f1c08f4c14daab9f9b9bd3502b0b384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::applyCommonDbgVariableAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> &amp; Var, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; VariableDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add attributes to <span class="doxyComputerOutput">Var</span> which reflect the common attributes of <span class="doxyComputerOutput">VariableDie</span>, namely those which are not dependant on the active variant.</p>

<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c898e1e28aff43017285cae176864ae">llvm::DwarfUnit::addAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">llvm::DwarfUnit::addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">llvm::DwarfUnit::addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">llvm::DwarfUnit::addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">llvm::DwarfUnit::addType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#a8efc6ce71f8d82ec684a6de55040c088">llvm::DbgVariable::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#aa6d11876bae08f2f51fe5a8d76eaff58">llvm::DbgVariable::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#a3f999918279bb2c923b2d35bec6fb01d">llvm::DbgVariable::getVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#a1605e91e3bead92601f3b9b7e4c47a95">llvm::DbgVariable::isArtificial</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a90e6b90f1ecca9999a225bac737d2fdc">constructVariableDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3554b83e3e334e00da341d9aba81a47e">finishEntityDefinition</a>.</p>

</div>
</div>

### applyLabelAttributes() {#ab848ab31ed9686e47adbc3cd56c7a1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::applyLabelAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbglabel">DbgLabel</a> &amp; Label, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; LabelDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1672 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">llvm::DwarfUnit::addSourceLine</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">llvm::DwarfUnit::addString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad6d394e7617fdbb955ce7db1fc9aaff7">constructLabelDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3554b83e3e334e00da341d9aba81a47e">finishEntityDefinition</a>.</p>

</div>
</div>

### applyStmtList() {#a780e3087cd40ac6f03e93e1722993cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::applyStmtList (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply the DW_AT_stmt_list from this compile unit to the specified <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">llvm::DwarfUnit::addSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a82d3abaa97d9734f17bdd52cfdf00fb7">llvm::MCObjectFileInfo::getDwarfLineSection</a>.</p>

</div>
</div>

### applySubprogramAttributesToDefinition() {#a9e16a00186a0cb4e8265515d9bbebb93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::applySubprogramAttributesToDefinition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; SPDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1687 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a742e325bd655dc33c538065902d73a9e">addGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">llvm::DwarfUnit::applySubprogramAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">includeMinimalInlineScopes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">constructAbstractSubprogramScopeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#afd5821362beb37693123202b5e35d15a">finishSubprogramDefinition</a>.</p>

</div>
</div>

### attachLowHighPC() {#a0b3f89703fa8ecd73c1b43a7ac656402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::attachLowHighPC (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; D, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Begin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae7f8bac4a8c515d95110494a2ed662e5">addLabelAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa748b4decf2622ab7e6a7ae30da0a2e0">llvm::DwarfUnit::addLabelDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2899e74730516967f04d81966bb4f881">llvm::MCSymbol::isDefined</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af8875ff9c8633acdeb1e970471f37f57">attachRangesOrLowHighPC</a>.</p>

</div>
</div>

### attachRangesOrLowHighPC() {#af8875ff9c8633acdeb1e970471f37f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::attachRangesOrLowHighPC (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; D, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rangespan">RangeSpan</a>, 2 &gt; Ranges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4e4e697039d4692563c2ccc3608864d1">addScopeRangeList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0b3f89703fa8ecd73c1b43a7ac656402">attachLowHighPC</a>, <a href="/web-llvm/docs/api/structs/llvm/rangespan/#aea0079a342c4f430d6132539aba040cc">llvm::RangeSpan::Begin</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a> and <a href="/web-llvm/docs/api/structs/llvm/rangespan/#a45b64bcb34960fd7158d9e89a9719166">llvm::RangeSpan::End</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a37d00bd782a8ae88d11495124673cd53">attachRangesOrLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">constructInlinedScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ac43078e4f82c8dea48b4a483de6f434a">constructLexicalScopeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### attachRangesOrLowHighPC() {#a37d00bd782a8ae88d11495124673cd53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::attachRangesOrLowHighPC (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; D, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a50e4c9f81d1b75e9f5706df4cdb3c489">InsnRange</a> &gt; &amp; Ranges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af8875ff9c8633acdeb1e970471f37f57">attachRangesOrLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae4fd64dbad816e7b3857e688386b3448">llvm::DwarfUnit::EndLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### constructAbstractSubprogramScopeDIE() {#a150001a8f1d0061691188b80802e0365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::constructAbstractSubprogramScopeDIE (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">llvm::DwarfUnit::addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa6bd295826d6eda8304af6da84feac34">llvm::DwarfUnit::addSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9e16a00186a0cb4e8265515d9bbebb93">applySubprogramAttributesToDefinition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">llvm::DwarfUnit::createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a05feed307dcff1df2e39f250502ab4b3a89db9e54bf0b0c16e3e98cf8607ff640">llvm::dwarf::DW_INL_inlined</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad52017f371f28817067fc0ea956886e7">DwarfCompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7b6f34c53b2dbad48a28b675922003e1">getOrCreateContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">llvm::DwarfUnit::getOrCreateSubprogramDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#ab0a7f64f121eaf4d95424a3fbfcc921c">llvm::DIE::getUnitDie</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">includeMinimalInlineScopes</a>.</p>

</div>
</div>

### constructCallSiteEntryDIE() {#a3f002d26ef8a98b14c82c510d49e26b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; DwarfCompileUnit::constructCallSiteEntryDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; ScopeDIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * CalleeSP, bool IsTail, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * PCAddr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * CallAddr, unsigned CallReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a call site entry <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> describing a call within <span class="doxyComputerOutput">Scope</span> to a callee described by <span class="doxyComputerOutput">CalleeSP</span>.</p>


<p><span class="doxyComputerOutput">IsTail</span> specifies whether the call is a tail call. <span class="doxyComputerOutput">PCAddr</span> points to the PC value after the call instruction. <span class="doxyComputerOutput">CallAddr</span> points to the PC value at the call instruction (or is null). <span class="doxyComputerOutput">CallReg</span> is a register location for an indirect call. For direct calls the <span class="doxyComputerOutput">CallReg</span> is set to 0.</p>


<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1282 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">llvm::DwarfUnit::addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">llvm::DwarfUnit::addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae7f8bac4a8c515d95110494a2ed662e5">addLabelAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa849a65237107c0118e25e93a42ab2bd">llvm::DwarfUnit::addLinkageName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#ac8dcff3941279d4c56ad6f044c1dd54b">AddLinkageNamesToDeclCallOriginsForTuning</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">llvm::DwarfUnit::createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a008bf8f3472eb0014e766bac06fbe537">llvm::DIE::findAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab5146bedc026123984b5193c0a6e94af">getDwarf5OrGNUAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0ff931a71f37552aeef5c2ef16e950c3">getDwarf5OrGNUTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">llvm::DwarfUnit::getOrCreateSubprogramDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a021658afc8b95fca777f7f6ebc36aa8c">useGNUAnalogForDwarf5Feature</a>.</p>

</div>
</div>

### constructCallSiteParmEntryDIEs() {#a0284131decd7881e49a1dc2b82e4ac58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::constructCallSiteParmEntryDIEs (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; CallSiteDIE, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgcallsiteparam">DbgCallSiteParam</a>, 4 &gt; &amp; Params)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct call site parameter DIEs for the <span class="doxyComputerOutput">CallSiteDIE</span>.</p>


<p>The <span class="doxyComputerOutput">Params</span> were collected by the <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>. Note: The order of parameters does not matter, since debuggers recognize call site parameters by the DW_AT_location attribute.</p>


<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">llvm::DwarfUnit::addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a3bd79b4ce04e1141856b6076717b4615">llvm::DIE::addChild</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>, <a href="/web-llvm/docs/api/classes/llvm/diedwarfexpression/#a24b5a14abc09026d9bf5b13f6fe0b2fa">llvm::DIEDwarfExpression::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab5146bedc026123984b5193c0a6e94af">getDwarf5OrGNUAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0ff931a71f37552aeef5c2ef16e950c3">getDwarf5OrGNUTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a517c4fddcafa9e846541f027a1364fcb">llvm::DwarfUnit::insertDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7188211a4157e4f38345d90d6030c562">llvm::DwarfExpression::setCallSiteParamValueFlag</a>.</p>

</div>
</div>

### constructImportedEntityDIE() {#af154345e2837458e53079bc2eaf50ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::constructImportedEntityDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> * IE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a3bd79b4ce04e1141856b6076717b4615">llvm::DIE::addChild</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">llvm::DwarfUnit::addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">llvm::DwarfUnit::addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">llvm::DwarfUnit::addString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">llvm::DwarfUnit::CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">llvm::DwarfUnit::getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a4b3648156c20e8cf63c5eb07c56ab2fe">llvm::Module::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">getOrCreateGlobalVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a1b6f98e91ce662c3a7a89705a00ef67f">getOrCreateImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">llvm::DwarfUnit::getOrCreateModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">llvm::DwarfUnit::getOrCreateNameSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">llvm::DwarfUnit::getOrCreateSubprogramDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">llvm::DwarfUnit::getOrCreateTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a517c4fddcafa9e846541f027a1364fcb">llvm::DwarfUnit::insertDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">constructImportedEntityDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a1b6f98e91ce662c3a7a89705a00ef67f">getOrCreateImportedEntityDIE</a>.</p>

</div>
</div>

### constructInlinedScopeDIE() {#a47e64bee9baa8d3436add9ec49d1c880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::constructInlinedScopeDIE (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; ParentScopeDIE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This scope represents an inlined body of a function.</p>


<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to represent this concrete inlined copy of the function.</p>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a3bd79b4ce04e1141856b6076717b4615">llvm::DIE::addChild</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">llvm::DwarfUnit::addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af8875ff9c8633acdeb1e970471f37f57">attachRangesOrLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">llvm::DwarfUnit::CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af648a1ecd9b0189801c2c8f8f15ffba3">llvm::getDISubprogram</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acd839ab10698d2e52b0021818e8d9625">getOrCreateSourceID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acf65d0311d21263e1470c9c5f2ad57d8">constructScopeDIE</a>.</p>

</div>
</div>

### constructLabelDIE() {#ad6d394e7617fdbb955ce7db1fc9aaff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::constructLabelDIE (<a href="/web-llvm/docs/api/classes/llvm/dbglabel">DbgLabel</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> &amp; Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given <a href="/web-llvm/docs/api/classes/llvm/dbglabel">DbgLabel</a>.</p>

<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 996 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab848ab31ed9686e47adbc3cd56c7a1f1">applyLabelAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a517c4fddcafa9e846541f027a1364fcb">llvm::DwarfUnit::insertDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a>.</p>

</div>
</div>

### constructLexicalScopeDIE() {#ac43078e4f82c8dea48b4a483de6f434a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::constructLexicalScopeDIE (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct new DW_TAG_lexical_block for this scope and attach DW_AT_low_pc/DW_AT_high_pc labels.</p>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af8875ff9c8633acdeb1e970471f37f57">attachRangesOrLowHighPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a> and <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acf65d0311d21263e1470c9c5f2ad57d8">constructScopeDIE</a>.</p>

</div>
</div>

### constructScopeDIE() {#acf65d0311d21263e1470c9c5f2ad57d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::constructScopeDIE (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; ParentScopeDIE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a3bd79b4ce04e1141856b6076717b4615">llvm::DIE::addChild</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">constructInlinedScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ac43078e4f82c8dea48b4a483de6f434a">constructLexicalScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a>.</p>

</div>
</div>

### constructSubprogramScopeDIE() {#a8cbe3dd2e5c24c363d750bd49f46838a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; DwarfCompileUnit::constructSubprogramScopeDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * Sub, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LineTableSym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for this subprogram scope.</p>

<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a3bd79b4ce04e1141856b6076717b4615">llvm::DIE::addChild</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">llvm::DwarfUnit::addDIEEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">includeMinimalInlineScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/dityperefarray/#ac4bfdb24ae42d443c9c1bd807edb5171">llvm::DITypeRefArray::size</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">updateSubprogramScopeDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>.</p>

</div>
</div>

### constructVariableDIE() {#a90e6b90f1ecca9999a225bac737d2fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::constructVariableDIE (<a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> &amp; DV, bool Abstract=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a>.</p>

<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#aab98ba710c2a5b5f61bc8dda747a5e38">llvm::DbgVariable::asVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#a1d9e9002e64cc718d5bdc179afe2b2a3">llvm::DbgVariable::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#a3f999918279bb2c923b2d35bec6fb01d">llvm::DbgVariable::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a517c4fddcafa9e846541f027a1364fcb">llvm::DwarfUnit::insertDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#aa41902585ef16d11fbd07dba6ba19687">llvm::DbgEntity::setDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4a09bbbcfe5fb24876e63ca5b05f45a8">constructVariableDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a>.</p>

</div>
</div>

### constructVariableDIE() {#a4a09bbbcfe5fb24876e63ca5b05f45a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::constructVariableDIE (<a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> &amp; DV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> &amp; Scope, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *&amp; ObjectPointer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience overload which writes the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer into an out variable ObjectPointer in addition to returning it.</p>

<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a90e6b90f1ecca9999a225bac737d2fdc">constructVariableDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#a37e1ead5d36eb33ba9093788422d4d6e">llvm::DbgVariable::isObjectPointer</a>.</p>

</div>
</div>

### createAbstractEntity() {#a77347a4881397840dcd27b24ce537976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::createAbstractEntity (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1492 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">llvm::DwarfUnit::DU</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>.</p>

</div>
</div>

### createAndAddScopeChildren() {#aa0d14e865eff41f3f1c6f53e1604e67e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::createAndAddScopeChildren (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; ScopeDIE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a3bd79b4ce04e1141856b6076717b4615">llvm::DIE::addChild</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad6d394e7617fdbb955ce7db1fc9aaff7">constructLabelDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acf65d0311d21263e1470c9c5f2ad57d8">constructScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a90e6b90f1ecca9999a225bac737d2fdc">constructVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">llvm::DwarfUnit::DU</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">includeMinimalInlineScopes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#a08fb230c2b93e704a4fd84ef773b6002">sortLocalVars</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">constructAbstractSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acf65d0311d21263e1470c9c5f2ad57d8">constructScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a8cbe3dd2e5c24c363d750bd49f46838a">constructSubprogramScopeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a>.</p>

</div>
</div>

### createBaseTypeDIEs() {#a4c89d112b2f04f66826428c19d11301b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::createBaseTypeDIEs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1726 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a5d4a5eccaf92037114cb5911b0bb457f">llvm::DIE::addChildFront</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">llvm::DwarfUnit::addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga8a7e29291b6e812a89dcdbb07948c0ac">llvm::dwarf::AttributeEncodingString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a415b620309aed1e1be14fbb29ae5adaa">ExprRefedBaseTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ac521760e9a45f304a4cbe46ed4fff845">llvm::Twine::toStringRef</a>.</p>

</div>
</div>

### emitFuncLineTableOffsets() {#aeaee698ea69682436f2ad91d3212fe55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfCompileUnit::emitFuncLineTableOffsets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1708 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#a8a4514b9c60e1daef32d1288585f88a3">EmitFuncLineTableOffsetsOption</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### emitHeader() {#a0c18db764d4e597a32d9ae44e2953cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::emitHeader (bool UseOffsets)</td>
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

<p>Emit the header for this unit, not including the initial length field.</p>

<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1507 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0c77b8d4ff2ea875d1c29128d4ef848">llvm::DwarfUnit::emitCommonHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a5304aa2b4acf341571b67df6ba125efa">getDWOId</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa5e5e39be4bacc4da9b8f17a49dd9521">llvm::DwarfUnit::LabelBegin</a>.</p>

</div>
</div>

### finishEntityDefinition() {#a3554b83e3e334e00da341d9aba81a47e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::finishEntityDefinition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a> * Entity)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ac81660b2aac6a21b5b3c18eb6ace603e">llvm::DwarfDebug::addAccelName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">llvm::DwarfUnit::addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae7f8bac4a8c515d95110494a2ed662e5">addLabelAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab848ab31ed9686e47adbc3cd56c7a1f1">applyLabelAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">llvm::DwarfUnit::CUNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#ad6807c08abe678734ff0dbbbe94d9332">llvm::DbgEntity::getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a13e424e67bc81915803e8ab194775446">llvm::DwarfUnit::getDwarfDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#a87303a6c9dda72c2b68184698f3321d8">llvm::DbgEntity::getEntity</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad9c9bcc6b272753369d8b7d322c879c8">getExistingAbstractEntity</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### finishSubprogramDefinition() {#afd5821362beb37693123202b5e35d15a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::finishSubprogramDefinition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">llvm::DwarfUnit::addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9e16a00186a0cb4e8265515d9bbebb93">applySubprogramAttributesToDefinition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">llvm::DwarfUnit::getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">includeMinimalInlineScopes</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>

</div>
</div>

### getBaseAddress() {#ad3b0fd581ce4e48abe3900bad5eb8a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol * llvm::DwarfCompileUnit::getBaseAddress ()</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### getCU() {#af45230644d6fe9517cbb489bb2f5b83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCompileUnit &amp; llvm::DwarfCompileUnit::getCU ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad52017f371f28817067fc0ea956886e7">DwarfCompileUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">getOrCreateCommonBlock</a>.</p>

</div>
</div>

### getDeferredLocalDecls() {#a6a6faa304af988d1f525a9e5139412ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNodeSetVector &amp; llvm::DwarfCompileUnit::getDeferredLocalDecls ()</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### getDwarf5OrGNUAttr() {#ab5146bedc026123984b5193c0a6e94af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Attribute DwarfCompileUnit::getDwarf5OrGNUAttr (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This takes a DWARF 5 attribute and returns it or a GNU analog.</p>

<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a021658afc8b95fca777f7f6ebc36aa8c">useGNUAnalogForDwarf5Feature</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">constructCallSiteEntryDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">constructCallSiteParmEntryDIEs</a>.</p>

</div>
</div>

### getDwarf5OrGNULocationAtom() {#a9374110f110bab23d52438a26f629216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::LocationAtom DwarfCompileUnit::getDwarf5OrGNULocationAtom (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0c">dwarf::LocationAtom</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This takes a DWARF 5 location atom and either returns it or a GNU analog.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a021658afc8b95fca777f7f6ebc36aa8c">useGNUAnalogForDwarf5Feature</a>.</p>

</div>
</div>

### getDwarf5OrGNUTag() {#a0ff931a71f37552aeef5c2ef16e950c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag DwarfCompileUnit::getDwarf5OrGNUTag (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This takes a DWARF 5 tag and returns it or a GNU analog.</p>

<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a021658afc8b95fca777f7f6ebc36aa8c">useGNUAnalogForDwarf5Feature</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">constructCallSiteEntryDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">constructCallSiteParmEntryDIEs</a>.</p>

</div>
</div>

### getDWOId() {#a5304aa2b4acf341571b67df6ba125efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DwarfCompileUnit::getDWOId ()</td>
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



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0c18db764d4e597a32d9ae44e2953cd3">emitHeader</a>.</p>

</div>
</div>

### getExistingAbstractEntity() {#ad9c9bcc6b272753369d8b7d322c879c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgEntity * DwarfCompileUnit::getExistingAbstractEntity (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1484 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3554b83e3e334e00da341d9aba81a47e">finishEntityDefinition</a>.</p>

</div>
</div>

### getGlobalNames() {#ad65e0a2dfe95734e2049e6602fc65f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringMap&lt; const DIE * &gt; &amp; llvm::DwarfCompileUnit::getGlobalNames ()</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### getGlobalTypes() {#adde26643b9a29b6fbca26a7d2aa1693b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringMap&lt; const DIE * &gt; &amp; llvm::DwarfCompileUnit::getGlobalTypes ()</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### getHeaderSize() {#a0e5a7772e91857ecf8d244dd25a1baf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfCompileUnit::getHeaderSize ()</td>
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

<p>Compute the size of a header for this unit, not including the initial length field.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8f45a669235b32b6a7e2d7e8a7b95f53">llvm::DwarfUnit::getHeaderSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a68d4481aea40e318a364df01ae10d308">getLength</a>.</p>

</div>
</div>

### getLength() {#a68d4481aea40e318a364df01ae10d308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfCompileUnit::getLength ()</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0e5a7772e91857ecf8d244dd25a1baf1">getHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a260b23f8c0c3b34a94b27886008630f9">llvm::DIE::getSize</a> and <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>.</p>

</div>
</div>

### getLexicalBlockDIE() {#a731f3ca3bc29b3acc59ef49fdb067f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::getLexicalBlockDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a> * LB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a>.</p>


<p>Note that this function assumes that the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> has been already created and it's an error, if it hasn't.</p>


<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1747 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a> and <a href="/web-llvm/docs/api/classes/llvm/dilocalscope/#a0e0b4a5906e0bc2a7fa033548c59a220">llvm::DILocalScope::getSubprogram</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7b6f34c53b2dbad48a28b675922003e1">getOrCreateContextDIE</a>.</p>

</div>
</div>

### getLineTableStartSym() {#ac84a303b99d4ac7659f9db66b3da8ef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::DwarfCompileUnit::getLineTableStartSym ()</td>
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

<p>Get line table start symbol for this unit.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### getMacroLabelBegin() {#a408063a00dcf4cf82daa52612bdb726a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::DwarfCompileUnit::getMacroLabelBegin ()</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### getOrCreateCommonBlock() {#a53bba044b64b7a894e30aeb52a247515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::getOrCreateCommonBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicommonblock">DICommonBlock</a> * CB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfcompileunit/globalexpr">GlobalExpr</a> &gt; GlobalExprs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a742e325bd655dc33c538065902d73a9e">addGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">llvm::DwarfUnit::addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">llvm::DwarfUnit::addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">llvm::DwarfUnit::createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af45230644d6fe9517cbb489bb2f5b83e">getCU</a>, <a href="/web-llvm/docs/api/classes/llvm/dicommonblock/#ae496b187ac489ae1f6e3709e87fac08a">llvm::DICommonBlock::getDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">llvm::DwarfUnit::getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dicommonblock/#a8c4910290b8539dd96599445e163fe9a">llvm::DICommonBlock::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dicommonblock/#a96d85338ed343e59f7cd31ffe951eea7">llvm::DICommonBlock::getLineNo</a>, <a href="/web-llvm/docs/api/classes/llvm/dicommonblock/#ac893cd7cbd53683633dd1ebc4cebedf7">llvm::DICommonBlock::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7b6f34c53b2dbad48a28b675922003e1">getOrCreateContextDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dicommonblock/#ac9286635c363b2db64a23fdd2ae08b1b">llvm::DICommonBlock::getScope</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">getOrCreateGlobalVariableDIE</a>.</p>

</div>
</div>

### getOrCreateContextDIE() {#a7b6f34c53b2dbad48a28b675922003e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::getOrCreateContextDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Ty)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for a given scope.</p>


<p>This instance of '<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7b6f34c53b2dbad48a28b675922003e1">getOrCreateContextDIE()</a>' can handle <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a>.</p>


<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a731f3ca3bc29b3acc59ef49fdb067f41">getLexicalBlockDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">llvm::DwarfUnit::getOrCreateContextDIE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">constructAbstractSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">getOrCreateCommonBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">getOrCreateGlobalVariableDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a1b6f98e91ce662c3a7a89705a00ef67f">getOrCreateImportedEntityDIE</a>.</p>

</div>
</div>

### getOrCreateGlobalVariableDIE() {#a9bd19f659a2944b4440bafe9f78a0809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::getOrCreateGlobalVariableDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> * GV, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfcompileunit/globalexpr">GlobalExpr</a> &gt; GlobalExprs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get or create global variable <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c898e1e28aff43017285cae176864ae">llvm::DwarfUnit::addAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">llvm::DwarfUnit::addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">llvm::DwarfUnit::addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a742e325bd655dc33c538065902d73a9e">addGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">llvm::DwarfUnit::addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">llvm::DwarfUnit::addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a242b3dd9a06d131c011d8e8d9b3bddf5">llvm::DwarfUnit::addTemplateParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">llvm::DwarfUnit::addType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">llvm::DwarfUnit::createAndAddDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a4a83181ff1d7e4f04ea87a382f974347">llvm::DIVariable::getAlignInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable/#ad269a679792daaa002c03b8c369494c0">llvm::DIGlobalVariable::getAnnotations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">llvm::DwarfUnit::getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable/#ab4f18803e54912efe8f36fcf1d955d8a">llvm::DIGlobalVariable::getDisplayName</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#af44724cae4bcd562972facee1cf035a5">llvm::DIVariable::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">getOrCreateCommonBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7b6f34c53b2dbad48a28b675922003e1">getOrCreateContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">llvm::DwarfUnit::getOrCreateStaticMemberDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a4b86385218322e8e5c2656dbad0de126">llvm::DIVariable::getScope</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable/#a2faad6b93bae3a6a8a6786dfdfbfc404">llvm::DIGlobalVariable::getStaticDataMemberDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a13471a1f55ae60d82d774585bfd3c5da">llvm::DINode::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable/#a80e31a027fe056fd59a0b538c4a8260f">llvm::DIGlobalVariable::getTemplateParams</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#adab9179b79371579b407e31155a32366">llvm::DIVariable::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable/#ac322ae3bc017654b618b9f636a1526e7">llvm::DIGlobalVariable::isDefinition</a> and <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable/#a88314689d28eb0c890fae3a1eda8fa90">llvm::DIGlobalVariable::isLocalToUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">constructImportedEntityDIE</a>.</p>

</div>
</div>

### getOrCreateImportedEntityDIE() {#a1b6f98e91ce662c3a7a89705a00ef67f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfCompileUnit::getOrCreateImportedEntityDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> * IE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for an imported entity.</p>

<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a3bd79b4ce04e1141856b6076717b4615">llvm::DIE::addChild</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">llvm::DwarfUnit::getDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7b6f34c53b2dbad48a28b675922003e1">getOrCreateContextDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">constructImportedEntityDIE</a>.</p>

</div>
</div>

### getOrCreateSourceID() {#acd839ab10698d2e52b0021818e8d9625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DwarfCompileUnit::getOrCreateSourceID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File)</td>
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

<p>Look up the source <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the given file.</p>


<p>If none currently exists, create a new <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and insert it in the line table.</p>


<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af72fc15677cff47ef8f3f982ebf2098c">llvm::DwarfUnit::getUniqueID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">constructInlinedScopeDIE</a>.</p>

</div>
</div>

### getRanges() {#acca21dd57a82d69c505bacff94e79f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; RangeSpan &gt; &amp; llvm::DwarfCompileUnit::getRanges ()</td>
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

<p>getRanges - Get the list of ranges for this unit.</p>

<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### getSkeleton() {#a9d8fd9011312799cf4f440538b8cb79c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCompileUnit * llvm::DwarfCompileUnit::getSkeleton ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad52017f371f28817067fc0ea956886e7">DwarfCompileUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>.</p>

</div>
</div>

### hasDwarfPubSections() {#ade4388f12ad1757626e62ed0e1da6cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfCompileUnit::hasDwarfPubSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1522 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fa9f6290f4436e5a2351f12e03b6433c3c">llvm::Apple</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01a9f6290f4436e5a2351f12e03b6433c3c">llvm::DICompileUnit::Apple</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">llvm::DwarfUnit::CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01a7a1920d61156abc05a60135aefe8bc67">llvm::DICompileUnit::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01ab7e89d55aa08a289aa48277386e6ff1d">llvm::DICompileUnit::GNU</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">includeMinimalInlineScopes</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01a6adf97f83acf6453d4a6a4b1070f3754">llvm::DICompileUnit::None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a742e325bd655dc33c538065902d73a9e">addGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3365d623c06b679b5852addcbe4214c6">addGlobalNameForTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ac514ce80941fff1bd81f371317a2f8b8">addGlobalTypeImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad94baae1a66e6173dc2f9ee860fc7d8d">addGlobalTypeUnitType</a>.</p>

</div>
</div>

### hasRangeLists() {#af8db94fb6e067c46abe4207d31b8cb34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfCompileUnit::hasRangeLists ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### includeMinimalInlineScopes() {#a19052e5d06c02fdb8e572529d0acb8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfCompileUnit::includeMinimalInlineScopes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1703 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abebd15dd4b82e33ca73757397490ea80">llvm::DwarfUnit::getCUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#afeaa84c982a7493e02d1b547297e0e69">llvm::DICompileUnit::getEmissionKind</a> and <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66da6b16b60468715f43621c437edef9a3b3">llvm::DICompileUnit::LineTablesOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9e16a00186a0cb4e8265515d9bbebb93">applySubprogramAttributesToDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">constructAbstractSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a8cbe3dd2e5c24c363d750bd49f46838a">constructSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">createAndAddScopeChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#afd5821362beb37693123202b5e35d15a">finishSubprogramDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ade4388f12ad1757626e62ed0e1da6cf8">hasDwarfPubSections</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### initStmtList() {#a5bf6adcaa4ad6740a1a7544e827a5231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::initStmtList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">llvm::DwarfUnit::addSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">llvm::DwarfUnit::CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a82d3abaa97d9734f17bdd52cfdf00fb7">llvm::MCObjectFileInfo::getDwarfLineSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af72fc15677cff47ef8f3f982ebf2098c">llvm::DwarfUnit::getUniqueID</a> and <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>.</p>

</div>
</div>

### setBaseAddress() {#afb3b1932132a240e60eb9a336f16685f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfCompileUnit::setBaseAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Base)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>.</p>

</div>
</div>

### setDWOId() {#abc18cc6156ebe4a69d0e9e6f5073081d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfCompileUnit::setDWOId (uint64_t DwoId)</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### setSkeleton() {#aa31a57991dc2dd622d2a4f911fbe05d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfCompileUnit::setSkeleton (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; Skel)</td>
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

<p>Set the skeleton unit associated with this unit.</p>

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad52017f371f28817067fc0ea956886e7">DwarfCompileUnit</a>.</p>

</div>
</div>

### takeRanges() {#a1dac2039805bd7eef2e24c4f8bab19be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; RangeSpan, 2 &gt; llvm::DwarfCompileUnit::takeRanges ()</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### updateSubprogramScopeDIE() {#a11a3a1f0710cf8260033c8eb18800175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; DwarfCompileUnit::updateSubprogramScopeDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LineTableSym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given subprogram and attach appropriate DW_AT_low_pc, DW_AT_high_pc and DW_AT_LLVM_stmt_sequence attributes.</p>


<p>If there are global variables in this scope then create and insert DIEs for these variables.</p>


<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">llvm::DwarfUnit::addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ac2e0ff8d944ddd6ebf0ab7f7ab7b9775">llvm::DwarfExpression::addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">llvm::DwarfUnit::addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">llvm::DwarfUnit::addSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa6bd295826d6eda8304af6da84feac34">llvm::DwarfUnit::addSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af2a335e267a7975d64235e578d89a2c9">llvm::DwarfExpression::addWasmLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">llvm::DwarfUnit::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af8875ff9c8633acdeb1e970471f37f57">attachRangesOrLowHighPC</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#a69b8f7941a5f3d374f3a4ef2fd86516ba17f65ba058c6314a928497bd58cb6623">llvm::TargetFrameLowering::DwarfFrameBase::CFA</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">llvm::DwarfUnit::CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">llvm::DwarfUnit::DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aeaee698ea69682436f2ad91d3212fe55">emitFuncLineTableOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/diedwarfexpression/#a24b5a14abc09026d9bf5b13f6fe0b2fa">llvm::DIEDwarfExpression::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a67cf1d94afd29ba3f7fa7a05241c43ae">llvm::TargetFrameLowering::getDwarfFrameBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">llvm::DwarfUnit::getOrCreateSubprogramDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">includeMinimalInlineScopes</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/wasmframebase/#a08f8ef82040567d298c6fa67068b4750">llvm::TargetFrameLowering::DwarfFrameBase::WasmFrameBase::Index</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#afacc26f29d80e10be4785a96ed6444dc">llvm::Register::isPhysicalRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#ab9d82d53acc347a5ab75ea59da93c298">llvm::TargetFrameLowering::DwarfFrameBase::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/wasmframebase/#a4bb65d886a57952aa51638c04a9f2293">llvm::TargetFrameLowering::DwarfFrameBase::WasmFrameBase::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#a82acb7f3bcf1d1f621a2afbcc936e85b">llvm::TargetFrameLowering::DwarfFrameBase::Location</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#a0f3e9e851be1c3d4d7276752c0c2d330">llvm::TargetFrameLowering::DwarfFrameBase::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#a7be6e48131f5c6e93e48b52a903a720e">llvm::TargetFrameLowering::DwarfFrameBase::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#a69b8f7941a5f3d374f3a4ef2fd86516ba52b328d5d033b938104b2f391ec0b6c7">llvm::TargetFrameLowering::DwarfFrameBase::Register</a> and <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase/#ac491fefadf04fa5c85142a5fab3f3d9d">llvm::TargetFrameLowering::DwarfFrameBase::WasmLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a8cbe3dd2e5c24c363d750bd49f46838a">constructSubprogramScopeDIE</a>.</p>

</div>
</div>

### useGNUAnalogForDwarf5Feature() {#a021658afc8b95fca777f7f6ebc36aa8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfCompileUnit::useGNUAnalogForDwarf5Feature ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to use the GNU analog for a DWARF5 tag, attribute, or location atom.</p>


<p>Only applicable when emitting otherwise DWARF4-compliant debug info.</p>


<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">llvm::DwarfUnit::DD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">constructCallSiteEntryDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab5146bedc026123984b5193c0a6e94af">getDwarf5OrGNUAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9374110f110bab23d52438a26f629216">getDwarf5OrGNULocationAtom</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0ff931a71f37552aeef5c2ef16e950c3">getDwarf5OrGNUTag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addWasmRelocBaseGlobal() {#a95f0e82cc10b33ad64eb683bad3c8c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::addWasmRelocBaseGlobal (<a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> * Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GlobalName, uint64_t GlobalIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add info for Wasm-global-based relocation.</p>

<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>

</div>
</div>

### finishNonUnitTypeDIE() {#a9189d91e2ad4fdcafa2bcabb2416d0c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::finishNonUnitTypeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; D, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * CTy)</td>
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



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1699 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>

</div>
</div>

### getAbstractEntities() {#a7960c18c7eb6f13b6d89e90f77839e1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; const DINode *, std::unique_ptr&lt; DbgEntity &gt; &gt; &amp; llvm::DwarfCompileUnit::getAbstractEntities ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### getAbstractScopeDIEs() {#a30d990804dfc693370a2adabc2b408e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; const DILocalScope *, DIE * &gt; &amp; llvm::DwarfCompileUnit::getAbstractScopeDIEs ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### isDwoUnit() {#a5521057959001396fa26a2e8c5aab93f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfCompileUnit::isDwoUnit ()</td>
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



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 1695 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ExprRefedBaseTypes {#a415b620309aed1e1be14fbb29ae5adaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BaseTypeRef&gt; llvm::DwarfCompileUnit::ExprRefedBaseTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4c89d112b2f04f66826428c19d11301b">createBaseTypeDIEs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AbstractEntities {#abe46f94798b06918c1a1c57ae3d474fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DINode *, std::unique_ptr&lt;DbgEntity&gt; &gt; llvm::DwarfCompileUnit::AbstractEntities</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### AbstractLocalScopeDIEs {#ac78967a5c9a9ac873d176d8340e427ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DILocalScope *, DIE *&gt; llvm::DwarfCompileUnit::AbstractLocalScopeDIEs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### BaseAddress {#a3884246dd85237f280b8af97cbd7b14d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::DwarfCompileUnit::BaseAddress = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### CURanges {#af6f62c2ed3a0fbc376894cca24787229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RangeSpan, 2&gt; llvm::DwarfCompileUnit::CURanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### DeferredLocalDecls {#a18d134ad06b80e5cf536760156d8fed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNodeSetVector llvm::DwarfCompileUnit::DeferredLocalDecls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### DWOId {#afa255852116b6b8b8c7d0e5b4f46ab51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DwarfCompileUnit::DWOId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DWO <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for correlating skeleton and split units.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### GlobalNames {#ac55c33958e5b3386a0becd839e317e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;const DIE *&gt; llvm::DwarfCompileUnit::GlobalNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GlobalNames - A map of globally visible named entities for this unit.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### GlobalTypes {#a8d55b538fcc1945a9f868c8fe757a107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;const DIE *&gt; llvm::DwarfCompileUnit::GlobalTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GlobalTypes - A map of globally visible types for this unit.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### HasRangeLists {#a3bf4085b668a609bf97761b8538ab028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfCompileUnit::HasRangeLists = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### LastFile {#a5fed3b73876ece0036312baf6a6d148b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIFile* llvm::DwarfCompileUnit::LastFile = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### LastFileID {#a98fee2ba144a6109171c5d4153488416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfCompileUnit::LastFileID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### LexicalBlockDIEs {#ae4f283be56c8ad8ff81ee1997bf40b97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DILocalScope *, DIE *&gt; llvm::DwarfCompileUnit::LexicalBlockDIEs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### LineTableStartSym {#a8a826dbe696bfe80107b079c2037b339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::DwarfCompileUnit::LineTableStartSym</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The start of the unit line section, this is also reused in appyStmtList.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### MacroLabelBegin {#a223cf2d20aae5ba92dbf79b9149d2d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::DwarfCompileUnit::MacroLabelBegin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The start of the unit macro info within macro section.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

### Skeleton {#a1a4892d7e6a08612fcfa2e1cfde588f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCompileUnit* llvm::DwarfCompileUnit::Skeleton = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skeleton unit associated with this unit.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## applyConcreteDbgVariableAttribute



<p><a id="applyConcreteDbgVariableAttribute"></a> Overload set which applies attributes to <span class="doxyComputerOutput">VariableDie</span> based on the active variant of <span class="doxyComputerOutput">DV</span>, which is passed as the first argument.</p>


### applyConcreteDbgVariableAttributes {#ad44176145a8a847b3392dbce8e9d2ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::applyConcreteDbgVariableAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loc/single">Loc::Single</a> &amp; Single, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> &amp; DV, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; VariableDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See applyConcreteDbgVariableAttribute.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 791 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>

</div>
</div>

### applyConcreteDbgVariableAttributes {#a9a79f7c9cce95a6fbd98fef45808fa45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::applyConcreteDbgVariableAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loc/multi">Loc::Multi</a> &amp; Multi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> &amp; DV, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; VariableDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See applyConcreteDbgVariableAttribute.</p>

<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>

</div>
</div>

### applyConcreteDbgVariableAttributes {#a726573af3e68dbcb5b752229d03f8744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::applyConcreteDbgVariableAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/loc/mmi">Loc::MMI</a> &amp; MMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> &amp; DV, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; VariableDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See applyConcreteDbgVariableAttribute.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 907 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>

</div>
</div>

### applyConcreteDbgVariableAttributes {#a4b4ab6cab8964c9f60de8e0e0772324f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::applyConcreteDbgVariableAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/loc/entryvalue">Loc::EntryValue</a> &amp; EntryValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> &amp; DV, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; VariableDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See applyConcreteDbgVariableAttribute.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>

</div>
</div>

### applyConcreteDbgVariableAttributes {#a9add5611cac542241e428a88ecde04c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCompileUnit::applyConcreteDbgVariableAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::monostate &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariable">DbgVariable</a> &amp; DV, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; VariableDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See applyConcreteDbgVariableAttribute.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>, definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp">DwarfCompileUnit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
