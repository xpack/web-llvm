---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfunit-2
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DwarfUnit` Class

<p>This dwarf writer support class manages information associated with a source file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DwarfUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">CodeGen/AsmPrinter/DwarfUnit.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieunit">DIEUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a compile or type unit. <a href="/web-llvm/docs/api/classes/llvm/dieunit/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit-2">DwarfCompileUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit-2">DwarfTypeUnit</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa741c84d13418c47473a9c3a05eb1e54">DwarfUnit</a> (dwarf::Tag, const DICompileUnit *Node, AsmPrinter *A, DwarfDebug *DW, DwarfFile *DWU, unsigned UniqueID=0)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ab461419067c655c6e99837faa7003">~DwarfUnit</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72fc15677cff47ef8f3f982ebf2098c">getUniqueID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets Unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this unit. <a href="#af72fc15677cff47ef8f3f982ebf2098c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bbdeeba8dbac3c17e48c16517a5a2ca">getAsmPrinter</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add3090d802188ed9bd035b1534574f15">getLabelBegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the the symbol for start of the section for this unit. <a href="#add3090d802188ed9bd035b1534574f15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab860a0ea2334cccbf45dc61e951f24c">getEndLabel</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2136f1c2850f7a143f730a0cb007214f">getLanguage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abebd15dd4b82e33ca73757397490ea80">getCUNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e424e67bc81915803e8ab194775446">getDwarfDebug</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b7757799d6bf9e5674586eaa362a61">hasContent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this compile unit has something to write out. <a href="#a98b7757799d6bf9e5674586eaa362a61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aace6bf1aa397a8c6f9b832c8a39b8b6c">getParentContextString</a> (const DIScope *Context) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get string containing language specific context for a global name. <a href="#aace6bf1aa397a8c6f9b832c8a39b8b6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa2594939f99f9c434b0558b3b2c686">addGlobalName</a> (StringRef Name, const DIE &amp;Die, const DIScope *Context)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new global name to the compile unit. <a href="#adfa2594939f99f9c434b0558b3b2c686">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795b65ecb3fb9634a9c95aa515b26e64">addGlobalTypeImpl</a> (const DIType *Ty, const DIE &amp;Die, const DIScope *Context)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new global type to the compile unit. <a href="#a795b65ecb3fb9634a9c95aa515b26e64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636fc6b14398163c6762d820c7f5d2a9">addGlobalType</a> (const DIType *Ty, const DIE &amp;Die, const DIScope *Context)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89437d84c778ca21710b480b3a2e48e0">getDIE</a> (const DINode *D) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> map slot for the specified debug variable. <a href="#a89437d84c778ca21710b480b3a2e48e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd864ffd6d132872a81840dafcf77cc">getDIELoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a fresh newly allocated <a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a>. <a href="#a2cd864ffd6d132872a81840dafcf77cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a517c4fddcafa9e846541f027a1364fcb">insertDIE</a> (const DINode *Desc, DIE *D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> into the map. <a href="#a517c4fddcafa9e846541f027a1364fcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dcac57169982b885dd1bace7f86d777">insertDIE</a> (DIE *D)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a> (DIE &amp;Die, dwarf::Attribute Attribute)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a flag that is true to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#ae6243db70660a7d705bd1c739c49cc6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d00f6235eca359e429053abedd6cfa5">addUInt</a> (DIEValueList &amp;Die, dwarf::Attribute Attribute, std::optional&lt; dwarf::Form &gt; Form, uint64_t Integer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an unsigned integer attribute data and value. <a href="#a3d00f6235eca359e429053abedd6cfa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b37eb41948672cdfb96862e32ac3b38">addUInt</a> (DIEValueList &amp;Block, dwarf::Form Form, uint64_t Integer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6bd295826d6eda8304af6da84feac34">addSInt</a> (DIEValueList &amp;Die, dwarf::Attribute Attribute, std::optional&lt; dwarf::Form &gt; Form, int64_t Integer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an signed integer attribute data and value. <a href="#aa6bd295826d6eda8304af6da84feac34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a873e29fff3dd24acc381f92e40667fd7">addSInt</a> (DIELoc &amp;Die, std::optional&lt; dwarf::Form &gt; Form, int64_t Integer)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0734fce4dae0f79f3a00e6b3539f8b96">addInt</a> (DIE &amp;Die, dwarf::Attribute Attribute, const APInt &amp;Integer, bool Unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an integer attribute data and value; value may be any width. <a href="#a0734fce4dae0f79f3a00e6b3539f8b96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40aa1e13b1e51c58c3463a519990fd51">addString</a> (DIE &amp;Die, dwarf::Attribute Attribute, StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a string attribute data and value. <a href="#a40aa1e13b1e51c58c3463a519990fd51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc9162892e03a06667b4f11a023170e8">addLabel</a> (DIEValueList &amp;Die, dwarf::Attribute Attribute, dwarf::Form Form, const MCSymbol *Label)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a Dwarf label attribute data and value. <a href="#acc9162892e03a06667b4f11a023170e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a697b2ea921e48e9d0925126608bc8b3d">addLabel</a> (DIELoc &amp;Die, dwarf::Form Form, const MCSymbol *Label)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d178b977eb4b3ee74e3052eb73382f">addSectionOffset</a> (DIE &amp;Die, dwarf::Attribute Attribute, uint64_t Integer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an offset into a section attribute data and value. <a href="#ac5d178b977eb4b3ee74e3052eb73382f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a7c0e3436e571693ed818b4985cf133">addOpAddress</a> (DIELoc &amp;Die, const MCSymbol *Sym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a dwarf op address data and value using the form given and an op of either DW_FORM_addr or DW_FORM_GNU_addr_index. <a href="#a3a7c0e3436e571693ed818b4985cf133">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ef869ce359f62362cd8ab0b372f6df">addPoolOpAddress</a> (DIEValueList &amp;Die, const MCSymbol *Label)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa748b4decf2622ab7e6a7ae30da0a2e0">addLabelDelta</a> (DIEValueList &amp;Die, dwarf::Attribute Attribute, const MCSymbol *Hi, const MCSymbol *Lo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a label delta attribute data and value. <a href="#aa748b4decf2622ab7e6a7ae30da0a2e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaba0cc8de9b241a925289c9e0d8295b">addDIEEntry</a> (DIE &amp;Die, dwarf::Attribute Attribute, DIE &amp;Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attribute data and value. <a href="#afaba0cc8de9b241a925289c9e0d8295b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d50108df42008d870359f0e7c98ea5d">addDIEEntry</a> (DIE &amp;Die, dwarf::Attribute Attribute, DIEEntry Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attribute data and value. <a href="#a6d50108df42008d870359f0e7c98ea5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80dce05e37b13ae2207ae1a7a45020a8">addDIETypeSignature</a> (DIE &amp;Die, uint64_t Signature)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a type's DW_AT_signature and set the declaration flag. <a href="#a80dce05e37b13ae2207ae1a7a45020a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22cc608046a783393c3097da86376822">addBlock</a> (DIE &amp;Die, dwarf::Attribute Attribute, DIELoc *Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add block data. <a href="#a22cc608046a783393c3097da86376822">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe78d2ae41f40f096d004f389eb66f1b">addBlock</a> (DIE &amp;Die, dwarf::Attribute Attribute, DIEBlock *Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add block data. <a href="#abe78d2ae41f40f096d004f389eb66f1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add07f005d598ee456d64181a6fd36bfb">addBlock</a> (DIE &amp;Die, dwarf::Attribute Attribute, dwarf::Form Form, DIEBlock *Block)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a> (DIE &amp;Die, unsigned Line, const DIFile *File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add location information to specified debug information entry. <a href="#ab0a887e5b9315ec43f516a5a362e3b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09231f9afbc43f1b884dfd995bf40f66">addSourceLine</a> (DIE &amp;Die, const DILocalVariable *V)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a75511bb96b3902e1ea6cacd5dc45b">addSourceLine</a> (DIE &amp;Die, const DIGlobalVariable *G)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345253fa2659077aca783c7017df7eb1">addSourceLine</a> (DIE &amp;Die, const DISubprogram *SP)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37acd2473e85422648d602697febbfe7">addSourceLine</a> (DIE &amp;Die, const DILabel *L)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e89654341b10dc2e095b51f2a6beb23">addSourceLine</a> (DIE &amp;Die, const DIType *Ty)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ea2a9afd1453b9ac15c05df9dacd39">addSourceLine</a> (DIE &amp;Die, const DIObjCProperty *Ty)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ccb514c025257d1c6d106dae4c0689">addConstantValue</a> (DIE &amp;Die, const ConstantInt *CI, const DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add constant value entry in variable <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a47ccb514c025257d1c6d106dae4c0689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f99aa9289ff51ee31de0d7c303969a8">addConstantValue</a> (DIE &amp;Die, const APInt &amp;Val, const DIType *Ty)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add70e1fee22605cd751d89682c4dd5c7">addConstantValue</a> (DIE &amp;Die, const APInt &amp;Val, bool Unsigned)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa488320919f5d67a71343c37dba91f93">addConstantValue</a> (DIE &amp;Die, uint64_t Val, const DIType *Ty)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11f4cd87a4292db7b1f7605debc5abc">addConstantValue</a> (DIE &amp;Die, bool Unsigned, uint64_t Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdbc6c6e847bf30e629b1de682424b8d">addConstantFPValue</a> (DIE &amp;Die, const ConstantFP *CFP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add constant value entry in variable <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#acdbc6c6e847bf30e629b1de682424b8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa849a65237107c0118e25e93a42ab2bd">addLinkageName</a> (DIE &amp;Die, StringRef LinkageName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a linkage name, if it isn't empty. <a href="#aa849a65237107c0118e25e93a42ab2bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a242b3dd9a06d131c011d8e8d9b3bddf5">addTemplateParams</a> (DIE &amp;Buffer, DINodeArray TParams)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add template parameters in buffer. <a href="#a242b3dd9a06d131c011d8e8d9b3bddf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ca23a0485648a0706b5caab309fc50">addThrownTypes</a> (DIE &amp;Die, DINodeArray ThrownTypes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add thrown types. <a href="#a14ca23a0485648a0706b5caab309fc50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5632cea4b6055960d3c3d31430650ee0">addAccess</a> (DIE &amp;Die, DINode::DIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the accessibility attribute. <a href="#a5632cea4b6055960d3c3d31430650ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af901a106fc9f196e781bcc03587c66d8">addType</a> (DIE &amp;Entity, const DIType *Ty, dwarf::Attribute Attribute=dwarf::DW_AT_type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new type attribute to the specified entity. <a href="#af901a106fc9f196e781bcc03587c66d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a> (const DINamespace *NS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a> (const DIModule *M)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad258972cf15e00c497db2e2621c60e7b">getOrCreateSubprogramDIE</a> (const DISubprogram *SP, bool Minimal=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a> (const DISubprogram *SP, DIE &amp;SPDie, bool SkipSPAttributes=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64cca2d21cc17e087bd22d4cc648b4a5">createTypeDIE</a> (const DIScope *Context, DIE &amp;ContextDIE, const DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with specific context. <a href="#a64cca2d21cc17e087bd22d4cc648b4a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a> (const MDNode *TyNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find existing <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> or create new <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given type. <a href="#a061639ab612b4f5036d163a01275ced0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a> (const DIScope *Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get context owner's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a245886f14570b56d514fd631d2b74c31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07fecfc1a873e6ebc47fcb8706c7e48">constructContainingTypeDIEs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct DIEs for types that contain vtables. <a href="#ad07fecfc1a873e6ebc47fcb8706c7e48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaab22fc54a4612ec58459997f58c6cc">constructSubprogramArguments</a> (DIE &amp;Buffer, DITypeRefArray Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct function argument DIEs. <a href="#abaab22fc54a4612ec58459997f58c6cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4053999da10fee3e053346031495319">createAndAddDIE</a> (dwarf::Tag Tag, DIE &amp;Parent, const DINode *N=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with the given Tag, add the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to its parent, and call insertDIE if MD is not null. <a href="#ac4053999da10fee3e053346031495319">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2acd2605469a025ea0520d586baf1b56">useSegmentedStringOffsetsTable</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f45a669235b32b6a7e2d7e8a7b95f53">getHeaderSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the size of a header for this unit, not including the initial length field. <a href="#a8f45a669235b32b6a7e2d7e8a7b95f53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e872823d52cafea3dca803cdc014e7">emitHeader</a> (bool UseOffsets)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the header for this unit, not including the initial length field. <a href="#a37e872823d52cafea3dca803cdc014e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c1d3ec37aec1008ed52018d257a2608">addStringOffsetsStart</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the DW_AT_str_offsets_base attribute to the unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a1c1d3ec37aec1008ed52018d257a2608">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab967d1b87b81cc88415cd294bc1d70c4">addRnglistsBase</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the DW_AT_rnglists_base attribute to the unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#ab967d1b87b81cc88415cd294bc1d70c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8855e888c6f1af018fc479664ba81ebb">getCU</a> ()=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a> (DIE &amp;Buffer, const DICompositeType *CTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6e3a70db3c30dc6999e3cd70ed8818">addSectionDelta</a> (DIE &amp;Die, dwarf::Attribute Attribute, const MCSymbol *Hi, const MCSymbol *Lo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addSectionDelta - Add a label delta attribute data and value. <a href="#a5f6e3a70db3c30dc6999e3cd70ed8818">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad340d0233181f79e69e6b70f1411f788">addSectionLabel</a> (DIE &amp;Die, dwarf::Attribute Attribute, const MCSymbol *Label, const MCSymbol *Sec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a Dwarf section label attribute data and value. <a href="#ad340d0233181f79e69e6b70f1411f788">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c898e1e28aff43017285cae176864ae">addAnnotation</a> (DIE &amp;Buffer, DINodeArray Annotations)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add DW_TAG_LLVM_annotation. <a href="#a1c898e1e28aff43017285cae176864ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe089815356ff5272af5e0ca382cb75">createTypeDIE</a> (const DICompositeType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get context owner's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a9fe089815356ff5272af5e0ca382cb75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31f89aa4723ba0da7351f5fc5c13d753">updateAcceleratorTables</a> (const DIScope *Context, const DIType *Ty, const DIE &amp;TyDIE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a named finished type then include it in the list of types for the accelerator tables. <a href="#a31f89aa4723ba0da7351f5fc5c13d753">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a> (const DISubprogram *SP, DIE &amp;SPDie, bool Minimal)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad426154fed29e102c17d745b44cf2006">isShareableAcrossCUs</a> (const DINode *D) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for this <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> can be shared across CUs. <a href="#ad426154fed29e102c17d745b44cf2006">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a> (DIEValueList &amp;Die, dwarf::Attribute Attribute, dwarf::Form Form, T &amp;&amp;Value)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a> (const DIDerivedType *DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create new static data member <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#acc3268e4df66097512cb6b4b87b438d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be9b0263b4dce4cf6b6e4f72d2ce733">getOrCreateSourceID</a> (const DIFile *File)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the source <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the given file. <a href="#a6be9b0263b4dce4cf6b6e4f72d2ce733">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c77b8d4ff2ea875d1c29128d4ef848">emitCommonHeader</a> (bool UseOffsets, dwarf::UnitType UT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the common part of the header for this unit. <a href="#ab0c77b8d4ff2ea875d1c29128d4ef848">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f20754947035fda02b15e369fee9af">addIntAsBlock</a> (DIE &amp;Die, dwarf::Attribute Attribute, const APInt &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper to add a wide integer constant to a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> using a block form. <a href="#af3f20754947035fda02b15e369fee9af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1dad81a1e6780e4b2be966d83e90cbd">constructTypeDIE</a> (DIE &amp;Buffer, const DIBasicType *BTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ac8e6bc58ade336b68457e3834219e">constructTypeDIE</a> (DIE &amp;Buffer, const DIStringType *BTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44fb6f8a489f43f53eadbd083f8e4395">constructTypeDIE</a> (DIE &amp;Buffer, const DIDerivedType *DTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a036687872d40bbaf3f5b2a2caaf6b965">constructTypeDIE</a> (DIE &amp;Buffer, const DISubroutineType *CTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab31435ceb28cebf00897cf5bd5d1d65d">constructSubrangeDIE</a> (DIE &amp;Buffer, const DISubrange *SR, DIE *IndexTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f2f2a4878553dca01503e986b5085a">constructGenericSubrangeDIE</a> (DIE &amp;Buffer, const DIGenericSubrange *SR, DIE *IndexTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4235daaac2798caf4ca3a2a63bcd5f73">constructArrayTypeDIE</a> (DIE &amp;Buffer, const DICompositeType *CTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af71a19c0053fbd501b4e7df30dffec16">constructEnumTypeDIE</a> (DIE &amp;Buffer, const DICompositeType *CTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d98a089312041e424dc6a385d97bed">constructMemberDIE</a> (DIE &amp;Buffer, const DIDerivedType *DT)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3bb32f3467824bd7d8fcf4ee2334f67">constructTemplateTypeParameterDIE</a> (DIE &amp;Buffer, const DITemplateTypeParameter *TP)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93513b8ad7c3bf122e442e92dcffc6f9">constructTemplateValueParameterDIE</a> (DIE &amp;Buffer, const DITemplateValueParameter *TVP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac216a54e35fb84c6c6664dc071778aa">getDefaultLowerBound</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the default lower bound for an array. <a href="#aac216a54e35fb84c6c6664dc071778aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc3033882eaf89e13882979d29e634c">getIndexTyDie</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an anonymous type for index type. <a href="#aecc3033882eaf89e13882979d29e634c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc884e1fd0510c0a3c4259da36f6b7e4">setIndexTyDie</a> (DIE *D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set D as anonymous type for index which can be reused later. <a href="#abc884e1fd0510c0a3c4259da36f6b7e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e5b7ca90600199f31d41465064b7205">finishNonUnitTypeDIE</a> (DIE &amp;D, const DICompositeType *CTy)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a7e1bd9eb5d0214e0004bdb0b4f10d5">isDwoUnit</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d8b6226a3ef79d63d214b39a0168c9a">getCrossSectionRelativeBaseAddress</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdee0920b5a31567d070b11733f51f29">isCompatibleWithVersion</a> (uint16_t Version) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns 'true' if the current DwarfVersion is compatible with the specified <span class="doxyComputerOutput">Version</span>. <a href="#abdee0920b5a31567d070b11733f51f29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2310d013342a17731b506aa8703c603">UniqueID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A numeric <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> unique among all CUs in the module. <a href="#ad2310d013342a17731b506aa8703c603">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7f81014d334cde3ccb0adc60028d1a">CUNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> for the compile unit. <a href="#a6b7f81014d334cde3ccb0adc60028d1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6677c846a0cd16e11adda0b56ce86bc">DIEValueAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af168e2063740a8197ed9ebf886f4bc0e">Asm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> of Dwarf emission. <a href="#af168e2063740a8197ed9ebf886f4bc0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e5e39be4bacc4da9b8f17a49dd9521">LabelBegin</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The start of the unit within its section. <a href="#aa5e5e39be4bacc4da9b8f17a49dd9521">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4fd64dbad816e7b3857e688386b3448">EndLabel</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emitted at the end of the <a href="/web-llvm/docs/api/namespaces/cu">CU</a> and used to compute the <a href="/web-llvm/docs/api/namespaces/cu">CU</a> Length field. <a href="#ae4fd64dbad816e7b3857e688386b3448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6688320f2a55f0e73b315d17b5691d7d">DD</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarffile">DwarfFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac553859c86da1b85f054877cff171ef5">DU</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9208ab4eec3d7b349083bd08282e488">IndexTyDie</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An anonymous type for index type. Owned by <a href="/web-llvm/docs/api/classes/llvm/dieunit">DIEUnit</a>. <a href="#ab9208ab4eec3d7b349083bd08282e488">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb002b7ae6f79a65164b6511877e9e2">MDNodeToDieMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks the mapping of unit level debug information variables to debug information entries. <a href="#addb002b7ae6f79a65164b6511877e9e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dieblock">DIEBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e01043a837000a452db38a8b7419812">DIEBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of all the DIEBlocks in use. <a href="#a1e01043a837000a452db38a8b7419812">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2000974b90ff9adde1b5448a8dad51d3">DIELocs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of all the DIELocs in use. <a href="#a2000974b90ff9adde1b5448a8dad51d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acc4d4cea1d5a8e8ed6b63151c160db">ContainingTypeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This map is used to keep track of subprogram DIEs that need DW_AT_containing_type attribute. <a href="#a6acc4d4cea1d5a8e8ed6b63151c160db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This dwarf writer support class manages information associated with a source file.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### DwarfUnit() {#aa741c84d13418c47473a9c3a05eb1e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfUnit::DwarfUnit (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> UnitTag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> * DW, <a href="/web-llvm/docs/api/classes/llvm/dwarffile">DwarfFile</a> * DWU, unsigned UniqueID=0)</td>
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



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#a83e4cae05827ffe9e2f4e3505bd848af">llvm::DIEUnit::DIEUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">DU</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad2310d013342a17731b506aa8703c603">UniqueID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6d50108df42008d870359f0e7c98ea5d">addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad52017f371f28817067fc0ea956886e7">llvm::DwarfCompileUnit::DwarfCompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a0fbb35d6382945bd41592fe8b8d4eee7">llvm::DwarfTypeUnit::DwarfTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">getOrCreateSubprogramDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~DwarfUnit() {#aa6ab461419067c655c6e99837faa7003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfUnit::~DwarfUnit ()</td>
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



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1e01043a837000a452db38a8b7419812">DIEBlocks</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2000974b90ff9adde1b5448a8dad51d3">DIELocs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAccess() {#a5632cea4b6055960d3c3d31430650ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addAccess (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the accessibility attribute.</p>

<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0d65769846c1450523fea2b9423f0166a53533831b8c9b40cc34d1e7239b3ad6b">llvm::dwarf::DW_ACCESS_private</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0d65769846c1450523fea2b9423f0166a9b1c9facbbf18363a980e7caa48f6f26">llvm::dwarf::DW_ACCESS_protected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0d65769846c1450523fea2b9423f0166ab70898d18dc7607a9bc3829f7baf1fcd">llvm::dwarf::DW_ACCESS_public</a> and <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9a30b209e4417da06657aed5dc140e0127">llvm::DINode::FlagAccessibility</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a>.</p>

</div>
</div>

### addAnnotation() {#a1c898e1e28aff43017285cae176864ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addAnnotation (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, DINodeArray Annotations)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add DW_TAG_LLVM_annotation.</p>

<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a47ccb514c025257d1c6d106dae4c0689">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>.</p>

</div>
</div>

### addBlock() {#a22cc608046a783393c3097da86376822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addBlock (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> * Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add block data.</p>

<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2000974b90ff9adde1b5448a8dad51d3">DIELocs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abe78d2ae41f40f096d004f389eb66f1b">addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae7f8bac4a8c515d95110494a2ed662e5">llvm::DwarfCompileUnit::addLabelAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">llvm::DwarfCompileUnit::constructCallSiteParmEntryDIEs</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### addBlock() {#abe78d2ae41f40f096d004f389eb66f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addBlock (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/classes/llvm/dieblock">DIEBlock</a> * Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add block data.</p>

<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">addBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>.</p>

</div>
</div>

### addBlock() {#add07f005d598ee456d64181a6fd36bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addBlock (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form, <a href="/web-llvm/docs/api/classes/llvm/dieblock">DIEBlock</a> * Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1e01043a837000a452db38a8b7419812">DIEBlocks</a>.</p>

</div>
</div>

### addConstantFPValue() {#acdbc6c6e847bf30e629b1de682424b8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addConstantFPValue (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * CFP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add constant value entry in variable <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a47ccb514c025257d1c6d106dae4c0689">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a>.</p>

</div>
</div>

### addConstantValue() {#a47ccb514c025257d1c6d106dae4c0689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addConstantValue (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add constant value entry in variable <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a47ccb514c025257d1c6d106dae4c0689">addConstantValue</a> and <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c898e1e28aff43017285cae176864ae">addAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acdbc6c6e847bf30e629b1de682424b8d">addConstantFPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#add70e1fee22605cd751d89682c4dd5c7">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5f99aa9289ff51ee31de0d7c303969a8">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a47ccb514c025257d1c6d106dae4c0689">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa488320919f5d67a71343c37dba91f93">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a>.</p>

</div>
</div>

### addConstantValue() {#a5f99aa9289ff51ee31de0d7c303969a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addConstantValue (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a47ccb514c025257d1c6d106dae4c0689">addConstantValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>.</p>

</div>
</div>

### addConstantValue() {#add70e1fee22605cd751d89682c4dd5c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addConstantValue (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val, bool Unsigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a47ccb514c025257d1c6d106dae4c0689">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fac837bff23a12c3735d463020f37979de">Unsigned</a>.</p>

</div>
</div>

### addConstantValue() {#aa488320919f5d67a71343c37dba91f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addConstantValue (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, uint64_t Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a47ccb514c025257d1c6d106dae4c0689">addConstantValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>.</p>

</div>
</div>

### addConstantValue() {#ae11f4cd87a4292db7b1f7605debc5abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addConstantValue (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, bool Unsigned, uint64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fac837bff23a12c3735d463020f37979de">Unsigned</a>.</p>

</div>
</div>

### addDIEEntry() {#afaba0cc8de9b241a925289c9e0d8295b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addDIEEntry (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attribute data and value.</p>

<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">addDIEEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">addType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">llvm::DwarfCompileUnit::constructAbstractSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">llvm::DwarfCompileUnit::constructCallSiteEntryDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad07fecfc1a873e6ebc47fcb8706c7e48">constructContainingTypeDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">llvm::DwarfCompileUnit::constructInlinedScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a8cbe3dd2e5c24c363d750bd49f46838a">llvm::DwarfCompileUnit::constructSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3554b83e3e334e00da341d9aba81a47e">llvm::DwarfCompileUnit::finishEntityDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#afd5821362beb37693123202b5e35d15a">llvm::DwarfCompileUnit::finishSubprogramDefinition</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>.</p>

</div>
</div>

### addDIEEntry() {#a6d50108df42008d870359f0e7c98ea5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addDIEEntry (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/classes/llvm/dieentry">DIEEntry</a> Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attribute data and value.</p>

<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#a83e4cae05827ffe9e2f4e3505bd848af">llvm::DIEUnit::DIEUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa741c84d13418c47473a9c3a05eb1e54">DwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a7d981b742b9e50f3499554c31c6aa001">llvm::DIE::getUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>.</p>

</div>
</div>

### addDIETypeSignature() {#a80dce05e37b13ae2207ae1a7a45020a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addDIETypeSignature (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, uint64_t Signature)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a type's DW_AT_signature and set the declaration flag.</p>

<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a>.</p>

</div>
</div>

### addFlag() {#ae6243db70660a7d705bd1c739c49cc6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addFlag (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a flag that is true to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a80dce05e37b13ae2207ae1a7a45020a8">addDIETypeSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">llvm::DwarfCompileUnit::constructCallSiteEntryDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abaab22fc54a4612ec58459997f58c6cc">constructSubprogramArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### addGlobalName() {#adfa2594939f99f9c434b0558b3b2c686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfUnit::addGlobalName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new global name to the compile unit.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a>.</p>

</div>
</div>

### addGlobalType() {#a636fc6b14398163c6762d820c7f5d2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addGlobalType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a795b65ecb3fb9634a9c95aa515b26e64">addGlobalTypeImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a64cca2d21cc17e087bd22d4cc648b4a5">createTypeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a31f89aa4723ba0da7351f5fc5c13d753">updateAcceleratorTables</a>.</p>

</div>
</div>

### addGlobalTypeImpl() {#a795b65ecb3fb9634a9c95aa515b26e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfUnit::addGlobalTypeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new global type to the compile unit.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a636fc6b14398163c6762d820c7f5d2a9">addGlobalType</a>.</p>

</div>
</div>

### addInt() {#a0734fce4dae0f79f3a00e6b3539f8b96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addInt (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Integer, bool Unsigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an integer attribute data and value; value may be any width.</p>

<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa6bd295826d6eda8304af6da84feac34">addSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fac837bff23a12c3735d463020f37979de">Unsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>.</p>

</div>
</div>

### addLabel() {#acc9162892e03a06667b4f11a023170e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addLabel (<a href="/web-llvm/docs/api/classes/llvm/dievaluelist">DIEValueList</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a Dwarf label attribute data and value.</p>

<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a697b2ea921e48e9d0925126608bc8b3d">addLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a7c0e3436e571693ed818b4985cf133">addOpAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">addSectionLabel</a>.</p>

</div>
</div>

### addLabel() {#a697b2ea921e48e9d0925126608bc8b3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addLabel (<a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc9162892e03a06667b4f11a023170e8">addLabel</a>.</p>

</div>
</div>

### addLabelDelta() {#aa748b4decf2622ab7e6a7ae30da0a2e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addLabelDelta (<a href="/web-llvm/docs/api/classes/llvm/dievaluelist">DIEValueList</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Hi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Lo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a label delta attribute data and value.</p>

<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">DIEValueAllocator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad6ef869ce359f62362cd8ab0b372f6df">addPoolOpAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0b3f89703fa8ecd73c1b43a7ac656402">llvm::DwarfCompileUnit::attachLowHighPC</a>.</p>

</div>
</div>

### addLinkageName() {#aa849a65237107c0118e25e93a42ab2bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addLinkageName (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LinkageName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a linkage name, if it isn't empty.</p>

<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3e999e4bb7297d284f931638721840e5">llvm::GlobalValue::dropLLVMManglingEscape</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">llvm::DwarfCompileUnit::constructCallSiteEntryDIE</a>.</p>

</div>
</div>

### addOpAddress() {#a3a7c0e3436e571693ed818b4985cf133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addOpAddress (<a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a dwarf op address data and value using the form given and an op of either DW_FORM_addr or DW_FORM_GNU_addr_index.</p>

<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc9162892e03a06667b4f11a023170e8">addLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad6ef869ce359f62362cd8ab0b372f6df">addPoolOpAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>.</p>

</div>
</div>

### addPoolOpAddress() {#ad6ef869ce359f62362cd8ab0b372f6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addPoolOpAddress (<a href="/web-llvm/docs/api/classes/llvm/dievaluelist">DIEValueList</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa748b4decf2622ab7e6a7ae30da0a2e0">addLabelDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae7f8bac4a8c515d95110494a2ed662e5">llvm::DwarfCompileUnit::addLabelAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a7c0e3436e571693ed818b4985cf133">addOpAddress</a>.</p>

</div>
</div>

### addRnglistsBase() {#ab967d1b87b81cc88415cd294bc1d70c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addRnglistsBase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the DW_AT_rnglists_base attribute to the unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1933 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">addSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">DU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a7cddd5b91a2f88c1c204cafeca322517">llvm::MCObjectFileInfo::getDwarfRnglistsSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>.</p>

</div>
</div>

### addSectionDelta() {#a5f6e3a70db3c30dc6999e3cd70ed8818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSectionDelta (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Hi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Lo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addSectionDelta - Add a label delta attribute data and value.</p>

<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1888 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">DIEValueAllocator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4e4e697039d4692563c2ccc3608864d1">llvm::DwarfCompileUnit::addScopeRangeList</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">addSectionLabel</a>.</p>

</div>
</div>

### addSectionLabel() {#ad340d0233181f79e69e6b70f1411f788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSectionLabel (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a Dwarf section label attribute data and value.</p>

<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1894 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc9162892e03a06667b4f11a023170e8">addLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5f6e3a70db3c30dc6999e3cd70ed8818">addSectionDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3abb9664e1a14148cc2ad7f330009b20">llvm::DwarfCompileUnit::addAddrTableBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab967d1b87b81cc88415cd294bc1d70c4">addRnglistsBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4e4e697039d4692563c2ccc3608864d1">llvm::DwarfCompileUnit::addScopeRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c1d3ec37aec1008ed52018d257a2608">addStringOffsetsStart</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a780e3087cd40ac6f03e93e1722993cc2">llvm::DwarfCompileUnit::applyStmtList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a5bf6adcaa4ad6740a1a7544e827a5231">llvm::DwarfCompileUnit::initStmtList</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### addSectionOffset() {#ac5d178b977eb4b3ee74e3052eb73382f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSectionOffset (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, uint64_t Integer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an offset into a section attribute data and value.</p>

<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>.</p>

</div>
</div>

### addSInt() {#aa6bd295826d6eda8304af6da84feac34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSInt (<a href="/web-llvm/docs/api/classes/llvm/dievaluelist">DIEValueList</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> &gt; Form, int64_t Integer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an signed integer attribute data and value.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dieinteger/#af397b05376454122495039750b702064">llvm::DIEInteger::BestForm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0734fce4dae0f79f3a00e6b3539f8b96">addInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a873e29fff3dd24acc381f92e40667fd7">addSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">llvm::DwarfCompileUnit::constructAbstractSubprogramScopeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### addSInt() {#a873e29fff3dd24acc381f92e40667fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSInt (<a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> &amp; Die, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> &gt; Form, int64_t Integer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa6bd295826d6eda8304af6da84feac34">addSInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>.</p>

</div>
</div>

### addSourceLine() {#ab0a887e5b9315ec43f516a5a362e3b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSourceLine (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, unsigned Line, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add location information to specified debug information entry.</p>

<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6be9b0263b4dce4cf6b6e4f72d2ce733">getOrCreateSourceID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4a75511bb96b3902e1ea6cacd5dc45b">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a37acd2473e85422648d602697febbfe7">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a09231f9afbc43f1b884dfd995bf40f66">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab4ea2a9afd1453b9ac15c05df9dacd39">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a345253fa2659077aca783c7017df7eb1">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6e89654341b10dc2e095b51f2a6beb23">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab848ab31ed9686e47adbc3cd56c7a1f1">llvm::DwarfCompileUnit::applyLabelAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">llvm::DwarfCompileUnit::getOrCreateCommonBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a>.</p>

</div>
</div>

### addSourceLine() {#a09231f9afbc43f1b884dfd995bf40f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSourceLine (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### addSourceLine() {#ac4a75511bb96b3902e1ea6cacd5dc45b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSourceLine (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### addSourceLine() {#a345253fa2659077aca783c7017df7eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSourceLine (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### addSourceLine() {#a37acd2473e85422648d602697febbfe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSourceLine (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### addSourceLine() {#a6e89654341b10dc2e095b51f2a6beb23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSourceLine (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### addSourceLine() {#ab4ea2a9afd1453b9ac15c05df9dacd39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addSourceLine (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diobjcproperty">DIObjCProperty</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### addString() {#a40aa1e13b1e51c58c3463a519990fd51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addString (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a string attribute data and value.</p>


<p>We always emit a reference to the string pool instead of immediate strings so that DIEs have more predictable sizes. In the case of split dwarf we emit an index into another table which gets us the static offset into the string table.</p>


<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">DU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2acd2605469a025ea0520d586baf1b56">useSegmentedStringOffsetsTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c898e1e28aff43017285cae176864ae">addAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ad06f166cd8884265b3a1ea2849f0c026">llvm::DwarfDebug::addDwarfTypeUnitType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa849a65237107c0118e25e93a42ab2bd">addLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab848ab31ed9686e47adbc3cd56c7a1f1">llvm::DwarfCompileUnit::applyLabelAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4c89d112b2f04f66826428c19d11301b">llvm::DwarfCompileUnit::createBaseTypeDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">llvm::DwarfCompileUnit::getOrCreateCommonBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a>.</p>

</div>
</div>

### addStringOffsetsStart() {#a1c1d3ec37aec1008ed52018d257a2608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addStringOffsetsStart ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the DW_AT_str_offsets_base attribute to the unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1926 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">addSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">DU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a3d677a1ab07bb4796933369f69396459">llvm::MCObjectFileInfo::getDwarfStrOffSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ad06f166cd8884265b3a1ea2849f0c026">llvm::DwarfDebug::addDwarfTypeUnitType</a>.</p>

</div>
</div>

### addTemplateParams() {#a242b3dd9a06d131c011d8e8d9b3bddf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addTemplateParams (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, DINodeArray TParams)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add template parameters in buffer.</p>

<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>.</p>

</div>
</div>

### addThrownTypes() {#a14ca23a0485648a0706b5caab309fc50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addThrownTypes (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, DINodeArray ThrownTypes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add thrown types.</p>

<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">addType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>.</p>

</div>
</div>

### addType() {#af901a106fc9f196e781bcc03587c66d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addType (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Entity, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute=dwarf::DW_AT_type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new type attribute to the specified entity.</p>


<p>This takes and attribute parameter because DW_AT_friend attributes are also type references.</p>


<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">addDIEEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a14ca23a0485648a0706b5caab309fc50">addThrownTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abaab22fc54a4612ec58459997f58c6cc">constructSubprogramArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a>.</p>

</div>
</div>

### addUInt() {#a3d00f6235eca359e429053abedd6cfa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addUInt (<a href="/web-llvm/docs/api/classes/llvm/dievaluelist">DIEValueList</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> &gt; Form, uint64_t Integer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an unsigned integer attribute data and value.</p>

<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dieinteger/#af397b05376454122495039750b702064">llvm::DIEInteger::BestForm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5632cea4b6055960d3c3d31430650ee0">addAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae11f4cd87a4292db7b1f7605debc5abc">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ad06f166cd8884265b3a1ea2849f0c026">llvm::DwarfDebug::addDwarfTypeUnitType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0734fce4dae0f79f3a00e6b3539f8b96">addInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a7c0e3436e571693ed818b4985cf133">addOpAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad6ef869ce359f62362cd8ab0b372f6df">addPoolOpAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4e4e697039d4692563c2ccc3608864d1">llvm::DwarfCompileUnit::addScopeRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac5d178b977eb4b3ee74e3052eb73382f">addSectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0b37eb41948672cdfb96862e32ac3b38">addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7f1c08f4c14daab9f9b9bd3502b0b384">llvm::DwarfCompileUnit::applyCommonDbgVariableAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">llvm::DwarfCompileUnit::constructInlinedScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4c89d112b2f04f66826428c19d11301b">llvm::DwarfCompileUnit::createBaseTypeDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### addUInt() {#a0b37eb41948672cdfb96862e32ac3b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addUInt (<a href="/web-llvm/docs/api/classes/llvm/dievaluelist">DIEValueList</a> &amp; Block, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form, uint64_t Integer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>.</p>

</div>
</div>

### applySubprogramAttributes() {#af98bb2acd8151e832fd48655cf8561bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::applySubprogramAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; SPDie, bool SkipSPAttributes=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5632cea4b6055960d3c3d31430650ee0">addAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c898e1e28aff43017285cae176864ae">addAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a14ca23a0485648a0706b5caab309fc50">addThrownTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">addType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abaab22fc54a4612ec58459997f58c6cc">constructSubprogramArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6acc4d4cea1d5a8e8ed6b63151c160db">ContainingTypeMap</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2cd864ffd6d132872a81840dafcf77cc">getDIELoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2136f1c2850f7a143f730a0cb007214f">getLanguage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae7ce1492f0cb3bd9fb92b462751f9e5b">llvm::dwarf::isC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9e16a00186a0cb4e8265515d9bbebb93">llvm::DwarfCompileUnit::applySubprogramAttributesToDefinition</a>.</p>

</div>
</div>

### constructContainingTypeDIEs() {#ad07fecfc1a873e6ebc47fcb8706c7e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructContainingTypeDIEs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct DIEs for types that contain vtables.</p>

<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6acc4d4cea1d5a8e8ed6b63151c160db">ContainingTypeMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### constructSubprogramArguments() {#abaab22fc54a4612ec58459997f58c6cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::constructSubprogramArguments (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/classes/llvm/dityperefarray">DITypeRefArray</a> Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct function argument DIEs.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> of the object pointer if one exists. Nullptr otherwise.</p></dd>
</dl>


<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">addType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>.</p>

</div>
</div>

### constructTypeDIE() {#ade80cb280096b057a649d3570dde295f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructTypeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * CTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 944 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5632cea4b6055960d3c3d31430650ee0">addAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c898e1e28aff43017285cae176864ae">addAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0734fce4dae0f79f3a00e6b3539f8b96">addInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a242b3dd9a06d131c011d8e8d9b3bddf5">addTemplateParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">addType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#aa58988e88e7b1220cf23af045dfb0f70">llvm::DIType::getAlignInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#ad2e64febd404c2f88e3d43e3d4963925">llvm::DICompositeType::getAnnotations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#a4ba54e885d45e215707278aa160a414c">llvm::DICompositeType::getDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#a8cee69d690ed86ce76452279e28793a5">llvm::DICompositeType::getElements</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#ae7103e933bc0128304ae334e0f2bff1e">llvm::DIType::getExportSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a72b28555a5542157a94925bee775c381">llvm::DIType::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#a752f20477f301bba0db8fcef7db6588d">llvm::DICompositeType::getIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a777848a3e8c10c10721c852d4efb9e3b">llvm::DIType::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a1a27093c6d543f556ecbde05b39cc9af">llvm::DIType::getNumExtraInhabitants</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">getOrCreateSubprogramDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#aed0c086b90c36bf35ed9b34c0c5777cc">llvm::DICompositeType::getRawIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#a4c3ec2bbc1252095ec499f353f83c6f0">llvm::DICompositeType::getRuntimeLang</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a8b53bdd5b8f1d8cd12a392c256cb54f3">llvm::DIType::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#a4fd68828c7c0838743420b9d0b48ffca">llvm::DICompositeType::getSpecification</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#aeac16c22ec5a0c13658381144c7e3439">llvm::DIE::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#a8f32f797838f7521e527b768b3483cfa">llvm::DICompositeType::getTemplateParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#ad1034598d2193424d72a16363fcfb799">llvm::DICompositeType::getVTableHolder</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a41aaf0cfd4e81054733e5deb8316a940">llvm::DIType::isAppleBlockExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a78039d632c4d3f50030540598ba03b47">llvm::DIType::isForwardDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a4058e68d700e5863fe573dcb038d33ab">llvm::DIType::isObjcClassComplete</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#af3f406ac863f7eb317afda1d3b531f8e">llvm::DIType::isTypePassByReference</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a89d152e101beeff3eb54720544e4c9f9">llvm::DIType::isTypePassByValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a9fe089815356ff5272af5e0ca382cb75">createTypeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a64cca2d21cc17e087bd22d4cc648b4a5">createTypeDIE</a>.</p>

</div>
</div>

### createAndAddDIE() {#ac4053999da10fee3e053346031495319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; DwarfUnit::createAndAddDIE (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * N=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with the given Tag, add the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to its parent, and call insertDIE if MD is not null.</p>

<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a3bd79b4ce04e1141856b6076717b4615">llvm::DIE::addChild</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">DIEValueAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a517c4fddcafa9e846541f027a1364fcb">insertDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c898e1e28aff43017285cae176864ae">addAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a14ca23a0485648a0706b5caab309fc50">addThrownTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">llvm::DwarfCompileUnit::constructAbstractSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">llvm::DwarfCompileUnit::constructCallSiteEntryDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abaab22fc54a4612ec58459997f58c6cc">constructSubprogramArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a9fe089815356ff5272af5e0ca382cb75">createTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a64cca2d21cc17e087bd22d4cc648b4a5">createTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">llvm::DwarfCompileUnit::getOrCreateCommonBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">getOrCreateSubprogramDIE</a>.</p>

</div>
</div>

### createTypeDIE() {#a64cca2d21cc17e087bd22d4cc648b4a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::createTypeDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; ContextDIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with specific context.</p>

<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a636fc6b14398163c6762d820c7f5d2a9">addGlobalType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8855e888c6f1af018fc479664ba81ebb">getCU</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a31f89aa4723ba0da7351f5fc5c13d753">updateAcceleratorTables</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ad06f166cd8884265b3a1ea2849f0c026">llvm::DwarfDebug::addDwarfTypeUnitType</a>.</p>

</div>
</div>

### createTypeDIE() {#a9fe089815356ff5272af5e0ca382cb75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::createTypeDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get context owner's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a31f89aa4723ba0da7351f5fc5c13d753">updateAcceleratorTables</a>.</p>

</div>
</div>

### emitHeader() {#a37e872823d52cafea3dca803cdc014e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfUnit::emitHeader (bool UseOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the header for this unit, not including the initial length field.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a66056de6e47af980edacced419d5d0b8">llvm::DwarfFile::emitUnit</a>.</p>

</div>
</div>

### getAsmPrinter() {#a8bbdeeba8dbac3c17e48c16517a5a2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter * llvm::DwarfUnit::getAsmPrinter ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>.</p>

</div>
</div>

### getCU() {#a8855e888c6f1af018fc479664ba81ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual DwarfCompileUnit &amp; llvm::DwarfUnit::getCU ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a64cca2d21cc17e087bd22d4cc648b4a5">createTypeDIE</a>.</p>

</div>
</div>

### getCUNode() {#abebd15dd4b82e33ca73757397490ea80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DICompileUnit * llvm::DwarfUnit::getCUNode ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">CUNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a0fbb35d6382945bd41592fe8b8d4eee7">llvm::DwarfTypeUnit::DwarfTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a66056de6e47af980edacced419d5d0b8">llvm::DwarfFile::emitUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">llvm::DwarfCompileUnit::includeMinimalInlineScopes</a>.</p>

</div>
</div>

### getDIE() {#a89437d84c778ca21710b480b3a2e48e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::getDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> map slot for the specified debug variable.</p>


<p>We delegate the request to <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> when the <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> can be part of the type system, since DIEs for the type system can be shared across CUs and the mappings are kept in <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a>.</p>


<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">DU</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad426154fed29e102c17d745b44cf2006">isShareableAcrossCUs</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#addb002b7ae6f79a65164b6511877e9e2">MDNodeToDieMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad07fecfc1a873e6ebc47fcb8706c7e48">constructContainingTypeDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a9fe089815356ff5272af5e0ca382cb75">createTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#afd5821362beb37693123202b5e35d15a">llvm::DwarfCompileUnit::finishSubprogramDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">llvm::DwarfCompileUnit::getOrCreateCommonBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a1b6f98e91ce662c3a7a89705a00ef67f">llvm::DwarfCompileUnit::getOrCreateImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">getOrCreateSubprogramDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a>.</p>

</div>
</div>

### getDIELoc() {#a2cd864ffd6d132872a81840dafcf77cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIELoc * llvm::DwarfUnit::getDIELoc ()</td>
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

<p>Returns a fresh newly allocated <a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a>.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">DIEValueAllocator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>.</p>

</div>
</div>

### getDwarfDebug() {#a13e424e67bc81915803e8ab194775446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfDebug &amp; llvm::DwarfUnit::getDwarfDebug ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3554b83e3e334e00da341d9aba81a47e">llvm::DwarfCompileUnit::finishEntityDefinition</a>.</p>

</div>
</div>

### getEndLabel() {#aab860a0ea2334cccbf45dc61e951f24c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::DwarfUnit::getEndLabel ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae4fd64dbad816e7b3857e688386b3448">EndLabel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a66056de6e47af980edacced419d5d0b8">llvm::DwarfFile::emitUnit</a>.</p>

</div>
</div>

### getHeaderSize() {#a8f45a669235b32b6a7e2d7e8a7b95f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::DwarfUnit::getHeaderSize ()</td>
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

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a61d1f7077f90348ee80ceb8885dd3930">llvm::DwarfFile::computeSizeAndOffsetsForUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0c77b8d4ff2ea875d1c29128d4ef848">emitCommonHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0e5a7772e91857ecf8d244dd25a1baf1">llvm::DwarfCompileUnit::getHeaderSize</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a51ea895dc3048572e73b2b909ae1c319">llvm::DwarfTypeUnit::getHeaderSize</a>.</p>

</div>
</div>

### getLabelBegin() {#add3090d802188ed9bd035b1534574f15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::DwarfUnit::getLabelBegin ()</td>
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

<p>Get the the symbol for start of the section for this unit.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa5e5e39be4bacc4da9b8f17a49dd9521">LabelBegin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac4372f5cbd92647d1f4f90fcdb8a5474">llvm::emitDWARF5AccelTable</a>.</p>

</div>
</div>

### getLanguage() {#a2136f1c2850f7a143f730a0cb007214f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::DwarfUnit::getLanguage ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">CUNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aace6bf1aa397a8c6f9b832c8a39b8b6c">getParentContextString</a>.</p>

</div>
</div>

### getOrCreateContextDIE() {#a245886f14570b56d514fd631d2b74c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::getOrCreateContextDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
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

<p>Get context owner's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">getOrCreateSubprogramDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a9fe089815356ff5272af5e0ca382cb75">createTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a7b6f34c53b2dbad48a28b675922003e1">llvm::DwarfCompileUnit::getOrCreateContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">getOrCreateStaticMemberDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">getOrCreateSubprogramDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a>.</p>

</div>
</div>

### getOrCreateModule() {#abb8b851d28660fcaa83d9d983853bc93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::getOrCreateModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dimodule">DIModule</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#adfa2594939f99f9c434b0558b3b2c686">addGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6be9b0263b4dce4cf6b6e4f72d2ce733">getOrCreateSourceID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a>.</p>

</div>
</div>

### getOrCreateNameSpace() {#a48251691c7140c430d26b9b4c7ecc667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::getOrCreateNameSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinamespace">DINamespace</a> * NS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#adfa2594939f99f9c434b0558b3b2c686">addGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dinamespace/#acdacfd705e894f30ff22112a2bd1299d">llvm::DINamespace::getExportSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/dinamespace/#a9f302f543cab66b01c4f214edf0e3186">llvm::DINamespace::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dinamespace/#a60de4cc798886b1f66d04bd67a92c407">llvm::DINamespace::getScope</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a>.</p>

</div>
</div>

### getOrCreateSubprogramDIE() {#ad258972cf15e00c497db2e2621c60e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::getOrCreateSubprogramDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP, bool Minimal=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa741c84d13418c47473a9c3a05eb1e54">DwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">getOrCreateSubprogramDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a7d981b742b9e50f3499554c31c6aa001">llvm::DIE::getUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">llvm::DwarfCompileUnit::constructAbstractSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">llvm::DwarfCompileUnit::constructCallSiteEntryDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">getOrCreateSubprogramDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### getOrCreateTypeDIE() {#a061639ab612b4f5036d163a01275ced0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::getOrCreateTypeDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * TyNode)</td>
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

<p>Find existing <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> or create new <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given type.</p>

<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa741c84d13418c47473a9c3a05eb1e54">DwarfUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#aa831f0a1520a405a32196cb32ec24084">getBaseType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/die/#a7d981b742b9e50f3499554c31c6aa001">llvm::DIE::getUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">addType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a>.</p>

</div>
</div>

### getParentContextString() {#aace6bf1aa397a8c6f9b832c8a39b8b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string DwarfUnit::getParentContextString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get string containing language specific context for a global name.</p>


<p>Walks the metadata parent chain in a language specific manner (using the compile unit language) and returns it as a string. This is done at the metadata level because DIEs may not currently have been added to the parent context and walking the DIEs looking for names is more expensive than walking the metadata.</p>


<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2136f1c2850f7a143f730a0cb007214f">getLanguage</a>, <a href="/web-llvm/docs/api/classes/llvm/discope/#abfb5e80306fec86349d69fd373f83d84">llvm::DIScope::getScope</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aaedb78de657237c48255243a68e1dbc1">llvm::dwarf::isCPlusPlus</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a742e325bd655dc33c538065902d73a9e">llvm::DwarfCompileUnit::addGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3365d623c06b679b5852addcbe4214c6">llvm::DwarfCompileUnit::addGlobalNameForTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ac514ce80941fff1bd81f371317a2f8b8">llvm::DwarfCompileUnit::addGlobalTypeImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad94baae1a66e6173dc2f9ee860fc7d8d">llvm::DwarfCompileUnit::addGlobalTypeUnitType</a>.</p>

</div>
</div>

### getUniqueID() {#af72fc15677cff47ef8f3f982ebf2098c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfUnit::getUniqueID ()</td>
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

<p>Gets Unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this unit.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad2310d013342a17731b506aa8703c603">UniqueID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acd839ab10698d2e52b0021818e8d9625">llvm::DwarfCompileUnit::getOrCreateSourceID</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a5bf6adcaa4ad6740a1a7544e827a5231">llvm::DwarfCompileUnit::initStmtList</a>.</p>

</div>
</div>

### hasContent() {#a98b7757799d6bf9e5674586eaa362a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfUnit::hasContent ()</td>
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

<p>Return true if this compile unit has something to write out.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a> and <a href="/web-llvm/docs/api/classes/llvm/die/#ac91c79b70f4cc8c8cfe0dff567124ea4">llvm::DIE::hasChildren</a>.</p>

</div>
</div>

### insertDIE() {#a517c4fddcafa9e846541f027a1364fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::insertDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * Desc, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> into the map.</p>


<p>We delegate the request to <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> when the <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> can be part of the type system, since DIEs for the type system can be shared across CUs and the mappings are kept in <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a>.</p>


<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">DU</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad426154fed29e102c17d745b44cf2006">isShareableAcrossCUs</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#addb002b7ae6f79a65164b6511877e9e2">MDNodeToDieMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">llvm::DwarfCompileUnit::constructCallSiteParmEntryDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad6d394e7617fdbb955ce7db1fc9aaff7">llvm::DwarfCompileUnit::constructLabelDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a90e6b90f1ecca9999a225bac737d2fdc">llvm::DwarfCompileUnit::constructVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad52017f371f28817067fc0ea956886e7">llvm::DwarfCompileUnit::DwarfCompileUnit</a>.</p>

</div>
</div>

### insertDIE() {#a5dcac57169982b885dd1bace7f86d777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::insertDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#addb002b7ae6f79a65164b6511877e9e2">MDNodeToDieMap</a>.</p>

</div>
</div>

### updateAcceleratorTables() {#a31f89aa4723ba0da7351f5fc5c13d753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::updateAcceleratorTables (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; TyDIE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a named finished type then include it in the list of types for the accelerator tables.</p>

<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a636fc6b14398163c6762d820c7f5d2a9">addGlobalType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6b7f81014d334cde3ccb0adc60028d1a">CUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da5209d785d6f9540a65239398210353f9">llvm::dwarf::DW_FLAG_type_implementation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a9fe089815356ff5272af5e0ca382cb75">createTypeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a64cca2d21cc17e087bd22d4cc648b4a5">createTypeDIE</a>.</p>

</div>
</div>

### useSegmentedStringOffsetsTable() {#a2acd2605469a025ea0520d586baf1b56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfUnit::useSegmentedStringOffsetsTable ()</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addAttribute() {#a3a4749711edc974c75d9439d5f8d8d3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfUnit::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/dievaluelist">DIEValueList</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form, T &amp;&amp; Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsversioning/#ga2087d6878afd42110e590b0c75fad4a2">llvm::dwarf::AttributeVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab6677c846a0cd16e11adda0b56ce86bc">DIEValueAllocator</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a255424b02147849a3f013d1dc7d8b544">llvm::DwarfCompileUnit::addBaseTypeRef</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#add07f005d598ee456d64181a6fd36bfb">addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6d50108df42008d870359f0e7c98ea5d">addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a80dce05e37b13ae2207ae1a7a45020a8">addDIETypeSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab1a8483dca80b0435c63148629476aaf">llvm::DwarfCompileUnit::addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc9162892e03a06667b4f11a023170e8">addLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae7f8bac4a8c515d95110494a2ed662e5">llvm::DwarfCompileUnit::addLabelAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa748b4decf2622ab7e6a7ae30da0a2e0">addLabelDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ac2ec97478e68f7a1d1570b6b058853b4">llvm::DwarfCompileUnit::addLocalLabelAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae8e1f64509dc4e7c6a0ee7ea1592cdf3">llvm::DwarfCompileUnit::addLocationList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5f6e3a70db3c30dc6999e3cd70ed8818">addSectionDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa6bd295826d6eda8304af6da84feac34">addSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>.</p>

</div>
</div>

### applySubprogramDefinitionAttributes() {#a2b107908666d5d5a2920e6fb28387f7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfUnit::applySubprogramDefinitionAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; SPDie, bool Minimal)</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afaba0cc8de9b241a925289c9e0d8295b">addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa849a65237107c0118e25e93a42ab2bd">addLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a242b3dd9a06d131c011d8e8d9b3bddf5">addTemplateParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">addType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac553859c86da1b85f054877cff171ef5">DU</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6be9b0263b4dce4cf6b6e4f72d2ce733">getOrCreateSourceID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a> and <a href="/web-llvm/docs/api/classes/llvm/dityperefarray/#ac4bfdb24ae42d443c9c1bd807edb5171">llvm::DITypeRefArray::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>.</p>

</div>
</div>

### emitCommonHeader() {#ab0c77b8d4ff2ea875d1c29128d4ef848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::emitCommonHeader (bool UseOffsets, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6a3dd4d92f72d16b160115c464ca436f">dwarf::UnitType</a> UT)</td>
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

<p>Emit the common part of the header for this unit.</p>

<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1835 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af168e2063740a8197ed9ebf886f4bc0e">Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae4fd64dbad816e7b3857e688386b3448">EndLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac10c6a9d85782db274d19ef8f828d9fc">llvm::MCObjectFileInfo::getDwarfAbbrevSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8f45a669235b32b6a7e2d7e8a7b95f53">getHeaderSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensaasmbackend-cpp/#a13a0babfc55adc9b798c39e65ec9e8a3">getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0c18db764d4e597a32d9ae44e2953cd3">llvm::DwarfCompileUnit::emitHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a728bd7f19076bf53ee0069149a6512f0">llvm::DwarfTypeUnit::emitHeader</a>.</p>

</div>
</div>

### getOrCreateSourceID() {#a6be9b0263b4dce4cf6b6e4f72d2ce733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::DwarfUnit::getOrCreateSourceID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File)</td>
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

<p>Look up the source <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the given file.</p>


<p>If none currently exists, create a new <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and insert it in the line table.</p>


<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab9208ab4eec3d7b349083bd08282e488">IndexTyDie</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abb8b851d28660fcaa83d9d983853bc93">getOrCreateModule</a>.</p>

</div>
</div>

### getOrCreateStaticMemberDIE() {#acc3268e4df66097512cb6b4b87b438d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::getOrCreateStaticMemberDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * DT)</td>
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

<p>Create new static data member <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1792 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5632cea4b6055960d3c3d31430650ee0">addAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acdbc6c6e847bf30e629b1de682424b8d">addConstantFPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a47ccb514c025257d1c6d106dae4c0689">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0a887e5b9315ec43f516a5a362e3b48">addSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af901a106fc9f196e781bcc03587c66d8">addType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">addUInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#aa58988e88e7b1220cf23af045dfb0f70">llvm::DIType::getAlignInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/diderivedtype/#aa537b7354f39b1d60795fde760509c7d">llvm::DIDerivedType::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a72b28555a5542157a94925bee775c381">llvm::DIType::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a777848a3e8c10c10721c852d4efb9e3b">llvm::DIType::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a245886f14570b56d514fd631d2b74c31">getOrCreateContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#af38242c719f0cacb09b91e354bd3145e">llvm::DIType::getScope</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#aeac16c22ec5a0c13658381144c7e3439">llvm::DIE::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a13471a1f55ae60d82d774585bfd3c5da">llvm::DINode::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#ae2c69eaa942e8a9e5efd0a1cf8d79d95">llvm::DIType::isArtificial</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a72f3beb3e0825cf70183d525cfe4be31">llvm::dwarf::isType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>.</p>

</div>
</div>

### isShareableAcrossCUs() {#ad426154fed29e102c17d745b44cf2006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfUnit::isShareableAcrossCUs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * D)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for this <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> can be shared across CUs.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6688320f2a55f0e73b315d17b5691d7d">DD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a517c4fddcafa9e846541f027a1364fcb">insertDIE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addIntAsBlock() {#af3f20754947035fda02b15e369fee9af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::addIntAsBlock (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper to add a wide integer constant to a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> using a block form.</p>

<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructArrayTypeDIE() {#a4235daaac2798caf4ca3a2a63bcd5f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructArrayTypeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * CTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1557 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructEnumTypeDIE() {#af71a19c0053fbd501b4e7df30dffec16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructEnumTypeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * CTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1631 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructGenericSubrangeDIE() {#a62f2f2a4878553dca01503e986b5085a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructGenericSubrangeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/digenericsubrange">DIGenericSubrange</a> * SR, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * IndexTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1474 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructMemberDIE() {#ae0d98a089312041e424dc6a385d97bed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; DwarfUnit::constructMemberDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1673 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructSubrangeDIE() {#ab31435ceb28cebf00897cf5bd5d1d65d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructSubrangeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubrange">DISubrange</a> * SR, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * IndexTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1433 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructTemplateTypeParameterDIE() {#aa3bb32f3467824bd7d8fcf4ee2334f67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructTemplateTypeParameterDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditemplatetypeparameter">DITemplateTypeParameter</a> * TP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructTemplateValueParameterDIE() {#a93513b8ad7c3bf122e442e92dcffc6f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructTemplateValueParameterDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditemplatevalueparameter">DITemplateValueParameter</a> * TVP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructTypeDIE() {#ad1dad81a1e6780e4b2be966d83e90cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructTypeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> * BTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructTypeDIE() {#aa0ac8e6bc58ade336b68457e3834219e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructTypeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> * BTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructTypeDIE() {#a44fb6f8a489f43f53eadbd083f8e4395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructTypeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * DTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### constructTypeDIE() {#a036687872d40bbaf3f5b2a2caaf6b965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::constructTypeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> * CTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### finishNonUnitTypeDIE() {#a3e5b7ca90600199f31d41465064b7205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfUnit::finishNonUnitTypeDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; D, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * CTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>

</div>
</div>

### getCrossSectionRelativeBaseAddress() {#a9d8b6226a3ef79d63d214b39a0168c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol * DwarfUnit::getCrossSectionRelativeBaseAddress ()</td>
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



<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1918 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### getDefaultLowerBound() {#aac216a54e35fb84c6c6664dc071778aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t DwarfUnit::getDefaultLowerBound ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the default lower bound for an array.</p>


<p>If the DWARF version doesn't handle the language, return -1.</p>


<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### getIndexTyDie() {#aecc3033882eaf89e13882979d29e634c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DwarfUnit::getIndexTyDie ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an anonymous type for index type.</p>

<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### isCompatibleWithVersion() {#abdee0920b5a31567d070b11733f51f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfUnit::isCompatibleWithVersion (uint16_t Version)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns 'true' if the current DwarfVersion is compatible with the specified <span class="doxyComputerOutput">Version</span>.</p>

<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>, definition at line 1946 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### isDwoUnit() {#a0a7e1bd9eb5d0214e0004bdb0b4f10d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::DwarfUnit::isDwoUnit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>

</div>
</div>

### setIndexTyDie() {#abc884e1fd0510c0a3c4259da36f6b7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfUnit::setIndexTyDie (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * D)</td>
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

<p>Set D as anonymous type for index which can be reused later.</p>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Asm {#af168e2063740a8197ed9ebf886f4bc0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter* llvm::DwarfUnit::Asm</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> of Dwarf emission.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3abb9664e1a14148cc2ad7f330009b20">llvm::DwarfCompileUnit::addAddrTableBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#add07f005d598ee456d64181a6fd36bfb">addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab967d1b87b81cc88415cd294bc1d70c4">addRnglistsBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4e4e697039d4692563c2ccc3608864d1">llvm::DwarfCompileUnit::addScopeRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">addSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c1d3ec37aec1008ed52018d257a2608">addStringOffsetsStart</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a780e3087cd40ac6f03e93e1722993cc2">llvm::DwarfCompileUnit::applyStmtList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a37d00bd782a8ae88d11495124673cd53">llvm::DwarfCompileUnit::attachRangesOrLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">llvm::DwarfCompileUnit::constructCallSiteParmEntryDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad52017f371f28817067fc0ea956886e7">llvm::DwarfCompileUnit::DwarfCompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa741c84d13418c47473a9c3a05eb1e54">DwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0c77b8d4ff2ea875d1c29128d4ef848">emitCommonHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0c18db764d4e597a32d9ae44e2953cd3">llvm::DwarfCompileUnit::emitHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a728bd7f19076bf53ee0069149a6512f0">llvm::DwarfTypeUnit::emitHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8bbdeeba8dbac3c17e48c16517a5a2ca">getAsmPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a51ea895dc3048572e73b2b909ae1c319">llvm::DwarfTypeUnit::getHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8f45a669235b32b6a7e2d7e8a7b95f53">getHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a68d4481aea40e318a364df01ae10d308">llvm::DwarfCompileUnit::getLength</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acd839ab10698d2e52b0021818e8d9625">llvm::DwarfCompileUnit::getOrCreateSourceID</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a5bf6adcaa4ad6740a1a7544e827a5231">llvm::DwarfCompileUnit::initStmtList</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### ContainingTypeMap {#a6acc4d4cea1d5a8e8ed6b63151c160db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;DIE *, const DINode *&gt; llvm::DwarfUnit::ContainingTypeMap</td>
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

<p>This map is used to keep track of subprogram DIEs that need DW_AT_containing_type attribute.</p>


<p>This attribute points to a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that corresponds to the <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> mapped with the subprogram <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad07fecfc1a873e6ebc47fcb8706c7e48">constructContainingTypeDIEs</a>.</p>

</div>
</div>

### CUNode {#a6b7f81014d334cde3ccb0adc60028d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DICompileUnit* llvm::DwarfUnit::CUNode</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> for the compile unit.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">llvm::DwarfCompileUnit::constructInlinedScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa741c84d13418c47473a9c3a05eb1e54">DwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3554b83e3e334e00da341d9aba81a47e">llvm::DwarfCompileUnit::finishEntityDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abebd15dd4b82e33ca73757397490ea80">getCUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2136f1c2850f7a143f730a0cb007214f">getLanguage</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ade4388f12ad1757626e62ed0e1da6cf8">llvm::DwarfCompileUnit::hasDwarfPubSections</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a5bf6adcaa4ad6740a1a7544e827a5231">llvm::DwarfCompileUnit::initStmtList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a31f89aa4723ba0da7351f5fc5c13d753">updateAcceleratorTables</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### DD {#a6688320f2a55f0e73b315d17b5691d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfDebug* llvm::DwarfUnit::DD</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3abb9664e1a14148cc2ad7f330009b20">llvm::DwarfCompileUnit::addAddrTableBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5f99aa9289ff51ee31de0d7c303969a8">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa488320919f5d67a71343c37dba91f93">addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6d50108df42008d870359f0e7c98ea5d">addDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae6243db70660a7d705bd1c739c49cc6b">addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae7f8bac4a8c515d95110494a2ed662e5">llvm::DwarfCompileUnit::addLabelAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa849a65237107c0118e25e93a42ab2bd">addLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae8e1f64509dc4e7c6a0ee7ea1592cdf3">llvm::DwarfCompileUnit::addLocationList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a7c0e3436e571693ed818b4985cf133">addOpAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad6ef869ce359f62362cd8ab0b372f6df">addPoolOpAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a39cb0b18cc6f463c1d383db1ee6c6226">llvm::DwarfCompileUnit::addRange</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab967d1b87b81cc88415cd294bc1d70c4">addRnglistsBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4e4e697039d4692563c2ccc3608864d1">llvm::DwarfCompileUnit::addScopeRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5f6e3a70db3c30dc6999e3cd70ed8818">addSectionDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad340d0233181f79e69e6b70f1411f788">addSectionLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac5d178b977eb4b3ee74e3052eb73382f">addSectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af98bb2acd8151e832fd48655cf8561bb">applySubprogramAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0b3f89703fa8ecd73c1b43a7ac656402">llvm::DwarfCompileUnit::attachLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a37d00bd782a8ae88d11495124673cd53">llvm::DwarfCompileUnit::attachRangesOrLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af8875ff9c8633acdeb1e970471f37f57">llvm::DwarfCompileUnit::attachRangesOrLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">llvm::DwarfCompileUnit::constructAbstractSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">llvm::DwarfCompileUnit::constructCallSiteEntryDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">llvm::DwarfCompileUnit::constructInlinedScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ac43078e4f82c8dea48b4a483de6f434a">llvm::DwarfCompileUnit::constructLexicalScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acf65d0311d21263e1470c9c5f2ad57d8">llvm::DwarfCompileUnit::constructScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">llvm::DwarfCompileUnit::createAndAddScopeChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a64cca2d21cc17e087bd22d4cc648b4a5">createTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa741c84d13418c47473a9c3a05eb1e54">DwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0c77b8d4ff2ea875d1c29128d4ef848">emitCommonHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0c18db764d4e597a32d9ae44e2953cd3">llvm::DwarfCompileUnit::emitHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a728bd7f19076bf53ee0069149a6512f0">llvm::DwarfTypeUnit::emitHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a13e424e67bc81915803e8ab194775446">getDwarfDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0e5a7772e91857ecf8d244dd25a1baf1">llvm::DwarfCompileUnit::getHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8f45a669235b32b6a7e2d7e8a7b95f53">getHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a48251691c7140c430d26b9b4c7ecc667">getOrCreateNameSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acd839ab10698d2e52b0021818e8d9625">llvm::DwarfCompileUnit::getOrCreateSourceID</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">getOrCreateTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ade4388f12ad1757626e62ed0e1da6cf8">llvm::DwarfCompileUnit::hasDwarfPubSections</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">llvm::DwarfCompileUnit::includeMinimalInlineScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a5bf6adcaa4ad6740a1a7544e827a5231">llvm::DwarfCompileUnit::initStmtList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad426154fed29e102c17d745b44cf2006">isShareableAcrossCUs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a31f89aa4723ba0da7351f5fc5c13d753">updateAcceleratorTables</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a021658afc8b95fca777f7f6ebc36aa8c">llvm::DwarfCompileUnit::useGNUAnalogForDwarf5Feature</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2acd2605469a025ea0520d586baf1b56">useSegmentedStringOffsetsTable</a>.</p>

</div>
</div>

### DIEBlocks {#a1e01043a837000a452db38a8b7419812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DIEBlock *&gt; llvm::DwarfUnit::DIEBlocks</td>
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

<p>A list of all the DIEBlocks in use.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#add07f005d598ee456d64181a6fd36bfb">addBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa6ab461419067c655c6e99837faa7003">~DwarfUnit</a>.</p>

</div>
</div>

### DIELocs {#a2000974b90ff9adde1b5448a8dad51d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DIELoc *&gt; llvm::DwarfUnit::DIELocs</td>
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

<p>A list of all the DIELocs in use.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a22cc608046a783393c3097da86376822">addBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa6ab461419067c655c6e99837faa7003">~DwarfUnit</a>.</p>

</div>
</div>

### DIEValueAllocator {#ab6677c846a0cd16e11adda0b56ce86bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::DwarfUnit::DIEValueAllocator</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3a4749711edc974c75d9439d5f8d8d3b">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a255424b02147849a3f013d1dc7d8b544">llvm::DwarfCompileUnit::addBaseTypeRef</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ae7f8bac4a8c515d95110494a2ed662e5">llvm::DwarfCompileUnit::addLabelAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa748b4decf2622ab7e6a7ae30da0a2e0">addLabelDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5f6e3a70db3c30dc6999e3cd70ed8818">addSectionDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">llvm::DwarfCompileUnit::constructCallSiteParmEntryDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">llvm::DwarfCompileUnit::constructInlinedScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad6d394e7617fdbb955ce7db1fc9aaff7">llvm::DwarfCompileUnit::constructLabelDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ac43078e4f82c8dea48b4a483de6f434a">llvm::DwarfCompileUnit::constructLexicalScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a8cbe3dd2e5c24c363d750bd49f46838a">llvm::DwarfCompileUnit::constructSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a90e6b90f1ecca9999a225bac737d2fdc">llvm::DwarfCompileUnit::constructVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4c89d112b2f04f66826428c19d11301b">llvm::DwarfCompileUnit::createBaseTypeDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2cd864ffd6d132872a81840dafcf77cc">getDIELoc</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### DU {#ac553859c86da1b85f054877cff171ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfFile* llvm::DwarfUnit::DU</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab967d1b87b81cc88415cd294bc1d70c4">addRnglistsBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4e4e697039d4692563c2ccc3608864d1">llvm::DwarfCompileUnit::addScopeRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c1d3ec37aec1008ed52018d257a2608">addStringOffsetsStart</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">applySubprogramDefinitionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a77347a4881397840dcd27b24ce537976">llvm::DwarfCompileUnit::createAbstractEntity</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">llvm::DwarfCompileUnit::createAndAddScopeChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa741c84d13418c47473a9c3a05eb1e54">DwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a517c4fddcafa9e846541f027a1364fcb">insertDIE</a>.</p>

</div>
</div>

### EndLabel {#ae4fd64dbad816e7b3857e688386b3448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::DwarfUnit::EndLabel = nullptr</td>
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

<p>Emitted at the end of the <a href="/web-llvm/docs/api/namespaces/cu">CU</a> and used to compute the <a href="/web-llvm/docs/api/namespaces/cu">CU</a> Length field.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a37d00bd782a8ae88d11495124673cd53">llvm::DwarfCompileUnit::attachRangesOrLowHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0c77b8d4ff2ea875d1c29128d4ef848">emitCommonHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aab860a0ea2334cccbf45dc61e951f24c">getEndLabel</a>.</p>

</div>
</div>

### IndexTyDie {#ab9208ab4eec3d7b349083bd08282e488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE* llvm::DwarfUnit::IndexTyDie = nullptr</td>
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

<p>An anonymous type for index type. Owned by <a href="/web-llvm/docs/api/classes/llvm/dieunit">DIEUnit</a>.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6be9b0263b4dce4cf6b6e4f72d2ce733">getOrCreateSourceID</a>.</p>

</div>
</div>

### LabelBegin {#aa5e5e39be4bacc4da9b8f17a49dd9521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::DwarfUnit::LabelBegin = nullptr</td>
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

<p>The start of the unit within its section.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0c18db764d4e597a32d9ae44e2953cd3">llvm::DwarfCompileUnit::emitHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a728bd7f19076bf53ee0069149a6512f0">llvm::DwarfTypeUnit::emitHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#add3090d802188ed9bd035b1534574f15">getLabelBegin</a>.</p>

</div>
</div>

### MDNodeToDieMap {#addb002b7ae6f79a65164b6511877e9e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MDNode *, DIE *&gt; llvm::DwarfUnit::MDNodeToDieMap</td>
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

<p>Tracks the mapping of unit level debug information variables to debug information entries.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a89437d84c778ca21710b480b3a2e48e0">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a517c4fddcafa9e846541f027a1364fcb">insertDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5dcac57169982b885dd1bace7f86d777">insertDIE</a>.</p>

</div>
</div>

### UniqueID {#ad2310d013342a17731b506aa8703c603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfUnit::UniqueID</td>
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

<p>A numeric <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> unique among all CUs in the module.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a0fbb35d6382945bd41592fe8b8d4eee7">llvm::DwarfTypeUnit::DwarfTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa741c84d13418c47473a9c3a05eb1e54">DwarfUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af72fc15677cff47ef8f3f982ebf2098c">getUniqueID</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
