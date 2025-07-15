---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dicompositetype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DICompositeType` Class Reference

<p>Composite types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DICompositeType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for types. <a href="/web-llvm/docs/api/classes/llvm/ditype/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26763bc93500b3f43f21d9e513304e32">DICompositeType</a> (LLVMContext &amp;C, StorageType Storage, unsigned Tag, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, uint32_t NumExtraInhabitants, DIFlags Flags, ArrayRef&lt; Metadata * &gt; Ops)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae914714a18515bddfe3b77ae64365297">~DICompositeType</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a8e972558c914e250e4cff07943256">replaceElements</a> (DINodeArray Elements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace operands. <a href="#aa8a8e972558c914e250e4cff07943256">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b309980d27dee29157a1c2c2747a7f5">replaceVTableHolder</a> (DIType *VTableHolder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada5141c959b90178aa10deeb3bcab291">replaceTemplateParams</a> (DITemplateParameterArray TemplateParams)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> (DICompositeType,(unsigned Tag, StringRef Name, DIFile *File, unsigned Line, DIScope *Scope, DIType *BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, DIFlags Flags, DINodeArray Elements, unsigned RuntimeLang, DIType *VTableHolder, DITemplateParameterArray TemplateParams=nullptr, StringRef Identifier="", DIDerivedType *Discriminator=nullptr, Metadata *DataLocation=nullptr, Metadata *Associated=nullptr, Metadata *Allocated=nullptr, Metadata *Rank=nullptr, DINodeArray Annotations=nullptr, DIType *Specification=nullptr, uint32_t NumExtraInhabitants=0),(Tag, Name, File, Line, Scope, BaseType, SizeInBits, AlignInBits, OffsetInBits, Specification, NumExtraInhabitants, Flags, Elements, RuntimeLang, VTableHolder, TemplateParams, Identifier, Discriminator, DataLocation, Associated, Allocated, Rank, Annotations)) DEFINE_MDNODE_GET(DICompositeType</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc5c561b9275f48a4f02ced5a4cda0e">getBaseType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DINodeArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cee69d690ed86ce76452279e28793a5">getElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1034598d2193424d72a16363fcfb799">getVTableHolder</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DITemplateParameterArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f32f797838f7521e527b768b3483cfa">getTemplateParams</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a752f20477f301bba0db8fcef7db6588d">getIdentifier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3ec2bbc1252095ec499f353f83c6f0">getRuntimeLang</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6591d66fcff3a248e52d43832383e90">getRawBaseType</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db30ddcf7e6fe53334715fd41bbc086">getRawElements</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a050df020c682005604ffb6805eb4c9dd">getRawVTableHolder</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a811c4e2197f08797b04727a78825a840">getRawTemplateParams</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed0c086b90c36bf35ed9b34c0c5777cc">getRawIdentifier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a5239dc3e926bf57c7d884dd1b76068">getRawDiscriminator</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba54e885d45e215707278aa160a414c">getDiscriminator</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d91a88beed98d0f979a7edcf402b93c">getRawDataLocation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c21843b633c99f35c5ee3663c14dc02">getDataLocation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38bd50db4fbc9402fc3c45b91f4e1f57">getDataLocationExp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40f5594c6dfaa311a641c029dc4853c">getRawAssociated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a447dba85856eab10231dfaf3b52794d4">getAssociated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a48380cb9547fb2884050586c3b43f">getAssociatedExp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c8f53db42ce69eacdf01dfdb20218e">getRawAllocated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2571cadb86a6a976a174cf0e6a9eb426">getAllocated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29e5f4ee2c46536209ea770e3a34487">getAllocatedExp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d3af8f69447353e96e2d6c049c5cab">getRawRank</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad64a25435085ccecade3752118f21eed">getRankConst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0510922f248b2dc490eb49644ea46167">getRankExp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93616928b7a98bf66e5a954d23436290">getRawAnnotations</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DINodeArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2e64febd404c2f88e3d43e3d4963925">getAnnotations</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23386279a41f839a9cb4cc172ad343d1">getRawSpecification</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fd68828c7c0838743420b9d0b48ffca">getSpecification</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa41b1859d43a065b8ad7bdf9c0f9fc55">mutate</a> (unsigned Tag, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, uint32_t NumExtraInhabitants, DIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change fields in place. <a href="#aa41b1859d43a065b8ad7bdf9c0f9fc55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TempDICompositeType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a306f8958f4fd0dcbfa6e6190ccbf4227">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a497076f217cc2fb02976fd000878bcf9">Tag</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6767d2895ceff871d83ac8acd16d0519">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abec58aff1526631a131d420b915ce6">File</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1041eea92d3ceaffb57d6877c2a754fb">Line</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761193b845e5c73cf1532176cf443e25">Scope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83694a85f040c1e2461571e697b78651">BaseType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac15a786c6b03ad5ffef88d8d76d58002">SizeInBits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00751f2b0e5a53eb3b6fe8bd01fb0032">AlignInBits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b5e2b744675847ac283db9f8956e11">OffsetInBits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8908b881f1174918ce495fdd6d7b97e7">Flags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16b715baf6f388121bd0cbf045196f77">Elements</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c34fae826b1493e3c2ebadcacfc40c">RuntimeLang</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af244d701794756a52584291c19fbec5a">VTableHolder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b47e790c985cdfc9eef457e932d6ea8">TemplateParams</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab578543c1fc1927d47f05097eae356c2">Identifier</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f5b11ef419957aef3425d170d5e3060">Discriminator</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab462961d37f9acc4e90463f800767cd2">DataLocation</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c5f322af0cd44491742c3ead672df5">Associated</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8328f0bfb72549d1fcf7013bcf0d80ac">Allocated</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3acbd81fde8e3d7b87f870ea902bf47b">Rank</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b295030d1931e38dd4978fb37e5dabe">Annotations</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a46a26cc42ac59d7e3d7bae5b3a512">Specification</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint64_t uint32_t uint64_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23914a3d92c922cd48aec7aea75cfe6a">NumExtraInhabitants</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83431fd3f958ed8127840bf7f97b680e">RuntimeLang</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e919f6d25f389c3d7305f12ffe1a84b">getODRTypeIfExists</a> (LLVMContext &amp;Context, MDString &amp;Identifier)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> (LLVMContext &amp;Context, MDString &amp;Identifier, unsigned Tag, MDString *Name, Metadata *File, unsigned Line, Metadata *Scope, Metadata *BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, Metadata *Specification, uint32_t NumExtraInhabitants, DIFlags Flags, Metadata *Elements, unsigned RuntimeLang, Metadata *VTableHolder, Metadata *TemplateParams, Metadata *Discriminator, Metadata *DataLocation, Metadata *Associated, Metadata *Allocated, Metadata *Rank, Metadata *Annotations)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> with the given ODR identifier. <a href="#accca8844cacd32b33a52a9c1ddf3876c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee7a6f209c3a862a0e7d5b3cd6ad0e67">classof</a> (const Metadata *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a666c0060208366b1e6a8fae91b3c8f03">getImpl</a> (LLVMContext &amp;Context, unsigned Tag, StringRef Name, Metadata *File, unsigned Line, DIScope *Scope, DIType *BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, DIType *Specification, uint32_t NumExtraInhabitants, DIFlags Flags, DINodeArray Elements, unsigned RuntimeLang, DIType *VTableHolder, DITemplateParameterArray TemplateParams, StringRef Identifier, DIDerivedType *Discriminator, Metadata *DataLocation, Metadata *Associated, Metadata *Allocated, Metadata *Rank, DINodeArray Annotations, StorageType Storage, bool ShouldCreate=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e3c3028a123bc008646c219b5439d5">getImpl</a> (LLVMContext &amp;Context, unsigned Tag, MDString *Name, Metadata *File, unsigned Line, Metadata *Scope, Metadata *BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, DIFlags Flags, Metadata *Elements, unsigned RuntimeLang, Metadata *VTableHolder, Metadata *TemplateParams, MDString *Identifier, Metadata *Discriminator, Metadata *DataLocation, Metadata *Associated, Metadata *Allocated, Metadata *Rank, Metadata *Annotations, Metadata *Specification, uint32_t NumExtraInhabitants, StorageType Storage, bool ShouldCreate=true)</td>
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

<p>Composite types.</p>


<p>TODO: Detach from DerivedTypeBase (split out MDEnumType?). TODO: Create a custom, unrelated node for DW_TAG_array_type.</p>


<p>Definition at line 1174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


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


<p>Definition at line 1175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


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


<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a00751f2b0e5a53eb3b6fe8bd01fb0032">AlignInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a>, <a href="#a8908b881f1174918ce495fdd6d7b97e7">Flags</a>, <a href="#a1041eea92d3ceaffb57d6877c2a754fb">Line</a>, <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>, <a href="#a23914a3d92c922cd48aec7aea75cfe6a">NumExtraInhabitants</a>, <a href="#a75b5e2b744675847ac283db9f8956e11">OffsetInBits</a>, <a href="#ac15a786c6b03ad5ffef88d8d76d58002">SizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a8265bf29997e9e49d47a38a762d4bb0f">llvm::Metadata::Storage</a> and <a href="#a497076f217cc2fb02976fd000878bcf9">Tag</a>.</p>


<p>Referenced by <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DICompositeType() {#a26763bc93500b3f43f21d9e513304e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DICompositeType::DICompositeType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, unsigned Tag, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, uint32_t NumExtraInhabitants, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Ops)</td>
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



<p>Definition at line 1180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~DICompositeType() {#ae914714a18515bddfe3b77ae64365297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DICompositeType::~DICompositeType ()</td>
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



<p>Definition at line 1188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### replaceElements() {#aa8a8e972558c914e250e4cff07943256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompositeType::replaceElements (DINodeArray Elements)</td>
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

<p>Replace operands.</p>


<p>If this <em><a href="/web-llvm/docs/api/classes/llvm/mdnode/#a92fd2fda0d83920749a3b0ef851b4580">isUniqued()</a></em> and not <em><a href="/web-llvm/docs/api/classes/llvm/mdnode/#ac8c31a76a81b27c7307d65575b62084f">isResolved()</a></em>, on a uniquing collision this will be RAUW'ed and deleted. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a <em><a href="/web-llvm/docs/api/classes/llvm/trackingmdref">TrackingMDRef</a></em> to keep track of its movement if necessary.</p>


<p>Definition at line 1386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a16b715baf6f388121bd0cbf045196f77">Elements</a>, <a href="#a8cee69d690ed86ce76452279e28793a5">getElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>

</div>
</div>

### replaceTemplateParams() {#ada5141c959b90178aa10deeb3bcab291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompositeType::replaceTemplateParams (DITemplateParameterArray TemplateParams)</td>
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



<p>Definition at line 1399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a> and <a href="#a1b47e790c985cdfc9eef457e932d6ea8">TemplateParams</a>.</p>

</div>
</div>

### replaceVTableHolder() {#a6b309980d27dee29157a1c2c2747a7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompositeType::replaceVTableHolder (<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * VTableHolder)</td>
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



<p>Definition at line 1395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a> and <a href="#af244d701794756a52584291c19fbec5a">VTableHolder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DEFINE\_MDNODE\_GET() {#a7142c5d3c9e5b4fdfca943357a54ad41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DICompositeType::DEFINE_MDNODE_GET (<a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a>, (unsigned <a href="#a497076f217cc2fb02976fd000878bcf9">Tag</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#a6767d2895ceff871d83ac8acd16d0519">Name</a>, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> *<a href="#a7abec58aff1526631a131d420b915ce6">File</a>, unsigned <a href="#a1041eea92d3ceaffb57d6877c2a754fb">Line</a>, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> *<a href="#a761193b845e5c73cf1532176cf443e25">Scope</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *<a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1">BaseType</a>, uint64_t <a href="#ac15a786c6b03ad5ffef88d8d76d58002">SizeInBits</a>, uint32_t <a href="#a00751f2b0e5a53eb3b6fe8bd01fb0032">AlignInBits</a>, uint64_t <a href="#a75b5e2b744675847ac283db9f8956e11">OffsetInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a8908b881f1174918ce495fdd6d7b97e7">Flags</a>, DINodeArray <a href="#a16b715baf6f388121bd0cbf045196f77">Elements</a>, unsigned RuntimeLang, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *<a href="#af244d701794756a52584291c19fbec5a">VTableHolder</a>, DITemplateParameterArray <a href="#a1b47e790c985cdfc9eef457e932d6ea8">TemplateParams</a>=nullptr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#ab578543c1fc1927d47f05097eae356c2">Identifier</a>="", <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *<a href="#a8f5b11ef419957aef3425d170d5e3060">Discriminator</a>=nullptr, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#ab462961d37f9acc4e90463f800767cd2">DataLocation</a>=nullptr, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#ad1c5f322af0cd44491742c3ead672df5">Associated</a>=nullptr, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a8328f0bfb72549d1fcf7013bcf0d80ac">Allocated</a>=nullptr, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a3acbd81fde8e3d7b87f870ea902bf47b">Rank</a>=nullptr, DINodeArray <a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>=nullptr, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *<a href="#a19a46a26cc42ac59d7e3d7bae5b3a512">Specification</a>=nullptr, uint32_t <a href="#a23914a3d92c922cd48aec7aea75cfe6a">NumExtraInhabitants</a>=0), (<a href="#a497076f217cc2fb02976fd000878bcf9">Tag</a>, <a href="#a6767d2895ceff871d83ac8acd16d0519">Name</a>, <a href="#a7abec58aff1526631a131d420b915ce6">File</a>, <a href="#a1041eea92d3ceaffb57d6877c2a754fb">Line</a>, <a href="#a761193b845e5c73cf1532176cf443e25">Scope</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1">BaseType</a>, <a href="#ac15a786c6b03ad5ffef88d8d76d58002">SizeInBits</a>, <a href="#a00751f2b0e5a53eb3b6fe8bd01fb0032">AlignInBits</a>, <a href="#a75b5e2b744675847ac283db9f8956e11">OffsetInBits</a>, <a href="#a19a46a26cc42ac59d7e3d7bae5b3a512">Specification</a>, <a href="#a23914a3d92c922cd48aec7aea75cfe6a">NumExtraInhabitants</a>, <a href="#a8908b881f1174918ce495fdd6d7b97e7">Flags</a>, <a href="#a16b715baf6f388121bd0cbf045196f77">Elements</a>, RuntimeLang, <a href="#af244d701794756a52584291c19fbec5a">VTableHolder</a>, <a href="#a1b47e790c985cdfc9eef457e932d6ea8">TemplateParams</a>, <a href="#ab578543c1fc1927d47f05097eae356c2">Identifier</a>, <a href="#a8f5b11ef419957aef3425d170d5e3060">Discriminator</a>, <a href="#ab462961d37f9acc4e90463f800767cd2">DataLocation</a>, <a href="#ad1c5f322af0cd44491742c3ead672df5">Associated</a>, <a href="#a8328f0bfb72549d1fcf7013bcf0d80ac">Allocated</a>, <a href="#a3acbd81fde8e3d7b87f870ea902bf47b">Rank</a>, <a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#a00751f2b0e5a53eb3b6fe8bd01fb0032">AlignInBits</a>, <a href="#a8328f0bfb72549d1fcf7013bcf0d80ac">Allocated</a>, <a href="#a9b295030d1931e38dd4978fb37e5dabe">Annotations</a>, <a href="#ad1c5f322af0cd44491742c3ead672df5">Associated</a>, <a href="#a83694a85f040c1e2461571e697b78651">BaseType</a>, <a href="#ab462961d37f9acc4e90463f800767cd2">DataLocation</a>, <a href="#a8f5b11ef419957aef3425d170d5e3060">Discriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a>, <a href="#a16b715baf6f388121bd0cbf045196f77">Elements</a>, <a href="#a7abec58aff1526631a131d420b915ce6">File</a>, <a href="#a8908b881f1174918ce495fdd6d7b97e7">Flags</a>, <a href="#ab578543c1fc1927d47f05097eae356c2">Identifier</a>, <a href="#a1041eea92d3ceaffb57d6877c2a754fb">Line</a>, <a href="#a6767d2895ceff871d83ac8acd16d0519">Name</a>, <a href="#a23914a3d92c922cd48aec7aea75cfe6a">NumExtraInhabitants</a>, <a href="#a75b5e2b744675847ac283db9f8956e11">OffsetInBits</a>, <a href="#a3acbd81fde8e3d7b87f870ea902bf47b">Rank</a>, <a href="#a761193b845e5c73cf1532176cf443e25">Scope</a>, <a href="#ac15a786c6b03ad5ffef88d8d76d58002">SizeInBits</a>, <a href="#a19a46a26cc42ac59d7e3d7bae5b3a512">Specification</a>, <a href="#a497076f217cc2fb02976fd000878bcf9">Tag</a>, <a href="#a1b47e790c985cdfc9eef457e932d6ea8">TemplateParams</a> and <a href="#af244d701794756a52584291c19fbec5a">VTableHolder</a>.</p>

</div>
</div>

### getAllocated() {#a2571cadb86a6a976a174cf0e6a9eb426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIVariable * llvm::DICompositeType::getAllocated ()</td>
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



<p>Definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a93c8f53db42ce69eacdf01dfdb20218e">getRawAllocated</a>.</p>

</div>
</div>

### getAllocatedExp() {#aa29e5f4ee2c46536209ea770e3a34487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * llvm::DICompositeType::getAllocatedExp ()</td>
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



<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a93c8f53db42ce69eacdf01dfdb20218e">getRawAllocated</a>.</p>

</div>
</div>

### getAnnotations() {#ad2e64febd404c2f88e3d43e3d4963925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DINodeArray llvm::DICompositeType::getAnnotations ()</td>
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



<p>Definition at line 1372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#a93616928b7a98bf66e5a954d23436290">getRawAnnotations</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>.</p>

</div>
</div>

### getAssociated() {#a447dba85856eab10231dfaf3b52794d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIVariable * llvm::DICompositeType::getAssociated ()</td>
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



<p>Definition at line 1348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#ad40f5594c6dfaa311a641c029dc4853c">getRawAssociated</a>.</p>

</div>
</div>

### getAssociatedExp() {#a24a48380cb9547fb2884050586c3b43f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * llvm::DICompositeType::getAssociatedExp ()</td>
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



<p>Definition at line 1351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#ad40f5594c6dfaa311a641c029dc4853c">getRawAssociated</a>.</p>

</div>
</div>

### getBaseType() {#afdc5c561b9275f48a4f02ced5a4cda0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIType * llvm::DICompositeType::getBaseType ()</td>
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



<p>Definition at line 1318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a> and <a href="#ae6591d66fcff3a248e52d43832383e90">getRawBaseType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp/#a0b1944244cbb1c8fc276d7ad1d91b726">hasVectorBeenPadded</a>.</p>

</div>
</div>

### getDataLocation() {#a4c21843b633c99f35c5ee3663c14dc02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIVariable * llvm::DICompositeType::getDataLocation ()</td>
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



<p>Definition at line 1341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a7d91a88beed98d0f979a7edcf402b93c">getRawDataLocation</a>.</p>

</div>
</div>

### getDataLocationExp() {#a38bd50db4fbc9402fc3c45b91f4e1f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * llvm::DICompositeType::getDataLocationExp ()</td>
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



<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a7d91a88beed98d0f979a7edcf402b93c">getRawDataLocation</a>.</p>

</div>
</div>

### getDiscriminator() {#a4ba54e885d45e215707278aa160a414c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * llvm::DICompositeType::getDiscriminator ()</td>
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



<p>Definition at line 1337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a928838d3e896f53856bd269829ddf5e0">llvm::DINode::getOperandAs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>.</p>

</div>
</div>

### getElements() {#a8cee69d690ed86ce76452279e28793a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DINodeArray llvm::DICompositeType::getElements ()</td>
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



<p>Definition at line 1319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#a5db30ddcf7e6fe53334715fd41bbc086">getRawElements</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp/#a7f4f80c5865c70bf46985351ff8c4dc6">calcArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp/#a0b1944244cbb1c8fc276d7ad1d91b726">hasVectorBeenPadded</a> and <a href="#aa8a8e972558c914e250e4cff07943256">replaceElements</a>.</p>

</div>
</div>

### getIdentifier() {#a752f20477f301bba0db8fcef7db6588d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DICompositeType::getIdentifier ()</td>
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



<p>Definition at line 1328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a8ca691a16f8c92064df94a30b246b916">llvm::DINode::getStringOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>.</p>

</div>
</div>

### getRankConst() {#ad64a25435085ccecade3752118f21eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt * llvm::DICompositeType::getRankConst ()</td>
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



<p>Definition at line 1362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a11d3af8f69447353e96e2d6c049c5cab">getRawRank</a>.</p>

</div>
</div>

### getRankExp() {#a0510922f248b2dc490eb49644ea46167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * llvm::DICompositeType::getRankExp ()</td>
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



<p>Definition at line 1367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a11d3af8f69447353e96e2d6c049c5cab">getRawRank</a>.</p>

</div>
</div>

### getRawAllocated() {#a93c8f53db42ce69eacdf01dfdb20218e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawAllocated ()</td>
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



<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a2571cadb86a6a976a174cf0e6a9eb426">getAllocated</a> and <a href="#aa29e5f4ee2c46536209ea770e3a34487">getAllocatedExp</a>.</p>

</div>
</div>

### getRawAnnotations() {#a93616928b7a98bf66e5a954d23436290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawAnnotations ()</td>
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



<p>Definition at line 1371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#ad2e64febd404c2f88e3d43e3d4963925">getAnnotations</a>.</p>

</div>
</div>

### getRawAssociated() {#ad40f5594c6dfaa311a641c029dc4853c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawAssociated ()</td>
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



<p>Definition at line 1347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a447dba85856eab10231dfaf3b52794d4">getAssociated</a> and <a href="#a24a48380cb9547fb2884050586c3b43f">getAssociatedExp</a>.</p>

</div>
</div>

### getRawBaseType() {#ae6591d66fcff3a248e52d43832383e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawBaseType ()</td>
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



<p>Definition at line 1331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#afdc5c561b9275f48a4f02ced5a4cda0e">getBaseType</a>.</p>

</div>
</div>

### getRawDataLocation() {#a7d91a88beed98d0f979a7edcf402b93c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawDataLocation ()</td>
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



<p>Definition at line 1340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a4c21843b633c99f35c5ee3663c14dc02">getDataLocation</a> and <a href="#a38bd50db4fbc9402fc3c45b91f4e1f57">getDataLocationExp</a>.</p>

</div>
</div>

### getRawDiscriminator() {#a3a5239dc3e926bf57c7d884dd1b76068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawDiscriminator ()</td>
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



<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>

</div>
</div>

### getRawElements() {#a5db30ddcf7e6fe53334715fd41bbc086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawElements ()</td>
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



<p>Definition at line 1332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a8cee69d690ed86ce76452279e28793a5">getElements</a>.</p>

</div>
</div>

### getRawIdentifier() {#aed0c086b90c36bf35ed9b34c0c5777cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * llvm::DICompositeType::getRawIdentifier ()</td>
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



<p>Definition at line 1335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a928838d3e896f53856bd269829ddf5e0">llvm::DINode::getOperandAs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#a72b38606434dd8cf03b2dd0f9039c488">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::addTypeRef</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>.</p>

</div>
</div>

### getRawRank() {#a11d3af8f69447353e96e2d6c049c5cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawRank ()</td>
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



<p>Definition at line 1361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#ad64a25435085ccecade3752118f21eed">getRankConst</a> and <a href="#a0510922f248b2dc490eb49644ea46167">getRankExp</a>.</p>

</div>
</div>

### getRawSpecification() {#a23386279a41f839a9cb4cc172ad343d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawSpecification ()</td>
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



<p>Definition at line 1376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a4fd68828c7c0838743420b9d0b48ffca">getSpecification</a>.</p>

</div>
</div>

### getRawTemplateParams() {#a811c4e2197f08797b04727a78825a840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawTemplateParams ()</td>
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



<p>Definition at line 1334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a8f32f797838f7521e527b768b3483cfa">getTemplateParams</a>.</p>

</div>
</div>

### getRawVTableHolder() {#a050df020c682005604ffb6805eb4c9dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DICompositeType::getRawVTableHolder ()</td>
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



<p>Definition at line 1333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#ad1034598d2193424d72a16363fcfb799">getVTableHolder</a>.</p>

</div>
</div>

### getRuntimeLang() {#a4c3ec2bbc1252095ec499f353f83c6f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DICompositeType::getRuntimeLang ()</td>
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



<p>Definition at line 1329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>.</p>

</div>
</div>

### getSpecification() {#a4fd68828c7c0838743420b9d0b48ffca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIType * llvm::DICompositeType::getSpecification ()</td>
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



<p>Definition at line 1377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a> and <a href="#a23386279a41f839a9cb4cc172ad343d1">getRawSpecification</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>.</p>

</div>
</div>

### getTemplateParams() {#a8f32f797838f7521e527b768b3483cfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DITemplateParameterArray llvm::DICompositeType::getTemplateParams ()</td>
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



<p>Definition at line 1325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#a811c4e2197f08797b04727a78825a840">getRawTemplateParams</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>.</p>

</div>
</div>

### getVTableHolder() {#ad1034598d2193424d72a16363fcfb799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIType * llvm::DICompositeType::getVTableHolder ()</td>
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



<p>Definition at line 1322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a> and <a href="#a050df020c682005604ffb6805eb4c9dd">getRawVTableHolder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneImpl() {#a306f8958f4fd0dcbfa6e6190ccbf4227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempDICompositeType llvm::DICompositeType::cloneImpl ()</td>
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



<p>Definition at line 1232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### mutate() {#aa41b1859d43a065b8ad7bdf9c0f9fc55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DICompositeType::mutate (unsigned Tag, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, uint32_t NumExtraInhabitants, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags)</td>
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

<p>Change fields in place.</p>

<p>Definition at line 1191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AlignInBits {#a00751f2b0e5a53eb3b6fe8bd01fb0032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t llvm::DICompositeType::AlignInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Allocated {#a8328f0bfb72549d1fcf7013bcf0d80ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata MDString Metadata Metadata Metadata Metadata* llvm::DICompositeType::Allocated = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Annotations {#a9b295030d1931e38dd4978fb37e5dabe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata MDString Metadata Metadata Metadata Metadata Metadata Metadata* llvm::DICompositeType::Annotations = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Associated {#ad1c5f322af0cd44491742c3ead672df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata MDString Metadata Metadata Metadata* llvm::DICompositeType::Associated = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### BaseType {#a83694a85f040c1e2461571e697b78651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata* llvm::DICompositeType::BaseType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### DataLocation {#ab462961d37f9acc4e90463f800767cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata MDString Metadata Metadata* llvm::DICompositeType::DataLocation = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Discriminator {#a8f5b11ef419957aef3425d170d5e3060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata MDString Metadata* llvm::DICompositeType::Discriminator = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Elements {#a16b715baf6f388121bd0cbf045196f77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata* llvm::DICompositeType::Elements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#aa8a8e972558c914e250e4cff07943256">replaceElements</a>.</p>

</div>
</div>

### File {#a7abec58aff1526631a131d420b915ce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata* llvm::DICompositeType::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Flags {#a8908b881f1174918ce495fdd6d7b97e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags llvm::DICompositeType::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Identifier {#ab578543c1fc1927d47f05097eae356c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata MDString* llvm::DICompositeType::Identifier = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#a3e919f6d25f389c3d7305f12ffe1a84b">getODRTypeIfExists</a>.</p>

</div>
</div>

### Line {#a1041eea92d3ceaffb57d6877c2a754fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned llvm::DICompositeType::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Name {#a6767d2895ceff871d83ac8acd16d0519}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString* llvm::DICompositeType::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### NumExtraInhabitants {#a23914a3d92c922cd48aec7aea75cfe6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata MDString Metadata Metadata Metadata Metadata Metadata Metadata Metadata uint32_t llvm::DICompositeType::NumExtraInhabitants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= 0),
      (<a href="#a497076f217cc2fb02976fd000878bcf9">Tag</a>, <a href="#a6767d2895ceff871d83ac8acd16d0519">Name</a>, <a href="#a7abec58aff1526631a131d420b915ce6">File</a>, <a href="#a1041eea92d3ceaffb57d6877c2a754fb">Line</a>, <a href="#a761193b845e5c73cf1532176cf443e25">Scope</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1">BaseType</a>, <a href="#ac15a786c6b03ad5ffef88d8d76d58002">SizeInBits</a>, <a href="#a00751f2b0e5a53eb3b6fe8bd01fb0032">AlignInBits</a>,
       <a href="#a75b5e2b744675847ac283db9f8956e11">OffsetInBits</a>, <a href="#a8908b881f1174918ce495fdd6d7b97e7">Flags</a>, <a href="#a16b715baf6f388121bd0cbf045196f77">Elements</a>, RuntimeLang, <a href="#af244d701794756a52584291c19fbec5a">VTableHolder</a>, <a href="#a1b47e790c985cdfc9eef457e932d6ea8">TemplateParams</a>,
       <a href="#ab578543c1fc1927d47f05097eae356c2">Identifier</a>, <a href="#a8f5b11ef419957aef3425d170d5e3060">Discriminator</a>, <a href="#ab462961d37f9acc4e90463f800767cd2">DataLocation</a>, <a href="#ad1c5f322af0cd44491742c3ead672df5">Associated</a>, <a href="#a8328f0bfb72549d1fcf7013bcf0d80ac">Allocated</a>, <a href="#a3acbd81fde8e3d7b87f870ea902bf47b">Rank</a>,
       <a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>, <a href="#a19a46a26cc42ac59d7e3d7bae5b3a512">Specification</a>, NumExtraInhabitants))
  TempDICompositeType <a href="/web-llvm/docs/api/classes/llvm/ditype/#aedf9e2987dd95705a56a95d9ba80fd44">clone</a>() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return cloneImpl(); }
  static <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *
  getODRType(<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;Context, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &amp;<a href="#ab578543c1fc1927d47f05097eae356c2">Identifier</a>, unsigned <a href="#a497076f217cc2fb02976fd000878bcf9">Tag</a>,
             <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *<a href="#a6767d2895ceff871d83ac8acd16d0519">Name</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a7abec58aff1526631a131d420b915ce6">File</a>, unsigned <a href="#a1041eea92d3ceaffb57d6877c2a754fb">Line</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a761193b845e5c73cf1532176cf443e25">Scope</a>,
             <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1">BaseType</a>, uint64_t <a href="#ac15a786c6b03ad5ffef88d8d76d58002">SizeInBits</a>, uint32_t <a href="#a00751f2b0e5a53eb3b6fe8bd01fb0032">AlignInBits</a>,
             uint64_t <a href="#a75b5e2b744675847ac283db9f8956e11">OffsetInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a19a46a26cc42ac59d7e3d7bae5b3a512">Specification</a>,
             uint32_t NumExtraInhabitants, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a8908b881f1174918ce495fdd6d7b97e7">Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a16b715baf6f388121bd0cbf045196f77">Elements</a>,
             unsigned RuntimeLang, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#af244d701794756a52584291c19fbec5a">VTableHolder</a>,
             <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a1b47e790c985cdfc9eef457e932d6ea8">TemplateParams</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a8f5b11ef419957aef3425d170d5e3060">Discriminator</a>,
             <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#ab462961d37f9acc4e90463f800767cd2">DataLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#ad1c5f322af0cd44491742c3ead672df5">Associated</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a8328f0bfb72549d1fcf7013bcf0d80ac">Allocated</a>,
             <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a3acbd81fde8e3d7b87f870ea902bf47b">Rank</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>)
</div>
</dd>
</dl>

<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### OffsetInBits {#a75b5e2b744675847ac283db9f8956e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t llvm::DICompositeType::OffsetInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Rank {#a3acbd81fde8e3d7b87f870ea902bf47b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata MDString Metadata Metadata Metadata Metadata Metadata* llvm::DICompositeType::Rank = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### RuntimeLang {#a18c34fae826b1493e3c2ebadcacfc40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned llvm::DICompositeType::RuntimeLang</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Scope {#a761193b845e5c73cf1532176cf443e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata* llvm::DICompositeType::Scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### SizeInBits {#ac15a786c6b03ad5ffef88d8d76d58002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t llvm::DICompositeType::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Specification {#a19a46a26cc42ac59d7e3d7bae5b3a512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata MDString Metadata Metadata Metadata Metadata Metadata Metadata Metadata* llvm::DICompositeType::Specification = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a> and <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Tag {#a497076f217cc2fb02976fd000878bcf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DICompositeType::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### TemplateParams {#a1b47e790c985cdfc9eef457e932d6ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata Metadata* llvm::DICompositeType::TemplateParams = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#ada5141c959b90178aa10deeb3bcab291">replaceTemplateParams</a>.</p>

</div>
</div>

### VTableHolder {#af244d701794756a52584291c19fbec5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString Metadata unsigned Metadata Metadata uint64_t uint32_t uint64_t DIFlags Metadata unsigned Metadata* llvm::DICompositeType::VTableHolder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#accca8844cacd32b33a52a9c1ddf3876c">buildODRType</a>, <a href="#a7142c5d3c9e5b4fdfca943357a54ad41">DEFINE_MDNODE_GET</a> and <a href="#a6b309980d27dee29157a1c2c2747a7f5">replaceVTableHolder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RuntimeLang {#a83431fd3f958ed8127840bf7f97b680e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DICompositeType::RuntimeLang</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### buildODRType() {#accca8844cacd32b33a52a9c1ddf3876c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DICompositeType::buildODRType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &amp; Identifier, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Specification, uint32_t NumExtraInhabitants, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Elements, unsigned RuntimeLang, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * VTableHolder, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * TemplateParams, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Discriminator, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * DataLocation, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Associated, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Allocated, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Rank, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Annotations)</td>
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

<p>Build a <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> with the given ODR identifier.</p>


<p>Looks up the mapped <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> for the given ODR <span class="doxyComputerOutput">Identifier</span>. If it doesn't exist, creates a new one. If it does exist and <em><a href="/web-llvm/docs/api/classes/llvm/ditype/#a78039d632c4d3f50030540598ba03b47">isForwardDecl()</a></em>, and the new arguments would be a definition, mutates the the type in place. In either case, returns the type.</p>


<p>If not <em><a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a89d7bf0d39222f8aba5ebf358076ce50">LLVMContext::isODRUniquingDebugTypes()</a></em>, this function returns nullptr.</p>


<p>Declaration at line 1308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a00751f2b0e5a53eb3b6fe8bd01fb0032">AlignInBits</a>, <a href="#a8328f0bfb72549d1fcf7013bcf0d80ac">Allocated</a>, <a href="#a9b295030d1931e38dd4978fb37e5dabe">Annotations</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1c5f322af0cd44491742c3ead672df5">Associated</a>, <a href="#a83694a85f040c1e2461571e697b78651">BaseType</a>, <a href="#ab462961d37f9acc4e90463f800767cd2">DataLocation</a>, <a href="#a8f5b11ef419957aef3425d170d5e3060">Discriminator</a>, <a href="#a16b715baf6f388121bd0cbf045196f77">Elements</a>, <a href="#a7abec58aff1526631a131d420b915ce6">File</a>, <a href="#a8908b881f1174918ce495fdd6d7b97e7">Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ab578543c1fc1927d47f05097eae356c2">Identifier</a>, <a href="#a1041eea92d3ceaffb57d6877c2a754fb">Line</a>, <a href="#a6767d2895ceff871d83ac8acd16d0519">Name</a>, <a href="#a23914a3d92c922cd48aec7aea75cfe6a">NumExtraInhabitants</a>, <a href="#a75b5e2b744675847ac283db9f8956e11">OffsetInBits</a>, <a href="#a3acbd81fde8e3d7b87f870ea902bf47b">Rank</a>, <a href="#a761193b845e5c73cf1532176cf443e25">Scope</a>, <a href="#ac15a786c6b03ad5ffef88d8d76d58002">SizeInBits</a>, <a href="#a19a46a26cc42ac59d7e3d7bae5b3a512">Specification</a>, <a href="#a497076f217cc2fb02976fd000878bcf9">Tag</a>, <a href="#a1b47e790c985cdfc9eef457e932d6ea8">TemplateParams</a> and <a href="#af244d701794756a52584291c19fbec5a">VTableHolder</a>.</p>

</div>
</div>

### classof() {#aee7a6f209c3a862a0e7d5b3cd6ad0e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DICompositeType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Definition at line 1404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

### getODRTypeIfExists() {#a3e919f6d25f389c3d7305f12ffe1a84b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DICompositeType::getODRTypeIfExists (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &amp; Identifier)</td>
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



<p>Declaration at line 1295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab578543c1fc1927d47f05097eae356c2">Identifier</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getImpl() {#a666c0060208366b1e6a8fae91b3c8f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * llvm::DICompositeType::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Specification, uint32_t NumExtraInhabitants, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, DINodeArray Elements, unsigned RuntimeLang, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * VTableHolder, DITemplateParameterArray TemplateParams, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Identifier, <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * Discriminator, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * DataLocation, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Associated, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Allocated, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Rank, DINodeArray Annotations, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getImpl() {#a08e3c3028a123bc008646c219b5439d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompositeType * DICompositeType::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Elements, unsigned RuntimeLang, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * VTableHolder, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * TemplateParams, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Identifier, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Discriminator, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * DataLocation, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Associated, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Allocated, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Rank, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Annotations, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Specification, uint32_t NumExtraInhabitants, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 1221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

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
