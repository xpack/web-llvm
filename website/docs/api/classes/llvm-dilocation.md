---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dilocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DILocation` Class Reference

<p>Debug location. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DILocation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> node. <a href="/web-llvm/docs/api/classes/llvm/mdnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e82e98e4dab67aa76d3d3e1cfa2955d">DILocation</a> (LLVMContext &amp;C, StorageType Storage, unsigned Line, unsigned Column, ArrayRef&lt; Metadata * &gt; MDs, bool ImplicitCode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d419a7df224fd438ed0155d099223f">~DILocation</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade41d27dadb1703a49ccaad333f3aa7f">replaceOperandWith</a> (unsigned I, Metadata *New)=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a716e71400d549be3440b62b53b0fb">DEFINE_MDNODE_GET</a> (DILocation,(unsigned Line, unsigned Column, Metadata *Scope, Metadata *InlinedAt=nullptr, bool ImplicitCode=false),(Line, Column, Scope, InlinedAt, ImplicitCode)) DEFINE_MDNODE_GET(DILocation</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7345daa994ad45abb206b757dda7f22">cloneWithDiscriminator</a> (unsigned Discriminator) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a new <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> with updated <span class="doxyComputerOutput">Discriminator</span>. <a href="#ab7345daa994ad45abb206b757dda7f22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a839785a42c232b11d0e1b6b6c0ddba69">cloneWithBaseDiscriminator</a> (unsigned BD) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a new <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> with updated base discriminator <span class="doxyComputerOutput">BD</span>. <a href="#a839785a42c232b11d0e1b6b6c0ddba69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e9ddde31c78bb0a6f70246eac6c648f">getDuplicationFactor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the duplication factor stored in the discriminator, or 1 if no duplication factor (or 0) is encoded. <a href="#a2e9ddde31c78bb0a6f70246eac6c648f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69ab81ed05b68f90320107086d351f6">getCopyIdentifier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the copy identifier stored in the discriminator. <a href="#af69ab81ed05b68f90320107086d351f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959d7d5282de6f6f459425591e7482d7">getBaseDiscriminator</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the base discriminator stored in the discriminator. <a href="#a959d7d5282de6f6f459425591e7482d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae79e1d26012dca43293dea8a19fc002b">cloneByMultiplyingDuplicationFactor</a> (unsigned DF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a new <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> with duplication factor <span class="doxyComputerOutput">DF</span> * current duplication factor encoded in the discriminator. <a href="#ae79e1d26012dca43293dea8a19fc002b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7122152b656f5de604a8ed2a8543f096">getRawScope</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa28470ce55ef213267d4aab516a8c315">getRawInlinedAt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">TempDILocation</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ba5acc685c81b688fcc3aed163b41b">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756c88c4d0458513f7a73da2e904afbf">Line</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c1af7081ee0320462a0211957862000">Column</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned unsigned <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071ee9cfcdddead5c2bf3f1df0d5b60a">Scope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned unsigned <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa339e863ff72c303ea4a5a851e13b77b">InlinedAt</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned unsigned <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca1d5e5c637826fcb4d98b7a59214e0">ImplicitCode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d5bbfbe6fc9f92e22bf16cb1c2dc110">isPseudoProbeDiscriminator</a> (unsigned Discriminator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78cc51c415c7e64b5efe2c8458fbd35a">getMergedLocation</a> (DILocation *LocA, DILocation *LocB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When two instructions are combined into a single instruction we also need to combine the original locations into a single location. <a href="#a78cc51c415c7e64b5efe2c8458fbd35a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a7ce961d5d90ff2fb6c9cee4576e5a">getMergedLocations</a> (ArrayRef&lt; DILocation * &gt; Locs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to combine the vector of locations passed as input in a single one. <a href="#a30a7ce961d5d90ff2fb6c9cee4576e5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9609cd613f944e461d2d2b83c4132c4">getMaskedDiscriminator</a> (unsigned D, unsigned B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the masked discriminator value for an input discrimnator value D (i.e. <a href="#aa9609cd613f944e461d2d2b83c4132c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38851dbdedf659ac8d12924fd5a88641">getBaseDiscriminatorBits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the bits used for base discriminators. <a href="#a38851dbdedf659ac8d12924fd5a88641">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98203aeac2bf8055f829ba0203e77665">getBaseDiscriminatorFromDiscriminator</a> (unsigned D, bool IsFSDiscriminator=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the base discriminator for a given encoded discriminator <span class="doxyComputerOutput">D</span>. <a href="#a98203aeac2bf8055f829ba0203e77665">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6878171e0bb76ddb464e30b5bad4952f">encodeDiscriminator</a> (unsigned BD, unsigned DF, unsigned CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Raw encoding of the discriminator. <a href="#a6878171e0bb76ddb464e30b5bad4952f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71afd3d2ac28f17a123c7a5e37822659">decodeDiscriminator</a> (unsigned D, unsigned &amp;BD, unsigned &amp;DF, unsigned &amp;CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Raw decoder for values in an encoded discriminator D. <a href="#a71afd3d2ac28f17a123c7a5e37822659">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19bf03e247a0e281b5f8179dc18fdb7f">getDuplicationFactorFromDiscriminator</a> (unsigned D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the duplication factor for a given encoded discriminator <span class="doxyComputerOutput">D</span>, or 1 if no value or 0 is encoded. <a href="#a19bf03e247a0e281b5f8179dc18fdb7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc03af4abcfe8d196600e2842ff416e6">getCopyIdentifierFromDiscriminator</a> (unsigned D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the copy identifier for a given encoded discriminator <span class="doxyComputerOutput">D</span>. <a href="#abc03af4abcfe8d196600e2842ff416e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af599fdffda00cb0c8f6d243a30d60d88">classof</a> (const Metadata *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213a5200cb4972699148b05e78616e43">getImpl</a> (LLVMContext &amp;Context, unsigned Line, unsigned Column, Metadata *Scope, Metadata *InlinedAt, bool ImplicitCode, StorageType Storage, bool ShouldCreate=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5672c1b7f97bac89d6e758a628bd16">getImpl</a> (LLVMContext &amp;Context, unsigned Line, unsigned Column, DILocalScope *Scope, DILocation *InlinedAt, bool ImplicitCode, StorageType Storage, bool ShouldCreate=true)</td>
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

<p>Debug location.</p>


<p>A debug location in source code, used for debug info and otherwise.</p>


<p>Uses the SubclassData1, SubclassData16 and SubclassData32 <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> slots.</p>


<p>Definition at line 1988 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


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


<p>Definition at line 1989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


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


<p>Definition at line 1990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9c1af7081ee0320462a0211957862000">Column</a>, <a href="#a6ca1d5e5c637826fcb4d98b7a59214e0">ImplicitCode</a>, <a href="#a756c88c4d0458513f7a73da2e904afbf">Line</a>, <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/metadata/#a8265bf29997e9e49d47a38a762d4bb0f">llvm::Metadata::Storage</a>.</p>


<p>Referenced by <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DILocation() {#a9e82e98e4dab67aa76d3d3e1cfa2955d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation::DILocation (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, unsigned Line, unsigned Column, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; MDs, bool ImplicitCode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~DILocation() {#af1d419a7df224fd438ed0155d099223f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DILocation::~DILocation ()</td>
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



<p>Definition at line 1994 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cloneByMultiplyingDuplicationFactor() {#ae79e1d26012dca43293dea8a19fc002b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; const DILocation * &gt; llvm::DILocation::cloneByMultiplyingDuplicationFactor (unsigned DF)</td>
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

<p>Returns a new <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> with duplication factor <span class="doxyComputerOutput">DF</span> * current duplication factor encoded in the discriminator.</p>


<p>The current duplication factor is as defined by <a href="#a2e9ddde31c78bb0a6f70246eac6c648f">getDuplicationFactor()</a>. Returns std::nullopt if encoding failed.</p>


<p>Definition at line 2150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab7345daa994ad45abb206b757dda7f22">cloneWithDiscriminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61cf315897c96016607a2b8d5916a64d">llvm::EnableFSDiscriminator</a>, <a href="#a6878171e0bb76ddb464e30b5bad4952f">encodeDiscriminator</a>, <a href="#a959d7d5282de6f6f459425591e7482d7">getBaseDiscriminator</a>, <a href="#af69ab81ed05b68f90320107086d351f6">getCopyIdentifier</a>, <a href="#a2e9ddde31c78bb0a6f70246eac6c648f">getDuplicationFactor</a> and <a href="#a1d5bbfbe6fc9f92e22bf16cb1c2dc110">isPseudoProbeDiscriminator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#ae69fb3f4bb10e284f6e2090ff13a7c61">llvm::VPTransformState::setDebugLocFrom</a>.</p>

</div>
</div>

### cloneWithBaseDiscriminator() {#a839785a42c232b11d0e1b6b6c0ddba69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; const DILocation * &gt; llvm::DILocation::cloneWithBaseDiscriminator (unsigned BD)</td>
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

<p>Returns a new <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> with updated base discriminator <span class="doxyComputerOutput">BD</span>.</p>


<p>Only the base discriminator is set in the new <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a>, the other encoded values are elided. If the discriminator cannot be encoded, the function returns std::nullopt.</p>


<p>Definition at line 2133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#ab7345daa994ad45abb206b757dda7f22">cloneWithDiscriminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a71afd3d2ac28f17a123c7a5e37822659">decodeDiscriminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61cf315897c96016607a2b8d5916a64d">llvm::EnableFSDiscriminator</a>, <a href="#a6878171e0bb76ddb464e30b5bad4952f">encodeDiscriminator</a> and <a href="#a959d7d5282de6f6f459425591e7482d7">getBaseDiscriminator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/adddiscriminators-cpp/#a6201294406f0d7ffae87b86d867045f8">addDiscriminators</a>.</p>

</div>
</div>

### cloneWithDiscriminator() {#ab7345daa994ad45abb206b757dda7f22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DILocation * llvm::DILocation::cloneWithDiscriminator (unsigned Discriminator)</td>
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

<p>Returns a new <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> with updated <span class="doxyComputerOutput">Discriminator</span>.</p>

<p>Definition at line 2126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a> and <a href="#a071ee9cfcdddead5c2bf3f1df0d5b60a">Scope</a>.</p>


<p>Referenced by <a href="#ae79e1d26012dca43293dea8a19fc002b">cloneByMultiplyingDuplicationFactor</a>, <a href="#a839785a42c232b11d0e1b6b6c0ddba69">cloneWithBaseDiscriminator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>.</p>

</div>
</div>

### DEFINE\_MDNODE\_GET() {#a34a716e71400d549be3440b62b53b0fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DILocation::DEFINE_MDNODE_GET (<a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a>, (unsigned <a href="#a756c88c4d0458513f7a73da2e904afbf">Line</a>, unsigned <a href="#a9c1af7081ee0320462a0211957862000">Column</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a071ee9cfcdddead5c2bf3f1df0d5b60a">Scope</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#aa339e863ff72c303ea4a5a851e13b77b">InlinedAt</a>=nullptr, bool <a href="#a6ca1d5e5c637826fcb4d98b7a59214e0">ImplicitCode</a>=false), (<a href="#a756c88c4d0458513f7a73da2e904afbf">Line</a>, <a href="#a9c1af7081ee0320462a0211957862000">Column</a>, <a href="#a071ee9cfcdddead5c2bf3f1df0d5b60a">Scope</a>, <a href="#aa339e863ff72c303ea4a5a851e13b77b">InlinedAt</a>, <a href="#a6ca1d5e5c637826fcb4d98b7a59214e0">ImplicitCode</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#a9c1af7081ee0320462a0211957862000">Column</a>, <a href="#a6ca1d5e5c637826fcb4d98b7a59214e0">ImplicitCode</a>, <a href="#aa339e863ff72c303ea4a5a851e13b77b">InlinedAt</a>, <a href="#a756c88c4d0458513f7a73da2e904afbf">Line</a> and <a href="#a071ee9cfcdddead5c2bf3f1df0d5b60a">Scope</a>.</p>

</div>
</div>

### getBaseDiscriminator() {#a959d7d5282de6f6f459425591e7482d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DILocation::getBaseDiscriminator ()</td>
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

<p>Returns the base discriminator stored in the discriminator.</p>

<p>Definition at line 2143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61cf315897c96016607a2b8d5916a64d">llvm::EnableFSDiscriminator</a> and <a href="#a98203aeac2bf8055f829ba0203e77665">getBaseDiscriminatorFromDiscriminator</a>.</p>


<p>Referenced by <a href="#ae79e1d26012dca43293dea8a19fc002b">cloneByMultiplyingDuplicationFactor</a>, <a href="#a839785a42c232b11d0e1b6b6c0ddba69">cloneWithBaseDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aeea4c49a1040f9305f6a09d7d7815544">llvm::sampleprof::FunctionSamples::getCallSiteIdentifier</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; FT &gt;::getInstWeightImpl</a>.</p>

</div>
</div>

### getCopyIdentifier() {#af69ab81ed05b68f90320107086d351f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DILocation::getCopyIdentifier ()</td>
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

<p>Returns the copy identifier stored in the discriminator.</p>

<p>Definition at line 2140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#abc03af4abcfe8d196600e2842ff416e6">getCopyIdentifierFromDiscriminator</a>.</p>


<p>Referenced by <a href="#ae79e1d26012dca43293dea8a19fc002b">cloneByMultiplyingDuplicationFactor</a>.</p>

</div>
</div>

### getDuplicationFactor() {#a2e9ddde31c78bb0a6f70246eac6c648f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DILocation::getDuplicationFactor ()</td>
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

<p>Returns the duplication factor stored in the discriminator, or 1 if no duplication factor (or 0) is encoded.</p>

<p>Definition at line 2137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#a19bf03e247a0e281b5f8179dc18fdb7f">getDuplicationFactorFromDiscriminator</a>.</p>


<p>Referenced by <a href="#ae79e1d26012dca43293dea8a19fc002b">cloneByMultiplyingDuplicationFactor</a>.</p>

</div>
</div>

### getRawInlinedAt() {#aa28470ce55ef213267d4aab516a8c315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DILocation::getRawInlinedAt ()</td>
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



<p>Definition at line 2247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>

</div>
</div>

### getRawScope() {#a7122152b656f5de604a8ed2a8543f096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DILocation::getRawScope ()</td>
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



<p>Definition at line 2246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>

</div>
</div>

### replaceOperandWith() {#ade41d27dadb1703a49ccaad333f3aa7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DILocation::replaceOperandWith (unsigned I, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * New)</td>
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



<p>Definition at line 2018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneImpl() {#a01ba5acc685c81b688fcc3aed163b41b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempDILocation llvm::DILocation::cloneImpl ()</td>
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



<p>Definition at line 2009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Column {#a9c1af7081ee0320462a0211957862000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned unsigned llvm::DILocation::Column</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a34a716e71400d549be3440b62b53b0fb">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### ImplicitCode {#a6ca1d5e5c637826fcb4d98b7a59214e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned unsigned DILocalScope DILocation bool llvm::DILocation::ImplicitCode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a34a716e71400d549be3440b62b53b0fb">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### InlinedAt {#aa339e863ff72c303ea4a5a851e13b77b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned unsigned DILocalScope DILocation* llvm::DILocation::InlinedAt = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a34a716e71400d549be3440b62b53b0fb">DEFINE_MDNODE_GET</a> and <a href="#a78cc51c415c7e64b5efe2c8458fbd35a">getMergedLocation</a>.</p>

</div>
</div>

### Line {#a756c88c4d0458513f7a73da2e904afbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DILocation::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a34a716e71400d549be3440b62b53b0fb">DEFINE_MDNODE_GET</a>, <a href="#a78cc51c415c7e64b5efe2c8458fbd35a">getMergedLocation</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Scope {#a071ee9cfcdddead5c2bf3f1df0d5b60a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned unsigned DILocalScope* llvm::DILocation::Scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#ab7345daa994ad45abb206b757dda7f22">cloneWithDiscriminator</a>, <a href="#a34a716e71400d549be3440b62b53b0fb">DEFINE_MDNODE_GET</a> and <a href="#a78cc51c415c7e64b5efe2c8458fbd35a">getMergedLocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#af599fdffda00cb0c8f6d243a30d60d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DILocation::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Definition at line 2253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

### decodeDiscriminator() {#a71afd3d2ac28f17a123c7a5e37822659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DILocation::decodeDiscriminator (unsigned D, unsigned &amp; BD, unsigned &amp; DF, unsigned &amp; CI)</td>
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

<p>Raw decoder for values in an encoded discriminator D.</p>

<p>Declaration at line 2225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h/#aae8162a5c7f4095424c29f4022786702">getNextComponentInDiscriminator</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h/#afcbeec35a76bf40fd2f359887365d593">getUnsignedFromPrefixEncoding</a>.</p>


<p>Referenced by <a href="#a839785a42c232b11d0e1b6b6c0ddba69">cloneWithBaseDiscriminator</a> and <a href="#a6878171e0bb76ddb464e30b5bad4952f">encodeDiscriminator</a>.</p>

</div>
</div>

### encodeDiscriminator() {#a6878171e0bb76ddb464e30b5bad4952f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; DILocation::encodeDiscriminator (unsigned BD, unsigned DF, unsigned CI)</td>
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

<p>Raw encoding of the discriminator.</p>


<p>APIs such as cloneWithDuplicationFactor have certain special case behavior (e.g. treating empty duplication factor as the value '1'). This API, in conjunction with cloneWithDiscriminator, may be used to encode the raw values provided.</p>


<p><span class="doxyComputerOutput">BD:</span> base discriminator <span class="doxyComputerOutput">DF:</span> duplication factor <span class="doxyComputerOutput">CI:</span> copy index</p>


<p>The return is std::nullopt if the values cannot be encoded in 32 bits - for example, values for BD or DF larger than 12 bits. Otherwise, the return is the encoded value.</p>


<p>Declaration at line 2221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a71afd3d2ac28f17a123c7a5e37822659">decodeDiscriminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h/#aaa01067fc8646aefc70f8e0d37abec00">encodeComponent</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h/#a4e7d93c6d2b31e7fb8fae321702b88f7">encodingBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ae79e1d26012dca43293dea8a19fc002b">cloneByMultiplyingDuplicationFactor</a> and <a href="#a839785a42c232b11d0e1b6b6c0ddba69">cloneWithBaseDiscriminator</a>.</p>

</div>
</div>

### getBaseDiscriminatorBits() {#a38851dbdedf659ac8d12924fd5a88641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DILocation::getBaseDiscriminatorBits ()</td>
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

<p>Return the bits used for base discriminators.</p>

<p>Definition at line 2182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8d300f3057d74f34e6dc0cc14eb6400c">llvm::getBaseFSBitEnd</a>.</p>


<p>Referenced by <a href="#a98203aeac2bf8055f829ba0203e77665">getBaseDiscriminatorFromDiscriminator</a>.</p>

</div>
</div>

### getBaseDiscriminatorFromDiscriminator() {#a98203aeac2bf8055f829ba0203e77665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DILocation::getBaseDiscriminatorFromDiscriminator (unsigned D, bool IsFSDiscriminator=false)</td>
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

<p>Returns the base discriminator for a given encoded discriminator <span class="doxyComputerOutput">D</span>.</p>

<p>Definition at line 2186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/structs/llvm/pseudoprobedwarfdiscriminator/#ad0c37806bfdb6415dbe3866307f6716c">llvm::PseudoProbeDwarfDiscriminator::extractDwarfBaseDiscriminator</a>, <a href="/web-llvm/docs/api/structs/llvm/pseudoprobedwarfdiscriminator/#a5db4061b62e740850ad71806b1dbd60e">llvm::PseudoProbeDwarfDiscriminator::extractProbeIndex</a>, <a href="#a38851dbdedf659ac8d12924fd5a88641">getBaseDiscriminatorBits</a>, <a href="#aa9609cd613f944e461d2d2b83c4132c4">getMaskedDiscriminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h/#afcbeec35a76bf40fd2f359887365d593">getUnsignedFromPrefixEncoding</a> and <a href="#a1d5bbfbe6fc9f92e22bf16cb1c2dc110">isPseudoProbeDiscriminator</a>.</p>


<p>Referenced by <a href="#a959d7d5282de6f6f459425591e7482d7">getBaseDiscriminator</a>.</p>

</div>
</div>

### getCopyIdentifierFromDiscriminator() {#abc03af4abcfe8d196600e2842ff416e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DILocation::getCopyIdentifierFromDiscriminator (unsigned D)</td>
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

<p>Returns the copy identifier for a given encoded discriminator <span class="doxyComputerOutput">D</span>.</p>

<p>Definition at line 2241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h/#aae8162a5c7f4095424c29f4022786702">getNextComponentInDiscriminator</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h/#afcbeec35a76bf40fd2f359887365d593">getUnsignedFromPrefixEncoding</a>.</p>


<p>Referenced by <a href="#af69ab81ed05b68f90320107086d351f6">getCopyIdentifier</a>.</p>

</div>
</div>

### getDuplicationFactorFromDiscriminator() {#a19bf03e247a0e281b5f8179dc18fdb7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DILocation::getDuplicationFactorFromDiscriminator (unsigned D)</td>
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

<p>Returns the duplication factor for a given encoded discriminator <span class="doxyComputerOutput">D</span>, or 1 if no value or 0 is encoded.</p>

<p>Definition at line 2230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61cf315897c96016607a2b8d5916a64d">llvm::EnableFSDiscriminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h/#aae8162a5c7f4095424c29f4022786702">getNextComponentInDiscriminator</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h/#afcbeec35a76bf40fd2f359887365d593">getUnsignedFromPrefixEncoding</a>.</p>


<p>Referenced by <a href="#a2e9ddde31c78bb0a6f70246eac6c648f">getDuplicationFactor</a>.</p>

</div>
</div>

### getMaskedDiscriminator() {#aa9609cd613f944e461d2d2b83c4132c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DILocation::getMaskedDiscriminator (unsigned D, unsigned B)</td>
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

<p>Return the masked discriminator value for an input discrimnator value D (i.e.</p>


<p>zero out the (B+1)-th and above bits for D (B is 0-base).</p>


<p>Definition at line 2177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa860d116fc20fde892f7485b706f9139">llvm::getN1Bits</a>.</p>


<p>Referenced by <a href="#a98203aeac2bf8055f829ba0203e77665">getBaseDiscriminatorFromDiscriminator</a>.</p>

</div>
</div>

### getMergedLocation() {#a78cc51c415c7e64b5efe2c8458fbd35a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation * DILocation::getMergedLocation (<a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * LocA, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * LocB)</td>
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

<p>When two instructions are combined into a single instruction we also need to combine the original locations into a single location.</p>


<p>When the locations are the same we can use either location. When they differ, we need a third location which is distinct from either. If they share a common scope, use this scope and compare the line/column pair of the locations with the common scope:</p>


<ul class="doxyList ">
<li>if both match, keep the line and column;</li>
<li>if only the line number matches, keep the line and set the column as 0;</li>
<li>otherwise set line and column as 0. If they do not share a common scope the location is ambiguous and can't be represented in a line entry. In this case, set line and column as 0 and use the scope of any location.</li>
</ul>

<p><span class="doxyComputerOutput">LocA</span> <span class="doxyComputerOutput">LocB:</span> The locations to be merged.</p>


<p>Declaration at line 2166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa339e863ff72c303ea4a5a851e13b77b">InlinedAt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a>, <a href="#a756c88c4d0458513f7a73da2e904afbf">Line</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#a071ee9cfcdddead5c2bf3f1df0d5b60a">Scope</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1a245b31aced1374f28f45d2b297f402">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::try_emplace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae88ca601f663c55cafa95cf742076aad">llvm::Instruction::applyMergedLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad81901d0d8b768b240e78bf357999f34">llvm::MachineBasicBlock::findBranchDebugLoc</a>, <a href="#a30a7ce961d5d90ff2fb6c9cee4576e5a">getMergedLocations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a7fae42d42333d13848fe4d545dc50049">mergeDILocations</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a1e64ed92fc7b343fa59c28105e16b794">performSink</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#af4696dcc1ada21996da960c711f26ee1">llvm::LegalizationArtifactCombiner::tryCombineAnyExt</a>.</p>

</div>
</div>

### getMergedLocations() {#a30a7ce961d5d90ff2fb6c9cee4576e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation * DILocation::getMergedLocations (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt; Locs)</td>
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

<p>Try to combine the vector of locations passed as input in a single one.</p>


<p>This function applies <a href="#a78cc51c415c7e64b5efe2c8458fbd35a">getMergedLocation()</a> repeatedly left-to-right.</p>


<p><span class="doxyComputerOutput">Locs:</span> The locations to be merged.</p>


<p>Declaration at line 2172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#a78cc51c415c7e64b5efe2c8458fbd35a">getMergedLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>.</p>

</div>
</div>

### isPseudoProbeDiscriminator() {#a1d5bbfbe6fc9f92e22bf16cb1c2dc110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DILocation::isPseudoProbeDiscriminator (unsigned Discriminator)</td>
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



<p>Definition at line 2121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#ae79e1d26012dca43293dea8a19fc002b">cloneByMultiplyingDuplicationFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a202ea3964f0d9dd2bf8bf07cb89e0fb0">llvm::extractProbeFromDiscriminator</a>, <a href="#a98203aeac2bf8055f829ba0203e77665">getBaseDiscriminatorFromDiscriminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a35bb2baa976d7716a9752ad544e8134f">anonymous{SampleProfile.cpp}::SampleProfileLoader::removePseudoProbeInstsDiscriminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#acf62b36239ac36c52ffc9a58a18332ab">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getImpl() {#a213a5200cb4972699148b05e78616e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation * DILocation::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Line, unsigned Column, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * InlinedAt, bool ImplicitCode, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 1996 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

</div>
</div>

### getImpl() {#a1f5672c1b7f97bac89d6e758a628bd16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation * llvm::DILocation::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Line, unsigned Column, <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * InlinedAt, bool ImplicitCode, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 2000 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

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
