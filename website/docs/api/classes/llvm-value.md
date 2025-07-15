---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/value
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Value` Class Reference

<p>LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Representation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Value { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodeconstant">BitcodeConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents a constant expression or constant aggregate using a custom structure internal to the bitcode reader. <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodeconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents an incoming formal argument to a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. <a href="/web-llvm/docs/api/classes/llvm/argument/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM Basic Block Representation. <a href="/web-llvm/docs/api/classes/llvm/basicblock/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadataasvalue">MetadataAsValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> wrapper in the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> hierarchy. <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91de4dfc49ed35db2100baf2faadc4e3">use_iterator</a> = use_iterator_impl&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef85ed36696cbc1a79882afb4e00d88">const_use_iterator</a> = use_iterator_impl&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2fbee42afeb868be98aaae56528636">user_iterator</a> = user_iterator_impl&lt; <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146665db2d7a79fa164098370a3a34c4">const_user_iterator</a> = user_iterator_impl&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#a19833a77591e9d860373ab7fc4793044">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of operands in the subclass. <a href="#a19833a77591e9d860373ab7fc4793044">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ReplaceMetadataUses { <a href="#aa371444bde2d15bdcfa3a523d31ac252">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ValueTy { <a href="#af6d11b38374c4f9e6ba3a6407da2dee0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Concrete subclass of this. <a href="#af6d11b38374c4f9e6ba3a6407da2dee0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cbd9e338a58f62b38e2b820de8c1e6f">ValueAsMetadata</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3382a955d5cfa8adec3e002ffd6c2b72">ValueHandleBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89fb6f29d69f077a86d811c6331681d1">Value</a> (const Value &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18dbfcb332af7515599ee795cf462843">Value</a> (Type *Ty, unsigned scid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a578f458da8a4ab67052dba0f7bffdd">~Value</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a>'s destructor should be virtual by design, but that would require that <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> and all of its subclasses have a vtable that effectively duplicates the information in the value <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a3a578f458da8a4ab67052dba0f7bffdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd5773aff310a001b58365f1298afb1b">operator=</a> (const Value &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef569d822dbf572ae71954d6831ce8a9">getMetadata</a> (unsigned KindID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current metadata attachments for the given kind, if any. <a href="#aef569d822dbf572ae71954d6831ce8a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c4c0580bdb7ccc8210222c7b22522b7">getMetadata</a> (StringRef Kind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b1bc6f9347dade1932d5e0a0be7904">getMetadata</a> (unsigned KindID, SmallVectorImpl&lt; MDNode * &gt; &amp;MDs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Appends all attachments with the given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to <span class="doxyComputerOutput">MDs</span> in insertion order. <a href="#aa8b1bc6f9347dade1932d5e0a0be7904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af580f3203cd4b561487e08bb1fd1d1ae">getMetadata</a> (StringRef Kind, SmallVectorImpl&lt; MDNode * &gt; &amp;MDs) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c13b9effae3289c194af4ca1865e4e">hasMetadata</a> (unsigned KindID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this value has the given type of metadata attached. <a href="#ac8c13b9effae3289c194af4ca1865e4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ece1c601517c563294f590d2cff210d">hasMetadata</a> (StringRef Kind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a338590123630c357df6340c38d066572">setMetadata</a> (unsigned KindID, MDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a particular kind of metadata attachment. <a href="#a338590123630c357df6340c38d066572">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9542c54e3e3ac516ab7437ae1b98bea8">setMetadata</a> (StringRef Kind, MDNode *Node)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1b0638c63ba711320b3bb9c69367ed6">addMetadata</a> (unsigned KindID, MDNode &amp;MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a metadata attachment. <a href="#aa1b0638c63ba711320b3bb9c69367ed6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97df41793a6441c58ab81b883ef106fa">addMetadata</a> (StringRef Kind, MDNode &amp;MD)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e56c814d11206720cc23059b871128d">print</a> (raw_ostream &amp;O, bool IsForDebug=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a1e56c814d11206720cc23059b871128d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba690234245eaba66ec19c429aaa7b3">print</a> (raw_ostream &amp;O, ModuleSlotTracker &amp;MST, bool IsForDebug=false) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62213d5211c9d944e5ede1f0059a6ae2">printAsOperand</a> (raw_ostream &amp;O, bool PrintType=true, const Module *M=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the name of this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> out to the specified <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#a62213d5211c9d944e5ede1f0059a6ae2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71c852fe821d8efa8a9cb0c359380ac7">printAsOperand</a> (raw_ostream &amp;O, bool PrintType, ModuleSlotTracker &amp;MST) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d640257f7689aa8095dccfb111e50c">deleteValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete a pointer to a generic <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a99d640257f7689aa8095dccfb111e50c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7dca9a9e816ef69fd9e9467f64f72b4">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support for debugging, callable in GDB: V-&gt;<a href="#af7dca9a9e816ef69fd9e9467f64f72b4">dump()</a> <a href="#af7dca9a9e816ef69fd9e9467f64f72b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0344a49526443edf90cc0aef3abd3337">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All values are typed, get the type of this value. <a href="#a0344a49526443edf90cc0aef3abd3337">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All values hold a context through their type. <a href="#ab3fc0225d8aaf8434026c3573f961f2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d88ae321b98d8a3b7f394977ae6d7f">hasName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0974858ce658c475882ec1f6082145de">ValueName</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f268730c076a9546009ede05e0dc41">getValueName</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a924b832eebd603551f849b631c8e5566">setValueName</a> (ValueName *VN)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb5c319f5905c1d3ca9eb5df546388c5">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a constant reference to the value's name. <a href="#adb5c319f5905c1d3ca9eb5df546388c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ee267850af7c235474a8c46c7ac5af">setName</a> (const Twine &amp;Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the name of the value. <a href="#a35ee267850af7c235474a8c46c7ac5af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae855357b6c5e6e7ed1869272708a3a84">takeName</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer the name from V to this value. <a href="#ae855357b6c5e6e7ed1869272708a3a84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391ffe96dd8c686b0d2620c7fb25f8a5">getNameOrAsOperand</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab5fc45117b450e8bb04e564cb6e5f2">replaceAllUsesWith</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change all uses of this to point to a new <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a3ab5fc45117b450e8bb04e564cb6e5f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f750cccc69c91465adea3e30ee2165">replaceNonMetadataUsesWith</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change non-metadata uses of this to point to a new <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#ae0f750cccc69c91465adea3e30ee2165">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e8dad1701aa6445be4a29f654b0473c">replaceUsesWithIf</a> (Value *New, llvm::function_ref&lt; bool(Use &amp;U)&gt; ShouldReplace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go through the uses list for this definition and make each use point to "V" if the callback ShouldReplace returns true for the given <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>. <a href="#a7e8dad1701aa6445be4a29f654b0473c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa56e7093b552d99d48d66c5ae781236a">replaceUsesOutsideBlock</a> (Value *V, BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>replaceUsesOutsideBlock - Go through the uses list for this definition and make each use point to "V" instead of "this" when the use is outside the block. <a href="#aa56e7093b552d99d48d66c5ae781236a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2986c3fbc5cdd954a818288692245b0d">assertModuleIsMaterializedImpl</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d7de807ebdfe1819df3ff6cb0f16158">use_empty</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a98b54fc834c577a61e455e7157b2b">materialized_use_empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a91de4dfc49ed35db2100baf2faadc4e3">use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad234db7c28b66de3845bb86249cac2">materialized_use_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1ef85ed36696cbc1a79882afb4e00d88">const_use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a316b721bb6a1794140cd580f5b031">materialized_use_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a91de4dfc49ed35db2100baf2faadc4e3">use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a413abcab8dbc3900fc2fde96a5d8fca6">use_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1ef85ed36696cbc1a79882afb4e00d88">const_use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24018b06ac0d956553428c86d5af7d5e">use_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a91de4dfc49ed35db2100baf2faadc4e3">use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86469939d2a8bdd4169be9403b89f5a">use_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1ef85ed36696cbc1a79882afb4e00d88">const_use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac124783761e79d74db1e97d38224216b">use_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a91de4dfc49ed35db2100baf2faadc4e3">use_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e05a5aed47fc02cbb7f252d489b405c">materialized_uses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a1ef85ed36696cbc1a79882afb4e00d88">const_use_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a8eddca4c6b9167400f54beb8786343">materialized_uses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a91de4dfc49ed35db2100baf2faadc4e3">use_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf855b7cd63a0cd7f73759e396f280c9">uses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a1ef85ed36696cbc1a79882afb4e00d88">const_use_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224d0ab04e6510402fb5c7221666efed">uses</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21f61086e696a788f549768fdc26a93">user_empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acd2fbee42afeb868be98aaae56528636">user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf1d82a256748288e01404b1903f762b">materialized_user_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a146665db2d7a79fa164098370a3a34c4">const_user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5f5400d4e88bcef211808e582a0be27">materialized_user_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acd2fbee42afeb868be98aaae56528636">user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158da2b6d3d938aaa15b6acd00150e2c">user_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a146665db2d7a79fa164098370a3a34c4">const_user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affbc364be263e23ef9f54686c947ca6c">user_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acd2fbee42afeb868be98aaae56528636">user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22118b2b3f206bfda2ffab4cda94d64">user_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a146665db2d7a79fa164098370a3a34c4">const_user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9d0fa4bc2ba8b0bdbf059790c055340">user_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user">User</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46db903db2484e1ef5062d094d6b0854">user_back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d3fe5f30609b50112d91f41d268567">user_back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#acd2fbee42afeb868be98aaae56528636">user_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0104cde53b84260b50b2557f1f718d96">materialized_users</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a146665db2d7a79fa164098370a3a34c4">const_user_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d8aaa6a925b40c09fdbf6d7ab332fd">materialized_users</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#acd2fbee42afeb868be98aaae56528636">user_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411cf3e3932f209ce3374cb31adc1da6">users</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a146665db2d7a79fa164098370a3a34c4">const_user_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47e5062f8da90137678150d09bb17751">users</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a402430a1bbe70a9282dcb0e0b6a2cd">hasOneUse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is exactly one use of this value. <a href="#a3a402430a1bbe70a9282dcb0e0b6a2cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c779ce2ba55bc94f52014fc25f3d520">hasNUses</a> (unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> has exactly N uses. <a href="#a7c779ce2ba55bc94f52014fc25f3d520">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fb137716cff838d389e392b9729dc9">hasNUsesOrMore</a> (unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this value has N uses or more. <a href="#a72fb137716cff838d389e392b9729dc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e987c6af902aad6baa39bd5b7ef322c">hasOneUser</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is exactly one user of this value. <a href="#a2e987c6af902aad6baa39bd5b7ef322c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae600e148910c49a1772ce51754141c">getSingleUndroppableUse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is exactly one use of this value that cannot be dropped. <a href="#a7ae600e148910c49a1772ce51754141c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7cde93d3843abb013fe880c58e7f83">getSingleUndroppableUse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user">User</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93270009c3358fba0a61654a9376ab4c">getUniqueUndroppableUser</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is exactly one unique user of this value that cannot be dropped (that user can have multiple uses of this value). <a href="#a93270009c3358fba0a61654a9376ab4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28ed67ff84559f2ca8a0b5975d03cbce">getUniqueUndroppableUser</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2480ba07d44a392d73449bd7269bcc4">hasNUndroppableUses</a> (unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there this value. <a href="#af2480ba07d44a392d73449bd7269bcc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b32d493aada47e4eff2cd28f0753be8">hasNUndroppableUsesOrMore</a> (unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this value has N uses or more. <a href="#a2b32d493aada47e4eff2cd28f0753be8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1fda0e425c4102e16fe73928efcd750">dropDroppableUses</a> (llvm::function_ref&lt; bool(const Use *)&gt; ShouldDrop=[](const Use *) { return true;})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove every uses that can safely be removed. <a href="#aa1fda0e425c4102e16fe73928efcd750">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a731895a3f577718bbaec9b180eb2a6bb">dropDroppableUsesIn</a> (User &amp;Usr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove every use of this value in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></span> that can safely be removed. <a href="#a731895a3f577718bbaec9b180eb2a6bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55bba6bcd9b098e1c227011e6cd66300">isUsedInBasicBlock</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this value is used in the specified basic block. <a href="#a55bba6bcd9b098e1c227011e6cd66300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba0055050d741f60b6e0523507a2c79f">getNumUses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method computes the number of uses of this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#aba0055050d741f60b6e0523507a2c79f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8c61025e1632cf57e24e59163e3df9c">addUse</a> (Use &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should only be used by the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> class. <a href="#aa8c61025e1632cf57e24e59163e3df9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6ca5a5b87bd84231be9d8dbec46c1a">getValueID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the concrete type of this object. <a href="#a4a6ca5a5b87bd84231be9d8dbec46c1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3408c3cf2cef0f378bab40f6660c3341">getRawSubclassOptionalData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the raw optional flags value contained in this value. <a href="#a3408c3cf2cef0f378bab40f6660c3341">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48790dc28d4007833380faed30c9f44c">clearSubclassOptionalData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the optional flags contained in this value. <a href="#a48790dc28d4007833380faed30c9f44c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48638782e724669238a05c0859b35e0">hasSameSubclassOptionalData</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the optional flags for equality. <a href="#aa48638782e724669238a05c0859b35e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab978072498608d7bd344804926c2a91a">hasValueHandle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is a value handle associated with this value. <a href="#ab978072498608d7bd344804926c2a91a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cfd8c0f6033a51197c2ef2b00beeca6">isUsedByMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is metadata referencing this value. <a href="#a6cfd8c0f6033a51197c2ef2b00beeca6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98897a3d01f6a4d7f10a5ac8fe862c82">isSwiftError</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this value is a swifterror value. <a href="#a98897a3d01f6a4d7f10a5ac8fe862c82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a966eb231e7d4e572874d2cb49b18faea">stripPointerCasts</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Strip off pointer casts, all-zero GEPs and address space casts. <a href="#a966eb231e7d4e572874d2cb49b18faea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ad28e3c7d7c2f0c2ecb5ddcd1da355">stripPointerCasts</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3111ed9ce005478f88fbf8d102a89fe9">stripPointerCastsAndAliases</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Strip off pointer casts, all-zero GEPs, address space casts, and aliases. <a href="#a3111ed9ce005478f88fbf8d102a89fe9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a559c1ffcea756dea87714e5d51ed82f4">stripPointerCastsAndAliases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0f0124982d06eda91a2ab22cc1534c">stripPointerCastsSameRepresentation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Strip off pointer casts, all-zero GEPs and address space casts but ensures the representation of the result stays the same. <a href="#a9a0f0124982d06eda91a2ab22cc1534c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20551fe1b3fb3429d78ac77b4f81a54">stripPointerCastsSameRepresentation</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ce93500c8d9a8fbd0a40e461f3b780">stripPointerCastsForAliasAnalysis</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Strip off pointer casts, all-zero GEPs, single-argument phi nodes and invariant group info. <a href="#af7ce93500c8d9a8fbd0a40e461f3b780">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac433d0ecf347d8fc3d4786002f31d7e9">stripPointerCastsForAliasAnalysis</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3711f4a2446d9e9302ebfa2fb1180883">stripInBoundsConstantOffsets</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Strip off pointer casts and all-constant inbounds GEPs. <a href="#a3711f4a2446d9e9302ebfa2fb1180883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acab7642aedd7e0d2e7b5857d99328c25">stripInBoundsConstantOffsets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23c582e2452eeb2b2cf6e0c43eca617e">stripAndAccumulateConstantOffsets</a> (const DataLayout &amp;DL, APInt &amp;Offset, bool AllowNonInbounds, bool AllowInvariantGroup=false, function_ref&lt; bool(Value &amp;Value, APInt &amp;Offset)&gt; ExternalAnalysis=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accumulate the constant offset this value has compared to a base pointer. <a href="#a23c582e2452eeb2b2cf6e0c43eca617e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a551ea28693c8f39b40d76f5255ca930d">stripAndAccumulateConstantOffsets</a> (const DataLayout &amp;DL, APInt &amp;Offset, bool AllowNonInbounds, bool AllowInvariantGroup=false, function_ref&lt; bool(Value &amp;Value, APInt &amp;Offset)&gt; ExternalAnalysis=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f27b1cef50a1f887650a8c79dbb436">stripAndAccumulateInBoundsConstantOffsets</a> (const DataLayout &amp;DL, APInt &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a wrapper around stripAndAccumulateConstantOffsets with the in-bounds requirement set to false. <a href="#a14f27b1cef50a1f887650a8c79dbb436">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a574f86d538a28119d082be202fedb615">stripAndAccumulateInBoundsConstantOffsets</a> (const DataLayout &amp;DL, APInt &amp;Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed745230c0e6c52f4b1ec0dae8c07fb">stripInBoundsOffsets</a> (function_ref&lt; void(const Value *)&gt; Func=[](const Value *) {}) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Strip off pointer casts and inbounds GEPs. <a href="#a3ed745230c0e6c52f4b1ec0dae8c07fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0443930d9dd02213bbc46588a7af488d">stripInBoundsOffsets</a> (function_ref&lt; void(const Value *)&gt; Func=[](const Value *) {})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5e4e131889dc27ebec32f382c835971">getPointerOffsetFrom</a> (const Value *Other, const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this ptr is provably equal to <span class="doxyComputerOutput">Other</span> plus a constant offset, return that offset in bytes. <a href="#ac5e4e131889dc27ebec32f382c835971">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b4d048a84149ece45db862333dea428">canBeFreed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the memory object referred to by V can by freed in the scope for which the SSA value defining the allocation is statically defined. <a href="#a7b4d048a84149ece45db862333dea428">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfdc7354dccb27bc092d9ac8c92b76c7">getPointerDereferenceableBytes</a> (const DataLayout &amp;DL, bool &amp;CanBeNull, bool &amp;CanBeFreed) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of bytes known to be dereferenceable for the pointer value. <a href="#acfdc7354dccb27bc092d9ac8c92b76c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f5c74e1b14ba4a61db057400644acc">getPointerAlignment</a> (const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an alignment of the pointer value. <a href="#a47f5c74e1b14ba4a61db057400644acc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a159bf794249e0567baf2a2a714d5c679">DoPHITranslation</a> (const BasicBlock *CurBB, const BasicBlock *PredBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Translate PHI node to its predecessor from the given basic block. <a href="#a159bf794249e0567baf2a2a714d5c679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1948efb247cc6e24d34a083f8c742b4">DoPHITranslation</a> (const BasicBlock *CurBB, const BasicBlock *PredBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f09c2c9951158f9eecfaf7068d7b20">mutateType</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mutate the type of this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to be of the specified type. <a href="#ac0f09c2c9951158f9eecfaf7068d7b20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Compare&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a44e27e6f869703f42ebd1b050a75a121">sortUseList</a> (Compare Cmp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort the use-list. <a href="#a44e27e6f869703f42ebd1b050a75a121">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25fd4916e8bb37be03d9f9b1279d5abc">reverseUseList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverse the use-list. <a href="#a25fd4916e8bb37be03d9f9b1279d5abc">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d200b1568f70b28ae0eb9bec58d6690">getAllMetadata</a> (SmallVectorImpl&lt; std::pair&lt; unsigned, MDNode * &gt; &gt; &amp;MDs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Appends all metadata attached to this value to <span class="doxyComputerOutput">MDs</span>, sorting by KindID. <a href="#a3d200b1568f70b28ae0eb9bec58d6690">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f496e54accb2cbe919fb456cb703f1a">hasMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this value has any metadata attached to it. <a href="#a1f496e54accb2cbe919fb456cb703f1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d88e21e9caa53945e903fd8c8700b4f">eraseMetadata</a> (unsigned KindID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase all metadata attachments with the given kind. <a href="#a9d88e21e9caa53945e903fd8c8700b4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1198eef44b311a7984cfc8fc97fac6d">eraseMetadataIf</a> (function_ref&lt; bool(unsigned, MDNode *)&gt; Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase all metadata attachments matching the given predicate. <a href="#ab1198eef44b311a7984cfc8fc97fac6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad151fceb9a0e77a8a8017d4f68791811">clearMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase all metadata attached to this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#ad151fceb9a0e77a8a8017d4f68791811">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59e5e9e741eead6d5b460cd28c473039">getMetadataImpl</a> (unsigned KindID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get metadata for the given kind, if any. <a href="#a59e5e9e741eead6d5b460cd28c473039">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05810d77360abad7ef2848184726d872">getSubclassDataFromValue</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae37705b598ef612f698198dc33d6f65">setValueSubclassData</a> (unsigned short D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8546e0e58990802037f15bc6d0ed65a2">destroyValueName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86c6a7f4d22622f24ff54f06b56d4ad">doRAUW</a> (Value *New, ReplaceMetadataUses)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228ec544914e8774e6192e13107dfb16">setNameImpl</a> (const Twine &amp;Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e38886795ed32ec28d4eb5dc92b6a4">SubclassOptionalData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold subclass data that can be dropped. <a href="#a21e38886795ed32ec28d4eb5dc92b6a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ef1cd0d25962bbb4785ae14258ed5d">NumUserOperands</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e7ed12d09bbe90b2061208177e2a3ba">IsUsedByMD</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a174c05075799a1b8213851ca52e9567c">HasName</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb4a52a4675976293ae4f77c982667b">HasMetadata</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe68086704afcf3325b6b9b14ca4b625">HasHungOffUses</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae534948f447c9e41a6890b01a8c13f0a">HasDescriptor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c6b58cf95a021591c108bcbec3eba6">SubclassID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa8f00af7144aac23602a137348d56da">HasValueHandle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed5dfa35f786c0e3bb2100ed095c4c5">SubclassData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold arbitrary subclass data. <a href="#a9ed5dfa35f786c0e3bb2100ed095c4c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefe036851d3148494382b70456624011">VTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312a6480f43c51cc705649c0b69affa8">UseList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44beb55f865ee8a8e42c3a9adeb599e2">dropDroppableUse</a> (Use &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the droppable use <span class="doxyComputerOutput">U</span>. <a href="#a44beb55f865ee8a8e42c3a9adeb599e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Compare&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f47772e8b597f1c1f42ab3802bd0891">mergeUseLists</a> (Use *L, Use *R, Compare Cmp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge two lists together. <a href="#a7f47772e8b597f1c1f42ab3802bd0891">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5941ebb386c8b46a569d1d8dbfe0c8c">MaxAlignmentExponent</a> = 32</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum alignment for instructions. <a href="#ab5941ebb386c8b46a569d1d8dbfe0c8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089e46429cea4cfcd2ba23a6fc6aa676">MaximumAlignment</a> = 1ULL &lt;&lt; <a href="#ab5941ebb386c8b46a569d1d8dbfe0c8c">MaxAlignmentExponent</a></td>
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

<p>LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Representation.</p>


<p>This is a very important LLVM class. It is the base class of all values computed by a program that may be used as operands to other values. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is the super class of other important classes such as <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> and <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. All Values have a <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> is not a subclass of <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. Some values can have a name and they belong to some <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. Setting the name on the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> automatically updates the module's symbol table.</p>


<p>Every value has a "use list" that keeps track of which other Values are using this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. A <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> can also have an arbitrary number of ValueHandle objects that watch it and listen to RAUW and Destroy events. See <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a> for details.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_use\_iterator {#a1ef85ed36696cbc1a79882afb4e00d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Value::const_use_iterator =  use_iterator_impl&lt;const Use&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### const\_user\_iterator {#a146665db2d7a79fa164098370a3a34c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Value::const_user_iterator =  user_iterator_impl&lt;const User&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### use\_iterator {#a91de4dfc49ed35db2100baf2faadc4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Value::use_iterator =  use_iterator_impl&lt;Use&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### user\_iterator {#acd2fbee42afeb868be98aaae56528636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Value::user_iterator =  user_iterator_impl&lt;User&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a19833a77591e9d860373ab7fc4793044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
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

<p>The number of operands in the subclass.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumUserOperandsBits<a id="a19833a77591e9d860373ab7fc4793044a6050aee72ddd23b6d91ec3f126679fec"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

</table>
</dd>
</dl>


<p>This member is defined by this class, but not used for anything. Subclasses can use it to store their number of operands, if they have any.</p>


<p>This is stored here to save space in <a href="/web-llvm/docs/api/classes/llvm/user">User</a> on 64-bit hosts. Since most instances of <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> have operands, 32-bit hosts aren't significantly affected.</p>


<p>Note, this should <em>NOT</em> be used directly by any class other than <a href="/web-llvm/docs/api/classes/llvm/user">User</a>. <a href="/web-llvm/docs/api/classes/llvm/user">User</a> uses this value to find the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> list.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### ReplaceMetadataUses {#aa371444bde2d15bdcfa3a523d31ac252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::Value::ReplaceMetadataUses </td>
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
<td class="doxyEnumItemName">No<a id="aa371444bde2d15bdcfa3a523d31ac252abafd7322c6e97d25b6299b5d6fe8920b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Yes<a id="aa371444bde2d15bdcfa3a523d31ac252a93cba07454f06a4a960172bbd6e2a435"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### ValueTy {#af6d11b38374c4f9e6ba3a6407da2dee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Value::ValueTy </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Concrete subclass of this.</p>


<p>An enumeration for keeping track of the concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that is actually instantiated. Values of this enumeration are kept in the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> classes SubclassID field. They are used for concrete type identification.</p>


<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ValueAsMetadata {#a3cbd9e338a58f62b38e2b820de8c1e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a3cbd9e338a58f62b38e2b820de8c1e6f">ValueAsMetadata</a>.</p>


<p>Referenced by <a href="#a3cbd9e338a58f62b38e2b820de8c1e6f">ValueAsMetadata</a>.</p>

</div>
</div>

### ValueHandleBase {#a3382a955d5cfa8adec3e002ffd6c2b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a18dbfcb332af7515599ee795cf462843">Value</a> and <a href="#a3382a955d5cfa8adec3e002ffd6c2b72">ValueHandleBase</a>.</p>


<p>Referenced by <a href="#a3382a955d5cfa8adec3e002ffd6c2b72">ValueHandleBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Value() {#a89fb6f29d69f077a86d811c6331681d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Value::Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Value() {#a18dbfcb332af7515599ee795cf462843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value::Value (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned scid)</td>
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



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="/web-llvm/docs/api/classes/llvm/use/#a53a48d67682705c5f7f06ffc850fd622">llvm::Use::getUser</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/valuesclass/#a2a1330b2b94b8e67c055e8b14fa01e5a">llvm::cl::ValuesClass::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodeconstant/#affe793be91af250a2844bc56371d510b">anonymous{BitcodeReader.cpp}::BitcodeConstant::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#ad904765991a90849720e14565ceca7d5">llvm::Argument::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1dfb5f698e35730791c0176a7c6c4b0a">llvm::BasicBlock::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#afaf51ba283866e0cc1400691f2956c49">llvm::InlineAsm::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#aaf3b2a9fa43c739eca76fdd58900d2fa">llvm::MetadataAsValue::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a8fc5e85e2959f635fbb7492697aec86e">llvm::User::classof</a>, <a href="#ab1948efb247cc6e24d34a083f8c742b4">DoPHITranslation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4bf8d79fb617413b09980966a60e5a">llvm::generateBuiltinVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eb67a945b171bedff8f1c3a0ca82a7f">llvm::generateGetQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63b94467b9a18c31a4ee6d6ec4c34425">llvm::generateWaveInst</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#acb7cde93d3843abb013fe880c58e7f83">getSingleUndroppableUse</a>, <a href="#a28ed67ff84559f2ca8a0b5975d03cbce">getUniqueUndroppableUser</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompilandenv/#a859c4fc930e3b66da9200bea5ae69be5">llvm::pdb::PDBSymbolCompilandEnv::getValue</a>, <a href="#aa48638782e724669238a05c0859b35e0">hasSameSubclassOptionalData</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-b35dd31197c29325629c63022d08b455/#a50bd5b08d577c6711e24a5858f39f03d">llvm::yaml::ScalarTraits&lt; UnsignedValue &gt;::input</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-b96b1c4665796fbba3d6ae995b6a497c/#ac943927a71a1ac35f2204993692b7b35">llvm::yaml::MappingTraits&lt; MachineConstantPoolValue &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#ad762896b80c211f6d9cacfe6f8438732">matchExpandedRem</a>, <a href="/web-llvm/docs/api/structs/llvm/user/const-value-op-iterator/#ab195ff1805d70a32fc73f6ee11afecf8">llvm::User::const_value_op_iterator::operator*</a>, <a href="/web-llvm/docs/api/structs/llvm/user/value-op-iterator/#a7e6f1f79bc8d8515cb075ca324316bb6">llvm::User::value_op_iterator::operator*</a>, <a href="/web-llvm/docs/api/structs/llvm/user/const-value-op-iterator/#afb40cd0099f73c515cced1766ce11c0e">llvm::User::const_value_op_iterator::operator-&gt;</a>, <a href="/web-llvm/docs/api/structs/llvm/user/value-op-iterator/#a200a7ca31cb01d37207fdb3de65e6767">llvm::User::value_op_iterator::operator-&gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a760ab7196132a185180795deff1fe81b">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aeff94b564d9e2d5c4afebe286cae962e">llvm::pdb::operator&lt;&lt;</a>, <a href="#abd5773aff310a001b58365f1298afb1b">operator=</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-b35dd31197c29325629c63022d08b455/#afc64a76b31ee4e7195871e36009fc0d0">llvm::yaml::ScalarTraits&lt; UnsignedValue &gt;::output</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>, <a href="#a551ea28693c8f39b40d76f5255ca930d">stripAndAccumulateConstantOffsets</a>, <a href="#a23c582e2452eeb2b2cf6e0c43eca617e">stripAndAccumulateConstantOffsets</a>, <a href="#a574f86d538a28119d082be202fedb615">stripAndAccumulateInBoundsConstantOffsets</a>, <a href="#a14f27b1cef50a1f887650a8c79dbb436">stripAndAccumulateInBoundsConstantOffsets</a>, <a href="#acab7642aedd7e0d2e7b5857d99328c25">stripInBoundsConstantOffsets</a>, <a href="#a0443930d9dd02213bbc46588a7af488d">stripInBoundsOffsets</a>, <a href="#a08ad28e3c7d7c2f0c2ecb5ddcd1da355">stripPointerCasts</a>, <a href="#a559c1ffcea756dea87714e5d51ed82f4">stripPointerCastsAndAliases</a>, <a href="#ac433d0ecf347d8fc3d4786002f31d7e9">stripPointerCastsForAliasAnalysis</a>, <a href="#ae20551fe1b3fb3429d78ac77b4f81a54">stripPointerCastsSameRepresentation</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a282fa3e9586425313e0a954c18deee15">llvm::User::User</a>, <a href="#a89fb6f29d69f077a86d811c6331681d1">Value</a>, <a href="#a3382a955d5cfa8adec3e002ffd6c2b72">ValueHandleBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a159c35fe8089d7348efef90d098aecbe">valuesOverlap</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a7715a3a87a83a23b15d67031e6855044">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~Value() {#a3a578f458da8a4ab67052dba0f7bffdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value::~Value ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a>'s destructor should be virtual by design, but that would require that <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> and all of its subclasses have a vtable that effectively duplicates the information in the value <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>As a size optimization, the destructor has been protected, and the caller should manually call deleteValue.</p>


<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#abd5773aff310a001b58365f1298afb1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value &amp; llvm::Value::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addMetadata() {#aa1b0638c63ba711320b3bb9c69367ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::addMetadata (unsigned KindID, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; MD)</td>
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

<p>Add a metadata attachment.</p>

<p>Declaration at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1565 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="#a9eb4a52a4675976293ae4f77c982667b">HasMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6577bf24ddcb2a2cd401ee3e4704527a">llvm::LLVMContextImpl::ValueMetadata</a>.</p>


<p>Referenced by <a href="#a97df41793a6441c58ab81b883ef106fa">addMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6ab34a535b1441b48a0ede2c2aa6fb98">llvm::MachineIRBuilder::buildConstDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a9b432a2a53b6ec71e9290e6f9d7582ea">llvm::VPWidenCastRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a0fd82e391d2d015065516e32f62870c1">llvm::VPWidenStoreRecipe::execute</a>.</p>

</div>
</div>

### addMetadata() {#a97df41793a6441c58ab81b883ef106fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::addMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; MD)</td>
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



<p>Declaration at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1572 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="#aa1b0638c63ba711320b3bb9c69367ed6">addMetadata</a> and <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>.</p>

</div>
</div>

### getMetadata() {#aef569d822dbf572ae71954d6831ce8a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::Value::getMetadata (unsigned KindID)</td>
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

<p>Get the current metadata attachments for the given kind, if any.</p>


<p>These functions require that the value have at most a single attachment of the given kind, and return <span class="doxyComputerOutput">nullptr</span> if such an attachment is missing.</p>


<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a59e5e9e741eead6d5b460cd28c473039">getMetadataImpl</a> and <a href="#a9eb4a52a4675976293ae4f77c982667b">HasMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="#af580f3203cd4b561487e08bb1fd1d1ae">getMetadata</a>, <a href="#a0ece1c601517c563294f590d2cff210d">hasMetadata</a> and <a href="#ac8c13b9effae3289c194af4ca1865e4e">hasMetadata</a>.</p>

</div>
</div>

### getMetadata() {#a8c4c0580bdb7ccc8210222c7b22522b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * Value::getMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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



<p>Declaration at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1498 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a3d94b2a186954951025cfb593c91e0a9">llvm::LLVMContext::getMDKindID</a>, <a href="#a59e5e9e741eead6d5b460cd28c473039">getMetadataImpl</a> and <a href="#a1f496e54accb2cbe919fb456cb703f1a">hasMetadata</a>.</p>

</div>
</div>

### getMetadata() {#aa8b1bc6f9347dade1932d5e0a0be7904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::getMetadata (unsigned KindID, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp; MDs)</td>
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

<p>Appends all attachments with the given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to <span class="doxyComputerOutput">MDs</span> in insertion order.</p>


<p>If the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> has no attachments with the given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, or if <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> is invalid, leaves MDs unchanged.</p>


<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1511 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="#a1f496e54accb2cbe919fb456cb703f1a">hasMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6577bf24ddcb2a2cd401ee3e4704527a">llvm::LLVMContextImpl::ValueMetadata</a>.</p>

</div>
</div>

### getMetadata() {#af580f3203cd4b561487e08bb1fd1d1ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::getMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp; MDs)</td>
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



<p>Declaration at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="#aef569d822dbf572ae71954d6831ce8a9">getMetadata</a> and <a href="#a1f496e54accb2cbe919fb456cb703f1a">hasMetadata</a>.</p>

</div>
</div>

### hasMetadata() {#ac8c13b9effae3289c194af4ca1865e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::hasMetadata (unsigned KindID)</td>
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

<p>Return true if this value has the given type of metadata attached.</p>

<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#aef569d822dbf572ae71954d6831ce8a9">getMetadata</a>.</p>

</div>
</div>

### hasMetadata() {#a0ece1c601517c563294f590d2cff210d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::hasMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#aef569d822dbf572ae71954d6831ce8a9">getMetadata</a>.</p>

</div>
</div>

### print() {#a1e56c814d11206720cc23059b871128d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 5061 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac1b59b7799509e47193276bc8b9a716d">getModuleFromVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a6a885a6ab00ca58dbc03b09d0485e6f1">isReferencingMDNode</a>, <a href="#a1e56c814d11206720cc23059b871128d">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afef1b1a235ce94996013a71608e08f58">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#af1d5c7867737745f90d074f16eb1c485">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a6c0673e9d30e91b31c2dbbfdae47f3f1">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitConditionalAssignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a2ec882a8aecc1b17265d0bebffa5cb1c">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDTPRel32Value</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#afb95b400bf91f96c149f206e45dc0d09">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDTPRel64Value</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a3b406af868aa746d08c62b38d8c259f7">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitELFSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ac08027460665b9a74ec5770fc3c69105">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitGPRel32Value</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa557364f7fbf9210e7937d72e1eaa1e3">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitGPRel64Value</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a398cbd8a4b88d125a501b3f6b5932588">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitSLEB128Value</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a4884277cc2c31ed03c037671a632d8ad">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitTPRel32Value</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5ba5fdec68cf4b56fb2ec57f42753267">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitTPRel64Value</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a2f652a1af8c13dd04aa1b2ba2cfd80d8">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitULEB128Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#a46c66115be8a99f00d13569a94ae0678">llvm::MCTargetStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ae37bcdd18e5b8eb58b8d88effad3fed8">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#ab5c7f0f9f87d69820d8e4d8b31f4b0ff">ensurePromotedGV</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#aef83676a470a77d6e089737fb024de94">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputAnnotations</a>, <a href="/web-llvm/docs/api/structs/llvm/acceltablebase/hashdata/#a1fc5a3feed7bc53248b94f0b2649e828">llvm::AccelTableBase::HashData::print</a>, <a href="#a1e56c814d11206720cc23059b871128d">print</a>, <a href="#a7ba690234245eaba66ec19c429aaa7b3">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#a3f17021840c979ef6923eea86d0902bf">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printFields</a>, <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#a37407e1adaf30ca92fcd32b516ce0b07">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printTemplateArgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#adfb4d18db2159531ff68606f587116f4">writeMDTuple</a>.</p>

</div>
</div>

### print() {#a7ba690234245eaba66ec19c429aaa7b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 5072 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a802b848d702c132a97b3da454c1e68c1">llvm::ModuleSlotTracker::getMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac1b59b7799509e47193276bc8b9a716d">getModuleFromVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#ace93d877ff9298d25a15e2a32f765653">llvm::ModuleSlotTracker::incorporateFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a1e56c814d11206720cc23059b871128d">print</a>, <a href="#a62213d5211c9d944e5ede1f0059a6ae2">printAsOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a>.</p>

</div>
</div>

### printAsOperand() {#a62213d5211c9d944e5ede1f0059a6ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::printAsOperand (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool PrintType=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the name of this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> out to the specified <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>


<p>This is useful when you just want to print 'int reg126', not the instruction that generated it. If you specify a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> for context, then even constants get pretty-printed; for example, the type of a null pointer is printed symbolically.</p>


<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 5144 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac1b59b7799509e47193276bc8b9a716d">getModuleFromVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a>, <a href="#a62213d5211c9d944e5ede1f0059a6ae2">printAsOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7cb3001e93d2e932542f82696da1ca4e">printAsOperandImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#af20152d720e6ffc7cf0151f2f657c3be">printWithoutType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afef1b1a235ce94996013a71608e08f58">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lazyvalueinfo-cpp-/lazyvalueinfoannotatedwriter/#ab4afff4105010d78636818f50e082031">llvm::anonymous{LazyValueInfo.cpp}::LazyValueInfoAnnotatedWriter::emitInstructionAnnot</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasset/#a402ffc8c32cbcbcf858f1188ce7a4c87">llvm::AliasSet::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ad75b48c94bacfc6a1d166164bd51af8b">llvm::MemoryPhi::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>, <a href="#a7ba690234245eaba66ec19c429aaa7b3">print</a>, <a href="#a71c852fe821d8efa8a9cb0c359380ac7">printAsOperand</a>, <a href="#a62213d5211c9d944e5ede1f0059a6ae2">printAsOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a92e7361f7532de414322df105163781f">replaceDominatedUsesWith</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>.</p>

</div>
</div>

### printAsOperand() {#a71c852fe821d8efa8a9cb0c359380ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::printAsOperand (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool PrintType, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 5159 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a802b848d702c132a97b3da454c1e68c1">llvm::ModuleSlotTracker::getMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a12bf76af836ffe2d2e00435a3f0861e9">llvm::ModuleSlotTracker::getModule</a>, <a href="#a62213d5211c9d944e5ede1f0059a6ae2">printAsOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7cb3001e93d2e932542f82696da1ca4e">printAsOperandImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#af20152d720e6ffc7cf0151f2f657c3be">printWithoutType</a>.</p>

</div>
</div>

### setMetadata() {#a338590123630c357df6340c38d066572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::setMetadata (unsigned KindID, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Node)</td>
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

<p>Set a particular kind of metadata attachment.</p>


<p>Sets the given attachment to <span class="doxyComputerOutput">MD</span>, erasing it if <span class="doxyComputerOutput">MD</span> is <span class="doxyComputerOutput">nullptr</span> or replacing it if it already exists.</p>


<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1531 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="#a9eb4a52a4675976293ae4f77c982667b">HasMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6577bf24ddcb2a2cd401ee3e4704527a">llvm::LLVMContextImpl::ValueMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a> and <a href="#a9542c54e3e3ac516ab7437ae1b98bea8">setMetadata</a>.</p>

</div>
</div>

### setMetadata() {#a9542c54e3e3ac516ab7437ae1b98bea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::setMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Node)</td>
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



<p>Declaration at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1559 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="#a9eb4a52a4675976293ae4f77c982667b">HasMetadata</a> and <a href="#a338590123630c357df6340c38d066572">setMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addUse() {#aa8c61025e1632cf57e24e59163e3df9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Value::addUse (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
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

<p>This method should only be used by the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> class.</p>

<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### assertModuleIsMaterialized() {#a3279672b4ef05895858df6f4b05c0de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Value::assertModuleIsMaterialized ()</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a2986c3fbc5cdd954a818288692245b0d">assertModuleIsMaterializedImpl</a>.</p>


<p>Referenced by <a href="#a413abcab8dbc3900fc2fde96a5d8fca6">use_begin</a>, <a href="#a24018b06ac0d956553428c86d5af7d5e">use_begin</a>, <a href="#a9d7de807ebdfe1819df3ff6cb0f16158">use_empty</a>, <a href="#a46db903db2484e1ef5062d094d6b0854">user_back</a>, <a href="#a59d3fe5f30609b50112d91f41d268567">user_back</a>, <a href="#a158da2b6d3d938aaa15b6acd00150e2c">user_begin</a>, <a href="#affbc364be263e23ef9f54686c947ca6c">user_begin</a>, <a href="#af21f61086e696a788f549768fdc26a93">user_empty</a>, <a href="#a411cf3e3932f209ce3374cb31adc1da6">users</a>, <a href="#a47e5062f8da90137678150d09bb17751">users</a>, <a href="#abf855b7cd63a0cd7f73759e396f280c9">uses</a> and <a href="#a224d0ab04e6510402fb5c7221666efed">uses</a>.</p>

</div>
</div>

### assertModuleIsMaterializedImpl() {#a2986c3fbc5cdd954a818288692245b0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::assertModuleIsMaterializedImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a>.</p>

</div>
</div>

### canBeFreed() {#a7b4d048a84149ece45db862333dea428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Value::canBeFreed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the memory object referred to by V can by freed in the scope for which the SSA value defining the allocation is statically defined.</p>


<p>E.g. deallocation after the static scope of a value does not count, but a deallocation before that does.</p>


<p>Declaration at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### clearSubclassOptionalData() {#a48790dc28d4007833380faed30c9f44c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Value::clearSubclassOptionalData ()</td>
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

<p>Clear the optional flags contained in this value.</p>

<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a21e38886795ed32ec28d4eb5dc92b6a4">SubclassOptionalData</a>.</p>

</div>
</div>

### deleteValue() {#a99d640257f7689aa8095dccfb111e50c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::deleteValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete a pointer to a generic <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist/#aab54c009e65d26aaa3160eaa876c94e2">llvm::BitcodeReaderValueList::assignValue</a> and <a href="/web-llvm/docs/api/structs/llvm/ilist-alloc-traits-af69980eb156f24a01ee00bf671d2f4b/#a3fb76a42061ab00b0786043741df3b2c">llvm::ilist_alloc_traits&lt; MemoryAccess &gt;::deleteNode</a>.</p>

</div>
</div>

### DoPHITranslation() {#a159bf794249e0567baf2a2a714d5c679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * Value::DoPHITranslation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CurBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PredBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Translate PHI node to its predecessor from the given basic block.</p>


<p>If this value is a PHI node with CurBB as its parent, return the value in the PHI node corresponding to PredBB. If not, return ourself. This is useful if you want to know the value something has in a predecessor block.</p>


<p>Declaration at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1067 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>.</p>

</div>
</div>

### DoPHITranslation() {#ab1948efb247cc6e24d34a083f8c742b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Value::DoPHITranslation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CurBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PredBB)</td>
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



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### dropDroppableUses() {#aa1fda0e425c4102e16fe73928efcd750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::dropDroppableUses (<a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *)&gt; ShouldDrop=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *) { return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove every uses that can safely be removed.</p>


<p>This will remove for example uses in llvm.assume. This should be used when performing want to perform a tranformation but some Droppable uses pervent it. This function optionally takes a filter to only remove some droppable uses.</p>


<p>Declaration at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### dropDroppableUsesIn() {#a731895a3f577718bbaec9b180eb2a6bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::dropDroppableUsesIn (<a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; Usr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove every use of this value in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></span> that can safely be removed.</p>

<p>Declaration at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### dump() {#af7dca9a9e816ef69fd9e9467f64f72b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Value::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Support for debugging, callable in GDB: V-&gt;<a href="#af7dca9a9e816ef69fd9e9467f64f72b4">dump()</a></p>

<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 5304 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#af7dca9a9e816ef69fd9e9467f64f72b4">dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a0fa90c2a513cc9801d885d999ddac777">CanWidenIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#aadc8ada3f35f60d30e774a6daf23d02f">checkPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="#af7dca9a9e816ef69fd9e9467f64f72b4">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a9bbea577bf401c708dc854d2dad600af">findLoopComponents</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopflatten-cpp-/flatteninfo/#ae4b9ef35d5c40d69ae861c215edd3a08">anonymous{LoopFlatten.cpp}::FlattenInfo::matchLinearIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a31ba90bd367677d2bf4065d6e51eca65">llvm::GlobalMergeFunc::merge</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86avoidstoreforwardingblocks-cpp-/x86avoidsfbpass/#a42cae0fd23182f6d2b4d4368a4ec21c3">anonymous{X86AvoidStoreForwardingBlocks.cpp}::X86AvoidSFBPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a58b2a7b6438666f763752c35da604195">setLoopComponents</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>.</p>

</div>
</div>

### getContext() {#ab3fc0225d8aaf8434026c3573f961f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; Value::getContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All values hold a context through their type.</p>

<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1075 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9a7c63edb94ce4fab2a5bb34dbf6079a">llvm::Instruction::addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6762e9e611c29b13a5c94bf8488fe798">llvm::Instruction::addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#af763d890b27bbeacc1b06636740de9a1">llvm::GlobalVariable::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a6cee3c634aa5de8c51e6eaa4e41898bc">llvm::GlobalVariable::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2060ab64acfc67af974e20cbc79ca273">llvm::CallBase::addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9ec1fe122d152d6c6cefbdab43a43cdc">llvm::CallBase::addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adf1a2105045f7e33738b34f49b0f9f08">llvm::CallBase::addDereferenceableParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9add940717795f05bb69603216f17254">llvm::CallBase::addDereferenceableRetAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a031e44afee1f29cd934862cebf714a88">llvm::CallBase::addFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0f72a62efd0912aba72c6818c720023c">llvm::CallBase::addFnAttr</a>, <a href="#a97df41793a6441c58ab81b883ef106fa">addMetadata</a>, <a href="#aa1b0638c63ba711320b3bb9c69367ed6">addMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a433ec4bd285111f13acdc8a78be16a72">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0e7b74d310c94c459b8985806192cc99">llvm::CallBase::addRangeRetAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae30660fb489f8cbe69bf8650daadcdb1">llvm::CallBase::addRetAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aa94f59b6921a7cd3567439b3302a5357">llvm::CallBase::addRetAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacktrie/#a93eab9244b86ce5f52aa4f15a71741be">llvm::memprof::CallStackTrie::addSingleAllocTypeAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a0b7601463f25d7904fa9d060ba629a5a">llvm::GlobalObject::addTypeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a1fb252b26b548e2ed904e02782013abd">llvm::DbgVariableIntrinsic::addVariableLocationOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a490938b206738261d5984fe958a872ad">adjustInliningThresholdUsingCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a4e9132c0a4e72e51f7310163385d1d98">llvm::AllocaInst::AllocaInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#abd9356b1c3a69a55b72df590c48f9738">llvm::SelectInst::areInvalidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#af36215890e150f71abd2be2eb400487f">llvm::AtomicCmpXchgInst::AtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacktrie/#ab9f10c4267af88a1bd143a7260d2ac8f">llvm::memprof::CallStackTrie::buildAndAttachMIBMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9875dff9496a8c83bc0bcf749858c45b">buildIntrinsicArgTypes</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvemitintrinsics-cpp-/#a54b7a397102703566ccbb015b4405474">anonymous{SPIRVEmitIntrinsics.cpp}::buildMD</a>, <a href="#ad151fceb9a0e77a8a8017d4f68791811">clearMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#ab330f042033636da90859626bc4dc542">llvm::CoroIdInst::clearPromise</a>, <a href="/web-llvm/docs/api/classes/llvm/fenceinst/#a6b2ad8a991fecc4b259e8ceffb3544cb">llvm::FenceInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/unreachableinst/#afd56ede3e6bb7d4d6932159e8eb003d8">llvm::UnreachableInst::cloneImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a0cb38e302133457f235fdcc6723abeac">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromLI</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a28ddcf99fafe235217356e423dcdd084">anonymous{ConstantFolding.cpp}::constantFoldCanonicalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bf95d0980fad19452f4c9aca445af3f">llvm::ConstantFoldInsertElementInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a125e2946cdcc7555d8f5c383681d7097">convertMetadataToAssumes</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxlowerargs-cpp-/#aafd9b42c5de69fbe2a25e6b94f8cc299">anonymous{NVPTXLowerArgs.cpp}::copyByValParam</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a6aa0afd1200f5f282ca02a9ebcf87ca7">llvm::GlobalObject::copyMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#ae9315c94e4cd695aceef039966a2beba">copyMetadataForAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e44f52bb2b2c5d2273eccec70faae">llvm::copyMetadataForLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab057ca6ed74ccfa73d1a0d2cf15b2300">llvm::copyNonnullMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadb1772c1026a517d15c771ceb6a91ca">llvm::copyRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#af5f4af29cea0dae3f4a3cf633dbacaba">llvm::ARMConstantPoolConstant::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c3ae5ad4be121cbb1bc87e871b679da">llvm::createCallMatchingInvoke</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac3e775626bfa565297feec5807947efc">llvm::IRBuilderBase::CreateElementUnorderedAtomicMemMove</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2001dcf6278f9e7e10b895d060d15abb">llvm::IRBuilderBase::CreateMaskedCompressStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad878957c30eb65983e09b60edb0e1a1b">llvm::IRBuilderBase::CreateMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab464550d233a70bf18d772d204549342">llvm::InstCombinerImpl::CreateNonTerminatorUnreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21576774815efd6bd8374d3ac55c65f6">llvm::createPGONameMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeac445a66283c4e567ebd390c058e39d">llvm::IRBuilderBase::CreatePreserveArrayAccessIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4804fd7127d8e249a628e93d6b8b3f2a">llvm::IRBuilderBase::CreatePreserveStructAccessIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#ab96042c1f6f237fe85abc4ec3ceb88d3">CreatePrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a19f9814e01d7c1d3167216cba953eab2">llvm::IRBuilderBase::CreateThreadLocalAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuprintfruntimebinding-cpp/#a0ed7b2c2e7da5af8cafe5996248e4889">diagnoseInvalidFormatString</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad46652b66427679d9c221df6915019ca">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::discardEVLParameter</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4576d69ed1543b06e5c41eb43b630bf1">llvm::Instruction::dropLocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#acccaf0eaeef2b860b1182f8985f59e94">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIVComparison</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a70c624e7362eb836118fe7ee02737b43">emitAtomicRMWLegalRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a9b051a25ba281897b4dc62df58312b7e">emitDbgAssign</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ae9aaedbefa65f41bb54b62d9137f13dd">emitGlobalConstantVector</a>, <a href="#a9d88e21e9caa53945e903fd8c8700b4f">eraseMetadata</a>, <a href="#ab1198eef44b311a7984cfc8fc97fac6d">eraseMetadataIf</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a88dfee6623475363a4e46966d8383c0f">llvm::SCEVExpander::expandUnionPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#ad160f0c6b2de8059d92dbff54d093531">llvm::SCEVExpander::expandWrapPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ad326bf7574f239b4177d077e513403aa">llvm::VPIRInstruction::extractLastLaneOfOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a39c9d039f5cbab6c4155e907c466ab25">extractMDNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ad3259dc4dae742caac6c6e4f577d1760">foldInsSequenceIntoSplat</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a12f6125cdd608cb0459585ddb68ead53">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::foldIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/hlsl/frontendresource/#a762b4d0928e1709415ce366e88b2bc3a">llvm::hlsl::FrontendResource::FrontendResource</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ab00c6dc5086df2a37cd2e78715968861">llvm::ConstantExpr::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dsolocalequivalent/#a552470933dc4c1724248d9773e36b4de">llvm::DSOLocalEquivalent::get</a>, <a href="/web-llvm/docs/api/classes/llvm/nocfivalue/#a12b8ccc251129b734bf00e84515d2711">llvm::NoCFIValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aade703948f2fdabdc65868bdf42d3141">llvm::Instruction::getAAMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7f4680b383ce7138bc2c12de282b14b4">getAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#acd530d0571f320d47d37e7ae51cf70ff">llvm::Constant::getAggregateElement</a>, <a href="#a3d200b1568f70b28ae0eb9bec58d6690">getAllMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a7f97c03389898566620894f7ba674df7">llvm::GlobalVariable::getAttributesAsList</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#aff3d225ae8841fccee34cd8a722f14b2">llvm::Attributor::getAttrsFromAssumes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87ef919ea907189c22b74f604a645b40">llvm::getDebugValueLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#ab1cf9198def27dfd719c425b1f9c5f50">llvm::ConstantDataSequential::getElementAsConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad61acd1c9fda9921a30f3ff510509873">llvm::ScalarEvolution::getElementSize</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a078455f9a6da73bc84f24700a81d19d7">llvm::ConstantExpr::getExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a64d6bd55aa4447bb25f1361993223450">llvm::ConstantExpr::getInsertElement</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#afb9fd1f991a7503fe4fd7dc16bda6f30">getKnownValueOnEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8eaaa1b4edc9934bfea0469269f3d869">getMemCmpLoad</a>, <a href="#a8c4c0580bdb7ccc8210222c7b22522b7">getMetadata</a>, <a href="#af580f3203cd4b561487e08bb1fd1d1ae">getMetadata</a>, <a href="#aa8b1bc6f9347dade1932d5e0a0be7904">getMetadata</a>, <a href="#a59e5e9e741eead6d5b460cd28c473039">getMetadataImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a72237a63b5edcf78a32453822139f1d5">llvm::GlobalValue::getPartition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp/#a3b9b774d938abd4c2836b47f52daa274">getPointerOperandAndType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ae67d970cf80e86c5789e52f9d57d0c70">getPreferredVectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a0b43ef7c72a8cb10a0cb09154a3b3b2d">llvm::slpvectorizer::BoUpSLP::getRootNodeTypeWithNoCast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a10dbf1e2be9c60af49efb9bfded99225">llvm::GlobalValue::getSanitizerMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a25ca2f3cb40ae1c26c73054659203b2d">llvm::Constant::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a658e3ea96ae67d36b7eec701df4f04dc">llvm::ConstantStruct::getTypeForElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#acea86ec3d4961375fa6135e67111884b">getVTableAddrForProfData</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af38a8629ae32606b01eacbbd667d831c">llvm::GlobalValue::GlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a6ac9067dc7c125cd83855df3e480e04c">handleBrSelExpect</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a7f7861a70cfa57999c2b47e570be2127">llvm::ValueAsMetadata::handleRAUW</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abc575c6c80287df1f51f698ec74e315e">llvm::Attributor::hasAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a7e0764cee9d3754f276a61e53da1c2b4">IdentifyValidPoisonGeneratingAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a006ce5c0c5ec18c589454f270a335a3c">IdentifyValidUBGeneratingAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5a6937fcd639ac78a93b48ab6624e957">llvm::DIBuilder::insertDbgAssign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a5a020f0ab461a1f6e3b87aff314bd040">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51d22a1ed809d7cb1c1eb46c820c8226">llvm::intersectAccessGroups</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoundef/#ad91f1de0705a6d8cfb9d1269ae996737">llvm::AANoUndef::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aawillreturn/#ad363b24d67098ccf362ea38277ce9c61">llvm::AAWillReturn::isImpliedByIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0109582eb646d501101a7e6a059814fb">isLoadCombineCandidateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#a45baf076726e8a271aa9dc0a8baa2c76">isPointerAlwaysReplaceable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#adfa24b29ddb799607095546fa388954a">llvm::AMDGPUAsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a55d9cc47f7041c1afad87f88ec5c7636">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerConstantPtrAuth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocleanup-cpp/#a77b6227cc85a61fcbce08b8387c575a9">lowerSubFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27aee52717271be9e79135bfaab890ce">llvm::makeGuardControlFlowExplicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaassumptioninfoimpl/#afd7017a3f3a492552121875308910210">anonymous{AttributorAttributes.cpp}::AAAssumptionInfoImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#a9a1b2954b9c4eb6f178a0c7e66581822">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a9971c8a3647ef1b5439ed7cd18aee749">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abc4265ad1d2a8b43fcf0e44d4b4f6274">llvm::Attributor::manifestAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ae04610310004450abde7293643734104">matchFPExtFromF16</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#aabd8a84d1694dda293cbdce6bde5fc11">maySpeculateLanes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a0346c3f86c714b9ae84f5566a95e90ac">migrateDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/negator/#a2abe5e7f029b63c7b1bd29ac231ef7fa">llvm::Negator::Negate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a9a1ec6b08304c2db10e687517bc4dd2c">optimizeMemCmpConstantSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3b82cff474790446f1288f1a086c1cd6">OptimizeNoopCopyExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a93f122dff654f8336680531a3898375c">llvm::CallBase::populateBundleOperandInfos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiloplowering-cpp/#a5761cea08563e881215f9511be699d06">populateOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pgo/#ac3ab1f99a5d99ba23fcfec6044ebc805">llvm::pgo::promoteIndirectCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48a6deb3e714d54e75caadcf84b0ca76">llvm::propagateMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3002d96da0f9030af718fbe2961b913f">llvm::ReadByteArrayFromGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ab18063e13ecbbbdea86aa54cd118b1db">llvm::CallBase::removeAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a38dc9fea21bad23a1ca15b9c7a7ec484">llvm::CallBase::removeAttributeAtIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa2ead3ae2cc059f459be46ce71ef20a5">removeCoroEndsFromRampFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#acd7acfca49e931306ba40f1eb6939f67">llvm::CallBase::removeFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ada5536ea9f061a27091a487f69565b3e">llvm::CallBase::removeFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a68f6ab734f9bafb1a1b591267ef402d8">llvm::CallBase::removeFnAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2ab5d0b4d639b3f79ff3922441e0082e">llvm::CallBase::removeParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#af7aecdc1aa280f1c8c0aa194b3453b46">llvm::CallBase::removeParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a14f9c4f42aae35f61b404a5d21e9d88d">llvm::CallBase::removeParamAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9724a78a61a4a4d72941116c6bd7c892">llvm::CallBase::removeRetAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2d9fe4a8103a58d5dee8ff09e6fa2152">llvm::CallBase::removeRetAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a1b8db417ccdc447464add1a3d9358759">llvm::GlobalValue::removeSanitizerMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab289568caaa6647ee577a06e6e12499a">replaceCoroEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#abf799de7147065c0e7f525e1b6009dde">llvm::coro::replaceCoroFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a9f66dfca05bfb9a4f5bddbad1ad043e6">llvm::DbgVariableIntrinsic::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a3d995a069d73ebebbd6a4aace342ef76">llvm::DbgVariableIntrinsic::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#aef2660c212a6794faf7ec16cae82248a">llvm::DbgAssignIntrinsic::setAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#a4c46f4f09337677b638261fc6487aade">llvm::DbgAssignIntrinsic::setAssignId</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a3e1cfc51d4ab9b192f09e050b24e410b">llvm::MemIntrinsicBase&lt; Derived &gt;::setDestAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a4ab0f2c30ee83d6377488de9a1f089e9">llvm::MemIntrinsicBase&lt; Derived &gt;::setDestAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicmemintrinsic/#a91ecdf20aedd95b2052709963e7c9c7b">llvm::AtomicMemIntrinsic::setElementSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcntrinstbase/#ac98dfc76a69863c13ae587fa9521c808">llvm::InstrProfCntrInstBase::setIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a444e3e622a00db2be6dcaf46cef996f5">llvm::setInlineRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelinst/#a91ea3c7496ba4e21be7e4d1ed54b03c6">llvm::DbgLabelInst::setLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad7cd933f586fc0c66656a4751ac069f">llvm::setLoopEstimatedTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aecb5289d51bac327bc2f7f5a2d0ad5c3">llvm::CallBase::setMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a695a53ce0b9f537880373b4ea1824a6b">llvm::Instruction::setMetadata</a>, <a href="#a9542c54e3e3ac516ab7437ae1b98bea8">setMetadata</a>, <a href="#a338590123630c357df6340c38d066572">setMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a959c782ed643a36be7d7264e379025d1">llvm::Instruction::setNoSanitizeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aff8740863a5ee2650339400236b6224b">llvm::GlobalValue::setPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a2faebe0374c9b44fdb9bd71cafdef798">llvm::DbgVariableIntrinsic::setRawLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#add48ed79a5cd63c7165f3f4da102b9fd">llvm::GlobalValue::setSanitizerMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/noaliasscopedeclinst/#a2defed486cd9ee3d4ff214afbd0c9066">llvm::NoAliasScopeDeclInst::setScopeList</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a959c99adbdc7f8375cf866916c6b60f2">llvm::GlobalObject::setSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#a06c7810ad5d205218bce57bff448b2e3">llvm::DbgAssignIntrinsic::setValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#afc31bb8f3573226060a5c31480fa650e">llvm::GlobalObject::setVCallVisibilityMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a1321465508b2b54862b90ca404386e06">shortenAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a708996b12b1b5e6ac2555880bdaeda64">simplifyX86MaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#aa2bc34e64d5998c42bde9be90ad5bad1">llvm::StoreInst::StoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a7223c62dc4b1db59861cb3a7e225a387">llvm::coro::suppressCoroAllocs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#ab9fe9fd51104da9e7faa88a213b74b9b">anonymous{LowerSwitch.cpp}::SwitchConvert</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#afb49554840d9c699b6b3a2a09361dbd8">llvm::CallBase::tryIntersectAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a11a65ce1550eac260dca320a7028328e">verifyTripCount</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-autoupgrade-cpp-/amdgpuunsafefpatomicsupgradevisitor/#aa5a373065be6eabfcc9eeb46018af87c">anonymous{AutoUpgrade.cpp}::AMDGPUUnsafeFPAtomicsUpgradeVisitor::visitAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9567d315d63f844326900f461f5b3d7a">llvm::InstCombinerImpl::visitIntToPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8b0688ee292d40a24ba7117b39d426bd">llvm::InstCombinerImpl::visitReturnInst</a>.</p>

</div>
</div>

### getName() {#adb5c319f5905c1d3ca9eb5df546388c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Value::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a constant reference to the value's name.</p>


<p>This guaranteed to return the same reference as long as the value is not modified. If the value has a name, this does a hashtable lookup, so it's not free.</p>


<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a60ded14ad5409c193178f8c72201a6cb">llvm::SSAUpdaterBulk::AddAvailableValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgesimpl/#a9f1939987274b79ee856d5a5255b91ae">anonymous{AttributorAttributes.cpp}::AACallEdgesImpl::addCalledFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad4f572b4f4bf6aa2dbf10a0bd160280d">llvm::addDiffRuntimeChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#aeddd04f458fd6e9db5a892543636e240">addEmuTlsVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a90036e9bed7ce7e86007bd8d83dd2d21">aspaceWrapValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#af680d052a24c294259bd765f02906202">anonymous{JMCInstrumenter.cpp}::attachDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/winexception/#aeaa5422d8ee3dd96aca4513a89a94035">llvm::WinException::beginFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroearly-cpp/#afbc0cbc36e72c326f3df01f017015786">buildDebugInfoForNoopResumeDestroyFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a3f27dda1e68a24fab4b3ed4a9cfc0e7c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildPatchableThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a0bfeadac5ccd4e56b4c5df9dc6bb8817">calcPredicateUsingBooleans</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a646829664451eb913bfa2f92920478ea">calcPredicateUsingInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a54c3911cf4abbcd272fa99a303823942">llvm::BranchProbabilityInfo::calculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a7227d9ecc33b8ed7a50b0d4341448c6c">calculateCXXStateNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#aaaced3d57d8877d30048b69be2787b21">calculateSEHStateNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1347d52f024418efd43a77e0fcb57355">llvm::InstCombinerImpl::canonicalizeCondSignextOfHighBitExtractToSignextHighBitExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa8ec1591dd8e7639e5b5e1869b49e9b5">CanPropagatePredecessorsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a6d4194ac737935234600bb19108a8042">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::chooseBestVariableForModuleStrategy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aaa5acf165c5a3bec2ff360c59f2f9448">llvm::orc::cloneGlobalAliasDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a88db5656a6723001ab395e9db68094c2">llvm::orc::cloneGlobalVariableDecl</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a866163a9dbd27133c221fc2569333ddb">anonymous{CodeMoverUtils.cpp}::ControlConditions::collectControlConditions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3a97fed79c86bf242b0f090e1cb2e6">llvm::colorEHFunclets</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad7586c4efa39c8f9162c7608ff9a57cf">llvm::InstCombinerImpl::combineLoadToNewType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ad9ef9dbac3fbf9cc30e63d86bf9d7e34">compareNames</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2ffeb0208ddb1c5cf8a4bfb2ef0c9008">llvm::VPBasicBlock::connectToPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#adcb7e087ebdb7b3e360160af660827c7">constructEntryMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a944b77cb28ad77cdf28380c4453f8d02">convertToParamAS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxlowerargs-cpp-/#aafd9b42c5de69fbe2a25e6b94f8cc299">anonymous{NVPTXLowerArgs.cpp}::copyByValParam</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#a101d392f12933ec345c1cef1f552809e">copyLinkageVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac56dc4e7c9b62727513a77d85a3dc243">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1f815573461be87717cbb7a4ce30f875">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a452dcc29fd5e19bda874218e10a8945c">createCloneDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a741f7bb1cc23d5c9d8917e1c7970c732">createInvariantCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a61a95dc82ae09814a35f56fcc56cad5b">createMemprofDefaultOptionsVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21576774815efd6bd8374d3ac55c65f6">llvm::createPGONameMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7aa8025f73f4e06135e6ba7083ad7aab">createUnreachableSwitchDefault</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a47ed1ed3cecee1de815ef53eace647b1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::distributeTransposes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate/#a4392517c22c653d59c5deead6ccfffb7">anonymous{LoopFuse.cpp}::FusionCandidate::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-materializationutils-cpp-/rematgraph/#a336028d6f8b409a071169b09e0b5e666">anonymous{MaterializationUtils.cpp}::RematGraph::dumpBasicBlockLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3fa67a76e6081ca187d962c197c6445d">llvm::dumpBasicBlockLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgmst/#af6d53cb002b3fe8f7c4b7a7c3323e4c0">llvm::CFGMST&lt; Edge, BBInfo &gt;::dumpEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cd89ca702a817aac3a4521dd2462a2e">llvm::DuplicateInstructionsInSplitBetween</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a664aaf46532d6ebeed0dfeb704308d33">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aa216c2cbc8d9610dc20db065aca671d3">llvm::LoopVectorizationPlanner::emitInvalidCostRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a78e5ec9027384598a0ce9fb4eb3cea72">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9180a7817130d1cac7cec7feec3bf6e6">llvm::emitLinkerFlagsForUsedCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4cc8d8a6afc7262b599109c2029fc311">llvm::AsmPrinter::emitSpecialLLVMGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a23f5821d9ac264ae25dd087747e2c181">emitTransformedIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a0afb8520349ae7dc725ebfbb0532dbb1">llvm::BranchProbabilityInfo::eraseBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#aa45aa859516b55fd0d010570b3f16170">llvm::VPBasicBlock::executeRecipes</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a505ddaadef479f2d0c0810c203000eaa">expandCrossIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#aee759d5807e7eb77e631717da4461426">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredication</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a3eba8b3e2e38c997d14bc2ee850be29a">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a1f1f1359a986d8e4d1b107ae4c524a32">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInMemoryIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a5cd88dbe6fb8f2ddbd621296ca4ebd5f">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToCastIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a62f9944dba24143c8954964d7dff45b8">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad2529fdcdfd78c5eccd6079fc3c74ad3">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToIntCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acae633d6254bf68b6ad97699f786b3b0">llvm::ExtractTypeInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a0dca3347facf58865b34df5e5df676f0">llvm::MustBeExecutedContextExplorer::findBackwardJoinPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#ab0cac3cc09d07bc44ffd388ff8be5e49">llvm::MustBeExecutedContextExplorer::findForwardJoinPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#ad914c82e07de4044a3314a5d03c5b85a">fixIrreducible</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4dbcb044eda11161781dfbf3f007f04">llvm::InstCombinerImpl::foldPHIArgExtractValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a29028fb86efd0ff0ea01f243f47684fc">llvm::InstCombinerImpl::foldPHIArgInsertValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad76042aae559769f4dc50ee2f9548789">foldSelectICmpLshrAshr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp/#a682c8b1a578622031f16f4be7766b603">forceRenaming</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a83088027da72950b627f9200965fb55b">llvm::ReplayInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bfi-detail/#a608965289792ad2d62922c506cf7ea40">llvm::bfi_detail::getBlockName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a9293c2849df988b06fecea7e1b021fee">getBranchHint</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#acf4019263b41c295bc55032dd651b6e4">llvm::HexagonTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a5e9dfc1cc5890ea9fb55b1dedcc2bd27">llvm::TargetLoweringObjectFileMachO::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad2a8da74fd4e4c892018c56c977addee">llvm::MachineBasicBlock::getFullName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a97235ab99e26ebd8fe54f629666f6bd2">getFuncAddrForProfData</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aed99d84162082a52cd08efb7dfe017e4">llvm::GlobalValue::getGlobalIdentifier</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-55c8cb82503f51812ad190e425a6fd3d/#a33c6f6eb06efcdf1daf21bc77c4b1a6f">llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getGraphName</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02f9563a016dafe7fbc78fcb1f76f101/#af2539ced6ca24d31e88f9b0217579a3e">llvm::DOTGraphTraits&lt; DOTFuncMSSAInfo * &gt;::getGraphName</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#a232bc3cdcfa2bab0574af9b47ff90c41">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::getInnerResumeDest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af25e9b73a31b54cd149a89a73b7032de">llvm::getIRPGONameForGlobalObject</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a7b91ad1b09dab040d3519c054e473efb">llvm::TargetLibraryInfoImpl::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a3b63142ca24145028afa3a5bdf3fe7fb">llvm::ExecutionEngine::getMangledName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-8e3d49d8257628f3fde0f02587f68f13/#ad84c5f2b4d317dc0213d926f5bb71e1e">llvm::DOTGraphTraits&lt; AttributorCallGraph * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a5ecc0bb5ee3eac043a66ce779ad05747">llvm::AArch64Subtarget::getPtrAuthBlockAddressDiscriminatorIfEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a2ddf5387f9cd603891e1933c2f84cf65">llvm::TargetLoweringObjectFileXCOFF::getSectionForExternalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl/#a6aef100d648e62bb628c87faf0ae9534">llvm::LazyValueInfoImpl::getValueAt</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl/#ad44ad3c83089fd4217748dce73578a56">llvm::LazyValueInfoImpl::getValueInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl/#a5803e595b84bd011b5da11029f4554f2">llvm::LazyValueInfoImpl::getValueOnEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a3d2c6d71f70d0e607257e6608872884e">getVarName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae2ebbbbc990e3d932da5d0d0ea255f42">HandleByValArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#a608a1965369c58e389152dd9485df72d">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashGlobalValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#ac9720fa4fb8bcc62c98a125f0b09fe9e">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo/#a1b4bc7c3f9aaad9e5b32303bd51081dc">llvm::SuspendCrossingInfo::hasPathCrossingSuspendPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo/#ad7b0b1b552021b1e8f080f4e79253853">llvm::SuspendCrossingInfo::hasPathOrLoopCrossingSuspendPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aebac730a26c607cea825366afca2d8b1">hoistBOAssociation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a7cbd4ee56d74745611d1e1fe7dddf995">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a12c711c62171c14dcedca2db5874d33e">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aafadfc35831cdb7ef3dd321cc28f1208">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0ced274818512cfd52e26d828ec1fcf2">llvm::InsertPreheaderForLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/internalizepass/#a93e7c89b8c8967cd2eeed0555e66d4f2">llvm::InternalizePass::internalizeModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70cdc32fcfc8ba3feaf026f4959e2c2a">llvm::InvertBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fcd2292dd9e51480a2f43d41acfe2">llvm::invertCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb077dd7e8e0c4efa7d2aaba0d21dab7">llvm::isControlFlowEquivalent</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#aab3a49dcff02cbc78628deef02c53296">llvm::HexagonTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanabilist/#a643c870211a29b46598eb1630b61156a">anonymous{DataFlowSanitizer.cpp}::DFSanABIList::isIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#a80f6063dd5f9d9d06818808cbb646f75">isInPartition</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#acc28d73804bc12a7a70c2e323ccb45fd">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::isLookupTableConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a766df1ea3c4bf3cbc8586f310562034f">isReportingError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a16ff47c73e3b36831f13b3ff0b1a3f33">isSpecialLLVMGlobalArrayForStaticInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a37e41a7f6870d875dafe144485f2fb3f">isSpecialLLVMGlobalArrayToSkip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae641260d79a9242ccf378d9a7949fdc3">llvm::isTLIScalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#addf7542694401439f2f600b3890c8831">anonymous{WholeProgramDevirt.cpp}::DevirtModule::lookUpFunctionValueInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4275af81cdeb1801deeae02ea2a0fb3b">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerBufferStore</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6a5658766cf2558d59b0344bb48f0754">llvm::AMDGPUTargetLowering::LowerGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a30b2570b289c65776a16666bd087c988">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerRawBufferLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a230768916fc2abaf5fb0f563654d2cc8">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToCreateHandle</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a70502c89919d53c74320c78b78d5c282">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerTypedBufferLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ab10e6ab2669a5c752426570de655e7ce">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerUpdateCounter</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ac388d17329447d2fd72ceabf79fefeba">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a665e880cc41e9fd97416741590e2e0d0">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecallcallsitereturned/#af1bd9d5096d40a231c52e763ca91647f">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCallCallSiteReturned::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver/#aa957a217201ee36323b4cd3c5d4c939a">llvm::SparseSolver&lt; LatticeKey, LatticeVal, KeyInfo &gt;::MarkBlockExecutable</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a1d0ccb6a03e7134dfd2d319d279bdb6a">llvm::SCCPInstVisitor::markBlockExecutable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aed6d706def80ab7bcb8b35112a9f94be">maybePrintComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a710878a88d68a9169313249bfd52862a">llvm::JumpThreadingPass::maybethreadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a31ba90bd367677d2bf4065d6e51eca65">llvm::GlobalMergeFunc::merge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a642ec4238f02650fc1e70d5b4ac8d844">movePHIValuesToInsertedBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aa715758b669411461023dd64ef038e2a">nearest_common_dominator</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-internalize-cpp-/preserveapilist/#a369967c56c6438c8a3711f1dda61d9c0">anonymous{Internalize.cpp}::PreserveAPIList::operator()</a>, <a href="/web-llvm/docs/api/structs/false/gepnode/#a8702875a47c894f09fb5b7f502b0b1f4">false::GepNode::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf6e500a902879012046ea1f8008d7e6">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a3c38fd13d9fa38356cca5ecdf7cfba23">optimizeSQRT</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#af7de33f6a986de428d183da62c941f13">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::partitionVariablesIntoIndirectStrategies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfounsupported/#a12864403c3efdae1dac8ca322dedf9ba">llvm::DiagnosticInfoUnsupported::print</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ad75b48c94bacfc6a1d166164bd51af8b">llvm::MemoryPhi::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a039c5bd63f390c0b66e2548b69a372c5">llvm::VPWidenCallRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac351340ed4428a1b6d69d303bcba86d9">llvm::SDNode::print_details</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a6f875a89b00cf04b3d413c954e9fe915">anonymous{AsmWriter.cpp}::AssemblyWriter::printBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a732a1e33a5b12385ee96d35735356c0e">printBBName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#a5477ec209ccebe7296e10d954c3fb86a">PrintDebugDomInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a39e0c396e9ae881eddc29a02ebc40956">printIRBlockReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#ab6e8eb04697a9174b65bf56d1a480310">llvm::anonymous{AMDGPUSplitModule.cpp}::printPartitionSummary</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5cb8771722bfd8bcbdeb391b17e6cfd6">processGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a25e3db50d3aa8a3fa245e3c2d3197d7a">processOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a96191c096e61f77ea0a6771263bdb5e1">llvm::JumpThreadingPass::processThreadableEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab7805c1d4f86c20199da1dd1fab589f0">llvm::InstCombinerImpl::pushFreezeToPreventPoisonFromPropagating</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adfeaf9db4445cbd2d43f260218036006">recoverFramePointer</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0121eb7b984a5cf2527133cb838d5982">llvm::Attributor::registerFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae327be8503a76bd4dccfff4713a38553">llvm::OpenMPIRBuilder::registerTargetGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater/#a300122a2a53b922943eff21c4039ad73">llvm::CallGraphUpdater::removeFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08f3f942afc0ee9115a8f9fa87e9191d">llvm::RemoveRedundantDbgInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a732f2f3b2dd163037799643ce7460547">removeRedundantDbgLocs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ac03fa12298f2b2ef59db774839aa630f">rename</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#acf172e841018fd16e65771f5ade0b297">replace</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a97741acf9b0e38ab508c939d99e53767">ReplaceCallWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a16096e55b9292113f13073fa2343b9c7">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceFloatIVWithIntegerIV</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a6300c8f1d33302d372c953398dd5f18c">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithNamedStructOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ac54843966305eb21541468d352728681">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8a96c9b1143670a73852464de9950e8e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceSRemWithURem</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a07714583aa2bea29cd0284d5340dd844">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::replaceUseWithTableLookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a670232d63153cd8cd2793b3106e80661">rewriteMemOpOfSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#ab9fcdedd3580f924cf782f155b549a22">rewritePHIsForCleanupPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a9db16f6b49d380b76183877d54b42c5c">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/memlocfragmentfill/#a8c0e38f8e7530ce5863d73acc50d25ff">anonymous{AssignmentTrackingAnalysis.cpp}::MemLocFragmentFill::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-dfajumpthreading-cpp-/dfajumpthreading/#a858489f4cff24516d6ac192f2165dce2">anonymous{DFAJumpThreading.cpp}::DFAJumpThreading::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/sanitizerbinarymetadata/#aeda46a0421732a3d803584285212162f">anonymous{SanitizerBinaryMetadata.cpp}::SanitizerBinaryMetadata::run</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentpromotionpass/#afe0f49f9daec2532b14ded30ed46ff28">llvm::ArgumentPromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionspecializer/#a27893e2167969de71fd88771382a93ad">llvm::FunctionSpecializer::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inlinecostannotationprinterpass/#aa0abf6fac51bc051d817b1f71c921098">llvm::InlineCostAnnotationPrinterPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a6c7a8371c75641e29a5259c131fd8408">runAttributorLightOnFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a30e276f415c0b092317585c37160f9ce">runAttributorOnFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a5b6fe6d57aa5475337994b0daec8cc54">llvm::JumpThreadingPass::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/classes/anonymous-constanthoisting-cpp-/constanthoistinglegacypass/#a6d8190a379520af73a22bb1f14b73f1f">anonymous{ConstantHoisting.cpp}::ConstantHoistingLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a50a95c05ee7d95c49a8c65c49046e3ec">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86returnthunks-cpp-/x86returnthunks/#ab4a10d58e295ec66ff8c9c1d3eeb0529">anonymous{X86ReturnThunks.cpp}::X86ReturnThunks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/detectroundchange/#a23677a404e91b3491d158fb8b0ea3f49">llvm::DetectRoundChange::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-blockextractor-cpp-/blockextractor/#ab929be069dc417044c41ddeca9bec3b7">anonymous{BlockExtractor.cpp}::BlockExtractor::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxgenerictonvvm-cpp-/generictonvvm/#ad0fae911d15e72e7f72b040a655dc081">anonymous{NVPTXGenericToNVVM.cpp}::GenericToNVVM::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#a63ce604ca599913727c7c8c7fbe4ca13">runSanitizeRealtimeBlocking</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#ab64771f762bdb53411b08c38f9d7b125">llvm::HexagonTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a56f18a5c4bcd2858f20bb765323fc89a">llvm::RISCVELFTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ae0683ad49b9a0ccca8bd1c97987a8cf9">llvm::IRSimilarity::IRInstructionData::setCalleeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a463056de56ab82cc6e2c50e5ccf17626">shouldCheckArgs</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpchain/#a6bb3a89ac6216b60c21d8815fb2fa220">anonymous{MergeICmps.cpp}::BCECmpChain::simplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ace8766b97ac54db2bec8c29e4016f3f6">speculateSelectInstLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0706966ac4f391854346bebfcda816fa">llvm::anonymous{AMDGPUSplitModule.cpp}::splitAMDGPUModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85ee70791795fa2ddb07694182f783b2">llvm::splitBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03f30f48490558525cd5458201d13afe">llvm::splitBBWithSuffix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae71573dba191b26eda0d5ea27b81ef62">trackInlinedStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#abfe26739ec5c54c0e4039d8e5d2d4a01">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryFindVirtualCallTargets</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ad5c772a0b61cb29106af3a4f9ae43d59">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryPromoteAndInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ad67aa9d5f2effed17239ab3fad098999">llvm::JumpThreadingPass::tryThreadEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a91d961bc77edfba4fb721c6637c0c6ed">unifyLoopExits</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#aae5f020a66b7a61f16cf63e17fa31e56">anonymous{StructuralHash.cpp}::StructuralHashImpl::update</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1b0f2f2dd0d27257193a0a63d9059dcb">llvm::CallInst::updateProfWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/invokeinst/#ad1f69c15f138b4ada1baae64b05004c6">llvm::InvokeInst::updateProfWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a90bcc9afc1cc990c8790a5424a93c926">upgradeARMIntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aff82c03c1ce8b945170bcb1f0f624c17">llvm::ScalarEvolution::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a81c8a5368d02d0b52654a3efe83dec38">llvm::LoopVersioning::versionLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aeac4ca2dcb29682747f7d637b47c8327">llvm::Function::viewCFG</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a29df0cec2acb067cfcb09eeeb726c7db">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aabb3d90405099bce8007a11942f3ab92">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitBitCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a48bf838fb202d25d6b13ba8048182fba">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitCastInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a16eb5732b0dacdde9b666ba69f630a16">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aee075a4b7e853e004ad694f7ef959f28">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#ac6bed7ccafa0ac0022efe4b392497224">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a32bd3fc6040488f54b8fb322216218a5">DataScalarizerVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a013a34181c208fa05a664e3f27bbad95">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a180c318fe2fe1f2f7d4f4ca4dccfd2f1">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitIntToPtrInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a9498339e26b296572a463a1300bf1a13">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aa9a049f0da67dd58d8854ac1de525ac7">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5b6ac7240be29b8a3a611a734a45d4a6">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitPtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2f39b95e8efb44737439c323b18a55d7">llvm::InstCombinerImpl::visitURem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b81e19b3ddf7ec786c5105ba5470153">widenGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a> and <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/exprlinearizer/#a4cf50167dfbcc11002f483718ac75556">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ExprLinearizer::writeFnName</a>.</p>

</div>
</div>

### getNameOrAsOperand() {#a391ffe96dd8c686b0d2620c7fb25f8a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Value::getNameOrAsOperand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a3a3a3183a327e1186dbe900032390ec6">hoist</a>, <a href="/web-llvm/docs/api/classes/llvm/functionspecializer/#a27893e2167969de71fd88771382a93ad">llvm::FunctionSpecializer::run</a> and <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#aea38159494421174efc48de560b11b61">llvm::SCCPInstVisitor::setLatticeValueForSpecializationArguments</a>.</p>

</div>
</div>

### getNumUses() {#aba0055050d741f60b6e0523507a2c79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Value::getNumUses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method computes the number of uses of this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>This is a linear time operation. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> hasOneUse, hasNUses, or hasNUsesOrMore to check for specific values.</p>


<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/#a86f06c6063c3a34171f47246e4c94ce8">anonymous{OpenMPOpt.cpp}::OMPInformationCache::collectUses</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>.</p>

</div>
</div>

### getPointerAlignment() {#a47f5c74e1b14ba4a61db057400644acc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align Value::getPointerAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an alignment of the pointer value.</p>


<p>Returns an alignment which is either specified explicitly, e.g. via align attribute of a function argument, or guaranteed by <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>.</p>


<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a35dd2e0efa71641e526e898918af9ef6">addNoUndefAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aaf7c3ea495e589d05c4e89f7c9dcc897">llvm::AMDGPU::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ac80824cf7bdae0e18c7032eb8ce5214c">instCombineSVELD1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6139b54e783a57871c92c1ac67e4be6e">instCombineSVEST1</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a2f9fee96328939e708e6c2a26a10e49d">llvm::SystemZSubtarget::isPC32DBLSymbol</a>.</p>

</div>
</div>

### getPointerDereferenceableBytes() {#acfdc7354dccb27bc092d9ac8c92b76c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Value::getPointerDereferenceableBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, bool &amp; CanBeNull, bool &amp; CanBeFreed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of bytes known to be dereferenceable for the pointer value.</p>


<p>If CanBeNull is set by this function the pointer can either be null or be dereferenceable up to the returned number of bytes.</p>


<p>IF CanBeFreed is true, the pointer is known to be dereferenceable at point of definition only. Caller must prove that allocation is not deallocated between point of definition and use.</p>


<p>Declaration at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aggressiveinstcombine-cpp-/strncmpinliner/#ac9d71bcb73b24374e675d3ac3b8f5e8b">anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner::optimizeStrNCmp</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>.</p>

</div>
</div>

### getPointerOffsetFrom() {#ac5e4e131889dc27ebec32f382c835971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int64_t &gt; Value::getPointerOffsetFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Other, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this ptr is provably equal to <span class="doxyComputerOutput">Other</span> plus a constant offset, return that offset in bytes.</p>


<p>Essentially <span class="doxyComputerOutput">ptr this</span> subtract <span class="doxyComputerOutput">ptr Other</span>.</p>


<p>Declaration at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1028 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a4ea8623be899e029827af260965c860d">llvm::DIExpression::calculateFragmentIntersect</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#ada6b74b298aa932a19fe1ccef722baa5">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::collectInitializers</a>.</p>

</div>
</div>

### getRawSubclassOptionalData() {#a3408c3cf2cef0f378bab40f6660c3341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Value::getRawSubclassOptionalData ()</td>
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

<p>Return the raw optional flags value contained in this value.</p>


<p>This should only be used when testing two Values for equivalence.</p>


<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a21e38886795ed32ec28d4eb5dc92b6a4">SubclassOptionalData</a>.</p>

</div>
</div>

### getSingleUndroppableUse() {#a7ae600e148910c49a1772ce51754141c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use * Value::getSingleUndroppableUse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there is exactly one use of this value that cannot be dropped.</p>

<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="#acb7cde93d3843abb013fe880c58e7f83">getSingleUndroppableUse</a> and <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a336ed98852175e7e955e9217080bd596">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::isKnowledgeWorthPreserving</a>.</p>

</div>
</div>

### getSingleUndroppableUse() {#acb7cde93d3843abb013fe880c58e7f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use * llvm::Value::getSingleUndroppableUse ()</td>
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



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a7ae600e148910c49a1772ce51754141c">getSingleUndroppableUse</a> and <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### getType() {#a0344a49526443edf90cc0aef3abd3337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::Value::getType ()</td>
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

<p>All values are typed, get the type of this value.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/combiner/#ae8b71818798cbd6a6e93e0fccbd39bfd">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::Combiner&lt; true &gt;::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a28c431daa68824e2c7f8721bf495fc25">llvm::AliasSetTracker::add</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#a42662469b6d20c41b3ed64e9f215b041">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::add</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#ac9d11e9f66eb3617827801cb7f0f6619">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::add</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#a10d4c86d6600a1727f3d3bd9e8f39314">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::add</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#a71ce471fff7e2bde83cdbdeb6bd506d8">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::add</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a032ee1ab74cd70ec3ff4801ec8a49f0f">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::addAccessedBytesForUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aebae63f31076e8c0dfe153c45a730497">addAssumeNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a03521060d257111b310d9da04dc20dee">addConditions</a>, <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a77dccdccff30d1cf89c684cf37cd85d8">anonymous{ConstraintElimination.cpp}::State::addInfoForInductions</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a64dcf542ea4428468c3250f5516eaad0">llvm::detail::PtrUseVisitorBase::adjustOffsetForGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuaaresult/#a268b9527fc2ecbb486822e53d18f90ca">llvm::AMDGPUAAResult::alias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a9534d3bff0727cc904e6bbc1064d2e2f">llvm::VNCoercion::analyzeLoadFromClobberingLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a54e6f143ee9c14b9498e4f43b97c2525">llvm::VNCoercion::analyzeLoadFromClobberingStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aebd8fb1e50c14f4988226de940a067ed">annotateNonNullNoUndefBasedOnAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a8508f3dbb1f9429445f50282297b4f9a">appendToGlobalArray</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#abe54f9c905611b1e6439acf843ea29e8">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::applyFractPat</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a657faf3a9e7b79484f0d514c828a58fd">applyX86MaskOn1BitsVec</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a9e70d6aa9b2f9a1b6bff9f405910e1ba">areBothVectorOrScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#af57aa964441f0796b3d49de878edaca5">areExtractShuffleVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#abd9356b1c3a69a55b72df590c48f9738">llvm::SelectInst::areInvalidOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#aa7934618280f5dc61a34615b689744d1">areInverseVectorBitmasks</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#abae944a67cbc6299389596f63df4359a">areNonOverlapSameBaseLoadAndStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiloplowering-cpp/#a4ec8ddbebba100a1e902badbdb4b3f0a">argVectorFlatten</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a81fe9e08548be6c5618ecc7213d285e3">aspaceWrapOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist/#aab54c009e65d26aaa3160eaa876c94e2">llvm::BitcodeReaderValueList::assignValue</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#af36215890e150f71abd2be2eb400487f">llvm::AtomicCmpXchgInst::AtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aef9fe930d99fc1baf2a6ae99a59df09e">atomicIgnoresDenormalModeOrFPModeIsFTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#ac70749f79f9e80a53b791daf274fb6a0">llvm::AtomicRMWInst::AtomicRMWInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a5664a95ba86f36f18dd124ea2b9f9f21">atomicSupportedIfLegalIntType</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryconstantexpr/#aba5825f2f519f76102cf1b2c6b8a9dc3">llvm::BinaryConstantExpr::BinaryConstantExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a420bedce165a865417db21cdc88307cb">BreakUpSubtract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9af7e2dd206cc24d4690e1d2a996c43e">llvm::buildAtomicRMWValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1bf8ff6aaf41f4f1f571e2346c72d165">llvm::buildCmpXchgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a54c5a810b1d6fbe75255674e7e9c40ba">BuildConstantFromSCEV</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a101a4250b1fd5a230a766de2a14cb271">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildEntryThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a9ef49346139404db3757cf8ba05dc6f2">BuildSubAggregate</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a3a5262b6225fdc05cfea242647c56db6">anonymous{WholeProgramDevirt.cpp}::DevirtModule::buildTypeIdentifierMap</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a9fe92d5d425b0ddab77a3bd58e734a74">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCastInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#ac1aa55cef94698e03f5b38274a656b4f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::calculatePointerDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a49077c24022f5ec4c84d809abf92e91e">callBufferedPrintfStart</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#a60735e0d022845d03d123916bb48e1e8">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::canCheckPtrAtRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#af10eb6aece68a8127f273e6a2dc0fc79">llvm::VNCoercion::canCoerceMustAliasedValueToLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a472408c33fff86419b4ff8fb2e343a64">canContractSqrtToRsq</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3e2793cc62829d80622b78cc681b25c2">canonicalizeBitCastExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#ac9ae2e49a0bf8f52cd2bac401c001b6c">canonicalizeLowbitMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a3c4424f4bbcee5f3dd484c2822221812">canonicalizeSaturatedAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f5cd5733f1f4d2254248b60fb8a937f">llvm::canReplacePointersIfEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a6f589baf90476080f25dba3a4522d4">llvm::canReplacePointersInUseIfEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab787227a6a978f146fcb2b2ed651642e">canSafelyConvertTo16Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a61e3236cbe0cbc94e306beb52ae1093d">canScalarizeAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a7b6c32da7b6a47b962a5bdce5a3bbc75">canTryToConstantAddTwoShiftAmounts</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#a92c9a1a2b05d0e6310b69180af44554a">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::canWidenScalarExtLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a99424675c5fc439756409a02a8f9405a">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a58d962e3d29a81e1cdd18243bf6c71d3">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeArgumentPointerLocations</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvegatherscatterlowering-cpp/#a7381b9def2e711b7f83115e43247768d">checkOffsetSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ab230432af09554d7dd357c77b0ec3cde">checkOrAndOpImpliedByOther</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargamd64helper/#a52e566979db5e4a27df0ac914873e024">anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::classifyArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ac3cf098d54027ac28278b060376bdcbd">CleanupConstantGlobalUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#a420b662320c3ba54d9560ad49c30caf0">llvm::AddrSpaceCastInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcastinst/#ad5ec02209a56c591743ec4305e386a61">llvm::BitCastInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fpextinst/#a8190171a29cd1785d483398540a7780b">llvm::FPExtInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fptosiinst/#a9d32ae6d5354d203c018765133684ef7">llvm::FPToSIInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fptouiinst/#ab4e319070c915544d080418cc7a5bf3d">llvm::FPToUIInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fptruncinst/#aa430e04b2876ce2df6e2645f47529f5f">llvm::FPTruncInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/inttoptrinst/#a5f59d3a0dab4262848e614ae0b73f37a">llvm::IntToPtrInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a8195fc57735a947a24bc9abee4a9c4d5">llvm::LoadInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#aea9834ebaa7797545bf6d263a66e9d2b">llvm::PtrToIntInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sextinst/#ae1a62d40883ff9a1008509b322d5d0b3">llvm::SExtInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sitofpinst/#a04cba684a78bb685e087842264cc121e">llvm::SIToFPInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/truncinst/#a29fae577a052d379c000bd4a08948105">llvm::TruncInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/uitofpinst/#aa89899a2dfe4b0ae836cdc5a23100971">llvm::UIToFPInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/vaarginst/#ae9ff6645dc0055fe932aa1bd5644d89c">llvm::VAArgInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/zextinst/#aebe48c365b31c0267d1ce8b91e566c4e">llvm::ZExtInst::cloneImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a21408b47716ef75ac95ded9097918f0a">llvm::FunctionComparator::cmpBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a351251756a2dcf559089f626d9241131">llvm::VNCoercion::coerceAvailableValueToLoadType</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a4b65c40648346b8d99dd58a2d3d318e9">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::collapseToPrimitiveShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/typesanitizer-cpp/#a8fe9c2e5d8a275393677c1c46c5f0596">collectMemAccessInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a1e502a1ec39cc64d6b86e9e68b29be89">collectShuffleElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ad7d79bd0b027705195d79619a1d0450a">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::combineOperandShadows</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a0cd7231f32d51864a9e307330e798de9">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::compare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0e0ddbf81c5fa1ee764ba3f4bd6ddbf5">CompareValueComplexity</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7032e1ab44275cf7331a7898a3713aad">llvm::slpvectorizer::BoUpSLP::computeMinimumValueSizes</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/vectorutils-cpp/#a25f997e4301f90461b6d4c57890dd99d">concatenateTwoVectors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4288169d91ab0f0f01405115fd2931a7">llvm::concatenateVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregate/#abecd8e154b2d3fb93c6b32596a899fc5">llvm::ConstantAggregate::ConstantAggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f6c692bb79cca65ae3097ddd4c47e69">llvm::ConstantFoldExtractElementInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bf95d0980fad19452f4c9aca445af3f">llvm::ConstantFoldInsertElementInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7fa9b738742521d0a684cec016ef47e">llvm::ConstantFoldInsertValueInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ae6e1699b7b98eaaf080f652b08792b9f">anonymous{ConstantFolding.cpp}::ConstantFoldInstOperandsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d58e0e9c2196e30a314dbc5d3431524">llvm::ConstantFoldLoadThroughBitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c89e0918b007ef2cf1d6b03c4b4948">llvm::ConstantFoldSelectInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a923c4a7af45a4531da9d7cee1041c4bf">llvm::Constant::containsConstantExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab77dd880f8a4804500c2fd5c4df979ee">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79e6c0c958b2de133d4b9d0e2c62f1e4">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8946e172b10c0ef5eaebb28ebb7662ad">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a07a576318c1a362676e2d4ff00b921bb">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e94595f29a0adde822a318f82dac61">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82984d4a91e7dc2072dfd8fad2854618">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a787f048d94a8f173da27cb792cff4758">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::convertEVLToMask</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a5ccdf0465e957f46ac1241b63af00864">ConvertShiftToMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aa49cf0e393f7067f09985cec1d4b7387">convertStrToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a7c67e5393efc9e53e1a841b70236bfcb">copyFunctionByValArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e44f52bb2b2c5d2273eccec70faae">llvm::copyMetadataForLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab057ca6ed74ccfa73d1a0d2cf15b2300">llvm::copyNonnullMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadb1772c1026a517d15c771ceb6a91ca">llvm::copyRangeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/unaryoperator/#a2200cefdf51f62605459b2f2cdfccfa1">llvm::UnaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a480959ce9fb41e0ac0ce2cd7907d7ace">llvm::IRBuilderBase::CreateAlignmentAssumption</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aaf8f473e687dfed67deb33964989fe57">llvm::IRBuilderBase::CreateAlignmentAssumption</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac1ec85c334d8b88e52733711e53be856">createAndInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a6cc340cf5dc46cf45eb6f784577cadbd">llvm::OpenMPIRBuilder::createAtomicCapture</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab84af206a9a08b9bf97eaadc87874c6c">llvm::OpenMPIRBuilder::createAtomicCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab2a2c89b21cf14b2c729a898006cb438">llvm::IRBuilderBase::CreateAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#acdb02479a44bbebcabf8b7b5e1baa921">llvm::CastInst::CreateBitOrPointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ac669acbd0f638c6ef32977575362052e">llvm::OpenMPIRBuilder::createCanonicalLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a93b7c4ad8be280f28707e920e5f3a41e">createCmpXchgInstFun</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ae5881267e88ebfd0527460a92b61f960">llvm::MatrixBuilder::CreateColumnMajorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a69138108d0e5888e6cafcdd27d082fc8">llvm::MatrixBuilder::CreateColumnMajorStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a7ea782436f7a688ebb717a91808b9c5d">llvm::AArch64TargetLowering::createComplexDeinterleavingIR</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a5098d4bb22d4347dc55e1d08dcbe6708">llvm::ARMTargetLowering::createComplexDeinterleavingIR</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#a05b24458637907fb6e27a842cc8dc0fc">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a102aafbf0ca4e05fa1620a24f797fcfb">llvm::IRBuilderBase::CreateExtractVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae3a4c284255a153d29ddcbd05bcf5345">createExtractVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a30a82385a4d14528fdc9819501044523">createFFSIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2811365af41b41df986ec1144b22d223">llvm::IRBuilderBase::CreateGCGetPointerBase</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a517ef9bae2905eedbd9c88e926065430">llvm::IRBuilderBase::CreateGCGetPointerOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a35929b5ae2c67d8c86640518636092ae">CreateGCStatepointCallCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a2f89404be2430701edb3e9827aaab276">CreateGCStatepointInvokeCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af377188a476a2d71184b0498a136fd1d">llvm::IRBuilderBase::CreateGlobalString</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ad035539cf7c551ab8d10af8a3a6c0f00">llvm::MatrixBuilder::CreateIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#acc518623c0b37b3586bc69a967ec83bc">llvm::MatrixBuilder::CreateIndexAssumption</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a28d8fda3ddcb508d0b669cda059ccd4d">llvm::IRBuilderBase::CreateInsertVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7fb2c76ce3457d7b38dcdfbe1d5fd051">llvm::IRBuilderBase::createIsFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a925d3d4bfc5ca46ef574619a0700e6d5">llvm::IRBuilderBase::CreateIsNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5bee51bbb174e00c367a77b98fbd2632">llvm::IRBuilderBase::CreateIsNotNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aafd864f39fd28e235eea03ae424ab8e0">llvm::IRBuilderBase::CreateIsNotNull</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac9843b4f9f9cb144c608c48785a394a8">llvm::IRBuilderBase::CreateIsNull</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abb42f81be3350e8f94849e8e6aceabab">llvm::IRBuilderBase::CreateLogicalAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae1db5150fc798ca464de8923ba0b8e7f">llvm::IRBuilderBase::CreateLogicalOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a291e8c83a8c02664076faa0896f1dbc4">createLogicFromTable</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a445fa52d77040bccb16bfea111234a2e">llvm::OpenMPIRBuilder::createLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a792b08a6322bb539ee5ce2f754588c8c">llvm::IRBuilderBase::CreateMalloc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2001dcf6278f9e7e10b895d060d15abb">llvm::IRBuilderBase::CreateMaskedCompressStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#afa922043d31aa2d3410fe0be8791b795">llvm::IRBuilderBase::CreateMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aee07a8623893cdad858a3b5f77354375">llvm::IRBuilderBase::CreateMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aad07e3e0fa03f6c780e13d924325d8d0">llvm::IRBuilderBase::CreateMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a44f4e9b64d7a612f2b8236f0d147f591">createMaskInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ab245615ce0c4feee775f0d793d9ec6ef">llvm::MatrixBuilder::CreateMatrixInsert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a61a95dc82ae09814a35f56fcc56cad5b">createMemprofDefaultOptionsVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a6472f2a2e040373d958419bde7523539">createMemSetLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointbuilder/#ac1e07222d14c1bc6e996ca85ca126e93">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizer/#a52c61b3548ffc6f5088b78dc45141354">llvm::SPIRVStructurizer::createOpSelectMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affc1b0222446287a4297e23855a5e18e">llvm::createPGOFuncNameVar</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a1536669cae3776862c9ed0a566595b7d">llvm::CastInst::CreatePointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ac120250caf531b58acce9d8cc34c7032">llvm::CastInst::CreatePointerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7891243700b67217e42c82bb4224eb0c">createPopcntIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aa140da54e72854ac947e8fe8c1aa043f">createPowWithIntegerExponent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#aa4ec1be5a80593697012bc67e2410e11">createPrivateConstGlobalForString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15889f1df360601e4f92325b39882a34">llvm::createPrivateGlobalForString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#adced657ead8595f4da252cea6e2f3dd8">createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd35d43ef05edd633413fa4cfa802c0e">llvm::createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a55693c3374f66a0794daf3c1dbd00974">createRawLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#abdf3ba57973320bd702d3b12b0b8fa8c">createRetPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a154fa9a8453f440902ba70defcb9ba44">createReverseEVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aeff5766c114e19126ba79be81e93fcd1">llvm::CastInst::CreateSExtOrBitCast</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a45f6cbf770c1d990014838ceb300e936">llvm::Attributor::createShallowWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a272e4181c033386bc62da6704be2d3e5">createShiftShuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a0406832b34218bdfd92947d2612f3c3d">anonymous{AddressSanitizer.cpp}::AddressSanitizer::createSlowPathCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abd45d87893b2cfe481d5fd6fd97999f1">llvm::AMDGPU::createSlowPathCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#acae95016bcdeb105bcbcaaa872893f5f">createTargetLoopWorkshareCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a991aa40e1236f6093ee0c3d93628319c">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a26d326912ec9ff7ea15f2b356f5d31eb">createTileStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a7bab17532f2b606ad25679ed9e138c73">CreateTripRemainder</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aab3f4e42107a79ae5939cd350e77b834">llvm::CastInst::CreateTruncOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3de426ba33675f047a941f656b33341b">llvm::IRBuilderBase::CreateVectorSplice</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0ec3f501c3072d93443b2a055b7d3c3d">llvm::IRBuilderBase::CreateVScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ad120ee39de5a92d1581ba9a5e1072296">llvm::CastInst::CreateZExtOrBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#abe3945bfefe671a9a34f864d493d5fe7">decompose</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a32e5e2e67b52bcd45fef4487f664f9ec">anonymous{DeadStoreElimination.cpp}::DSEState::deleteDeadInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper/#afb93c0389fa161c51b25541def502b89">anonymous{InstrProfiling.cpp}::PGOCounterPromoterHelper::doExtraRewritesBeforeFinalDeletion</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ae45f11045718186c0300d34919228c2a">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIdentitySCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae744a53dbb2720e5678fb879156761e9">llvm::embedBufferInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5730c4888cfeb0d60f0afc368e179d61">llvm::emitBinaryFloatFnCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#aa71b78b68e5077a0c0201ceb8b5cbe85">emitBinaryFloatFnCallHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a949a40285ef7371d1d242ffc66337c7b">llvm::AsmPrinter::emitGlobalConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#af7fb6d7d97dc4e12a6ac3a9efebcd71a">emitGlobalConstantArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9fcb3f76aba8a8c062f9db30393cabfc">emitGlobalConstantDataSequential</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a1b10a2f32679fe17714d07081c36be28">emitGlobalConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ab23c37279d90814b87d6c8ab25b43d0b">emitGlobalConstantImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#af8918ba9c2bab47454cfbe9bb8942871">emitGlobalConstantLargeInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ae9aaedbefa65f41bb54b62d9137f13dd">emitGlobalConstantVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad8bec6d053e2c93fee21eebfffae31d0">llvm::emitHotColdNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb10d4f78442972e711932060882cd79">llvm::emitHotColdNewAligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ee7adc14967589134b654d321b3561d">llvm::emitHotColdNewAlignedNoThrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6cfbf3bb83193d8447d8f7c392915cb">llvm::emitHotColdNewNoThrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad721b230836c9430afd9a392db0c7c5a">llvm::emitHotColdSizeReturningNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf8c11d60a5385f70c3a140c03f136e4">llvm::emitHotColdSizeReturningNewAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a91b7eb2a05d10c788413bec7977f3474">emitImplicitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a8631130c37aa54ae6c9127abc5fe392a">llvm::AArch64TargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab439771b84f342c37a8823fb2f797642">llvm::ARMTargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a34f5b50de28a2e4f6aa78069f36c9816">llvm::LoongArchTargetLowering::emitMaskedAtomicCmpXchgIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a683761fbb11ed0969edf7eee08b08bf3">llvm::PPCTargetLowering::emitMaskedAtomicCmpXchgIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a56ca709f7f49818ffef3f5103a13a5a5">llvm::RISCVTargetLowering::emitMaskedAtomicCmpXchgIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a6afb7e7298c87508bd965772db54ec19">llvm::LoongArchTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a0e0d3c023e19c20fbf01b40d36aced80">llvm::PPCTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a241b3032c605e4faafb173c3adf15105">llvm::RISCVTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a133fc35b714b7fc4b5a0935c811ed37a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::emitSIMDTiling</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#aaa3dfbded3ebc8068ad825a039bfdfaf">llvm::HexagonTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a1c68a6f0cdbdeb8a431791ad286109a0">llvm::PPCTargetLowering::emitTrailingFence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a23f5821d9ac264ae25dd087747e2c181">emitTransformedIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d61091498dd892d586e250c8d29fe3a">llvm::emitVSNPrintf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9310a89abda7116ac06bf226544daadd">llvm::emitVSPrintf</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4bf34b557699d07e1d58470100ba982c">emitX86Select</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6fb486939378ca836b98249408abcedf">llvm::ARMAsmPrinter::emitXXStructor</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a63540fe3243b44a62cb656c73274f8ac">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::ensureType</a>, <a href="/web-llvm/docs/api/classes/llvm/evaluator/#aac9fd94c18d93885c8d947121ab9721e">llvm::Evaluator::EvaluateFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#aefdc5e2a3d0696ee5c5bf0b467e5f0c5">evaluateICmpRelation</a>, <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#a0b6f2c0e5bec17e3b7fddc78e12cd5d1">llvm::VPActiveLaneMaskPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a19aa4af9c02f8e3571cc82c0634a25f6">llvm::VPHistogramRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#af2ef259f4a63359fe35f05b8b67a911b">llvm::VPInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ab0d48fabf61af227821d568b1c3aa4ca">llvm::VPInterleaveRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vppartialreductionrecipe/#a29641e0ae49abc7a19221cc882c08da6">llvm::VPPartialReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a3e63796e123d5ba9cbfa023983328c37">llvm::VPPredInstPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#ac66885d3ce04a263a03746461eac12b1">llvm::VPReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a2ed5b7b284097278ee4e550897b1f057">llvm::VPReplicateRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#ab76c8b759635aabfadc49dc1292aec2c">llvm::VPReverseVectorPointerRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencanonicalivrecipe/#a06435ca2ee49b05bd4d93bdbb3b7d8e6">llvm::VPWidenCanonicalIVRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ad6ab589f9da183bfc7227344c30aab78">llvm::VPWidenIntrinsicRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#afd60b87e0eaaccd0f8c122208ac1049d">llvm::VPWidenPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a505ddaadef479f2d0c0810c203000eaa">expandCrossIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d3e8ce57fb65481a42b256d26c264d">llvm::expandDivision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cfb58d48c02daaaa8ee7e924e9fb36">llvm::expandDivisionUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c6db1ba2b3654c01ec2363b2bc34ce4">llvm::expandDivisionUpTo64Bits</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a9b0aeaa55a33109c212ca71908c51131">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::expandDivRem24Impl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a4b23196df4c243ce29f29f54a26cae7e">llvm::ARMTargetLowering::ExpandInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a687e754bf03f8d135bc899b49db74472">llvm::X86TargetLowering::ExpandInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35f13ead4222c0c45fb21f7e63025bbc">llvm::expandMemMoveAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a017debc0002d97577349af103f3bbe4d">expandNormalizeIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a3eba8b3e2e38c997d14bc2ee850be29a">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a1f1f1359a986d8e4d1b107ae4c524a32">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInMemoryIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a2153c46ea6d560ce96b6ad7e822d2c70">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInReduction</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a5cd88dbe6fb8f2ddbd621296ca4ebd5f">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToCastIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a62f9944dba24143c8954964d7dff45b8">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandreductions-cpp-/#ae32d63d2aee7169e45cf696b040ccb66">anonymous{ExpandReductions.cpp}::expandReductions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0154d60f04a5d8549b44635852557f0">llvm::expandRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a090725add53936fcebc89f58fc9a7da1">llvm::expandRemainderUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27da54a97fcba955457048148b1fef99">llvm::expandRemainderUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ad28c25a19888a3846117d94821e75042">expandSignIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a53468ec93dc5de2584b89a719ab34627">llvm::AAMDNodes::extendToTBAA</a>, <a href="/web-llvm/docs/api/classes/llvm/extractelementconstantexpr/#a2b3ae15f9761af81b8744359323a5799">llvm::ExtractElementConstantExpr::ExtractElementConstantExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a8078ce258348e8fd9d2e16bead13e770">extractMaskedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a790e9b70f12899a4cb2aefd33826ee7d">llvm::AArch64TargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6914b95d1fcf7a5aca24fe82bf4100c2">llvm::RISCVTargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a07fd59cf6f37dd8cc9b6f5f2d0ff3e59">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeFloatZero</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#adcf5270fa9a80077dc604114f66fafaa">llvm::FCmpInst::FCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#a254cb3886750473f69d9a9f8b0cbbdab">llvm::FCmpInst::FCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a25781ba284c79cb93c65fd0c529ebf7c">findCommonType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aa5aa7648807905cd7b63153812029fe2">findDemandedEltsBySingleUser</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a51a05a00df99aa3401385eb46a6e5ae1">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::findDppPoisonedOutput</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a221bfefa2a7606c89cb5a8635375f891">findFuncPointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#adc183a6edc37f305ee9ca5ff0bc33a6e">FindLoopCounter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab09fc7dee4f7e02c60f7a9c928dc1603">llvm::findScalarElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a971a505a1d78e8a14569d04e0ec1b169">fitArgInto64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a0b7d633cf22c2f54d391f3f5c0a5ef56">fixupFPReturnAndCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#aacbd97f1443d5a400a39b1899b363812">flushDenormalConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a69211e2fb3d1eed7ee14964bfc04e261">llvm::FlushFPConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#adbe242b084763cfdb35c7850bd4098b5">llvm::BinOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a45ec897890074179e7de73b934798976">foldAndOrOfICmpEqConstantAndICmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a36b7410be1f86b52970bb1381904e282">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a6556e45ee27ad333bf33eda6b1f04b8a">foldBitCastBitwiseLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a5d0fa3868fb321fcd4b5d632028db897">foldBitCastSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad600d9077d7e1eadff1334ee14f7f25a">llvm::foldBranchToCommonDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ab737e320d75547e2b43f6044fc3f3bcc">foldCastShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a5a43eda4795549e941b4bacafdb956bb">foldConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a2c93d37ad765182a1bc1e43f4b967b99">foldCopySignIdioms</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a3ef88a20b7b51243e963ed25e0e0c30e">foldDependentIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a7cd9c2a24848210d4d3c7798c6093a55">foldFCmpFNegCommonOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a568e85197421e091a259bf80e19c6765">foldFPtoI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78688f28e25e6d68d3f06ddf6e7aac0f">llvm::InstCombinerImpl::foldICmpCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d58c11c9787c2764e5f11bb127ced00">llvm::InstCombinerImpl::foldICmpInstWithConstantNotInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a8d4d5411fbc454f1beedf2b79abc6571">foldICmpIntrinsicWithIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1140591a375ac3efde57977192880eb0">llvm::InstCombinerImpl::foldICmpOrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a60d8db999d3887919b031cd5b85db10e">foldICmpShlLHSC</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a06131a96d98381fd2b73c4ef401d416c">llvm::InstCombinerImpl::foldICmpSRemConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a39e315cb89b7144083895c083cc958e0">llvm::InstCombinerImpl::foldICmpSubConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9175bf0e4b0c3a18e2f86bb11270ee78">llvm::InstCombinerImpl::foldICmpUDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9ab27a13577b53506529f28d41aa0672">llvm::InstCombinerImpl::foldICmpWithCastOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a84f21a080a9d5fddbdcee787d3f295e0">foldICmpWithHighBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7caf9cd5dff4734b8af500d6f0f07437">llvm::InstCombinerImpl::foldICmpWithTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac91d6fa292dc4e13ce99fc9f02c90f85">foldIdentityShuffles</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78d5bb4c6437373debabeb3f816645cb">llvm::InstCombinerImpl::foldItoFPtoI</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a12f6125cdd608cb0459585ddb68ead53">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::foldIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a45705c727d8388c014471504b4ab0c4e">foldLogicCastConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#aa875b86e81398234a9aa576ab946c76b">foldMinimumOverTrailingOrLeadingZeroCount</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aed2c2c5e2a07649e02d6647d9a5c8852">llvm::InstCombinerImpl::foldPowiReassoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afcb58333497c40468d7889705a5d0b03">foldSelectICmpAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad51f65187d4c6b69d6bf8f71e027e4de">foldSelectICmpAndBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad76042aae559769f4dc50ee2f9548789">foldSelectICmpLshrAshr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a525ea3a09eef862d8b6480717cbe7901">foldSetClearBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instsimplifyfolder/#a8db493e6d91726e469aa91fa425cd269">llvm::InstSimplifyFolder::FoldShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a661440047dc1b2af077911d9cf92236a">foldShuffleWithInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa72b51b8f455c8a622bb6f8cc9c14860">llvm::InstCombinerImpl::foldVariableSignZeroExtensionOfVariableHighBitExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a26105b2c5dc3071155303a10ef8c3923">foldVectorCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aee3e98b16f1c8d8d8b30b9a459a6a602">foldVecTruncToExtElt</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ad15d45b871d3111e8da4f9b394d7c83f">forwardStoredOnceStore</a>, <a href="/web-llvm/docs/api/classes/llvm/freezeinst/#a2b19ed32ae29a202bd29f9401ecb034b">llvm::FreezeInst::FreezeInst</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#a045f5491e24124a1ee6f454e5119c38c">generateSignedDivisionCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ab15480fad5e956eadbf7c6fa518c642e">generateSignedRemainderCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ab00c6dc5086df2a37cd2e78715968861">llvm::ConstantExpr::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a6c1bd5fd8ec3eeb7320cd9d457b0f164">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46d61c561714322cb42bd3db9f1609fa">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7f4680b383ce7138bc2c12de282b14b4">getAccessType</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotionhelper/#a6df9b95e8bacacbad0035f25c46d2581">anonymous{CodeGenPrepare.cpp}::TypePromotionHelper::getAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a94b8d8925deffd735f51d36b77d3f9ca">getAddressForMemoryInput</a>, <a href="/web-llvm/docs/api/classes/llvm/inttoptrinst/#a69434c1c574013fb2765bd2c5b27cc7b">llvm::IntToPtrInst::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a2486e46f400c6bb9acdc1441c9a126fb">llvm::Constant::getAggregateElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#acd530d0571f320d47d37e7ae51cf70ff">llvm::Constant::getAggregateElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#abd4502cb507e24663c9bcf9129eb4060">getAISize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acdec81ddbe2a44db51de1226fa1ff5f0">llvm::getAllocSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#af7e7c9415c23ae336af651877798a377">getAlternateBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a2e25b4d49c29e587a6a408e19f57ab0e">getAnyNonZeroConstInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ab5e88a19352e7dce1b0115f5e6b37b47">getArgSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp/#af00d722295f4e7b769e28af02fbefc1f">getArgumentTypeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af9fc0080b4accc0b19bfbbc624701e30">llvm::ConstantExpr::getAsInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afb6a2b1b5242599e12b7fe897140eda3">getAssignmentInfoImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">llvm::IRPosition::getAssociatedType</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialconstantvalues/#ac6c45f02f71621808dd33da72d73cb00">llvm::AAPotentialConstantValues::getAssumedConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a1e99011cd6c37ad4ab5be287c94735bf">llvm::AAValueConstantRange::getAssumedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a11d6de2bddc669af3e9b358e46e38e9e">getAtomicOpSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a48ac978d44f5d426d300a400142708b5">getAtomicOpSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#adccfbc5892aaeafbf2178ddc7c71bde5">getAvailableLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#ae6c02f1cd1e346da82377714db2a5033">getBoolVecFromMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a4d34a6e13a44aa2f7c490762cbd3afb7">getBoundsCheckCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#af0e4d9315f1815020f42edec6a27ad1f">getBranchCondString</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad1ed10076dcd144800421886c7caea42">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a3abb1cc80a02ab7f543ff2d98987e121">getConstantInt</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a79e8ff1687364a4f9ac11f6dc1c4ce2d">llvm::VNCoercion::getConstantValueForLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a8e787163c914dba0f28ef79e92c9768b">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraintForSolving</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#ac9234105b582bbe087981c231eb7b292">llvm::AddrSpaceCastInst::getDestAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#ad118358d398f591303b00c2e5462e3a9">llvm::MemIntrinsicBase&lt; Derived &gt;::getDestAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aeba3c4846ce91323f585f957963d8f67">llvm::CastInst::getDestTy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a5d6281f602a2d61050f8e8214c34b16e">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getDivNumBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#a36b782c6eb416c7d3b1086d5f50b2e54">llvm::ConstantAggregateZero::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#ac0d41ea0afa3131e1a0838e07c111c0e">llvm::ConstantDataSequential::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#a9e8fadb6ef05bea5f591cae0125344e1">llvm::ConstantAggregateZero::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#a4b63206cf34ac604b93967cda7c6b7e5">llvm::ConstantAggregateZero::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#adfec4ea2af1aceb0553bed871d24c67e">llvm::PoisonValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a750bda5b8bbe027514b4a11bebc5f806">llvm::PoisonValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a081de928f8254a95de78630b968e5b4b">llvm::UndefValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a0fd8c8463763315a08157f4f1ae5ddeb">llvm::UndefValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a078455f9a6da73bc84f24700a81d19d7">llvm::ConstantExpr::getExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a4904e476c0d296b50491f629f7de59c3">llvm::MemoryLocation::getForDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#aa116214bf0f5cf6201935447b27334e8">getFromRangeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#ac2f8a243eec640b2ebf8e022d57c9411">getFunctionPointerElemType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#aec8bb28502320250bf2d4a55ab99e242">llvm::DataLayout::getIndexedOffsetInType</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a46b5cd2a0881c8be5183d70a32eef90d">llvm::CanonicalLoopInfo::getIndVarType</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#a232bc3cdcfa2bab0574af9b47ff90c41">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::getInnerResumeDest</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a64d6bd55aa4447bb25f1361993223450">llvm::ConstantExpr::getInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a4f9d007abe180fd0a5d2ed7cbec50e58">llvm::ConstantInt::getIntegerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ac475c1bc115b2d8b03a7959be84b1ca9">getInvertibleOperands</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a7159508155406ad5c350cc429980e09d">anonymous{AttributorAttributes.cpp}::getKnownNonNullAndDerefBytesForUse</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76e90df9d2b35d9174077de99d909165">llvm::TargetLoweringBase::getLoadMemOperandFlags</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a0fd41cd05155ed81f0ac16e8a478b860">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getLocalVarIdptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#aeee622fb99bdc4c058a9ef179d0a0d09">getMaskedTypeForICmpPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a92bfc4d7aa6add742c2a82b2e8f61455">getMatchingValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aad5def33faf75944be159808071d9698">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getMatrix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a6b72d403292d9dddd1ef1ce3e8bc394c">llvm::VNCoercion::getMemInstValueForLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ab55d9da87838f5736581bfcd5b54afa1">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae94615351738e4ace274b61029700da9">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ade3b3b604b9b365a57f791ab198a691a">getNoopInput</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#aa1bb0403aefc1f09b73e96d9243d3673">llvm::ConstantDataSequential::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a6854d18eda81a9867ab5b4aefb844db0">llvm::UndefValue::getNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a68d20206b060ac3ad19f416ed5a4899b">llvm::offloading::getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike/#aad811cf3b50296c6f065133a96294e28">anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getOpCostOnBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a338bc4206ec4d19d62a2567d60c9c36c">llvm::AArch64TTIImpl::getOrCreateResultFromMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#aa83b181aa14d5afe1390faad388f91a4">llvm::InnerLoopVectorizer::getOrCreateVectorTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a2c33b15661e7fc5f6f1ae9bc1004744a">llvm::AtomicCmpXchgInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#af39e1cad69b6406376c47e4b111228dc">llvm::AtomicRMWInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#a378cf64c77de950ae67fc6e279e34620">llvm::PtrToIntInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a28bf8984fbfb08fd27df435e631e6832">llvm::ConstantExpr::getPointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a1f469b1f703519ae25ce564c8704310f">llvm::ConstantExpr::getPointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a43e0076afb4800dd00a72e0a4171f667">llvm::GEPOperator::getPointerOperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#aae8254e868c5d6a9ebaff577e7fdb14b">llvm::GetElementPtrInst::getPointerOperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a945c21ff70f310de538153db17e7b857">llvm::LoadInst::getPointerOperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointoperator/#a90682a7985b212c30341ade867c543f0">llvm::PtrToIntOperator::getPointerOperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a3b6c763a8feb798bae343dec87529b06">llvm::StoreInst::getPointerOperandType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5997c4992589047ebc712b52b6e101cb">llvm::FastISel::getRegForGEPIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a0b43ef7c72a8cb10a0cb09154a3b3b2d">llvm::slpvectorizer::BoUpSLP::getRootNodeTypeWithNoCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a7cda2537b71f969625ba49ea583a70f4">llvm::VPDerivedIVRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#adfb86b2782f4476b862b9bd9f1157f26">llvm::VPWidenIntOrFpInductionRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#a63af5f287e94f3d11f879c1512b2f0f1">llvm::ConstantAggregateZero::getSequentialElement</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a92e67f7da40e1b5d1bf0163a6284fc45">llvm::PoisonValue::getSequentialElement</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#ac1a71ad4196bd3e400699fa02e152958">llvm::UndefValue::getSequentialElement</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a7480612cfe31fd07e5d1d5d45bf3c3b4">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrKernel</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aac05ca292709f88f6ba0ae241e0e84bf">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrUserspace</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aecd57a29db63344a976ec5830496e733">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowPtrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a266c328585c72cd84dc48ef488acef49">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getShallowScore</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0096a88b01feba943407155e0b6a1e77">getShuffleDemandedElts</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a6f6506f0bc515fe29da3b58565300017">llvm::ConstantExpr::getShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0f12063b62264c753e65abb8e9ff29d8">llvm::ARMTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a685bfe474ca920468f17fc82cf4664e6">llvm::PPCTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a900def112d7e109823a5bb89a3c01dd8">llvm::SystemZTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ac437e7230f2990fd60bf089f20ea2e78">llvm::X86TargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a1050308e21901d5abbab72e0d6e1423a">llvm::XtensaTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a25ca2f3cb40ae1c26c73054659203b2d">llvm::Constant::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#ab292fdaede434f81cf224662e9de7e35">llvm::AddrSpaceCastInst::getSrcAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastoperator/#a6239a1c5f8bc81d1d3b77b7f338a6342">llvm::AddrSpaceCastOperator::getSrcAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a01cc70c1e8052996fb44f59fa63a015c">llvm::CastInst::getSrcTy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcprojectioninst/#a6cffcfabac72ca61185ea24c1208b937">llvm::GCProjectionInst::getStatepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#aec5273476a8a080ea53c3a94ad70ed0b">llvm::VPIntrinsic::getStaticVectorLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#acec08d690b0cd43dfa708f6dd754712d">getStepVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a43ab95f8d1cfe32b5c75a4d4d666d89c">llvm::VNCoercion::getStoreValueForLoadHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#ac1fce2baaba15c35a2bb18563ef08678">getStrideAndModOffsetOfGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#aa91e37c28a0db63d2acfc33ecb15e0aa">llvm::ConstantAggregateZero::getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a91118060af65a58fffc1c8eb85912cb4">llvm::PoisonValue::getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a28582f3720134b47468804fff5ac5368">llvm::UndefValue::getStructElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a798a85d56b9dc609e615130607563819">llvm::AArch64TargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a5d19f3955a23e8eb2a974efcc8fb19da">llvm::AllocaInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#afa1ddb91b119080599eeb32d57ea26d1">llvm::ConstantArray::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#af25529592c7a7bbffe7acbc752d513c0">llvm::ConstantDataArray::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a8e9244979dfbcb32adc9f628ac06a0c8">llvm::ConstantDataVector::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#ab7338f76624b2494acf477ee8ca0dd9f">llvm::ConstantPointerNull::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a9c076d9864c54370f92e1ab92f66fc5d">llvm::ConstantStruct::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constanttargetnone/#a6e12bb5a1f04eb21d5121fe4195f858a">llvm::ConstantTargetNone::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#a905aa2c18ca16ed8304461695f373120">llvm::ConstantVector::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af135b4f1b9124a5a7497af5f39fc012a">llvm::InlineAsm::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/insertelementinst/#a49230ece74a48a27fb2bb1a4928b6e29">llvm::InsertElementInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/nocfivalue/#a89693ae93fe5bea3c3f3c5ce57e7bb4f">llvm::NoCFIValue::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a94abfc169f1ff22a179d219f781fcc94">llvm::SCEVUnknown::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a59c34209e9206120edf7ce3c5da4f872">llvm::ShuffleVectorInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a056eabb719f475aa4c5a7e2ba11973b9">llvm::GetElementPtrInst::getTypeAtIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3e8b055fdb7e07479b83d69c15211d54">getUniformBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a0786ad18996fdeb6bb0e33c3bfa4ce82">llvm::VNCoercion::getValueForLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a4a9e209a264c8bc0020eb0feb1d4a32b">getValueOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad1f0755693a05c2b008e9a576c3b162b">llvm::LoopVectorizationCostModel::getVectorCallCost</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a54f30c8bea3912d1d0f347626c395be6">llvm::slpvectorizer::BoUpSLP::getVectorElementSize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab3d70bf3dae5a7c20d3a0ff4fc67a000">llvm::X86TTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5abced3ab870d7abf57f2b35a02cd041">llvm::LoopVectorizationCostModel::getVectorIntrinsicCost</a>, <a href="/web-llvm/docs/api/classes/llvm/extractelementinst/#acac09986a48f1f758f882cc7ba780c08">llvm::ExtractElementInst::getVectorOperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a42f1b66a51c9c74a14385ead6991e370">llvm::RISCVTTIImpl::getVPLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a2c90afd148f896bab791bdcad6b41dd0">anonymous{SimplifyIndVar.cpp}::WidenIV::getWideRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aab577cba8223fe4bb96df5591d49d98a">llvm::ConstantExpr::getWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#af9ea64c7dae47dcfa2c9f5775fb5915d">llvm::GlobalVariable::GlobalVariable</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#abba654ce68a6aba9f7cbd731b0917877">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleAVXMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae2ebbbbc990e3d932da5d0d0ea255f42">HandleByValArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aa28fe1a3de7cc0e732f5d7ee1dc5adbd">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleDppIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a823e9b0883ae72e62421714cd8bbda4c">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleEqualityComparison</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a04fa6c52e825a7d994a3a5eeb1cc4549">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleFunnelShift</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a94631928dd87cd8134a31c5fb3168c70">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleIntrinsicByApplyingToShadow</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a512e6c35c0ac3187be4445bab50b766e">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMaskedCompressStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a5056eaa4a9d5c87c3566577a0736c47d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMaskedScatter</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a3405abbd1975b05777dc44d9089f1ece">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMaskedStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a1f4b3d9a1db2a863f398981ea5c1d641">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMulByConstant</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aa78bfa47c700608c53890cc25cd44a5b">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleNEONVectorStoreIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a7f7861a70cfa57999c2b47e570be2127">llvm::ValueAsMetadata::handleRAUW</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#ac689bdce81e76d215f170f7eb3821be3">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleRelationalComparisonExact</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a220983874e8efc856fac602c19e9aa2b">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a047890dfe94355c41e98c0b8561b9f14">handleSpaceCheckIntrinsics</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a8ec2e744dff018b81c0eb2a7e9ea4e2b">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorConvertIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aa386f90ca7b1b24989ce41d70a0ce052">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorStoreIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ace87755a2044122196774c1cb0368fde">llvm::PHINode::hasConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a0551e2af33758e2c39e724ec4f205263">llvm::Constant::hasExactInverseFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#ac2717c2132c268d29f71c5c86cc40971">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#a613cbb92bcdafb29568798d6b520e3b1">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a78c7e7972f2cde9531b9f9d71196cfc5">hasSameArgumentList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ae965d93aa46ad834c21718eba4b5b78e">hasSameExtUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a2472e4d5a0e2f4d6d41f2f58c8261348">llvm::ICmpInst::ICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#adf8d12a487891532df62e728d22f2c6f">llvm::ICmpInst::ICmpInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a7cc7cd380b6ceacc35ef685d5b047d80">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::identifyReductionNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#abc9e58a3e27b86d2eb05efba577c6000">llvm::memtag::incrementThreadLong</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a69398364db52b18db9d922fec6d8eb87">llvm::MIRParserImpl::initializeConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#af001e6326d49bf139dfeee21772f01f0">inlineGetBaseAndOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/insertelementconstantexpr/#a8c65350c022707b6495de898c4b7d14b">llvm::InsertElementConstantExpr::InsertElementConstantExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a4cad1dcbccfcc610dc8d47100b4871ef">insertInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#ae621284e39538e26bdef3fa0904db7fe">insertMaskedValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#af6968bc7c8e7e0d6b3fcddb5a934a3c3">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::insertShadowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24da6451c0e494831c85fa96cb572c9a">insertSinCosCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a75cf62ffe10261611bab4d74598ab0e4">insertVector</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a9f4e542bdcac1a2ab15b6e55991f07c8">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::insertWarningFn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aa75e387193fd10b9055d76076288f1ad">instCombineConvertFromSVBool</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a04dad23556e58f793c9a508a1a2d9aa5">llvm::PPCTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a5f64e951a3840e09ae4d21552754ec13">instCombineST1ScatterIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a965b006c5624011322112bb1f1325f8e">instCombineSVECondLast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#afdcb3be103dc32527286d0352eeacdd6">instCombineSVEDupqLane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ae2f9543c1954e97e2887aab7c33e18b4">instCombineSVELast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a9946a89352eee5ab78f0f3fc4fc18941">instCombineSVEPTest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af0b80ad51fe1f4372499e354b6f2e402">llvm::AMDGPU::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af414e22c02fcc9ff3ce2d81ee8d3cfcb">llvm::AMDGPU::instrumentAddressImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a548c5b4779101e84af6a92e2548be083">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAMDGPUAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#ad5393f64ef6c65d1f090169819b68598">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::instrumentAsmArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#ad73240db48b2eda2b2ca2ce38530c552">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentMaskedLoadOrStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#ac6119f1988ee2e260e58defc26361639">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentUnusualSizeOrAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/aggloadstorerewriter/#a784e0c8f27c7cc40d3b741bef27e153d">anonymous{SROA.cpp}::AggLoadStoreRewriter::InstVisitor&lt; AggLoadStoreRewriter, bool &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#acd2031b426c61bce2c9afd0f1463d109">llvm::IntrinsicCostAttributes::IntrinsicCostAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#abad7cbd5f62e879218e11a44a0159628">isAllActivePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a662be1e66a5af621d46fa1c7a8aa1004">llvm::Constant::isAllOnesValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a1f2a3f39b7febd40285065a7ed05b71d">llvm::AA::isAssumedThreadLocalObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a5ee07316c71711c956769e3dd902079e">isAtomicRMWLegalXChgTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a807bb3d2ecc2999993a91d499bd26543">isCmpSameOrSwapped</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#a04a8af897aa17e64fedac0215ae4e705">isCompatibleReplacement</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#a7475e25ff38cec22e5930669aae3069d">llvm::MipsTargetObjectFile::IsConstantInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetobjectfile/#ae8ab637603f274f121322788c5741f89">llvm::LanaiTargetObjectFile::isConstantInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#af826af3bc0b968c8711604291425f7c0">llvm::RISCVELFTargetObjectFile::isConstantInSmallSection</a>, <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#af7b88a2a7449e4edc75721e2ab686d9e">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::isDependenceDistanceOfOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aee0f586f3e5fc07e4c55d3e8caade9a6">llvm::Constant::isElementWiseEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a947eb0bc52dfe966730db285b510b678">llvm::Constant::isFiniteNonZeroFP</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a710fc966df72f9cae9f17ec7eb76f5e8">llvm::SystemZTTIImpl::isFoldableLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a16658fce14f4b2888f76f0972d239139">isFreeConcat</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#acdf2ba7931aca786fe764e4361610d3e">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::isFusionProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7ac21134b2aaca2a7d55f6ff9d92f5b2">isHighCostExpansion</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoalias/#a0a95494aa0152eb057e6e9ca25572f87">llvm::AANoAlias::isImpliedByIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c42afd9259c6322e00383f27bca19b0">llvm::isImpliedCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aeb1b55a34e106493b57164146f40623b">llvm::CastInst::isIntegerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a08188d419e040050ef28ea516afebf98">isIntegerLoopHeaderPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a593afa69fb7cfbb4506f605bd785f923">isIntegerWideningViableForSlice</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a336ed98852175e7e955e9217080bd596">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::isKnowledgeWorthPreserving</a>, <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#a2ced3b7cd6ff2ea19dd70f2f0fb10e2d">llvm::ConstantPtrAuth::isKnownCompatibleWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a373d20116312d859aa88b46b48a8fd8c">isKnownNonEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9afd47568010f063c6ca4ed6473db03">llvm::isKnownNonEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a831a5dec04e512d616fccb6e1f474e79">isLoadInvariantInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f579c2fbf1fda44d35d059d9799eddc">llvm::isMathLibCallNoop</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ab49825b73027cf30c861cfc51c6e821f">llvm::Constant::isMinSignedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aabb53b9354c612fd43fa47b8266114d6">llvm::Constant::isNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a60bcf26670bb451fea6d0924b5cdde53">llvm::Constant::isNegativeZeroValue</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a1438002c91e6e1c7a587a194b268239d">llvm::CastInst::isNoopCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a44232befb736ff8d861bd991a5a68239">isNoopPtrIntCastPair</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a96b2951252cda0fe4fc0cdc9ce3770f9">llvm::Constant::isNormalFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae426459d2c178a60009dd869bb23c4cd">llvm::Constant::isNotMinSignedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aeb641261038c74d4edd4d258d471111a">llvm::Constant::isNotOneValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a586fb7954fcb7d759a997b3e1e979d30">llvm::Constant::isOneValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ae076239dfaf8887811009871f69f4b0e">isOperandOfVmullHighP64</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ade4086b409f00a755cfc6c0b03f67413">isPointerValueDeadOnEntryToFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a9d2e61bef8fbdb714e9f0a739bf49a58">llvm::AArch64TargetLowering::isProfitableToHoist</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a857dba88c2223d0a509b5d390f7144f0">llvm::PPCTargetLowering::isProfitableToHoist</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#adfeafe69289d62b3269dd29ba8e88038">llvm::SITargetLowering::isProfitableToHoist</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#aca87c42e8556b7f2e73454d63efa87f2">isPromotedInstructionLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/sveintrinsicopts-cpp/#ab3363381f198b25f4ce23364c08ea1f0">isPTruePromoted</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a3f1861e30cebca3c33d71a2e73de0c5b">llvm::GCNTTIImpl::isReadRegisterSourceOfDivergence</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aab40deb840751b104926b1052d91e7fc">llvm::CallBase::isReturnNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af029ac9445c750f9a2a2d90c2aeab9e3">isSafeLoadOfSelectToSpeculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a8bb9afd23da56f99f3bcdb52e9c74320">isSafeToSpeculateStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ace7029cdad3163ebfb8172d25e8a59e3">isShuffleEquivalentToSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ae8f4745a87bae0a614d6bda1cc55ab01">isShuffleExtractingFromLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a7d6c29a3f2cf33fdabaadeba33e47d78">llvm::ConstantDataSequential::isString</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a2a0d9aecb6da964944ddf642321b12f7">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::isTrue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a66fb0770ddf5f596079ee32ca4b8b599">isUnsupportedAMDGPUAddrspace</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbits/#abdfa4615d4c528925ba6490398cc54af">llvm::DemandedBits::isUseDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/extractelementinst/#ae9b20825832b7718625e7db28ea29218">llvm::ExtractElementInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/insertelementinst/#a94984d91c7ee37a076fa26d03a131c49">llvm::InsertElementInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a5050f6aa93de9b9e43146d95909839aa">llvm::ShuffleVectorInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a4679b8d3496374b0f0fead1b778f99a2">llvm::ShuffleVectorInst::isValidOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af6735614e085435a0f3bb90aab527213">isVectorPromotionViable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab4c31035e44c7bda618eb2eb81dcf314">isVectorPromotionViableForSlice</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ad97fc23e85a854a19101bf8e861356aa">llvm::Constant::isZeroValue</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantscalar/#gab5d3d570a38c53cd67c5288df7d8fdd5">LLVMConstRealGetDouble</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopidiomrecognize-cpp-/memmoveverifier/#a2f0412aee208de4e6fe854c4c3b50937">anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier::loadAndStoreMayFormMemmove</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a5d31f8dc135425bc0f938f13bcca4a0a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::loadMatrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a88b0909bfe0684c1c286237dd9985ce9">lookThroughCastConst</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a160d793aacc4ffadcdf86eddbf401c69">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::Lower64ShadowExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac306f2130698421f64f8a139faf38675">llvm::lowerAtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac963dddf8453fc717992d3ce36a27d8b">llvm::lowerAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c0cdb3908fc8b0f795f411e32bb806e">llvm::FastISel::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a429785d5b6015aff39a7a998d9e70fa3">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac2b1c517d194a6bdd00f66bce97f52c3">llvm::AsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa3168bc53fc117710cec207cc6f60518">llvm::ARMTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering/#a333bc33c92a4288cf0b3e4514f4cb075">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::lowerIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1b51a567be126f7919bef1c351d859e2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a6d7b7ecce18021429495c1db66a025ee">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a790c96adef17241b1ba4dbf475c3e57e">LowerNegateToMultiply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41052a5d27c665c41207f349f1a45af2">llvm::lowerObjectSizeCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a5e5cf24df0a45159407988a98fe42700">lowerPtrAnnotation</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a30b2570b289c65776a16666bd087c988">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerRawBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a51d9ea5d0487385704b6aa356485b70c">llvm::AMDGPUCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#abfdadd18c92c595797ca5409d708f2ef">llvm::M68kCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a821ed33f62736f960fa90c585205677d">llvm::MipsCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/ppccalllowering/#a0895983a48b4fe2de9c52579431f8744">llvm::PPCCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a2a90be51e47dadfbb04df4f64465ea04">llvm::RISCVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ace03d9ed2825d1401093a441f164ecdf">llvm::X86CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a230768916fc2abaf5fb0f563654d2cc8">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToCreateHandle</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aadb2a52a94fd7cf1e3f1643e0f5e2934">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerTranspose</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a70502c89919d53c74320c78b78d5c282">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerTypedBufferLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a304f0837129322608c9e0384d193a0ba">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::makeIVComparisonInvariant</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaddressspaceimpl/#a53cdd0197a337c06817844761012a6e0">anonymous{AttributorAttributes.cpp}::AAAddressSpaceImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf62ca503c047621e9b9047c548f231f">llvm::matchDecomposedSelectPattern</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopflatten-cpp-/flatteninfo/#ae4b9ef35d5c40d69ae861c215edd3a08">anonymous{LoopFlatten.cpp}::FlattenInfo::matchLinearIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a9e6840885acb4ffa3e94e81a70b392fc">matchOrConcat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvgatherscatterlowering-cpp/#ad33dbce954e66608510537a16aaf130f">matchStridedConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue/#ac96558c87ecbcc96f020a0efcaade750">llvm::gvn::AvailableValue::MaterializeAdjustedValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a2a6b95606a7aa4afbc8a38114dd8da82">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::materializeOneCheck</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a09cbf4fc467ebb29733bdb77d74e7d07">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::materializeStores</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#af60845674c792fb83289ea7695d3807e">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::mayAliasWithArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac46926a2483bd793432d5ca0f7879de3">maybePrintCallAddrSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aa6cdda5199aa68a60388dd66800ec8fd">memChrToCharCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1a5189be752e56bf8343fd72f45720ee">mergeConditionalStoreToAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a6b456d582237b235a7f387d11e56c2bc">llvm::TargetTransformInfoImplBase::minRequiredElementSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/irpromoter/#ad6f05443ad26a04eab6ff0f8c9548ade">anonymous{TypePromotion.cpp}::IRPromoter::Mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a5d0250802fc18f3e96531f43c6280c18">llvm::InstDeleterIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/sinkinstructionstrategy/#a3ca14f887397b546b6b253d3e82ed4ee">llvm::SinkInstructionStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a746205e6d7f5c0bb265ecc8a911d5b82">narrowVectorSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsos16-cpp/#a676538c00f189e19fdec0781ba253e5d">needsFPFromSig</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8b569b7040c15c2e2233b3064caa8f4f">llvm::RandomIRBuilder::newSource</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a9ace593776041510de450a2eccc56eeb">operandWithNewAddressSpaceOrCreatePoison</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ae812aaa917422c3c4b067cda1b1d7019">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::optimizeAMXCastFromPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aef572ae661cf9f5b14651ef952629c10">OptimizeAwayTrappingUsesOfValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ad2bfc3e2f7b1661868517e662ac7496c">optimizeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a5c59325f9c3c1526f4439392c892fd41">optimizeCallInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a996275d837998b396728990f8be0ef3a">OptimizeEmptyGlobalAtExitDtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a8f948dd0c375dfeb4cdf99bc33905e66">optimizeIntegerToVectorInsertions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a9a1ec6b08304c2db10e687517bc4dd2c">optimizeMemCmpConstantSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aee5d0f05688dce3f38e3c495744d49e8">optimizeMemCmpVarSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#add5616535a62c9047ccfbf84bf778663">optimizeNaN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3b82cff474790446f1288f1a086c1cd6">OptimizeNoopCopyExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a13c72931678c2da267fc265c7a2afdfb">optimizeOnceStoredGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a0751e03131065414fffaa087c9e084cb">optimizeSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a75e6b6bf03adf614aaf100a9afdcd612">optimizeVectorResizeWithIntegerBitCasts</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a03dc80eab5eb9f0f1ae05d6c3360d988">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithFDivFast</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#af1f9568f6a2469baf6e85a9dc7b6c588">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithRcp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae87e464933c41dbf0ad62bdf89905831">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithRsq</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiloplowering-cpp/#a5761cea08563e881215f9511be699d06">populateOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1080880d0ca078dceb9d3c8923576ae1">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::preferToKeepConstantsAttached</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a143bc5faeb35f7363570e97bccf76e53">llvm::VPlan::prepareToExecute</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ad57efe4558f8566bb06e708cd818578d">anonymous{AsmWriter.cpp}::AssemblyWriter::printArgument</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#adaaee6d07806670bf06660d4c1e85bc2">processArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aaa116d55b70fa3716c4ee6f0eb3488d8">processCmpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#acfadccba72143e2f818f0a355698ff10">processNonStringArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a25e3db50d3aa8a3fa245e3c2d3197d7a">processOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a580f44370be222c0b2be5a2a7fa3f048">processSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ad47460e620c33c83309f749ea8f34c6b">processSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ace24fe825742577e78df32f725ad7b26">processSIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#aec05cafc12b1852dbd16670773d4f00d">processUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a20728ab5a970c250099d56e721746064">propagateNaN</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopidiomrecognition-cpp-/polynomialmultiplyrecognize/#a2d8e2d584aba003918f1d906f645df9e">anonymous{HexagonLoopIdiomRecognition.cpp}::PolynomialMultiplyRecognize::recognize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae327be8503a76bd4dccfff4713a38553">llvm::OpenMPIRBuilder::registerTargetGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5197ef3eec835595e81bcecb4ee02969">llvm::PHINode::removeIncomingValueIf</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a4082748189dc3460ea7130cd8d7790b5">llvm::MemoryDependenceResults::removeInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a635463dc5e146744799163c2f820e51b">llvm::SCEVExpander::replaceCongruentIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a92e7361f7532de414322df105163781f">replaceDominatedUsesWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a16096e55b9292113f13073fa2343b9c7">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceFloatIVWithIntegerIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#a0e7841803a620fb47c7cd3086debaf54">replaceFoldableUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8543371395854bee27033b8e24836cb0">replaceFrameSizeAndAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a36da270a9d55e053ba96b61f7f09a914">llvm::GlobalVariable::replaceInitializer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22deed11f251c5761b2b4bf021eff4ac">llvm::replaceNonLocalUsesWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a645f6e970e94d7ca51922b3932338f51">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceRemWithNumeratorOrZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a236935b2df66a03a0a54350a6b9b84bc">replaceSwiftErrorOps</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a174c8fd19771468c53842a7fde8ddce1">llvm::Constant::replaceUndefsWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroelide-cpp/#a211159fe60fc76cdea300e3532e60655">replaceWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a14ef30a60513d26f82c93d796deb7494">llvm::Record::resolveReferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70727db13f5962a76e5dd0ffd21ecd07">llvm::returnTypeIsEligibleForTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad75372cc26ff6f641159aed90d5fc11e">reuseTableCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a9910dce4a3e020d503a0e4062d66646f">llvm::GCNTTIImpl::rewriteIntrinsicWithAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxttiimpl/#a2c490533c8b0e3198460793c9d739f5a">llvm::NVPTXTTIImpl::rewriteIntrinsicWithAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a52cff5d33f36f7d74476e993b0118f58">rmwOpMayLowerToLibcall</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestack/#a77d82dc0922a0f94f90fcc7e9e194035">anonymous{SafeStack.cpp}::SafeStack::run</a>, <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loadandstorepromoter/#ac1da68baf80229b2d8af34499eb1c73f">llvm::LoadAndStorePromoter::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memderefprinterpass/#a9643b91d2f4e79487e5b260eb11fef74">llvm::MemDerefPrinterPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a4240fc0963676b19a8cbf8448a599700">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilwriterpass-cpp-/embeddxilpass/#a40185bab20927a719a78e3747d96430d">anonymous{DXILWriterPass.cpp}::EmbedDXILPass::runOnModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8cf671ed90e3e80717aaa6318b24794c">llvm::SelectionDAGBuilder::salvageUnresolvedDbgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1434fc5d1782f15a392af0320f13f6c7">llvm::FastISel::selectExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a629a9b41f0b6dfa91f5b0a7ac34f2d1a">llvm::GlobalAlias::setAliasee</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0107453b6a36d93e5a10d48cdac4d06c">llvm::CallBase::setCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a64ab14972c2bd5c0a01eaf7242dee624">llvm::MemIntrinsicBase&lt; Derived &gt;::setDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a430025e146710444567fa8bd1da2d3a9">setInfoSVEStN</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a095f8f031d99ce3c0b25478713293dea">llvm::GlobalVariable::setInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#a77fca2c3fdf25a035739378ae30ec9d8">llvm::DbgAssignIntrinsic::setKillAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#aaf2539583fcfa83b3ecdfc1fea52cff6">llvm::DbgVariableIntrinsic::setKillLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#aea38159494421174efc48de560b11b61">llvm::SCCPInstVisitor::setLatticeValueForSpecializationArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a3e472e6fd83abb77745a59bccd367688">llvm::MemIntrinsicBase&lt; Derived &gt;::setLength</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ae548511913b150465cebb7956571da83">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::setOrigin</a>, <a href="/web-llvm/docs/api/classes/llvm/memsetbase/#a5145ecc9510133b8db74dfa22bbf5d3d">llvm::MemSetBase&lt; BaseCL &gt;::setValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a25af03cf36c07d235f487e525e5dcd07">llvm::AAMDNodes::shiftTBAAStruct</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/compatiblesets/#a4ef2eab86cf6fefd01ef4607cc834432">anonymous{SimplifyCFG.cpp}::CompatibleSets::shouldBelongToSameSet</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeece7dddae8cb49c379f7cd11a847217">llvm::TargetLoweringBase::shouldCastAtomicLoadInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a93fa81ce3759c975472e23d85d14bec1">llvm::TargetLoweringBase::shouldCastAtomicRMWIInIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#af6a1350b26889cb5eebc75372ab4d3f5">shouldConvertImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a70a83c8d008bb40c08c02d3238a992a3">llvm::AArch64TargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ac4b5d6d1333be49386e35e56c28647fe">llvm::ARMTargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a2f3b0d090892cc5dd71222862723e231">llvm::LoongArchTargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#acf15eefe45c9e2c4a90a40a7a9a779f3">llvm::PPCTargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a9f599da93ccc12e05a0126cfdc57b885">llvm::RISCVTargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9e745a45e9d5aa38916ad1fabf333403">llvm::SITargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a62ca2fe454c98ca30dd17d0b37ba3534">llvm::AArch64TargetLowering::shouldExpandAtomicLoadInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0a17ad44231dd559dedb8ff61bcfe29e">llvm::ARMTargetLowering::shouldExpandAtomicLoadInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a4623112d6a3de641f2af75604341bc64">llvm::HexagonTargetLowering::shouldExpandAtomicLoadInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a7c188b2e9f8e7ab4da2a49c83acd299c">llvm::AArch64TargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6ed1fafeaecc08fe13e54b080e259dd2">llvm::ARMTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a5916c5a40e28fd6b62ec267bfe57e43d">llvm::LoongArchTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ac4cecb5dac1dff98c076e4ab11e37f93">llvm::NVPTXTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5047a95accb91898b9135182491d547c">llvm::PPCTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7a07b54d60a81306d5f8c4f12fe8d0cb">llvm::RISCVTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a29137845e271a0520a8f1c3c397faf50">llvm::SparcTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a8f438755ea4e823390b7d3eef773bbd8">llvm::SystemZTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/threadsanitizer-cpp/#a0bb37c4d9d72e23c0da8cafdb59f466a">shouldInstrumentReadWriteFromAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a355c480e36ee4fa1a1a9135427005331">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::shrinkDivRem64</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a77aac577d89abc9411adfdf918d7d539">shrinkInsertElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a40c4c6660c6d108c0202fd73c28f2834">shrinkSplatShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorconstantexpr/#a9a1de10288271bcf0f869d8121f8525a">llvm::ShuffleVectorConstantExpr::ShuffleVectorConstantExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a808bb58d9e36f7e9c27b5606d6a9e7d0">llvm::LoongArchTargetLowering::signExtendConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a822fcc93f796cf246c48b13ef6ff05cd">llvm::RISCVTargetLowering::signExtendConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3a8f0d83fd0c16251206c0d0f3e78174">simplifyAddInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab2354d93dbb7ffbde58e687309f44fad">simplifyAMDGCNImageIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3eefa98bc7f6c24b6f1fa0bb220a77a4">simplifyAndCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a496b149294586554f0cd9fd240d8d80d">simplifyAndOfICmpsWithAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#acb8e54b9f6be2fdb87b369c2218db1cc">simplifyAndOrOfFCmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae5781faa80a27cf51fa316feaa2ad363">simplifyAndOrOfICmpsWithConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a557f3c41bf651bbd713f9220c59f0b1a">llvm::InstCombinerImpl::SimplifyAnyMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a29b4afe26752d50b7207bf4cd3f984f3">simplifyAShrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a41c00c458f7416c93927bc2f332b3898">simplifyAssocCastAssoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a6343e645572ce8783bbf5853d181479f">simplifyByDomEq</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab133fcc8ac42264ff3425cea7b6642bc">llvm::InstCombinerImpl::SimplifyDemandedInstructionBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a1747fa66edae41ea9492c338ef853e12">llvm::GCNTTIImpl::simplifyDemandedLaneMaskArg</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a558144ce515858cbab3df5c7005a5a50">llvm::InstCombinerImpl::simplifyDivRemOfSelectWithZeroOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a48ebda753879b3d5d55fa0e1566b5439">simplifyExtractElementInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a68091149082c7a34c2198012a0800d6d">simplifyFAddInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7ae2d2701ffe4abf529cd4fb1ca26049">simplifyFDivInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5b47854a993004418cb56068fe2dd9dd">simplifyFMAFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a95596f2a72e57df0c710e3dc7b225597">simplifyFRemInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a9a357829c347a3ab1d10dced5dbeb27a">simplifyFSubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abdf4b5f9e1dc6887cac393ee643c10b6">llvm::simplifyInsertElementInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac2e1b2bf5707da420c5d0578a227e34c">simplifyInsertValueInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a9a4e22418fd040f349bdecefdc303c2e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::simplifyIVRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ab6fe80e6f4b357ca0fdc9eafa69c430f">simplifyLdexp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99fa28f2d78ae2ce889b621ab275a4ad">llvm::simplifyLoadInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ab8c09431e3ba6ccd88dfa4a32c2127be">simplifyLogicOfAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7b473dc0c6603bb29f38c46858df840e">simplifyOrOfICmpsWithAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a868bc52af4d6fe7f56fb460175735a98">simplifyReductionOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a9364799319bac519aa565ec882986e6d">simplifyRelocatesOffABase</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aed163588354401b6679a39acad6fae2a">simplifyRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5bb5f4b5b2420a7f3950939b2de01330">simplifyRightShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a630c735bfbff439b152d83f92302cb34">simplifySDivInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a8e2f5715194e637f638fcd6e0851448b">simplifyShlInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0bf04415ab72b83b24140635c6a7ea52">simplifyShuffleVectorInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#add0275e00f4260c742c6cf3ec24b1987">simplifySRemInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#adc11c5fbec9bf293b000637357da66e4">simplifySwitchOfPowersOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4355ad633eda8e7c8a6538ea41bb34f3">simplifyUnsignedRangeCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a1ba99155749ea6a41858f9bc4449f543">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::simplifyUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a1ecff7a038229dccedd3fb1aba929059">simplifyX86addcarry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a8f3b97594fe4e833960ffddc2a778a53">simplifyX86movmsk</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#abf44819ee45fe0465818d5244da90f68">simplifyX86pmadd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a7db2eee6dd2ea98d0ec3c05950be2915">simplifyX86pmulh</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a9cfeea050198084d67109f0260e33970">simplifyXorInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ace8766b97ac54db2bec8c29e4016f3f6">speculateSelectInstLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae68caba8680314219b2f2a7c2d91ecee">llvm::SplitBlockAndInsertForEachLane</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32aaa22eb69c944393cd5a1c79fa0d35">llvm::SplitBlockAndInsertSimpleForLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3c7e1486d1d466b3be981adcb21a6359">splitMergedValStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a40bdb7ed86f1fdb139eb9fd73b05405a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::splitVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#acf395765fdd0db82a9d8c6a89174a83b">llvm::StoreInst::StoreInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a0830273a57e2290e00f3ea50b6e082e4">anonymous{DeadStoreElimination.cpp}::DSEState::storeIsNoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ac9fae87b41835eff9f16de8aa6b11239">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::storeMatrix</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a00c704ed1965bd5d0348f156a8e33506">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::storeOrigin</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a0fd3732392fdbdbc5a4436c0f1262999">anonymous{InlineCost.cpp}::CallAnalyzer::stripAndComputeInBoundsConstantOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/stripgcrelocates-cpp/#a5d9143fec81c7c1bea9330ccc664f45c">stripGCRelocates</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3fb33a8a29e076405285e5282eba81fd">swapICmpOperandsToExposeCSEOpportunities</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4515378302b14f9df5b64311e4c84a80">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a52e0d03acf3c67fcf1c68887dca291a7">tagGlobalDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4af4fe6392d3860167eafedc817ed8b1">llvm::Constant::toConstantRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5ca29e57ad15a06f70b6676ec2665f34">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::transformAMXCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a44ca78ca7013578c50cdd38647811346">transformGlobalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#abce78109fa7acac1ae7aa1b4ee1ce07f">transformToIndexedCompare</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#afa9d4327193a1cc24ab70233ec67af82">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddState</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a42a2b649b3ebe7e9cf882d260685c9d0">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddStateFromCallee</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a58e687cb25ed94c378fc444895422a13">trimTrailingZerosInVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a821be8169bc31b8413a69cd7f22ff9ab">anonymous{SimplifyIndVar.cpp}::WidenIV::truncateIVUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a19caca7bafe1b8a5f67802ce62431282">tryInsertCastToCommonAddrSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a760fb390c24b907500c0a181fada9590">llvm::VPRecipeBuilder::tryToCreateWidenRecipe</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a5ac801ed9e1a056f66831b7f0129fdb0">tryToMergePartialOverlappingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a97cbd12fcf61e3cf7db640c3661e66df">tryToShorten</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a8528dea79f0940669c4fcb751940ca94">tryUnmergingGEPsAcrossIndirectBr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b081ab710b9eb7fcb8dff225d41cf1f">tryWidenGlobalArrayAndDests</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad96e48f13961854d2242e9462a920394">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a448318fedd7b77f12f1163c8d5a5b10a">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a49a422e75fb519fc9419967ae2c3679b">upgradeAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a90bcc9afc1cc990c8790a5424a93c926">upgradeARMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad9d7a82ba140ac920458705124372cd6">upgradeAVX512MaskToSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#acd3fbecf680813e839ac85bf3b3a81f2">upgradeMaskedCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aa4e6667108e3ef2a76f536bd8f5e93e6">upgradeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a2bb059c3ec33f54ef3e4566ad1fde6c0">upgradeMaskToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad37834e4f8e16e808997aef286954fd0">upgradeNVVMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ae2068f406068749ea0cca3bacd6815a0">upgradePMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4958a5a521b8764e5daf029c5c306db2">upgradeX86ALIGNIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad194379f5156fa6a9ec196923d80df3a">upgradeX86BinaryIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#abbe50b1b6428dd6884355b64360f2f29">upgradeX86ConcatShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a2e38c407c9078c144f8aa68eef3ac0ac">upgradeX86Rotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a252d7fc6161c61ec238f1ee24e8279b3">upgradeX86vpcom</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a02b56bd888812aead982e69819ce8452">upgradeX86VPERMT2Intrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a8535b262a19144f9ff988b6bd8c19f42">valueEscapes</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a02e1c458e5c141b448867b728af11ae9">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::VariableShadowExtend</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a86163cb169435641156cbc611072c931">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vbytes</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84163d559062da6b736ab943644e0a16">llvm::versionCallSite</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#a1cbe5f9d545c0382e3994c1685c0aa85">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#aeedae9a864c19d88fef2a138e8573a44">llvm::ObjectSizeOffsetEvaluator::visitAllocaInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#af4ed8c796cc564c14664505603f6aac1">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvcodegenprepare-cpp-/riscvcodegenprepare/#a6cde9aa5130a6fb02753799ff1cc6c93">anonymous{RISCVCodeGenPrepare.cpp}::RISCVCodeGenPrepare::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#abf86ae2ede168d53dec70f0b0cb9d9b5">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#af2a279d40332c538cc1a05dc6b7981e8">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d5d32552609554018891c30a532f1d6">llvm::InstCombinerImpl::visitAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargamd64helper/#acc81d19554e4eb245d659a89a2fd6f37">anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargsystemzhelper/#af0bc023f29f779469e5e8e3f92b9db0f">anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a16eb5732b0dacdde9b666ba69f630a16">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a679f36556ace611ccc56580cb497973a">llvm::InstCombinerImpl::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a555a1a7ce9538b817e65c911ed7da13a">llvm::Interpreter::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa72f4f7fc2ee2bf6cd3b64bd07c37e8">llvm::InstCombinerImpl::visitFSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#ac6bed7ccafa0ac0022efe4b392497224">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#aaa39273101436002f3e3bd16293327be">anonymous{MergeICmps.cpp}::visitICmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a21c7503f18216d727a9798c0643f3bf8">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a900ef0957c31205735317d246eb68f7c">anonymous{MergeICmps.cpp}::visitICmpLoadOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a013a34181c208fa05a664e3f27bbad95">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a47c795f3e83fbfbd37c1b890c850dbe7">llvm::Interpreter::visitInsertValueInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a232a0fe878bb0a5a47219195daadca39">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a28d5aaadc2b319f9ac050aa712e49a76">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitIntrinsicInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9567d315d63f844326900f461f5b3d7a">llvm::InstCombinerImpl::visitIntToPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a180c318fe2fe1f2f7d4f4ca4dccfd2f1">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitIntToPtrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a57aff0646c7151c4158d839c386332cc">visitIVCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a6710af6aa118958e7ce91327582b3a98">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/storefatptrsasintsvisitor/#a77976478ff4af840d8dc298cd7bb1b65">anonymous{AMDGPULowerBufferFatPointers.cpp}::StoreFatPtrsAsIntsVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ab1f923b66b5437b4912f28e87b6076ff">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a9498339e26b296572a463a1300bf1a13">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aa9a049f0da67dd58d8854ac1de525ac7">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a684df7f760d6dcbfea36c5bccb2cfccd">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5b6ac7240be29b8a3a611a734a45d4a6">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitPtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8b0688ee292d40a24ba7117b39d426bd">llvm::InstCombinerImpl::visitReturnInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a22ba91d5d49420a24b01342672953762">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5c5efa376b5dcc0c0b0628d89882a498">llvm::InstCombinerImpl::visitSIToFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a4bbb23dd030b9c2a968b02a090e4c2cf">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitStoreInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a8f85dad5b58e981324eab559a5be4e87">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitStoreInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#abd36596e248efce1fca0f543c3ea6aa1">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitStoreInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8042dd4cb7e9772368f2808b8db577be">llvm::InstCombinerImpl::visitStoreInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a09b9488bfc0aa55fe37ace2bb46745d5">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vlsb</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#aeb3015db092e8e97f7a585096688b6cf">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vresize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b81e19b3ddf7ec786c5105ba5470153">widenGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue/#a5ed4aebc49d7a699dc40a248391f0ac1">anonymous{BasicAliasAnalysis.cpp}::CastedValue::withSExtOfValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue/#a096cb21b10c3d48f35a912947974c872">anonymous{BasicAliasAnalysis.cpp}::CastedValue::withZExtOfValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ac7a7c36cb1f1a299406e3cfa95b7404e">anonymous{AsmWriter.cpp}::AssemblyWriter::writeOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#adc27aa83649282c846c35b22413ebf83">anonymous{AsmWriter.cpp}::AssemblyWriter::writeParamOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#aa8f5b66c1e3e1c2f0740764818920442">llvm::MetadataAsValue::~MetadataAsValue</a>.</p>

</div>
</div>

### getUniqueUndroppableUser() {#a93270009c3358fba0a61654a9376ab4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User * Value::getUniqueUndroppableUser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there is exactly one unique user of this value that cannot be dropped (that user can have multiple uses of this value).</p>

<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="#a28ed67ff84559f2ca8a0b5975d03cbce">getUniqueUndroppableUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### getUniqueUndroppableUser() {#a28ed67ff84559f2ca8a0b5975d03cbce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const User * llvm::Value::getUniqueUndroppableUser ()</td>
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



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a93270009c3358fba0a61654a9376ab4c">getUniqueUndroppableUser</a> and <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### getValueID() {#a4a6ca5a5b87bd84231be9d8dbec46c1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Value::getValueID ()</td>
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

<p>Return an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the concrete type of this object.</p>


<p>This is used to implement the classof checks. This should not be used for any other purpose, as the values may change as LLVM evolves. Also, note that for instructions, the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>'s opcode is added to InstructionVal. So this means three things:</p>


## there is no value with code InstructionVal (no opcode==0) {#autotoc_md33}


## there are more possible values for the value type than in ValueTy enum {#autotoc_md34}


## the InstructionVal enumerator must be the highest valued enumerator in {#autotoc_md35}


<p>the <a href="#af6d11b38374c4f9e6ba3a6407da2dee0">ValueTy</a> enum.</p>


<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydef/#a1512fb44e40487a77bef4a380a29be4f">llvm::MemoryDef::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuse/#ab34bf1259982ce0099caa3d8c85394ed">llvm::MemoryUse::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#adc7764ac2159a586017d69783b7a3ddc">llvm::MemoryUseOrDef::classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0e0ddbf81c5fa1ee764ba3f4bd6ddbf5">CompareValueComplexity</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae1a4c619a44ea59a2cdeeb85060f385d">llvm::Constant::destroyConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-5ea3482d08fbaa55649ae656680cc713/#aa547d248f12fe80ad1151538a12f7a3d">llvm::isa_impl&lt; Argument, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-3992237c0e44660d67d71664fbc3357d/#a0fa4fd108e41b40df6d3c8152a7b8f48">llvm::isa_impl&lt; BasicBlock, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-6d7e13f93b8701ce5a1940d41fa02b22/#ae6e3fb6804174101033a5cd179101780">llvm::isa_impl&lt; Constant, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-ffd4953fdb0844925984eace09500fe2/#a2208f4e77a7b103a215f9936f0fb806c">llvm::isa_impl&lt; ConstantAggregate, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-b54cab365e9e3417f7327c07a2ba0914/#a757c1d04cb75a3750b1c121049ea6b77">llvm::isa_impl&lt; ConstantData, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-ec547d9edb1427be943da2389210ca63/#a4b98b530d0333e39fa119c18e5b34401">llvm::isa_impl&lt; Function, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-e3bb99a89ebf6430ce3d1823b59da3b6/#abec1415f535f0bb4a08e2ee1c1559ffd">llvm::isa_impl&lt; GlobalAlias, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-3b34e6830df11a6812dedd830cefdd8f/#a3aa511dadf0c3957e7b75d31b9255005">llvm::isa_impl&lt; GlobalIFunc, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-ed62cbbe90ed2d012d11c7948dc24e6d/#a892343ab24cda5239371ddf5b298d658">llvm::isa_impl&lt; GlobalVariable, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-fa726687026a340db5b8acecc2c5bb88/#a6f99f49b2dcef36f7b31c8ed64145307">llvm::isa_impl&lt; InlineAsm, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-0fc75815d59c0c8ccca259fd632c6d2e/#a16b7dab711f014635a047d74777c727b">llvm::isa_impl&lt; Instruction, Value &gt;::doit</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a7c733400ba8d113fd2976d4fea0db981">llvm::GlobalValue::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#afb784171b976ddd992e3f27ac36a894d">llvm::Constant::handleOperandChange</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#aadff5eaae30623b4077b9dec90f29dcf">llvm::MemoryAccess::print</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae52ff267989fb6aca697d29dea0cb027">llvm::GlobalValue::removeFromParent</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a472652f9e89e006426f371fcbfa6f619">llvm::GlobalValue::setThreadLocalMode</a>.</p>

</div>
</div>

### getValueName() {#a99f268730c076a9546009ede05e0dc41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueName * Value::getValueName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### hasName() {#ad9d88ae321b98d8a3b7f394977ae6d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::hasName ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a174c05075799a1b8213851ca52e9567c">HasName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-materializationutils-cpp-/rematgraph/#a336028d6f8b409a071169b09e0b5e666">anonymous{MaterializationUtils.cpp}::RematGraph::dumpBasicBlockLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3fa67a76e6081ca187d962c197c6445d">llvm::dumpBasicBlockLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a78e5ec9027384598a0ce9fb4eb3cea72">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9180a7817130d1cac7cec7feec3bf6e6">llvm::emitLinkerFlagsForUsedCOFF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#ab04f963f804d27e1b7d7c9b9cfcacb9e">externalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a6d232c3c6e60c94891fffed1f9277e8a">llvm::anonymous{AMDGPUSplitModule.cpp}::externalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp/#a01f706e23190c71e799d87c5eef792e6">extractSubModule</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#adb6d1f8091dc25c1713b6cbfe642d88b">llvm::ModuleSummaryIndex::getGlobalValueSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a3b63142ca24145028afa3a5bdf3fe7fb">llvm::ExecutionEngine::getMangledName</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a2ddf5387f9cd603891e1933c2f84cf65">llvm::TargetLoweringObjectFileXCOFF::getSectionForExternalReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#a608a1965369c58e389152dd9485df72d">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashGlobalValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#acc28d73804bc12a7a70c2e323ccb45fd">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::isLookupTableConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/structs/false/gepnode/#a8702875a47c894f09fb5b7f502b0b1f4">false::GepNode::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8d20a7c0aa0ef76c738e2ca9e21d35d5">OptimizeGlobalVars</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ad75b48c94bacfc6a1d166164bd51af8b">llvm::MemoryPhi::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ad57efe4558f8566bb06e708cd818578d">anonymous{AsmWriter.cpp}::AssemblyWriter::printArgument</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a6f875a89b00cf04b3d413c954e9fe915">anonymous{AsmWriter.cpp}::AssemblyWriter::printBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a732a1e33a5b12385ee96d35735356c0e">printBBName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a39e0c396e9ae881eddc29a02ebc40956">printIRBlockReference</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>.</p>

</div>
</div>

### hasNUndroppableUses() {#af2480ba07d44a392d73449bd7269bcc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Value::hasNUndroppableUses (unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there this value.</p>


<p>This is specialized because it is a common request and does not require traversing the whole use list.</p>


<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### hasNUndroppableUsesOrMore() {#a2b32d493aada47e4eff2cd28f0753be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Value::hasNUndroppableUsesOrMore (unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this value has N uses or more.</p>


<p>This is logically equivalent to <a href="#aba0055050d741f60b6e0523507a2c79f">getNumUses()</a> &gt;= N.</p>


<p>Declaration at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### hasNUses() {#a7c779ce2ba55bc94f52014fc25f3d520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Value::hasNUses (unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> has exactly N uses.</p>

<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a2280e030e66011e1715514cd6965be59">canonicalizeAbs</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5586ec5eac8a93b87b095f949ea8daf3">anonymous{SimplifyIndVar.cpp}::WidenIV::createWideIV</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a133fc35b714b7fc4b5a0935c811ed37a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::emitSIMDTiling</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a6415fb68bc55f3a316aa414a5c2c0ab2">llvm::RecurrenceDescriptor::getReductionOpChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#ae3341aa2a4a16c49b2be04002018a1a6">getVectorDeinterleaveFactor</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a0deafca5c66f3b900139bcf024085e8f">isSSATMinMaxPattern</a>.</p>

</div>
</div>

### hasNUsesOrMore() {#a72fb137716cff838d389e392b9729dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Value::hasNUsesOrMore (unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this value has N uses or more.</p>


<p>This is logically equivalent to <a href="#aba0055050d741f60b6e0523507a2c79f">getNumUses()</a> &gt;= N.</p>


<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### hasOneUse() {#a3a402430a1bbe70a9282dcb0e0b6a2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::hasOneUse ()</td>
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

<p>Return true if there is exactly one use of this value.</p>


<p>This is specialized because it is a common request and does not require traversing the whole use list.</p>


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a88027543aef5a9bc0d82bc5e5e3506c3">llvm::hasSingleElement</a> and <a href="#abf855b7cd63a0cd7f73759e396f280c9">uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abe6927d96b3815417479246b5afc732e">areTwoInsertFromSameBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a65c587ebfe84f7c55b3d2266ff0500f9">canonicalizeSaturatedSubtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ab23c37279d90814b87d6c8ab25b43d0b">emitGlobalConstantImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a00e3a88ec91a20ce25260bfe2ff33bcc">factorizeFAddFSub</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3c995d3af67d9f0024160f8480989563">findBuildAggregate_rec</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae17b24216f27d8266c87b9fa9a70f533">llvm::SelectionDAGBuilder::FindMergedConditions</a>, <a href="/web-llvm/docs/api/groups/arcutilities/#gaf231df4dd6fb738c1f548aedb34ca81e">FindSingleUseIdentifiedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#afce22397c3eff1d8c0dc8e3d8c464829">foldAndOrOfICmpsWithConstEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a385c1da88456d434ee18caa8f48018c2">foldAndToXor</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a36b7410be1f86b52970bb1381904e282">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad600d9077d7e1eadff1334ee14f7f25a">llvm::foldBranchToCommonDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a8362ad1cd10ec969ca55715f7fe5cfb0">foldClampRangeOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ab01a210491dcbefc8db253f4dbaa6497">foldComplexAndOrPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac1582713ab3ea01b71ad1cd559fbf4af">foldCtpopPow2Test</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afbfe964338488078570fe14e7deb0551">llvm::InstCombinerImpl::foldICmpBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab82eb0514d646d43f777a8b0cc83fdec">llvm::InstCombinerImpl::foldICmpInstWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#afb20557855b41f2b32ebd166b4d4b10f">foldICmpOrXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a06131a96d98381fd2b73c4ef401d416c">llvm::InstCombinerImpl::foldICmpSRemConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a39e315cb89b7144083895c083cc958e0">llvm::InstCombinerImpl::foldICmpSubConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7c9fd9f2dba79c2289639f72457fcea1">llvm::InstCombinerImpl::foldICmpUsingBoolRange</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a04d40b2885dcf7e80feed09ba6209e54">llvm::InstCombinerImpl::foldICmpWithZextOrSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a42c33c78c903c369b359db824b70cb1b">foldIdentityExtractShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ae87408bcb6b98e4aa9282af08508ffbe">foldIDivShl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ad3259dc4dae742caac6c6e4f577d1760">foldInsSequenceIntoSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a9fc15c7f338806b191bd2977f4be2513">foldIntrinsicUsingDistributiveLaws</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a8b324b9fcea4493d60035273d9b8e085">foldNoWrapAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a26257c73e483eab4b0e15d53340de986">foldOrToXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad51f65187d4c6b69d6bf8f71e027e4de">foldSelectICmpAndBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a45188914d3b4b24a4a4d7898750b893f">foldSubOfMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a24dce8fa354f0f1d52209e805f0ae6a3">foldUnsignedUnderflowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aee3e98b16f1c8d8d8b30b9a459a6a602">foldVecTruncToExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a3b3df3036740dfcdeb37c3ad977b039a">foldXorToXor</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotionhelper/#a6df9b95e8bacacbad0035f25c46d2581">anonymous{CodeGenPrepare.cpp}::TypePromotionHelper::getAction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aae70ddddbfd05ed5831918fa1836b947">llvm::AArch64TTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a949d5831f77e0c9dc7d3509911cf92f2">llvm::ARMTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae8b00d72cfbbf3ef02315ae6a0ecc418">llvm::GCNTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae83866ca1a903e74fd6b66c1fec0d528">llvm::ARMTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#acee4a569a0d284e1397899937aad7836">llvm::HexagonTTIImpl::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a9407ebeb07769b15977760b26beb7db6">llvm::ARMTTIImpl::getIntImmCostInst</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a97ebd00c769b1d7c67f7db4b58137c93">llvm::SystemZTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a37275b44ee2af4598d1782f93d9204f3">hasNonFlagsUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37275b44ee2af4598d1782f93d9204f3">hasNonFlagsUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#afa93649aba5a7b6388adff903a4a6085">hasUseOtherThanLLVMUsed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a697cde840957bbc0b2848a593c3e0d5a">hoistMulAddAssociation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70cdc32fcfc8ba3feaf026f4959e2c2a">llvm::InvertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a89705a5029e6850fc3d6445ebc775c15">llvm::RecurrenceDescriptor::isConditionalRdxPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ae61f1ffec3d05496e5372922373338c2">llvm::AArch64TTIImpl::isExtPartOfAvgExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3bd0d872bcf9d623a8c432e3369cb0ec">isF128MovedToParts</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a797a268a4ac8802907a1b36ee57166e2">llvm::RecurrenceDescriptor::isFindLastIVPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a405ff61e8571b58fecaa716540af108f">isFirstInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a710fc966df72f9cae9f17ec7eb76f5e8">llvm::SystemZTTIImpl::isFoldableLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a2db21ddc2a6983ec696cd972ad43031e">isFPSatMinMaxPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a26c84133695829e63f3a69adaddbe6b4">isI128MovedToParts</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a670aa0012e26bf3d40dfa5068743ac48">llvm::X86::mayFoldIntoStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#acb762c0dfb2a90596163f59e2dfbd029">narrowInsElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a19d2abc5a580be68aa7751c0e1ce7263">ShouldBreakUpSubtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53e9a46c5489f12eb459b3ecce3db181">shouldExpandCmpArithRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6ad23b58059ffd91df6a2dddf30c5d71">llvm::X86TargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddcombine/#a47fa84ad65315d095fa4153566cbd0b6">anonymous{InstCombineAddSub.cpp}::FAddCombine::simplify</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa9bbead3db102aa9d3eaeb47e695db1a">llvm::InstCombinerImpl::SimplifyAddWithRemainder</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab18666f9305cc63df7009c9e4ec0e35a">llvm::InstCombinerImpl::simplifyBinOpSplats</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7e500d9f027b07d62374f0cee5d56724">llvm::InstCombinerImpl::SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a558144ce515858cbab3df5c7005a5a50">llvm::InstCombinerImpl::simplifyDivRemOfSelectWithZeroOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5a81ca548cc88df15a58aed766bdd890">llvm::FastISel::tryToFoldLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#aa0555f067de530264e995e433ebb7e42">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5457b45fe74cf2f411f5824d32fd389d">llvm::InstCombinerImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a629e02c312173d0da1b62288bc8fbd48">llvm::InstCombinerImpl::visitFree</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#aaa39273101436002f3e3bd16293327be">anonymous{MergeICmps.cpp}::visitICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### hasOneUser() {#a2e987c6af902aad6baa39bd5b7ef322c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Value::hasOneUser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there is exactly one user of this value.</p>


<p>Note that this is not the same as "has one use". If a value has one use, then there certainly is a single user. But if value has several uses, it is possible that all uses are in a single user, or not.</p>


<p>This check is potentially costly, since it requires traversing, in the worst case, the whole use list of a value.</p>


<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0581d6d5dc280ba2a39087a557050a6a">isNotUsedOrFoldableInLoop</a>.</p>

</div>
</div>

### hasSameSubclassOptionalData() {#aa48638782e724669238a05c0859b35e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::hasSameSubclassOptionalData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the optional flags for equality.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a21e38886795ed32ec28d4eb5dc92b6a4">SubclassOptionalData</a> and <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### hasValueHandle() {#ab978072498608d7bd344804926c2a91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::hasValueHandle ()</td>
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

<p>Return true if there is a value handle associated with this value.</p>

<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#abcf78af37d56a9b72a49c65428210758">llvm::MemorySSAUpdater::removeMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a60fac14032181eef9fe2f3e790ce9c28">llvm::SSAUpdaterBulk::RewriteAllUses</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a>.</p>

</div>
</div>

### isSwiftError() {#a98897a3d01f6a4d7f10a5ac8fe862c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Value::isSwiftError ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this value is a swifterror value.</p>


<p>swifterror values can be either a function argument or an alloca with a swifterror attribute.</p>


<p>Declaration at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/typesanitizer-cpp/#a8fe9c2e5d8a275393677c1c46c5f0596">collectMemAccessInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a> and <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#a7c0e62d20df8bb7c81815f187e1df1eb">llvm::SwiftErrorValueTracking::preassignVRegs</a>.</p>

</div>
</div>

### isUsedByMetadata() {#a6cfd8c0f6033a51197c2ef2b00beeca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::isUsedByMetadata ()</td>
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

<p>Return true if there is metadata referencing this value.</p>

<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a0e7ed12d09bbe90b2061208177e2a3ba">IsUsedByMD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a>.</p>

</div>
</div>

### isUsedInBasicBlock() {#a55bba6bcd9b098e1c227011e6cd66300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Value::isUsedInBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this value is used in the specified basic block.</p>

<p>Declaration at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### materialized\_use\_begin() {#a7ad234db7c28b66de3845bb86249cac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_iterator llvm::Value::materialized_use_begin ()</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="#a1e05a5aed47fc02cbb7f252d489b405c">materialized_uses</a>, <a href="#a8a8eddca4c6b9167400f54beb8786343">materialized_uses</a>, <a href="#a413abcab8dbc3900fc2fde96a5d8fca6">use_begin</a>, <a href="#a24018b06ac0d956553428c86d5af7d5e">use_begin</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a>.</p>

</div>
</div>

### materialized\_use\_begin() {#a07a316b721bb6a1794140cd580f5b031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_use_iterator llvm::Value::materialized_use_begin ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### materialized\_use\_empty() {#a60a98b54fc834c577a61e455e7157b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::materialized_use_empty ()</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a>.</p>

</div>
</div>

### materialized\_user\_begin() {#acf1d82a256748288e01404b1903f762b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">user_iterator llvm::Value::materialized_user_begin ()</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="#a0104cde53b84260b50b2557f1f718d96">materialized_users</a>, <a href="#a24d8aaa6a925b40c09fdbf6d7ab332fd">materialized_users</a>, <a href="#a46db903db2484e1ef5062d094d6b0854">user_back</a>, <a href="#a59d3fe5f30609b50112d91f41d268567">user_back</a>, <a href="#a158da2b6d3d938aaa15b6acd00150e2c">user_begin</a> and <a href="#affbc364be263e23ef9f54686c947ca6c">user_begin</a>.</p>

</div>
</div>

### materialized\_user\_begin() {#ae5f5400d4e88bcef211808e582a0be27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_user_iterator llvm::Value::materialized_user_begin ()</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### materialized\_users() {#a0104cde53b84260b50b2557f1f718d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; user_iterator &gt; llvm::Value::materialized_users ()</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#acf1d82a256748288e01404b1903f762b">materialized_user_begin</a> and <a href="#aa22118b2b3f206bfda2ffab4cda94d64">user_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp/#a4c51a380543c40939531dc2875b2cf4f">forEachUser</a>, <a href="#a411cf3e3932f209ce3374cb31adc1da6">users</a> and <a href="#a47e5062f8da90137678150d09bb17751">users</a>.</p>

</div>
</div>

### materialized\_users() {#a24d8aaa6a925b40c09fdbf6d7ab332fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_user_iterator &gt; llvm::Value::materialized_users ()</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#acf1d82a256748288e01404b1903f762b">materialized_user_begin</a> and <a href="#aa22118b2b3f206bfda2ffab4cda94d64">user_end</a>.</p>

</div>
</div>

### materialized\_uses() {#a1e05a5aed47fc02cbb7f252d489b405c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_iterator &gt; llvm::Value::materialized_uses ()</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a7ad234db7c28b66de3845bb86249cac2">materialized_use_begin</a> and <a href="#ad86469939d2a8bdd4169be9403b89f5a">use_end</a>.</p>


<p>Referenced by <a href="#abf855b7cd63a0cd7f73759e396f280c9">uses</a> and <a href="#a224d0ab04e6510402fb5c7221666efed">uses</a>.</p>

</div>
</div>

### materialized\_uses() {#a8a8eddca4c6b9167400f54beb8786343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_use_iterator &gt; llvm::Value::materialized_uses ()</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a7ad234db7c28b66de3845bb86249cac2">materialized_use_begin</a> and <a href="#ad86469939d2a8bdd4169be9403b89f5a">use_end</a>.</p>

</div>
</div>

### mutateType() {#ac0f09c2c9951158f9eecfaf7068d7b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Value::mutateType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Mutate the type of this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to be of the specified type.</p>


<p>Note that this is an extremely dangerous operation which can create completely invalid IR very easily. It is strongly recommended that you recreate IR objects with the right types instead of mutating them in place.</p>


<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbase/#aba272b7337f4e135f28eeb0bcc69adbb">llvm::CallBase::mutateFunctionType</a>.</p>

</div>
</div>

### replaceAllUsesWith() {#a3ab5fc45117b450e8bb04e564cb6e5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::replaceAllUsesWith (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change all uses of this to point to a new <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>Go through the uses list for this definition and make each use point to "V" instead of "this". After this completes, 'this's use list is guaranteed to be empty.</p>


<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a420bedce165a865417db21cdc88307cb">BreakUpSubtract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a064517d4fd6ce0d70f560e1ae3cdb4a6">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::combineLoadCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a20fc81c83f56078eb06e2db21611f58f">combineLoadToOperationType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a5ccdf0465e957f46ac1241b63af00864">ConvertShiftToMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxlowerargs-cpp-/#aafd9b42c5de69fbe2a25e6b94f8cc299">anonymous{NVPTXLowerArgs.cpp}::copyByValParam</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a55693c3374f66a0794daf3c1dbd00974">createRawLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a83ab43e08fac8e86c8bf333048ed60e2">createTypedBufferLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewritestatepointsforgc-cpp-/deferredreplacement/#a22b51efbb28485b0a26d255371306bcb">anonymous{RewriteStatepointsForGC.cpp}::DeferredReplacement::doReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a52f9ebe90c5295cbd67350376bd57eb3">dropTypeTests</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa5133cfd6ce1419c7162cd0d7ba39ea9">EliminateDuplicatePHINodesNaiveImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ae45f11045718186c0300d34919228c2a">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIdentitySCEV</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#acccaf0eaeef2b860b1182f8985f59e94">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIVComparison</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a664aaf46532d6ebeed0dfeb704308d33">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af4e05bf48a81b884e707efa650560fbf">llvm::objcarc::EraseInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d3e8ce57fb65481a42b256d26c264d">llvm::expandDivision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cfb58d48c02daaaa8ee7e924e9fb36">llvm::expandDivisionUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c6db1ba2b3654c01ec2363b2bc34ce4">llvm::expandDivisionUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a105cf64e7a2027cc32f43526f2e3df53">expandIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandmemcmp-cpp-/#aa507b512719f5e8d2b31c99f5534541b">anonymous{ExpandMemCmp.cpp}::expandMemCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0154d60f04a5d8549b44635852557f0">llvm::expandRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a090725add53936fcebc89f58fc9a7da1">llvm::expandRemainderUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27da54a97fcba955457048148b1fef99">llvm::expandRemainderUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a80a071231d638f7bf7976f9eb6478a4f">findPHIToPartitionLoops</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#a0c8e1730578d5e4181a2bd1502328802">llvm::SanitizerStatReport::finish</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a36b7410be1f86b52970bb1381904e282">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#a232bc3cdcfa2bab0574af9b47ff90c41">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::getInnerResumeDest</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2c1978d516a0154dd7f006e502ab4cfa">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::handleDynamicAllocaCall</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#afb784171b976ddd992e3f27ac36a894d">llvm::Constant::handleOperandChange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#af001e6326d49bf139dfeee21772f01f0">inlineGetBaseAndOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac306f2130698421f64f8a139faf38675">llvm::lowerAtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac963dddf8453fc717992d3ce36a27d8b">llvm::lowerAtomicRMWInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#ad2fd6546e0f1cc42311962f4ad4b29cd">lowerExpectIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a790c96adef17241b1ba4dbf475c3e57e">LowerNegateToMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocleanup-cpp/#a77b6227cc85a61fcbce08b8387c575a9">lowerSubFn</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a79f47e97963f500c113eb9bfee2e5b47">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileDP</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#aabc37fb487455e5268d389333bc5c890">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileLoadStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a230768916fc2abaf5fb0f563654d2cc8">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToCreateHandle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ab10e6ab2669a5c752426570de655e7ce">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerUpdateCounter</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1f70470f7a7722fd55c58c81358107f2">mergeCleanupPad</a>, <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a5d0250802fc18f3e96531f43c6280c18">llvm::InstDeleterIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a1e5a795e237da6e01636980c98b645ab">nullifySetjmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ae812aaa917422c3c4b067cda1b1d7019">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::optimizeAMXCastFromPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a996275d837998b396728990f8be0ef3a">OptimizeEmptyGlobalAtExitDtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aaa116d55b70fa3716c4ee6f0eb3488d8">processCmpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a6d4d9e7eb49fd2f51ffcb0596b37c596">processMinMaxIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a25e3db50d3aa8a3fa245e3c2d3197d7a">processOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ad47460e620c33c83309f749ea8f34c6b">processSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ace24fe825742577e78df32f725ad7b26">processSIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a914ea1510476a800508ae70d159bd8c0">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::processStaticAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#aec05cafc12b1852dbd16670773d4f00d">processUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa2ead3ae2cc059f459be46ce71ef20a5">removeCoroEndsFromRampFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5197ef3eec835595e81bcecb4ee02969">llvm::PHINode::removeIncomingValueIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a4601f3a29dbb6d4ea9da7f4dd26e2ae7">removeMarkerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cbd0aa1465957c50eaea8374875b27">llvm::removeUnwindEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#acf172e841018fd16e65771f5ade0b297">replace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#ac926ba61257c2262ebca3deca2cc8c76">replaceAliasWithAliasee</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a19e092ecf7889abf7277f13824e0c601">replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#aaa1cdfbf8bbbb3d37466c44f0b8a403b">anonymous{ExpandVariadics.cpp}::ExpandVariadics::replaceAllUsesWithNewDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#af678f41709f265e2589f247e883aa738">replaceAsyncResumeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a97741acf9b0e38ab508c939d99e53767">ReplaceCallWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab289568caaa6647ee577a06e6e12499a">replaceCoroEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a16096e55b9292113f13073fa2343b9c7">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceFloatIVWithIntegerIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8543371395854bee27033b8e24836cb0">replaceFrameSizeAndAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ac54843966305eb21541468d352728681">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a649ac561acbab510055b0e8f48ca0617">replaceLoopPHINodesWithPreheaderValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker/#ad39fccc0304ca0ff35a57687380ca595">anonymous{CodeGenPrepare.cpp}::SimplificationTracker::ReplacePhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#acd162cfe23d841a49056ce6436dd2075">replacePrepare</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ad4ea440b89ee11cd2aaecfd52290e069">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceRemWithNumerator</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a645f6e970e94d7ca51922b3932338f51">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceRemWithNumeratorOrZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8a96c9b1143670a73852464de9950e8e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceSRemWithURem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ac26a57370fde8e7b017b6094a9216b77">replaceSubOverflowUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a236935b2df66a03a0a54350a6b9b84bc">replaceSwiftErrorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad75372cc26ff6f641159aed90d5fc11e">reuseTableCompare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/classes/llvm/extractgvpass/#aa8ccdb19bbe28d226592a236b93311e8">llvm::ExtractGVPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loadandstorepromoter/#ac1da68baf80229b2d8af34499eb1c73f">llvm::LoadAndStorePromoter::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a4240fc0963676b19a8cbf8448a599700">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-shadowstackgclowering-cpp-/shadowstackgcloweringimpl/#a0b0a9e6fcf89c53f5411701c15ad6045">anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxgenerictonvvm-cpp-/generictonvvm/#ad0fae911d15e72e7f72b040a655dc081">anonymous{NVPTXGenericToNVVM.cpp}::GenericToNVVM::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a9364799319bac519aa565ec882986e6d">simplifyRelocatesOffABase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a9f3928b341e4412b8b66b794896014f0">simplifySuspendPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ace8766b97ac54db2bec8c29e4016f3f6">speculateSelectInstLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5ca29e57ad15a06f70b6676ec2665f34">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::transformAMXCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a7a5253091344c2d534f5afd16941e25d">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#aadcf41a9f704494210a217eb089678b3">tryToReplaceWithGEPBuiltin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b081ab710b9eb7fcb8dff225d41cf1f">tryWidenGlobalArrayAndDests</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a90987ac6a5075492b12b46acd6e9814c">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::updateShapeAndReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a29df0cec2acb067cfcb09eeeb726c7db">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#abf86ae2ede168d53dec70f0b0cb9d9b5">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a32bd3fc6040488f54b8fb322216218a5">DataScalarizerVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/storefatptrsasintsvisitor/#a77976478ff4af840d8dc298cd7bb1b65">anonymous{AMDGPULowerBufferFatPointers.cpp}::StoreFatPtrsAsIntsVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a9498339e26b296572a463a1300bf1a13">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#a9a06c7811f1ea67a51787ab0de806b5a">llvm::ObjectSizeOffsetEvaluator::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5b6ac7240be29b8a3a611a734a45d4a6">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitPtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### replaceNonMetadataUsesWith() {#ae0f750cccc69c91465adea3e30ee2165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::replaceNonMetadataUsesWith (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change non-metadata uses of this to point to a new <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>Go through the uses list for this definition and make each use point to "V" instead of "this". This function skips metadata entries in the list.</p>


<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### replaceUsesOutsideBlock() {#aa56e7093b552d99d48d66c5ae781236a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::replaceUsesOutsideBlock (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>replaceUsesOutsideBlock - Go through the uses list for this definition and make each use point to "V" instead of "this" when the use is outside the block.</p>


<p>'This's use list is expected to have at least one element. Unlike <a href="#a3ab5fc45117b450e8bb04e564cb6e5f2">replaceAllUsesWith()</a> this function does not support basic block values.</p>


<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### replaceUsesWithIf() {#a7e8dad1701aa6445be4a29f654b0473c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::replaceUsesWithIf (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * New, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;U)&gt; ShouldReplace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Go through the uses list for this definition and make each use point to "V" if the callback ShouldReplace returns true for the given <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>.</p>


<p>Unlike <a href="#a3ab5fc45117b450e8bb04e564cb6e5f2">replaceAllUsesWith()</a> this function does not support basic block values.</p>


<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a21fc5eae685ef3e2dce4403a75d5ff2f">llvm::MemorySSAUpdater::insertDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ace02ac07a3f704ffd345301bff92e5a8">replaceConstants</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#a79c3418f6abda9608f981c915c80e682">anonymous{AMDGPUSwLowerLDS.cpp}::replacesUsesOfGlobalInFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyoptimizereturned-cpp-/optimizereturned/#ae81d17afe649660014f0e1ca569e8bf3">anonymous{WebAssemblyOptimizeReturned.cpp}::OptimizeReturned::visitCallBase</a>.</p>

</div>
</div>

### reverseUseList() {#a25fd4916e8bb37be03d9f9b1279d5abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::reverseUseList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reverse the use-list.</p>

<p>Declaration at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1077 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### setName() {#a35ee267850af7c235474a8c46c7ac5af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::setName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the name of the value.</p>


<p>Choose a new unique name if the provided name is taken.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The new name; or "" if the value's name should be removed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a4e9132c0a4e72e51f7310163385d1d98">llvm::AllocaInst::AllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#acee1035fe1c77f85d4b80655e4df150a">llvm::BinaryOperator::BinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#ab29f15fad3f35ea8248e93e3dc805224">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::buildCFICheck</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a8eadc0b6c1d49a31d389dd611f44b08f">llvm::CastInst::CastInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionspecialization-cpp/#a5c190ec23618fc34d6b84fe7a671c788">cloneCandidateFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedeb89fa4ceb608d9d49bcd53ddcd2c1">llvm::CloneFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ae65337bd76ece9e7b1d20cf665bfa742">llvm::CmpInst::CmpInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#ab79e380b2ff4d4653bc9a766e1a59220">anonymous{MachineOutliner.cpp}::MachineOutliner::computeAndPublishHashSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/atomicinfo/#a27eedf5da8f111fe29254e21d94ffaa1">llvm::OpenMPIRBuilder::AtomicInfo::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a69c116deda6ae831a71558a4630323cb">llvm::InnerLoopVectorizer::createInductionAdditionalBypassValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cd89ca702a817aac3a4521dd2462a2e">llvm::DuplicateInstructionsInSplitBetween</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a23f5821d9ac264ae25dd087747e2c181">emitTransformedIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a0f37fe11b57d14686c7ca5e7a3846174">llvm::VPDerivedIVRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#ab04f963f804d27e1b7d7c9b9cfcacb9e">externalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a6d232c3c6e60c94891fffed1f9277e8a">llvm::anonymous{AMDGPUSplitModule.cpp}::externalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp/#a682c8b1a578622031f16f4be7766b603">forceRenaming</a>, <a href="/web-llvm/docs/api/classes/llvm/freezeinst/#a2b19ed32ae29a202bd29f9401ecb034b">llvm::FreezeInst::FreezeInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af38a8629ae32606b01eacbbd667d831c">llvm::GlobalValue::GlobalValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a823e9b0883ae72e62421714cd8bbda4c">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleEqualityComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a2e130f575ee6cbddeb0d62b295dee036">InsertStackProtectors</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#ab8d13cc98fc2777a70c49a4e6ede971f">llvm::LoadInst::LoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a557d913cc365524a47e73e4a8d468ab2">lowerIntrinsicToFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#aa5369c9d1c15e1c2fe5106461ae89334">lowerObjCCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a3c38fd13d9fa38356cca5ecdf7cfba23">optimizeSQRT</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a727a05f1cb9b333d251bd1485784d039">anonymous{ThinLTOBitcodeWriter.cpp}::promoteInternals</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a948aaf9d2ae438b3e2369223f55ec841">rematerializeChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ac03fa12298f2b2ef59db774839aa630f">rename</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#aaa1cdfbf8bbbb3d37466c44f0b8a403b">anonymous{ExpandVariadics.cpp}::ExpandVariadics::replaceAllUsesWithNewDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a97741acf9b0e38ab508c939d99e53767">ReplaceCallWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/materializationutils-cpp/#aba618c16a34739af0506ba1082d209a3">rewriteMaterializableInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/loopconstrainer/#af041772a16751b1c52d52ae08cd5046d">llvm::LoopConstrainer::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxgenerictonvvm-cpp-/generictonvvm/#ad0fae911d15e72e7f72b040a655dc081">anonymous{NVPTXGenericToNVVM.cpp}::GenericToNVVM::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a50ca93f9d04de6b4256cdfdb677611ed">llvm::ShuffleVectorInst::ShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a9550ae3e26eaa39468d80a6940709b5c">llvm::ShuffleVectorInst::ShuffleVectorInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/unaryoperator/#a301854f13228be009fe2a6af14f05484">llvm::UnaryOperator::UnaryOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/classes/llvm/vaarginst/#a6151a1bc3895a3bd7b433dd9f747898f">llvm::VAArgInst::VAArgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a> and <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a81c8a5368d02d0b52654a3efe83dec38">llvm::LoopVersioning::versionLoop</a>.</p>

</div>
</div>

### setValueName() {#a924b832eebd603551f849b631c8e5566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::setValueName (<a href="/web-llvm/docs/api/namespaces/llvm/#a0974858ce658c475882ec1f6082145de">ValueName</a> * VN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### sortUseList() {#a44e27e6f869703f42ebd1b050a75a121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Compare&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Value::sortUseList (Compare Cmp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sort the use-list.</p>


<p>Sorts the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>'s use-list by Cmp using a stable mergesort. Cmp is expected to compare two <em><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></em> references.</p>


<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>

</div>
</div>

### stripAndAccumulateConstantOffsets() {#a23c582e2452eeb2b2cf6e0c43eca617e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::Value::stripAndAccumulateConstantOffsets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset, bool AllowNonInbounds, bool AllowInvariantGroup=false, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">Offset</a>)&gt; ExternalAnalysis=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accumulate the constant offset this value has compared to a base pointer.</p>


<p>Only 'getelementptr' instructions (GEPs) are accumulated but other instructions, e.g., casts, are stripped away as well. The accumulated constant offset is added to <span class="doxyComputerOutput">Offset</span> and the base pointer is returned.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <span class="doxyComputerOutput">Offset</span> has to have a bit-width equal to the IntPtr type for the address space of 'this' pointer value, e.g., use DataLayout::getIndexTypeSizeInBits(Ty).</p>


<p>If <span class="doxyComputerOutput">AllowNonInbounds</span> is true, offsets in GEPs are stripped and accumulated even if the GEP is not "inbounds".</p>


<p>If <span class="doxyComputerOutput">AllowInvariantGroup</span> is true then this method also looks through strip.invariant.group and launder.invariant.group intrinsics.</p>


<p>If <span class="doxyComputerOutput">ExternalAnalysis</span> is provided it will be used to calculate a offset when a operand of GEP is not constant. For example, for a value <span class="doxyComputerOutput">ExternalAnalysis</span> might try to calculate a lower bound. If <span class="doxyComputerOutput">ExternalAnalysis</span> is successful, it should return true.</p>


<p>If this is called on a non-pointer value, it returns 'this' and the <span class="doxyComputerOutput">Offset</span> is not modified.</p>


<p>Note that this function will never return a nullptr. It will also never manipulate the <span class="doxyComputerOutput">Offset</span> in a way that would not match the difference between the underlying value and the returned one. Thus, if no constant offset was found, the returned value is the underlying one and <span class="doxyComputerOutput">Offset</span> is unchanged.</p>


<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#abae944a67cbc6299389596f63df4359a">areNonOverlapSameBaseLoadAndStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ac3cf098d54027ac28278b060376bdcbd">CleanupConstantGlobalUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a5a43eda4795549e941b4bacafdb956bb">foldConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afb6a2b1b5242599e12b7fe897140eda3">getAssignmentInfoImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#a2ced3b7cd6ff2ea19dd70f2f0fb10e2d">llvm::ConstantPtrAuth::isKnownCompatibleWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a55d9cc47f7041c1afad87f88ec5c7636">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerConstantPtrAuth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99fa28f2d78ae2ce889b621ab275a4ad">llvm::simplifyLoadInst</a>, <a href="#a574f86d538a28119d082be202fedb615">stripAndAccumulateInBoundsConstantOffsets</a>, <a href="#a14f27b1cef50a1f887650a8c79dbb436">stripAndAccumulateInBoundsConstantOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a8f460c92906b40c343854b69d48db50a">stripAndAccumulateOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#abce78109fa7acac1ae7aa1b4ee1ce07f">transformToIndexedCompare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>.</p>

</div>
</div>

### stripAndAccumulateConstantOffsets() {#a551ea28693c8f39b40d76f5255ca930d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Value::stripAndAccumulateConstantOffsets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset, bool AllowNonInbounds, bool AllowInvariantGroup=false, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">Offset</a>)&gt; ExternalAnalysis=nullptr)</td>
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



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### stripAndAccumulateInBoundsConstantOffsets() {#a14f27b1cef50a1f887650a8c79dbb436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::Value::stripAndAccumulateInBoundsConstantOffsets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset)</td>
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

<p>This is a wrapper around stripAndAccumulateConstantOffsets with the in-bounds requirement set to false.</p>

<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a23c582e2452eeb2b2cf6e0c43eca617e">stripAndAccumulateConstantOffsets</a> and <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8133ee4dcc7f8903e9b582593c09bf28">isNonEqualPointersWithRecursiveGEP</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>.</p>

</div>
</div>

### stripAndAccumulateInBoundsConstantOffsets() {#a574f86d538a28119d082be202fedb615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Value::stripAndAccumulateInBoundsConstantOffsets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset)</td>
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



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a23c582e2452eeb2b2cf6e0c43eca617e">stripAndAccumulateConstantOffsets</a> and <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### stripInBoundsConstantOffsets() {#a3711f4a2446d9e9302ebfa2fb1180883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * Value::stripInBoundsConstantOffsets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Strip off pointer casts and all-constant inbounds GEPs.</p>


<p>Returns the original pointer value. If this is called on a non-pointer value, it returns 'this'.</p>


<p>Declaration at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ae9ce92095ff18cb2c607d5a3591703ca">llvm::CodeExtractor::isLegalToShrinkwrapLifetimeMarkers</a> and <a href="/web-llvm/docs/api/structs/llvm/pgoindirectcallvisitor/#aba025734aa83b5cacf35c35bd572ee0e">llvm::PGOIndirectCallVisitor::tryGetVTableInstruction</a>.</p>

</div>
</div>

### stripInBoundsConstantOffsets() {#acab7642aedd7e0d2e7b5857d99328c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Value::stripInBoundsConstantOffsets ()</td>
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



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### stripInBoundsOffsets() {#a3ed745230c0e6c52f4b1ec0dae8c07fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * Value::stripInBoundsOffsets (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)&gt; Func=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *) {})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Strip off pointer casts and inbounds GEPs.</p>


<p>Returns the original pointer value. If this is called on a non-pointer value, it returns 'this'.</p>


<p>Declaration at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#ae3d9d3b5408e22143d8aee0d684454c4">anonymous{AssumeBundleBuilder.cpp}::canonicalizedKnowledge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizerbinarymetadata-cpp-/#a89d4abcbb96779cc08e69bd19abbac1d">anonymous{SanitizerBinaryMetadata.cpp}::maybeSharedMutable</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/threadsanitizer-cpp/#a0bb37c4d9d72e23c0da8cafdb59f466a">shouldInstrumentReadWriteFromAddress</a>.</p>

</div>
</div>

### stripInBoundsOffsets() {#a0443930d9dd02213bbc46588a7af488d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Value::stripInBoundsOffsets (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)&gt; Func=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *) {})</td>
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



<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### stripPointerCasts() {#a966eb231e7d4e572874d2cb49b18faea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * Value::stripPointerCasts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Strip off pointer casts, all-zero GEPs and address space casts.</p>


<p>Returns the original uncasted value. If this is called on a non-pointer value, it returns 'this'.</p>


<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a84a89ee9844b6cffc3660100168d7bee">llvm::MachineFunction::addLandingPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a7ba763fe17be006dc5cb7408dd332432">canParameterizeCallOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a23c3ad9b1a74163fc898fc3f8fa398dc">llvm::Attributor::changeAfterManifest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ad9ef9dbac3fbf9cc30e63d86bf9d7e34">compareNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a259334992127b809a034f025fc2bd13f">llvm::diagnoseDontCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8dbd4c4f3aebf9f810f0590d49ba1003">llvm::emitCalloc</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#aedbc3a6b1ed39b77650edac4239774cf">llvm::WebAssemblyAsmPrinter::EmitFunctionAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1484bdcb6b4c84ceb447270f8acca352">llvm::emitMemCpyChk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11b84a626ef34d3ced2e131937e58ddd">llvm::emitPutChar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8cc4358373eeb5363cd620bbdaeab">llvm::emitPutS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af4e05bf48a81b884e707efa650560fbf">llvm::objcarc::EraseInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ab0d48fabf61af227821d568b1c3aa4ca">llvm::VPInterleaveRecipe::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af88f364cd09c715e8853a1027c7180ef">llvm::findDevirtualizableCallsForTypeTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a1eea4a3473408dad3e81030a130a51ca">findInitTrampolineFromAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a8c82bb68e32af4477888125c41741a7f">FindUsedValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a348eede5b05a57edfafe7f8595cced8b">findUsedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#a6557fc92152c6e431a0072d7fe76bd83">llvm::AnyCoroIdRetconInst::getAllocFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/coroasynccontextdeallocinst/#a408cad1d4886ba53e81472a7852285d4">llvm::CoroAsyncContextDeallocInst::getAsyncContext</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendasyncinst/#a22e75cd1b723b6fae19aebb4407f9c60">llvm::CoroSuspendAsyncInst::getAsyncContextProjectionFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/coroasynccontextallocinst/#aec91e357f7c432ac64c479e194efd3b6">llvm::CoroAsyncContextAllocInst::getAsyncFunctionPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidasyncinst/#ab461e95beef7d14d7d648575035c5e63">llvm::CoroIdAsyncInst::getAsyncFunctionPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#adccfbc5892aaeafbf2178ddc7c71bde5">getAvailableLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#a5678ec2adcd02082dc703831ebdee65c">llvm::CoroIdInst::getCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#abe0e0a10af167017af1842ba615492ab">llvm::AnyCoroIdRetconInst::getDeallocFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a44f399ae5b08171d0b9886d0a27a582a">llvm::MemIntrinsicBase&lt; Derived &gt;::getDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#ad06f2af2991a303ba80e1e9fea006eaf">getInvariantGroupClobberingInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a81ed5939e93e21552b452f5f82a73a38">llvm::MemoryDependenceResults::getInvariantGroupPointerDependency</a>, <a href="/web-llvm/docs/api/namespaces/kernelinfo/#a3ce86cd1750ba693983bdec2c5d361be">KernelInfo::getKernelEnvironementGVFromKernelInitCB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#a7dd0ca6accd47d876a191473b33feacb">getKnownConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f8e808593fe987a587d9259865f136">llvm::getMaybeBitcastedCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/coroasyncendinst/#a027bb9d1043a71779d88816a0e22140d">llvm::CoroAsyncEndInst::getMustTailCallFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendasyncinst/#afa005fa6599ee04bd121e40a0dcdf756">llvm::CoroSuspendAsyncInst::getMustTailCallFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofinstbase/#ad6fc31f833f27dc182b882cbeceb7a5a">llvm::InstrProfInstBase::getNameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#aa17122071013697e6134f40d91c5c69d">llvm::CoroIdInst::getPromise</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#a3f0278794a8d4c4711fd5d60fbb28515">llvm::AnyCoroIdRetconInst::getPrototype</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#a9dbdb0ca9332c447a3ec6f7b3bbb2fce">llvm::CoroIdInst::getRawInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendasyncinst/#aeb9fbb3057734e2753c7cf8966bd0e84">llvm::CoroSuspendAsyncInst::getResumeFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a14c7178bc4d56dc8482dbb51fa6979b8">llvm::objcarc::getreturnRVOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#aaebde92913b64b73fa77dd6e8767d9d9">llvm::MemTransferBase&lt; BaseCL &gt;::getSource</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#a1217110bea3dc6c47ed8fab732d092b9">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::handleParallel51</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a8daf1ecab5704c6aa3672b2fcec60f29">isMaskedStoreOverwrite</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad2005ee17b5b6cb575257dc12793a077">anonymous{DeadStoreElimination.cpp}::DSEState::isOverwrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bca5709e8d5f8d45c9e46c51322e017">llvm::isSafeToLoadUnconditionally</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a996275d837998b396728990f8be0ef3a">OptimizeEmptyGlobalAtExitDtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a13c72931678c2da267fc265c7a2afdfb">optimizeOnceStoredGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#aef83676a470a77d6e089737fb024de94">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputAnnotations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#acd162cfe23d841a49056ce6436dd2075">replacePrepare</a>, <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/irlinker/#a29e247c718172acd518f8bb0255ff851">anonymous{IRMover.cpp}::IRLinker::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a9f3928b341e4412b8b66b794896014f0">simplifySuspendPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a6c6af867b9eca0a16600b50e31df0e33">llvm::Constant::stripPointerCasts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab73239c9eac42ae767c00ecc64e98dff">llvm::tryDelinearizeFixedSizeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>.</p>

</div>
</div>

### stripPointerCasts() {#a08ad28e3c7d7c2f0c2ecb5ddcd1da355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Value::stripPointerCasts ()</td>
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



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### stripPointerCastsAndAliases() {#a3111ed9ce005478f88fbf8d102a89fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * Value::stripPointerCastsAndAliases ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Strip off pointer casts, all-zero GEPs, address space casts, and aliases.</p>


<p>Returns the original uncasted value. If this is called on a non-pointer value, it returns 'this'.</p>


<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#a4f013baba6aa2ee4ad4a2cf6814f9f40">llvm::GlobalIFunc::getResolverFunction</a>.</p>

</div>
</div>

### stripPointerCastsAndAliases() {#a559c1ffcea756dea87714e5d51ed82f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Value::stripPointerCastsAndAliases ()</td>
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



<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### stripPointerCastsForAliasAnalysis() {#af7ce93500c8d9a8fbd0a40e461f3b780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * Value::stripPointerCastsForAliasAnalysis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Strip off pointer casts, all-zero GEPs, single-argument phi nodes and invariant group info.</p>


<p>Returns the original uncasted value. If this is called on a non-pointer value, it returns 'this'. This function should be used only in Alias analysis.</p>


<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalsaaresult/#ad1af2012f83ff1c94df346bbc8ac3b6a">llvm::GlobalsAAResult::alias</a>.</p>

</div>
</div>

### stripPointerCastsForAliasAnalysis() {#ac433d0ecf347d8fc3d4786002f31d7e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Value::stripPointerCastsForAliasAnalysis ()</td>
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



<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### stripPointerCastsSameRepresentation() {#a9a0f0124982d06eda91a2ab22cc1534c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * Value::stripPointerCastsSameRepresentation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Strip off pointer casts, all-zero GEPs and address space casts but ensures the representation of the result stays the same.</p>


<p>Returns the original uncasted value with the same representation. If this is called on a non-pointer value, it returns 'this'.</p>


<p>Declaration at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a1ef8e45df24dcf4222b48c8fe4077c3e">llvm::AlignmentFromAssumptionsPass::extractAlignmentInfo</a> and <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a085e72b5a3ed050deb15aa57090c54ba">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraint</a>.</p>

</div>
</div>

### stripPointerCastsSameRepresentation() {#ae20551fe1b3fb3429d78ac77b4f81a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Value::stripPointerCastsSameRepresentation ()</td>
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



<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a18dbfcb332af7515599ee795cf462843">Value</a>.</p>

</div>
</div>

### takeName() {#ae855357b6c5e6e7ed1869272708a3a84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::takeName (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfer the name from V to this value.</p>


<p>After taking V's name, sets V's name to empty.</p>



:::info
<p>It is an error to call V-&gt;takeName(V).</p>
:::


<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2b3fdb09b0789963c439d41fe91e44a1">llvm::changeToCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a3017b0d25a7e8961371e80a5fe4b10c7">expandUDivOrURem</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a36b7410be1f86b52970bb1381904e282">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a5a43eda4795549e941b4bacafdb956bb">foldConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp/#a682c8b1a578622031f16f4be7766b603">forceRenaming</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a4e5c7b6a107ed8c6fa33ce4b8a6f97c2">instCombineLD1GatherIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7fcf73aaa1b218db266c0f9d4020ab3f">instCombineRDFFR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7915bab3089583402f61b46f7baea356">instCombineSVECmpNE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aed4b32e0e8ed6a18607dde66ca4a433e">instCombineSVECntElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a9946a89352eee5ab78f0f3fc4fc18941">instCombineSVEPTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aba5cce04083b467217c8829a13e5b981">instCombineSVETBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a194bc0e605101ffd7f8249fcf88e45ca">instCombineSVEUnpack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aac6aaf36d8c34dfd27b90fc04ea3c08f">instCombineSVEUzp1</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a790c96adef17241b1ba4dbf475c3e57e">LowerNegateToMultiply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a0751e03131065414fffaa087c9e084cb">optimizeSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af939eab05ffe67221645aab1342156b2">PropagateOperandBundles</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a207ccf3b7552ac06054637cf55e01265">reassociateMinMaxWithConstantInOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a56b5a0fa4891dca73946affd4e6e3ffd">removeFromUsedList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cbd0aa1465957c50eaea8374875b27">llvm::removeUnwindEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#ac926ba61257c2262ebca3deca2cc8c76">replaceAliasWithAliasee</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a8b47a3cfdac6c8cc7e158e8ee75973d7">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::replaceMulWithMul24</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ae17ac9c827f3c2d2ae6ec6da46566807">replaceUnaryCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a670232d63153cd8cd2793b3106e80661">rewriteMemOpOfSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-shadowstackgclowering-cpp-/shadowstackgcloweringimpl/#a0b0a9e6fcf89c53f5411701c15ad6045">anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-spirvregularizer-cpp-/spirvregularizer/#ad05a40cc766968c47d80ddd0f72d3114">anonymous{SPIRVRegularizer.cpp}::SPIRVRegularizer::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a64cd5b79789610d81be5d0b2633868ae">anonymous{ThinLTOBitcodeWriter.cpp}::simplifyExternals</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a9364799319bac519aa565ec882986e6d">simplifyRelocatesOffABase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ab952034edc23ad21ab312e0baaea0d7e">tryFactorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5417dab7a760eedf39c533b1b31b1b23">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a21c7503f18216d727a9798c0643f3bf8">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a28d5aaadc2b319f9ac050aa712e49a76">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitIntrinsicInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a06396b4dd155b05f3faeb9dc674c3787">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitMinNum</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5b6ac7240be29b8a3a611a734a45d4a6">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitPtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#aa22a44bbc6646770b4bd139ca4fe2d94">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSelectInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a960e756e8b2f056fbba7baa5bdcfb769">widenDestArray</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b81e19b3ddf7ec786c5105ba5470153">widenGlobalVariable</a>.</p>

</div>
</div>

### use\_begin() {#a413abcab8dbc3900fc2fde96a5d8fca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_iterator llvm::Value::use_begin ()</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#a7ad234db7c28b66de3845bb86249cac2">materialized_use_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a064517d4fd6ce0d70f560e1ae3cdb4a6">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::combineLoadCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#a57e48e140e75da173a7ec5c681a1f2cc">forEachCall</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl/#ae5eb92f05b5c0c082472775da1e6cace">llvm::LazyValueInfoImpl::getValueAtUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a37275b44ee2af4598d1782f93d9204f3">hasNonFlagsUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37275b44ee2af4598d1782f93d9204f3">hasNonFlagsUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#abcf78af37d56a9b72a49c65428210758">llvm::MemorySSAUpdater::removeMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5ca29e57ad15a06f70b6676ec2665f34">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::transformAMXCast</a>.</p>

</div>
</div>

### use\_begin() {#a24018b06ac0d956553428c86d5af7d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_use_iterator llvm::Value::use_begin ()</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#a7ad234db7c28b66de3845bb86249cac2">materialized_use_begin</a>.</p>

</div>
</div>

### use\_empty() {#a9d7de807ebdfe1819df3ff6cb0f16158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::use_empty ()</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a52e95fe46f358afc3b0006f256f9d487">computeVirtualCallSiteTypeInfoMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#abdf3ba57973320bd702d3b12b0b8fa8c">createRetPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5586ec5eac8a93b87b095f949ea8daf3">anonymous{SimplifyIndVar.cpp}::WidenIV::createWideIV</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86loweramxtype-cpp-/#ac70ad014fafab07c0e998e501bffd828">anonymous{X86LowerAMXType.cpp}::DCEInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dce-cpp/#ada357ebb15bf8c3cb88900273ec95888">DCEInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5a50ba4ab5027d4013cf6bc2edf66085">deleteIfDead</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae1a4c619a44ea59a2cdeeb85060f385d">llvm::Constant::destroyConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa9a2aed0d26a4fca41f8fc0986a3f12b">llvm::AsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a52f9ebe90c5295cbd67350376bd57eb3">dropTypeTests</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a410a078c88ab7a1e5a4ce7362adc3efa">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::eraseFromParentAndMove</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af4e05bf48a81b884e707efa650560fbf">llvm::objcarc::EraseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a12f6125cdd608cb0459585ddb68ead53">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::foldIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#a57e48e140e75da173a7ec5c681a1f2cc">forEachCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae6fa18c5b7272e2bdd00c26da8041358">hasAddressTakenAndUsed</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ae965d93aa46ad834c21718eba4b5b78e">hasSameExtUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#afa93649aba5a7b6388adff903a4a6085">hasUseOtherThanLLVMUsed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#adb7886272a3ab071ecd4a576d865dc21">llvm::AANoCapture::isImpliedByIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a87548c69480b23599d643d518412895c">isIntrinsicOrLFToBeTailCalled</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a336ed98852175e7e955e9217080bd596">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::isKnowledgeWorthPreserving</a>, <a href="/web-llvm/docs/api/classes/aliasscopetracker/#a426cdd40c6024520c943e7c3d11f1d78">AliasScopeTracker::isNoAliasScopeDeclDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#abbd47852a13b73290f4625f20c9018d8">isRemovableWrite</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#aadea9e45e0a6d101d915754dde54226a">mustPreserveGV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ab7fe47fe1b533f4c9bdd23baf28f3c8c">OptimizeAwayTrappingUsesOfLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aba35cb55d089d58ace72978cb0249dc8">optimizeGlobalsInModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a580f44370be222c0b2be5a2a7fa3f048">processSelect</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a727a05f1cb9b333d251bd1485784d039">anonymous{ThinLTOBitcodeWriter.cpp}::promoteInternals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1de454f8f11d343f01bde5f057af057e">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#adc17801011bc699f45494d07c83a2ddd">llvm::StatepointLoweringState::relocCallVisited</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#acd0427b84adce00e5b26f993c7aa48c8">llvm::MemorySSA::removeFromLookups</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa8ccbcf19b9150f2872f794ecdc53d3e">llvm::slpvectorizer::BoUpSLP::removeInstructionsAndOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#abcf78af37d56a9b72a49c65428210758">llvm::MemorySSAUpdater::removeMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a97741acf9b0e38ab508c939d99e53767">ReplaceCallWith</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a70f7f0574edbfc0f75424499133d4ba3">llvm::LazyCallGraph::RefSCC::replaceNodeFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/#a928b990e2086ecbb0da94e377a0a4a7d">anonymous{PartialInlining.cpp}::PartialInlinerImpl::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#a20589df6cd2c2e12e77a1741a0e4223e">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a363028d7884038c73a4f3f2474530c33">anonymous{WholeProgramDevirt.cpp}::DevirtModule::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loadandstorepromoter/#ac1da68baf80229b2d8af34499eb1c73f">llvm::LoadAndStorePromoter::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a619173b034be1462e5179788c6656c0e">llvm::StatepointLoweringState::scheduleRelocCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7d068ffb71feb72ff6d1dee350ec7677">simplifyAndDCEInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0706966ac4f391854346bebfcda816fa">llvm::anonymous{AMDGPUSplitModule.cpp}::splitAMDGPUModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#a93898976321fdcdb6827b4885b0d435c">splitGlobals</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a216b0f52f244182222da5b7fcbc8ca01">stripDebugDeclareImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5ca29e57ad15a06f70b6676ec2665f34">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::transformAMXCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a9481f3ebdbe940c0b6fe67d1fe0e45a2">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitGetElementPtrInst</a>.</p>

</div>
</div>

### use\_end() {#ad86469939d2a8bdd4169be9403b89f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_iterator llvm::Value::use_end ()</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="#a1e05a5aed47fc02cbb7f252d489b405c">materialized_uses</a>, <a href="#a8a8eddca4c6b9167400f54beb8786343">materialized_uses</a> and <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>.</p>

</div>
</div>

### use\_end() {#ac124783761e79d74db1e97d38224216b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_use_iterator llvm::Value::use_end ()</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### user\_back() {#a46db903db2484e1ef5062d094d6b0854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User * llvm::Value::user_back ()</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#acf1d82a256748288e01404b1903f762b">materialized_user_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constant/#ae1a4c619a44ea59a2cdeeb85060f385d">llvm::Constant::destroyConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ab23c37279d90814b87d6c8ab25b43d0b">emitGlobalConstantImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a216b0f52f244182222da5b7fcbc8ca01">stripDebugDeclareImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a643f8d7ef849e1312c83906b4b27b4aa">llvm::InstCombinerImpl::visitInsertValueInst</a>.</p>

</div>
</div>

### user\_back() {#a59d3fe5f30609b50112d91f41d268567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const User * llvm::Value::user_back ()</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#acf1d82a256748288e01404b1903f762b">materialized_user_begin</a>.</p>

</div>
</div>

### user\_begin() {#a158da2b6d3d938aaa15b6acd00150e2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">user_iterator llvm::Value::user_begin ()</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#acf1d82a256748288e01404b1903f762b">materialized_user_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#af408665da3f00cec50ecb935ad72e689">addAllGlobalValueUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aae70ddddbfd05ed5831918fa1836b947">llvm::AArch64TTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae8b00d72cfbbf3ef02315ae6a0ecc418">llvm::GCNTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a9407ebeb07769b15977760b26beb7db6">llvm::ARMTTIImpl::getIntImmCostInst</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a97ebd00c769b1d7c67f7db4b58137c93">llvm::SystemZTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ae965d93aa46ad834c21718eba4b5b78e">hasSameExtUse</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a710fc966df72f9cae9f17ec7eb76f5e8">llvm::SystemZTTIImpl::isFoldableLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a2db21ddc2a6983ec696cd972ad43031e">isFPSatMinMaxPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a26c84133695829e63f3a69adaddbe6b4">isI128MovedToParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#ac228330c525b61539291248b52ddb30e">isPointerUseReplacable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a0deafca5c66f3b900139bcf024085e8f">isSSATMinMaxPattern</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a670aa0012e26bf3d40dfa5068743ac48">llvm::X86::mayFoldIntoStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a960620248182018e566b095f06a605df">llvm::Constant::removeDeadConstantUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a19e092ecf7889abf7277f13824e0c601">replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a4240fc0963676b19a8cbf8448a599700">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6ad23b58059ffd91df6a2dddf30c5d71">llvm::X86TargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6609528bd67d5506a9bf9a2cce2d6f58">llvm::Instruction::user_back</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9c799bce3238ef2d8b7b2da3e03745d6">llvm::Instruction::user_back</a>.</p>

</div>
</div>

### user\_begin() {#affbc364be263e23ef9f54686c947ca6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_user_iterator llvm::Value::user_begin ()</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#acf1d82a256748288e01404b1903f762b">materialized_user_begin</a>.</p>

</div>
</div>

### user\_empty() {#af21f61086e696a788f549768fdc26a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::user_empty ()</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>.</p>

</div>
</div>

### user\_end() {#aa22118b2b3f206bfda2ffab4cda94d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">user_iterator llvm::Value::user_end ()</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#af408665da3f00cec50ecb935ad72e689">addAllGlobalValueUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#ac228330c525b61539291248b52ddb30e">isPointerUseReplacable</a>, <a href="#a0104cde53b84260b50b2557f1f718d96">materialized_users</a>, <a href="#a24d8aaa6a925b40c09fdbf6d7ab332fd">materialized_users</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a960620248182018e566b095f06a605df">llvm::Constant::removeDeadConstantUsers</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a4240fc0963676b19a8cbf8448a599700">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>.</p>

</div>
</div>

### user\_end() {#ae9d0fa4bc2ba8b0bdbf059790c055340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_user_iterator llvm::Value::user_end ()</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### users() {#a411cf3e3932f209ce3374cb31adc1da6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; user_iterator &gt; llvm::Value::users ()</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#a0104cde53b84260b50b2557f1f718d96">materialized_users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0ee1f18526ee78ef18612b6a86dc16fc">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ababcaf6e2e00fc3fc8791ea2c3acbda5">addFullyUnrolledInstructionsToIgnore</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2cf59a15a8b7603c5d66d8fdb117ecec">AllUsesOfValueWillTrapIfNull</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/allocainfo/#aed57a9dd738a483f6ac02904b981c94d">anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::AnalyzeAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a7227d9ecc33b8ed7a50b0d4341448c6c">calculateCXXStateNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#aaaced3d57d8877d30048b69be2787b21">calculateSEHStateNumbers</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#adb122f608fe469bd24f486598a4bc881">anonymous{CoroElide.cpp}::CoroIdElider::canCoroBeginEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#aafa8144325b3c584e828b07d73a8cb25">llvm::LoopVectorizationLegality::canFoldTailByMasking</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7414a7c636bc5a30b0e8478019a1bcd4">llvm::canTrackGlobalVariableInterprocedurally</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#aa89462fcd72ee43d1b3f2df0a61a698e">checkOverflow</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#aba29b35909e39c48517e7475412c776a">anonymous{PointerTypeAnalysis.cpp}::classifyPointerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ac3cf098d54027ac28278b060376bdcbd">CleanupConstantGlobalUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adc803f628b45e58e3de84b46dd0b7d83">CleanupPointerRootUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#a54ab652f375db02ea7894a5f9a512d15">clearAssumptionsOfUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ad4c63831e91ac3cd309f7cc144519411">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::combineAMXcast</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5727bfde67259475310b6da6c18027e5">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::combineLdSt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#ab299749106299a5f9b4420486988f11a">anonymous{CoroElide.cpp}::CoroIdElider::CoroIdElider</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5897728042dea4157da81dc8fe3fe160">llvm::createAnyOfReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#a8c9ae0be5e6bcad90cdf141962a117f3">createRetBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#abdf3ba57973320bd702d3b12b0b8fa8c">createRetPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f2b185fd3e7dd4d0e694e773792fb8">llvm::InstCombinerImpl::dominatesAllUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a52f9ebe90c5295cbd67350376bd57eb3">dropTypeTests</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#acccaf0eaeef2b860b1182f8985f59e94">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIVComparison</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19d345e6fa45d60ff4092769417b89b2">llvm::findDbgDeclares</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#ac43142f662a5dd59c09abd92322a9821">findDbgIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a1eea4a3473408dad3e81030a130a51ca">findInitTrampolineFromAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a206a95af7fd1177ef8396cd69b888de2">findInnerReductionPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a41caa0b8eaefb07b7f8fcf19b05bb249">FindPreallocatedCall</a>, <a href="/web-llvm/docs/api/groups/arcutilities/#gaf231df4dd6fb738c1f548aedb34ca81e">FindSingleUseIdentifiedObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a25bb1b65c9a916d968fcc66158103506">findUses</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a39e315cb89b7144083895c083cc958e0">llvm::InstCombinerImpl::foldICmpSubConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abd122b6678d6a8f14b6ab6bc18863b27">llvm::InstCombinerImpl::foldPHIArgIntToPtrToPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ad15d45b871d3111e8da4f9b394d7c83f">forwardStoredOnceStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ab5e88a19352e7dce1b0115f5e6b37b47">getArgSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a33732eca78566a433c723c087dda203e">getCleanupRetUnwindDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#aa3b0ffc4e031802ced683f381cac97af">getCleanupRetUnwindDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a41add7dc9178ec10f8f2d4d6fd2a6f9a">getFSqrtDivOptPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#af997f3314625f4b7fcac2d24b5d9539e">llvm::GCStatepointInst::getGCRelocates</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#ab1af1f498b4d814ee68810a03fbe28a7">getGCResultLocality</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#ad06f2af2991a303ba80e1e9fea006eaf">getInvariantGroupClobberingInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#ae680ddd3ca632852ddc356932e208482">llvm::HexagonTargetObjectFile::getLutUsedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac1b59b7799509e47193276bc8b9a716d">getModuleFromVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e029adee2598c38ae32e0bce262e4d0">llvm::getNumOfCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a6415fb68bc55f3a316aa414a5c2c0ab2">llvm::RecurrenceDescriptor::getReductionOpChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a3cc72cfbc837c8e89491b6357c358778">getUnwindDestToken</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4e19285f051b80099ed8b36c5c94eaf2">getUnwindDestTokenHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7294d908ab6f3be2a71593bd8f7f1eb3">llvm::AMDGPU::getUsesOfLDSByFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#ac17b99a95c0b634b1c5de85e77b42a7a">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getUsesOfLDSByNonKernels</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#ae3341aa2a4a16c49b2be04002018a1a6">getVectorDeinterleaveFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a0ea8063abb874faff99f39c4e849f8de">HasAddressTaken</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#ab3f525d3e208af9a6e3e547fb58196e2">hasExceptionPointerOrCodeUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a0f31e8ea7a0fea18c2df924e7d6e8de8">hasHardUserWithinLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#afaa78d0b3224d3175937f997dc2bc688">hasLifetimeMarkers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89f41bef45732023f8662884065cd058">llvm::hasOutsideLoopUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ae965d93aa46ad834c21718eba4b5b78e">hasSameExtUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a24b18f2c77f69e54841c51bb3d31cad2">hasStoreUsersOnly</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizerbinarymetadata-cpp-/#abd05beff43e8533c652627d0f54ccbff">anonymous{SanitizerBinaryMetadata.cpp}::hasUseAfterReturnUnsafeUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#ac3b3ae3662af2dcad3cab15f9ba148d4">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fcd2292dd9e51480a2f43d41acfe2">llvm::invertCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5023b360abc7a5d1612061fba30003a6">llvm::isAllocaPromotable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a5d94ee8aaee00c42c11954aaa6022894">isAllocSiteRemovable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca57f75a6554ba9ed3bc72ef7b7540de">llvm::isAlmostDeadIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a899698594c66589eab9bdca89c843798">isArgUnmodifiedByAllCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#afe702618f56478e67eb0f705efb648b6">llvm::Loop::isAuxiliaryInductionVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ac63a8c5280ada17077a6aa14363348b3">llvm::Constant::isConstantUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo/#a093ef109d6ca444b796483cab67f3a27">llvm::SuspendCrossingInfo::isDefinitionAcrossSuspend</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a203487323e0aa341b6c24f9ef20b5909">llvm::RecurrenceDescriptor::isFixedOrderRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a1db077f1815950aa2f419be901c429c6">isGOTEquivalentCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7ac21134b2aaca2a7d55f6ff9d92f5b2">isHighCostExpansion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a56bc54b1cdc353a04db9ffa06e20d33c">isI32InsnAllUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a831a5dec04e512d616fccb6e1f474e79">isLoadInvariantInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a1034debe467e168b688e5630170d9093">llvm::coro::anonymous{SpillUtils.cpp}::isLocalAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#adfa827b083d21f99d75f9e3e08205fee">isOnlyUsedInComparisonWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a095a10eac0b263743eb5086a581e4020">isOnlyUsedInEqualityComparison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5804b68ebc77c8751a9cb4e066735450">llvm::isOverflowIntrinsicNoWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ade4086b409f00a755cfc6c0b03f67413">isPointerValueDeadOnEntryToFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/sveintrinsicopts-cpp/#ab3363381f198b25f4ce23364c08ea1f0">isPTruePromoted</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a6b46ea77082dda0b24b9fea490ae8fc8">isSafeAndProfitableToSinkLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#af47b2b88cf087903cd678c12700be7b4">isUsedAsMemCpySource</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae21f217cd2f8044e639f13111a0b37db">isUsedByLifetimeMarker</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a47b0e7da15eccab3545643118aa2f99f">localAllocaNeedsStackSave</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7994fd7ca0d8f8fcf2a9d18d151d0988">llvm::LowerDbgDeclare</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a36764d140de2314a0f15b203f0556112">llvm::coro::anonymous{SpillUtils.cpp}::lowerNonLocalAlloca</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a4c0d39301fbda30cede0fcbb4d649c75">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a49830d163fb836dbd4d3af87150b1bd9">mapWasmLandingPadIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopflatten-cpp-/flatteninfo/#ae4b9ef35d5c40d69ae861c215edd3a08">anonymous{LoopFlatten.cpp}::FlattenInfo::matchLinearIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a49795f7ac26b96f40f4acfd51cc1c822">needCarryOrOverflowFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#acda14ede9da471244980c7fada91a4aa">negateICmpIfUsedByBranchOrSelectOnly</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a1e5a795e237da6e01636980c98b645ab">nullifySetjmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a225a82c4ac2e230eabb25ae5b14a019d">OnlyUsedBy</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a5b1f1cdeb4ae8fd31ba514fdb15b018d">onlyUsedByLifetimeMarkersOrDroppableInstsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a23e66d415d7d85df65edc042d54de8d6">onlyZeroFlagUsed</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ae812aaa917422c3c4b067cda1b1d7019">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::optimizeAMXCastFromPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ab7fe47fe1b533f4c9bdd23baf28f3c8c">OptimizeAwayTrappingUsesOfLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a996275d837998b396728990f8be0ef3a">OptimizeEmptyGlobalAtExitDtors</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#aa50432deded202fb241ca2c204e8137a">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::optimizeLiveType</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a42ba71cba0e3d5e1b4e5395fd080016d">llvm::AlignmentFromAssumptionsPass::processAssumption</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#aec05cafc12b1852dbd16670773d4f00d">processUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#adf1371d869d3a7468c48401a2a321b26">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::propagateShapeForward</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#ac65b91bafca4f727e589bdfbfb79edc1">anonymous{SimplifyIndVar.cpp}::WidenIV::pushNarrowIVUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopidiomrecognition-cpp-/polynomialmultiplyrecognize/#a2d8e2d584aba003918f1d906f645df9e">anonymous{HexagonLoopIdiomRecognition.cpp}::PolynomialMultiplyRecognize::recognize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a36fe1ed1682023b7fb3c4699f9009d31">removePAICalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a8eb92eb19c1f4493993e26eee9cc7f60">anonymous{DXILOpLowering.cpp}::OpLowerer::removeResourceGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionprecedencetracking/#a2dd8fd10b417c6205bd128a3c660df4b">llvm::InstructionPrecedenceTracking::removeUsersOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#abf799de7147065c0e7f525e1b6009dde">llvm::coro::replaceCoroFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a16096e55b9292113f13073fa2343b9c7">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceFloatIVWithIntegerIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a649ac561acbab510055b0e8f48ca0617">replaceLoopPHINodesWithPreheaderValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#ae5532112c4ead645d90e6fe4e5092f5f">rewriteNonInstructionUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentpromotionpass/#afe0f49f9daec2532b14ded30ed46ff28">llvm::ArgumentPromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfaspacecastsimplifypass/#a76364c57022d89ac618f1b1e22bef6e2">llvm::BPFASpaceCastSimplifyPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a1d6e16608b64f29f9a4d1483507317b5">llvm::coro::BaseCloner::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroearly-cpp/#a0af71aee449ca1e2e4a0e3c280d8a791">setCannotDuplicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a463056de56ab82cc6e2c50e5ccf17626">shouldCheckArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac6c9b791cef5925e123539fb2934316b">shouldCombineToPostInc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#a41713fe2635c183d98e1a6b7c1cedff5">shouldSpeculateInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver/#ab2eb802e84c2b0f592aee41ad6c2b729">llvm::SparseSolver&lt; LatticeKey, LatticeVal, KeyInfo &gt;::Solve</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8ff215a6e938a8df32c29c99bc126603">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::strengthenRightShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a7223c62dc4b1db59861cb3a7e225a387">llvm::coro::suppressCoroAllocs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3fb33a8a29e076405285e5282eba81fd">swapICmpOperandsToExposeCSEOpportunities</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a7a5253091344c2d534f5afd16941e25d">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ae8ee5af33e0f1b85755cf5a1e4951793">tryToElideArgumentCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a8528dea79f0940669c4fcb751940ca94">tryUnmergingGEPsAcrossIndirectBr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b081ab710b9eb7fcb8dff225d41cf1f">tryWidenGlobalArrayAndDests</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a8178893fef2816f4172536f259aa6450">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::updateImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#aa1dc9f6d1275060b935085cf57095e9b">usedInOneFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#aa91fc385b3c151e89ac23b656e9bf8b6">usersDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a8535b262a19144f9ff988b6bd8c19f42">valueEscapes</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>.</p>

</div>
</div>

### users() {#a47e5062f8da90137678150d09bb17751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_user_iterator &gt; llvm::Value::users ()</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#a0104cde53b84260b50b2557f1f718d96">materialized_users</a>.</p>

</div>
</div>

### uses() {#abf855b7cd63a0cd7f73759e396f280c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_iterator &gt; llvm::Value::uses ()</td>
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



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#a1e05a5aed47fc02cbb7f252d489b405c">materialized_uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#ae52dc32e051ded6356e4065b75d19935">addIntrinsicToSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/globalstatus-cpp/#a17a474b70329d911e0b4f13e552dc99f">analyzeGlobalAux</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ab0cf90f56e055b09227ab0f84acc4083">llvm::InstCombiner::canFreelyInvertAllUsersOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9e6b15b1005dd460a35359f104cb06fe">canRewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ae9efb27478c86bece81f1bf5bca2d348">canSinkInstructions</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4062c17e282cb2667cf0d52150c67fea">collectSRATypes</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/#a86f06c6063c3a34171f47246e4c94ce8">anonymous{OpenMPOpt.cpp}::OMPInformationCache::collectUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a52e95fe46f358afc3b0006f256f9d487">computeVirtualCallSiteTypeInfoMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a52f9ebe90c5295cbd67350376bd57eb3">dropTypeTests</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a55af5cce8eb7833907578e6fc3f0ab5e">eliminateSwiftErrorAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7f5b1f0925dc2dbb62f05681772ca912">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::finalizeLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typemetadatautils-cpp/#a64702c7c3e6913b9076666d4e071b35d">findCallsAtConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a1e71f36e9936f126265e383fd67440f7">findDemandedEltsByAllUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8148654fcf3528ef06d7a0e28b57b952">llvm::findDevirtualizableCallsForTypeCheckedLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af88f364cd09c715e8853a1027c7180ef">llvm::findDevirtualizableCallsForTypeTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typemetadatautils-cpp/#a5b42cb0df93187fef9fa135a5d14a06a">findLoadCallsAtConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ae8c2577ec683ddfe8caa2bf447de78df">findUser</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#acf71d4170b64e15a937f8c8ed61cbd68">anonymous{AttributorAttributes.cpp}::followUsesInContext</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a0b9027fe8e7ff91d9d6ee565fbdb3db4">anonymous{DeadStoreElimination.cpp}::DSEState::getDomMemoryDef</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a81ed5939e93e21552b452f5f82a73a38">llvm::MemoryDependenceResults::getInvariantGroupPointerDependency</a>, <a href="#a3a402430a1bbe70a9282dcb0e0b6a2cd">hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae78f734e49b5ad94836bf32dda101ec6">llvm::hasPartialIVCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a29da820d4c19ac64f750762012fd13ca">anonymous{IndirectCallPromotion.cpp}::isDestBBSuitableForSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#ae1c9444bcb6b157e8f8c4ec8bf265010">isOnlyCopiedFromConstantMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-cpp/#aaf4331210de8ead749895971e5de9791">isPossibleIndirectCallTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a79f47e97963f500c113eb9bfee2e5b47">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileDP</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#aabc37fb487455e5268d389333bc5c890">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileLoadStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignimpl/#a386b43737ff3f36caaf7369350e678b1">anonymous{AttributorAttributes.cpp}::AAAlignImpl::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#aee580d948709366b6a676f8b48460137">llvm::LoopInfo::movementPreservesLCSSAForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89d936a98d65c79ddb962452b2d670bd">llvm::PointerMayBeCaptured</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a385464d789381c250f924d62222498f3">predictValueUseListOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/valueenumerator-cpp/#a0446dc9c4c3fd1116f5510fab7d64a43">predictValueUseListOrderImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilvalueenumerator-cpp/#a0446dc9c4c3fd1116f5510fab7d64a43">predictValueUseListOrderImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a29d1924e4ba18c2dcbb6af2582f889a3">llvm::ValueEnumerator::print</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a42ba71cba0e3d5e1b4e5395fd080016d">llvm::AlignmentFromAssumptionsPass::processAssumption</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a580f44370be222c0b2be5a2a7fa3f048">processSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a0a084f86091fd327d3113e8674c54192">anonymous{ThinLTOBitcodeWriter.cpp}::promoteTypeIds</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad50c0551a73d70d5bd769557bdbec3d7">anonymous{DeadStoreElimination.cpp}::DSEState::pushMemUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a82f896385cac84a2e477159ad31ace74">removeIntrinsicUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af0ce60c4a958016f62ce78f1eda423af">removeUnusedBlocksFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a83664bf5c186d5e2d65853f2cce4ec3a">replaceAllPrepares</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a92e7361f7532de414322df105163781f">replaceDominatedUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a669b909f685098d484bb789192620885">replaceLoopInvariantUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22deed11f251c5761b2b4bf021eff4ac">llvm::replaceNonLocalUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#acd162cfe23d841a49056ce6436dd2075">replacePrepare</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a87b0b481058d1def42e0b3a6564ed93d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceSplitDoubleCallUsages</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a30e276f415c0b092317585c37160f9ce">runAttributorOnFunctions</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a021e32e2bf67f331d9384a162dc402c2">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeCheckedLoadUsers</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeTestUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a1ba99155749ea6a41858f9bc4449f543">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::simplifyUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#af1fb897c419e6a5080ecf54baf13f169">llvm::JumpThreadingPass::tryToUnfoldSelectInCurrBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a714c6f3608e37d0dba17cdc086dc16d2">llvm::updatePublicTypeTestCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#a5109075f25d18bf4127922f2ab403dca">UpdateSSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a406d93c10bd410f7ef8af5c00b037b8b">valueIsOnlyUsedLocallyOrStoredToOneGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a6dcb5e3d63691e83e0fdc0d67148077a">llvm::MemorySSA::verifyOrderingDominationAndDefUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### uses() {#a224d0ab04e6510402fb5c7221666efed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_use_iterator &gt; llvm::Value::uses ()</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>References <a href="#a3279672b4ef05895858df6f4b05c0de8">assertModuleIsMaterialized</a> and <a href="#a1e05a5aed47fc02cbb7f252d489b405c">materialized_uses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### clearMetadata() {#ad151fceb9a0e77a8a8017d4f68791811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::clearMetadata ()</td>
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

<p>Erase all metadata attached to this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Declaration at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1603 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="#a9eb4a52a4675976293ae4f77c982667b">HasMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6577bf24ddcb2a2cd401ee3e4704527a">llvm::LLVMContextImpl::ValueMetadata</a>.</p>


<p>Referenced by <a href="#a9d88e21e9caa53945e903fd8c8700b4f">eraseMetadata</a> and <a href="#ab1198eef44b311a7984cfc8fc97fac6d">eraseMetadataIf</a>.</p>

</div>
</div>

### eraseMetadata() {#a9d88e21e9caa53945e903fd8c8700b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Value::eraseMetadata (unsigned KindID)</td>
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

<p>Erase all metadata attachments with the given kind.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any metadata was removed.</p></dd>
</dl>


<p>Declaration at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1576 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="#ad151fceb9a0e77a8a8017d4f68791811">clearMetadata</a>, <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="#a9eb4a52a4675976293ae4f77c982667b">HasMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6577bf24ddcb2a2cd401ee3e4704527a">llvm::LLVMContextImpl::ValueMetadata</a>.</p>

</div>
</div>

### eraseMetadataIf() {#ab1198eef44b311a7984cfc8fc97fac6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::eraseMetadataIf (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(unsigned, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *)&gt; Pred)</td>
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

<p>Erase all metadata attachments matching the given predicate.</p>

<p>Declaration at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1588 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad151fceb9a0e77a8a8017d4f68791811">clearMetadata</a>, <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="#a9eb4a52a4675976293ae4f77c982667b">HasMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6577bf24ddcb2a2cd401ee3e4704527a">llvm::LLVMContextImpl::ValueMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9c5f771f232bbd4cf6ec230bd78f9174">llvm::Instruction::dropUnknownNonDebugMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#af5b08506925637f8addbc11e2190dde6">llvm::Instruction::eraseMetadataIf</a>.</p>

</div>
</div>

### getAllMetadata() {#a3d200b1568f70b28ae0eb9bec58d6690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::getAllMetadata (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &gt; &amp; MDs)</td>
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

<p>Appends all metadata attached to this value to <span class="doxyComputerOutput">MDs</span>, sorting by KindID.</p>


<p>The first element of each pair returned is the KindID, the second element is the metadata value. Attachments with the same <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> appear in insertion order.</p>


<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a>, <a href="#a1f496e54accb2cbe919fb456cb703f1a">hasMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6577bf24ddcb2a2cd401ee3e4704527a">llvm::LLVMContextImpl::ValueMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab025fe91d5f5c6ff951cb7e1f5c2bf64">llvm::Instruction::getAllMetadataOtherThanDebugLoc</a>.</p>

</div>
</div>

### getMetadataImpl() {#a59e5e9e741eead6d5b460cd28c473039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * Value::getMetadataImpl (unsigned KindID)</td>
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

<p>Get metadata for the given kind, if any.</p>


<p>This is an internal function that must only be called after checking that <span class="doxyComputerOutput"><a href="#a1f496e54accb2cbe919fb456cb703f1a">hasMetadata()</a></span> returns true.</p>


<p>Declaration at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 1505 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="#ab3fc0225d8aaf8434026c3573f961f2c">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mdattachments/#af61dae2e0490d044c27c19855884c95f">llvm::MDAttachments::lookup</a>.</p>


<p>Referenced by <a href="#a8c4c0580bdb7ccc8210222c7b22522b7">getMetadata</a> and <a href="#aef569d822dbf572ae71954d6831ce8a9">getMetadata</a>.</p>

</div>
</div>

### getSubclassDataFromValue() {#a05810d77360abad7ef2848184726d872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::Value::getSubclassDataFromValue ()</td>
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



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ad7c657cd513c76f7d328ffdf0fc46f2b">llvm::ConstantExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5e63b88c979e47ac7da57890a45bd2c2">llvm::Function::hasGC</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ad93d1f4325f9ecee231d5f62adf8d74e">llvm::Function::hasLazyArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6a0f6312963ee6fb0969243607174949">llvm::Function::hasPersonalityFn</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a68f94d59950d5fa55b818dca8ea59579">llvm::Function::hasPrefixData</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ae8c01344089090a372ee86f62c07f2bb">llvm::Function::hasPrologueData</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#ae6db8746934e6feae3649a8709fce3cc">llvm::Function::setCallingConv</a>.</p>

</div>
</div>

### hasMetadata() {#a1f496e54accb2cbe919fb456cb703f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Value::hasMetadata ()</td>
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

<p>Return true if this value has any metadata attached to it.</p>

<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a9eb4a52a4675976293ae4f77c982667b">HasMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9c5f771f232bbd4cf6ec230bd78f9174">llvm::Instruction::dropUnknownNonDebugMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aade703948f2fdabdc65868bdf42d3141">llvm::Instruction::getAAMetadata</a>, <a href="#a3d200b1568f70b28ae0eb9bec58d6690">getAllMetadata</a>, <a href="#a8c4c0580bdb7ccc8210222c7b22522b7">getMetadata</a>, <a href="#af580f3203cd4b561487e08bb1fd1d1ae">getMetadata</a>, <a href="#aa8b1bc6f9347dade1932d5e0a0be7904">getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a565f546ad95bd3a9bbe9a1e5040803f0">llvm::Instruction::hasMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a54867ca5f252be2c60176e14e7240391">llvm::Instruction::hasMetadataOtherThanDebugLoc</a>.</p>

</div>
</div>

### setValueSubclassData() {#aae37705b598ef612f698198dc33d6f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Value::setValueSubclassData (unsigned short D)</td>
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



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroyValueName() {#a8546e0e58990802037f15bc6d0ed65a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::destroyValueName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### doRAUW() {#ac86c6a7f4d22622f24ff54f06b56d4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::doRAUW (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * New, ReplaceMetadataUses ReplaceMetaUses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### setNameImpl() {#a228ec544914e8774e6192e13107dfb16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::setNameImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### HasDescriptor {#ae534948f447c9e41a6890b01a8c13f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Value::HasDescriptor</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbase/#a042568b06f355d5c5fcd78dcfb381676">llvm::CallBase::hasDescriptor</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a282fa3e9586425313e0a954c18deee15">llvm::User::User</a>.</p>

</div>
</div>

### HasHungOffUses {#abe68086704afcf3325b6b9b14ca4b625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Value::HasHungOffUses</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/user/#a024c7e10ce431a93ffdb4e5e6401e0be">llvm::User::getOperandList</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a715e8009737f71c4b3d2ea7d2abc33c4">llvm::User::setNumHungOffUseOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a282fa3e9586425313e0a954c18deee15">llvm::User::User</a>.</p>

</div>
</div>

### HasMetadata {#a9eb4a52a4675976293ae4f77c982667b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Value::HasMetadata</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="#aa1b0638c63ba711320b3bb9c69367ed6">addMetadata</a>, <a href="#ad151fceb9a0e77a8a8017d4f68791811">clearMetadata</a>, <a href="#a9d88e21e9caa53945e903fd8c8700b4f">eraseMetadata</a>, <a href="#ab1198eef44b311a7984cfc8fc97fac6d">eraseMetadataIf</a>, <a href="#aef569d822dbf572ae71954d6831ce8a9">getMetadata</a>, <a href="#a1f496e54accb2cbe919fb456cb703f1a">hasMetadata</a>, <a href="#a9542c54e3e3ac516ab7437ae1b98bea8">setMetadata</a> and <a href="#a338590123630c357df6340c38d066572">setMetadata</a>.</p>

</div>
</div>

### HasName {#a174c05075799a1b8213851ca52e9567c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Value::HasName</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="#ad9d88ae321b98d8a3b7f394977ae6d7f">hasName</a>.</p>

</div>
</div>

### IsUsedByMD {#a0e7ed12d09bbe90b2061208177e2a3ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Value::IsUsedByMD</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a7f7861a70cfa57999c2b47e570be2127">llvm::ValueAsMetadata::handleRAUW</a> and <a href="#a6cfd8c0f6033a51197c2ef2b00beeca6">isUsedByMetadata</a>.</p>

</div>
</div>

### NumUserOperands {#ab9ef1cd0d25962bbb4785ae14258ed5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Value::NumUserOperands</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a6b69f170344729a16c5f3bbf89aea84d">llvm::User::getOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a3f3b252f63d32a9a6e05208ce26562bf">llvm::User::getOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">llvm::User::op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a49d32fbcf8305d76cfff528214a4eca0">llvm::User::op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a4824112678b4304314abf4b358750b9b">llvm::GlobalVariable::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a715e8009737f71c4b3d2ea7d2abc33c4">llvm::User::setNumHungOffUseOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a282fa3e9586425313e0a954c18deee15">llvm::User::User</a>.</p>

</div>
</div>

### SubclassOptionalData {#a21e38886795ed32ec28d4eb5dc92b6a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::Value::SubclassOptionalData</td>
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

<p>Hold subclass data that can be dropped.</p>


<p>This member is similar to SubclassData, however it is for holding information which may be used to aid optimization, but which may be cleared to zero without affecting conservative interpretation.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/binaryconstantexpr/#aba5825f2f519f76102cf1b2c6b8a9dc3">llvm::BinaryConstantExpr::BinaryConstantExpr</a>, <a href="#a48790dc28d4007833380faed30c9f44c">clearSubclassOptionalData</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a847cf9e9ee78147bc19b33f21cbba380">llvm::OverflowingBinaryOperator::ConstantExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/possiblyexactoperator/#a847cf9e9ee78147bc19b33f21cbba380">llvm::PossiblyExactOperator::ConstantExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac56dc4e7c9b62727513a77d85a3dc243">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1f815573461be87717cbb7a4ce30f875">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af9fc0080b4accc0b19bfbbc624701e30">llvm::ConstantExpr::getAsInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a8be4fec4d0b6071fb7d7520364fd5378">llvm::FPMathOperator::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a9f19d28f31c79215e0e0190115b0373d">llvm::GEPOperator::getNoWrapFlags</a>, <a href="#a3408c3cf2cef0f378bab40f6660c3341">getRawSubclassOptionalData</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aab577cba8223fe4bb96df5591d49d98a">llvm::ConstantExpr::getWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#adc3e04036467d5c54b04ca43f1ae4e35">llvm::FPMathOperator::hasAllowContract</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a0e4fac852204510c3218d42582b64e3f">llvm::FPMathOperator::hasAllowReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a8cfe8ef5bdce7cb9675d9b948424f5dc">llvm::FPMathOperator::hasAllowReciprocal</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#af033630a6f4a852c95625648b3f893c6">llvm::FPMathOperator::hasApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#ae6d93d933e7e2e0d11075507102317d7">llvm::FPMathOperator::hasNoInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a81877288bdf18216272d7724ecb894c8">llvm::FPMathOperator::hasNoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a7876c618729b8764493aa340b53b574f">llvm::OverflowingBinaryOperator::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/truncinst/#ab8c959a45b2f8891f96bc1242d1d41be">llvm::TruncInst::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#ac25b138a0eb2441346d23183e7ee964f">llvm::FPMathOperator::hasNoSignedZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a95474ea140862464db7ea0580f01eae9">llvm::OverflowingBinaryOperator::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/truncinst/#aedcdbb2c0d352dd9af09e2ee3b33873c">llvm::TruncInst::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a1c3d1a0d43200a0336d30721a12d981b">llvm::ICmpInst::hasSameSign</a>, <a href="#aa48638782e724669238a05c0859b35e0">hasSameSubclassOptionalData</a>, <a href="/web-llvm/docs/api/classes/llvm/possiblydisjointinst/#a2e1698ce76bccc7120910d393edcdd1b">llvm::PossiblyDisjointInst::isDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/possiblyexactoperator/#a661000e67b90152194e0f7e5d665e8c7">llvm::PossiblyExactOperator::isExact</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a0f3e20e19cc93a7cf75fbe6b4b27a728">llvm::FPMathOperator::isFast</a>, <a href="/web-llvm/docs/api/classes/llvm/truncinst/#a0032f5535d126c1dbe75d97fce9993fe">llvm::TruncInst::setHasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/truncinst/#a46376725101a52a504c685a795554d12">llvm::TruncInst::setHasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/possiblydisjointinst/#a1205f1321483c51d9dbc73e3a43de248">llvm::PossiblyDisjointInst::setIsDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#ae01c55fd5d6f0acb9228179a698c3cb3">llvm::GetElementPtrInst::setNoWrapFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a236c918e82e3885748e82eddfa7debcb">llvm::ICmpInst::setSameSign</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasValueHandle {#aaa8f00af7144aac23602a137348d56da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::Value::HasValueHandle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### SubclassData {#a9ed5dfa35f786c0e3bb2100ed095c4c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::Value::SubclassData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hold arbitrary subclass data.</p>


<p>This member is defined by this class, but is not used for anything. Subclasses can use it to hold whatever state they find useful. This field is initialized to zero by the ctor.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### SubclassID {#a61c6b58cf95a021591c108bcbec3eba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char llvm::Value::SubclassID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### UseList {#a312a6480f43c51cc705649c0b69affa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use* llvm::Value::UseList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

### VTy {#aefe036851d3148494382b70456624011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::Value::VTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### dropDroppableUse() {#a44beb55f865ee8a8e42c3a9adeb599e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Value::dropDroppableUse (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
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

<p>Remove the droppable use <span class="doxyComputerOutput">U</span>.</p>

<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a82f896385cac84a2e477159ad31ace74">removeIntrinsicUsers</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### mergeUseLists() {#a7f47772e8b597f1c1f42ab3802bd0891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Compare&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use * llvm::Value::mergeUseLists (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * L, <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * R, Compare Cmp)</td>
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

<p>Merge two lists together.</p>


<p>Merges <span class="doxyComputerOutput">L</span> and <span class="doxyComputerOutput">R</span> using <span class="doxyComputerOutput">Cmp</span>. To enable stable sorts, always pushes "equal" items from L before items from R.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the first element in the list.</p></dd>
</dl>



:::info
<p>Completely ignores <em>Use::Prev</em> (doesn't read, doesn't update).</p>
:::


<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### MaxAlignmentExponent {#ab5941ebb386c8b46a569d1d8dbfe0c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Value::MaxAlignmentExponent = 32</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum alignment for instructions.</p>


<p>This is the greatest alignment value supported by load, store, and alloca instructions, and global values.</p>


<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6e7b79b3933def717c2a0f2fc6fa38e0">llvm::getOrEnforceKnownAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferalignment-cpp/#a8bceeb1a77614890ce9fc9a637c68b2b">inferAlignment</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### MaximumAlignment {#a089e46429cea4cfcd2ba23a6fc6aa676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::Value::MaximumAlignment = 1ULL &lt;&lt; <a href="#ab5941ebb386c8b46a569d1d8dbfe0c8c">MaxAlignmentExponent</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#ad9df6f2ecd1b45e0f481b4f0c297a367">llvm::GEPOperator::getMaxPreservedAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#afb8975f28d8418cad8ea770575736b81">llvm::Attribute::getWithAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af7700655934807d2b707112f79217377">isSafeCheapLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a49b398b1c83ef4d42c8f7756b443f61f">llvm::GlobalObject::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a744c0517c37679d036cc7f381a12f60f">llvm::GlobalObject::setAlignment</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#abe94b0d36f169e52ede6a35d6ac41859">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::updateImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">Value.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
