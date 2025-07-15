---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvsymbolvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LVSymbolVisitor` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVSymbolVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">llvm/DebugInfo/LogicalView/Readers/LVCodeViewVisitor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbacks">SymbolVisitorCallbacks</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef35d6527789bb3c14339bf04d56261">LVSymbolVisitor</a> (LVCodeViewReader *Reader, ScopedPrinter &amp;W, LVLogicalVisitor *LogicalVisitor, LazyRandomTypeCollection &amp;Types, LazyRandomTypeCollection &amp;Ids, LVSymbolVisitorDelegate *ObjDelegate, LVShared *Shared)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb66fb508d7e33e1c04facf801cea2a7">visitSymbolBegin</a> (CVSymbol &amp;Record) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb63c1e53889580c2adff7d040b7620">visitSymbolBegin</a> (CVSymbol &amp;Record, uint32_t Offset) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Paired begin/end actions for all symbols. <a href="#a2bb63c1e53889580c2adff7d040b7620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1789b181a5b67fbf120a7338f5fd7340">visitSymbolEnd</a> (CVSymbol &amp;Record) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff047591187b7be4e82469398177bd37">visitUnknownSymbol</a> (CVSymbol &amp;Record) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Action to take on unknown symbols. By default, they are ignored. <a href="#aff047591187b7be4e82469398177bd37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b73a81f4900e2beefee963a8856cc6">visitKnownRecord</a> (CVSymbol &amp;Record, BlockSym &amp;Block) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac911209abea3b815ff6f96fe71560b">visitKnownRecord</a> (CVSymbol &amp;Record, BPRelativeSym &amp;Local) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89b27021a77eb70d0481da029751aebb">visitKnownRecord</a> (CVSymbol &amp;Record, BuildInfoSym &amp;BuildInfo) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d92f8e253ad8bb1bdb5e60f91c877d">visitKnownRecord</a> (CVSymbol &amp;Record, Compile2Sym &amp;Compile2) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc9a506692070b035881b1d548c87965">visitKnownRecord</a> (CVSymbol &amp;Record, Compile3Sym &amp;Compile3) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7715a3a87a83a23b15d67031e6855044">visitKnownRecord</a> (CVSymbol &amp;Record, ConstantSym &amp;Constant) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae901cd9487d3528e4305f60715aa53a4">visitKnownRecord</a> (CVSymbol &amp;Record, DataSym &amp;Data) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec38ee744ebd39dd489b0d5f52ada00">visitKnownRecord</a> (CVSymbol &amp;Record, DefRangeFramePointerRelFullScopeSym &amp;DefRangeFramePointerRelFullScope) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cc8f37b88434f493eb4cdf2c6596ba5">visitKnownRecord</a> (CVSymbol &amp;Record, DefRangeFramePointerRelSym &amp;DefRangeFramePointerRel) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7651adf465ecbe58fce9cb202391532">visitKnownRecord</a> (CVSymbol &amp;Record, DefRangeRegisterRelSym &amp;DefRangeRegisterRel) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9722ed801caebb3a695ed7dfe0472d2a">visitKnownRecord</a> (CVSymbol &amp;Record, DefRangeRegisterSym &amp;DefRangeRegister) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4452fd8e79fab52e8fa7a243ad0ba3c9">visitKnownRecord</a> (CVSymbol &amp;Record, DefRangeSubfieldRegisterSym &amp;DefRangeSubfieldRegister) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8767d62827feb3a07578e10a648c8f">visitKnownRecord</a> (CVSymbol &amp;Record, DefRangeSubfieldSym &amp;DefRangeSubfield) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6dce4234dfed467146522a0c820df35">visitKnownRecord</a> (CVSymbol &amp;Record, DefRangeSym &amp;DefRange) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d35c98ac054e90008f7ccb2267aa147">visitKnownRecord</a> (CVSymbol &amp;Record, FrameProcSym &amp;FrameProc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a5adea20fc95bb7884b808c62e58fa">visitKnownRecord</a> (CVSymbol &amp;Record, InlineSiteSym &amp;InlineSite) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1b660812c790e9e40def86f8f9b472">visitKnownRecord</a> (CVSymbol &amp;Record, LocalSym &amp;Local) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad346357982c3fcc064fa5e5b434233f3">visitKnownRecord</a> (CVSymbol &amp;Record, ObjNameSym &amp;ObjName) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a5f40ab7232a3d65f93896104d82357">visitKnownRecord</a> (CVSymbol &amp;Record, ProcSym &amp;Proc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84cd42c2c873ab9cd791ecd43b5d4e4">visitKnownRecord</a> (CVSymbol &amp;Record, RegRelativeSym &amp;Local) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0634ef995ed734d9cc3f51484bd58a61">visitKnownRecord</a> (CVSymbol &amp;Record, ScopeEndSym &amp;ScopeEnd) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82e6c167b5c0eb346bdf5125df2134e">visitKnownRecord</a> (CVSymbol &amp;Record, Thunk32Sym &amp;Thunk) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b76ca042deff17f9ea685d118012fd">visitKnownRecord</a> (CVSymbol &amp;Record, UDTSym &amp;UDT) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf84d48048aee19abab732beff8318f6">visitKnownRecord</a> (CVSymbol &amp;Record, UsingNamespaceSym &amp;UN) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28ec6a31deb35ac1cdeceb5d544fccce">visitKnownRecord</a> (CVSymbol &amp;Record, JumpTableSym &amp;JumpTable) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14292195c357c0ee1d3c90f8a92551e2">visitKnownRecord</a> (CVSymbol &amp;Record, CallerSym &amp;Caller) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39d4961ae39ea88440f7580b39f30b66">printLocalVariableAddrRange</a> (const LocalVariableAddrRange &amp;Range, uint32_t RelocationOffset)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6881c8b049a83ccb5cf9f44a2ae3b2a4">printLocalVariableAddrGap</a> (ArrayRef&lt; LocalVariableAddrGap &gt; Gaps)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac02c2f823df24143853db031a5971130">printTypeIndex</a> (StringRef FieldName, TypeIndex TI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a200b58acf493542391b32e12f57084da">symbolIsCompileUnit</a> (SymbolKind Kind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23fc6d2bb2317a1c5262ddd84544ed6b">determineSymbolKind</a> (LVSymbol *Symbol, RegisterId Register)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader">LVCodeViewReader</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae52f5ff440ac6ef509cabcbb969eb4">Reader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58a246aa4107faadb2633930458b22d4">W</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor">LVLogicalVisitor</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9886436d70e68ab351a74a7fef3b20b">LogicalVisitor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412bc72789d9400347d3a5880f7cbca8">Types</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ec1e149b7893ea258e63dbe1e9ac45a">Ids</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitordelegate">LVSymbolVisitorDelegate</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f1e720bcd80897b8879213cab6628c">ObjDelegate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/logicalview/lvshared">LVShared</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010548f0ca67c01fba4ee41ea39b00e7">Shared</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4155c46429471027bff8e6fa2d89b21">CurrentOffset</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab048b593f0a0de17d8201ad8db8a32d3">CurrentObjectName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol">LVSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06cb91defccec4f9174fd91cddc918d6">LocalSymbol</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74318d03818a25c00dcfed64a5120141">HasIds</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3f49510ef897634d204c66412a9ee3">InFunctionScope</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d647dd440e4456137f3ba8e5db4d10a">IsCompileUnit</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a18efaabef8a962bb9f48589ec97b5be9">RegisterId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b954e5baa12d358793a014b1e34ee4">LocalFrameRegister</a> = RegisterId::NONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a18efaabef8a962bb9f48589ec97b5be9">RegisterId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f5183af4d02ef99087f41f74ae252d1">ParamFrameRegister</a> = RegisterId::NONE</td>
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


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LVSymbolVisitor() {#a4ef35d6527789bb3c14339bf04d56261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVSymbolVisitor::LVSymbolVisitor (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader">LVCodeViewReader</a> * Reader, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor">LVLogicalVisitor</a> * LogicalVisitor, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &amp; Types, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &amp; Ids, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitordelegate">LVSymbolVisitorDelegate</a> * ObjDelegate, <a href="/web-llvm/docs/api/structs/llvm/logicalview/lvshared">LVShared</a> * Shared)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitKnownRecord() {#a72b73a81f4900e2beefee963a8856cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/blocksym">BlockSym</a> &amp; Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a8ac911209abea3b815ff6f96fe71560b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/bprelativesym">BPRelativeSym</a> &amp; Local)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a08415ad3aca5fdf4f53418cea4a06ff4">llvm::logicalview::LVScope::addElement</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#a201df3ca3db5a4cfc5dbf5e4cd5001fd">llvm::logicalview::LVObject::getParentScope</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa509820290d57f333403f490dde7316f4">llvm::logicalview::Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a45e15187fdda4ce7c9089efc869db3c4">llvm::logicalview::LVElement::updateLevel</a>.</p>

</div>
</div>

### visitKnownRecord() {#a89b27021a77eb70d0481da029751aebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/buildinfosym">BuildInfoSym</a> &amp; BuildInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/buildinfosym/#a3272f56f1a824f430700fed2734d3395">llvm::codeview::BuildInfoSym::BuildId</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a34d92f8e253ad8bb1bdb5e60f91c877d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/compile2sym">Compile2Sym</a> &amp; Compile2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af9926b3af0182685d3452d7fe5d24bc6">llvm::codeview::getCompileSym3FlagNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac7968d6a65249b6a93f37a1134b54778">llvm::codeview::getCPUTypeNames</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/compile2sym/#a40c6d33766cdcd6879c6473b23b7010d">llvm::codeview::Compile2Sym::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/compile2sym/#a09f3df8b8a76f9db60182004bb16f9a0">llvm::codeview::Compile2Sym::getLanguage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1c10e59416d98e95d2bc433fdb8273ab">llvm::logicalview::getReader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adb139a16564e12216b2d4bfea7a81eff">llvm::codeview::getSourceLanguageNames</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a8d96f20ae76f4b4a0de2b0712d5fdfb6">llvm::logicalview::LVReader::isSystemEntry</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/compile2sym/#af81ec14a115b0cddbd45a9ca24aca44d">llvm::codeview::Compile2Sym::Machine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/compile2sym/#a9126daf7216d388ef13f6a5eef22e265">llvm::codeview::Compile2Sym::Version</a>.</p>

</div>
</div>

### visitKnownRecord() {#afc9a506692070b035881b1d548c87965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/compile3sym">Compile3Sym</a> &amp; Compile3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af9926b3af0182685d3452d7fe5d24bc6">llvm::codeview::getCompileSym3FlagNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac7968d6a65249b6a93f37a1134b54778">llvm::codeview::getCPUTypeNames</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/compile3sym/#a38d945ee6d3b9b50b8bdfa87c8e27a71">llvm::codeview::Compile3Sym::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/compile3sym/#a80d2654377e9698c52755f103d21b244">llvm::codeview::Compile3Sym::getLanguage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1c10e59416d98e95d2bc433fdb8273ab">llvm::logicalview::getReader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adb139a16564e12216b2d4bfea7a81eff">llvm::codeview::getSourceLanguageNames</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a8d96f20ae76f4b4a0de2b0712d5fdfb6">llvm::logicalview::LVReader::isSystemEntry</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/compile3sym/#ad73a7f403903500f2428b6b094c8b0e4">llvm::codeview::Compile3Sym::Machine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/compile3sym/#a9dde8d5888eca17314932274e6627312">llvm::codeview::Compile3Sym::Version</a>.</p>

</div>
</div>

### visitKnownRecord() {#a7715a3a87a83a23b15d67031e6855044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/constantsym">ConstantSym</a> &amp; Constant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>

</div>
</div>

### visitKnownRecord() {#ae901cd9487d3528e4305f60715aa53a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/datasym">DataSym</a> &amp; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1333 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1c10e59416d98e95d2bc433fdb8273ab">llvm::logicalview::getReader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a2ec38ee744ebd39dd489b0d5f52ada00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeframepointerrelfullscopesym">DefRangeFramePointerRelFullScopeSym</a> &amp; DefRangeFramePointerRelFullScope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1038 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeframepointerrelfullscopesym/#aef322c6616f52ee18274b137dc72b3b8">llvm::codeview::DefRangeFramePointerRelFullScopeSym::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a0cc8f37b88434f493eb4cdf2c6596ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeframepointerrelsym">DefRangeFramePointerRelSym</a> &amp; DefRangeFramePointerRel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1066 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeframepointerrelsym/#ad200205a0e50a16efc32e0af5168e487">llvm::codeview::DefRangeFramePointerRelSym::Gaps</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeframepointerrelsym/#a74bf299d325f3c136b53ef0aa3e49d01">llvm::codeview::DefRangeFramePointerRelSym::getRelocationOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeframepointerrelsym/#a4e58f71f2e3e43d9e84a34b96437f914">llvm::codeview::DefRangeFramePointerRelSym::Hdr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeframepointerrelheader/#a18ec6b7155d33dedeb3105e572c81b34">llvm::codeview::DefRangeFramePointerRelHeader::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeframepointerrelsym/#a70ff9f47cc66f304584a40ef427355ad">llvm::codeview::DefRangeFramePointerRelSym::Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa87ba2ecc8b6915e8bd6f5089918229fd">llvm::logicalview::Range</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#ab7651adf465ecbe58fce9cb202391532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregisterrelsym">DefRangeRegisterRelSym</a> &amp; DefRangeRegisterRel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterrelheader/#aa35912ee6dc477785d65b0bfa20de028">llvm::codeview::DefRangeRegisterRelHeader::BasePointerOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregisterrelsym/#aa8b3a2966825eb52f7526e7d96de8ca6">llvm::codeview::DefRangeRegisterRelSym::Gaps</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregisterrelsym/#a4ba9b0352eb8f5ecfcc6e8c66fc9e4d5">llvm::codeview::DefRangeRegisterRelSym::getRelocationOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregisterrelsym/#a0e9878bf4591ee8350b1642eda5f9179">llvm::codeview::DefRangeRegisterRelSym::hasSpilledUDTMember</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregisterrelsym/#a03b6426b1fddf2f3bb02ac863219dfd3">llvm::codeview::DefRangeRegisterRelSym::Hdr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregisterrelsym/#a65d14670f390ee5befce64caa60207bc">llvm::codeview::DefRangeRegisterRelSym::offsetInParent</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregisterrelsym/#ad8212213d7a45b0108f59e0fe1934f6d">llvm::codeview::DefRangeRegisterRelSym::Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa87ba2ecc8b6915e8bd6f5089918229fd">llvm::logicalview::Range</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterrelheader/#a5e13ff5f78796391c35246e69a83ab79">llvm::codeview::DefRangeRegisterRelHeader::Register</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a9722ed801caebb3a695ed7dfe0472d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregistersym">DefRangeRegisterSym</a> &amp; DefRangeRegister)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregistersym/#abb12e433bd1fd19173c3f48bc9df59a2">llvm::codeview::DefRangeRegisterSym::Gaps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aa3906edca282ab1321562c82c7e0ad69">llvm::codeview::getRegisterNames</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregistersym/#a54be95e9ae238d13b8ce5fde11798d28">llvm::codeview::DefRangeRegisterSym::getRelocationOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregistersym/#af3486dce817f419259b1a5c12db9751d">llvm::codeview::DefRangeRegisterSym::Hdr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterheader/#a2e0c520284acc9fc94e513f6c3a3a881">llvm::codeview::DefRangeRegisterHeader::MayHaveNoName</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangeregistersym/#ad81c6741b3424fe73005d81024dae91f">llvm::codeview::DefRangeRegisterSym::Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa87ba2ecc8b6915e8bd6f5089918229fd">llvm::logicalview::Range</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterheader/#a104d5325c4fd1b5af890bde1d9401a97">llvm::codeview::DefRangeRegisterHeader::Register</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a4452fd8e79fab52e8fa7a243ad0ba3c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldregistersym">DefRangeSubfieldRegisterSym</a> &amp; DefRangeSubfieldRegister)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1178 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldregistersym/#a98e5b67d88129a4ad788d7bc4e25fd96">llvm::codeview::DefRangeSubfieldRegisterSym::Gaps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aa3906edca282ab1321562c82c7e0ad69">llvm::codeview::getRegisterNames</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldregistersym/#a80492a7189ad008e3e053699e505e5a9">llvm::codeview::DefRangeSubfieldRegisterSym::getRelocationOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldregistersym/#ad4fd7af071924580a885221861775e5d">llvm::codeview::DefRangeSubfieldRegisterSym::Hdr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangesubfieldregisterheader/#a2d84d27279b2899af173d543663f6522">llvm::codeview::DefRangeSubfieldRegisterHeader::MayHaveNoName</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangesubfieldregisterheader/#a91323e71d4e779505960a2624d644e06">llvm::codeview::DefRangeSubfieldRegisterHeader::OffsetInParent</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldregistersym/#a5433c848b682fc51af53d1e7508636ae">llvm::codeview::DefRangeSubfieldRegisterSym::Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa87ba2ecc8b6915e8bd6f5089918229fd">llvm::logicalview::Range</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangesubfieldregisterheader/#a8ec4f0468be2b9fd2f3951853e283402">llvm::codeview::DefRangeSubfieldRegisterHeader::Register</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a6c8767d62827feb3a07578e10a648c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldsym">DefRangeSubfieldSym</a> &amp; DefRangeSubfield)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1216 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldsym/#aa6ec5926bd110e889fdce41e93221b89">llvm::codeview::DefRangeSubfieldSym::Gaps</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldsym/#aef2f5b57ff90af629d9a8857c01b462b">llvm::codeview::DefRangeSubfieldSym::getRelocationOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref/#a89f91fb97bacfa2e66d5f5b912a85304">llvm::codeview::DebugStringTableSubsectionRef::getString</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldsym/#af710a055605d898b0fb4d77d942707b3">llvm::codeview::DefRangeSubfieldSym::OffsetInParent</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldsym/#a4b71c4e4b342e47a13863691b9731a42">llvm::codeview::DefRangeSubfieldSym::Program</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesubfieldsym/#ae2532acee7975700bbb5dc3608ae47ad">llvm::codeview::DefRangeSubfieldSym::Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa87ba2ecc8b6915e8bd6f5089918229fd">llvm::logicalview::Range</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#ab6dce4234dfed467146522a0c820df35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesym">DefRangeSym</a> &amp; DefRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesym/#a754161bd7d4b88ae85b58da00cfb20e0">llvm::codeview::DefRangeSym::Gaps</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesym/#a8e5752ad97761d41cf12c83fc507372c">llvm::codeview::DefRangeSym::getRelocationOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref/#a89f91fb97bacfa2e66d5f5b912a85304">llvm::codeview::DebugStringTableSubsectionRef::getString</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesym/#ae6bad6400149830c3c898a01f72bbf72">llvm::codeview::DefRangeSym::Program</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/defrangesym/#aa780aaf8aeaf74048ed8270c6a3a5438">llvm::codeview::DefRangeSym::Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa87ba2ecc8b6915e8bd6f5089918229fd">llvm::logicalview::Range</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a8d35c98ac054e90008f7ccb2267aa147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/frameprocsym">FrameProcSym</a> &amp; FrameProc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1300 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a05feed307dcff1df2e39f250502ab4b3a9081f59bd5fbb04a767ceb79fe39f01e">llvm::dwarf::DW_INL_declared_inlined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a05feed307dcff1df2e39f250502ab4b3a89db9e54bf0b0c16e3e98cf8607ff640">llvm::dwarf::DW_INL_inlined</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/frameprocsym/#a9f9234933a971625f87de9950d261117">llvm::codeview::FrameProcSym::Flags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/frameprocsym/#a70df966921e77291bef69d4fb11589cc">llvm::codeview::FrameProcSym::getLocalFramePtrReg</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/frameprocsym/#a8d6b80731607ab8ea8ee698d255ce3cf">llvm::codeview::FrameProcSym::getParamFramePtrReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30bafc6d010fc5b3d8ff4400670e597c4e7b">llvm::codeview::Inlined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30bad52f2ee95fcec0572e4fa7bf7a1edcf2">llvm::codeview::MarkedInline</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a10a5adea20fc95bb7884b808c62e58fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/inlinesitesym">InlineSiteSym</a> &amp; InlineSite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1375 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a05feed307dcff1df2e39f250502ab4b3a89db9e54bf0b0c16e3e98cf8607ff640">llvm::dwarf::DW_INL_inlined</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a6a8055f0fbfe309460da1d55c9735d73">llvm::logicalview::LVElement::setInlineCode</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a6cac754bf68e000a76bab131e6097c5e">llvm::logicalview::LVElement::setReference</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ae4cf505e0bb9d8ef6c42dacfb7c4450e">llvm::logicalview::LVObject::setTag</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a5d1b660812c790e9e40def86f8f9b472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/localsym">LocalSym</a> &amp; Local)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1411 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a08415ad3aca5fdf4f53418cea4a06ff4">llvm::logicalview::LVScope::addElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aa23c84528d1f5453a84583dc639f844f">llvm::codeview::getLocalFlagNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a122913b65bb4e07d697d9910e5e58762ae35d7621c3114c8072d6c2a47c910915">llvm::codeview::IsCompilerGenerated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a122913b65bb4e07d697d9910e5e58762a3c21f0dc49836cff410ee48c6541f48d">llvm::codeview::IsParameter</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa509820290d57f333403f490dde7316f4">llvm::logicalview::Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a45e15187fdda4ce7c9089efc869db3c4">llvm::logicalview::LVElement::updateLevel</a>.</p>

</div>
</div>

### visitKnownRecord() {#ad346357982c3fcc064fa5e5b434233f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/objnamesym">ObjNameSym</a> &amp; ObjName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1460 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/objnamesym/#afb1a38ba6398c2bcc984a517fb414084">llvm::codeview::ObjNameSym::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/objnamesym/#a2d0074bd2a7563e6863a57548c2c5adc">llvm::codeview::ObjNameSym::Signature</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a5a5f40ab7232a3d65f93896104d82357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym">ProcSym</a> &amp; Proc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1471 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym/#a4cc8ab95c4a9ba051f766e0de8760d3b">llvm::codeview::ProcSym::CodeOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym/#adfb66187c91573e949cf8e085f87e031">llvm::codeview::ProcSym::CodeSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab996639d406a5466d5c8a1586fb4a9d8">llvm::demangle</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym/#affd12340b79c294dcc22749a4316235c">llvm::codeview::ProcSym::Flags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym/#a4baf229be1b62ed0d2c85d1b19944517">llvm::codeview::ProcSym::FunctionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a957f4d1425cced530d8488b4bbeaa425">llvm::logicalview::getInnerComponent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aae92675b6e3f5e6bac3b1c2c811a2c87">llvm::codeview::getProcSymFlagNames</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym/#ac9c3fcf22f9cbdcaa995703cd29b223f">llvm::codeview::ProcSym::getRelocationOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#acb1db28679177b959c08481c98cafa29">llvm::codeview::TypeIndex::isNoneType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a405aadbe59614b6be8cfbcd0f3b4ac2a">llvm::codeview::TypeIndex::isSimple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym/#a796fdc408b43d5ba05514eda019d01d9">llvm::codeview::ProcSym::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/procsym/#a9b985905ab7d51788bfeaf5fadb78371">llvm::codeview::ProcSym::Segment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#ae84cd42c2c873ab9cd791ecd43b5d4e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/regrelativesym">RegRelativeSym</a> &amp; Local)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 867 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a08415ad3aca5fdf4f53418cea4a06ff4">llvm::logicalview::LVScope::addElement</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#a201df3ca3db5a4cfc5dbf5e4cd5001fd">llvm::logicalview::LVObject::getParentScope</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa509820290d57f333403f490dde7316f4">llvm::logicalview::Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a45e15187fdda4ce7c9089efc869db3c4">llvm::logicalview::LVElement::updateLevel</a>.</p>

</div>
</div>

### visitKnownRecord() {#a0634ef995ed734d9cc3f51484bd58a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/scopeendsym">ScopeEndSym</a> &amp; ScopeEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1615 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#ab82e6c167b5c0eb346bdf5125df2134e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/thunk32sym">Thunk32Sym</a> &amp; Thunk)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1622 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bad23b094e66eef00330206ffe8cd8b6f5">llvm::pdb::Thunk</a>.</p>

</div>
</div>

### visitKnownRecord() {#a81b76ca042deff17f9ea685d118012fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/udtsym">UDTSym</a> &amp; UDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1641 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1c10e59416d98e95d2bc433fdb8273ab">llvm::logicalview::getReader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a63a780627da7c5b7088ebaf5bd7408aa">llvm::logicalview::getRecordName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba37c9ef439007788bd633ea027a36e87e">llvm::pdb::UDT</a>.</p>

</div>
</div>

### visitKnownRecord() {#adf84d48048aee19abab732beff8318f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/usingnamespacesym">UsingNamespaceSym</a> &amp; UN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1676 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/usingnamespacesym/#a332933be3f739094f26f874c512981b9">llvm::codeview::UsingNamespaceSym::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a28ec6a31deb35ac1cdeceb5d544fccce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/jumptablesym">JumpTableSym</a> &amp; JumpTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1683 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a61c0d5ba66a4752cf3ae54d83cd77a1a">llvm::codeview::getJumpTableEntrySizeNames</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a14292195c357c0ee1d3c90f8a92551e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/callersym">CallerSym</a> &amp; Caller)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1700 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba14e7dd71a82eb3c2500ac2687efef82b">llvm::pdb::Caller</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitSymbolBegin() {#afb66fb508d7e33e1c04facf801cea2a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitSymbolBegin (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>Reference <a href="#afb66fb508d7e33e1c04facf801cea2a7">visitSymbolBegin</a>.</p>


<p>Referenced by <a href="#afb66fb508d7e33e1c04facf801cea2a7">visitSymbolBegin</a>.</p>

</div>
</div>

### visitSymbolBegin() {#a2bb63c1e53889580c2adff7d040b7620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitSymbolBegin (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, uint32_t Offset)</td>
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

<p>Paired begin/end actions for all symbols.</p>


<p>Receives all record data, including the fixed-length record prefix. <a href="#afb66fb508d7e33e1c04facf801cea2a7">visitSymbolBegin()</a> should return the type of the Symbol, or an error if it cannot be determined.</p>


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a7c1504aff077c30eff33d31643dbb57d">llvm::codeview::getSymbolTypeNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefadfd0a82c4bf37b1e90b690a22a20692e">llvm::logicalview::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a921f65a0abb128eb4e94c61eb85a1748">llvm::codeview::symbolOpensScope</a>.</p>

</div>
</div>

### visitSymbolEnd() {#a1789b181a5b67fbf120a7338f5fd7340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitSymbolEnd (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a7c1504aff077c30eff33d31643dbb57d">llvm::codeview::getSymbolTypeNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a68021fb1ffc174d48bce0deeb5671788">llvm::codeview::symbolEndsScope</a>.</p>

</div>
</div>

### visitUnknownSymbol() {#aff047591187b7be4e82469398177bd37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVSymbolVisitor::visitUnknownSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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

<p>Action to take on unknown symbols. By default, they are ignored.</p>

<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### determineSymbolKind() {#a23fc6d2bb2317a1c5262ddd84544ed6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVSymbolVisitor::determineSymbolKind (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol">LVSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a18efaabef8a962bb9f48589ec97b5be9">RegisterId</a> Register)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### printLocalVariableAddrGap() {#a6881c8b049a83ccb5cf9f44a2ae3b2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVSymbolVisitor::printLocalVariableAddrGap (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/localvariableaddrgap">LocalVariableAddrGap</a> &gt; Gaps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### printLocalVariableAddrRange() {#a39d4961ae39ea88440f7580b39f30b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVSymbolVisitor::printLocalVariableAddrRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codeview/localvariableaddrrange">LocalVariableAddrRange</a> &amp; Range, uint32_t RelocationOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### printTypeIndex() {#ac02c2f823df24143853db031a5971130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVSymbolVisitor::printTypeIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### symbolIsCompileUnit() {#a200b58acf493542391b32e12f57084da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVSymbolVisitor::symbolIsCompileUnit (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">SymbolKind</a> Kind)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentObjectName {#ab048b593f0a0de17d8201ad8db8a32d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::logicalview::LVSymbolVisitor::CurrentObjectName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### CurrentOffset {#ab4155c46429471027bff8e6fa2d89b21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::logicalview::LVSymbolVisitor::CurrentOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### HasIds {#a74318d03818a25c00dcfed64a5120141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVSymbolVisitor::HasIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### Ids {#a6ec1e149b7893ea258e63dbe1e9ac45a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection&amp; llvm::logicalview::LVSymbolVisitor::Ids</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### InFunctionScope {#afb3f49510ef897634d204c66412a9ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVSymbolVisitor::InFunctionScope = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### IsCompileUnit {#a4d647dd440e4456137f3ba8e5db4d10a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVSymbolVisitor::IsCompileUnit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### LocalFrameRegister {#a96b954e5baa12d358793a014b1e34ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterId llvm::logicalview::LVSymbolVisitor::LocalFrameRegister = RegisterId::NONE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### LocalSymbol {#a06cb91defccec4f9174fd91cddc918d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbol* llvm::logicalview::LVSymbolVisitor::LocalSymbol = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### LogicalVisitor {#aa9886436d70e68ab351a74a7fef3b20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVLogicalVisitor* llvm::logicalview::LVSymbolVisitor::LogicalVisitor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### ObjDelegate {#ae9f1e720bcd80897b8879213cab6628c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbolVisitorDelegate* llvm::logicalview::LVSymbolVisitor::ObjDelegate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### ParamFrameRegister {#a3f5183af4d02ef99087f41f74ae252d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterId llvm::logicalview::LVSymbolVisitor::ParamFrameRegister = RegisterId::NONE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### Reader {#a5ae52f5ff440ac6ef509cabcbb969eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVCodeViewReader* llvm::logicalview::LVSymbolVisitor::Reader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### Shared {#a010548f0ca67c01fba4ee41ea39b00e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVShared* llvm::logicalview::LVSymbolVisitor::Shared</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### Types {#a412bc72789d9400347d3a5880f7cbca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection&amp; llvm::logicalview::LVSymbolVisitor::Types</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### W {#a58a246aa4107faadb2633930458b22d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedPrinter&amp; llvm::logicalview::LVSymbolVisitor::W</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
