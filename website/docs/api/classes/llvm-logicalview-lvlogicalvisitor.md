---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvlogicalvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LVLogicalVisitor` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVLogicalVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">llvm/DebugInfo/LogicalView/Readers/LVCodeViewVisitor.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46654008276126523078757003c39cbd">LVScopeStack</a> = std::stack&lt; <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b858d9f27a8f02ec88170eb3507fc02">LVInlineeEntry</a> = std::pair&lt; uint32_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d7e879e21ff73804313c85ac84e079">LVInlineeInfo</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a>, LVInlineeEntry &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a2cd771c7636ae7d678c857cf0b8065">LVLogicalVisitor</a> (LVCodeViewReader *Reader, ScopedPrinter &amp;W, llvm::pdb::InputFile &amp;Input)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78145049dd341346af2472c711b58f2">setInput</a> (std::shared_ptr&lt; llvm::pdb::InputFile &gt; TypeServer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fdec980e4ef3a393d4070c1ab0eb608">setInput</a> (std::shared_ptr&lt; LazyRandomTypeCollection &gt; PrecompHeader)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0015c4403308257ee00d748bd1df52bd">addInlineeInfo</a> (TypeIndex TI, uint32_t LineNumber, StringRef Filename)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a> (StringRef FieldName, TypeIndex TI, uint32_t StreamIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5983caf504578aa578a6cc4e494333ef">printMemberAttributes</a> (MemberAttributes Attrs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee48c8b3820d7921735c05689074899">printMemberAttributes</a> (MemberAccess Access, MethodKind Kind, MethodOptions Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af691af071aabd478296d790bd536104c">createElement</a> (TypeLeafKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1022791b30259f5f02aaf547d52def4">createElement</a> (SymbolKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dea375bf5f6ee24e99884e5d5d91944">createElement</a> (TypeIndex TI, TypeLeafKind Kind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68da2ce647c44cc62f321e770312a1ec">inlineSiteAnnotation</a> (LVScope *AbstractFunction, LVScope *InlinedFunction, InlineSiteSym &amp;InlineSite)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c1887e97daffa480031c432a34c894">pushScope</a> (LVScope *Scope)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f3c4beadc37f6026e6e3d048afe3f0">popScope</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a389be388f2f65fd0647e21ed64263394">closeScope</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96cebf83499ed175093feaf6a11faa7c">setRoot</a> (LVScope *Root)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaaffda56ec54951484eed174154c4f8">addElement</a> (LVScope *Scope, bool IsCompileUnit)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49079d9f002ed7634d570403acaf66e9">addElement</a> (LVSymbol *Symbol)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46950157c305545f281d91d3aae9478">addElement</a> (LVType *Type)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac143b752eb34740b07eeae2ac06360c9">getCompileUnitName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529099998163a45fe5679ffae51efcf5">setCompileUnitName</a> (std::string Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a> (uint32_t StreamIdx, TypeIndex TI, LVScope *Parent=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac00415fcfc3c32dbdaff086663d0eb16">getShared</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae557894f894c777fc261ff1244d91237">getReaderScope</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a> (CVType &amp;Record, TypeIndex TI, LVElement *Element, uint32_t StreamIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a> (CVType &amp;Record)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a> (CVMemberRecord &amp;Record, TypeIndex TI, LVElement *Element, uint32_t StreamIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a> (CVMemberRecord &amp;Record)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab787867fd9b82c943b4a971511ee78cb">startProcessArgumentList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d3139101d2e070d14668cd975a6158b">stopProcessArgumentList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa90811e29ceaa8c0d237d9fb2049e38">processFiles</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae19100bf53254a287d0812a18cf3a6b9">processLines</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6fd9f274d063ce78752881806051307">processNamespaces</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d93ef611f1c51f7fa6da9281d2845a">printRecords</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa583f2e4b792c5eadd2aecc04e1c2361">visitUnknownType</a> (CVType &amp;Record, TypeIndex TI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0015ff019ddc43f0e4840febaf74664d">visitKnownRecord</a> (CVType &amp;Record, ArgListRecord &amp;Args, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac72c1663cfda32b4cb722e815b1ea005">visitKnownRecord</a> (CVType &amp;Record, ArrayRecord &amp;AT, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e81e85684fa7bde4a91f870f4c44b8">visitKnownRecord</a> (CVType &amp;Record, BitFieldRecord &amp;BF, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d42ec1825f9e56033a386b52d39337">visitKnownRecord</a> (CVType &amp;Record, BuildInfoRecord &amp;BI, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade7088de2025cc1850af4e51e17c9255">visitKnownRecord</a> (CVType &amp;Record, ClassRecord &amp;Class, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca019e8fbb127c461eba43cb4649642">visitKnownRecord</a> (CVType &amp;Record, EnumRecord &amp;Enum, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4808cdf082e92e24c882c5a00a0c93">visitKnownRecord</a> (CVType &amp;Record, FieldListRecord &amp;FieldList, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3473440a5ef85d0c44e95308f22a77">visitKnownRecord</a> (CVType &amp;Record, FuncIdRecord &amp;Func, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb64629acda1a991247ba4c049c60c4">visitKnownRecord</a> (CVType &amp;Record, LabelRecord &amp;LR, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd431dc7da0c6db4b9987a3b85e4876">visitKnownRecord</a> (CVType &amp;Record, ModifierRecord &amp;Mod, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d54e1dd5acde5b32e990f461bc2daa2">visitKnownRecord</a> (CVType &amp;Record, MemberFuncIdRecord &amp;Id, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa27f4570b743eb19adf1278056c387">visitKnownRecord</a> (CVType &amp;Record, MemberFunctionRecord &amp;MF, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac28d415acf28987bc11560889b9e76b1">visitKnownRecord</a> (CVType &amp;Record, MethodOverloadListRecord &amp;Overloads, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6549e77fe8b0654042aa48cc785d3e7">visitKnownRecord</a> (CVType &amp;Record, PointerRecord &amp;Ptr, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a421cf2ef2fc76b72f322783bfd9e3">visitKnownRecord</a> (CVType &amp;Record, ProcedureRecord &amp;Proc, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20ff4db3e31aae1d9b6ce04ad03c421d">visitKnownRecord</a> (CVType &amp;Record, UnionRecord &amp;Union, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a978c30bae82893422130ec3bf98a56ce">visitKnownRecord</a> (CVType &amp;Record, TypeServer2Record &amp;TS, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f7b86f4b3c852f56ca5abb71840a4d6">visitKnownRecord</a> (CVType &amp;Record, VFTableRecord &amp;VFT, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c5ef69da66ecc0e7a63e74252cbffe">visitKnownRecord</a> (CVType &amp;Record, VFTableShapeRecord &amp;Shape, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec578dadc7c4409612fdaf21e83dcec">visitKnownRecord</a> (CVType &amp;Record, StringListRecord &amp;Strings, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8a4731c6b598189e6503052d277cf5">visitKnownRecord</a> (CVType &amp;Record, StringIdRecord &amp;String, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2bde320a72ca54870bb93585991de89">visitKnownRecord</a> (CVType &amp;Record, UdtSourceLineRecord &amp;SourceLine, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe0bd76d0a524ced56b7dd7e10451ee8">visitKnownRecord</a> (CVType &amp;Record, UdtModSourceLineRecord &amp;ModSourceLine, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb7f7308a370b9bb952aebfa8c04d585">visitKnownRecord</a> (CVType &amp;Record, PrecompRecord &amp;Precomp, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d47724a657b7c47da03316e855b9b48">visitKnownRecord</a> (CVType &amp;Record, EndPrecompRecord &amp;EndPrecomp, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e358bb94c8f56f008ff91345a9092e">visitUnknownMember</a> (CVMemberRecord &amp;Record, TypeIndex TI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a> (CVMemberRecord &amp;Record, BaseClassRecord &amp;Base, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa300b4d35c32e9fbd142578c447a556f">visitKnownMember</a> (CVMemberRecord &amp;Record, DataMemberRecord &amp;Field, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ddf6a3be3f9d8629ad887d3125ce0bb">visitKnownMember</a> (CVMemberRecord &amp;Record, EnumeratorRecord &amp;Enum, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3229086e49b76d1dbdc7bd0e6300737">visitKnownMember</a> (CVMemberRecord &amp;Record, ListContinuationRecord &amp;Cont, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9aeda1f1736cdf67f11ea6f1c99b107">visitKnownMember</a> (CVMemberRecord &amp;Record, NestedTypeRecord &amp;Nested, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9efe423cacffbe87239e1e0f556d6d86">visitKnownMember</a> (CVMemberRecord &amp;Record, OneMethodRecord &amp;Method, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d03e43695c8f8371c9c1fe4a6519ae6">visitKnownMember</a> (CVMemberRecord &amp;Record, OverloadedMethodRecord &amp;Method, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad006d3e6801c21a539ffc8b32d91a17d">visitKnownMember</a> (CVMemberRecord &amp;Record, StaticDataMemberRecord &amp;Field, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee2ae8a2caff14a0928ded0348efd8c">visitKnownMember</a> (CVMemberRecord &amp;Record, VFPtrRecord &amp;VFTable, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c4e4e6831c8f3f7304cdaf11060b0f">visitKnownMember</a> (CVMemberRecord &amp;Record, VirtualBaseClassRecord &amp;Base, TypeIndex TI, LVElement *Element)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4681071bf84200dace5251305a67a1c">visitKnownMember</a> (CVMemberRecord &amp;Record, TypeVisitorCallbacks &amp;Callbacks, TypeIndex TI, LVElement *Element)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af11c2a836925d0e70268cb478d829473">visitKnownRecord</a> (CVType &amp;Record, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38aaf9af22e7aebd5e41ddb05c414922">visitMemberRecord</a> (CVMemberRecord &amp;Record, TypeVisitorCallbacks &amp;Callbacks, TypeIndex TI, LVElement *Element)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a> (CVType &amp;Record, TypeIndex TI, LVElement *Element)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0207108b6a9915e15f1c51ae130e4fc">types</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7f4d4241e0bab3dc4c34f376a2b027">ids</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af14a3d113f966a63549e9f97536a25e4">visitFieldListMemberStream</a> (TypeIndex TI, LVElement *Element, ArrayRef&lt; uint8_t &gt; FieldList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype">LVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38dbbbf51dacc424037386cba22fdff7">createBaseType</a> (TypeIndex TI, StringRef TypeName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype">LVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66bb16b301f46019574cd3f290b30a0">createPointerType</a> (TypeIndex TI, StringRef TypeName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4361facf4ae0c29135543afc88fcc6af">createParameter</a> (TypeIndex TI, StringRef Name, LVScope *Parent)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b6b26c42264ff56ba114259a01f7111">createParameter</a> (LVElement *Element, StringRef Name, LVScope *Parent)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa68e6f8040df9211ba25409dae01334">createDataMember</a> (CVMemberRecord &amp;Record, LVScope *Parent, StringRef Name, TypeIndex Type, MemberAccess Access)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24fdef0fa5fe13d01b065cd7abe6de03">createParents</a> (StringRef ScopedName, LVElement *Element)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5958154e459c5a8cc1779af56941d8b6">CurrentElement</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ecf5656d06b3d2dbe7243e34fd8dea">CurrentScope</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5713cbf681b40f62f591788ae9ab0c84">CurrentSymbol</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype">LVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6605ba61712bd6a951ee6df2c2a5d85a">CurrentType</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149ce82e21fc8a2698e6f53327def127">Reader</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3adbf76993743bebe9266aae0550908a">W</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile">llvm::pdb::InputFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6562ad9a00fdf6584854d337aeb280b6">Input</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile">llvm::pdb::InputFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d064227c6ff5722c1337fbcb00a8fb">TypeServer</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8002267465e31018956f0bd2a1af7209">PrecompHeader</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/logicalview/lvshared">LVShared</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a420f6409cf1e46a646bd97c48fc1cb1c">Shared</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LVScopeStack</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42d736083d2421c3b42983a9dcfcff24">ScopeStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f0834be9db31576a1dc5eb97a2bed9">ReaderParent</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6683a3e1b2aeeb349aefbe217c98dae0">ReaderScope</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ce1abefc4cb5ee245dd3bf9df4999d">InCompileUnitScope</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f81f6060cdd1bb6ef90be2ba10cd35">ProcessArgumentList</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80dc5247559ca3487cbdba3f02ed0e5">OverloadedMethodName</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c36904d390536eb7bba20049f8926f2">CompileUnitName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LVInlineeInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f22fd8227665da352cf3dacaa5f10fc">InlineeInfo</a></td>
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


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LVInlineeEntry {#a4b858d9f27a8f02ec88170eb3507fc02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVLogicalVisitor::LVInlineeEntry =  std::pair&lt;uint32_t, StringRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### LVInlineeInfo {#ad0d7e879e21ff73804313c85ac84e079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVLogicalVisitor::LVInlineeInfo =  std::map&lt;TypeIndex, LVInlineeEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### LVScopeStack {#a46654008276126523078757003c39cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVLogicalVisitor::LVScopeStack =  std::stack&lt;LVScope *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LVLogicalVisitor() {#a7a2cd771c7636ae7d678c857cf0b8065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVLogicalVisitor::LVLogicalVisitor (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader">LVCodeViewReader</a> * Reader, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile">llvm::pdb::InputFile</a> &amp; Input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1730 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addElement() {#adaaffda56ec54951484eed174154c4f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::addElement (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope, bool IsCompileUnit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2953 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a738fb172d3b98e08a4325dc7ca5588b8a8c3ec1f8ff1687eccdbe29b51531787e">llvm::logicalview::IsCompileUnit</a>, <a href="#a55f3c4beadc37f6026e6e3d048afe3f0">popScope</a> and <a href="#aa4c1887e97daffa480031c432a34c894">pushScope</a>.</p>


<p>Referenced by <a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a>, <a href="#a6ddf6a3be3f9d8629ad887d3125ce0bb">visitKnownMember</a>, <a href="#a9efe423cacffbe87239e1e0f556d6d86">visitKnownMember</a> and <a href="#a37c4e4e6831c8f3f7304cdaf11060b0f">visitKnownMember</a>.</p>

</div>
</div>

### addElement() {#a49079d9f002ed7634d570403acaf66e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::addElement (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol">LVSymbol</a> * Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2968 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### addElement() {#af46950157c305545f281d91d3aae9478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::addElement (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype">LVType</a> * Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2972 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### addInlineeInfo() {#a0015c4403308257ee00d748bd1df52bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::addInlineeInfo (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, uint32_t LineNumber, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa1351017ac6423911223bc19a8cb7c653">llvm::logicalview::Filename</a>.</p>

</div>
</div>

### closeScope() {#a389be388f2f65fd0647e21ed64263394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::closeScope ()</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>Reference <a href="#a55f3c4beadc37f6026e6e3d048afe3f0">popScope</a>.</p>

</div>
</div>

### createElement() {#af691af071aabd478296d790bd536104c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement * LVLogicalVisitor::createElement (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a945d5dcbe78d400d17656726e2f6089b">TypeLeafKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2976 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#a02ecf5656d06b3d2dbe7243e34fd8dea">CurrentScope</a>, <a href="#a5713cbf681b40f62f591788ae9ab0c84">CurrentSymbol</a>, <a href="#a6605ba61712bd6a951ee6df2c2a5d85a">CurrentType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a79c2f8f476f8287d14a1c154d9eae2e7">llvm::codeview::TypeIndex::FirstNonSimpleIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>.</p>


<p>Referenced by <a href="#a6dea375bf5f6ee24e99884e5d5d91944">createElement</a>, <a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a>, <a href="#a6ddf6a3be3f9d8629ad887d3125ce0bb">visitKnownMember</a>, <a href="#ae9aeda1f1736cdf67f11ea6f1c99b107">visitKnownMember</a>, <a href="#a9efe423cacffbe87239e1e0f556d6d86">visitKnownMember</a> and <a href="#a37c4e4e6831c8f3f7304cdaf11060b0f">visitKnownMember</a>.</p>

</div>
</div>

### createElement() {#ad1022791b30259f5f02aaf547d52def4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement * LVLogicalVisitor::createElement (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">SymbolKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3061 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#a02ecf5656d06b3d2dbe7243e34fd8dea">CurrentScope</a>, <a href="#a5713cbf681b40f62f591788ae9ab0c84">CurrentSymbol</a>, <a href="#a6605ba61712bd6a951ee6df2c2a5d85a">CurrentType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a>.</p>

</div>
</div>

### createElement() {#a6dea375bf5f6ee24e99884e5d5d91944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement * LVLogicalVisitor::createElement (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a945d5dcbe78d400d17656726e2f6089b">TypeLeafKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3128 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#af691af071aabd478296d790bd536104c">createElement</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a79c2f8f476f8287d14a1c154d9eae2e7">llvm::codeview::TypeIndex::FirstNonSimpleIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a7d5e1069198fc42ca3def0ecb7134ca2">llvm::pdb::formatTypeLeafKind</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#abf33a9b90a30d17ecb3c53b2920cc5b1">llvm::codeview::TypeIndex::getIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ac91b7c005927969946b469b676f10d97">llvm::logicalview::LVObject::setOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>.</p>

</div>
</div>

### finishVisitation() {#aeefe0bd6abc3bfcaa5c237bfa9c13011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::finishVisitation (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2907 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#aa583f2e4b792c5eadd2aecc04e1c2361">visitUnknownType</a>.</p>


<p>Referenced by <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="#a9efe423cacffbe87239e1e0f556d6d86">visitKnownMember</a>, <a href="#a9d03e43695c8f8371c9c1fe4a6519ae6">visitKnownMember</a>, <a href="#ac72c1663cfda32b4cb722e815b1ea005">visitKnownRecord</a>, <a href="#ade7088de2025cc1850af4e51e17c9255">visitKnownRecord</a>, <a href="#a9ca019e8fbb127c461eba43cb4649642">visitKnownRecord</a>, <a href="#aef3473440a5ef85d0c44e95308f22a77">visitKnownRecord</a>, <a href="#a0d54e1dd5acde5b32e990f461bc2daa2">visitKnownRecord</a>, <a href="#afaa27f4570b743eb19adf1278056c387">visitKnownRecord</a>, <a href="#a47a421cf2ef2fc76b72f322783bfd9e3">visitKnownRecord</a> and <a href="#a20ff4db3e31aae1d9b6ce04ad03c421d">visitKnownRecord</a>.</p>

</div>
</div>

### getCompileUnitName() {#ac143b752eb34740b07eeae2ac06360c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::logicalview::LVLogicalVisitor::getCompileUnitName ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### getElement() {#ae4da1612e3cab687247782f44c2807d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement * LVLogicalVisitor::getElement (uint32_t StreamIdx, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Parent=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3313 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a08415ad3aca5fdf4f53418cea4a06ff4">llvm::logicalview::LVScope::addElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#abf33a9b90a30d17ecb3c53b2920cc5b1">llvm::codeview::TypeIndex::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#acb1db28679177b959c08481c98cafa29">llvm::codeview::TypeIndex::isNoneType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a405aadbe59614b6be8cfbcd0f3b4ac2a">llvm::codeview::TypeIndex::isSimple</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a8b1dd732eb26d531ff0a7efc29fda083">llvm::codeview::TypeIndex::simpleTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a>.</p>


<p>Referenced by <a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a>, <a href="#ae9aeda1f1736cdf67f11ea6f1c99b107">visitKnownMember</a>, <a href="#a37c4e4e6831c8f3f7304cdaf11060b0f">visitKnownMember</a>, <a href="#ac72c1663cfda32b4cb722e815b1ea005">visitKnownRecord</a>, <a href="#a37e81e85684fa7bde4a91f870f4c44b8">visitKnownRecord</a>, <a href="#a9ca019e8fbb127c461eba43cb4649642">visitKnownRecord</a>, <a href="#afaa27f4570b743eb19adf1278056c387">visitKnownRecord</a>, <a href="#adbd431dc7da0c6db4b9987a3b85e4876">visitKnownRecord</a>, <a href="#ac6549e77fe8b0654042aa48cc785d3e7">visitKnownRecord</a> and <a href="#a47a421cf2ef2fc76b72f322783bfd9e3">visitKnownRecord</a>.</p>

</div>
</div>

### getReaderScope() {#ae557894f894c777fc261ff1244d91237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScope * llvm::logicalview::LVLogicalVisitor::getReaderScope ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### getShared() {#ac00415fcfc3c32dbdaff086663d0eb16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVShared * llvm::logicalview::LVLogicalVisitor::getShared ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### inlineSiteAnnotation() {#a68da2ce647c44cc62f321e770312a1ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::inlineSiteAnnotation (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * AbstractFunction, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * InlinedFunction, <a href="/web-llvm/docs/api/classes/llvm/codeview/inlinesitesym">InlineSiteSym</a> &amp; InlineSite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3420 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a889734f0b7842a441eda2b37b6b4c19c">llvm::logicalview::LVScope::addObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372a9247192b52c418519a5f4cc82d460ffb">llvm::codeview::ChangeCodeLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372a2a4e54e04bc1ace4e001b9bfa8d5745b">llvm::codeview::ChangeCodeLengthAndCodeOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372ac8d46e9b8b90465f265a773672338e70">llvm::codeview::ChangeCodeOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372afd958fe410ae43d1681f8802c0ec60c9">llvm::codeview::ChangeCodeOffsetAndLineOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372a235411def9e0c5f5a4bad7f98275eb48">llvm::codeview::ChangeFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372a8bb0c4a1dc3752b8f6edaea47d1bdb22">llvm::codeview::ChangeLineOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0883f644d58e1e0e4624e4773b4fc372adaac3f86343855d64fea7cde051faa79">llvm::codeview::CodeOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa1351017ac6423911223bc19a8cb7c653">llvm::logicalview::Filename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac071e70044138f6b9a2568a4bac82352">llvm::fmt_align</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#a201df3ca3db5a4cfc5dbf5e4cd5001fd">llvm::logicalview::LVObject::getParentScope</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#aca4ac52f5fdc8ecab2c7bf0fceb753f6">llvm::logicalview::LVScope::getRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa55754bcb413b06333e15211f66f05353">llvm::codeview::InlineeLines</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a945d5e233cf7d6240f6b783b36a374ff">llvm::Left</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a8d4dd8d1ec9d9328d03bb2b99aa74744aeebd338ddbd547e41e4a1296de82963a">llvm::logicalview::Locations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefadfd0a82c4bf37b1e90b690a22a20692e">llvm::logicalview::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ae1058ebf1112641a607a4466101f3910">llvm::logicalview::LVObject::setLineNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abec19670f96ed423c2e4d4f10a4c6975">llvm::toHex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3beda524b0772ca36035db4399a6a571">llvm::utohexstr</a>.</p>

</div>
</div>

### popScope() {#a55f3c4beadc37f6026e6e3d048afe3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::popScope ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>Referenced by <a href="#adaaffda56ec54951484eed174154c4f8">addElement</a> and <a href="#a389be388f2f65fd0647e21ed64263394">closeScope</a>.</p>

</div>
</div>

### printMemberAttributes() {#a5983caf504578aa578a6cc4e494333ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::printMemberAttributes (<a href="/web-llvm/docs/api/structs/llvm/codeview/memberattributes">MemberAttributes</a> Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### printMemberAttributes() {#a3ee48c8b3820d7921735c05689074899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::printMemberAttributes (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a86888a0082bafa16b982170695ebb881">MemberAccess</a> Access, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a> Kind, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626f">MethodOptions</a> Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#adb4fa2b9065093d32736f78ea43a8c8a">Access</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### printMemberBegin() {#aedd64107ac11a6fb26ac504794620a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::printMemberBegin (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element, uint32_t StreamIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1762 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a7d5e1069198fc42ca3def0ecb7134ca2">llvm::pdb::formatTypeLeafKind</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#abf33a9b90a30d17ecb3c53b2920cc5b1">llvm::codeview::TypeIndex::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ad2140967118b77a7ba7115ac2ba743ca">llvm::logicalview::LVObject::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#aafc55a5fae9ebe734aa0ef8ba8934e72">llvm::logicalview::LeafTypeNames</a> and <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>.</p>


<p>Referenced by <a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a>, <a href="#aa300b4d35c32e9fbd142578c447a556f">visitKnownMember</a>, <a href="#a6ddf6a3be3f9d8629ad887d3125ce0bb">visitKnownMember</a>, <a href="#af3229086e49b76d1dbdc7bd0e6300737">visitKnownMember</a>, <a href="#ae9aeda1f1736cdf67f11ea6f1c99b107">visitKnownMember</a>, <a href="#a9efe423cacffbe87239e1e0f556d6d86">visitKnownMember</a>, <a href="#a9d03e43695c8f8371c9c1fe4a6519ae6">visitKnownMember</a>, <a href="#ad006d3e6801c21a539ffc8b32d91a17d">visitKnownMember</a>, <a href="#a6ee2ae8a2caff14a0928ded0348efd8c">visitKnownMember</a> and <a href="#a37c4e4e6831c8f3f7304cdaf11060b0f">visitKnownMember</a>.</p>

</div>
</div>

### printMemberEnd() {#a47be875e6cb8de5b0f948dd745271342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::printMemberEnd (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1776 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>Referenced by <a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a>, <a href="#aa300b4d35c32e9fbd142578c447a556f">visitKnownMember</a>, <a href="#a6ddf6a3be3f9d8629ad887d3125ce0bb">visitKnownMember</a>, <a href="#af3229086e49b76d1dbdc7bd0e6300737">visitKnownMember</a>, <a href="#ae9aeda1f1736cdf67f11ea6f1c99b107">visitKnownMember</a>, <a href="#a9efe423cacffbe87239e1e0f556d6d86">visitKnownMember</a>, <a href="#a9d03e43695c8f8371c9c1fe4a6519ae6">visitKnownMember</a>, <a href="#ad006d3e6801c21a539ffc8b32d91a17d">visitKnownMember</a>, <a href="#a6ee2ae8a2caff14a0928ded0348efd8c">visitKnownMember</a> and <a href="#a37c4e4e6831c8f3f7304cdaf11060b0f">visitKnownMember</a>.</p>

</div>
</div>

### printRecords() {#a03d93ef611f1c51f7fa6da9281d2845a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::printRecords (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3390 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a7d5e1069198fc42ca3def0ecb7134ca2">llvm::pdb::formatTypeLeafKind</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#ab9157acbaccd4abe39c0aa7c46e9b496">llvm::logicalview::LVCodeViewReader::getSymbolKindName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>.</p>

</div>
</div>

### printTypeBegin() {#adfc7ea7e7d25bf908bb338d6c6c26040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::printTypeBegin (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element, uint32_t StreamIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1744 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a7d5e1069198fc42ca3def0ecb7134ca2">llvm::pdb::formatTypeLeafKind</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#abf33a9b90a30d17ecb3c53b2920cc5b1">llvm::codeview::TypeIndex::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ad2140967118b77a7ba7115ac2ba743ca">llvm::logicalview::LVObject::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#aafc55a5fae9ebe734aa0ef8ba8934e72">llvm::logicalview::LeafTypeNames</a> and <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>.</p>


<p>Referenced by <a href="#a0015ff019ddc43f0e4840febaf74664d">visitKnownRecord</a>, <a href="#ac72c1663cfda32b4cb722e815b1ea005">visitKnownRecord</a>, <a href="#a37e81e85684fa7bde4a91f870f4c44b8">visitKnownRecord</a>, <a href="#ab7d42ec1825f9e56033a386b52d39337">visitKnownRecord</a>, <a href="#ade7088de2025cc1850af4e51e17c9255">visitKnownRecord</a>, <a href="#a8d47724a657b7c47da03316e855b9b48">visitKnownRecord</a>, <a href="#a9ca019e8fbb127c461eba43cb4649642">visitKnownRecord</a>, <a href="#a7f4808cdf082e92e24c882c5a00a0c93">visitKnownRecord</a>, <a href="#aef3473440a5ef85d0c44e95308f22a77">visitKnownRecord</a>, <a href="#acdb64629acda1a991247ba4c049c60c4">visitKnownRecord</a>, <a href="#a0d54e1dd5acde5b32e990f461bc2daa2">visitKnownRecord</a>, <a href="#afaa27f4570b743eb19adf1278056c387">visitKnownRecord</a>, <a href="#ac28d415acf28987bc11560889b9e76b1">visitKnownRecord</a>, <a href="#adbd431dc7da0c6db4b9987a3b85e4876">visitKnownRecord</a>, <a href="#ac6549e77fe8b0654042aa48cc785d3e7">visitKnownRecord</a>, <a href="#adb7f7308a370b9bb952aebfa8c04d585">visitKnownRecord</a>, <a href="#a47a421cf2ef2fc76b72f322783bfd9e3">visitKnownRecord</a>, <a href="#a9ec578dadc7c4409612fdaf21e83dcec">visitKnownRecord</a>, <a href="#a978c30bae82893422130ec3bf98a56ce">visitKnownRecord</a>, <a href="#afe0bd76d0a524ced56b7dd7e10451ee8">visitKnownRecord</a>, <a href="#a20ff4db3e31aae1d9b6ce04ad03c421d">visitKnownRecord</a>, <a href="#a0f7b86f4b3c852f56ca5abb71840a4d6">visitKnownRecord</a> and <a href="#ac1c5ef69da66ecc0e7a63e74252cbffe">visitKnownRecord</a>.</p>

</div>
</div>

### printTypeEnd() {#a19922b17910cfc07362dd1e721732a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::printTypeEnd (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1757 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>Referenced by <a href="#a0015ff019ddc43f0e4840febaf74664d">visitKnownRecord</a>, <a href="#ac72c1663cfda32b4cb722e815b1ea005">visitKnownRecord</a>, <a href="#a37e81e85684fa7bde4a91f870f4c44b8">visitKnownRecord</a>, <a href="#ab7d42ec1825f9e56033a386b52d39337">visitKnownRecord</a>, <a href="#ade7088de2025cc1850af4e51e17c9255">visitKnownRecord</a>, <a href="#a8d47724a657b7c47da03316e855b9b48">visitKnownRecord</a>, <a href="#a9ca019e8fbb127c461eba43cb4649642">visitKnownRecord</a>, <a href="#a7f4808cdf082e92e24c882c5a00a0c93">visitKnownRecord</a>, <a href="#aef3473440a5ef85d0c44e95308f22a77">visitKnownRecord</a>, <a href="#acdb64629acda1a991247ba4c049c60c4">visitKnownRecord</a>, <a href="#a0d54e1dd5acde5b32e990f461bc2daa2">visitKnownRecord</a>, <a href="#afaa27f4570b743eb19adf1278056c387">visitKnownRecord</a>, <a href="#ac28d415acf28987bc11560889b9e76b1">visitKnownRecord</a>, <a href="#adbd431dc7da0c6db4b9987a3b85e4876">visitKnownRecord</a>, <a href="#ac6549e77fe8b0654042aa48cc785d3e7">visitKnownRecord</a>, <a href="#adb7f7308a370b9bb952aebfa8c04d585">visitKnownRecord</a>, <a href="#a47a421cf2ef2fc76b72f322783bfd9e3">visitKnownRecord</a>, <a href="#a9ec578dadc7c4409612fdaf21e83dcec">visitKnownRecord</a>, <a href="#a978c30bae82893422130ec3bf98a56ce">visitKnownRecord</a>, <a href="#afe0bd76d0a524ced56b7dd7e10451ee8">visitKnownRecord</a>, <a href="#a20ff4db3e31aae1d9b6ce04ad03c421d">visitKnownRecord</a>, <a href="#a0f7b86f4b3c852f56ca5abb71840a4d6">visitKnownRecord</a> and <a href="#ac1c5ef69da66ecc0e7a63e74252cbffe">visitKnownRecord</a>.</p>

</div>
</div>

### printTypeIndex() {#a832f233d86928be8e40e916d9565c05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::printTypeIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, uint32_t StreamIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1738 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aff82033771977413104f16ed617d2b4f">llvm::codeview::printTypeIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>.</p>


<p>Referenced by <a href="#a6dea375bf5f6ee24e99884e5d5d91944">createElement</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#ae19100bf53254a287d0812a18cf3a6b9">processLines</a>, <a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a>, <a href="#aa300b4d35c32e9fbd142578c447a556f">visitKnownMember</a>, <a href="#af3229086e49b76d1dbdc7bd0e6300737">visitKnownMember</a>, <a href="#ae9aeda1f1736cdf67f11ea6f1c99b107">visitKnownMember</a>, <a href="#a9efe423cacffbe87239e1e0f556d6d86">visitKnownMember</a>, <a href="#a9d03e43695c8f8371c9c1fe4a6519ae6">visitKnownMember</a>, <a href="#ad006d3e6801c21a539ffc8b32d91a17d">visitKnownMember</a>, <a href="#a6ee2ae8a2caff14a0928ded0348efd8c">visitKnownMember</a>, <a href="#a37c4e4e6831c8f3f7304cdaf11060b0f">visitKnownMember</a>, <a href="#a0015ff019ddc43f0e4840febaf74664d">visitKnownRecord</a>, <a href="#ac72c1663cfda32b4cb722e815b1ea005">visitKnownRecord</a>, <a href="#a37e81e85684fa7bde4a91f870f4c44b8">visitKnownRecord</a>, <a href="#ab7d42ec1825f9e56033a386b52d39337">visitKnownRecord</a>, <a href="#ade7088de2025cc1850af4e51e17c9255">visitKnownRecord</a>, <a href="#a9ca019e8fbb127c461eba43cb4649642">visitKnownRecord</a>, <a href="#aef3473440a5ef85d0c44e95308f22a77">visitKnownRecord</a>, <a href="#a0d54e1dd5acde5b32e990f461bc2daa2">visitKnownRecord</a>, <a href="#afaa27f4570b743eb19adf1278056c387">visitKnownRecord</a>, <a href="#adbd431dc7da0c6db4b9987a3b85e4876">visitKnownRecord</a>, <a href="#ac6549e77fe8b0654042aa48cc785d3e7">visitKnownRecord</a>, <a href="#a47a421cf2ef2fc76b72f322783bfd9e3">visitKnownRecord</a>, <a href="#a3f8a4731c6b598189e6503052d277cf5">visitKnownRecord</a>, <a href="#a9ec578dadc7c4409612fdaf21e83dcec">visitKnownRecord</a>, <a href="#afe0bd76d0a524ced56b7dd7e10451ee8">visitKnownRecord</a>, <a href="#ab2bde320a72ca54870bb93585991de89">visitKnownRecord</a>, <a href="#a20ff4db3e31aae1d9b6ce04ad03c421d">visitKnownRecord</a>, <a href="#a0f7b86f4b3c852f56ca5abb71840a4d6">visitKnownRecord</a> and <a href="#aa583f2e4b792c5eadd2aecc04e1c2361">visitUnknownType</a>.</p>

</div>
</div>

### processFiles() {#afa90811e29ceaa8c0d237d9fb2049e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::processFiles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3388 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### processLines() {#ae19100bf53254a287d0812a18cf3a6b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::processLines ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3354 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#abf34282e6a33e21a45fee038b6dd4b2c">llvm::logicalview::LVElement::setFilenameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ae1058ebf1112641a607a4466101f3910">llvm::logicalview::LVObject::setLineNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caf1c5192a50efac0a24a738de0948f60f">llvm::pdb::StreamIPI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>.</p>

</div>
</div>

### processNamespaces() {#aa6fd9f274d063ce78752881806051307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::processNamespaces ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3383 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### pushScope() {#aa4c1887e97daffa480031c432a34c894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::pushScope (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>Referenced by <a href="#adaaffda56ec54951484eed174154c4f8">addElement</a>.</p>

</div>
</div>

### setCompileUnitName() {#a529099998163a45fe5679ffae51efcf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::setCompileUnitName (std::string Name)</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

### setInput() {#ad78145049dd341346af2472c711b58f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::setInput (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile">llvm::pdb::InputFile</a> &gt; TypeServer)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### setInput() {#a9fdec980e4ef3a393d4070c1ab0eb608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::setInput (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> &gt; PrecompHeader)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### setRoot() {#a96cebf83499ed175093feaf6a11faa7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::setRoot (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Root)</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### startProcessArgumentList() {#ab787867fd9b82c943b4a971511ee78cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::startProcessArgumentList ()</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### stopProcessArgumentList() {#a0d3139101d2e070d14668cd975a6158b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVLogicalVisitor::stopProcessArgumentList ()</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### visitKnownMember() {#a3cf4854b9700e7d9f6fa045c28c536a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/baseclassrecord">BaseClassRecord</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2632 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#adaaffda56ec54951484eed174154c4f8">addElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa095a1b43effec73955e31e790438de49">llvm::logicalview::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba45b3e4c35409fb597ea598dc4b984b8c">llvm::pdb::BaseClass</a>, <a href="#af691af071aabd478296d790bd536104c">createElement</a>, <a href="#a5713cbf681b40f62f591788ae9ab0c84">CurrentSymbol</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#aa4681071bf84200dace5251305a67a1c">visitKnownMember</a> and <a href="#ac28d415acf28987bc11560889b9e76b1">visitKnownRecord</a>.</p>

</div>
</div>

### visitKnownMember() {#aa300b4d35c32e9fbd142578c447a556f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/datamemberrecord">DataMemberRecord</a> &amp; Field, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2655 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownMember() {#a6ddf6a3be3f9d8629ad887d3125ce0bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumeratorrecord">EnumeratorRecord</a> &amp; Enum, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2673 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#adaaffda56ec54951484eed174154c4f8">addElement</a>, <a href="#af691af071aabd478296d790bd536104c">createElement</a>, <a href="#a6605ba61712bd6a951ee6df2c2a5d85a">CurrentType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bacf20423ed48998082c20099488a0917c">llvm::pdb::Enum</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownMember() {#af3229086e49b76d1dbdc7bd0e6300737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/listcontinuationrecord">ListContinuationRecord</a> &amp; Cont, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2696 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/listcontinuationrecord/#a9f54276ecf56c0f9226894225b479fac">llvm::codeview::ListContinuationRecord::getContinuationIndex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownMember() {#ae9aeda1f1736cdf67f11ea6f1c99b107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/nestedtyperecord">NestedTypeRecord</a> &amp; Nested, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2708 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a08415ad3aca5fdf4f53418cea4a06ff4">llvm::logicalview::LVScope::addElement</a>, <a href="#af691af071aabd478296d790bd536104c">createElement</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a957f4d1425cced530d8488b4bbeaa425">llvm::logicalview::getInnerComponent</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a63a780627da7c5b7088ebaf5bd7408aa">llvm::logicalview::getRecordName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa13c479c348969ab459513a4bfd559bb9">llvm::codeview::Nested</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba5fede51b97a819dedf4f83bc2aacbc6a">llvm::pdb::Typedef</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a45e15187fdda4ce7c9089efc869db3c4">llvm::logicalview::LVElement::updateLevel</a>.</p>

</div>
</div>

### visitKnownMember() {#a9efe423cacffbe87239e1e0f556d6d86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord">OneMethodRecord</a> &amp; Method, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2753 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#adaaffda56ec54951484eed174154c4f8">addElement</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#ae64e42551b20dd850923628e968c61b2">llvm::codeview::OneMethodRecord::Attrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626fa8815388be62c71a9521910cfde9bef4f">llvm::codeview::CompilerGenerated</a>, <a href="#af691af071aabd478296d790bd536104c">createElement</a>, <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#a99cb8d9d0bb2afa112ef8d4239eb2f1e">llvm::codeview::OneMethodRecord::getAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/memberattributes/#acca80fa19086015b7bf9f1f14ba2010b">llvm::codeview::MemberAttributes::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#ac5995cb258a5e2e48cbd88eb9d55c248">llvm::codeview::OneMethodRecord::getMethodKind</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#ad90ae94cd1ece9ed03e400d768d001f9">llvm::codeview::OneMethodRecord::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#a41620ed344dcf14ecf5e645376ba5c32">llvm::codeview::OneMethodRecord::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#a0fe5da86460c13bb2dce221d7abaf065">llvm::codeview::OneMethodRecord::getVFTableOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#a66952c25fab42f836c97333715a36239">llvm::codeview::OneMethodRecord::isIntroducingVirtual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a7acb49478601af95b4023b911a973ecf">llvm::logicalview::LVElement::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7a84a8921b25f505d0d2077aeb5db4bc16">llvm::codeview::Static</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a>.</p>

</div>
</div>

### visitKnownMember() {#a9d03e43695c8f8371c9c1fe4a6519ae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/overloadedmethodrecord">OverloadedMethodRecord</a> &amp; Method, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2799 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/overloadedmethodrecord/#aaaebe31e1f514f2e7fd32cea86c331b3">llvm::codeview::OverloadedMethodRecord::getMethodList</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/overloadedmethodrecord/#a708a8c842f336c4fa4011380e2ab7f9e">llvm::codeview::OverloadedMethodRecord::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/overloadedmethodrecord/#a878ea824cfb5ac936a4eee8ac2800f3a">llvm::codeview::OverloadedMethodRecord::getNumOverloads</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a>.</p>

</div>
</div>

### visitKnownMember() {#ad006d3e6801c21a539ffc8b32d91a17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/staticdatamemberrecord">StaticDataMemberRecord</a> &amp; Field, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2822 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownMember() {#a6ee2ae8a2caff14a0928ded0348efd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/vfptrrecord">VFPtrRecord</a> &amp; VFTable, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2839 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/vfptrrecord/#ac13fca46f6f274bc62d04955af371770">llvm::codeview::VFPtrRecord::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownMember() {#a37c4e4e6831c8f3f7304cdaf11060b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/virtualbaseclassrecord">VirtualBaseClassRecord</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2851 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#adaaffda56ec54951484eed174154c4f8">addElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa095a1b43effec73955e31e790438de49">llvm::logicalview::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba45b3e4c35409fb597ea598dc4b984b8c">llvm::pdb::BaseClass</a>, <a href="#af691af071aabd478296d790bd536104c">createElement</a>, <a href="#a5713cbf681b40f62f591788ae9ab0c84">CurrentSymbol</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aedd64107ac11a6fb26ac504794620a05">printMemberBegin</a>, <a href="#a47be875e6cb8de5b0f948dd745271342">printMemberEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7a615e6f9baca5553d44683a098d342b70">llvm::codeview::Virtual</a>.</p>

</div>
</div>

### visitKnownMember() {#aa4681071bf84200dace5251305a67a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::logicalview::LVLogicalVisitor::visitKnownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks">TypeVisitorCallbacks</a> &amp; Callbacks, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a>.</p>

</div>
</div>

### visitKnownRecord() {#a0015ff019ddc43f0e4840febaf74664d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/arglistrecord">ArgListRecord</a> &amp; Args, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1790 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a1161e5a4e753384aaba3a8e4533c4261">Arguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#af11c2a836925d0e70268cb478d829473">visitKnownRecord</a>.</p>

</div>
</div>

### visitKnownRecord() {#ac72c1663cfda32b4cb722e815b1ea005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/arrayrecord">ArrayRecord</a> &amp; AT, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1813 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a4e133ab5dd57656a742661a1ad58ac3b">llvm::logicalview::LVElement::getCount</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/arrayrecord/#a86d8676a2f169fe3f57e3c627ae4c7db">llvm::codeview::ArrayRecord::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#abf33a9b90a30d17ecb3c53b2920cc5b1">llvm::codeview::TypeIndex::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/arrayrecord/#ace9eb92135c2c439d09d5539cf485d91">llvm::codeview::ArrayRecord::getIndexType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aeeee24e4951098e13042b484886d47bb">llvm::codeview::getModifiedType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/arrayrecord/#afd37e14ae1301a44d9005cbef0ce8256">llvm::codeview::ArrayRecord::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a0cff1590886f995eeef57d0d4b9e0fda">llvm::codeview::TypeIndex::getSimpleKind</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/arrayrecord/#ad8f61ea1d5c34f590c59c92326c44c72">llvm::codeview::ArrayRecord::getSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aecc3f01151200b7e67533ed9a8682b71">llvm::codeview::getSizeInBytesForTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac4a2f1866a17117b240fe173fae7699b">llvm::codeview::getSizeInBytesForTypeRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a22875bd8ea1a66c0b019ac7de3a847b0">llvm::logicalview::getTrueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aa59cca6142d1e491d779bd3f0b7436dc">llvm::codeview::isAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a405aadbe59614b6be8cfbcd0f3b4ac2a">llvm::codeview::TypeIndex::isSimple</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#aaeef9f2a2d0dc09ec00ec9b38242c706">llvm::codeview::CVRecord&lt; Kind &gt;::kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a0b64317e22e40d30ff720b0548be353a">llvm::logicalview::LVElement::setCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa8af5251a7b1117bd3b09f7cd75361f67">llvm::logicalview::Subrange</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a>.</p>

</div>
</div>

### visitKnownRecord() {#a37e81e85684fa7bde4a91f870f4c44b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/bitfieldrecord">BitFieldRecord</a> &amp; BF, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1931 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/bitfieldrecord/#adaf25ae737006658867aae8757286377">llvm::codeview::BitFieldRecord::getBitOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/bitfieldrecord/#a6c25596d85f1523791c14617e49a9353">llvm::codeview::BitFieldRecord::getBitSize</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/bitfieldrecord/#ac1a0d54118fa976b9f587842b6ee7ffc">llvm::codeview::BitFieldRecord::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a352f964e44d4756105476720498d6f02">llvm::logicalview::LVElement::setBitSize</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aac48d6fa0f7c1727388feb115620d50e">llvm::logicalview::LVElement::setType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#ab7d42ec1825f9e56033a386b52d39337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/buildinforecord">BuildInfoRecord</a> &amp; BI, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1947 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a1161e5a4e753384aaba3a8e4533c4261">Arguments</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/buildinforecord/#ae9fc1e07fb2c81925a1083cda84ca5c6">llvm::codeview::BuildInfoRecord::getArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac1b702e99f1978f2dd36cac2f7400f">llvm::getTypeName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a7acb49478601af95b4023b911a973ecf">llvm::logicalview::LVElement::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/buildinforecord/#a9cb5a0aa939df62682746f85bbea6f4ba5131cae258edfc120a1fe3e425c10a3a">llvm::codeview::BuildInfoRecord::SourceFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caf1c5192a50efac0a24a738de0948f60f">llvm::pdb::StreamIPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#ade7088de2025cc1850af4e51e17c9255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord">ClassRecord</a> &amp; Class, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1971 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85a9bd81329febf6efe22788e03ddeaf0af">llvm::pdb::Class</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/tagrecord/#a6ce7692f6399c7ea2cdd3d84af0c912d">llvm::codeview::TagRecord::getFieldList</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#acb1db28679177b959c08481c98cafa29">llvm::codeview::TypeIndex::isNoneType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#aaeef9f2a2d0dc09ec00ec9b38242c706">llvm::codeview::CVRecord&lt; Kind &gt;::kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a>.</p>

</div>
</div>

### visitKnownRecord() {#a9ca019e8fbb127c461eba43cb4649642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord">EnumRecord</a> &amp; Enum, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2041 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bacf20423ed48998082c20099488a0917c">llvm::pdb::Enum</a>, <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#acb1db28679177b959c08481c98cafa29">llvm::codeview::TypeIndex::isNoneType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a>.</p>

</div>
</div>

### visitKnownRecord() {#a7f4808cdf082e92e24c882c5a00a0c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/fieldlistrecord">FieldListRecord</a> &amp; FieldList, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2098 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a856d291d3b47f25806d62863137976a2aa1017051aa12b8176e548f2752a73693">llvm::codeview::FieldList</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#aef3473440a5ef85d0c44e95308f22a77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/funcidrecord">FuncIdRecord</a> &amp; Func, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2113 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#acb1db28679177b959c08481c98cafa29">llvm::codeview::TypeIndex::isNoneType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caf1c5192a50efac0a24a738de0948f60f">llvm::pdb::StreamIPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a>.</p>

</div>
</div>

### visitKnownRecord() {#acdb64629acda1a991247ba4c049c60c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/labelrecord">LabelRecord</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2158 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#adbd431dc7da0c6db4b9987a3b85e4876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/modifierrecord">ModifierRecord</a> &amp; Mod, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2266 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a79ceee9f8e3c1f0cc74223e05d2448bf">llvm::codeview::Const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ace1aa05c7223128f172b16dd05dafa07">llvm::dwarf::DW_TAG_unaligned</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#a201df3ca3db5a4cfc5dbf5e4cd5001fd">llvm::logicalview::LVObject::getParentScope</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a7acb49478601af95b4023b911a973ecf">llvm::logicalview::LVElement::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ae4cf505e0bb9d8ef6c42dacfb7c4450e">llvm::logicalview::LVObject::setTag</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aac48d6fa0f7c1727388feb115620d50e">llvm::logicalview::LVElement::setType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a9f19679888db198f8dd45606487e6cd6">llvm::codeview::Unaligned</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a3e3af98b6b48c7e593d8d18863e3333b">llvm::codeview::Volatile</a>.</p>

</div>
</div>

### visitKnownRecord() {#a0d54e1dd5acde5b32e990f461bc2daa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberfuncidrecord">MemberFuncIdRecord</a> &amp; Id, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2168 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85a9bd81329febf6efe22788e03ddeaf0af">llvm::pdb::Class</a>, <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caf1c5192a50efac0a24a738de0948f60f">llvm::pdb::StreamIPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#afaa27f4570b743eb19adf1278056c387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberfunctionrecord">MemberFunctionRecord</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2199 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85a9bd81329febf6efe22788e03ddeaf0af">llvm::pdb::Class</a>, <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberfunctionrecord/#a1e26ad63f29ee7fed6196cdfa372bb85">llvm::codeview::MemberFunctionRecord::getArgumentList</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberfunctionrecord/#ae2470b5992cef24b8bb224cc193c9273">llvm::codeview::MemberFunctionRecord::getClassType</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#abf33a9b90a30d17ecb3c53b2920cc5b1">llvm::codeview::TypeIndex::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberfunctionrecord/#a6bcc704320991e4eccbb1a4afac46f6f">llvm::codeview::MemberFunctionRecord::getParameterCount</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberfunctionrecord/#a1159087bde2119e229b2f0f42cacb73b">llvm::codeview::MemberFunctionRecord::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberfunctionrecord/#a1788a42e4d884efe4daa3df9623962f3">llvm::codeview::MemberFunctionRecord::getThisPointerAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberfunctionrecord/#ac6d9bc1eda56ed332305b188e0f46085">llvm::codeview::MemberFunctionRecord::getThisType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aac48d6fa0f7c1727388feb115620d50e">llvm::logicalview::LVElement::setType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a7c84cffd04a037f3e087b309bf176929a77631ca4f0e08419b70726a447333ab6">llvm::codeview::This</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a>.</p>

</div>
</div>

### visitKnownRecord() {#ac28d415acf28987bc11560889b9e76b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/methodoverloadlistrecord">MethodOverloadListRecord</a> &amp; Overloads, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2246 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/methodoverloadlistrecord/#a1b55b7ba490a7e583dd7f874bc3f6a37">llvm::codeview::MethodOverloadListRecord::Methods</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#a442a2d9e12e944cb483f3a6435b84cb0">llvm::codeview::OneMethodRecord::Name</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a>.</p>

</div>
</div>

### visitKnownRecord() {#ac6549e77fe8b0654042aa48cc785d3e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/pointerrecord">PointerRecord</a> &amp; Ptr, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2327 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#a201df3ca3db5a4cfc5dbf5e4cd5001fd">llvm::logicalview::LVObject::getParentScope</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbca3408011d07d71eb98afa178eae72faf6">llvm::codeview::LValueReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbca61cf8510205077b6f5491d38cd44c0f7">llvm::codeview::Pointer</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa034d70b46e41ec9d0306b0001e04cae7">llvm::codeview::Restrict</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbcaa68a3262ced5b445f2a5a1953c279116">llvm::codeview::RValueReference</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a7acb49478601af95b4023b911a973ecf">llvm::logicalview::LVElement::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ae4cf505e0bb9d8ef6c42dacfb7c4450e">llvm::logicalview::LVObject::setTag</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aac48d6fa0f7c1727388feb115620d50e">llvm::logicalview::LVElement::setType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a47a421cf2ef2fc76b72f322783bfd9e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/procedurerecord">ProcedureRecord</a> &amp; Proc, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2410 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/procedurerecord/#a424555b9c20828cab5d1bed26e331024">llvm::codeview::ProcedureRecord::getArgumentList</a>, <a href="#ae4da1612e3cab687247782f44c2807d9">getElement</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/procedurerecord/#a445450f43dd40124fdc72b452a4e52ee">llvm::codeview::ProcedureRecord::getParameterCount</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/procedurerecord/#a3f84e13f2f0a382bc36e86886bdf28eb">llvm::codeview::ProcedureRecord::getReturnType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a>.</p>

</div>
</div>

### visitKnownRecord() {#a20ff4db3e31aae1d9b6ce04ad03c421d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord">UnionRecord</a> &amp; Union, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2441 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a90c9f20715929cbe06c523bf8546c38baf2d346b1bb7c1c85ab6f7f21e3666b9f">llvm::logicalview::Types</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85aaef12e903e606a4895a16b393bfdec8c">llvm::pdb::Union</a>.</p>

</div>
</div>

### visitKnownRecord() {#a978c30bae82893422130ec3bf98a56ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeserver2record">TypeServer2Record</a> &amp; TS, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2488 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeserver2record/#ae004212d8b7dc6d67cf6e65f3ca8005f">llvm::codeview::TypeServer2Record::getAge</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeserver2record/#a9da83e85a1940c44ddc76b858846c790">llvm::codeview::TypeServer2Record::getGuid</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeserver2record/#a76283f64f8e26bc0e415b0922f3a3837">llvm::codeview::TypeServer2Record::getName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a0f7b86f4b3c852f56ca5abb71840a4d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/vftablerecord">VFTableRecord</a> &amp; VFT, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2501 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/vftablerecord/#acd5edd112d1ef062114c9fd52b2c4b5e">llvm::codeview::VFTableRecord::getCompleteClass</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/vftablerecord/#a7a11bb08cab741bb48d5faee0bee58a6">llvm::codeview::VFTableRecord::getMethodNames</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/vftablerecord/#aaf72b9fe672ccad7a9cbe3525203db09">llvm::codeview::VFTableRecord::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/vftablerecord/#a778ae15024f7c2a7f326648c0836feac">llvm::codeview::VFTableRecord::getOverriddenVTable</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/vftablerecord/#a1ab584b51b8823c7bbae14e8f58152aa">llvm::codeview::VFTableRecord::getVFPtrOffset</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#ac1c5ef69da66ecc0e7a63e74252cbffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/vftableshaperecord">VFTableShapeRecord</a> &amp; Shape, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2517 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/vftableshaperecord/#ae4b38070fd44d5456121745954d85e47">llvm::codeview::VFTableShapeRecord::getEntryCount</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a9ec578dadc7c4409612fdaf21e83dcec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/stringlistrecord">StringListRecord</a> &amp; Strings, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2529 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a1161e5a4e753384aaba3a8e4533c4261">Arguments</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/stringlistrecord/#aefdbf7c6d49492f2eb9181b4c48f2cc1">llvm::codeview::StringListRecord::getIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caf1c5192a50efac0a24a738de0948f60f">llvm::pdb::StreamIPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a3f8a4731c6b598189e6503052d277cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/stringidrecord">StringIdRecord</a> &amp; String, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2547 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#a201df3ca3db5a4cfc5dbf5e4cd5001fd">llvm::logicalview::LVObject::getParentScope</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caf1c5192a50efac0a24a738de0948f60f">llvm::pdb::StreamIPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#ab2bde320a72ca54870bb93585991de89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/udtsourcelinerecord">UdtSourceLineRecord</a> &amp; SourceLine, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2569 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/udtsourcelinerecord/#a5a35178249562327342e20a9e3ce48a5">llvm::codeview::UdtSourceLineRecord::getLineNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/udtsourcelinerecord/#ac64d8f32826d757d0dd367ab975f830c">llvm::codeview::UdtSourceLineRecord::getSourceFile</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/udtsourcelinerecord/#a94035a2c4bde8d48d2be2fc35bce4f19">llvm::codeview::UdtSourceLineRecord::getUDT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caf1c5192a50efac0a24a738de0948f60f">llvm::pdb::StreamIPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#afe0bd76d0a524ced56b7dd7e10451ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/udtmodsourcelinerecord">UdtModSourceLineRecord</a> &amp; ModSourceLine, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2583 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/udtmodsourcelinerecord/#a7ee930c5157bacfc9a43eadf5347cac6">llvm::codeview::UdtModSourceLineRecord::getLineNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/udtmodsourcelinerecord/#a77c8747e8166c53992d33c0fe84be564">llvm::codeview::UdtModSourceLineRecord::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/udtmodsourcelinerecord/#a3523e18699d937436a2170e2eaa02082">llvm::codeview::UdtModSourceLineRecord::getSourceFile</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/udtmodsourcelinerecord/#acaa4c1e2382e74bc1aacab74d161c8e7">llvm::codeview::UdtModSourceLineRecord::getUDT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caf1c5192a50efac0a24a738de0948f60f">llvm::pdb::StreamIPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#adb7f7308a370b9bb952aebfa8c04d585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/precomprecord">PrecompRecord</a> &amp; Precomp, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2600 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/precomprecord/#a91ed5867a587595b07991d55c3a05733">llvm::codeview::PrecompRecord::getPrecompFilePath</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/precomprecord/#a28d5bd2abb27cd914e88d309c7f11757">llvm::codeview::PrecompRecord::getSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/precomprecord/#ad510a4c51f1880c187fb606e14734ad3">llvm::codeview::PrecompRecord::getStartTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/precomprecord/#a95f2bb58f2785700d0aa3d8407773885">llvm::codeview::PrecompRecord::getTypesCount</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#a8d47724a657b7c47da03316e855b9b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/endprecomprecord">EndPrecompRecord</a> &amp; EndPrecomp, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2614 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/endprecomprecord/#a677b9987bbe1572b00e4fd1ed0988fc0">llvm::codeview::EndPrecompRecord::getSignature</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adfc7ea7e7d25bf908bb338d6c6c26040">printTypeBegin</a>, <a href="#a19922b17910cfc07362dd1e721732a14">printTypeEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitKnownRecord() {#af11c2a836925d0e70268cb478d829473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::logicalview::LVLogicalVisitor::visitKnownRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a0015ff019ddc43f0e4840febaf74664d">visitKnownRecord</a>.</p>

</div>
</div>

### visitMemberRecord() {#a38aaf9af22e7aebd5e41ddb05c414922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitMemberRecord (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks">TypeVisitorCallbacks</a> &amp; Callbacks, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2876 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#aed7f5f2d36484023b0c6c0d45b911100">llvm::codeview::TypeVisitorCallbacks::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#aabb0d570b56d25c7bd534ad3ac109d19">llvm::codeview::TypeVisitorCallbacks::visitMemberEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#a0a6a92b5ee8fe2bcc2e6c2d0b08b8f10">llvm::codeview::TypeVisitorCallbacks::visitUnknownMember</a>.</p>

</div>
</div>

### visitUnknownMember() {#a92e358bb94c8f56f008ff91345a9092e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitUnknownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2625 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitUnknownType() {#aa583f2e4b792c5eadd2aecc04e1c2361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitUnknownType (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 1781 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a832f233d86928be8e40e916d9565c05e">printTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#aeefe0bd6abc3bfcaa5c237bfa9c13011">finishVisitation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createBaseType() {#a38dbbbf51dacc424037386cba22fdff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVType * LVLogicalVisitor::createBaseType (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3205 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### createDataMember() {#aaa68e6f8040df9211ba25409dae01334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::createDataMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Type, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a86888a0082bafa16b982170695ebb881">MemberAccess</a> Access)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3160 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### createParameter() {#a4361facf4ae0c29135543afc88fcc6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbol * LVLogicalVisitor::createParameter (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3200 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### createParameter() {#a9b6b26c42264ff56ba114259a01f7111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbol * LVLogicalVisitor::createParameter (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3189 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### createParents() {#a24fdef0fa5fe13d01b065cd7abe6de03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVLogicalVisitor::createParents (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ScopedName, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3241 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### createPointerType() {#ac66bb16b301f46019574cd3f290b30a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVType * LVLogicalVisitor::createPointerType (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 3223 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### ids() {#a1d7f4d4241e0bab3dc4c34f376a2b027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection &amp; llvm::logicalview::LVLogicalVisitor::ids ()</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### types() {#ad0207108b6a9915e15f1c51ae130e4fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection &amp; llvm::logicalview::LVLogicalVisitor::types ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### visitFieldListMemberStream() {#af14a3d113f966a63549e9f97536a25e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVLogicalVisitor::visitFieldListMemberStream (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; FieldList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>, definition at line 2931 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurrentElement {#a5958154e459c5a8cc1779af56941d8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement* llvm::logicalview::LVLogicalVisitor::CurrentElement = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### CurrentScope {#a02ecf5656d06b3d2dbe7243e34fd8dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScope* llvm::logicalview::LVLogicalVisitor::CurrentScope = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>Referenced by <a href="#ad1022791b30259f5f02aaf547d52def4">createElement</a> and <a href="#af691af071aabd478296d790bd536104c">createElement</a>.</p>

</div>
</div>

### CurrentSymbol {#a5713cbf681b40f62f591788ae9ab0c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbol* llvm::logicalview::LVLogicalVisitor::CurrentSymbol = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>Referenced by <a href="#ad1022791b30259f5f02aaf547d52def4">createElement</a>, <a href="#af691af071aabd478296d790bd536104c">createElement</a>, <a href="#a3cf4854b9700e7d9f6fa045c28c536a0">visitKnownMember</a> and <a href="#a37c4e4e6831c8f3f7304cdaf11060b0f">visitKnownMember</a>.</p>

</div>
</div>

### CurrentType {#a6605ba61712bd6a951ee6df2c2a5d85a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVType* llvm::logicalview::LVLogicalVisitor::CurrentType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>


<p>Referenced by <a href="#ad1022791b30259f5f02aaf547d52def4">createElement</a>, <a href="#af691af071aabd478296d790bd536104c">createElement</a> and <a href="#a6ddf6a3be3f9d8629ad887d3125ce0bb">visitKnownMember</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CompileUnitName {#a4c36904d390536eb7bba20049f8926f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::logicalview::LVLogicalVisitor::CompileUnitName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### InCompileUnitScope {#a71ce1abefc4cb5ee245dd3bf9df4999d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVLogicalVisitor::InCompileUnitScope = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### InlineeInfo {#a0f22fd8227665da352cf3dacaa5f10fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVInlineeInfo llvm::logicalview::LVLogicalVisitor::InlineeInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### Input {#a6562ad9a00fdf6584854d337aeb280b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::pdb::InputFile&amp; llvm::logicalview::LVLogicalVisitor::Input</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### OverloadedMethodName {#af80dc5247559ca3487cbdba3f02ed0e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::logicalview::LVLogicalVisitor::OverloadedMethodName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### PrecompHeader {#a8002267465e31018956f0bd2a1af7209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;LazyRandomTypeCollection&gt; llvm::logicalview::LVLogicalVisitor::PrecompHeader = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### ProcessArgumentList {#ab1f81f6060cdd1bb6ef90be2ba10cd35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVLogicalVisitor::ProcessArgumentList = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### Reader {#a149ce82e21fc8a2698e6f53327def127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVCodeViewReader* llvm::logicalview::LVLogicalVisitor::Reader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### ReaderParent {#a27f0834be9db31576a1dc5eb97a2bed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScope* llvm::logicalview::LVLogicalVisitor::ReaderParent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### ReaderScope {#a6683a3e1b2aeeb349aefbe217c98dae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScope* llvm::logicalview::LVLogicalVisitor::ReaderScope = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### ScopeStack {#a42d736083d2421c3b42983a9dcfcff24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScopeStack llvm::logicalview::LVLogicalVisitor::ScopeStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### Shared {#a420f6409cf1e46a646bd97c48fc1cb1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;LVShared&gt; llvm::logicalview::LVLogicalVisitor::Shared</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### TypeServer {#a06d064227c6ff5722c1337fbcb00a8fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;llvm::pdb::InputFile&gt; llvm::logicalview::LVLogicalVisitor::TypeServer = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

</div>
</div>

### W {#a3adbf76993743bebe9266aae0550908a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedPrinter&amp; llvm::logicalview::LVLogicalVisitor::W</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvcodeviewvisitor-h">LVCodeViewVisitor.h</a>.</p>

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
