---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dicompileunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DICompileUnit` Class Reference

<p>Compile unit. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DICompileUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for scope-like contexts. <a href="/web-llvm/docs/api/classes/llvm/discope/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DebugEmissionKind : unsigned { <a href="#abbc2b566b9aa870d5b7131017b7ba66d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DebugNameTableKind : unsigned { <a href="#a47f44483cc8b041dd1678649b750da01">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888ebf7e3cd0ee51cfb3db1fbb4ce94c">DICompileUnit</a> (LLVMContext &amp;C, StorageType Storage, unsigned SourceLanguage, bool IsOptimized, unsigned RuntimeVersion, unsigned EmissionKind, uint64_t DWOId, bool SplitDebugInlining, bool DebugInfoForProfiling, unsigned NameTableKind, bool RangesBaseAddress, ArrayRef&lt; Metadata * &gt; Ops)</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1074d47e2954714107b2f927245c15ae">~DICompileUnit</a> ()=default</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9c2f038b1a61e566893b05cb19187d">replaceEnumTypes</a> (DICompositeTypeArray N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace arrays. <a href="#a4e9c2f038b1a61e566893b05cb19187d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7672beda79b3ce26a92e6b27a024ef85">replaceRetainedTypes</a> (DITypeArray N)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c78bd25d89294be0cc8fa519c8cf2a1">replaceGlobalVariables</a> (DIGlobalVariableExpressionArray N)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6add89069d0c88b795155b8de8bce1">replaceImportedEntities</a> (DIImportedEntityArray N)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d16da4f9fe3a9a316c3d34791745283">replaceMacros</a> (DIMacroNodeArray N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a> (DICompileUnit,(unsigned SourceLanguage, DIFile *File, StringRef Producer, bool IsOptimized, StringRef Flags, unsigned RuntimeVersion, StringRef SplitDebugFilename, DebugEmissionKind EmissionKind, DICompositeTypeArray EnumTypes, DIScopeArray RetainedTypes, DIGlobalVariableExpressionArray GlobalVariables, DIImportedEntityArray ImportedEntities, DIMacroNodeArray Macros, uint64_t DWOId, bool SplitDebugInlining, bool DebugInfoForProfiling, DebugNameTableKind NameTableKind, bool RangesBaseAddress, StringRef SysRoot, StringRef SDK),(SourceLanguage, File, Producer, IsOptimized, Flags, RuntimeVersion, SplitDebugFilename, EmissionKind, EnumTypes, RetainedTypes, GlobalVariables, ImportedEntities, Macros, DWOId, SplitDebugInlining, DebugInfoForProfiling,(unsigned) NameTableKind, RangesBaseAddress, SysRoot, SDK)) DEFINE_MDNODE_GET_DISTINCT_TEMPORARY(DICompileUnit</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="#a9baff343830f2e1aa33fe00d88dd78bc">SDK</a> TempDICompileUnit</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14054b7d69358b5a38dceb6c5789e08">clone</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad685f7e7d1b35f0e38a51359927147e8">getSourceLanguage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff913f548b86cd6ac0cb51f713dfc9b8">isOptimized</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74df13f9e078a87ebeb63ab58ce909ae">getRuntimeVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abbc2b566b9aa870d5b7131017b7ba66d">DebugEmissionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4862073480e7ac7169a3741fef1339">getEmissionKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36ac215f97478b9332071e06786aed77">isDebugDirectivesOnly</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100f52daef15eef06fddf617f6933d88">getDebugInfoForProfiling</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a47f44483cc8b041dd1678649b750da01">DebugNameTableKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9111ba431ceafe9283b9ee0a587f533d">getNameTableKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66eec10f8fa9072c82cbd9a840f64ac7">getRangesBaseAddress</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d9dd21a67dd50dbfae84e25d00e104">getProducer</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433572934c94c2bbd88989e056457d91">getFlags</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af664fcb825cb6ffc1567fc2bc244173f">getSplitDebugFilename</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DICompositeTypeArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29adc91ac421b1dfa93a74e2bbeda027">getEnumTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DIScopeArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb84ad711e2a0a0638d71098e807163b">getRetainedTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DIGlobalVariableExpressionArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7dd8cb7b0e6317da07d88f486aeb5b7">getGlobalVariables</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DIImportedEntityArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99fa64bf6b86f9b941f2a65486736719">getImportedEntities</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DIMacroNodeArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73200a2b59434489dc362c602fbb38d1">getMacros</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae958a8312f8255cb40accb9c486c198f">getDWOId</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69bcc2c7a7370bf0b09bc8cd5054af2">setDWOId</a> (uint64_t DwoId)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8580ec112636cac325223ad51b031dd4">getSplitDebugInlining</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d55132a5a8de273be5b932fa9e9fe7">setSplitDebugInlining</a> (bool SplitDebugInlining)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d5852e8c6b39d5384771dd83ffe2aec">getSysRoot</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644e14dd0e49dbb5fdfffdb0d40c001e">getSDK</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a462ce085c954ae30cf97838d3742f8fd">getRawProducer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995b035a302a4f7c9a79cb325065d07e">getRawFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089ad9064ccde84723bdd93cac758bf0">getRawSplitDebugFilename</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1728e830c90f846a0206cf3c4dd25e4">getRawEnumTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a129de53c1585da6d86a3911b71f92e31">getRawRetainedTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0cfb47b6864511214cb4f1faa9c12c1">getRawGlobalVariables</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade05c0809e768c7598f18703080aca65">getRawImportedEntities</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756f62cf3a7b5faa963be37236134137">getRawMacros</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51cde0281b867ed3ae17fb8028d6d2fd">getRawSysRoot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9130f77644181524e3db068cd0709e21">getRawSDK</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">TempDICompileUnit</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada741fa71d035264da849868de9320df">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f7b3264e80582672f5523ef733babec">File</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dd0bc35988e605669d88fd7f045bbc3">Producer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84077038f8002b988c6e5aa3a519ba0b">IsOptimized</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ce00f4228fb65359c3f41221c7e94d">Flags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b401a93fd0913d7714ca7f9c70f4a31">RuntimeVersion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3cc55f6fd1f2a87914ec4a917d8590e">SplitDebugFilename</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c118671bebab2e1f5ec703fc1ce50ff">EmissionKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59e97f8efd0075a5ae2d608261700047">EnumTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1be4355284a09effd3c7047b686582">RetainedTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a531481b1dcb9f57f843b64665fb9c">GlobalVariables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6008cdfb9ec4f00ce721c0dd693b119">ImportedEntities</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3003292f7da5d92da60ce8ac53eec3a8">Macros</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea1edfd722819f72d5862899c7506e0">DWOId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4629623e8a010db15ddeee6d60f9a10">SplitDebugInlining</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a64a494b808d7b759cd00a7d2d5f6f6">DebugInfoForProfiling</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c0e95d6fe40a377be4a3944afd128d">NameTableKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e911f4d9b2daa90895180ae997f789">RangesBaseAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c400cf291205295a834f5558c58d92">SysRoot</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9baff343830f2e1aa33fe00d88dd78bc">SDK</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af51187d4746c0e710f5604cbc8918f02">SourceLanguage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49be0fa334bcec98cffca3a8be03fac9">File</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec4ba546bf8dab9d9594fff08d53d8a">Producer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae687621b0dfd09e0208aab8f73b953">IsOptimized</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a051c7d277d65b67d4d2e52236015b24e">Flags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515cb0855c3b79722944f43f61844dad">RuntimeVersion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db5fbe3e8c323c51fbd5f6facf225db">SplitDebugFilename</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb225da4b6cbb8af05bf5052e88ba5bb">EmissionKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927f5687c58299ad4c61511282687779">EnumTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcb6f5933d9df319673346c1b4d0b1c6">RetainedTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1ba98c96857c926e0d48c023f62951">GlobalVariables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77057cc109197f161365792577fffd98">ImportedEntities</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a2f7d64466bd3ec645fccc1a7326b7">Macros</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1e05eeb5aa175303fe2c84006ba8a9a">DWOId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac49c7f0fafe97c2f837198f507f0ef1">SplitDebugInlining</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb136c71a504205bff11d14add80ed1f">DebugInfoForProfiling</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5142a92cd8320fd11238afd12e09c18">NameTableKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad68ba4b6396d8f137c09b3a58ce9a112">RangesBaseAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t bool bool unsigned bool <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86150f14f26efa0575a15e68ec955aab">SysRoot</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f73f76fc996dcbaa304b85af02de90">SourceLanguage</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a2bd50a0bb6a2fab18aafa2c56bb6c4">RuntimeVersion</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6154eb9ab4766471a75506f32d247a78">DWOId</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2905cdd4515135dbd9c018f769e9bc3">EmissionKind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cad2c86e635b2b76bc966efc8e5953c">NameTableKind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d289703b6eb35e2aa966223e2b66d48">IsOptimized</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfa18b27f8183f7dd27fb90f175e532">SplitDebugInlining</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9fb3c082dd6b3c01e6b5456da818020">DebugInfoForProfiling</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace1eb073a2148219cb98f3ab09a4b513">RangesBaseAddress</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="#abbc2b566b9aa870d5b7131017b7ba66d">DebugEmissionKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeaa84c982a7493e02d1b547297e0e69">getEmissionKind</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168bde7847da28592f7c592d0eed28c8">emissionKindString</a> (DebugEmissionKind EK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="#a47f44483cc8b041dd1678649b750da01">DebugNameTableKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a659717c7e0fe157516a881f0de5e1dec">getNameTableKind</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153271fe0f31039d8c15c519611204cc">nameTableKindString</a> (DebugNameTableKind PK)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c558c37352930215ced7f433865751">get</a> ()=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65bb56033bd3155f6c6905ed17900347">getIfExists</a> ()=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7797d4a32dbb959f7f4372b6d48f3601">classof</a> (const Metadata *MD)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9ac07be3679f8052a3df89f6e3f6e2">getImpl</a> (LLVMContext &amp;Context, unsigned SourceLanguage, DIFile *File, StringRef Producer, bool IsOptimized, StringRef Flags, unsigned RuntimeVersion, StringRef SplitDebugFilename, unsigned EmissionKind, DICompositeTypeArray EnumTypes, DIScopeArray RetainedTypes, DIGlobalVariableExpressionArray GlobalVariables, DIImportedEntityArray ImportedEntities, DIMacroNodeArray Macros, uint64_t DWOId, bool SplitDebugInlining, bool DebugInfoForProfiling, unsigned NameTableKind, bool RangesBaseAddress, StringRef SysRoot, StringRef SDK, StorageType Storage, bool ShouldCreate=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf25a9e8c51a311d6ac9d4eca022719">getImpl</a> (LLVMContext &amp;Context, unsigned SourceLanguage, Metadata *File, MDString *Producer, bool IsOptimized, MDString *Flags, unsigned RuntimeVersion, MDString *SplitDebugFilename, unsigned EmissionKind, Metadata *EnumTypes, Metadata *RetainedTypes, Metadata *GlobalVariables, Metadata *ImportedEntities, Metadata *Macros, uint64_t DWOId, bool SplitDebugInlining, bool DebugInfoForProfiling, unsigned NameTableKind, bool RangesBaseAddress, MDString *SysRoot, MDString *SDK, StorageType Storage, bool ShouldCreate=true)</td>
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

<p>Compile unit.</p>

<p>Definition at line 1469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### DebugEmissionKind {#abbc2b566b9aa870d5b7131017b7ba66d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DICompileUnit::DebugEmissionKind : unsigned</td>
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
<td class="doxyEnumItemName">NoDebug<a id="abbc2b566b9aa870d5b7131017b7ba66dadb74da0a389a2704e8e01c66ace2913e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FullDebug<a id="abbc2b566b9aa870d5b7131017b7ba66daa44087d1fe20ab5e128a0f592b6a85c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LineTablesOnly<a id="abbc2b566b9aa870d5b7131017b7ba66da6b16b60468715f43621c437edef9a3b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DebugDirectivesOnly<a id="abbc2b566b9aa870d5b7131017b7ba66dad9c778495a1251c95f818a65864f504b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastEmissionKind<a id="abbc2b566b9aa870d5b7131017b7ba66da94efb087d5b21ccbc192ea3d61a399fa"></a></td>
<td class="doxyEnumItemDescription"> (= DebugDirectivesOnly)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### DebugNameTableKind {#a47f44483cc8b041dd1678649b750da01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DICompileUnit::DebugNameTableKind : unsigned</td>
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
<td class="doxyEnumItemName">Default<a id="a47f44483cc8b041dd1678649b750da01a7a1920d61156abc05a60135aefe8bc67"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNU<a id="a47f44483cc8b041dd1678649b750da01ab7e89d55aa08a289aa48277386e6ff1d"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a47f44483cc8b041dd1678649b750da01a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Apple<a id="a47f44483cc8b041dd1678649b750da01a9f6290f4436e5a2351f12e03b6433c3c"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastDebugNameTableKind<a id="a47f44483cc8b041dd1678649b750da01ab92514422f075429b7045d1d51ffc673"></a></td>
<td class="doxyEnumItemDescription"> (= Apple)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LLVMContextImpl {#aa81f87de855d80e4275071841a7e0c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl">LLVMContextImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>


<p>Referenced by <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>

</div>
</div>

### MDNode {#acf51c34793180f67be514c1d6e4167f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>


<p>Referenced by <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DICompileUnit() {#a888ebf7e3cd0ee51cfb3db1fbb4ce94c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompileUnit::DICompileUnit (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, unsigned SourceLanguage, bool IsOptimized, unsigned RuntimeVersion, unsigned EmissionKind, uint64_t DWOId, bool SplitDebugInlining, bool DebugInfoForProfiling, unsigned NameTableKind, bool RangesBaseAddress, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~DICompileUnit() {#a1074d47e2954714107b2f927245c15ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DICompileUnit::~DICompileUnit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### replaceEnumTypes() {#a4e9c2f038b1a61e566893b05cb19187d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompileUnit::replaceEnumTypes (DICompositeTypeArray N)</td>
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

<p>Replace arrays.</p>


<p>If this <em><a href="/web-llvm/docs/api/classes/llvm/mdnode/#a92fd2fda0d83920749a3b0ef851b4580">isUniqued()</a></em> and not <em><a href="/web-llvm/docs/api/classes/llvm/mdnode/#ac8c31a76a81b27c7307d65575b62084f">isResolved()</a></em>, it will be RAUW'ed and deleted on a uniquing collision. In practice, uniquing collisions on <em><a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a></em> should be fairly rare.</p>


<p>Definition at line 1652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>

</div>
</div>

### replaceGlobalVariables() {#a7c78bd25d89294be0cc8fa519c8cf2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompileUnit::replaceGlobalVariables (DIGlobalVariableExpressionArray N)</td>
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



<p>Definition at line 1656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>

</div>
</div>

### replaceImportedEntities() {#abe6add89069d0c88b795155b8de8bce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompileUnit::replaceImportedEntities (DIImportedEntityArray N)</td>
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



<p>Definition at line 1659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>

</div>
</div>

### replaceMacros() {#a7d16da4f9fe3a9a316c3d34791745283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompileUnit::replaceMacros (DIMacroNodeArray N)</td>
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



<p>Definition at line 1662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>

</div>
</div>

### replaceRetainedTypes() {#a7672beda79b3ce26a92e6b27a024ef85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompileUnit::replaceRetainedTypes (DITypeArray N)</td>
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



<p>Definition at line 1655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#ad14054b7d69358b5a38dceb6c5789e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString SDK TempDICompileUnit llvm::DICompileUnit::clone ()</td>
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



<p>Definition at line 1590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#ad14054b7d69358b5a38dceb6c5789e08">clone</a>.</p>


<p>Referenced by <a href="#ad14054b7d69358b5a38dceb6c5789e08">clone</a>.</p>

</div>
</div>

### DEFINE\_MDNODE\_GET\_DISTINCT\_TEMPORARY() {#af9d697248b7d8962046d9e808fe17c09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DICompileUnit::DEFINE_MDNODE_GET_DISTINCT_TEMPORARY (<a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a>, (unsigned <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#a4187b233b3c324ed58f7cc6495e9ec0d">SourceLanguage</a>, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> *<a href="#a2f7b3264e80582672f5523ef733babec">File</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#a9dd0bc35988e605669d88fd7f045bbc3">Producer</a>, bool IsOptimized, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#a34ce00f4228fb65359c3f41221c7e94d">Flags</a>, unsigned RuntimeVersion, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#aa3cc55f6fd1f2a87914ec4a917d8590e">SplitDebugFilename</a>, <a href="#abbc2b566b9aa870d5b7131017b7ba66d">DebugEmissionKind</a> EmissionKind, DICompositeTypeArray <a href="#a59e97f8efd0075a5ae2d608261700047">EnumTypes</a>, DIScopeArray <a href="#a5d1be4355284a09effd3c7047b686582">RetainedTypes</a>, DIGlobalVariableExpressionArray <a href="#a99a531481b1dcb9f57f843b64665fb9c">GlobalVariables</a>, DIImportedEntityArray <a href="#aa6008cdfb9ec4f00ce721c0dd693b119">ImportedEntities</a>, DIMacroNodeArray <a href="#a3003292f7da5d92da60ce8ac53eec3a8">Macros</a>, uint64_t DWOId, bool SplitDebugInlining, bool DebugInfoForProfiling, <a href="#a47f44483cc8b041dd1678649b750da01">DebugNameTableKind</a> NameTableKind, bool RangesBaseAddress, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#aa1c400cf291205295a834f5558c58d92">SysRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#a9baff343830f2e1aa33fe00d88dd78bc">SDK</a>), (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#a4187b233b3c324ed58f7cc6495e9ec0d">SourceLanguage</a>, <a href="#a2f7b3264e80582672f5523ef733babec">File</a>, <a href="#a9dd0bc35988e605669d88fd7f045bbc3">Producer</a>, IsOptimized, <a href="#a34ce00f4228fb65359c3f41221c7e94d">Flags</a>, RuntimeVersion, <a href="#aa3cc55f6fd1f2a87914ec4a917d8590e">SplitDebugFilename</a>, EmissionKind, <a href="#a59e97f8efd0075a5ae2d608261700047">EnumTypes</a>, <a href="#a5d1be4355284a09effd3c7047b686582">RetainedTypes</a>, <a href="#a99a531481b1dcb9f57f843b64665fb9c">GlobalVariables</a>, <a href="#aa6008cdfb9ec4f00ce721c0dd693b119">ImportedEntities</a>, <a href="#a3003292f7da5d92da60ce8ac53eec3a8">Macros</a>, DWOId, SplitDebugInlining, DebugInfoForProfiling,(unsigned) NameTableKind, RangesBaseAddress, <a href="#aa1c400cf291205295a834f5558c58d92">SysRoot</a>, <a href="#a9baff343830f2e1aa33fe00d88dd78bc">SDK</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#a59e97f8efd0075a5ae2d608261700047">EnumTypes</a>, <a href="#a2f7b3264e80582672f5523ef733babec">File</a>, <a href="#a34ce00f4228fb65359c3f41221c7e94d">Flags</a>, <a href="#a99a531481b1dcb9f57f843b64665fb9c">GlobalVariables</a>, <a href="#aa6008cdfb9ec4f00ce721c0dd693b119">ImportedEntities</a>, <a href="#a3003292f7da5d92da60ce8ac53eec3a8">Macros</a>, <a href="#a9dd0bc35988e605669d88fd7f045bbc3">Producer</a>, <a href="#a5d1be4355284a09effd3c7047b686582">RetainedTypes</a>, <a href="#a9baff343830f2e1aa33fe00d88dd78bc">SDK</a>, <a href="#aa3cc55f6fd1f2a87914ec4a917d8590e">SplitDebugFilename</a> and <a href="#aa1c400cf291205295a834f5558c58d92">SysRoot</a>.</p>

</div>
</div>

### getDebugInfoForProfiling() {#a100f52daef15eef06fddf617f6933d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::getDebugInfoForProfiling ()</td>
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



<p>Definition at line 1601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>.</p>

</div>
</div>

### getDWOId() {#ae958a8312f8255cb40accb9c486c198f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DICompileUnit::getDWOId ()</td>
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



<p>Definition at line 1624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getEmissionKind() {#a2d4862073480e7ac7169a3741fef1339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugEmissionKind llvm::DICompileUnit::getEmissionKind ()</td>
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



<p>Definition at line 1595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/llparser/#a46836f2cf5e318baf7539c56130c16ab">llvm::LLParser::parseMDField</a>.</p>

</div>
</div>

### getEnumTypes() {#a29adc91ac421b1dfa93a74e2bbeda027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeTypeArray llvm::DICompileUnit::getEnumTypes ()</td>
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



<p>Definition at line 1609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#aa1728e830c90f846a0206cf3c4dd25e4">getRawEnumTypes</a>.</p>

</div>
</div>

### getFlags() {#a433572934c94c2bbd88989e056457d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DICompileUnit::getFlags ()</td>
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



<p>Definition at line 1607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a8ca691a16f8c92064df94a30b246b916">llvm::DINode::getStringOperand</a>.</p>

</div>
</div>

### getGlobalVariables() {#ac7dd8cb7b0e6317da07d88f486aeb5b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIGlobalVariableExpressionArray llvm::DICompileUnit::getGlobalVariables ()</td>
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



<p>Definition at line 1615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#ac0cfb47b6864511214cb4f1faa9c12c1">getRawGlobalVariables</a>.</p>

</div>
</div>

### getImportedEntities() {#a99fa64bf6b86f9b941f2a65486736719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIImportedEntityArray llvm::DICompileUnit::getImportedEntities ()</td>
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



<p>Definition at line 1618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#ade05c0809e768c7598f18703080aca65">getRawImportedEntities</a>.</p>

</div>
</div>

### getMacros() {#a73200a2b59434489dc362c602fbb38d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIMacroNodeArray llvm::DICompileUnit::getMacros ()</td>
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



<p>Definition at line 1621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#a756f62cf3a7b5faa963be37236134137">getRawMacros</a>.</p>

</div>
</div>

### getNameTableKind() {#a9111ba431ceafe9283b9ee0a587f533d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugNameTableKind llvm::DICompileUnit::getNameTableKind ()</td>
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



<p>Definition at line 1602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/llparser/#a1e2375ce5af65ae70e5450c3a7938a26">llvm::LLParser::parseMDField</a>.</p>

</div>
</div>

### getProducer() {#aa1d9dd21a67dd50dbfae84e25d00e104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DICompileUnit::getProducer ()</td>
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



<p>Definition at line 1606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a8ca691a16f8c92064df94a30b246b916">llvm::DINode::getStringOperand</a>.</p>

</div>
</div>

### getRangesBaseAddress() {#a66eec10f8fa9072c82cbd9a840f64ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::getRangesBaseAddress ()</td>
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



<p>Definition at line 1605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getRawEnumTypes() {#aa1728e830c90f846a0206cf3c4dd25e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompileUnit::getRawEnumTypes ()</td>
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



<p>Definition at line 1638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a29adc91ac421b1dfa93a74e2bbeda027">getEnumTypes</a>.</p>

</div>
</div>

### getRawFlags() {#a995b035a302a4f7c9a79cb325065d07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * llvm::DICompileUnit::getRawFlags ()</td>
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



<p>Definition at line 1634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a928838d3e896f53856bd269829ddf5e0">llvm::DINode::getOperandAs</a>.</p>

</div>
</div>

### getRawGlobalVariables() {#ac0cfb47b6864511214cb4f1faa9c12c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompileUnit::getRawGlobalVariables ()</td>
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



<p>Definition at line 1640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#ac7dd8cb7b0e6317da07d88f486aeb5b7">getGlobalVariables</a>.</p>

</div>
</div>

### getRawImportedEntities() {#ade05c0809e768c7598f18703080aca65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompileUnit::getRawImportedEntities ()</td>
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



<p>Definition at line 1641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a99fa64bf6b86f9b941f2a65486736719">getImportedEntities</a>.</p>

</div>
</div>

### getRawMacros() {#a756f62cf3a7b5faa963be37236134137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompileUnit::getRawMacros ()</td>
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



<p>Definition at line 1642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a73200a2b59434489dc362c602fbb38d1">getMacros</a>.</p>

</div>
</div>

### getRawProducer() {#a462ce085c954ae30cf97838d3742f8fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * llvm::DICompileUnit::getRawProducer ()</td>
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



<p>Definition at line 1633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a928838d3e896f53856bd269829ddf5e0">llvm::DINode::getOperandAs</a>.</p>

</div>
</div>

### getRawRetainedTypes() {#a129de53c1585da6d86a3911b71f92e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompileUnit::getRawRetainedTypes ()</td>
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



<p>Definition at line 1639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#abb84ad711e2a0a0638d71098e807163b">getRetainedTypes</a>.</p>

</div>
</div>

### getRawSDK() {#a9130f77644181524e3db068cd0709e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * llvm::DICompileUnit::getRawSDK ()</td>
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



<p>Definition at line 1644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a928838d3e896f53856bd269829ddf5e0">llvm::DINode::getOperandAs</a>.</p>

</div>
</div>

### getRawSplitDebugFilename() {#a089ad9064ccde84723bdd93cac758bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * llvm::DICompileUnit::getRawSplitDebugFilename ()</td>
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



<p>Definition at line 1635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a928838d3e896f53856bd269829ddf5e0">llvm::DINode::getOperandAs</a>.</p>

</div>
</div>

### getRawSysRoot() {#a51cde0281b867ed3ae17fb8028d6d2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * llvm::DICompileUnit::getRawSysRoot ()</td>
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



<p>Definition at line 1643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a928838d3e896f53856bd269829ddf5e0">llvm::DINode::getOperandAs</a>.</p>

</div>
</div>

### getRetainedTypes() {#abb84ad711e2a0a0638d71098e807163b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIScopeArray llvm::DICompileUnit::getRetainedTypes ()</td>
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



<p>Definition at line 1612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#a129de53c1585da6d86a3911b71f92e31">getRawRetainedTypes</a>.</p>

</div>
</div>

### getRuntimeVersion() {#a74df13f9e078a87ebeb63ab58ce909ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DICompileUnit::getRuntimeVersion ()</td>
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



<p>Definition at line 1594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getSDK() {#a644e14dd0e49dbb5fdfffdb0d40c001e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DICompileUnit::getSDK ()</td>
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



<p>Definition at line 1631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a8ca691a16f8c92064df94a30b246b916">llvm::DINode::getStringOperand</a>.</p>

</div>
</div>

### getSourceLanguage() {#ad685f7e7d1b35f0e38a51359927147e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DICompileUnit::getSourceLanguage ()</td>
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



<p>Definition at line 1592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getSplitDebugFilename() {#af664fcb825cb6ffc1567fc2bc244173f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DICompileUnit::getSplitDebugFilename ()</td>
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



<p>Definition at line 1608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a8ca691a16f8c92064df94a30b246b916">llvm::DINode::getStringOperand</a>.</p>

</div>
</div>

### getSplitDebugInlining() {#a8580ec112636cac325223ad51b031dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::getSplitDebugInlining ()</td>
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



<p>Definition at line 1626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>.</p>

</div>
</div>

### getSysRoot() {#a8d5852e8c6b39d5384771dd83ffe2aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DICompileUnit::getSysRoot ()</td>
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



<p>Definition at line 1630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a8ca691a16f8c92064df94a30b246b916">llvm::DINode::getStringOperand</a>.</p>

</div>
</div>

### isDebugDirectivesOnly() {#a36ac215f97478b9332071e06786aed77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::isDebugDirectivesOnly ()</td>
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



<p>Definition at line 1598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#abbc2b566b9aa870d5b7131017b7ba66dad9c778495a1251c95f818a65864f504b">DebugDirectivesOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a66056de6e47af980edacced419d5d0b8">llvm::DwarfFile::emitUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>.</p>

</div>
</div>

### isOptimized() {#aff913f548b86cd6ac0cb51f713dfc9b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::isOptimized ()</td>
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



<p>Definition at line 1593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### setDWOId() {#aa69bcc2c7a7370bf0b09bc8cd5054af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompileUnit::setDWOId (uint64_t DwoId)</td>
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



<p>Definition at line 1625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### setSplitDebugInlining() {#a24d55132a5a8de273be5b932fa9e9fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompileUnit::setSplitDebugInlining (bool SplitDebugInlining)</td>
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



<p>Definition at line 1627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneImpl() {#ada741fa71d035264da849868de9320df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempDICompileUnit llvm::DICompileUnit::cloneImpl ()</td>
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



<p>Definition at line 1545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DebugInfoForProfiling {#a0a64a494b808d7b759cd00a7d2d5f6f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool llvm::DICompileUnit::DebugInfoForProfiling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### DebugInfoForProfiling {#adb136c71a504205bff11d14add80ed1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::DebugInfoForProfiling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### DWOId {#abea1edfd722819f72d5862899c7506e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t llvm::DICompileUnit::DWOId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### DWOId {#ae1e05eeb5aa175303fe2c84006ba8a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::DWOId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### EmissionKind {#a0c118671bebab2e1f5ec703fc1ce50ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned llvm::DICompileUnit::EmissionKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### EmissionKind {#abb225da4b6cbb8af05bf5052e88ba5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::EmissionKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### EnumTypes {#a59e97f8efd0075a5ae2d608261700047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata* llvm::DICompileUnit::EnumTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### EnumTypes {#a927f5687c58299ad4c61511282687779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::EnumTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### File {#a2f7b3264e80582672f5523ef733babec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata* llvm::DICompileUnit::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### File {#a49be0fa334bcec98cffca3a8be03fac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Flags {#a34ce00f4228fb65359c3f41221c7e94d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString* llvm::DICompileUnit::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### Flags {#a051c7d277d65b67d4d2e52236015b24e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### GlobalVariables {#a99a531481b1dcb9f57f843b64665fb9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata* llvm::DICompileUnit::GlobalVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### GlobalVariables {#a3d1ba98c96857c926e0d48c023f62951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::GlobalVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### ImportedEntities {#aa6008cdfb9ec4f00ce721c0dd693b119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata* llvm::DICompileUnit::ImportedEntities</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### ImportedEntities {#a77057cc109197f161365792577fffd98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::ImportedEntities</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### IsOptimized {#a84077038f8002b988c6e5aa3a519ba0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool llvm::DICompileUnit::IsOptimized</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### IsOptimized {#a1ae687621b0dfd09e0208aab8f73b953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::IsOptimized</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Macros {#a3003292f7da5d92da60ce8ac53eec3a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata* llvm::DICompileUnit::Macros</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### Macros {#a05a2f7d64466bd3ec645fccc1a7326b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::Macros</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### NameTableKind {#a88c0e95d6fe40a377be4a3944afd128d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned llvm::DICompileUnit::NameTableKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### NameTableKind {#af5142a92cd8320fd11238afd12e09c18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::NameTableKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Producer {#a9dd0bc35988e605669d88fd7f045bbc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString* llvm::DICompileUnit::Producer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### Producer {#a5ec4ba546bf8dab9d9594fff08d53d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::Producer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### RangesBaseAddress {#a14e911f4d9b2daa90895180ae997f789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool llvm::DICompileUnit::RangesBaseAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### RangesBaseAddress {#ad68ba4b6396d8f137c09b3a58ce9a112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::RangesBaseAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### RetainedTypes {#a5d1be4355284a09effd3c7047b686582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata* llvm::DICompileUnit::RetainedTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### RetainedTypes {#abcb6f5933d9df319673346c1b4d0b1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::RetainedTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### RuntimeVersion {#a9b401a93fd0913d7714ca7f9c70f4a31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned llvm::DICompileUnit::RuntimeVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### RuntimeVersion {#a515cb0855c3b79722944f43f61844dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::RuntimeVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SDK {#a9baff343830f2e1aa33fe00d88dd78bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString* llvm::DICompileUnit::SDK</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### SourceLanguage {#af51187d4746c0e710f5604cbc8918f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::SourceLanguage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SplitDebugFilename {#aa3cc55f6fd1f2a87914ec4a917d8590e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString* llvm::DICompileUnit::SplitDebugFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### SplitDebugFilename {#a5db5fbe3e8c323c51fbd5f6facf225db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::SplitDebugFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SplitDebugInlining {#aa4629623e8a010db15ddeee6d60f9a10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool llvm::DICompileUnit::SplitDebugInlining</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SplitDebugInlining {#aac49c7f0fafe97c2f837198f507f0ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::SplitDebugInlining</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SysRoot {#aa1c400cf291205295a834f5558c58d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString* llvm::DICompileUnit::SysRoot</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#af9d697248b7d8962046d9e808fe17c09">DEFINE_MDNODE_GET_DISTINCT_TEMPORARY</a>.</p>

</div>
</div>

### SysRoot {#a86150f14f26efa0575a15e68ec955aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Metadata MDString bool MDString unsigned MDString unsigned Metadata Metadata Metadata Metadata Metadata uint64_t bool bool unsigned bool MDString MDString llvm::DICompileUnit::SysRoot</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DebugInfoForProfiling {#ab9fb3c082dd6b3c01e6b5456da818020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::DebugInfoForProfiling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### DWOId {#a6154eb9ab4766471a75506f32d247a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DICompileUnit::DWOId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### EmissionKind {#ab2905cdd4515135dbd9c018f769e9bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DICompileUnit::EmissionKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### IsOptimized {#a6d289703b6eb35e2aa966223e2b66d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::IsOptimized</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### NameTableKind {#a2cad2c86e635b2b76bc966efc8e5953c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DICompileUnit::NameTableKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### RangesBaseAddress {#ace1eb073a2148219cb98f3ab09a4b513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::RangesBaseAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### RuntimeVersion {#a1a2bd50a0bb6a2fab18aafa2c56bb6c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DICompileUnit::RuntimeVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SourceLanguage {#a84f73f76fc996dcbaa304b85af02de90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DICompileUnit::SourceLanguage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SplitDebugInlining {#aabfa18b27f8183f7dd27fb90f175e532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::SplitDebugInlining</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a7797d4a32dbb959f7f4372b6d48f3601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompileUnit::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

### emissionKindString() {#a168bde7847da28592f7c592d0eed28c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DICompileUnit::emissionKindString (<a href="#abbc2b566b9aa870d5b7131017b7ba66d">DebugEmissionKind</a> EK)</td>
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



<p>Declaration at line 1491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 999 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="#abbc2b566b9aa870d5b7131017b7ba66dad9c778495a1251c95f818a65864f504b">DebugDirectivesOnly</a>, <a href="#abbc2b566b9aa870d5b7131017b7ba66daa44087d1fe20ab5e128a0f592b6a85c1">FullDebug</a>, <a href="#abbc2b566b9aa870d5b7131017b7ba66da6b16b60468715f43621c437edef9a3b3">LineTablesOnly</a> and <a href="#abbc2b566b9aa870d5b7131017b7ba66dadb74da0a389a2704e8e01c66ace2913e">NoDebug</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdfieldprinter/#a3e68548b639b11a055a7b6b9138430b8">anonymous{AsmWriter.cpp}::MDFieldPrinter::printEmissionKind</a>.</p>

</div>
</div>

### get() {#af7c558c37352930215ced7f433865751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompileUnit::get ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getEmissionKind() {#afeaa84c982a7493e02d1b547297e0e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DICompileUnit::DebugEmissionKind &gt; DICompileUnit::getEmissionKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Declaration at line 1490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#abbc2b566b9aa870d5b7131017b7ba66dad9c778495a1251c95f818a65864f504b">DebugDirectivesOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#abbc2b566b9aa870d5b7131017b7ba66daa44087d1fe20ab5e128a0f592b6a85c1">FullDebug</a>, <a href="#abbc2b566b9aa870d5b7131017b7ba66da6b16b60468715f43621c437edef9a3b3">LineTablesOnly</a> and <a href="#abbc2b566b9aa870d5b7131017b7ba66dadb74da0a389a2704e8e01c66ace2913e">NoDebug</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a19052e5d06c02fdb8e572529d0acb8f6">llvm::DwarfCompileUnit::includeMinimalInlineScopes</a>.</p>

</div>
</div>

### getIfExists() {#a65bb56033bd3155f6c6905ed17900347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompileUnit::getIfExists ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getNameTableKind() {#a659717c7e0fe157516a881f0de5e1dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DICompileUnit::DebugNameTableKind &gt; DICompileUnit::getNameTableKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Declaration at line 1492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="#a47f44483cc8b041dd1678649b750da01a9f6290f4436e5a2351f12e03b6433c3c">Apple</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#a47f44483cc8b041dd1678649b750da01a7a1920d61156abc05a60135aefe8bc67">Default</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#a47f44483cc8b041dd1678649b750da01ab7e89d55aa08a289aa48277386e6ff1d">GNU</a> and <a href="#a47f44483cc8b041dd1678649b750da01a6adf97f83acf6453d4a6a4b1070f3754">None</a>.</p>

</div>
</div>

### nameTableKindString() {#a153271fe0f31039d8c15c519611204cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DICompileUnit::nameTableKindString (<a href="#a47f44483cc8b041dd1678649b750da01">DebugNameTableKind</a> PK)</td>
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



<p>Declaration at line 1493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1013 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="#a47f44483cc8b041dd1678649b750da01a9f6290f4436e5a2351f12e03b6433c3c">Apple</a>, <a href="#a47f44483cc8b041dd1678649b750da01a7a1920d61156abc05a60135aefe8bc67">Default</a>, <a href="#a47f44483cc8b041dd1678649b750da01ab7e89d55aa08a289aa48277386e6ff1d">GNU</a> and <a href="#a47f44483cc8b041dd1678649b750da01a6adf97f83acf6453d4a6a4b1070f3754">None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdfieldprinter/#a73fbe10c61d14e300d2aecd1ba27cf40">anonymous{AsmWriter.cpp}::MDFieldPrinter::printNameTableKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getImpl() {#adf9ac07be3679f8052a3df89f6e3f6e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompileUnit * llvm::DICompileUnit::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned SourceLanguage, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Producer, bool IsOptimized, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Flags, unsigned RuntimeVersion, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SplitDebugFilename, unsigned EmissionKind, DICompositeTypeArray EnumTypes, DIScopeArray RetainedTypes, DIGlobalVariableExpressionArray GlobalVariables, DIImportedEntityArray ImportedEntities, DIMacroNodeArray Macros, uint64_t DWOId, bool SplitDebugInlining, bool DebugInfoForProfiling, unsigned NameTableKind, bool RangesBaseAddress, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SysRoot, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SDK, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getImpl() {#aebf25a9e8c51a311d6ac9d4eca022719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompileUnit * DICompileUnit::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned SourceLanguage, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * File, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Producer, bool IsOptimized, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Flags, unsigned RuntimeVersion, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * SplitDebugFilename, unsigned EmissionKind, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * EnumTypes, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * RetainedTypes, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * GlobalVariables, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * ImportedEntities, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Macros, uint64_t DWOId, bool SplitDebugInlining, bool DebugInfoForProfiling, unsigned NameTableKind, bool RangesBaseAddress, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * SysRoot, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * SDK, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 1535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
