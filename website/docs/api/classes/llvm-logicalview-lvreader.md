---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LVReader` Class Reference

<p>The logical reader owns of all the logical elements created during the debug information parsing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">llvm/DebugInfo/LogicalView/Core/LVReader.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader">LVBinaryReader</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a7b25150e8d216ca4c8e76f303535da">LVCompileUnits</a> = std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit">LVScopeCompileUnit</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e8126edb83953e3574e3219f2699441">LVReader</a> ()=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51b8f4c5562374eaa5c78328fb06866">LVReader</a> (StringRef InputFilename, StringRef FileFormatName, ScopedPrinter &amp;W, LVBinaryType BinaryType=LVBinaryType::NONE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6780a33f3a5ba4d163b2197418ec48ea">LVReader</a> (const LVReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9979d510ae1d37d0e20c81f303d8b382">~LVReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader">LVReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8936c821e1cbf6a17a9734e33dc3c464">operator=</a> (const LVReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvoperation">LVOperation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06aaf2479ae6fe75fa6343470c9a8b3">createOperation</a> (LVSmall OpCode, ArrayRef&lt; LVUnsigned &gt; Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6646a556e7732c3d1037047b4bb4ee7e">getFilename</a> (LVObject *Object, size_t Index) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cfe13a99c14005ccbf4e6b653713f0e">getFilename</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a716192d66503b8a150d3733eff9bed90">setFilename</a> (std::string Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a173b2c02cb716c1a72a382299247be61">getFileFormatName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d0e7c1f6f2d4eebe51c777d93e32994">outputStream</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ecb9e315e671cd9a27fbe0ff16aa60">isBinaryTypeNone</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9820ed153363430133ad612fcc12ba24">isBinaryTypeELF</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73c06cb3a2d9d61ca64f3b6d1f21da50">isBinaryTypeCOFF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit">LVScopeCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab63da9e640f8c75ac3ecdd69f5973958">getCompileUnit</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfef57e1f937ca038c926e972ffd0cef">setCompileUnit</a> (LVScope *Scope)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ca29eae6fd36123cdbbfe24f3f3bba">setCompileUnitCPUType</a> (codeview::CPUType Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3a314f44c015362563c5333db978173d">codeview::CPUType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd83f4a260a18452465d5b20bde0f5e">getCompileUnitCPUType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscoperoot">LVScopeRoot</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ababa74ea6d8e9a9ce3088ab57c0c05ec">getScopesRoot</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6198458ec732d8dff12eb1a80049ded">doPrint</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a15ec2eff468d1dc1137a8a8f20f525">doLoad</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba7d69a179758cfe95b692774eb95ab">getRegisterName</a> (LVSmall Opcode, ArrayRef&lt; uint64_t &gt; Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79e79d328c2a1364382c050f1edc3b9f">getDotTextSectionIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac114092781e95d398899c7f2864ce714">getSectionIndex</a> (LVScope *Scope)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d96f20ae76f4b4a0de2b0712d5fdfb6">isSystemEntry</a> (LVElement *Element, StringRef Name={}) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsplitcontext">LVSplitContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fb7fc2d1f1a253a711802569b1eb8d6">getSplitContext</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47afac89aa48ca6a5c668780c2f1875d">notifyAddedElement</a> (LVLine *Line)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb09fcfc3a072a252db0ec57b633567a">notifyAddedElement</a> (LVScope *Scope)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4b49aa764ec9304ac9477baf23534b">notifyAddedElement</a> (LVSymbol *Symbol)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a08d2b0039c19cc3c2c60d03bc648b5">notifyAddedElement</a> (LVType *Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad04c501dd7f0cb888ae3e44b71be05e0">LVLines</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a564c678b9c1f6e695345ada025a66fb2">getLines</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a5d77e75079f8249cc3e8681e6b2d8a18">LVScopes</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa02580d86cd6da9d4053e8c149d8bb8">getScopes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a86d76ed6f92c1d16716bd39fadc6de5d">LVSymbols</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd721fd42c94e71fd18cc56f69c23f3">getSymbols</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#aef1328881e2236584b34de4050631e4b">LVTypes</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304580d8cb7b13766ace495f2b06b669">getTypes</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d1f13f69ec0826e1aa53f5707b7b4b4">doPrintLine</a> (const LVLine *Line) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b83ee7be20688c81f85d26e950fa189">doPrintLocation</a> (const LVLocation *Location) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af959c06dc7fdb452d6e01fda5a8bdb87">doPrintScope</a> (const LVScope *Scope) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c00de0cb165c2b1614beed2ba93b0a6">doPrintSymbol</a> (const LVSymbol *Symbol) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a7055afc23cbe06ef5b9275bb3241d">doPrintType</a> (const LVType *Type) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a206e61e7cba8163e0d352952e5c1ce38">print</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0b147052132b017bbe8e90566947ab">printRecords</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d0643b6cad761f898aa581a6f763ac">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a41c1ff211e463932557ac5aa62f22d">addCompileUnitOffset</a> (LVOffset Offset, LVScopeCompileUnit *CompileUnit)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75cb2856d2563990ed489c38b63a5c3">createScopes</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b8fdf818581607c61a5b0bdd3bf5ed">createAlternativePath</a> (StringRef From)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8f1aeb4ef8575cbc64f67508effbbb2">printScopes</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaab12708cd80462767f21e03dae228f">printMatchedElements</a> (bool UseMatchedElements)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a064991d6ccde27d6f57caa0edd5b8377">sortScopes</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f63bc638a406df2ff7f596ef2abe67">createSplitFolder</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscoperoot">LVScopeRoot</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8db53bfaede35c8940fceb72b495aa">Root</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f89d9798f252c035000d6a03cb86300">InputFilename</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c36ab397c2a31a605e88a0a476ee9c">FileFormatName</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05c1edcb51769b9ed74087532906b12e">W</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b66787d42fd33ae1c2fe2c5fd7225c">OS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit">LVScopeCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd8bf25dbcb16ca9fa57ef73d062006">CompileUnit</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac33e886406f67bcea7a9e84d0e648bf3">DotTextSectionIndex</a> = <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a51919633e20f013bde3389c6db7fca2a">UndefinedSectionIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833c">LVBinaryType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d25e907ca4e4988957b0d92e3fc2649">BinaryType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsplitcontext">LVSplitContext</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0124c4576857c3dfb85e10ab35d96aa4">SplitContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LVCompileUnits</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15cdd7d160ee5e4e4b27170ac5cbccd7">CompileUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad04c501dd7f0cb888ae3e44b71be05e0">LVLines</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19dacab0131f3e7fb8c6b10540e2ecf7">Lines</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a5d77e75079f8249cc3e8681e6b2d8a18">LVScopes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ea2ee95947eb6243081591abfac97de">Scopes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a86d76ed6f92c1d16716bd39fadc6de5d">LVSymbols</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81e0c38426a17514cc3d44877ddf4307">Symbols</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#aef1328881e2236584b34de4050631e4b">LVTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb7611db25c8c291cb3dce109b64f71a">Types</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fddde6079870b9ca6d06becf14c8842">OutputSplit</a> = false</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader">LVReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f00af39c0390ab78b03370eb251266">getInstance</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab170f24e5d76fee6ae66e469f43564f3">setInstance</a> (LVReader *Reader)</td>
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

<p>The logical reader owns of all the logical elements created during the debug information parsing.</p>


<p>For its creation it uses a specific bump allocator for each type of logical element.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LVCompileUnits {#a4a7b25150e8d216ca4c8e76f303535da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVReader::LVCompileUnits =  std::map&lt;LVOffset, LVScopeCompileUnit *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LVReader() {#a3e8126edb83953e3574e3219f2699441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVReader::LVReader ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="#aa7f00af39c0390ab78b03370eb251266">getInstance</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ab90487a134bc2d94772898fa50e09896">llvm::logicalview::LVBinaryReader::LVBinaryReader</a>, <a href="#a6780a33f3a5ba4d163b2197418ec48ea">LVReader</a>, <a href="#a8936c821e1cbf6a17a9734e33dc3c464">operator=</a> and <a href="#ab170f24e5d76fee6ae66e469f43564f3">setInstance</a>.</p>

</div>
</div>

### LVReader() {#ab51b8f4c5562374eaa5c78328fb06866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVReader::LVReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputFilename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileFormatName, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833c">LVBinaryType</a> BinaryType=<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833cab50339a10e1de285ac99d4c3990b8693">LVBinaryType::NONE</a>)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="#a30c36ab397c2a31a605e88a0a476ee9c">FileFormatName</a>, <a href="#a8f89d9798f252c035000d6a03cb86300">InputFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833cab50339a10e1de285ac99d4c3990b8693">llvm::logicalview::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="#ae3b66787d42fd33ae1c2fe2c5fd7225c">OS</a> and <a href="#a05c1edcb51769b9ed74087532906b12e">W</a>.</p>

</div>
</div>

### LVReader() {#a6780a33f3a5ba4d163b2197418ec48ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVReader::LVReader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader">LVReader</a> &amp;)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#a3e8126edb83953e3574e3219f2699441">LVReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LVReader() {#a9979d510ae1d37d0e20c81f303d8b382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::logicalview::LVReader::~LVReader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a8936c821e1cbf6a17a9734e33dc3c464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVReader &amp; llvm::logicalview::LVReader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader">LVReader</a> &amp;)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#a3e8126edb83953e3574e3219f2699441">LVReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createOperation() {#ad06aaf2479ae6fe75fa6343470c9a8b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVOperation * llvm::logicalview::LVReader::createOperation (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ab9502425858a198bcbe9227a823f8aea">LVSmall</a> OpCode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a45b19aeb7105fd9f5f768b5e6787c837">LVUnsigned</a> &gt; Operands)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### doLoad() {#a8a15ec2eff468d1dc1137a8a8f20f525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReader::doLoad ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvpatterns/#a0a8ef488029bd1208eb4fc49054c7e20">llvm::logicalview::LVPatterns::addGenericPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvpatterns/#abf4651941d4b3e69dc692697901596b6">llvm::logicalview::LVPatterns::addOffsetPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp/#a4a4be4c21b1fd5b45a71fd7218bdae50">checkIntegrityScopesTree</a>, <a href="#af75cb2856d2563990ed489c38b63a5c3">createScopes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a49e9684d6b3ce0b3b3744a864c3212e6">llvm::logicalview::patterns</a>, <a href="#aca8db53bfaede35c8940fceb72b495aa">Root</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a>, <a href="#ab170f24e5d76fee6ae66e469f43564f3">setInstance</a>, <a href="#a064991d6ccde27d6f57caa0edd5b8377">sortScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvpatterns/#aa9a49f88eede80e9d9c90a692fb398d5">llvm::logicalview::LVPatterns::updateReportOptions</a>.</p>

</div>
</div>

### doPrint() {#ab6198458ec732d8dff12eb1a80049ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReader::doPrint ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="#adaab12708cd80462767f21e03dae228f">printMatchedElements</a>, <a href="#ae8f1aeb4ef8575cbc64f67508effbbb2">printScopes</a>, <a href="#ab170f24e5d76fee6ae66e469f43564f3">setInstance</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcompare/#a7dd02cee213cf5ed75d6589b4771bb1f">llvm::logicalview::LVCompare::execute</a>.</p>

</div>
</div>

### doPrintLine() {#a1d1f13f69ec0826e1aa53f5707b7b4b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVReader::doPrintLine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvline">LVLine</a> * Line)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a49e9684d6b3ce0b3b3744a864c3212e6">llvm::logicalview::patterns</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvpatterns/#a67df580d59aa917cb07161e9194c7cf2">llvm::logicalview::LVPatterns::printElement</a>.</p>

</div>
</div>

### doPrintLocation() {#a8b83ee7be20688c81f85d26e950fa189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVReader::doPrintLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlocation">LVLocation</a> * Location)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173ceface5bf551379459c1c61d2a204061c455">llvm::logicalview::Location</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a49e9684d6b3ce0b3b3744a864c3212e6">llvm::logicalview::patterns</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvpatterns/#a5f2b7e94a3ea85879282b71824fd8bf3">llvm::logicalview::LVPatterns::printObject</a>.</p>

</div>
</div>

### doPrintScope() {#af959c06dc7fdb452d6e01fda5a8bdb87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVReader::doPrintScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope)</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a49e9684d6b3ce0b3b3744a864c3212e6">llvm::logicalview::patterns</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvpatterns/#a67df580d59aa917cb07161e9194c7cf2">llvm::logicalview::LVPatterns::printElement</a>.</p>

</div>
</div>

### doPrintSymbol() {#a6c00de0cb165c2b1614beed2ba93b0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVReader::doPrintSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol">LVSymbol</a> * Symbol)</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a49e9684d6b3ce0b3b3744a864c3212e6">llvm::logicalview::patterns</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvpatterns/#a67df580d59aa917cb07161e9194c7cf2">llvm::logicalview::LVPatterns::printElement</a>.</p>

</div>
</div>

### doPrintType() {#ad3a7055afc23cbe06ef5b9275bb3241d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVReader::doPrintType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype">LVType</a> * Type)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a49e9684d6b3ce0b3b3744a864c3212e6">llvm::logicalview::patterns</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvpatterns/#a67df580d59aa917cb07161e9194c7cf2">llvm::logicalview::LVPatterns::printElement</a>.</p>

</div>
</div>

### dump() {#af4d0643b6cad761f898aa581a6f763ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReader::dump ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a206e61e7cba8163e0d352952e5c1ce38">print</a>.</p>

</div>
</div>

### getCompileUnit() {#ab63da9e640f8c75ac3ecdd69f5973958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScopeCompileUnit * llvm::logicalview::LVReader::getCompileUnit ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#aabd8bf25dbcb16ca9fa57ef73d062006">CompileUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a5caa751076636bb6406202e10ad062c7">llvm::logicalview::getReaderCompileUnit</a>.</p>

</div>
</div>

### getCompileUnitCPUType() {#a4dd83f4a260a18452465d5b20bde0f5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::CPUType llvm::logicalview::LVReader::getCompileUnitCPUType ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#aabd8bf25dbcb16ca9fa57ef73d062006">CompileUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#a50c7683b6e84562ebcc173bd25a76deb">llvm::logicalview::LVCodeViewReader::getRegisterName</a>.</p>

</div>
</div>

### getDotTextSectionIndex() {#a79e79d328c2a1364382c050f1edc3b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSectionIndex llvm::logicalview::LVReader::getDotTextSectionIndex ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#ac33e886406f67bcea7a9e84d0e648bf3">DotTextSectionIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymboltable/#a14c79bada6f31803a5aba019bcb7cf0e">llvm::logicalview::LVSymbolTable::getIndex</a>, <a href="#ac114092781e95d398899c7f2864ce714">getSectionIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymboltable/#ac8e5b75c69a12213b1af7ba626ce0773">llvm::logicalview::LVSymbolTable::update</a>.</p>

</div>
</div>

### getFileFormatName() {#a173b2c02cb716c1a72a382299247be61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::logicalview::LVReader::getFileFormatName ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#a30c36ab397c2a31a605e88a0a476ee9c">FileFormatName</a>.</p>

</div>
</div>

### getFilename() {#a6646a556e7732c3d1037047b4bb4ee7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef LVReader::getFilename (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject">LVObject</a> * Object, size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>Reference <a href="#aabd8bf25dbcb16ca9fa57ef73d062006">CompileUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aaa8cdab8c168315f16eabeca19e770aa">llvm::logicalview::LVElement::setFile</a>.</p>

</div>
</div>

### getFilename() {#a9cfe13a99c14005ccbf4e6b653713f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::logicalview::LVReader::getFilename ()</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#a8f89d9798f252c035000d6a03cb86300">InputFilename</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a> and <a href="#af75cb2856d2563990ed489c38b63a5c3">createScopes</a>.</p>

</div>
</div>

### getLines() {#a564c678b9c1f6e695345ada025a66fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LVLines &amp; llvm::logicalview::LVReader::getLines ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### getRegisterName() {#a4ba7d69a179758cfe95b692774eb95ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::logicalview::LVReader::getRegisterName (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ab9502425858a198bcbe9227a823f8aea">LVSmall</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Operands)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvoperation/#ab06697932d84361c7224356910300796">llvm::logicalview::LVOperation::getOperandsCodeViewInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvoperation/#a4c0878bb234ca16e88d593ceb27b5ede">llvm::logicalview::LVOperation::getOperandsDWARFInfo</a>.</p>

</div>
</div>

### getScopes() {#aaa02580d86cd6da9d4053e8c149d8bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LVScopes &amp; llvm::logicalview::LVReader::getScopes ()</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### getScopesRoot() {#ababa74ea6d8e9a9ce3088ab57c0c05ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScopeRoot * llvm::logicalview::LVReader::getScopesRoot ()</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#aca8db53bfaede35c8940fceb72b495aa">Root</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcompare/#a7dd02cee213cf5ed75d6589b4771bb1f">llvm::logicalview::LVCompare::execute</a>.</p>

</div>
</div>

### getSectionIndex() {#ac114092781e95d398899c7f2864ce714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual LVSectionIndex llvm::logicalview::LVReader::getSectionIndex (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#a79e79d328c2a1364382c050f1edc3b9f">getDotTextSectionIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aaf013089b3c23b831d93d1bd97440809">llvm::logicalview::LVElement::printLinkageName</a>.</p>

</div>
</div>

### getSplitContext() {#a8fb7fc2d1f1a253a711802569b1eb8d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSplitContext &amp; llvm::logicalview::LVReader::getSplitContext ()</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a903d88237af17c7f2d72fa2ca280e471">llvm::logicalview::getReaderSplitContext</a>.</p>

</div>
</div>

### getSymbols() {#a4bd721fd42c94e71fd18cc56f69c23f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LVSymbols &amp; llvm::logicalview::LVReader::getSymbols ()</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### getTypes() {#a304580d8cb7b13766ace495f2b06b669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LVTypes &amp; llvm::logicalview::LVReader::getTypes ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### isBinaryTypeCOFF() {#a73c06cb3a2d9d61ca64f3b6d1f21da50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVReader::isBinaryTypeCOFF ()</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833ca4fa2ac5353638195d4ce3bc48a5a9db7">llvm::logicalview::COFF</a>.</p>

</div>
</div>

### isBinaryTypeELF() {#a9820ed153363430133ad612fcc12ba24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVReader::isBinaryTypeELF ()</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833cab61b2d6c6fa62903b882aaa53452c111">llvm::logicalview::ELF</a>.</p>

</div>
</div>

### isBinaryTypeNone() {#a74ecb9e315e671cd9a27fbe0ff16aa60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVReader::isBinaryTypeNone ()</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833cab50339a10e1de285ac99d4c3990b8693">llvm::logicalview::NONE</a>.</p>

</div>
</div>

### isSystemEntry() {#a8d96f20ae76f4b4a0de2b0712d5fdfb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::logicalview::LVReader::isSystemEntry (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name={})</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/anonymous-lvcodeviewvisitor-cpp-/lvnamespacededuction/#a1eac8c1aa5d220e8fbba5871b15fb81d">llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVNamespaceDeduction::get</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopefunction/#a21efdb6ee2de55c5f8ee1956e14749c8">llvm::logicalview::LVScopeFunction::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a34d92f8e253ad8bb1bdb5e60f91c877d">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#afc9a506692070b035881b1d548c87965">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>.</p>

</div>
</div>

### notifyAddedElement() {#a47afac89aa48ca6a5c668780c2f1875d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReader::notifyAddedElement (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvline">LVLine</a> * Line)</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#a1736a13ffb4a43b3493f83fa5cf812d3">llvm::logicalview::LVScopeCompileUnit::addedElement</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#a0d1acd8c89a1529468823b4bfb207331">llvm::logicalview::LVScopeCompileUnit::addedElement</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#aa785acdf9dbf3052d70321ede3fecc42">llvm::logicalview::LVScopeCompileUnit::addedElement</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#a6e2ae538b86b26ca4d0d8242252bb9cb">llvm::logicalview::LVScopeCompileUnit::addedElement</a>.</p>

</div>
</div>

### notifyAddedElement() {#afb09fcfc3a072a252db0ec57b633567a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReader::notifyAddedElement (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope)</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>.</p>

</div>
</div>

### notifyAddedElement() {#a4c4b49aa764ec9304ac9477baf23534b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReader::notifyAddedElement (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol">LVSymbol</a> * Symbol)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>.</p>

</div>
</div>

### notifyAddedElement() {#a3a08d2b0039c19cc3c2c60d03bc648b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReader::notifyAddedElement (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype">LVType</a> * Type)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>.</p>

</div>
</div>

### outputStream() {#a4d0e7c1f6f2d4eebe51c777d93e32994}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::logicalview::LVReader::outputStream ()</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#ae3b66787d42fd33ae1c2fe2c5fd7225c">OS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#aaeb4ea25f6bc1bbccd544d48f199f7b5">llvm::logicalview::LVScope::doPrint</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscoperoot/#a6e726d8dda471e304170f6878ef09997">llvm::logicalview::LVScopeRoot::doPrintMatches</a>.</p>

</div>
</div>

### print() {#a206e61e7cba8163e0d352952e5c1ce38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVReader::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#ae3b66787d42fd33ae1c2fe2c5fd7225c">OS</a>.</p>


<p>Referenced by <a href="#af4d0643b6cad761f898aa581a6f763ac">dump</a>.</p>

</div>
</div>

### printRecords() {#afc0b147052132b017bbe8e90566947ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::logicalview::LVReader::printRecords (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#ae3b66787d42fd33ae1c2fe2c5fd7225c">OS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#aaeb4ea25f6bc1bbccd544d48f199f7b5">llvm::logicalview::LVScope::doPrint</a>.</p>

</div>
</div>

### setCompileUnit() {#acfef57e1f937ca038c926e972ffd0cef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReader::setCompileUnit (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aabd8bf25dbcb16ca9fa57ef73d062006">CompileUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#aaeb4ea25f6bc1bbccd544d48f199f7b5">llvm::logicalview::LVScope::doPrint</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscoperoot/#a6e726d8dda471e304170f6878ef09997">llvm::logicalview::LVScopeRoot::doPrintMatches</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcompare/#a7dd02cee213cf5ed75d6589b4771bb1f">llvm::logicalview::LVCompare::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit/#ae3ec47977d2c50e44e756c1709565c8b">llvm::logicalview::LVScopeCompileUnit::printSizes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscoperoot/#a1511bc822e4060a5e84ac7169aae4b4b">llvm::logicalview::LVScopeRoot::processRangeInformation</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a8f2af7d70b027caa4ae798eb16883b66">llvm::logicalview::LVScope::resolveElements</a>.</p>

</div>
</div>

### setCompileUnitCPUType() {#a81ca29eae6fd36123cdbbfe24f3f3bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReader::setCompileUnitCPUType (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3a314f44c015362563c5333db978173d">codeview::CPUType</a> Type)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Reference <a href="#aabd8bf25dbcb16ca9fa57ef73d062006">CompileUnit</a>.</p>

</div>
</div>

### setFilename() {#a716192d66503b8a150d3733eff9bed90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReader::setFilename (std::string Name)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="#a8f89d9798f252c035000d6a03cb86300">InputFilename</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addCompileUnitOffset() {#a1a41c1ff211e463932557ac5aa62f22d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVReader::addCompileUnitOffset (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a> Offset, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit">LVScopeCompileUnit</a> * CompileUnit)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="#aabd8bf25dbcb16ca9fa57ef73d062006">CompileUnit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefadfd0a82c4bf37b1e90b690a22a20692e">llvm::logicalview::Offset</a>.</p>

</div>
</div>

### createAlternativePath() {#a53b8fdf818581607c61a5b0bdd3bf5ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::logicalview::LVReader::createAlternativePath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> From)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa8749375717a95d086e49f655fa75046">llvm::sys::path::convert_to_slash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="#a8f89d9798f252c035000d6a03cb86300">InputFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa950616e5405e4ef51a87d384180e7aa1">llvm::sys::path::posix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa0f4137ed1502b5045d6083aa258b5c42">llvm::sys::path::windows</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>.</p>

</div>
</div>

### createScopes() {#af75cb2856d2563990ed489c38b63a5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::logicalview::LVReader::createScopes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>References <a href="#a30c36ab397c2a31a605e88a0a476ee9c">FileFormatName</a>, <a href="#a9cfe13a99c14005ccbf4e6b653713f0e">getFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="#aca8db53bfaede35c8940fceb72b495aa">Root</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#ab2b600452f45c702aaffaaeb6c4182c0">llvm::logicalview::LVCodeViewReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a> and <a href="#a8a15ec2eff468d1dc1137a8a8f20f525">doLoad</a>.</p>

</div>
</div>

### printMatchedElements() {#adaab12708cd80462767f21e03dae228f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReader::printMatchedElements (bool UseMatchedElements)</td>
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



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>References <a href="#ae3b66787d42fd33ae1c2fe2c5fd7225c">OS</a> and <a href="#aca8db53bfaede35c8940fceb72b495aa">Root</a>.</p>


<p>Referenced by <a href="#ab6198458ec732d8dff12eb1a80049ded">doPrint</a>.</p>

</div>
</div>

### printScopes() {#ae8f1aeb4ef8575cbc64f67508effbbb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReader::printScopes ()</td>
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



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="#ae3b66787d42fd33ae1c2fe2c5fd7225c">OS</a>, <a href="#aca8db53bfaede35c8940fceb72b495aa">Root</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ab6198458ec732d8dff12eb1a80049ded">doPrint</a>.</p>

</div>
</div>

### sortScopes() {#a064991d6ccde27d6f57caa0edd5b8377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::logicalview::LVReader::sortScopes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="#a8a15ec2eff468d1dc1137a8a8f20f525">doLoad</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createSplitFolder() {#ae0f63bc638a406df2ff7f596ef2abe67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVReader::createSplitFolder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CompileUnit {#aabd8bf25dbcb16ca9fa57ef73d062006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScopeCompileUnit* llvm::logicalview::LVReader::CompileUnit = nullptr</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="#a1a41c1ff211e463932557ac5aa62f22d">addCompileUnitOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#adf2a6238adfb3ada928de5340d5298b6">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ac378e86f9979cde149105568f10ee404">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>, <a href="#ab63da9e640f8c75ac3ecdd69f5973958">getCompileUnit</a>, <a href="#a4dd83f4a260a18452465d5b20bde0f5e">getCompileUnitCPUType</a>, <a href="#a6646a556e7732c3d1037047b4bb4ee7e">getFilename</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a873cd38481c3ed6a7e21bc016ec10ae2">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a65eee5509cce98dcc69693ea13bb9220">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="#acfef57e1f937ca038c926e972ffd0cef">setCompileUnit</a> and <a href="#a81ca29eae6fd36123cdbbfe24f3f3bba">setCompileUnitCPUType</a>.</p>

</div>
</div>

### DotTextSectionIndex {#ac33e886406f67bcea7a9e84d0e648bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSectionIndex llvm::logicalview::LVReader::DotTextSectionIndex = <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a51919633e20f013bde3389c6db7fca2a">UndefinedSectionIndex</a></td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="#a79e79d328c2a1364382c050f1edc3b9f">getDotTextSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a23627e0b6a1a860f08078cffc221b4b6">llvm::logicalview::LVBinaryReader::getSectionIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a8f648767e6fee704685f85355aa7fa64">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>.</p>

</div>
</div>

### FileFormatName {#a30c36ab397c2a31a605e88a0a476ee9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::logicalview::LVReader::FileFormatName</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#ab2b600452f45c702aaffaaeb6c4182c0">llvm::logicalview::LVCodeViewReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>, <a href="#af75cb2856d2563990ed489c38b63a5c3">createScopes</a>, <a href="#a173b2c02cb716c1a72a382299247be61">getFileFormatName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ab90487a134bc2d94772898fa50e09896">llvm::logicalview::LVBinaryReader::LVBinaryReader</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#a5a1bd6b089058360736e027da1171157">llvm::logicalview::LVCodeViewReader::LVCodeViewReader</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#aca7919065cf881851a0edff7ae9fbeb1">llvm::logicalview::LVCodeViewReader::LVCodeViewReader</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#aa5c941357b1a4565c7001065a68fb538">llvm::logicalview::LVDWARFReader::LVDWARFReader</a> and <a href="#ab51b8f4c5562374eaa5c78328fb06866">LVReader</a>.</p>

</div>
</div>

### InputFilename {#a8f89d9798f252c035000d6a03cb86300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::logicalview::LVReader::InputFilename</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="#a53b8fdf818581607c61a5b0bdd3bf5ed">createAlternativePath</a>, <a href="#a9cfe13a99c14005ccbf4e6b653713f0e">getFilename</a>, <a href="#ab51b8f4c5562374eaa5c78328fb06866">LVReader</a> and <a href="#a716192d66503b8a150d3733eff9bed90">setFilename</a>.</p>

</div>
</div>

### OS {#ae3b66787d42fd33ae1c2fe2c5fd7225c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::logicalview::LVReader::OS</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="#ab51b8f4c5562374eaa5c78328fb06866">LVReader</a>, <a href="#a4d0e7c1f6f2d4eebe51c777d93e32994">outputStream</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a740f19b6aaa166ffb6c29565ad8fc0ba">llvm::logicalview::LVBinaryReader::print</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#a233a5f5615d011f6fe8856c96ff9d66e">llvm::logicalview::LVCodeViewReader::print</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#a6085b16b5d9f99d6baafde6585f7ee89">llvm::logicalview::LVDWARFReader::print</a>, <a href="#a206e61e7cba8163e0d352952e5c1ce38">print</a>, <a href="#adaab12708cd80462767f21e03dae228f">printMatchedElements</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#a24a11dbf5d82a23a68332b1e320d5470">llvm::logicalview::LVCodeViewReader::printRecords</a>, <a href="#afc0b147052132b017bbe8e90566947ab">printRecords</a> and <a href="#ae8f1aeb4ef8575cbc64f67508effbbb2">printScopes</a>.</p>

</div>
</div>

### Root {#aca8db53bfaede35c8940fceb72b495aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScopeRoot* llvm::logicalview::LVReader::Root = nullptr</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#ab2b600452f45c702aaffaaeb6c4182c0">llvm::logicalview::LVCodeViewReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>, <a href="#af75cb2856d2563990ed489c38b63a5c3">createScopes</a>, <a href="#a8a15ec2eff468d1dc1137a8a8f20f525">doLoad</a>, <a href="#ababa74ea6d8e9a9ce3088ab57c0c05ec">getScopesRoot</a>, <a href="#adaab12708cd80462767f21e03dae228f">printMatchedElements</a>, <a href="#ae8f1aeb4ef8575cbc64f67508effbbb2">printScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#aff98f67d98b64c4ea5b3ed912838e83b">llvm::logicalview::LVCodeViewReader::sortScopes</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#a920a403e93a285632b45dc6a4e91218c">llvm::logicalview::LVDWARFReader::sortScopes</a>.</p>

</div>
</div>

### W {#a05c1edcb51769b9ed74087532906b12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedPrinter&amp; llvm::logicalview::LVReader::W</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#ab2b600452f45c702aaffaaeb6c4182c0">llvm::logicalview::LVCodeViewReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ab90487a134bc2d94772898fa50e09896">llvm::logicalview::LVBinaryReader::LVBinaryReader</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#a5a1bd6b089058360736e027da1171157">llvm::logicalview::LVCodeViewReader::LVCodeViewReader</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#aca7919065cf881851a0edff7ae9fbeb1">llvm::logicalview::LVCodeViewReader::LVCodeViewReader</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#aa5c941357b1a4565c7001065a68fb538">llvm::logicalview::LVDWARFReader::LVDWARFReader</a> and <a href="#ab51b8f4c5562374eaa5c78328fb06866">LVReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BinaryType {#a9d25e907ca4e4988957b0d92e3fc2649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVBinaryType llvm::logicalview::LVReader::BinaryType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### CompileUnits {#a15cdd7d160ee5e4e4b27170ac5cbccd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVCompileUnits llvm::logicalview::LVReader::CompileUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### Lines {#a19dacab0131f3e7fb8c6b10540e2ecf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVLines llvm::logicalview::LVReader::Lines</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### OutputSplit {#a8fddde6079870b9ca6d06becf14c8842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVReader::OutputSplit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### Scopes {#a0ea2ee95947eb6243081591abfac97de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScopes llvm::logicalview::LVReader::Scopes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### SplitContext {#a0124c4576857c3dfb85e10ab35d96aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSplitContext llvm::logicalview::LVReader::SplitContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### Symbols {#a81e0c38426a17514cc3d44877ddf4307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbols llvm::logicalview::LVReader::Symbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

### Types {#afb7611db25c8c291cb3dce109b64f71a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVTypes llvm::logicalview::LVReader::Types</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getInstance() {#aa7f00af39c0390ab78b03370eb251266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVReader &amp; LVReader::getInstance ()</td>
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



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp/#a08e17b013ab2110ffddcd384661f95de">CurrentReader</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a3e8126edb83953e3574e3219f2699441">LVReader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1c10e59416d98e95d2bc433fdb8273ab">llvm::logicalview::getReader</a>.</p>

</div>
</div>

### setInstance() {#ab170f24e5d76fee6ae66e469f43564f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVReader::setInstance (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader">LVReader</a> * Reader)</td>
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



<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp/#a08e17b013ab2110ffddcd384661f95de">CurrentReader</a> and <a href="#a3e8126edb83953e3574e3219f2699441">LVReader</a>.</p>


<p>Referenced by <a href="#a8a15ec2eff468d1dc1137a8a8f20f525">doLoad</a>, <a href="#ab6198458ec732d8dff12eb1a80049ded">doPrint</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcompare/#a7dd02cee213cf5ed75d6589b4771bb1f">llvm::logicalview::LVCompare::execute</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvreader-h">LVReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvreader-cpp">LVReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
