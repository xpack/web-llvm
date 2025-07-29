---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dibuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DIBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DIBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">llvm/IR/DIBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ac7630f0db651689bd561d7ab07ba3">DIBuilder</a> (Module &amp;M, bool AllowUnresolved=true, DICompileUnit *CU=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a builder for a module. <a href="#ac8ac7630f0db651689bd561d7ab07ba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c4484b7ba6a99b4f7ca7ffe5ef15b7">DIBuilder</a> (const DIBuilder &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a130980edd7814f02bcdd5ac6c2fbdb4e">operator=</a> (const DIBuilder &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a138b93205c71960aa94763a1081c50e9">finalize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct any deferred debug info descriptors. <a href="#a138b93205c71960aa94763a1081c50e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e5c0418b92861c5387f5f60b60ef614">finalizeSubprogram</a> (DISubprogram *SP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize a specific subprogram - no new variables may be added to this subprogram afterwards. <a href="#a2e5c0418b92861c5387f5f60b60ef614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f7af99f64b66e158b210e4433a1aed">createCompileUnit</a> (unsigned Lang, DIFile *File, StringRef Producer, bool isOptimized, StringRef Flags, unsigned RV, StringRef SplitName=StringRef(), DICompileUnit::DebugEmissionKind Kind=DICompileUnit::DebugEmissionKind::FullDebug, uint64_t DWOId=0, bool SplitDebugInlining=true, bool DebugInfoForProfiling=false, DICompileUnit::DebugNameTableKind NameTableKind=DICompileUnit::DebugNameTableKind::Default, bool RangesBaseAddress=false, StringRef SysRoot={}, StringRef SDK={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> provides an anchor for all debugging information generated during this instance of compilation. <a href="#a36f7af99f64b66e158b210e4433a1aed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac26b4f6298753fa1566e66758c9dbe">createFile</a> (StringRef Filename, StringRef Directory, std::optional&lt; DIFile::ChecksumInfo&lt; StringRef &gt; &gt; Checksum=std::nullopt, std::optional&lt; StringRef &gt; Source=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a file descriptor to hold debugging information for a file. <a href="#afac26b4f6298753fa1566e66758c9dbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dimacro">DIMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fe785a1cdccf63c091f5faf40f622ee">createMacro</a> (DIMacroFile *Parent, unsigned Line, unsigned MacroType, StringRef Name, StringRef Value=StringRef())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a macro. <a href="#a1fe785a1cdccf63c091f5faf40f622ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dimacrofile">DIMacroFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab435c6fadebc269d84de9b4747806a2f">createTempMacroFile</a> (DIMacroFile *Parent, unsigned Line, DIFile *File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information temporary entry for a macro file. <a href="#ab435c6fadebc269d84de9b4747806a2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dienumerator">DIEnumerator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac468b3d2f57aaac4935a7956509c785b">createEnumerator</a> (StringRef Name, const APSInt &amp;Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a single enumerator value. <a href="#ac468b3d2f57aaac4935a7956509c785b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dienumerator">DIEnumerator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27c9b02989f2380d2e3a2fffe6a9672b">createEnumerator</a> (StringRef Name, uint64_t Val, bool IsUnsigned=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef273038c3745ae3c1e9b6c01ce1e100">createUnspecifiedType</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a DWARF unspecified type. <a href="#aef273038c3745ae3c1e9b6c01ce1e100">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c6964fb822f5491b18b38e5facbc49c">createNullPtrType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create C++11 nullptr type. <a href="#a7c6964fb822f5491b18b38e5facbc49c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a54c168f44523926f5bcf1f69e3cb4">createBasicType</a> (StringRef Name, uint64_t SizeInBits, unsigned Encoding, DINode::DIFlags Flags=DINode::FlagZero, uint32_t NumExtraInhabitants=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a basic type. <a href="#aa7a54c168f44523926f5bcf1f69e3cb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5153d3ea2754b6b7fa554daecdf4ea5d">createStringType</a> (StringRef Name, uint64_t SizeInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a string type. <a href="#a5153d3ea2754b6b7fa554daecdf4ea5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed4d9ff2d7f4bc923175f432a0209ef">createStringType</a> (StringRef Name, DIVariable *StringLength, DIExpression *StrLocationExp=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Fortran assumed length string type. <a href="#a9ed4d9ff2d7f4bc923175f432a0209ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bcb4de1da083a08f344d6454b4a4b9e">createStringType</a> (StringRef Name, DIExpression *StringLengthExp, DIExpression *StrLocationExp=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Fortran assumed length string type. <a href="#a2bcb4de1da083a08f344d6454b4a4b9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35d8232846c9e46b1db929daff2bf477">createQualifiedType</a> (unsigned Tag, DIType *FromTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a qualified type, e.g. <a href="#a35d8232846c9e46b1db929daff2bf477">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f163bf8a14c1c7823f6d8fce7fb5ac7">createPointerType</a> (DIType *PointeeTy, uint64_t SizeInBits, uint32_t AlignInBits=0, std::optional&lt; unsigned &gt; DWARFAddressSpace=std::nullopt, StringRef Name="", DINodeArray Annotations=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a pointer. <a href="#a8f163bf8a14c1c7823f6d8fce7fb5ac7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51c008ee3bacaaed30e6a2cfac0268b">createPtrAuthQualifiedType</a> (DIType *FromTy, unsigned Key, bool IsAddressDiscriminated, unsigned ExtraDiscriminator, bool IsaPointer, bool authenticatesNullValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a __ptrauth qualifier. <a href="#ad51c008ee3bacaaed30e6a2cfac0268b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82c0e7e3bb9354afd71d7edbc19f48a">createMemberPointerType</a> (DIType *PointeeTy, DIType *Class, uint64_t SizeInBits, uint32_t AlignInBits=0, DINode::DIFlags Flags=DINode::FlagZero)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a pointer to member. <a href="#ab82c0e7e3bb9354afd71d7edbc19f48a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1b53df8ec7e16b15d8d72c50c9d7448">createReferenceType</a> (unsigned Tag, DIType *RTy, uint64_t SizeInBits=0, uint32_t AlignInBits=0, std::optional&lt; unsigned &gt; DWARFAddressSpace=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a c++ style reference or rvalue reference type. <a href="#ab1b53df8ec7e16b15d8d72c50c9d7448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d9a1f42764491af27b361ae59c694b1">createTypedef</a> (DIType *Ty, StringRef Name, DIFile *File, unsigned LineNo, DIScope *Context, uint32_t AlignInBits=0, DINode::DIFlags Flags=DINode::FlagZero, DINodeArray Annotations=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a typedef. <a href="#a0d9a1f42764491af27b361ae59c694b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88e594333479ba5f47d695a163a72846">createTemplateAlias</a> (DIType *Ty, StringRef Name, DIFile *File, unsigned LineNo, DIScope *Context, DINodeArray TParams, uint32_t AlignInBits=0, DINode::DIFlags Flags=DINode::FlagZero, DINodeArray Annotations=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a template alias. <a href="#a88e594333479ba5f47d695a163a72846">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d1c90a73404dc6a9eeb8d9206aa8b23">createFriend</a> (DIType *Ty, DIType *FriendTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a 'friend'. <a href="#a7d1c90a73404dc6a9eeb8d9206aa8b23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2236a7be2d15db19f575591000670c9c">createInheritance</a> (DIType *Ty, DIType *BaseTy, uint64_t BaseOffset, uint32_t VBPtrOffset, DINode::DIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry to establish inheritance relationship between two types. <a href="#a2236a7be2d15db19f575591000670c9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf77460ca5103d4d0b2708b013a1b88">createMemberType</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, DINode::DIFlags Flags, DIType *Ty, DINodeArray Annotations=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a member. <a href="#adbf77460ca5103d4d0b2708b013a1b88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24655d8cf9e92a91d8b51101f64553c5">createVariantMemberType</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, Constant *Discriminant, DINode::DIFlags Flags, DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a variant. <a href="#a24655d8cf9e92a91d8b51101f64553c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b8b82d8ef44a362f7be889d56121944">createBitFieldMemberType</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNo, uint64_t SizeInBits, uint64_t OffsetInBits, uint64_t StorageOffsetInBits, DINode::DIFlags Flags, DIType *Ty, DINodeArray Annotations=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a bit field member. <a href="#a0b8b82d8ef44a362f7be889d56121944">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23995c2ddd74a9abcc31d939e0643779">createStaticMemberType</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNo, DIType *Ty, DINode::DIFlags Flags, Constant *Val, unsigned Tag, uint32_t AlignInBits=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a C++ static data member. <a href="#a23995c2ddd74a9abcc31d939e0643779">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b7af05053d96eafcdd3e06b41ba6749">createObjCIVar</a> (StringRef Name, DIFile *File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, DINode::DIFlags Flags, DIType *Ty, MDNode *PropertyNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Objective-C instance variable. <a href="#a3b7af05053d96eafcdd3e06b41ba6749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diobjcproperty">DIObjCProperty</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1f0e54c22f59c0ca1b03fa355cbdde8">createObjCProperty</a> (StringRef Name, DIFile *File, unsigned LineNumber, StringRef GetterName, StringRef SetterName, unsigned PropertyAttributes, DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Objective-C property. <a href="#af1f0e54c22f59c0ca1b03fa355cbdde8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280c57f61faff3e28571c62b3e4558e2">createClassType</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, DINode::DIFlags Flags, DIType *DerivedFrom, DINodeArray Elements, unsigned RunTimeLang=0, DIType *VTableHolder=nullptr, MDNode *TemplateParms=nullptr, StringRef UniqueIdentifier="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a class. <a href="#a280c57f61faff3e28571c62b3e4558e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe762b489a1c62e1d3baf58b330e6652">createStructType</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, DINode::DIFlags Flags, DIType *DerivedFrom, DINodeArray Elements, unsigned RunTimeLang=0, DIType *VTableHolder=nullptr, StringRef UniqueIdentifier="", DIType *Specification=nullptr, uint32_t NumExtraInhabitants=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a struct. <a href="#afe762b489a1c62e1d3baf58b330e6652">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d7a72e4269b08b6a786c6950c014bc4">createUnionType</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, DINode::DIFlags Flags, DINodeArray Elements, unsigned RunTimeLang=0, StringRef UniqueIdentifier="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an union. <a href="#a5d7a72e4269b08b6a786c6950c014bc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99e6c0300816ba0fd1ebbc4a8cbd3da">createVariantPart</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, DINode::DIFlags Flags, DIDerivedType *Discriminator, DINodeArray Elements, StringRef UniqueIdentifier="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a variant part. <a href="#ad99e6c0300816ba0fd1ebbc4a8cbd3da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditemplatetypeparameter">DITemplateTypeParameter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac74a0301ef623b8694f6ba75b9bf62af">createTemplateTypeParameter</a> (DIScope *Scope, StringRef Name, DIType *Ty, bool IsDefault)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information for template type parameter. <a href="#ac74a0301ef623b8694f6ba75b9bf62af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditemplatevalueparameter">DITemplateValueParameter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7403e1a803ce258b0087e5faef340d7">createTemplateValueParameter</a> (DIScope *Scope, StringRef Name, DIType *Ty, bool IsDefault, Constant *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information for template value parameter. <a href="#af7403e1a803ce258b0087e5faef340d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditemplatevalueparameter">DITemplateValueParameter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093b77c3612cbef1a9b29e680006f982">createTemplateTemplateParameter</a> (DIScope *Scope, StringRef Name, DIType *Ty, StringRef Val, bool IsDefault=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information for a template template parameter. <a href="#a093b77c3612cbef1a9b29e680006f982">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditemplatevalueparameter">DITemplateValueParameter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9282142c56014690597e4209fa3c4725">createTemplateParameterPack</a> (DIScope *Scope, StringRef Name, DIType *Ty, DINodeArray Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information for a template parameter pack. <a href="#a9282142c56014690597e4209fa3c4725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6cf034bd9dd454892e193bc3340998b">createArrayType</a> (uint64_t Size, uint32_t AlignInBits, DIType *Ty, DINodeArray Subscripts, PointerUnion&lt; DIExpression *, DIVariable * &gt; DataLocation=nullptr, PointerUnion&lt; DIExpression *, DIVariable * &gt; Associated=nullptr, PointerUnion&lt; DIExpression *, DIVariable * &gt; Allocated=nullptr, PointerUnion&lt; DIExpression *, DIVariable * &gt; Rank=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an array. <a href="#ab6cf034bd9dd454892e193bc3340998b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef92fe78919116804d90d9acfb98754">createVectorType</a> (uint64_t Size, uint32_t AlignInBits, DIType *Ty, DINodeArray Subscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a vector type. <a href="#a3ef92fe78919116804d90d9acfb98754">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28497d68ae2a721d43823c87919cfac5">createEnumerationType</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, DINodeArray Elements, DIType *UnderlyingType, unsigned RunTimeLang=0, StringRef UniqueIdentifier="", bool IsScoped=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an enumeration. <a href="#a28497d68ae2a721d43823c87919cfac5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7327bb62e5803d0eb1f8239d4d4509a9">createSetType</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a set. <a href="#a7327bb62e5803d0eb1f8239d4d4509a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1930fd092560cf172fb618ba55263ec7">createSubroutineType</a> (DITypeRefArray ParameterTypes, DINode::DIFlags Flags=DINode::FlagZero, unsigned CC=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create subroutine type. <a href="#a1930fd092560cf172fb618ba55263ec7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b51afb7d6bdbb81b30eb5e121c1efb">createForwardDecl</a> (unsigned Tag, StringRef Name, DIScope *Scope, DIFile *F, unsigned Line, unsigned RuntimeLang=0, uint64_t SizeInBits=0, uint32_t AlignInBits=0, StringRef UniqueIdentifier="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a permanent forward-declared type. <a href="#af5b51afb7d6bdbb81b30eb5e121c1efb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47dddfcbfe0d635de4712fad2e7f900">createReplaceableCompositeType</a> (unsigned Tag, StringRef Name, DIScope *Scope, DIFile *F, unsigned Line, unsigned RuntimeLang=0, uint64_t SizeInBits=0, uint32_t AlignInBits=0, DINode::DIFlags Flags=DINode::FlagFwdDecl, StringRef UniqueIdentifier="", DINodeArray Annotations=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a temporary forward-declared type. <a href="#ad47dddfcbfe0d635de4712fad2e7f900">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852f95fcd7c86fbd6517811f37108351">retainType</a> (DIScope *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retain DIScope* in a module even if it is not referenced through debug info anchors. <a href="#a852f95fcd7c86fbd6517811f37108351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a044f53a8c7873a1426602c69594bb679">createUnspecifiedParameter</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create unspecified parameter type for a subroutine type. <a href="#a044f53a8c7873a1426602c69594bb679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DINodeArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac22bd3a0571eb4e961def1c480247296">getOrCreateArray</a> (ArrayRef&lt; Metadata * &gt; Elements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a DINodeArray, create one if required. <a href="#ac22bd3a0571eb4e961def1c480247296">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DIMacroNodeArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65906c0586aeaa1831125ddeeaa7aa7a">getOrCreateMacroArray</a> (ArrayRef&lt; Metadata * &gt; Elements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a DIMacroNodeArray, create one if required. <a href="#a65906c0586aeaa1831125ddeeaa7aa7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dityperefarray">DITypeRefArray</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf27ce323516bd289ce53d2e241581fc">getOrCreateTypeArray</a> (ArrayRef&lt; Metadata * &gt; Elements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/dityperefarray">DITypeRefArray</a>, create one if required. <a href="#abf27ce323516bd289ce53d2e241581fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubrange">DISubrange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaec462f93a64e27fa16d1416b1dbbb8b">getOrCreateSubrange</a> (int64_t Lo, int64_t Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a value range. <a href="#aaec462f93a64e27fa16d1416b1dbbb8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubrange">DISubrange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0488e45d72dfdd3c9f1b7780fc812675">getOrCreateSubrange</a> (int64_t Lo, Metadata *CountNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubrange">DISubrange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3656fa387ece7e6b1d3511da750743bd">getOrCreateSubrange</a> (Metadata *Count, Metadata *LowerBound, Metadata *UpperBound, Metadata *Stride)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/digenericsubrange">DIGenericSubrange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaef4f4223cd89524ff85e199545f57c">getOrCreateGenericSubrange</a> (DIGenericSubrange::BoundType Count, DIGenericSubrange::BoundType LowerBound, DIGenericSubrange::BoundType UpperBound, DIGenericSubrange::BoundType Stride)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb4bcf5ce38d7b765c6f915f66f4bcf">createGlobalVariableExpression</a> (DIScope *Context, StringRef Name, StringRef LinkageName, DIFile *File, unsigned LineNo, DIType *Ty, bool IsLocalToUnit, bool isDefined=true, DIExpression *Expr=nullptr, MDNode *Decl=nullptr, MDTuple *TemplateParams=nullptr, uint32_t AlignInBits=0, DINodeArray Annotations=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable. <a href="#a9cb4bcf5ce38d7b765c6f915f66f4bcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0836d7f22fd1d8bd8d2fd97da17bc9ba">createTempGlobalVariableFwdDecl</a> (DIScope *Context, StringRef Name, StringRef LinkageName, DIFile *File, unsigned LineNo, DIType *Ty, bool IsLocalToUnit, MDNode *Decl=nullptr, MDTuple *TemplateParams=nullptr, uint32_t AlignInBits=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identical to createGlobalVariable except that the resulting DbgNode is temporary and meant to be RAUWed. <a href="#a0836d7f22fd1d8bd8d2fd97da17bc9ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6081972b0560d0f16bd503654924b1b">createAutoVariable</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNo, DIType *Ty, bool AlwaysPreserve=false, DINode::DIFlags Flags=DINode::FlagZero, uint32_t AlignInBits=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for an auto variable. <a href="#ae6081972b0560d0f16bd503654924b1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c600597532d3123b025c387d90aa7df">createLabel</a> (DIScope *Scope, StringRef Name, DIFile *File, unsigned LineNo, bool AlwaysPreserve=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for an label. <a href="#a4c600597532d3123b025c387d90aa7df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa7c4efcb5c40c8527c13759f10ef5ed">createParameterVariable</a> (DIScope *Scope, StringRef Name, unsigned ArgNo, DIFile *File, unsigned LineNo, DIType *Ty, bool AlwaysPreserve=false, DINode::DIFlags Flags=DINode::FlagZero, DINodeArray Annotations=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a parameter variable. <a href="#afa7c4efcb5c40c8527c13759f10ef5ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d53e81b2b3ddcc4518e816fc89711d">createExpression</a> (ArrayRef&lt; uint64_t &gt; Addr={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable which has a complex address expression for its address. <a href="#ad1d53e81b2b3ddcc4518e816fc89711d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a783740c21f25f5600065aca639a66936">createConstantValueExpression</a> (uint64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an expression for a variable that does not have an address, but does have a constant value. <a href="#a783740c21f25f5600065aca639a66936">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d91109bab556ea565fe8dd35f1d30c">createFunction</a> (DIScope *Scope, StringRef Name, StringRef LinkageName, DIFile *File, unsigned LineNo, DISubroutineType *Ty, unsigned ScopeLine, DINode::DIFlags Flags=DINode::FlagZero, DISubprogram::DISPFlags SPFlags=DISubprogram::SPFlagZero, DITemplateParameterArray TParams=nullptr, DISubprogram *Decl=nullptr, DITypeArray ThrownTypes=nullptr, DINodeArray Annotations=nullptr, StringRef TargetFuncName="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified subprogram. <a href="#a57d91109bab556ea565fe8dd35f1d30c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae4713be3cb6c59e31f8e83d02ee7e3">createTempFunctionFwdDecl</a> (DIScope *Scope, StringRef Name, StringRef LinkageName, DIFile *File, unsigned LineNo, DISubroutineType *Ty, unsigned ScopeLine, DINode::DIFlags Flags=DINode::FlagZero, DISubprogram::DISPFlags SPFlags=DISubprogram::SPFlagZero, DITemplateParameterArray TParams=nullptr, DISubprogram *Decl=nullptr, DITypeArray ThrownTypes=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identical to createFunction, except that the resulting DbgNode is meant to be RAUWed. <a href="#a3ae4713be3cb6c59e31f8e83d02ee7e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab37a47c83ecb05b68a904e49a7f69f68">createMethod</a> (DIScope *Scope, StringRef Name, StringRef LinkageName, DIFile *File, unsigned LineNo, DISubroutineType *Ty, unsigned VTableIndex=0, int ThisAdjustment=0, DIType *VTableHolder=nullptr, DINode::DIFlags Flags=DINode::FlagZero, DISubprogram::DISPFlags SPFlags=DISubprogram::SPFlagZero, DITemplateParameterArray TParams=nullptr, DITypeArray ThrownTypes=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified C++ method. <a href="#ab37a47c83ecb05b68a904e49a7f69f68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicommonblock">DICommonBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cec597df7f95486c2db2f888d45ad85">createCommonBlock</a> (DIScope *Scope, DIGlobalVariable *decl, StringRef Name, DIFile *File, unsigned LineNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create common block entry for a Fortran common block. <a href="#a7cec597df7f95486c2db2f888d45ad85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dinamespace">DINamespace</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fec0fd637f104b5c3cab3ffdbe3b3aa">createNameSpace</a> (DIScope *Scope, StringRef Name, bool ExportSymbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This creates new descriptor for a namespace with the specified parent scope. <a href="#a4fec0fd637f104b5c3cab3ffdbe3b3aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dimodule">DIModule</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affeea0b69c510392c5015ea861393738">createModule</a> (DIScope *Scope, StringRef Name, StringRef ConfigurationMacros, StringRef IncludePath, StringRef APINotesFile={}, DIFile *File=nullptr, unsigned LineNo=0, bool IsDecl=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This creates new descriptor for a module with the specified parent scope. <a href="#affeea0b69c510392c5015ea861393738">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile">DILexicalBlockFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a715aa3a14c857ca33f84affd4e01a9">createLexicalBlockFile</a> (DIScope *Scope, DIFile *File, unsigned Discriminator=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This creates a descriptor for a lexical block with a new file attached. <a href="#a2a715aa3a14c857ca33f84affd4e01a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9cc4f1d1803b0b793267544900a44f">createLexicalBlock</a> (DIScope *Scope, DIFile *File, unsigned Line, unsigned Col)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This creates a descriptor for a lexical block with the specified parent context. <a href="#a5b9cc4f1d1803b0b793267544900a44f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf1ad638dccc0e0dfc111d3b9dbc494">createImportedModule</a> (DIScope *Context, DINamespace *NS, DIFile *File, unsigned Line, DINodeArray Elements=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported module. <a href="#adaf1ad638dccc0e0dfc111d3b9dbc494">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2298c4b86797583b1e58b873c2f821bc">createImportedModule</a> (DIScope *Context, DIImportedEntity *NS, DIFile *File, unsigned Line, DINodeArray Elements=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported module. <a href="#a2298c4b86797583b1e58b873c2f821bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbed914ff7d389793f04bf2fc8e33ef5">createImportedModule</a> (DIScope *Context, DIModule *M, DIFile *File, unsigned Line, DINodeArray Elements=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported module. <a href="#adbed914ff7d389793f04bf2fc8e33ef5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae19d8948863925e5e9baf877da432322">createImportedDeclaration</a> (DIScope *Context, DINode *Decl, DIFile *File, unsigned Line, StringRef Name="", DINodeArray Elements=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported function. <a href="#ae19d8948863925e5e9baf877da432322">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae590e0c860e4c1fb30629dfecac4bd58">DbgInstPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9019e662ee1c0c04e06e9871650268c8">insertDeclare</a> (llvm::Value *Storage, DILocalVariable *VarInfo, DIExpression *Expr, const DILocation *DL, BasicBlock *InsertAtEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.declare intrinsic call. <a href="#a9019e662ee1c0c04e06e9871650268c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae590e0c860e4c1fb30629dfecac4bd58">DbgInstPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a6937fcd639ac78a93b48ab6624e957">insertDbgAssign</a> (Instruction *LinkedInstr, Value *Val, DILocalVariable *SrcVar, DIExpression *ValExpr, Value *Addr, DIExpression *AddrExpr, const DILocation *DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.assign intrinsic call. <a href="#a5a6937fcd639ac78a93b48ab6624e957">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae590e0c860e4c1fb30629dfecac4bd58">DbgInstPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a214637beca449d58d4313a69a9ba32af">insertDeclare</a> (llvm::Value *Storage, DILocalVariable *VarInfo, DIExpression *Expr, const DILocation *DL, InsertPosition InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.declare intrinsic call. <a href="#a214637beca449d58d4313a69a9ba32af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae590e0c860e4c1fb30629dfecac4bd58">DbgInstPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb6aff41bfe64d206d563112993cfb01">insertLabel</a> (DILabel *LabelInfo, const DILocation *DL, InsertPosition InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.label intrinsic call. <a href="#adb6aff41bfe64d206d563112993cfb01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae590e0c860e4c1fb30629dfecac4bd58">DbgInstPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915a8d23e084b7a40475a3ce2245495b">insertDbgValueIntrinsic</a> (llvm::Value *Val, DILocalVariable *VarInfo, DIExpression *Expr, const DILocation *DL, InsertPosition InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.value intrinsic call. <a href="#a915a8d23e084b7a40475a3ce2245495b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a736aced5bb739ef4976f57e0bc58ae22">replaceVTableHolder</a> (DICompositeType *&amp;T, DIType *VTableHolder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the vtable holder in the given type. <a href="#a736aced5bb739ef4976f57e0bc58ae22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee05194feacd4f95209e840e7242332">replaceArrays</a> (DICompositeType *&amp;T, DINodeArray Elements, DINodeArray TParams=DINodeArray())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace arrays on a composite type. <a href="#afee05194feacd4f95209e840e7242332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0cfa048f7096ffb7b085d2d5d1a399ba">replaceTemporary</a> (TempMDNode &amp;&amp;N, NodeTy *Replacement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace a temporary node. <a href="#a0cfa048f7096ffb7b085d2d5d1a399ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab7d60c6b793b2096fe776f564c761cf">getImportTrackingVector</a> (const DIScope *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d969f5be07110b801d641d3ad41838">getSubprogramNodesTrackingVector</a> (const DIScope *S)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d5cbbc5ebe7a2bc0e03e26b107decf2">trackIfUnresolved</a> (MDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a temporary. <a href="#a3d5cbbc5ebe7a2bc0e03e26b107decf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d97b977568094ddc59082a15e7ca89">insertDbgVariableRecord</a> (DbgVariableRecord *DVR, InsertPosition InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Internal helper. Track metadata if untracked and insert <span class="doxyComputerOutput">DVR</span>. <a href="#a26d97b977568094ddc59082a15e7ca89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c4cbaef84a1113e18f489710ee13aff">insertDbgIntrinsic</a> (llvm::Function *Intrinsic, llvm::Value *Val, DILocalVariable *VarInfo, DIExpression *Expr, const DILocation *DL, InsertPosition InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Internal helper with common code used by insertDbg{<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>,Addr}<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic">Intrinsic</a>. <a href="#a8c4cbaef84a1113e18f489710ee13aff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ce6b0bbbc33d704e5668293ff50385">M</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2733c6588f0ef5dd7374a3999bc427f3">VMContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6889b9d2493882bb03df260d9913e0c">CUNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The one compile unit created by this DIBuiler. <a href="#af6889b9d2493882bb03df260d9913e0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477ccb1f9c93d7e6c129fd85015a2930">DeclareFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>llvm.dbg.declare <a href="#a477ccb1f9c93d7e6c129fd85015a2930">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade84addd36b6666e149657bc1e21c54f">ValueFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>llvm.dbg.value <a href="#ade84addd36b6666e149657bc1e21c54f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c218ec6fef9d6b9e20230d29dd9ae5">LabelFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>llvm.dbg.label <a href="#ab7c218ec6fef9d6b9e20230d29dd9ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3171eb9bda03334360141385e19ae29f">AssignFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>llvm.dbg.assign <a href="#a3171eb9bda03334360141385e19ae29f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4b11a4c02371143a29044600a1f9e1">AllEnumTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f91221e356f6dbf453a4108a1c9aa2b">AllRetainTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track the RetainTypes, since they can be updated later on. <a href="#a4f91221e356f6dbf453a4108a1c9aa2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e01e226a5989dc3fbf4e8e8dbf39176">AllSubprograms</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321782416aad2cd4b66e31aea0e2087d">AllGVs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf9521fac87cfbdde3827169dbd524f">ImportedModules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9bac72f37773a7815606b596104b52b">AllMacrosPerParent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map Macro parent (which can be <a href="/web-llvm/docs/api/classes/llvm/dimacrofile">DIMacroFile</a> or nullptr) to a list of <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> all of type <a href="/web-llvm/docs/api/classes/llvm/dimacronode">DIMacroNode</a>. <a href="#af9bac72f37773a7815606b596104b52b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da65395deaaf40cfb4edc588d0611ff">UnresolvedNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track nodes that may be unresolved. <a href="#a2da65395deaaf40cfb4edc588d0611ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db0f0bbf1547cf061f08b6d03178344">AllowUnresolvedNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a>, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e88336f08013ed870e78405f17567f">SubprogramTrackedNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Each subprogram's preserved local variables, labels and imported entities. <a href="#ad5e88336f08013ed870e78405f17567f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae861fa6520a5b626bbc07dab42ff8005">createArtificialSubprogram</a> (DISubprogram *SP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a distinct clone of <span class="doxyComputerOutput">SP</span> with FlagArtificial set. <a href="#ae861fa6520a5b626bbc07dab42ff8005">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bc8816adbffd7e286400bb7367058d6">createArtificialType</a> (DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a uniqued clone of <span class="doxyComputerOutput">Ty</span> with FlagArtificial set. <a href="#a3bc8816adbffd7e286400bb7367058d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0061aafefff3c780f2b55c3772d94c3c">createObjectPointerType</a> (DIType *Ty, bool Implicit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a uniqued clone of <span class="doxyComputerOutput">Ty</span> with FlagObjectPointer set. <a href="#a0061aafefff3c780f2b55c3772d94c3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DIBuilder() {#ac8ac7630f0db651689bd561d7ab07ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBuilder::DIBuilder (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, bool AllowUnresolved=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * CU=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a builder for a module.</p>


<p>If <span class="doxyComputerOutput">AllowUnresolved</span>, collect unresolved nodes attached to the module in order to resolve cycles during <em><a href="#a138b93205c71960aa94763a1081c50e9">finalize()</a></em>.</p>


<p>If <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/cu">CU</a></span> is given a value other than nullptr, then set <span class="doxyComputerOutput">CUNode</span> to <a href="/web-llvm/docs/api/namespaces/cu">CU</a>.</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a89c4484b7ba6a99b4f7ca7ffe5ef15b7">DIBuilder</a> and <a href="#a130980edd7814f02bcdd5ac6c2fbdb4e">operator=</a>.</p>

</div>
</div>

### DIBuilder() {#a89c4484b7ba6a99b4f7ca7ffe5ef15b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIBuilder::DIBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp;)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>


<p>Reference <a href="#ac8ac7630f0db651689bd561d7ab07ba3">DIBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a130980edd7814f02bcdd5ac6c2fbdb4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBuilder &amp; llvm::DIBuilder::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp;)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01a7a1920d61156abc05a60135aefe8bc67">llvm::DICompileUnit::Default</a>, <a href="#ac8ac7630f0db651689bd561d7ab07ba3">DIBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66daa44087d1fe20ab5e128a0f592b6a85c1">llvm::DICompileUnit::FullDebug</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createArrayType() {#ab6cf034bd9dd454892e193bc3340998b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DIBuilder::createArrayType (uint64_t Size, uint32_t AlignInBits, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, DINodeArray Subscripts, <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *, <a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> * &gt; DataLocation=nullptr, <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *, <a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> * &gt; Associated=nullptr, <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *, <a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> * &gt; Allocated=nullptr, <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *, <a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> * &gt; Rank=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for an array.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Array size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Element type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Subscripts</td>
<td class="doxyParamItemDescription"><p>Subscripts.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DataLocation</td>
<td class="doxyParamItemDescription"><p>The location of the raw data of a descriptor-based Fortran array, either a DIExpression* or a DIVariable*.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Associated</td>
<td class="doxyParamItemDescription"><p>The associated attribute of a descriptor-based Fortran array, either a DIExpression* or a DIVariable*.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Allocated</td>
<td class="doxyParamItemDescription"><p>The allocated attribute of a descriptor-based Fortran array, either a DIExpression* or a DIVariable*.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Rank</td>
<td class="doxyParamItemDescription"><p>The rank attribute of a descriptor-based Fortran array, either a DIExpression* or a DIVariable*.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### createAutoVariable() {#ae6081972b0560d0f16bd503654924b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalVariable * DIBuilder::createAutoVariable (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, bool AlwaysPreserve=false, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero, uint32_t AlignInBits=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for an auto variable.</p>


<p>This is a local variable that is not a subprogram parameter.</p>


<p><span class="doxyComputerOutput">Scope</span> must be a <em><a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a></em>, and thus its scope chain eventually leads to a <em><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a></em>.</p>


<p>If <span class="doxyComputerOutput">AlwaysPreserve</span>, this variable will be referenced from its containing subprogram, and will survive some optimizations.</p>


<p>Declaration at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a08ad252830f022d82e560f5447107d07">createLocalVariable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>.</p>

</div>
</div>

### createBasicType() {#aa7a54c168f44523926f5bcf1f69e3cb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBasicType * DIBuilder::createBasicType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t SizeInBits, unsigned Encoding, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero, uint32_t NumExtraInhabitants=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a basic type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Size of the type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Encoding</td>
<td class="doxyParamItemDescription"><p>DWARF encoding code, e.g., dwarf::DW_ATE_float.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Optional DWARF attributes, e.g., DW_AT_endianity.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumExtraInhabitants</td>
<td class="doxyParamItemDescription"><p>The number of extra inhabitants of the type. An extra inhabitant is a bit pattern that does not represent a valid value for instances of a given type. This is used by the Swift language.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### createBitFieldMemberType() {#a0b8b82d8ef44a362f7be889d56121944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createBitFieldMemberType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, uint64_t SizeInBits, uint64_t OffsetInBits, uint64_t StorageOffsetInBits, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, DINodeArray Annotations=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a bit field member.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Member scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StorageOffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member storage offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parent type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/annotations"&gt;Annotations&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Member annotations.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createClassType() {#a280c57f61faff3e28571c62b3e4558e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DIBuilder::createClassType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * DerivedFrom, DINodeArray Elements, unsigned RunTimeLang=0, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * VTableHolder=nullptr, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * TemplateParms=nullptr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UniqueIdentifier="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a class.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this class is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>class name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>class members.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RunTimeLang</td>
<td class="doxyParamItemDescription"><p>Optional parameter, Objective-C runtime version.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VTableHolder</td>
<td class="doxyParamItemDescription"><p>Debug info of the base class that contains vtable for this type. This is used in DW_AT_containing_type. See DWARF documentation for more info.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TemplateParms</td>
<td class="doxyParamItemDescription"><p>Template type parameters.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifier</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the class.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### createCommonBlock() {#a7cec597df7f95486c2db2f888d45ad85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICommonBlock * DIBuilder::createCommonBlock (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> * decl, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create common block entry for a Fortran common block.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope of this common block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">decl</td>
<td class="doxyParamItemDescription"><p>Global variable declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of this common block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>The file this common block is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 920 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createCompileUnit() {#a36f7af99f64b66e158b210e4433a1aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompileUnit * DIBuilder::createCompileUnit (unsigned Lang, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Producer, bool isOptimized, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Flags, unsigned RV, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SplitName=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(), <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66d">DICompileUnit::DebugEmissionKind</a> Kind=<a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66daa44087d1fe20ab5e128a0f592b6a85c1">DICompileUnit::DebugEmissionKind::FullDebug</a>, uint64_t DWOId=0, bool SplitDebugInlining=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool DebugInfoForProfiling=false, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01">DICompileUnit::DebugNameTableKind</a> NameTableKind=<a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01a7a1920d61156abc05a60135aefe8bc67">DICompileUnit::DebugNameTableKind::Default</a>, bool RangesBaseAddress=false, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SysRoot={}, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SDK={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> provides an anchor for all debugging information generated during this instance of compilation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Lang</td>
<td class="doxyParamItemDescription"><p>Source programming language, eg. dwarf::DW_LANG_C99</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File info.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Producer</td>
<td class="doxyParamItemDescription"><p>Identify the producer of debugging information and code. Usually this is a compiler version string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">isOptimized</td>
<td class="doxyParamItemDescription"><p>A boolean flag which indicates whether optimization is enabled or not.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>This string lists command line options. This string is directly embedded in debug info output which may be used by a tool analyzing generated debugging information.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RV</td>
<td class="doxyParamItemDescription"><p>This indicates runtime version for languages like Objective-C.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SplitName</td>
<td class="doxyParamItemDescription"><p>The name of the file that we'll split debug info out into.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The kind of debug information to generate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DWOId</td>
<td class="doxyParamItemDescription"><p>The DWOId if this is a split skeleton compile unit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SplitDebugInlining</td>
<td class="doxyParamItemDescription"><p>Whether to emit inline debug info.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DebugInfoForProfiling</td>
<td class="doxyParamItemDescription"><p>Whether to emit extra debug info for profile collection.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameTableKind</td>
<td class="doxyParamItemDescription"><p>Whether to emit .debug_gnu_pubnames, .debug_pubnames, or no pubnames at all.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SysRoot</td>
<td class="doxyParamItemDescription"><p>The clang system root (value of -isysroot).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SDK</td>
<td class="doxyParamItemDescription"><p>The SDK name. On Darwin, this is the last component of the sysroot.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae917c72e5b8e15491cd0dbdd44d818f2">llvm::NamedMDNode::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78f32f1cfba451a8c3691f00768da230a8f16e9a8f3582985075ffd88f363d616">llvm::dwarf::DW_LANG_lo_user</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a>.</p>

</div>
</div>

### createConstantValueExpression() {#a783740c21f25f5600065aca639a66936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * llvm::DIBuilder::createConstantValueExpression (uint64_t Val)</td>
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

<p>Create an expression for a variable that does not have an address, but does have a constant value.</p>

<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7c0a683d5c4984e6d58f5f3809ff6ec3">llvm::getExpressionForConstant</a>.</p>

</div>
</div>

### createEnumerationType() {#a28497d68ae2a721d43823c87919cfac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DIBuilder::createEnumerationType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, DINodeArray Elements, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * UnderlyingType, unsigned RunTimeLang=0, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UniqueIdentifier="", bool IsScoped=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for an enumeration.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this enumeration is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Union name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Enumeration elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UnderlyingType</td>
<td class="doxyParamItemDescription"><p>Underlying type of a C++11/ObjC fixed enum.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RunTimeLang</td>
<td class="doxyParamItemDescription"><p>Optional parameter, Objective-C runtime version.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifier</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the enum.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsScoped</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> flag indicate if this is C++11/ObjC 'enum class'.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createEnumerator() {#ac468b3d2f57aaac4935a7956509c785b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEnumerator * DIBuilder::createEnumerator (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a single enumerator value.</p>

<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createEnumerator() {#a27c9b02989f2380d2e3a2fffe6a9672b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEnumerator * DIBuilder::createEnumerator (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Val, bool IsUnsigned=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createExpression() {#ad1d53e81b2b3ddcc4518e816fc89711d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIBuilder::createExpression (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Addr={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for the specified variable which has a complex address expression for its address.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>An array of complex address operations.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="#a9cb4bcf5ce38d7b765c6f915f66f4bcf">createGlobalVariableExpression</a>.</p>

</div>
</div>

### createFile() {#afac26b4f6298753fa1566e66758c9dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIFile * DIBuilder::createFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/difile/checksuminfo">DIFile::ChecksumInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt; Checksum=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a file descriptor to hold debugging information for a file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Filename</td>
<td class="doxyParamItemDescription"><p>File name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Directory</td>
<td class="doxyParamItemDescription"><p>Directory.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Checksum</td>
<td class="doxyParamItemDescription"><p>Optional checksum kind (e.g. CSK_MD5, CSK_SHA1, etc.) and value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Source</td>
<td class="doxyParamItemDescription"><p>Optional source text.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createForwardDecl() {#af5b51afb7d6bdbb81b30eb5e121c1efb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DIBuilder::createForwardDecl (unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * F, unsigned Line, unsigned RuntimeLang=0, uint64_t SizeInBits=0, uint32_t AlignInBits=0, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UniqueIdentifier="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a permanent forward-declared type.</p>

<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### createFriend() {#a7d1c90a73404dc6a9eeb8d9206aa8b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createFriend (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * FriendTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a 'friend'.</p>

<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createFunction() {#a57d91109bab556ea565fe8dd35f1d30c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * DIBuilder::createFunction (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LinkageName, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> * Ty, unsigned ScopeLine, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero, <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#aee46b4d49ad15932fe2706f1d308d4e9">DISubprogram::DISPFlags</a> SPFlags=DISubprogram::SPFlagZero, DITemplateParameterArray TParams=nullptr, <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * Decl=nullptr, DITypeArray ThrownTypes=nullptr, DINodeArray Annotations=nullptr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetFuncName="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for the specified subprogram.</p>


<p>See comments in DISubprogram* for descriptions of these fields.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LinkageName</td>
<td class="doxyParamItemDescription"><p>Mangled function name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this variable is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ScopeLine</td>
<td class="doxyParamItemDescription"><p>Set to the beginning of the scope this starts</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>e.g. is this function prototyped or not. These flags are used to emit dwarf attributes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SPFlags</td>
<td class="doxyParamItemDescription"><p>Additional flags specific to subprograms.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TParams</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> template parameters.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ThrownTypes</td>
<td class="doxyParamItemDescription"><p>Exception types this function may throw.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/annotations"&gt;Annotations&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> <a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetFuncName</td>
<td class="doxyParamItemDescription"><p>The name of the target function if this is a trampoline.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a859931f9f18bb9556861a9568be49d1e">getSubprogram</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>.</p>

</div>
</div>

### createGlobalVariableExpression() {#a9cb4bcf5ce38d7b765c6f915f66f4bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIGlobalVariableExpression * DIBuilder::createGlobalVariableExpression (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LinkageName, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, bool IsLocalToUnit, bool isDefined=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr=nullptr, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Decl=nullptr, <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> * TemplateParams=nullptr, uint32_t AlignInBits=0, DINodeArray Annotations=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for the specified variable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Context</td>
<td class="doxyParamItemDescription"><p>Variable scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LinkageName</td>
<td class="doxyParamItemDescription"><p>Mangled name of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this variable is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Variable <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsLocalToUnit</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> flag indicate whether this variable is externally visible or not.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The location of the global relative to the attached <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Decl</td>
<td class="doxyParamItemDescription"><p>Reference to the corresponding declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Variable alignment(or 0 if no alignment attr was
                   specified)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a7ed9b2e89b42ead2f8dbda271333152c">checkGlobalVariableScope</a>, <a href="#ad1d53e81b2b3ddcc4518e816fc89711d">createExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### createImportedDeclaration() {#ae19d8948863925e5e9baf877da432322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIImportedEntity * DIBuilder::createImportedDeclaration (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * Decl, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="", DINodeArray Elements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for an imported function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Context</td>
<td class="doxyParamItemDescription"><p>The scope this module is imported into.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Decl</td>
<td class="doxyParamItemDescription"><p>The declaration (or definition) of a function, type, or variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where the declaration is located.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number of the declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Renamed elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>

</div>
</div>

### createImportedModule() {#adaf1ad638dccc0e0dfc111d3b9dbc494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIImportedEntity * DIBuilder::createImportedModule (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/dinamespace">DINamespace</a> * NS, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned Line, DINodeArray Elements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for an imported module.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Context</td>
<td class="doxyParamItemDescription"><p>The scope this module is imported into</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NS</td>
<td class="doxyParamItemDescription"><p>The namespace being imported here.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where the declaration is located.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number of the declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Renamed elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>

</div>
</div>

### createImportedModule() {#a2298c4b86797583b1e58b873c2f821bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIImportedEntity * DIBuilder::createImportedModule (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> * NS, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned Line, DINodeArray Elements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for an imported module.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Context</td>
<td class="doxyParamItemDescription"><p>The scope this module is imported into.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NS</td>
<td class="doxyParamItemDescription"><p>An aliased namespace.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where the declaration is located.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number of the declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Renamed elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 917 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>

</div>
</div>

### createImportedModule() {#adbed914ff7d389793f04bf2fc8e33ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIImportedEntity * DIBuilder::createImportedModule (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/dimodule">DIModule</a> * M, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned Line, DINodeArray Elements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for an imported module.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Context</td>
<td class="doxyParamItemDescription"><p>The scope this module is imported into.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>The module being imported here</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where the declaration is located.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number of the declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Renamed elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 928 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>

</div>
</div>

### createInheritance() {#a2236a7be2d15db19f575591000670c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createInheritance (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * BaseTy, uint64_t BaseOffset, uint32_t VBPtrOffset, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry to establish inheritance relationship between two types.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Original type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseTy</td>
<td class="doxyParamItemDescription"><p>Base type. Ty is inherits from base.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseOffset</td>
<td class="doxyParamItemDescription"><p>Base offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VBPtrOffset</td>
<td class="doxyParamItemDescription"><p>Virtual base pointer offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to describe inheritance attribute, e.g. private</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createLabel() {#a4c600597532d3123b025c387d90aa7df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILabel * DIBuilder::createLabel (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, bool AlwaysPreserve=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for an label.</p>


<p><span class="doxyComputerOutput">Scope</span> must be a <em><a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a></em>, and thus its scope chain eventually leads to a <em><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a></em>.</p>


<p>Declaration at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createLexicalBlock() {#a5b9cc4f1d1803b0b793267544900a44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILexicalBlock * DIBuilder::createLexicalBlock (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned Line, unsigned Col)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This creates a descriptor for a lexical block with the specified parent context.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Parent lexical scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>Source file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Col</td>
<td class="doxyParamItemDescription"><p>Column number.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createLexicalBlockFile() {#a2a715aa3a14c857ca33f84affd4e01a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILexicalBlockFile * DIBuilder::createLexicalBlockFile (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned Discriminator=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This creates a descriptor for a lexical block with a new file attached.</p>


<p>This merely extends the existing lexical block as it crosses a file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Lexical block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>Source file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Discriminator</td>
<td class="doxyParamItemDescription"><p>DWARF path discriminator value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 889 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createMacro() {#a1fe785a1cdccf63c091f5faf40f622ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIMacro * DIBuilder::createMacro (<a href="/web-llvm/docs/api/classes/llvm/dimacrofile">DIMacroFile</a> * Parent, unsigned Line, unsigned MacroType, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a macro.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parent</td>
<td class="doxyParamItemDescription"><p>Macro parent (could be nullptr).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Source line number where the macro is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MacroType</td>
<td class="doxyParamItemDescription"><p>DW_MACINFO_define or DW_MACINFO_undef.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Macro name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Macro value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1aa2d5a6f618fb7bc61c2b48b6cbd6f605">llvm::dwarf::DW_MACINFO_define</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1a1d03dab779486bab7cfd80a9d1b15d16">llvm::dwarf::DW_MACINFO_undef</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createMemberPointerType() {#ab82c0e7e3bb9354afd71d7edbc19f48a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createMemberPointerType (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * PointeeTy, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Class, uint64_t SizeInBits, uint32_t AlignInBits=0, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a pointer to member.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PointeeTy</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> pointed to by this pointer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment. (optional)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Class</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> for which this pointer points to members of.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createMemberType() {#adbf77460ca5103d4d0b2708b013a1b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createMemberType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, DINodeArray Annotations=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a member.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Member scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parent type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/annotations"&gt;Annotations&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Member annotations.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### createMethod() {#ab37a47c83ecb05b68a904e49a7f69f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * DIBuilder::createMethod (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LinkageName, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> * Ty, unsigned VTableIndex=0, int ThisAdjustment=0, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * VTableHolder=nullptr, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero, <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#aee46b4d49ad15932fe2706f1d308d4e9">DISubprogram::DISPFlags</a> SPFlags=DISubprogram::SPFlagZero, DITemplateParameterArray TParams=nullptr, DITypeArray ThrownTypes=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for the specified C++ method.</p>


<p>See comments in <em>DISubprogram*</em> for descriptions of these fields.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LinkageName</td>
<td class="doxyParamItemDescription"><p>Mangled function name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this variable is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VTableIndex</td>
<td class="doxyParamItemDescription"><p>Index no of this method in virtual table, or -1u if unrepresentable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ThisAdjustment</td>
<td class="doxyParamItemDescription"><p>MS ABI-specific adjustment of 'this' that occurs in the prologue.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VTableHolder</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> that holds vtable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>e.g. is this function prototyped or not. This flags are used to emit dwarf attributes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SPFlags</td>
<td class="doxyParamItemDescription"><p>Additional flags specific to subprograms.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TParams</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> template parameters.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ThrownTypes</td>
<td class="doxyParamItemDescription"><p>Exception types this function may throw.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a859931f9f18bb9556861a9568be49d1e">getSubprogram</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>.</p>

</div>
</div>

### createModule() {#affeea0b69c510392c5015ea861393738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIModule * DIBuilder::createModule (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ConfigurationMacros, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IncludePath, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> APINotesFile={}, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File=nullptr, unsigned LineNo=0, bool IsDecl=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This creates new descriptor for a module with the specified parent scope.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Parent scope</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of this module</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ConfigurationMacros</td>
<td class="doxyParamItemDescription"><p>A space-separated shell-quoted list of -D macro definitions as they would appear on a command line.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IncludePath</td>
<td class="doxyParamItemDescription"><p>The path to the module map file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">APINotesFile</td>
<td class="doxyParamItemDescription"><p>The path to an API notes file for this module.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>Source file of the module. Used for Fortran modules.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Source line number of the module. Used for Fortran modules.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDecl</td>
<td class="doxyParamItemDescription"><p>This is a module declaration; default to false; when set to true, only Scope and Name are required as this entry is just a hint for the debugger to find the corresponding definition in the global scope.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createNameSpace() {#a4fec0fd637f104b5c3cab3ffdbe3b3aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DINamespace * DIBuilder::createNameSpace (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool ExportSymbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This creates new descriptor for a namespace with the specified parent scope.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Namespace scope</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of this namespace</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExportSymbols</td>
<td class="doxyParamItemDescription"><p>True for C++ inline namespaces.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createNullPtrType() {#a7c6964fb822f5491b18b38e5facbc49c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBasicType * DIBuilder::createNullPtrType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create C++11 nullptr type.</p>

<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="#aef273038c3745ae3c1e9b6c01ce1e100">createUnspecifiedType</a>.</p>

</div>
</div>

### createObjCIVar() {#a3b7af05053d96eafcdd3e06b41ba6749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createObjCIVar (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * PropertyNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for Objective-C instance variable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parent type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PropertyNode</td>
<td class="doxyParamItemDescription"><p>Property associated with this ivar.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createObjCProperty() {#af1f0e54c22f59c0ca1b03fa355cbdde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIObjCProperty * DIBuilder::createObjCProperty (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNumber, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GetterName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SetterName, unsigned PropertyAttributes, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for Objective-C property.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Property name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this property is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GetterName</td>
<td class="doxyParamItemDescription"><p>Name of the Objective C property getter selector.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SetterName</td>
<td class="doxyParamItemDescription"><p>Name of the Objective C property setter selector.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PropertyAttributes</td>
<td class="doxyParamItemDescription"><p>Objective C property attributes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createParameterVariable() {#afa7c4efcb5c40c8527c13759f10ef5ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalVariable * DIBuilder::createParameterVariable (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, bool AlwaysPreserve=false, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero, DINodeArray Annotations=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for a parameter variable.</p>


<p><span class="doxyComputerOutput">Scope</span> must be a <em><a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a></em>, and thus its scope chain eventually leads to a <em><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a></em>.</p>


<p><span class="doxyComputerOutput">ArgNo</span> is the index (starting from <span class="doxyComputerOutput">1</span>) of this variable in the subprogram parameters. <span class="doxyComputerOutput">ArgNo</span> should not conflict with other parameters of the same subprogram.</p>


<p>If <span class="doxyComputerOutput">AlwaysPreserve</span>, this variable will be referenced from its containing subprogram, and will survive some optimizations.</p>


<p>Declaration at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a08ad252830f022d82e560f5447107d07">createLocalVariable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### createPointerType() {#a8f163bf8a14c1c7823f6d8fce7fb5ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createPointerType (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * PointeeTy, uint64_t SizeInBits, uint32_t AlignInBits=0, std::optional&lt; unsigned &gt; DWARFAddressSpace=std::nullopt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="", DINodeArray Annotations=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a pointer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PointeeTy</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> pointed by this pointer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment. (optional)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DWARFAddressSpace</td>
<td class="doxyParamItemDescription"><p>DWARF address space. (optional)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Pointer type name. (optional)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/annotations"&gt;Annotations&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Member annotations.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### createPtrAuthQualifiedType() {#ad51c008ee3bacaaed30e6a2cfac0268b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createPtrAuthQualifiedType (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * FromTy, unsigned Key, bool IsAddressDiscriminated, unsigned ExtraDiscriminator, bool IsaPointer, bool authenticatesNullValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a __ptrauth qualifier.</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### createQualifiedType() {#a35d8232846c9e46b1db929daff2bf477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createQualifiedType (unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * FromTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a qualified type, e.g.</p>


<p>'const int'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Tag</td>
<td class="doxyParamItemDescription"><p>Tag identifing type, e.g. dwarf::TAG_volatile_type</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FromTy</td>
<td class="doxyParamItemDescription"><p>Base <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### createReferenceType() {#ab1b53df8ec7e16b15d8d72c50c9d7448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createReferenceType (unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * RTy, uint64_t SizeInBits=0, uint32_t AlignInBits=0, std::optional&lt; unsigned &gt; DWARFAddressSpace=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a c++ style reference or rvalue reference type.</p>

<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### createReplaceableCompositeType() {#ad47dddfcbfe0d635de4712fad2e7f900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DIBuilder::createReplaceableCompositeType (unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * F, unsigned Line, unsigned RuntimeLang=0, uint64_t SizeInBits=0, uint32_t AlignInBits=0, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagFwdDecl, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UniqueIdentifier="", DINodeArray Annotations=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a temporary forward-declared type.</p>

<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a508e910bb51c882cc17c43afcb2bf7d7">llvm::MDNode::getTemporary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### createSetType() {#a7327bb62e5803d0eb1f8239d4d4509a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createSetType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a set.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this set is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Set name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this set is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Set size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Set alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Base type of the set.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createStaticMemberType() {#a23995c2ddd74a9abcc31d939e0643779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createStaticMemberType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Val, unsigned Tag, uint32_t AlignInBits=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a C++ static data member.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Member scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is declared.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of the static member.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Val</td>
<td class="doxyParamItemDescription"><p>Const initializer of the member.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Tag</td>
<td class="doxyParamItemDescription"><p>DWARF tag of the static member.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a91844752a109d8486027ab038e8f1d36">getConstantOrNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### createStringType() {#a5153d3ea2754b6b7fa554daecdf4ea5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIStringType * DIBuilder::createStringType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t SizeInBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a string type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Size of the type.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createStringType() {#a9ed4d9ff2d7f4bc923175f432a0209ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIStringType * DIBuilder::createStringType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> * StringLength, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * StrLocationExp=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for Fortran assumed length string type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StringLength</td>
<td class="doxyParamItemDescription"><p>String length expressed as <a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> *.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StrLocationExp</td>
<td class="doxyParamItemDescription"><p>Optional memory location of the string.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createStringType() {#a2bcb4de1da083a08f344d6454b4a4b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIStringType * DIBuilder::createStringType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * StringLengthExp, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * StrLocationExp=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for Fortran assumed length string type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StringLengthExp</td>
<td class="doxyParamItemDescription"><p>String length expressed in <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> form.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StrLocationExp</td>
<td class="doxyParamItemDescription"><p>Optional memory location of the string.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createStructType() {#afe762b489a1c62e1d3baf58b330e6652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DIBuilder::createStructType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * DerivedFrom, DINodeArray Elements, unsigned RunTimeLang=0, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * VTableHolder=nullptr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UniqueIdentifier="", <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Specification=nullptr, uint32_t NumExtraInhabitants=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a struct.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this struct is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Struct name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Struct elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RunTimeLang</td>
<td class="doxyParamItemDescription"><p>Optional parameter, Objective-C runtime version.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifier</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the struct.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Specification</td>
<td class="doxyParamItemDescription"><p>The type that this type completes. This is used by Swift to represent generic types.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumExtraInhabitants</td>
<td class="doxyParamItemDescription"><p>The number of extra inhabitants of the type. An extra inhabitant is a bit pattern that does not represent a valid value for instances of a given type. This is used by the Swift language.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### createSubroutineType() {#a1930fd092560cf172fb618ba55263ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubroutineType * DIBuilder::createSubroutineType (<a href="/web-llvm/docs/api/classes/llvm/dityperefarray">DITypeRefArray</a> ParameterTypes, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero, unsigned CC=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create subroutine type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParameterTypes</td>
<td class="doxyParamItemDescription"><p>An array of subroutine parameter types. This includes return type at 0th index.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>E.g.: LValueReference. These flags are used to emit dwarf attributes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CC</td>
<td class="doxyParamItemDescription"><p>Calling convention, e.g. dwarf::DW_CC_normal</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>.</p>

</div>
</div>

### createTempFunctionFwdDecl() {#a3ae4713be3cb6c59e31f8e83d02ee7e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * DIBuilder::createTempFunctionFwdDecl (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LinkageName, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> * Ty, unsigned ScopeLine, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero, <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#aee46b4d49ad15932fe2706f1d308d4e9">DISubprogram::DISPFlags</a> SPFlags=DISubprogram::SPFlagZero, DITemplateParameterArray TParams=nullptr, <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * Decl=nullptr, DITypeArray ThrownTypes=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identical to createFunction, except that the resulting DbgNode is meant to be RAUWed.</p>

<p>Declaration at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a508e910bb51c882cc17c43afcb2bf7d7">llvm::MDNode::getTemporary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>.</p>

</div>
</div>

### createTempGlobalVariableFwdDecl() {#a0836d7f22fd1d8bd8d2fd97da17bc9ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIGlobalVariable * DIBuilder::createTempGlobalVariableFwdDecl (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LinkageName, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, bool IsLocalToUnit, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Decl=nullptr, <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> * TemplateParams=nullptr, uint32_t AlignInBits=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identical to createGlobalVariable except that the resulting DbgNode is temporary and meant to be RAUWed.</p>

<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a7ed9b2e89b42ead2f8dbda271333152c">checkGlobalVariableScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a508e910bb51c882cc17c43afcb2bf7d7">llvm::MDNode::getTemporary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>.</p>

</div>
</div>

### createTemplateAlias() {#a88e594333479ba5f47d695a163a72846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createTemplateAlias (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, DINodeArray TParams, uint32_t AlignInBits=0, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero, DINodeArray Annotations=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a template alias.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Original type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Alias name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Context</td>
<td class="doxyParamItemDescription"><p>The surrounding context for the alias.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TParams</td>
<td class="doxyParamItemDescription"><p>The template arguments.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment. (optional)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to describe inheritance attribute (optional), e.g. private.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/annotations"&gt;Annotations&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>. (optional)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createTemplateParameterPack() {#a9282142c56014690597e4209fa3c4725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DITemplateValueParameter * DIBuilder::createTemplateParameterPack (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, DINodeArray Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information for a template parameter pack.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> parameter name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parameter type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Val</td>
<td class="doxyParamItemDescription"><p>An array of types in the pack.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#ac565d17a6ef8e7639ce88d6be474d08b">createTemplateValueParameterHelper</a>.</p>

</div>
</div>

### createTemplateTemplateParameter() {#a093b77c3612cbef1a9b29e680006f982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DITemplateValueParameter * DIBuilder::createTemplateTemplateParameter (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Val, bool IsDefault=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information for a template template parameter.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> parameter name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parameter type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Val</td>
<td class="doxyParamItemDescription"><p>The fully qualified name of the template.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDefault</td>
<td class="doxyParamItemDescription"><p>Parameter is default or not.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#ac565d17a6ef8e7639ce88d6be474d08b">createTemplateValueParameterHelper</a> and <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>.</p>

</div>
</div>

### createTemplateTypeParameter() {#ac74a0301ef623b8694f6ba75b9bf62af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DITemplateTypeParameter * DIBuilder::createTemplateTypeParameter (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, bool IsDefault)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information for template type parameter.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> parameter name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parameter type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDefault</td>
<td class="doxyParamItemDescription"><p>Parameter is default or not</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### createTemplateValueParameter() {#af7403e1a803ce258b0087e5faef340d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DITemplateValueParameter * DIBuilder::createTemplateValueParameter (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, bool IsDefault, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information for template value parameter.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> parameter name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parameter type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDefault</td>
<td class="doxyParamItemDescription"><p>Parameter is default or not</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Val</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> parameter value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#ac565d17a6ef8e7639ce88d6be474d08b">createTemplateValueParameterHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a91844752a109d8486027ab038e8f1d36">getConstantOrNull</a>.</p>

</div>
</div>

### createTempMacroFile() {#ab435c6fadebc269d84de9b4747806a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIMacroFile * DIBuilder::createTempMacroFile (<a href="/web-llvm/docs/api/classes/llvm/dimacrofile">DIMacroFile</a> * Parent, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information temporary entry for a macro file.</p>


<p>List of macro node direct children will be calculated by <a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a>, using the <span class="doxyComputerOutput">Parent</span> relationship.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parent</td>
<td class="doxyParamItemDescription"><p>Macro file parent (could be nullptr).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Source line number where the macro file is included.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File descriptor containing the name of the macro file.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1a494aa8941672ece775a0e3996c43495c">llvm::dwarf::DW_MACINFO_start_file</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a508e910bb51c882cc17c43afcb2bf7d7">llvm::MDNode::getTemporary</a>.</p>

</div>
</div>

### createTypedef() {#a0d9a1f42764491af27b361ae59c694b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createTypedef (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, uint32_t AlignInBits=0, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags=DINode::FlagZero, DINodeArray Annotations=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a typedef.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Original type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Typedef name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Context</td>
<td class="doxyParamItemDescription"><p>The surrounding context for the typedef.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment. (optional)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to describe inheritance attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/annotations"&gt;Annotations&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>. (optional)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createUnionType() {#a5d7a72e4269b08b6a786c6950c014bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DIBuilder::createUnionType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, DINodeArray Elements, unsigned RunTimeLang=0, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UniqueIdentifier="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for an union.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this union is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Union name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Union elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RunTimeLang</td>
<td class="doxyParamItemDescription"><p>Optional parameter, Objective-C runtime version.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifier</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the union.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createUnspecifiedParameter() {#a044f53a8c7873a1426602c69594bb679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBasicType * DIBuilder::createUnspecifiedParameter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create unspecified parameter type for a subroutine type.</p>

<p>Declaration at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>

</div>
</div>

### createUnspecifiedType() {#aef273038c3745ae3c1e9b6c01ce1e100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBasicType * DIBuilder::createUnspecifiedType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a DWARF unspecified type.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="#a7c6964fb822f5491b18b38e5facbc49c">createNullPtrType</a>.</p>

</div>
</div>

### createVariantMemberType() {#a24655d8cf9e92a91d8b51101f64553c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIBuilder::createVariantMemberType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Discriminant, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a variant.</p>


<p>A variant normally should be a member of a variant part.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Member scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Discriminant</td>
<td class="doxyParamItemDescription"><p>The discriminant for this branch; null for the default branch</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parent type.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a91844752a109d8486027ab038e8f1d36">getConstantOrNull</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createVariantPart() {#ad99e6c0300816ba0fd1ebbc4a8cbd3da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DIBuilder::createVariantPart (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * Discriminator, DINodeArray Elements, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UniqueIdentifier="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a variant part.</p>


<p>A variant part normally has a discriminator (though this is not required) and a number of variant children.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this union is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Union name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Discriminator</td>
<td class="doxyParamItemDescription"><p>Discriminant member</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Variant elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifier</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the union.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>

</div>
</div>

### createVectorType() {#a3ef92fe78919116804d90d9acfb98754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DIBuilder::createVectorType (uint64_t Size, uint32_t AlignInBits, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, DINodeArray Subscripts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a vector type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Array size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Element type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Subscripts</td>
<td class="doxyParamItemDescription"><p>Subscripts.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### finalize() {#a138b93205c71960aa94763a1081c50e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIBuilder::finalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct any deferred debug info descriptors.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1a494aa8941672ece775a0e3996c43495c">llvm::dwarf::DW_MACINFO_start_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a2e5c0418b92861c5387f5f60b60ef614">finalizeSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#aad2e50b107c264353f4de80e03f9f754">llvm::MDTuple::get</a>, <a href="#a65906c0586aeaa1831125ddeeaa7aa7a">getOrCreateMacroArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a0cfa048f7096ffb7b085d2d5d1a399ba">replaceTemporary</a>.</p>

</div>
</div>

### finalizeSubprogram() {#a2e5c0418b92861c5387f5f60b60ef614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIBuilder::finalizeSubprogram (<a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize a specific subprogram - no new variables may be added to this subprogram afterwards.</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#aad2e50b107c264353f4de80e03f9f754">llvm::MDTuple::get</a>.</p>


<p>Referenced by <a href="#a138b93205c71960aa94763a1081c50e9">finalize</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>.</p>

</div>
</div>

### getOrCreateArray() {#ac22bd3a0571eb4e961def1c480247296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DINodeArray DIBuilder::getOrCreateArray (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Elements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a DINodeArray, create one if required.</p>

<p>Declaration at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#aad2e50b107c264353f4de80e03f9f754">llvm::MDTuple::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### getOrCreateGenericSubrange() {#aeaef4f4223cd89524ff85e199545f57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIGenericSubrange * DIBuilder::getOrCreateGenericSubrange (<a href="/web-llvm/docs/api/classes/llvm/digenericsubrange/#ae3cca40d1d077f3c937c341333c54941">DIGenericSubrange::BoundType</a> Count, <a href="/web-llvm/docs/api/classes/llvm/digenericsubrange/#ae3cca40d1d077f3c937c341333c54941">DIGenericSubrange::BoundType</a> LowerBound, <a href="/web-llvm/docs/api/classes/llvm/digenericsubrange/#ae3cca40d1d077f3c937c341333c54941">DIGenericSubrange::BoundType</a> UpperBound, <a href="/web-llvm/docs/api/classes/llvm/digenericsubrange/#ae3cca40d1d077f3c937c341333c54941">DIGenericSubrange::BoundType</a> Stride)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getOrCreateMacroArray() {#a65906c0586aeaa1831125ddeeaa7aa7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIMacroNodeArray DIBuilder::getOrCreateMacroArray (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Elements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a DIMacroNodeArray, create one if required.</p>

<p>Declaration at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#aad2e50b107c264353f4de80e03f9f754">llvm::MDTuple::get</a>.</p>


<p>Referenced by <a href="#a138b93205c71960aa94763a1081c50e9">finalize</a>.</p>

</div>
</div>

### getOrCreateSubrange() {#aaec462f93a64e27fa16d1416b1dbbb8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubrange * DIBuilder::getOrCreateSubrange (int64_t Lo, int64_t Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for a value range.</p>


<p>This implicitly uniques the values returned.</p>


<p>Declaration at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a9ad53d2a00a6fb861b3a048c6592b742">llvm::ConstantInt::getSigned</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### getOrCreateSubrange() {#a0488e45d72dfdd3c9f1b7780fc812675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubrange * DIBuilder::getOrCreateSubrange (int64_t Lo, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * CountNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a9ad53d2a00a6fb861b3a048c6592b742">llvm::ConstantInt::getSigned</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>

</div>
</div>

### getOrCreateSubrange() {#a3656fa387ece7e6b1d3511da750743bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubrange * DIBuilder::getOrCreateSubrange (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Count, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * LowerBound, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * UpperBound, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Stride)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### getOrCreateTypeArray() {#abf27ce323516bd289ce53d2e241581fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DITypeRefArray DIBuilder::getOrCreateTypeArray (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Elements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <a href="/web-llvm/docs/api/classes/llvm/dityperefarray">DITypeRefArray</a>, create one if required.</p>

<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>.</p>

</div>
</div>

### insertDbgAssign() {#a5a6937fcd639ac78a93b48ab6624e957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgInstPtr DIBuilder::insertDbgAssign (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * LinkedInstr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * SrcVar, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * ValExpr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * AddrExpr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a new llvm.dbg.assign intrinsic call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LinkedInstr</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> with a <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> to link with the new intrinsic. The intrinsic will be inserted after this instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Val</td>
<td class="doxyParamItemDescription"><p>The value component of this dbg.assign.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcVar</td>
<td class="doxyParamItemDescription"><p>Variable's debug info descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ValExpr</td>
<td class="doxyParamItemDescription"><p>A complex location expression to modify <span class="doxyComputerOutput">Val</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>The address component (store destination).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AddrExpr</td>
<td class="doxyParamItemDescription"><p>A complex location expression to modify <span class="doxyComputerOutput">Addr</span>. NOTE: <span class="doxyComputerOutput">ValExpr</span> carries the FragInfo for the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug info location, usually: (line: 0, column: 0, scope: var-decl-scope). See getDebugValueLoc.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 968 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#acb02462725b8625bd395f4fa53520ed4">llvm::DbgVariableRecord::createDVRAssign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a9b051a25ba281897b4dc62df58312b7e">emitDbgAssign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a5a020f0ab461a1f6e3b87aff314bd040">insertNewDbgInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a0346c3f86c714b9ae84f5566a95e90ac">migrateDebugInfo</a>.</p>

</div>
</div>

### insertDbgValueIntrinsic() {#a915a8d23e084b7a40475a3ce2245495b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgInstPtr DIBuilder::insertDbgValueIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * VarInfo, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a new llvm.dbg.value intrinsic call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Val</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> of the variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VarInfo</td>
<td class="doxyParamItemDescription"><p>Variable's debug info descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>A complex location expression.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug info location.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InsertPt</td>
<td class="doxyParamItemDescription"><p>Location for the new intrinsic.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 996 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a8337b222b982e9caf0f6226efb56039c">llvm::DbgVariableRecord::createDbgVariableRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-promotememorytoregister-cpp-/#acce7135d82ed41802b7c4ccd9059d3db">anonymous{PromoteMemoryToRegister.cpp}::createDebugValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ac0da78bd6844fdff5ec2fc0654d00de7">insertDbgValueOrDbgVariableRecord</a>.</p>

</div>
</div>

### insertDeclare() {#a9019e662ee1c0c04e06e9871650268c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgInstPtr DIBuilder::insertDeclare (<a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * Storage, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * VarInfo, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertAtEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a new llvm.dbg.declare intrinsic call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Storage</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> of the variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VarInfo</td>
<td class="doxyParamItemDescription"><p>Variable's debug info descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>A complex location expression.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug info location.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InsertAtEnd</td>
<td class="doxyParamItemDescription"><p>Location for the new intrinsic.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a> and <a href="#a9019e662ee1c0c04e06e9871650268c8">insertDeclare</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="#a9019e662ee1c0c04e06e9871650268c8">insertDeclare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab994e75dc5cae892a87ae9a86d4b767a">insertNewDbgInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>.</p>

</div>
</div>

### insertDeclare() {#a214637beca449d58d4313a69a9ba32af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgInstPtr DIBuilder::insertDeclare (<a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * Storage, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * VarInfo, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a new llvm.dbg.declare intrinsic call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Storage</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> of the variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VarInfo</td>
<td class="doxyParamItemDescription"><p>Variable's debug info descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>A complex location expression.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug info location.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InsertPt</td>
<td class="doxyParamItemDescription"><p>Location for the new intrinsic.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 979 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 1050 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a8461772cf63d3b043a673a75b6b95e39">llvm::DbgVariableRecord::createDVRDeclare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#ad5ee8b40336e0c147c85f2520ada223c">getDbgIntrinsicValueImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a2607e2337fc3a69c867344fc4e3d209b">getDeclareIntrin</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a38229438b1c22802074b3181b0b80b85">llvm::DILocalVariable::getScope</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalscope/#a0e0b4a5906e0bc2a7fa033548c59a220">llvm::DILocalScope::getSubprogram</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#ad269a2105e7a19e6a7eac9d3399d7917">initIRBuilder</a>.</p>

</div>
</div>

### insertLabel() {#adb6aff41bfe64d206d563112993cfb01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgInstPtr DIBuilder::insertLabel (<a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> * LabelInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a new llvm.dbg.label intrinsic call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LabelInfo</td>
<td class="doxyParamItemDescription"><p>Label's debug info descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug info location.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InsertBefore</td>
<td class="doxyParamItemDescription"><p>Location for the new intrinsic.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/insertposition/#a85d3be01e87a0909859f543e00c5929a">llvm::InsertPosition::getBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/dilabel/#a87999af3acdf673c2b50574a6a65d461">llvm::DILabel::getScope</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalscope/#a0e0b4a5906e0bc2a7fa033548c59a220">llvm::DILocalScope::getSubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#ad269a2105e7a19e6a7eac9d3399d7917">initIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a365301682c41f8a7094218176d712cda">llvm::BasicBlock::insertDbgRecordBefore</a> and <a href="/web-llvm/docs/api/classes/llvm/insertposition/#a004805cdcc4314519ac66a4977ab408c">llvm::InsertPosition::isValid</a>.</p>

</div>
</div>

### replaceArrays() {#afee05194feacd4f95209e840e7242332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIBuilder::replaceArrays (<a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *&amp; T, DINodeArray Elements, DINodeArray TParams=DINodeArray())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace arrays on a composite type.</p>


<p>If <span class="doxyComputerOutput">T</span> is resolved, but the arrays aren't – which can happen if <span class="doxyComputerOutput">T</span> has a self-reference – <em><a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a></em> needs to track the array to resolve cycles.</p>


<p>Declaration at line 1013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### replaceTemporary() {#a0cfa048f7096ffb7b085d2d5d1a399ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeTy * llvm::DIBuilder::replaceTemporary (TempMDNode &amp;&amp; N, NodeTy * Replacement)</td>
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

<p>Replace a temporary node.</p>


<p>Call <em><a href="/web-llvm/docs/api/classes/llvm/mdnode/#a2e9fe39301fbac7276c8d9f3e1884dc2">MDNode::replaceAllUsesWith()</a></em> on <span class="doxyComputerOutput">N</span>, replacing it with <span class="doxyComputerOutput">Replacement</span>.</p>


<p>If <span class="doxyComputerOutput">Replacement</span> is the same as <span class="doxyComputerOutput">N.get()</span>, instead call <em><a href="/web-llvm/docs/api/classes/llvm/mdnode/#af8e7c85da0c37b1a8a5099d7a01f03a8">MDNode::replaceWithUniqued()</a></em>. In this case, the uniqued node could have a different address, so we return the final address.</p>


<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#af8e7c85da0c37b1a8a5099d7a01f03a8">llvm::MDNode::replaceWithUniqued</a>.</p>


<p>Referenced by <a href="#a138b93205c71960aa94763a1081c50e9">finalize</a>.</p>

</div>
</div>

### replaceVTableHolder() {#a736aced5bb739ef4976f57e0bc58ae22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIBuilder::replaceVTableHolder (<a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *&amp; T, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * VTableHolder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the vtable holder in the given type.</p>


<p>If this creates a self reference, it may orphan some unresolved cycles in the operands of <span class="doxyComputerOutput">T</span>, so <em><a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a></em> needs to track that.</p>


<p>Declaration at line 1005 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### retainType() {#a852f95fcd7c86fbd6517811f37108351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIBuilder::retainType (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retain DIScope* in a module even if it is not referenced through debug info anchors.</p>

<p>Declaration at line 668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getImportTrackingVector() {#aab7d60c6b793b2096fe776f564c761cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; TrackingMDNodeRef &gt; &amp; llvm::DIBuilder::getImportTrackingVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * S)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### getSubprogramNodesTrackingVector() {#ac5d969f5be07110b801d641d3ad41838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; TrackingMDNodeRef &gt; &amp; llvm::DIBuilder::getSubprogramNodesTrackingVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * S)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### insertDbgIntrinsic() {#a8c4cbaef84a1113e18f489710ee13aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * DIBuilder::insertDbgIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> * Intrinsic, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * VarInfo, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Internal helper with common code used by insertDbg{<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>,Addr}<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic">Intrinsic</a>.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 1092 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>

</div>
</div>

### insertDbgVariableRecord() {#a26d97b977568094ddc59082a15e7ca89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIBuilder::insertDbgVariableRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * DVR, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Internal helper. Track metadata if untracked and insert <span class="doxyComputerOutput">DVR</span>.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>

</div>
</div>

### trackIfUnresolved() {#a3d5cbbc5ebe7a2bc0e03e26b107decf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIBuilder::trackIfUnresolved (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a temporary.</p>


<p>Create an <em>temporary</em> node and track it in <em>UnresolvedNodes</em>.</p>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllEnumTypes {#a2e4b11a4c02371143a29044600a1f9e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TrackingMDNodeRef, 4&gt; llvm::DIBuilder::AllEnumTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### AllGVs {#a321782416aad2cd4b66e31aea0e2087d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Metadata *, 4&gt; llvm::DIBuilder::AllGVs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### AllMacrosPerParent {#af9bac72f37773a7815606b596104b52b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;MDNode *, SetVector&lt;Metadata *&gt; &gt; llvm::DIBuilder::AllMacrosPerParent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map Macro parent (which can be <a href="/web-llvm/docs/api/classes/llvm/dimacrofile">DIMacroFile</a> or nullptr) to a list of <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> all of type <a href="/web-llvm/docs/api/classes/llvm/dimacronode">DIMacroNode</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/dimacronode">DIMacroNode</a>'s with nullptr parent are <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> direct children.</p>


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### AllowUnresolvedNodes {#a2db0f0bbf1547cf061f08b6d03178344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIBuilder::AllowUnresolvedNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### AllRetainTypes {#a4f91221e356f6dbf453a4108a1c9aa2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TrackingMDNodeRef, 4&gt; llvm::DIBuilder::AllRetainTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track the RetainTypes, since they can be updated later on.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### AllSubprograms {#a4e01e226a5989dc3fbf4e8e8dbf39176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DISubprogram *, 4&gt; llvm::DIBuilder::AllSubprograms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### AssignFn {#a3171eb9bda03334360141385e19ae29f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::DIBuilder::AssignFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>llvm.dbg.assign</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### CUNode {#af6889b9d2493882bb03df260d9913e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompileUnit* llvm::DIBuilder::CUNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The one compile unit created by this DIBuiler.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### DeclareFn {#a477ccb1f9c93d7e6c129fd85015a2930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::DIBuilder::DeclareFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>llvm.dbg.declare</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### ImportedModules {#adaf9521fac87cfbdde3827169dbd524f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TrackingMDNodeRef, 4&gt; llvm::DIBuilder::ImportedModules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### LabelFn {#ab7c218ec6fef9d6b9e20230d29dd9ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::DIBuilder::LabelFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>llvm.dbg.label</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### M {#a08ce6b0bbbc33d704e5668293ff50385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; llvm::DIBuilder::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### SubprogramTrackedNodes {#ad5e88336f08013ed870e78405f17567f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;DISubprogram *, SmallVector&lt;TrackingMDNodeRef, 4&gt; &gt; llvm::DIBuilder::SubprogramTrackedNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Each subprogram's preserved local variables, labels and imported entities.</p>


<p>Do not use a std::vector. Some versions of libc++ apparently copy instead of move on grow operations, and <a href="/web-llvm/docs/api/classes/llvm/trackingmdref">TrackingMDRef</a> is expensive to copy.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### UnresolvedNodes {#a2da65395deaaf40cfb4edc588d0611ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TrackingMDNodeRef, 4&gt; llvm::DIBuilder::UnresolvedNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track nodes that may be unresolved.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### ValueFn {#ade84addd36b6666e149657bc1e21c54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::DIBuilder::ValueFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>llvm.dbg.value</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

### VMContext {#a2733c6588f0ef5dd7374a3999bc427f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::DIBuilder::VMContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createArtificialSubprogram() {#ae861fa6520a5b626bbc07dab42ff8005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * DIBuilder::createArtificialSubprogram (<a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
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

<p>Create a distinct clone of <span class="doxyComputerOutput">SP</span> with FlagArtificial set.</p>

<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7f0bcc228d194e9ec76797f689511951">llvm::MDNode::replaceWithDistinct</a>.</p>

</div>
</div>

### createArtificialType() {#a3bc8816adbffd7e286400bb7367058d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIType * DIBuilder::createArtificialType (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
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

<p>Create a uniqued clone of <span class="doxyComputerOutput">Ty</span> with FlagArtificial set.</p>

<p>Declaration at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a3acad1d2d3a16b66adc99bc4cfdd9efe">createTypeWithFlags</a>.</p>

</div>
</div>

### createObjectPointerType() {#a0061aafefff3c780f2b55c3772d94c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIType * DIBuilder::createObjectPointerType (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, bool Implicit)</td>
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

<p>Create a uniqued clone of <span class="doxyComputerOutput">Ty</span> with FlagObjectPointer set.</p>


<p>If <span class="doxyComputerOutput">Implicit</span> is true, also set FlagArtificial.</p>


<p>Declaration at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a>, definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a3acad1d2d3a16b66adc99bc4cfdd9efe">createTypeWithFlags</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">DIBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
